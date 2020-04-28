---
title: WHSWarehouseWaveLoadBuildingTemplateV2Entity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Wave load building templates V2

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/WHSWarehouseWaveLoadBuildingTemplateV2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Wave load building templates V2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[TemplateSequenceNumber](#TemplateSequenceNumber)||<a href="WHSWarehouseWaveLoadBuildingTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseWaveLoadBuildingTemplateV2Entity</a>|
|[TemplateName](#TemplateName)||<a href="WHSWarehouseWaveLoadBuildingTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseWaveLoadBuildingTemplateV2Entity</a>|
|[WaveStepCode](#WaveStepCode)||<a href="WHSWarehouseWaveLoadBuildingTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseWaveLoadBuildingTemplateV2Entity</a>|
|[LoadTemplateId](#LoadTemplateId)||<a href="WHSWarehouseWaveLoadBuildingTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseWaveLoadBuildingTemplateV2Entity</a>|
|[WarehouseEquipmentCode](#WarehouseEquipmentCode)||<a href="WHSWarehouseWaveLoadBuildingTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseWaveLoadBuildingTemplateV2Entity</a>|
|[LoadMixGroupId](#LoadMixGroupId)||<a href="WHSWarehouseWaveLoadBuildingTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseWaveLoadBuildingTemplateV2Entity</a>|
|[WillWarehouseWaveLoadBuildingValidateVolumetrics](#WillWarehouseWaveLoadBuildingValidateVolumetrics)||<a href="WHSWarehouseWaveLoadBuildingTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseWaveLoadBuildingTemplateV2Entity</a>|
|[CanWarehouseWaveLoadBuildingUseOpenLoads](#CanWarehouseWaveLoadBuildingUseOpenLoads)||<a href="WHSWarehouseWaveLoadBuildingTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseWaveLoadBuildingTemplateV2Entity</a>|
|[CanWarehouseWaveLoadBuildingCreateLoads](#CanWarehouseWaveLoadBuildingCreateLoads)||<a href="WHSWarehouseWaveLoadBuildingTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseWaveLoadBuildingTemplateV2Entity</a>|
|[IsLoadLineSplittingAllowed](#IsLoadLineSplittingAllowed)||<a href="WHSWarehouseWaveLoadBuildingTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseWaveLoadBuildingTemplateV2Entity</a>|
|[TemplateQuery](#TemplateQuery)||<a href="WHSWarehouseWaveLoadBuildingTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseWaveLoadBuildingTemplateV2Entity</a>|
|[BackingTable_WHSLoadBuildTemplateRelationshipId](#BackingTable_WHSLoadBuildTemplateRelationshipId)||<a href="WHSWarehouseWaveLoadBuildingTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseWaveLoadBuildingTemplateV2Entity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="WHSWarehouseWaveLoadBuildingTemplateV2Entity.md" target="_blank">InventoryAndWarehouseManagement/WHSWarehouseWaveLoadBuildingTemplateV2Entity</a>|

### <a href=#TemplateSequenceNumber name="TemplateSequenceNumber">TemplateSequenceNumber</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseWaveLoadBuildingTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TemplateSequenceNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TemplateName name="TemplateName">TemplateName</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseWaveLoadBuildingTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TemplateName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WaveStepCode name="WaveStepCode">WaveStepCode</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseWaveLoadBuildingTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WaveStepCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LoadTemplateId name="LoadTemplateId">LoadTemplateId</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseWaveLoadBuildingTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoadTemplateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseEquipmentCode name="WarehouseEquipmentCode">WarehouseEquipmentCode</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseWaveLoadBuildingTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseEquipmentCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LoadMixGroupId name="LoadMixGroupId">LoadMixGroupId</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseWaveLoadBuildingTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoadMixGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillWarehouseWaveLoadBuildingValidateVolumetrics name="WillWarehouseWaveLoadBuildingValidateVolumetrics">WillWarehouseWaveLoadBuildingValidateVolumetrics</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseWaveLoadBuildingTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillWarehouseWaveLoadBuildingValidateVolumetrics attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CanWarehouseWaveLoadBuildingUseOpenLoads name="CanWarehouseWaveLoadBuildingUseOpenLoads">CanWarehouseWaveLoadBuildingUseOpenLoads</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseWaveLoadBuildingTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CanWarehouseWaveLoadBuildingUseOpenLoads attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CanWarehouseWaveLoadBuildingCreateLoads name="CanWarehouseWaveLoadBuildingCreateLoads">CanWarehouseWaveLoadBuildingCreateLoads</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseWaveLoadBuildingTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CanWarehouseWaveLoadBuildingCreateLoads attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsLoadLineSplittingAllowed name="IsLoadLineSplittingAllowed">IsLoadLineSplittingAllowed</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseWaveLoadBuildingTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsLoadLineSplittingAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TemplateQuery name="TemplateQuery">TemplateQuery</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseWaveLoadBuildingTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TemplateQuery attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_WHSLoadBuildTemplateRelationshipId name="BackingTable_WHSLoadBuildTemplateRelationshipId">BackingTable_WHSLoadBuildTemplateRelationshipId</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseWaveLoadBuildingTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_WHSLoadBuildTemplateRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Main/WHSLoadBuildTemplate.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/WHSLoadBuildTemplate.cdm.json/WHSLoadBuildTemplate</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Main/WHSLoadBuildTemplate.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/WHSWarehouseWaveLoadBuildingTemplateV2Entity (this entity)  

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
