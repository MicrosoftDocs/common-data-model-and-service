---
title: FBGeneralAdjustmentCodePISCOFINSEntity in Tax - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Tax adjustment codes for PIS/COFINS in Tax(FBGeneralAdjustmentCodePISCOFINSEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/Tax/FBGeneralAdjustmentCodePISCOFINSEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax adjustment codes for PIS/COFINS</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[Identification](#Identification)||<a href="FBGeneralAdjustmentCodePISCOFINSEntity.md" target="_blank">Tax/FBGeneralAdjustmentCodePISCOFINSEntity</a>|
|[Description](#Description)||<a href="FBGeneralAdjustmentCodePISCOFINSEntity.md" target="_blank">Tax/FBGeneralAdjustmentCodePISCOFINSEntity</a>|
|[TaxType](#TaxType)||<a href="FBGeneralAdjustmentCodePISCOFINSEntity.md" target="_blank">Tax/FBGeneralAdjustmentCodePISCOFINSEntity</a>|
|[AdjustmentType](#AdjustmentType)||<a href="FBGeneralAdjustmentCodePISCOFINSEntity.md" target="_blank">Tax/FBGeneralAdjustmentCodePISCOFINSEntity</a>|
|[SpedAdjustmentCode](#SpedAdjustmentCode)||<a href="FBGeneralAdjustmentCodePISCOFINSEntity.md" target="_blank">Tax/FBGeneralAdjustmentCodePISCOFINSEntity</a>|
|[TransferEvent](#TransferEvent)||<a href="FBGeneralAdjustmentCodePISCOFINSEntity.md" target="_blank">Tax/FBGeneralAdjustmentCodePISCOFINSEntity</a>|
|[ValidFromDate](#ValidFromDate)||<a href="FBGeneralAdjustmentCodePISCOFINSEntity.md" target="_blank">Tax/FBGeneralAdjustmentCodePISCOFINSEntity</a>|
|[ValidToDate](#ValidToDate)||<a href="FBGeneralAdjustmentCodePISCOFINSEntity.md" target="_blank">Tax/FBGeneralAdjustmentCodePISCOFINSEntity</a>|
|[OtherDebit](#OtherDebit)||<a href="FBGeneralAdjustmentCodePISCOFINSEntity.md" target="_blank">Tax/FBGeneralAdjustmentCodePISCOFINSEntity</a>|
|[ReceitaCode](#ReceitaCode)||<a href="FBGeneralAdjustmentCodePISCOFINSEntity.md" target="_blank">Tax/FBGeneralAdjustmentCodePISCOFINSEntity</a>|
|[BackingTable_FBGeneralAdjustmentCodePISCOFINS_BRRelationshipId](#BackingTable_FBGeneralAdjustmentCodePISCOFINS_BRRelationshipId)||<a href="FBGeneralAdjustmentCodePISCOFINSEntity.md" target="_blank">Tax/FBGeneralAdjustmentCodePISCOFINSEntity</a>|

### <a href=#Identification name="Identification">Identification</a>

First included in: Tax/FBGeneralAdjustmentCodePISCOFINSEntity (this entity)  

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

First included in: Tax/FBGeneralAdjustmentCodePISCOFINSEntity (this entity)  

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

### <a href=#TaxType name="TaxType">TaxType</a>

First included in: Tax/FBGeneralAdjustmentCodePISCOFINSEntity (this entity)  

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

### <a href=#AdjustmentType name="AdjustmentType">AdjustmentType</a>

First included in: Tax/FBGeneralAdjustmentCodePISCOFINSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AdjustmentType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SpedAdjustmentCode name="SpedAdjustmentCode">SpedAdjustmentCode</a>

First included in: Tax/FBGeneralAdjustmentCodePISCOFINSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Adjustment code</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SpedAdjustmentCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Adjustment code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransferEvent name="TransferEvent">TransferEvent</a>

First included in: Tax/FBGeneralAdjustmentCodePISCOFINSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferEvent attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidFromDate name="ValidFromDate">ValidFromDate</a>

First included in: Tax/FBGeneralAdjustmentCodePISCOFINSEntity (this entity)  

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

First included in: Tax/FBGeneralAdjustmentCodePISCOFINSEntity (this entity)  

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

First included in: Tax/FBGeneralAdjustmentCodePISCOFINSEntity (this entity)  

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

First included in: Tax/FBGeneralAdjustmentCodePISCOFINSEntity (this entity)  

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

### <a href=#BackingTable_FBGeneralAdjustmentCodePISCOFINS_BRRelationshipId name="BackingTable_FBGeneralAdjustmentCodePISCOFINS_BRRelationshipId">BackingTable_FBGeneralAdjustmentCodePISCOFINS_BRRelationshipId</a>

First included in: Tax/FBGeneralAdjustmentCodePISCOFINSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_FBGeneralAdjustmentCodePISCOFINS_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/FiscalBooksBrazil/Main/FBGeneralAdjustmentCodePISCOFINS_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Main/FBGeneralAdjustmentCodePISCOFINS_BR.cdm.json/FBGeneralAdjustmentCodePISCOFINS_BR</a></td><td><a href="../../../Tables/Finance/FiscalBooksBrazil/Main/FBGeneralAdjustmentCodePISCOFINS_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
