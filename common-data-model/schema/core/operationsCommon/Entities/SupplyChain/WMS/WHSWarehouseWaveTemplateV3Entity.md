---
title: WHSWarehouseWaveTemplateV3Entity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 5/5/2020
ms.author: nebanfic
---

# Warehouse wave templates V3

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/WMS/WHSWarehouseWaveTemplateV3Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Warehouse wave templates V3</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[WillReleaseToWarehouseAddShipmentToOpenWave](#WillReleaseToWarehouseAddShipmentToOpenWave)||<a href="WHSWarehouseWaveTemplateV3Entity.md" target="_blank">WMS/WHSWarehouseWaveTemplateV3Entity</a>|
|[WillReleaseToWarehouseAutomaticallyCreateWaves](#WillReleaseToWarehouseAutomaticallyCreateWaves)||<a href="WHSWarehouseWaveTemplateV3Entity.md" target="_blank">WMS/WHSWarehouseWaveTemplateV3Entity</a>|
|[WillReleaseToWarehouseAutomaticallyProcessWaves](#WillReleaseToWarehouseAutomaticallyProcessWaves)||<a href="WHSWarehouseWaveTemplateV3Entity.md" target="_blank">WMS/WHSWarehouseWaveTemplateV3Entity</a>|
|[WillReachingThresholdAutomaticallyProcessWave](#WillReachingThresholdAutomaticallyProcessWave)||<a href="WHSWarehouseWaveTemplateV3Entity.md" target="_blank">WMS/WHSWarehouseWaveTemplateV3Entity</a>|
|[WillWaveProcessingAutomaticallyReleaseCreatedReplenishmentWork](#WillWaveProcessingAutomaticallyReleaseCreatedReplenishmentWork)||<a href="WHSWarehouseWaveTemplateV3Entity.md" target="_blank">WMS/WHSWarehouseWaveTemplateV3Entity</a>|
|[WillWaveCreationAutomaticallyReleaseWaves](#WillWaveCreationAutomaticallyReleaseWaves)||<a href="WHSWarehouseWaveTemplateV3Entity.md" target="_blank">WMS/WHSWarehouseWaveTemplateV3Entity</a>|
|[WarehouseId](#WarehouseId)||<a href="WHSWarehouseWaveTemplateV3Entity.md" target="_blank">WMS/WHSWarehouseWaveTemplateV3Entity</a>|
|[InventorySiteId](#InventorySiteId)||<a href="WHSWarehouseWaveTemplateV3Entity.md" target="_blank">WMS/WHSWarehouseWaveTemplateV3Entity</a>|
|[IsTemplateValid](#IsTemplateValid)||<a href="WHSWarehouseWaveTemplateV3Entity.md" target="_blank">WMS/WHSWarehouseWaveTemplateV3Entity</a>|
|[MaximumNumberOfShipmentLinesPerWave](#MaximumNumberOfShipmentLinesPerWave)||<a href="WHSWarehouseWaveTemplateV3Entity.md" target="_blank">WMS/WHSWarehouseWaveTemplateV3Entity</a>|
|[MaximumWeightPerWave](#MaximumWeightPerWave)||<a href="WHSWarehouseWaveTemplateV3Entity.md" target="_blank">WMS/WHSWarehouseWaveTemplateV3Entity</a>|
|[MaximumNumberOfShipmentsPerWave](#MaximumNumberOfShipmentsPerWave)||<a href="WHSWarehouseWaveTemplateV3Entity.md" target="_blank">WMS/WHSWarehouseWaveTemplateV3Entity</a>|
|[TemplateDescription](#TemplateDescription)||<a href="WHSWarehouseWaveTemplateV3Entity.md" target="_blank">WMS/WHSWarehouseWaveTemplateV3Entity</a>|
|[TemplateName](#TemplateName)||<a href="WHSWarehouseWaveTemplateV3Entity.md" target="_blank">WMS/WHSWarehouseWaveTemplateV3Entity</a>|
|[TemplateQuery](#TemplateQuery)||<a href="WHSWarehouseWaveTemplateV3Entity.md" target="_blank">WMS/WHSWarehouseWaveTemplateV3Entity</a>|
|[TemplateSequenceNumber](#TemplateSequenceNumber)||<a href="WHSWarehouseWaveTemplateV3Entity.md" target="_blank">WMS/WHSWarehouseWaveTemplateV3Entity</a>|
|[TemplateType](#TemplateType)||<a href="WHSWarehouseWaveTemplateV3Entity.md" target="_blank">WMS/WHSWarehouseWaveTemplateV3Entity</a>|
|[FirstDefaultWaveAttributeValue](#FirstDefaultWaveAttributeValue)||<a href="WHSWarehouseWaveTemplateV3Entity.md" target="_blank">WMS/WHSWarehouseWaveTemplateV3Entity</a>|
|[SecondDefaultWaveAttributeValue](#SecondDefaultWaveAttributeValue)||<a href="WHSWarehouseWaveTemplateV3Entity.md" target="_blank">WMS/WHSWarehouseWaveTemplateV3Entity</a>|
|[ThirdDefaultWaveAttributeValue](#ThirdDefaultWaveAttributeValue)||<a href="WHSWarehouseWaveTemplateV3Entity.md" target="_blank">WMS/WHSWarehouseWaveTemplateV3Entity</a>|
|[FourthDefaultWaveAttributeValue](#FourthDefaultWaveAttributeValue)||<a href="WHSWarehouseWaveTemplateV3Entity.md" target="_blank">WMS/WHSWarehouseWaveTemplateV3Entity</a>|
|[Relationship_WarehouseRelationshipId](#Relationship_WarehouseRelationshipId)||<a href="WHSWarehouseWaveTemplateV3Entity.md" target="_blank">WMS/WHSWarehouseWaveTemplateV3Entity</a>|
|[Relationship_InventorySiteRelationshipId](#Relationship_InventorySiteRelationshipId)||<a href="WHSWarehouseWaveTemplateV3Entity.md" target="_blank">WMS/WHSWarehouseWaveTemplateV3Entity</a>|
|[Relationship_FirstDefaultWarehouseWaveAttributeRelationshipId](#Relationship_FirstDefaultWarehouseWaveAttributeRelationshipId)||<a href="WHSWarehouseWaveTemplateV3Entity.md" target="_blank">WMS/WHSWarehouseWaveTemplateV3Entity</a>|
|[Relationship_SecondDefaultWarehouseWaveAttributeRelationshipId](#Relationship_SecondDefaultWarehouseWaveAttributeRelationshipId)||<a href="WHSWarehouseWaveTemplateV3Entity.md" target="_blank">WMS/WHSWarehouseWaveTemplateV3Entity</a>|
|[Relationship_ThirdDefaultWarehouseWaveAttributeRelationshipId](#Relationship_ThirdDefaultWarehouseWaveAttributeRelationshipId)||<a href="WHSWarehouseWaveTemplateV3Entity.md" target="_blank">WMS/WHSWarehouseWaveTemplateV3Entity</a>|
|[Relationship_FourthDefaultWarehouseWaveAttributeRelationshipId](#Relationship_FourthDefaultWarehouseWaveAttributeRelationshipId)||<a href="WHSWarehouseWaveTemplateV3Entity.md" target="_blank">WMS/WHSWarehouseWaveTemplateV3Entity</a>|
|[BackingTable_WHSWaveTemplateTableRelationshipId](#BackingTable_WHSWaveTemplateTableRelationshipId)||<a href="WHSWarehouseWaveTemplateV3Entity.md" target="_blank">WMS/WHSWarehouseWaveTemplateV3Entity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="WHSWarehouseWaveTemplateV3Entity.md" target="_blank">WMS/WHSWarehouseWaveTemplateV3Entity</a>|

### <a href=#WillReleaseToWarehouseAddShipmentToOpenWave name="WillReleaseToWarehouseAddShipmentToOpenWave">WillReleaseToWarehouseAddShipmentToOpenWave</a>

First included in: WMS/WHSWarehouseWaveTemplateV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillReleaseToWarehouseAddShipmentToOpenWave attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillReleaseToWarehouseAutomaticallyCreateWaves name="WillReleaseToWarehouseAutomaticallyCreateWaves">WillReleaseToWarehouseAutomaticallyCreateWaves</a>

First included in: WMS/WHSWarehouseWaveTemplateV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillReleaseToWarehouseAutomaticallyCreateWaves attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillReleaseToWarehouseAutomaticallyProcessWaves name="WillReleaseToWarehouseAutomaticallyProcessWaves">WillReleaseToWarehouseAutomaticallyProcessWaves</a>

First included in: WMS/WHSWarehouseWaveTemplateV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillReleaseToWarehouseAutomaticallyProcessWaves attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillReachingThresholdAutomaticallyProcessWave name="WillReachingThresholdAutomaticallyProcessWave">WillReachingThresholdAutomaticallyProcessWave</a>

First included in: WMS/WHSWarehouseWaveTemplateV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillReachingThresholdAutomaticallyProcessWave attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillWaveProcessingAutomaticallyReleaseCreatedReplenishmentWork name="WillWaveProcessingAutomaticallyReleaseCreatedReplenishmentWork">WillWaveProcessingAutomaticallyReleaseCreatedReplenishmentWork</a>

First included in: WMS/WHSWarehouseWaveTemplateV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillWaveProcessingAutomaticallyReleaseCreatedReplenishmentWork attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillWaveCreationAutomaticallyReleaseWaves name="WillWaveCreationAutomaticallyReleaseWaves">WillWaveCreationAutomaticallyReleaseWaves</a>

First included in: WMS/WHSWarehouseWaveTemplateV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillWaveCreationAutomaticallyReleaseWaves attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseId name="WarehouseId">WarehouseId</a>

First included in: WMS/WHSWarehouseWaveTemplateV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventorySiteId name="InventorySiteId">InventorySiteId</a>

First included in: WMS/WHSWarehouseWaveTemplateV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventorySiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsTemplateValid name="IsTemplateValid">IsTemplateValid</a>

First included in: WMS/WHSWarehouseWaveTemplateV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsTemplateValid attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumNumberOfShipmentLinesPerWave name="MaximumNumberOfShipmentLinesPerWave">MaximumNumberOfShipmentLinesPerWave</a>

First included in: WMS/WHSWarehouseWaveTemplateV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumNumberOfShipmentLinesPerWave attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumWeightPerWave name="MaximumWeightPerWave">MaximumWeightPerWave</a>

First included in: WMS/WHSWarehouseWaveTemplateV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumWeightPerWave attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumNumberOfShipmentsPerWave name="MaximumNumberOfShipmentsPerWave">MaximumNumberOfShipmentsPerWave</a>

First included in: WMS/WHSWarehouseWaveTemplateV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumNumberOfShipmentsPerWave attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TemplateDescription name="TemplateDescription">TemplateDescription</a>

First included in: WMS/WHSWarehouseWaveTemplateV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TemplateDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TemplateName name="TemplateName">TemplateName</a>

First included in: WMS/WHSWarehouseWaveTemplateV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TemplateName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TemplateQuery name="TemplateQuery">TemplateQuery</a>

First included in: WMS/WHSWarehouseWaveTemplateV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TemplateQuery attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TemplateSequenceNumber name="TemplateSequenceNumber">TemplateSequenceNumber</a>

First included in: WMS/WHSWarehouseWaveTemplateV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TemplateSequenceNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TemplateType name="TemplateType">TemplateType</a>

First included in: WMS/WHSWarehouseWaveTemplateV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TemplateType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FirstDefaultWaveAttributeValue name="FirstDefaultWaveAttributeValue">FirstDefaultWaveAttributeValue</a>

First included in: WMS/WHSWarehouseWaveTemplateV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Attribute 1</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FirstDefaultWaveAttributeValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Attribute 1</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SecondDefaultWaveAttributeValue name="SecondDefaultWaveAttributeValue">SecondDefaultWaveAttributeValue</a>

First included in: WMS/WHSWarehouseWaveTemplateV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Attribute 2</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SecondDefaultWaveAttributeValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Attribute 2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThirdDefaultWaveAttributeValue name="ThirdDefaultWaveAttributeValue">ThirdDefaultWaveAttributeValue</a>

First included in: WMS/WHSWarehouseWaveTemplateV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Attribute 3</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThirdDefaultWaveAttributeValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Attribute 3</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FourthDefaultWaveAttributeValue name="FourthDefaultWaveAttributeValue">FourthDefaultWaveAttributeValue</a>

First included in: WMS/WHSWarehouseWaveTemplateV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Attribute 4</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FourthDefaultWaveAttributeValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Attribute 4</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WarehouseRelationshipId name="Relationship_WarehouseRelationshipId">Relationship_WarehouseRelationshipId</a>

First included in: WMS/WHSWarehouseWaveTemplateV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WarehouseRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventorySiteRelationshipId name="Relationship_InventorySiteRelationshipId">Relationship_InventorySiteRelationshipId</a>

First included in: WMS/WHSWarehouseWaveTemplateV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventorySiteRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FirstDefaultWarehouseWaveAttributeRelationshipId name="Relationship_FirstDefaultWarehouseWaveAttributeRelationshipId">Relationship_FirstDefaultWarehouseWaveAttributeRelationshipId</a>

First included in: WMS/WHSWarehouseWaveTemplateV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FirstDefaultWarehouseWaveAttributeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SecondDefaultWarehouseWaveAttributeRelationshipId name="Relationship_SecondDefaultWarehouseWaveAttributeRelationshipId">Relationship_SecondDefaultWarehouseWaveAttributeRelationshipId</a>

First included in: WMS/WHSWarehouseWaveTemplateV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SecondDefaultWarehouseWaveAttributeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ThirdDefaultWarehouseWaveAttributeRelationshipId name="Relationship_ThirdDefaultWarehouseWaveAttributeRelationshipId">Relationship_ThirdDefaultWarehouseWaveAttributeRelationshipId</a>

First included in: WMS/WHSWarehouseWaveTemplateV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ThirdDefaultWarehouseWaveAttributeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FourthDefaultWarehouseWaveAttributeRelationshipId name="Relationship_FourthDefaultWarehouseWaveAttributeRelationshipId">Relationship_FourthDefaultWarehouseWaveAttributeRelationshipId</a>

First included in: WMS/WHSWarehouseWaveTemplateV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FourthDefaultWarehouseWaveAttributeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_WHSWaveTemplateTableRelationshipId name="BackingTable_WHSWaveTemplateTableRelationshipId">BackingTable_WHSWaveTemplateTableRelationshipId</a>

First included in: WMS/WHSWarehouseWaveTemplateV3Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_WHSWaveTemplateTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Main/WHSWaveTemplateTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/WHSWaveTemplateTable.cdm.json/WHSWaveTemplateTable</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Main/WHSWaveTemplateTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: WMS/WHSWarehouseWaveTemplateV3Entity (this entity)  

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
