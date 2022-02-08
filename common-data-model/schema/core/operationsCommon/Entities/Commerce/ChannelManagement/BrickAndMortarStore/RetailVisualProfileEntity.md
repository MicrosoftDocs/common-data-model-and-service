---
title: RetailVisualProfileEntity in BrickAndMortarStore - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# POS visual profiles in BrickAndMortarStore(RetailVisualProfileEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Commerce/ChannelManagement/BrickAndMortarStore/RetailVisualProfileEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>POS visual profiles</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ProfileId](#ProfileId)||<a href="RetailVisualProfileEntity.md" target="_blank">BrickAndMortarStore/RetailVisualProfileEntity</a>|
|[BackgroundPictureId](#BackgroundPictureId)||<a href="RetailVisualProfileEntity.md" target="_blank">BrickAndMortarStore/RetailVisualProfileEntity</a>|
|[DesignAllowedOnPos](#DesignAllowedOnPos)||<a href="RetailVisualProfileEntity.md" target="_blank">BrickAndMortarStore/RetailVisualProfileEntity</a>|
|[DeviceType](#DeviceType)||<a href="RetailVisualProfileEntity.md" target="_blank">BrickAndMortarStore/RetailVisualProfileEntity</a>|
|[FontScheme](#FontScheme)||<a href="RetailVisualProfileEntity.md" target="_blank">BrickAndMortarStore/RetailVisualProfileEntity</a>|
|[FullScreenMode](#FullScreenMode)||<a href="RetailVisualProfileEntity.md" target="_blank">BrickAndMortarStore/RetailVisualProfileEntity</a>|
|[HideCursor](#HideCursor)||<a href="RetailVisualProfileEntity.md" target="_blank">BrickAndMortarStore/RetailVisualProfileEntity</a>|
|[Name](#Name)||<a href="RetailVisualProfileEntity.md" target="_blank">BrickAndMortarStore/RetailVisualProfileEntity</a>|
|[Pallet](#Pallet)||<a href="RetailVisualProfileEntity.md" target="_blank">BrickAndMortarStore/RetailVisualProfileEntity</a>|
|[PictureId](#PictureId)||<a href="RetailVisualProfileEntity.md" target="_blank">BrickAndMortarStore/RetailVisualProfileEntity</a>|
|[POSSkinName](#POSSkinName)||<a href="RetailVisualProfileEntity.md" target="_blank">BrickAndMortarStore/RetailVisualProfileEntity</a>|
|[ScreenHeight](#ScreenHeight)||<a href="RetailVisualProfileEntity.md" target="_blank">BrickAndMortarStore/RetailVisualProfileEntity</a>|
|[ScreenWidth](#ScreenWidth)||<a href="RetailVisualProfileEntity.md" target="_blank">BrickAndMortarStore/RetailVisualProfileEntity</a>|
|[SkinFile](#SkinFile)||<a href="RetailVisualProfileEntity.md" target="_blank">BrickAndMortarStore/RetailVisualProfileEntity</a>|
|[PictureIdPortrait](#PictureIdPortrait)||<a href="RetailVisualProfileEntity.md" target="_blank">BrickAndMortarStore/RetailVisualProfileEntity</a>|
|[RetailDeviceTypeId](#RetailDeviceTypeId)||<a href="RetailVisualProfileEntity.md" target="_blank">BrickAndMortarStore/RetailVisualProfileEntity</a>|
|[ShowApplicationBarLabel](#ShowApplicationBarLabel)||<a href="RetailVisualProfileEntity.md" target="_blank">BrickAndMortarStore/RetailVisualProfileEntity</a>|
|[ShowDateTime](#ShowDateTime)||<a href="RetailVisualProfileEntity.md" target="_blank">BrickAndMortarStore/RetailVisualProfileEntity</a>|
|[BackingTable_RetailVisualProfileRelationshipId](#BackingTable_RetailVisualProfileRelationshipId)||<a href="RetailVisualProfileEntity.md" target="_blank">BrickAndMortarStore/RetailVisualProfileEntity</a>|

### <a href=#ProfileId name="ProfileId">ProfileId</a>

First included in: BrickAndMortarStore/RetailVisualProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProfileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackgroundPictureId name="BackgroundPictureId">BackgroundPictureId</a>

First included in: BrickAndMortarStore/RetailVisualProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackgroundPictureId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DesignAllowedOnPos name="DesignAllowedOnPos">DesignAllowedOnPos</a>

First included in: BrickAndMortarStore/RetailVisualProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DesignAllowedOnPos attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeviceType name="DeviceType">DeviceType</a>

First included in: BrickAndMortarStore/RetailVisualProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeviceType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FontScheme name="FontScheme">FontScheme</a>

First included in: BrickAndMortarStore/RetailVisualProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FontScheme attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FullScreenMode name="FullScreenMode">FullScreenMode</a>

First included in: BrickAndMortarStore/RetailVisualProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FullScreenMode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HideCursor name="HideCursor">HideCursor</a>

First included in: BrickAndMortarStore/RetailVisualProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HideCursor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: BrickAndMortarStore/RetailVisualProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Pallet name="Pallet">Pallet</a>

First included in: BrickAndMortarStore/RetailVisualProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Accent color</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Pallet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Accent color</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PictureId name="PictureId">PictureId</a>

First included in: BrickAndMortarStore/RetailVisualProfileEntity (this entity)  

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

### <a href=#POSSkinName name="POSSkinName">POSSkinName</a>

First included in: BrickAndMortarStore/RetailVisualProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the POSSkinName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ScreenHeight name="ScreenHeight">ScreenHeight</a>

First included in: BrickAndMortarStore/RetailVisualProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Screen height</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ScreenHeight attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Screen height</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ScreenWidth name="ScreenWidth">ScreenWidth</a>

First included in: BrickAndMortarStore/RetailVisualProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Screen width</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ScreenWidth attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Screen width</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SkinFile name="SkinFile">SkinFile</a>

First included in: BrickAndMortarStore/RetailVisualProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SkinFile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PictureIdPortrait name="PictureIdPortrait">PictureIdPortrait</a>

First included in: BrickAndMortarStore/RetailVisualProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Portrait image ID</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PictureIdPortrait attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Portrait image ID</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailDeviceTypeId name="RetailDeviceTypeId">RetailDeviceTypeId</a>

First included in: BrickAndMortarStore/RetailVisualProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailDeviceTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShowApplicationBarLabel name="ShowApplicationBarLabel">ShowApplicationBarLabel</a>

First included in: BrickAndMortarStore/RetailVisualProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowApplicationBarLabel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShowDateTime name="ShowDateTime">ShowDateTime</a>

First included in: BrickAndMortarStore/RetailVisualProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_RetailVisualProfileRelationshipId name="BackingTable_RetailVisualProfileRelationshipId">BackingTable_RetailVisualProfileRelationshipId</a>

First included in: BrickAndMortarStore/RetailVisualProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailVisualProfileRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../Tables/Commerce/ChannelManagement/BrickAndMortarStore/Parameter/RetailVisualProfile.md" target="_blank">/core/operationsCommon/Tables/Commerce/ChannelManagement/BrickAndMortarStore/Parameter/RetailVisualProfile.cdm.json/RetailVisualProfile</a></td><td><a href="../../../../Tables/Commerce/ChannelManagement/BrickAndMortarStore/Parameter/RetailVisualProfile.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
