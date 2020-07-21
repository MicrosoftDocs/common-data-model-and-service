---
title: RetailTillLayoutLegacy in Parameter - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/21/2020
ms.author: nebanfic
---

# Screen layout in Parameter(RetailTillLayoutLegacy)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Commerce/ChannelManagement/BrickAndMortarStore/Parameter/RetailTillLayoutLegacy.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailTillLayoutLegacy/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Screen layout</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailTillLayoutLegacy.md" target="_blank">Parameter/RetailTillLayoutLegacy</a>|
|[layoutId](#layoutId)||<a href="RetailTillLayoutLegacy.md" target="_blank">Parameter/RetailTillLayoutLegacy</a>|
|[CashChangerLayoutXML](#CashChangerLayoutXML)||<a href="RetailTillLayoutLegacy.md" target="_blank">Parameter/RetailTillLayoutLegacy</a>|
|[customerLayoutId](#customerLayoutId)||<a href="RetailTillLayoutLegacy.md" target="_blank">Parameter/RetailTillLayoutLegacy</a>|
|[CustomerLayoutXML](#CustomerLayoutXML)||<a href="RetailTillLayoutLegacy.md" target="_blank">Parameter/RetailTillLayoutLegacy</a>|
|[DeviceType](#DeviceType)||<a href="RetailTillLayoutLegacy.md" target="_blank">Parameter/RetailTillLayoutLegacy</a>|
|[height](#height)||<a href="RetailTillLayoutLegacy.md" target="_blank">Parameter/RetailTillLayoutLegacy</a>|
|[IMG_CashChangerLayoutXML](#IMG_CashChangerLayoutXML)||<a href="RetailTillLayoutLegacy.md" target="_blank">Parameter/RetailTillLayoutLegacy</a>|
|[layoutXML](#layoutXML)||<a href="RetailTillLayoutLegacy.md" target="_blank">Parameter/RetailTillLayoutLegacy</a>|
|[name](#name)||<a href="RetailTillLayoutLegacy.md" target="_blank">Parameter/RetailTillLayoutLegacy</a>|
|[receiptId](#receiptId)||<a href="RetailTillLayoutLegacy.md" target="_blank">Parameter/RetailTillLayoutLegacy</a>|
|[ReceiptItemsLayoutXML](#ReceiptItemsLayoutXML)||<a href="RetailTillLayoutLegacy.md" target="_blank">Parameter/RetailTillLayoutLegacy</a>|
|[ReceiptPaymentLayoutXML](#ReceiptPaymentLayoutXML)||<a href="RetailTillLayoutLegacy.md" target="_blank">Parameter/RetailTillLayoutLegacy</a>|
|[totalId](#totalId)||<a href="RetailTillLayoutLegacy.md" target="_blank">Parameter/RetailTillLayoutLegacy</a>|
|[TotalsLayoutXML](#TotalsLayoutXML)||<a href="RetailTillLayoutLegacy.md" target="_blank">Parameter/RetailTillLayoutLegacy</a>|
|[width](#width)||<a href="RetailTillLayoutLegacy.md" target="_blank">Parameter/RetailTillLayoutLegacy</a>|
|[layoutXMLPortrait](#layoutXMLPortrait)||<a href="RetailTillLayoutLegacy.md" target="_blank">Parameter/RetailTillLayoutLegacy</a>|
|[StartScreen](#StartScreen)||<a href="RetailTillLayoutLegacy.md" target="_blank">Parameter/RetailTillLayoutLegacy</a>|
|[ConfiguraitonLayoutId](#ConfiguraitonLayoutId)||<a href="RetailTillLayoutLegacy.md" target="_blank">Parameter/RetailTillLayoutLegacy</a>|
|[ConfigurationSizeId](#ConfigurationSizeId)||<a href="RetailTillLayoutLegacy.md" target="_blank">Parameter/RetailTillLayoutLegacy</a>|
|[Relationship_RetailDeviceTypesRelationshipId](#Relationship_RetailDeviceTypesRelationshipId)||<a href="RetailTillLayoutLegacy.md" target="_blank">Parameter/RetailTillLayoutLegacy</a>|
|[Relationship_RetailTillLayoutConfigurationRelationshipId](#Relationship_RetailTillLayoutConfigurationRelationshipId)||<a href="RetailTillLayoutLegacy.md" target="_blank">Parameter/RetailTillLayoutLegacy</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Parameter/RetailTillLayoutLegacy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailTillLayoutLegacy/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#layoutId name="layoutId">layoutId</a>

First included in: Parameter/RetailTillLayoutLegacy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the layoutId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashChangerLayoutXML name="CashChangerLayoutXML">CashChangerLayoutXML</a>

First included in: Parameter/RetailTillLayoutLegacy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashChangerLayoutXML attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#customerLayoutId name="customerLayoutId">customerLayoutId</a>

First included in: Parameter/RetailTillLayoutLegacy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the customerLayoutId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerLayoutXML name="CustomerLayoutXML">CustomerLayoutXML</a>

First included in: Parameter/RetailTillLayoutLegacy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerLayoutXML attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeviceType name="DeviceType">DeviceType</a>

First included in: Parameter/RetailTillLayoutLegacy (this entity)  

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

### <a href=#height name="height">height</a>

First included in: Parameter/RetailTillLayoutLegacy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the height attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#IMG_CashChangerLayoutXML name="IMG_CashChangerLayoutXML">IMG_CashChangerLayoutXML</a>

First included in: Parameter/RetailTillLayoutLegacy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IMG_CashChangerLayoutXML attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#layoutXML name="layoutXML">layoutXML</a>

First included in: Parameter/RetailTillLayoutLegacy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the layoutXML attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#name name="name">name</a>

First included in: Parameter/RetailTillLayoutLegacy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#receiptId name="receiptId">receiptId</a>

First included in: Parameter/RetailTillLayoutLegacy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the receiptId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceiptItemsLayoutXML name="ReceiptItemsLayoutXML">ReceiptItemsLayoutXML</a>

First included in: Parameter/RetailTillLayoutLegacy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceiptItemsLayoutXML attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceiptPaymentLayoutXML name="ReceiptPaymentLayoutXML">ReceiptPaymentLayoutXML</a>

First included in: Parameter/RetailTillLayoutLegacy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceiptPaymentLayoutXML attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#totalId name="totalId">totalId</a>

First included in: Parameter/RetailTillLayoutLegacy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the totalId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalsLayoutXML name="TotalsLayoutXML">TotalsLayoutXML</a>

First included in: Parameter/RetailTillLayoutLegacy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalsLayoutXML attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#width name="width">width</a>

First included in: Parameter/RetailTillLayoutLegacy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the width attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#layoutXMLPortrait name="layoutXMLPortrait">layoutXMLPortrait</a>

First included in: Parameter/RetailTillLayoutLegacy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the layoutXMLPortrait attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StartScreen name="StartScreen">StartScreen</a>

First included in: Parameter/RetailTillLayoutLegacy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default start screen</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartScreen attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Default start screen</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ConfiguraitonLayoutId name="ConfiguraitonLayoutId">ConfiguraitonLayoutId</a>

First included in: Parameter/RetailTillLayoutLegacy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConfiguraitonLayoutId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConfigurationSizeId name="ConfigurationSizeId">ConfigurationSizeId</a>

First included in: Parameter/RetailTillLayoutLegacy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConfigurationSizeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailDeviceTypesRelationshipId name="Relationship_RetailDeviceTypesRelationshipId">Relationship_RetailDeviceTypesRelationshipId</a>

First included in: Parameter/RetailTillLayoutLegacy (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/RetailDeviceTypes.md" target="_blank">/core/operationsCommon/Tables/Commerce/ChannelManagement/BrickAndMortarStore/Miscellaneous/RetailDeviceTypes.cdm.json/RetailDeviceTypes</a></td><td><a href="../Miscellaneous/RetailDeviceTypes.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailTillLayoutConfigurationRelationshipId name="Relationship_RetailTillLayoutConfigurationRelationshipId">Relationship_RetailTillLayoutConfigurationRelationshipId</a>

First included in: Parameter/RetailTillLayoutLegacy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailTillLayoutConfigurationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/RetailTillLayoutConfiguration.md" target="_blank">/core/operationsCommon/Tables/Commerce/ChannelManagement/BrickAndMortarStore/Miscellaneous/RetailTillLayoutConfiguration.cdm.json/RetailTillLayoutConfiguration</a></td><td><a href="../Miscellaneous/RetailTillLayoutConfiguration.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
