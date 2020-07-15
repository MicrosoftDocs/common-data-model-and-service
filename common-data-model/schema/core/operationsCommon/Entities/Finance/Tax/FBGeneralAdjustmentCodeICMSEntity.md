---
title: FBGeneralAdjustmentCodeICMSEntity in Tax - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/15/2020
ms.author: nebanfic
---

# Tax adjustment codes for ICMS in Tax(FBGeneralAdjustmentCodeICMSEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/Tax/FBGeneralAdjustmentCodeICMSEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax adjustment codes for ICMS</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[Identification](#Identification)||<a href="FBGeneralAdjustmentCodeICMSEntity.md" target="_blank">Tax/FBGeneralAdjustmentCodeICMSEntity</a>|
|[Description](#Description)||<a href="FBGeneralAdjustmentCodeICMSEntity.md" target="_blank">Tax/FBGeneralAdjustmentCodeICMSEntity</a>|
|[State](#State)||<a href="FBGeneralAdjustmentCodeICMSEntity.md" target="_blank">Tax/FBGeneralAdjustmentCodeICMSEntity</a>|
|[TaxType](#TaxType)||<a href="FBGeneralAdjustmentCodeICMSEntity.md" target="_blank">Tax/FBGeneralAdjustmentCodeICMSEntity</a>|
|[ICMSType](#ICMSType)||<a href="FBGeneralAdjustmentCodeICMSEntity.md" target="_blank">Tax/FBGeneralAdjustmentCodeICMSEntity</a>|
|[Classification](#Classification)||<a href="FBGeneralAdjustmentCodeICMSEntity.md" target="_blank">Tax/FBGeneralAdjustmentCodeICMSEntity</a>|
|[OccurrenceCode](#OccurrenceCode)||<a href="FBGeneralAdjustmentCodeICMSEntity.md" target="_blank">Tax/FBGeneralAdjustmentCodeICMSEntity</a>|
|[SpedAdjustmentCode](#SpedAdjustmentCode)||<a href="FBGeneralAdjustmentCodeICMSEntity.md" target="_blank">Tax/FBGeneralAdjustmentCodeICMSEntity</a>|
|[GIAAdjustmentCode](#GIAAdjustmentCode)||<a href="FBGeneralAdjustmentCodeICMSEntity.md" target="_blank">Tax/FBGeneralAdjustmentCodeICMSEntity</a>|
|[ValidFromDate](#ValidFromDate)||<a href="FBGeneralAdjustmentCodeICMSEntity.md" target="_blank">Tax/FBGeneralAdjustmentCodeICMSEntity</a>|
|[ValidToDate](#ValidToDate)||<a href="FBGeneralAdjustmentCodeICMSEntity.md" target="_blank">Tax/FBGeneralAdjustmentCodeICMSEntity</a>|
|[OtherDebit](#OtherDebit)||<a href="FBGeneralAdjustmentCodeICMSEntity.md" target="_blank">Tax/FBGeneralAdjustmentCodeICMSEntity</a>|
|[ReceitaCode](#ReceitaCode)||<a href="FBGeneralAdjustmentCodeICMSEntity.md" target="_blank">Tax/FBGeneralAdjustmentCodeICMSEntity</a>|
|[BackingTable_FBGeneralAdjustmentCodeICMS_BRRelationshipId](#BackingTable_FBGeneralAdjustmentCodeICMS_BRRelationshipId)||<a href="FBGeneralAdjustmentCodeICMSEntity.md" target="_blank">Tax/FBGeneralAdjustmentCodeICMSEntity</a>|

### <a href=#Identification name="Identification">Identification</a>

First included in: Tax/FBGeneralAdjustmentCodeICMSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Identification attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: Tax/FBGeneralAdjustmentCodeICMSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#State name="State">State</a>

First included in: Tax/FBGeneralAdjustmentCodeICMSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the State attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxType name="TaxType">TaxType</a>

First included in: Tax/FBGeneralAdjustmentCodeICMSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ICMSType name="ICMSType">ICMSType</a>

First included in: Tax/FBGeneralAdjustmentCodeICMSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tax type</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ICMSType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Classification name="Classification">Classification</a>

First included in: Tax/FBGeneralAdjustmentCodeICMSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Classification attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OccurrenceCode name="OccurrenceCode">OccurrenceCode</a>

First included in: Tax/FBGeneralAdjustmentCodeICMSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OccurrenceCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SpedAdjustmentCode name="SpedAdjustmentCode">SpedAdjustmentCode</a>

First included in: Tax/FBGeneralAdjustmentCodeICMSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sped adjustment code</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SpedAdjustmentCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sped adjustment code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GIAAdjustmentCode name="GIAAdjustmentCode">GIAAdjustmentCode</a>

First included in: Tax/FBGeneralAdjustmentCodeICMSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>GIA adjustment code</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GIAAdjustmentCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>GIA adjustment code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidFromDate name="ValidFromDate">ValidFromDate</a>

First included in: Tax/FBGeneralAdjustmentCodeICMSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidFromDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidToDate name="ValidToDate">ValidToDate</a>

First included in: Tax/FBGeneralAdjustmentCodeICMSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidToDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OtherDebit name="OtherDebit">OtherDebit</a>

First included in: Tax/FBGeneralAdjustmentCodeICMSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OtherDebit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceitaCode name="ReceitaCode">ReceitaCode</a>

First included in: Tax/FBGeneralAdjustmentCodeICMSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceitaCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_FBGeneralAdjustmentCodeICMS_BRRelationshipId name="BackingTable_FBGeneralAdjustmentCodeICMS_BRRelationshipId">BackingTable_FBGeneralAdjustmentCodeICMS_BRRelationshipId</a>

First included in: Tax/FBGeneralAdjustmentCodeICMSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_FBGeneralAdjustmentCodeICMS_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/FiscalBooksBrazil/Main/FBGeneralAdjustmentCodeICMS_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Main/FBGeneralAdjustmentCodeICMS_BR.cdm.json/FBGeneralAdjustmentCodeICMS_BR</a></td><td><a href="../../../Tables/Finance/FiscalBooksBrazil/Main/FBGeneralAdjustmentCodeICMS_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
