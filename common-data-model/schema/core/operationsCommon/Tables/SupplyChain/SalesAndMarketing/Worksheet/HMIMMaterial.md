---
title: HMIMMaterial - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 5/5/2020
ms.author: nebanfic
---

# Hazardous materials

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Worksheet/HMIMMaterial.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[HMIMMaterial/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Hazardous materials</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="HMIMMaterial.md" target="_blank">Worksheet/HMIMMaterial</a>|
|[MaterialCode](#MaterialCode)||<a href="HMIMMaterial.md" target="_blank">Worksheet/HMIMMaterial</a>|
|[MaterialDescription](#MaterialDescription)||<a href="HMIMMaterial.md" target="_blank">Worksheet/HMIMMaterial</a>|
|[RegCode](#RegCode)||<a href="HMIMMaterial.md" target="_blank">Worksheet/HMIMMaterial</a>|
|[IdentificationCode](#IdentificationCode)||<a href="HMIMMaterial.md" target="_blank">Worksheet/HMIMMaterial</a>|
|[PackingGroupCode](#PackingGroupCode)||<a href="HMIMMaterial.md" target="_blank">Worksheet/HMIMMaterial</a>|
|[ShippingPrintText](#ShippingPrintText)||<a href="HMIMMaterial.md" target="_blank">Worksheet/HMIMMaterial</a>|
|[UnitOfMeasure](#UnitOfMeasure)||<a href="HMIMMaterial.md" target="_blank">Worksheet/HMIMMaterial</a>|
|[ClassCode](#ClassCode)||<a href="HMIMMaterial.md" target="_blank">Worksheet/HMIMMaterial</a>|
|[DivisionCode](#DivisionCode)||<a href="HMIMMaterial.md" target="_blank">Worksheet/HMIMMaterial</a>|
|[Multiplier](#Multiplier)||<a href="HMIMMaterial.md" target="_blank">Worksheet/HMIMMaterial</a>|
|[TechnicalNameCode](#TechnicalNameCode)||<a href="HMIMMaterial.md" target="_blank">Worksheet/HMIMMaterial</a>|
|[TransportCategoryCode](#TransportCategoryCode)||<a href="HMIMMaterial.md" target="_blank">Worksheet/HMIMMaterial</a>|
|[MarinePollutant](#MarinePollutant)||<a href="HMIMMaterial.md" target="_blank">Worksheet/HMIMMaterial</a>|
|[EnviroDangerous](#EnviroDangerous)||<a href="HMIMMaterial.md" target="_blank">Worksheet/HMIMMaterial</a>|
|[LimitedQty](#LimitedQty)||<a href="HMIMMaterial.md" target="_blank">Worksheet/HMIMMaterial</a>|
|[TunnelCode](#TunnelCode)||<a href="HMIMMaterial.md" target="_blank">Worksheet/HMIMMaterial</a>|
|[LabelCode](#LabelCode)||<a href="HMIMMaterial.md" target="_blank">Worksheet/HMIMMaterial</a>|
|[NOS](#NOS)||<a href="HMIMMaterial.md" target="_blank">Worksheet/HMIMMaterial</a>|
|[StowageCode](#StowageCode)||<a href="HMIMMaterial.md" target="_blank">Worksheet/HMIMMaterial</a>|
|[IATAStar](#IATAStar)||<a href="HMIMMaterial.md" target="_blank">Worksheet/HMIMMaterial</a>|
|[EMSCode](#EMSCode)||<a href="HMIMMaterial.md" target="_blank">Worksheet/HMIMMaterial</a>|
|[AirType](#AirType)||<a href="HMIMMaterial.md" target="_blank">Worksheet/HMIMMaterial</a>|
|[PackInstCodePassenger](#PackInstCodePassenger)||<a href="HMIMMaterial.md" target="_blank">Worksheet/HMIMMaterial</a>|
|[PackInstCodeCargo](#PackInstCodeCargo)||<a href="HMIMMaterial.md" target="_blank">Worksheet/HMIMMaterial</a>|
|[Relationship_HMIMRegulationRelationshipId](#Relationship_HMIMRegulationRelationshipId)||<a href="HMIMMaterial.md" target="_blank">Worksheet/HMIMMaterial</a>|
|[Relationship_HMIMIdentificationRelationshipId](#Relationship_HMIMIdentificationRelationshipId)||<a href="HMIMMaterial.md" target="_blank">Worksheet/HMIMMaterial</a>|
|[Relationship_HMIMPackingGroupRelationshipId](#Relationship_HMIMPackingGroupRelationshipId)||<a href="HMIMMaterial.md" target="_blank">Worksheet/HMIMMaterial</a>|
|[Relationship_HMIMClassRelationshipId](#Relationship_HMIMClassRelationshipId)||<a href="HMIMMaterial.md" target="_blank">Worksheet/HMIMMaterial</a>|
|[Relationship_HMIMDivisionRelationshipId](#Relationship_HMIMDivisionRelationshipId)||<a href="HMIMMaterial.md" target="_blank">Worksheet/HMIMMaterial</a>|
|[Relationship_HMIMTechnicalNameRelationshipId](#Relationship_HMIMTechnicalNameRelationshipId)||<a href="HMIMMaterial.md" target="_blank">Worksheet/HMIMMaterial</a>|
|[Relationship_HMIMTransportCategoryRelationshipId](#Relationship_HMIMTransportCategoryRelationshipId)||<a href="HMIMMaterial.md" target="_blank">Worksheet/HMIMMaterial</a>|
|[Relationship_HMIMTunnelRelationshipId](#Relationship_HMIMTunnelRelationshipId)||<a href="HMIMMaterial.md" target="_blank">Worksheet/HMIMMaterial</a>|
|[Relationship_HMIMStowageRelationshipId](#Relationship_HMIMStowageRelationshipId)||<a href="HMIMMaterial.md" target="_blank">Worksheet/HMIMMaterial</a>|
|[Relationship_HMIMEMSRelationshipId](#Relationship_HMIMEMSRelationshipId)||<a href="HMIMMaterial.md" target="_blank">Worksheet/HMIMMaterial</a>|
|[Relationship_PassengerHMIMPackingInstructionRelationshipId](#Relationship_PassengerHMIMPackingInstructionRelationshipId)||<a href="HMIMMaterial.md" target="_blank">Worksheet/HMIMMaterial</a>|
|[Relationship_CargoHMIMPackingInstructionRelationshipId](#Relationship_CargoHMIMPackingInstructionRelationshipId)||<a href="HMIMMaterial.md" target="_blank">Worksheet/HMIMMaterial</a>|
|[Relationship_HMIMLabelRelationshipId](#Relationship_HMIMLabelRelationshipId)||<a href="HMIMMaterial.md" target="_blank">Worksheet/HMIMMaterial</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Worksheet/HMIMMaterial (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[HMIMMaterial/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#MaterialCode name="MaterialCode">MaterialCode</a>

First included in: Worksheet/HMIMMaterial (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaterialCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaterialDescription name="MaterialDescription">MaterialDescription</a>

First included in: Worksheet/HMIMMaterial (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Proper shipping name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaterialDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Proper shipping name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RegCode name="RegCode">RegCode</a>

First included in: Worksheet/HMIMMaterial (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RegCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IdentificationCode name="IdentificationCode">IdentificationCode</a>

First included in: Worksheet/HMIMMaterial (this entity)  

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

### <a href=#PackingGroupCode name="PackingGroupCode">PackingGroupCode</a>

First included in: Worksheet/HMIMMaterial (this entity)  

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

### <a href=#ShippingPrintText name="ShippingPrintText">ShippingPrintText</a>

First included in: Worksheet/HMIMMaterial (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Shipping print text</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingPrintText attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shipping print text</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnitOfMeasure name="UnitOfMeasure">UnitOfMeasure</a>

First included in: Worksheet/HMIMMaterial (this entity)  

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

### <a href=#ClassCode name="ClassCode">ClassCode</a>

First included in: Worksheet/HMIMMaterial (this entity)  

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

### <a href=#DivisionCode name="DivisionCode">DivisionCode</a>

First included in: Worksheet/HMIMMaterial (this entity)  

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

### <a href=#Multiplier name="Multiplier">Multiplier</a>

First included in: Worksheet/HMIMMaterial (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Multiplier</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Multiplier attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Multiplier</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TechnicalNameCode name="TechnicalNameCode">TechnicalNameCode</a>

First included in: Worksheet/HMIMMaterial (this entity)  

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

### <a href=#TransportCategoryCode name="TransportCategoryCode">TransportCategoryCode</a>

First included in: Worksheet/HMIMMaterial (this entity)  

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

### <a href=#MarinePollutant name="MarinePollutant">MarinePollutant</a>

First included in: Worksheet/HMIMMaterial (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MarinePollutant attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#EnviroDangerous name="EnviroDangerous">EnviroDangerous</a>

First included in: Worksheet/HMIMMaterial (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnviroDangerous attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#LimitedQty name="LimitedQty">LimitedQty</a>

First included in: Worksheet/HMIMMaterial (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LimitedQty attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TunnelCode name="TunnelCode">TunnelCode</a>

First included in: Worksheet/HMIMMaterial (this entity)  

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

### <a href=#LabelCode name="LabelCode">LabelCode</a>

First included in: Worksheet/HMIMMaterial (this entity)  

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

### <a href=#NOS name="NOS">NOS</a>

First included in: Worksheet/HMIMMaterial (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NOS attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#StowageCode name="StowageCode">StowageCode</a>

First included in: Worksheet/HMIMMaterial (this entity)  

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

### <a href=#IATAStar name="IATAStar">IATAStar</a>

First included in: Worksheet/HMIMMaterial (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IATAStar attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#EMSCode name="EMSCode">EMSCode</a>

First included in: Worksheet/HMIMMaterial (this entity)  

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

### <a href=#AirType name="AirType">AirType</a>

First included in: Worksheet/HMIMMaterial (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AirType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PackInstCodePassenger name="PackInstCodePassenger">PackInstCodePassenger</a>

First included in: Worksheet/HMIMMaterial (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Packing - passenger and cargo aircraft</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackInstCodePassenger attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Packing - passenger and cargo aircraft</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PackInstCodeCargo name="PackInstCodeCargo">PackInstCodeCargo</a>

First included in: Worksheet/HMIMMaterial (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Packing - cargo aircraft only</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackInstCodeCargo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Packing - cargo aircraft only</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_HMIMRegulationRelationshipId name="Relationship_HMIMRegulationRelationshipId">Relationship_HMIMRegulationRelationshipId</a>

First included in: Worksheet/HMIMMaterial (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_HMIMRegulationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/HMIMRegulation.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Main/HMIMRegulation.cdm.json/HMIMRegulation</a></td><td><a href="../Main/HMIMRegulation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_HMIMIdentificationRelationshipId name="Relationship_HMIMIdentificationRelationshipId">Relationship_HMIMIdentificationRelationshipId</a>

First included in: Worksheet/HMIMMaterial (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_HMIMIdentificationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/HMIMIdentification.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Main/HMIMIdentification.cdm.json/HMIMIdentification</a></td><td><a href="../Main/HMIMIdentification.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_HMIMPackingGroupRelationshipId name="Relationship_HMIMPackingGroupRelationshipId">Relationship_HMIMPackingGroupRelationshipId</a>

First included in: Worksheet/HMIMMaterial (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_HMIMPackingGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/HMIMPackingGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Group/HMIMPackingGroup.cdm.json/HMIMPackingGroup</a></td><td><a href="../Group/HMIMPackingGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_HMIMClassRelationshipId name="Relationship_HMIMClassRelationshipId">Relationship_HMIMClassRelationshipId</a>

First included in: Worksheet/HMIMMaterial (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_HMIMClassRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/HMIMClass.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Main/HMIMClass.cdm.json/HMIMClass</a></td><td><a href="../Main/HMIMClass.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_HMIMDivisionRelationshipId name="Relationship_HMIMDivisionRelationshipId">Relationship_HMIMDivisionRelationshipId</a>

First included in: Worksheet/HMIMMaterial (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_HMIMDivisionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/HMIMDivision.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Main/HMIMDivision.cdm.json/HMIMDivision</a></td><td><a href="../Main/HMIMDivision.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_HMIMTechnicalNameRelationshipId name="Relationship_HMIMTechnicalNameRelationshipId">Relationship_HMIMTechnicalNameRelationshipId</a>

First included in: Worksheet/HMIMMaterial (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_HMIMTechnicalNameRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/HMIMTechnicalName.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Main/HMIMTechnicalName.cdm.json/HMIMTechnicalName</a></td><td><a href="../Main/HMIMTechnicalName.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_HMIMTransportCategoryRelationshipId name="Relationship_HMIMTransportCategoryRelationshipId">Relationship_HMIMTransportCategoryRelationshipId</a>

First included in: Worksheet/HMIMMaterial (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_HMIMTransportCategoryRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/HMIMTransportCategory.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Main/HMIMTransportCategory.cdm.json/HMIMTransportCategory</a></td><td><a href="../Main/HMIMTransportCategory.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_HMIMTunnelRelationshipId name="Relationship_HMIMTunnelRelationshipId">Relationship_HMIMTunnelRelationshipId</a>

First included in: Worksheet/HMIMMaterial (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_HMIMTunnelRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/HMIMTunnel.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Main/HMIMTunnel.cdm.json/HMIMTunnel</a></td><td><a href="../Main/HMIMTunnel.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_HMIMStowageRelationshipId name="Relationship_HMIMStowageRelationshipId">Relationship_HMIMStowageRelationshipId</a>

First included in: Worksheet/HMIMMaterial (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_HMIMStowageRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/HMIMStowage.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Main/HMIMStowage.cdm.json/HMIMStowage</a></td><td><a href="../Main/HMIMStowage.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_HMIMEMSRelationshipId name="Relationship_HMIMEMSRelationshipId">Relationship_HMIMEMSRelationshipId</a>

First included in: Worksheet/HMIMMaterial (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_HMIMEMSRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/HMIMEMS.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Main/HMIMEMS.cdm.json/HMIMEMS</a></td><td><a href="../Main/HMIMEMS.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PassengerHMIMPackingInstructionRelationshipId name="Relationship_PassengerHMIMPackingInstructionRelationshipId">Relationship_PassengerHMIMPackingInstructionRelationshipId</a>

First included in: Worksheet/HMIMMaterial (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PassengerHMIMPackingInstructionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/HMIMPackingInstruction.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Main/HMIMPackingInstruction.cdm.json/HMIMPackingInstruction</a></td><td><a href="../Main/HMIMPackingInstruction.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CargoHMIMPackingInstructionRelationshipId name="Relationship_CargoHMIMPackingInstructionRelationshipId">Relationship_CargoHMIMPackingInstructionRelationshipId</a>

First included in: Worksheet/HMIMMaterial (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CargoHMIMPackingInstructionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/HMIMPackingInstruction.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Main/HMIMPackingInstruction.cdm.json/HMIMPackingInstruction</a></td><td><a href="../Main/HMIMPackingInstruction.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_HMIMLabelRelationshipId name="Relationship_HMIMLabelRelationshipId">Relationship_HMIMLabelRelationshipId</a>

First included in: Worksheet/HMIMMaterial (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_HMIMLabelRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/HMIMLabel.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Main/HMIMLabel.cdm.json/HMIMLabel</a></td><td><a href="../Main/HMIMLabel.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
