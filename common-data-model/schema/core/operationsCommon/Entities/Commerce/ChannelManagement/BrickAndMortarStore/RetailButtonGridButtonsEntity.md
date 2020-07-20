---
title: RetailButtonGridButtonsEntity in BrickAndMortarStore - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/20/2020
ms.author: nebanfic
---

# POS button grid buttons in BrickAndMortarStore(RetailButtonGridButtonsEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Commerce/ChannelManagement/BrickAndMortarStore/RetailButtonGridButtonsEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>POS button grid buttons</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[Action](#Action)||<a href="RetailButtonGridButtonsEntity.md" target="_blank">BrickAndMortarStore/RetailButtonGridButtonsEntity</a>|
|[ActionProperty](#ActionProperty)||<a href="RetailButtonGridButtonsEntity.md" target="_blank">BrickAndMortarStore/RetailButtonGridButtonsEntity</a>|
|[BackColor](#BackColor)||<a href="RetailButtonGridButtonsEntity.md" target="_blank">BrickAndMortarStore/RetailButtonGridButtonsEntity</a>|
|[BackColor2](#BackColor2)||<a href="RetailButtonGridButtonsEntity.md" target="_blank">BrickAndMortarStore/RetailButtonGridButtonsEntity</a>|
|[BorderColor](#BorderColor)||<a href="RetailButtonGridButtonsEntity.md" target="_blank">BrickAndMortarStore/RetailButtonGridButtonsEntity</a>|
|[buttonGridId](#buttonGridId)||<a href="RetailButtonGridButtonsEntity.md" target="_blank">BrickAndMortarStore/RetailButtonGridButtonsEntity</a>|
|[Col](#Col)||<a href="RetailButtonGridButtonsEntity.md" target="_blank">BrickAndMortarStore/RetailButtonGridButtonsEntity</a>|
|[colour](#colour)||<a href="RetailButtonGridButtonsEntity.md" target="_blank">BrickAndMortarStore/RetailButtonGridButtonsEntity</a>|
|[ColSpan](#ColSpan)||<a href="RetailButtonGridButtonsEntity.md" target="_blank">BrickAndMortarStore/RetailButtonGridButtonsEntity</a>|
|[DisplayText](#DisplayText)||<a href="RetailButtonGridButtonsEntity.md" target="_blank">BrickAndMortarStore/RetailButtonGridButtonsEntity</a>|
|[FontColor](#FontColor)||<a href="RetailButtonGridButtonsEntity.md" target="_blank">BrickAndMortarStore/RetailButtonGridButtonsEntity</a>|
|[FontSize](#FontSize)||<a href="RetailButtonGridButtonsEntity.md" target="_blank">BrickAndMortarStore/RetailButtonGridButtonsEntity</a>|
|[FontStyle](#FontStyle)||<a href="RetailButtonGridButtonsEntity.md" target="_blank">BrickAndMortarStore/RetailButtonGridButtonsEntity</a>|
|[GradientMode](#GradientMode)||<a href="RetailButtonGridButtonsEntity.md" target="_blank">BrickAndMortarStore/RetailButtonGridButtonsEntity</a>|
|[ID](#ID)||<a href="RetailButtonGridButtonsEntity.md" target="_blank">BrickAndMortarStore/RetailButtonGridButtonsEntity</a>|
|[imageAlignment](#imageAlignment)||<a href="RetailButtonGridButtonsEntity.md" target="_blank">BrickAndMortarStore/RetailButtonGridButtonsEntity</a>|
|[NewImageAlignment](#NewImageAlignment)||<a href="RetailButtonGridButtonsEntity.md" target="_blank">BrickAndMortarStore/RetailButtonGridButtonsEntity</a>|
|[NewTextAlignment](#NewTextAlignment)||<a href="RetailButtonGridButtonsEntity.md" target="_blank">BrickAndMortarStore/RetailButtonGridButtonsEntity</a>|
|[PictureId](#PictureId)||<a href="RetailButtonGridButtonsEntity.md" target="_blank">BrickAndMortarStore/RetailButtonGridButtonsEntity</a>|
|[RowNum](#RowNum)||<a href="RetailButtonGridButtonsEntity.md" target="_blank">BrickAndMortarStore/RetailButtonGridButtonsEntity</a>|
|[RowSpan](#RowSpan)||<a href="RetailButtonGridButtonsEntity.md" target="_blank">BrickAndMortarStore/RetailButtonGridButtonsEntity</a>|
|[UseCustomLookAndFeel](#UseCustomLookAndFeel)||<a href="RetailButtonGridButtonsEntity.md" target="_blank">BrickAndMortarStore/RetailButtonGridButtonsEntity</a>|
|[EnableCustomFontForPOS](#EnableCustomFontForPOS)||<a href="RetailButtonGridButtonsEntity.md" target="_blank">BrickAndMortarStore/RetailButtonGridButtonsEntity</a>|
|[HideButtonText](#HideButtonText)||<a href="RetailButtonGridButtonsEntity.md" target="_blank">BrickAndMortarStore/RetailButtonGridButtonsEntity</a>|
|[Tooltip](#Tooltip)||<a href="RetailButtonGridButtonsEntity.md" target="_blank">BrickAndMortarStore/RetailButtonGridButtonsEntity</a>|
|[EnableLiveContent](#EnableLiveContent)||<a href="RetailButtonGridButtonsEntity.md" target="_blank">BrickAndMortarStore/RetailButtonGridButtonsEntity</a>|
|[NotificationContentAlignment](#NotificationContentAlignment)||<a href="RetailButtonGridButtonsEntity.md" target="_blank">BrickAndMortarStore/RetailButtonGridButtonsEntity</a>|
|[BackingTable_RetailButtonGridButtonsRelationshipId](#BackingTable_RetailButtonGridButtonsRelationshipId)||<a href="RetailButtonGridButtonsEntity.md" target="_blank">BrickAndMortarStore/RetailButtonGridButtonsEntity</a>|

### <a href=#Action name="Action">Action</a>

First included in: BrickAndMortarStore/RetailButtonGridButtonsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Action attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActionProperty name="ActionProperty">ActionProperty</a>

First included in: BrickAndMortarStore/RetailButtonGridButtonsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActionProperty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackColor name="BackColor">BackColor</a>

First included in: BrickAndMortarStore/RetailButtonGridButtonsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackColor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackColor2 name="BackColor2">BackColor2</a>

First included in: BrickAndMortarStore/RetailButtonGridButtonsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackColor2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BorderColor name="BorderColor">BorderColor</a>

First included in: BrickAndMortarStore/RetailButtonGridButtonsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BorderColor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#buttonGridId name="buttonGridId">buttonGridId</a>

First included in: BrickAndMortarStore/RetailButtonGridButtonsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the buttonGridId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Col name="Col">Col</a>

First included in: BrickAndMortarStore/RetailButtonGridButtonsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Col attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#colour name="colour">colour</a>

First included in: BrickAndMortarStore/RetailButtonGridButtonsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the colour attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ColSpan name="ColSpan">ColSpan</a>

First included in: BrickAndMortarStore/RetailButtonGridButtonsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ColSpan attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DisplayText name="DisplayText">DisplayText</a>

First included in: BrickAndMortarStore/RetailButtonGridButtonsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisplayText attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FontColor name="FontColor">FontColor</a>

First included in: BrickAndMortarStore/RetailButtonGridButtonsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FontColor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FontSize name="FontSize">FontSize</a>

First included in: BrickAndMortarStore/RetailButtonGridButtonsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FontSize attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FontStyle name="FontStyle">FontStyle</a>

First included in: BrickAndMortarStore/RetailButtonGridButtonsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FontStyle attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GradientMode name="GradientMode">GradientMode</a>

First included in: BrickAndMortarStore/RetailButtonGridButtonsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GradientMode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ID name="ID">ID</a>

First included in: BrickAndMortarStore/RetailButtonGridButtonsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#imageAlignment name="imageAlignment">imageAlignment</a>

First included in: BrickAndMortarStore/RetailButtonGridButtonsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the imageAlignment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NewImageAlignment name="NewImageAlignment">NewImageAlignment</a>

First included in: BrickAndMortarStore/RetailButtonGridButtonsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NewImageAlignment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NewTextAlignment name="NewTextAlignment">NewTextAlignment</a>

First included in: BrickAndMortarStore/RetailButtonGridButtonsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NewTextAlignment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PictureId name="PictureId">PictureId</a>

First included in: BrickAndMortarStore/RetailButtonGridButtonsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PictureId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RowNum name="RowNum">RowNum</a>

First included in: BrickAndMortarStore/RetailButtonGridButtonsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RowNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RowSpan name="RowSpan">RowSpan</a>

First included in: BrickAndMortarStore/RetailButtonGridButtonsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RowSpan attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseCustomLookAndFeel name="UseCustomLookAndFeel">UseCustomLookAndFeel</a>

First included in: BrickAndMortarStore/RetailButtonGridButtonsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseCustomLookAndFeel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnableCustomFontForPOS name="EnableCustomFontForPOS">EnableCustomFontForPOS</a>

First included in: BrickAndMortarStore/RetailButtonGridButtonsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableCustomFontForPOS attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HideButtonText name="HideButtonText">HideButtonText</a>

First included in: BrickAndMortarStore/RetailButtonGridButtonsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HideButtonText attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Tooltip name="Tooltip">Tooltip</a>

First included in: BrickAndMortarStore/RetailButtonGridButtonsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Tooltip attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnableLiveContent name="EnableLiveContent">EnableLiveContent</a>

First included in: BrickAndMortarStore/RetailButtonGridButtonsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableLiveContent attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NotificationContentAlignment name="NotificationContentAlignment">NotificationContentAlignment</a>

First included in: BrickAndMortarStore/RetailButtonGridButtonsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NotificationContentAlignment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_RetailButtonGridButtonsRelationshipId name="BackingTable_RetailButtonGridButtonsRelationshipId">BackingTable_RetailButtonGridButtonsRelationshipId</a>

First included in: BrickAndMortarStore/RetailButtonGridButtonsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailButtonGridButtonsRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../Tables/Commerce/ChannelManagement/BrickAndMortarStore/Parameter/RetailButtonGridButtons.md" target="_blank">/core/operationsCommon/Tables/Commerce/ChannelManagement/BrickAndMortarStore/Parameter/RetailButtonGridButtons.cdm.json/RetailButtonGridButtons</a></td><td><a href="../../../../Tables/Commerce/ChannelManagement/BrickAndMortarStore/Parameter/RetailButtonGridButtons.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
