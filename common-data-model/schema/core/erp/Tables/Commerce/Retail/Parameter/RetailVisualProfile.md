---
title: RetailVisualProfile - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# RetailVisualProfile

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Commerce/Retail/Parameter/RetailVisualProfile.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailVisualProfile/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailVisualProfile.md" target="_blank">Parameter/RetailVisualProfile</a>|
|[profileId](#profileId)||<a href="RetailVisualProfile.md" target="_blank">Parameter/RetailVisualProfile</a>|
|[BackgroundPictureId](#BackgroundPictureId)||<a href="RetailVisualProfile.md" target="_blank">Parameter/RetailVisualProfile</a>|
|[designAllowedOnPos](#designAllowedOnPos)||<a href="RetailVisualProfile.md" target="_blank">Parameter/RetailVisualProfile</a>|
|[DeviceType](#DeviceType)||<a href="RetailVisualProfile.md" target="_blank">Parameter/RetailVisualProfile</a>|
|[FontScheme](#FontScheme)||<a href="RetailVisualProfile.md" target="_blank">Parameter/RetailVisualProfile</a>|
|[FullScreenMode](#FullScreenMode)||<a href="RetailVisualProfile.md" target="_blank">Parameter/RetailVisualProfile</a>|
|[hideCursor](#hideCursor)||<a href="RetailVisualProfile.md" target="_blank">Parameter/RetailVisualProfile</a>|
|[name](#name)||<a href="RetailVisualProfile.md" target="_blank">Parameter/RetailVisualProfile</a>|
|[Pallet](#Pallet)||<a href="RetailVisualProfile.md" target="_blank">Parameter/RetailVisualProfile</a>|
|[PictureId](#PictureId)||<a href="RetailVisualProfile.md" target="_blank">Parameter/RetailVisualProfile</a>|
|[PictureIdCompact](#PictureIdCompact)||<a href="RetailVisualProfile.md" target="_blank">Parameter/RetailVisualProfile</a>|
|[POSSkinName](#POSSkinName)||<a href="RetailVisualProfile.md" target="_blank">Parameter/RetailVisualProfile</a>|
|[ScreenHeight](#ScreenHeight)||<a href="RetailVisualProfile.md" target="_blank">Parameter/RetailVisualProfile</a>|
|[ScreenWidth](#ScreenWidth)||<a href="RetailVisualProfile.md" target="_blank">Parameter/RetailVisualProfile</a>|
|[SkinFile](#SkinFile)||<a href="RetailVisualProfile.md" target="_blank">Parameter/RetailVisualProfile</a>|
|[PictureIdPortrait](#PictureIdPortrait)||<a href="RetailVisualProfile.md" target="_blank">Parameter/RetailVisualProfile</a>|
|[PictureIdCompactPortrait](#PictureIdCompactPortrait)||<a href="RetailVisualProfile.md" target="_blank">Parameter/RetailVisualProfile</a>|
|[HeaderPalette](#HeaderPalette)||<a href="RetailVisualProfile.md" target="_blank">Parameter/RetailVisualProfile</a>|
|[ShowAppBarLabel](#ShowAppBarLabel)||<a href="RetailVisualProfile.md" target="_blank">Parameter/RetailVisualProfile</a>|
|[ShowDateTime](#ShowDateTime)||<a href="RetailVisualProfile.md" target="_blank">Parameter/RetailVisualProfile</a>|
|[LogOnLayout](#LogOnLayout)||<a href="RetailVisualProfile.md" target="_blank">Parameter/RetailVisualProfile</a>|
|[LogOnKeyboard](#LogOnKeyboard)||<a href="RetailVisualProfile.md" target="_blank">Parameter/RetailVisualProfile</a>|
|[PictureIdLogo](#PictureIdLogo)||<a href="RetailVisualProfile.md" target="_blank">Parameter/RetailVisualProfile</a>|
|[Relationship_BackgroundPictureIdRelationshipId](#Relationship_BackgroundPictureIdRelationshipId)||<a href="RetailVisualProfile.md" target="_blank">Parameter/RetailVisualProfile</a>|
|[Relationship_RetailDeviceTypesRelationshipId](#Relationship_RetailDeviceTypesRelationshipId)||<a href="RetailVisualProfile.md" target="_blank">Parameter/RetailVisualProfile</a>|
|[Relationship_RetailImagesRelationshipId](#Relationship_RetailImagesRelationshipId)||<a href="RetailVisualProfile.md" target="_blank">Parameter/RetailVisualProfile</a>|
|[Relationship_RetailPOSThemeRelationshipId](#Relationship_RetailPOSThemeRelationshipId)||<a href="RetailVisualProfile.md" target="_blank">Parameter/RetailVisualProfile</a>|
|[Relationship_RetailThemePalletRelationshipId](#Relationship_RetailThemePalletRelationshipId)||<a href="RetailVisualProfile.md" target="_blank">Parameter/RetailVisualProfile</a>|
|[Relationship_PictureIdPortraitRelationshipId](#Relationship_PictureIdPortraitRelationshipId)||<a href="RetailVisualProfile.md" target="_blank">Parameter/RetailVisualProfile</a>|
|[Relationship_PictureIdCompactRelationshipId](#Relationship_PictureIdCompactRelationshipId)||<a href="RetailVisualProfile.md" target="_blank">Parameter/RetailVisualProfile</a>|
|[Relationship_PictureIdCompactPortraitRelationshipId](#Relationship_PictureIdCompactPortraitRelationshipId)||<a href="RetailVisualProfile.md" target="_blank">Parameter/RetailVisualProfile</a>|
|[Relationship_RetailThemePalletHeaderRelationshipId](#Relationship_RetailThemePalletHeaderRelationshipId)||<a href="RetailVisualProfile.md" target="_blank">Parameter/RetailVisualProfile</a>|
|[Relationship_PictureIdLogoRelationshipId](#Relationship_PictureIdLogoRelationshipId)||<a href="RetailVisualProfile.md" target="_blank">Parameter/RetailVisualProfile</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Parameter/RetailVisualProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailVisualProfile/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#profileId name="profileId">profileId</a>

First included in: Parameter/RetailVisualProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the profileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackgroundPictureId name="BackgroundPictureId">BackgroundPictureId</a>

First included in: Parameter/RetailVisualProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackgroundPictureId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#designAllowedOnPos name="designAllowedOnPos">designAllowedOnPos</a>

First included in: Parameter/RetailVisualProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the designAllowedOnPos attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DeviceType name="DeviceType">DeviceType</a>

First included in: Parameter/RetailVisualProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeviceType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FontScheme name="FontScheme">FontScheme</a>

First included in: Parameter/RetailVisualProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FontScheme attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#FullScreenMode name="FullScreenMode">FullScreenMode</a>

First included in: Parameter/RetailVisualProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FullScreenMode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#hideCursor name="hideCursor">hideCursor</a>

First included in: Parameter/RetailVisualProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the hideCursor attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#name name="name">name</a>

First included in: Parameter/RetailVisualProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Pallet name="Pallet">Pallet</a>

First included in: Parameter/RetailVisualProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Pallet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PictureId name="PictureId">PictureId</a>

First included in: Parameter/RetailVisualProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PictureId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PictureIdCompact name="PictureIdCompact">PictureIdCompact</a>

First included in: Parameter/RetailVisualProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PictureIdCompact attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#POSSkinName name="POSSkinName">POSSkinName</a>

First included in: Parameter/RetailVisualProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the POSSkinName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ScreenHeight name="ScreenHeight">ScreenHeight</a>

First included in: Parameter/RetailVisualProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ScreenHeight attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ScreenWidth name="ScreenWidth">ScreenWidth</a>

First included in: Parameter/RetailVisualProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ScreenWidth attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SkinFile name="SkinFile">SkinFile</a>

First included in: Parameter/RetailVisualProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SkinFile attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#PictureIdPortrait name="PictureIdPortrait">PictureIdPortrait</a>

First included in: Parameter/RetailVisualProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PictureIdPortrait attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PictureIdCompactPortrait name="PictureIdCompactPortrait">PictureIdCompactPortrait</a>

First included in: Parameter/RetailVisualProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PictureIdCompactPortrait attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#HeaderPalette name="HeaderPalette">HeaderPalette</a>

First included in: Parameter/RetailVisualProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HeaderPalette attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShowAppBarLabel name="ShowAppBarLabel">ShowAppBarLabel</a>

First included in: Parameter/RetailVisualProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowAppBarLabel attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ShowDateTime name="ShowDateTime">ShowDateTime</a>

First included in: Parameter/RetailVisualProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowDateTime attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LogOnLayout name="LogOnLayout">LogOnLayout</a>

First included in: Parameter/RetailVisualProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogOnLayout attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LogOnKeyboard name="LogOnKeyboard">LogOnKeyboard</a>

First included in: Parameter/RetailVisualProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogOnKeyboard attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PictureIdLogo name="PictureIdLogo">PictureIdLogo</a>

First included in: Parameter/RetailVisualProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PictureIdLogo attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Relationship_BackgroundPictureIdRelationshipId name="Relationship_BackgroundPictureIdRelationshipId">Relationship_BackgroundPictureIdRelationshipId</a>

First included in: Parameter/RetailVisualProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BackgroundPictureIdRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailImages.md" target="_blank">/core/erp/Tables/Commerce/Retail/Parameter/RetailImages.cdm.json/RetailImages</a></td><td><a href="RetailImages.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailDeviceTypesRelationshipId name="Relationship_RetailDeviceTypesRelationshipId">Relationship_RetailDeviceTypesRelationshipId</a>

First included in: Parameter/RetailVisualProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailDeviceTypesRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/RetailDeviceTypes.md" target="_blank">/core/erp/Tables/Commerce/Retail/Miscellaneous/RetailDeviceTypes.cdm.json/RetailDeviceTypes</a></td><td><a href="../Miscellaneous/RetailDeviceTypes.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailImagesRelationshipId name="Relationship_RetailImagesRelationshipId">Relationship_RetailImagesRelationshipId</a>

First included in: Parameter/RetailVisualProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailImagesRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailImages.md" target="_blank">/core/erp/Tables/Commerce/Retail/Parameter/RetailImages.cdm.json/RetailImages</a></td><td><a href="RetailImages.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailPOSThemeRelationshipId name="Relationship_RetailPOSThemeRelationshipId">Relationship_RetailPOSThemeRelationshipId</a>

First included in: Parameter/RetailVisualProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailPOSThemeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/RetailPOSTheme.md" target="_blank">/core/erp/Tables/Commerce/Retail/Miscellaneous/RetailPOSTheme.cdm.json/RetailPOSTheme</a></td><td><a href="../Miscellaneous/RetailPOSTheme.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailThemePalletRelationshipId name="Relationship_RetailThemePalletRelationshipId">Relationship_RetailThemePalletRelationshipId</a>

First included in: Parameter/RetailVisualProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailThemePalletRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/RetailThemePallet.md" target="_blank">/core/erp/Tables/Commerce/Retail/Miscellaneous/RetailThemePallet.cdm.json/RetailThemePallet</a></td><td><a href="../Miscellaneous/RetailThemePallet.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PictureIdPortraitRelationshipId name="Relationship_PictureIdPortraitRelationshipId">Relationship_PictureIdPortraitRelationshipId</a>

First included in: Parameter/RetailVisualProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PictureIdPortraitRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailImages.md" target="_blank">/core/erp/Tables/Commerce/Retail/Parameter/RetailImages.cdm.json/RetailImages</a></td><td><a href="RetailImages.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PictureIdCompactRelationshipId name="Relationship_PictureIdCompactRelationshipId">Relationship_PictureIdCompactRelationshipId</a>

First included in: Parameter/RetailVisualProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PictureIdCompactRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailImages.md" target="_blank">/core/erp/Tables/Commerce/Retail/Parameter/RetailImages.cdm.json/RetailImages</a></td><td><a href="RetailImages.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PictureIdCompactPortraitRelationshipId name="Relationship_PictureIdCompactPortraitRelationshipId">Relationship_PictureIdCompactPortraitRelationshipId</a>

First included in: Parameter/RetailVisualProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PictureIdCompactPortraitRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailImages.md" target="_blank">/core/erp/Tables/Commerce/Retail/Parameter/RetailImages.cdm.json/RetailImages</a></td><td><a href="RetailImages.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailThemePalletHeaderRelationshipId name="Relationship_RetailThemePalletHeaderRelationshipId">Relationship_RetailThemePalletHeaderRelationshipId</a>

First included in: Parameter/RetailVisualProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailThemePalletHeaderRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/RetailThemePallet.md" target="_blank">/core/erp/Tables/Commerce/Retail/Miscellaneous/RetailThemePallet.cdm.json/RetailThemePallet</a></td><td><a href="../Miscellaneous/RetailThemePallet.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PictureIdLogoRelationshipId name="Relationship_PictureIdLogoRelationshipId">Relationship_PictureIdLogoRelationshipId</a>

First included in: Parameter/RetailVisualProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PictureIdLogoRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailImages.md" target="_blank">/core/erp/Tables/Commerce/Retail/Parameter/RetailImages.cdm.json/RetailImages</a></td><td><a href="RetailImages.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
