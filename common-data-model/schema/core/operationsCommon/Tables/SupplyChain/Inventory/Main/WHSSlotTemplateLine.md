---
title: WHSSlotTemplateLine - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# Slotting template details

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/Inventory/Main/WHSSlotTemplateLine.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[WHSSlotTemplateLine/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Slotting template details</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="WHSSlotTemplateLine.md" target="_blank">Main/WHSSlotTemplateLine</a>|
|[AssignSlotCriteria](#AssignSlotCriteria)||<a href="WHSSlotTemplateLine.md" target="_blank">Main/WHSSlotTemplateLine</a>|
|[AllowLetUps](#AllowLetUps)||<a href="WHSSlotTemplateLine.md" target="_blank">Main/WHSSlotTemplateLine</a>|
|[Description](#Description)||<a href="WHSSlotTemplateLine.md" target="_blank">Main/WHSSlotTemplateLine</a>|
|[SlotMaxQty](#SlotMaxQty)||<a href="WHSSlotTemplateLine.md" target="_blank">Main/WHSSlotTemplateLine</a>|
|[SlotMinQty](#SlotMinQty)||<a href="WHSSlotTemplateLine.md" target="_blank">Main/WHSSlotTemplateLine</a>|
|[OverflowLocation](#OverflowLocation)||<a href="WHSSlotTemplateLine.md" target="_blank">Main/WHSSlotTemplateLine</a>|
|[SequenceNumber](#SequenceNumber)||<a href="WHSSlotTemplateLine.md" target="_blank">Main/WHSSlotTemplateLine</a>|
|[SlotTemplate](#SlotTemplate)||<a href="WHSSlotTemplateLine.md" target="_blank">Main/WHSSlotTemplateLine</a>|
|[SlotUOMTierId](#SlotUOMTierId)||<a href="WHSSlotTemplateLine.md" target="_blank">Main/WHSSlotTemplateLine</a>|
|[PackedQueryRun](#PackedQueryRun)||<a href="WHSSlotTemplateLine.md" target="_blank">Main/WHSSlotTemplateLine</a>|
|[UnitOfMeasureSymbol](#UnitOfMeasureSymbol)||<a href="WHSSlotTemplateLine.md" target="_blank">Main/WHSSlotTemplateLine</a>|
|[LocDirHintCode](#LocDirHintCode)||<a href="WHSSlotTemplateLine.md" target="_blank">Main/WHSSlotTemplateLine</a>|
|[UseFixedLocation](#UseFixedLocation)||<a href="WHSSlotTemplateLine.md" target="_blank">Main/WHSSlotTemplateLine</a>|
|[DataAreaId](#DataAreaId)||<a href="WHSSlotTemplateLine.md" target="_blank">Main/WHSSlotTemplateLine</a>|
|[Relationship_WHSSlotTemplateRelationshipId](#Relationship_WHSSlotTemplateRelationshipId)||<a href="WHSSlotTemplateLine.md" target="_blank">Main/WHSSlotTemplateLine</a>|
|[Relationship_WHSSlotUOMTierRelationshipId](#Relationship_WHSSlotUOMTierRelationshipId)||<a href="WHSSlotTemplateLine.md" target="_blank">Main/WHSSlotTemplateLine</a>|
|[Relationship_WHSLocDirHintRelationshipId](#Relationship_WHSLocDirHintRelationshipId)||<a href="WHSSlotTemplateLine.md" target="_blank">Main/WHSSlotTemplateLine</a>|
|[Relationship_WMSLocationRelationshipId](#Relationship_WMSLocationRelationshipId)||<a href="WHSSlotTemplateLine.md" target="_blank">Main/WHSSlotTemplateLine</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="WHSSlotTemplateLine.md" target="_blank">Main/WHSSlotTemplateLine</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/WHSSlotTemplateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[WHSSlotTemplateLine/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AssignSlotCriteria name="AssignSlotCriteria">AssignSlotCriteria</a>

First included in: Main/WHSSlotTemplateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssignSlotCriteria attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AllowLetUps name="AllowLetUps">AllowLetUps</a>

First included in: Main/WHSSlotTemplateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowLetUps attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: Main/WHSSlotTemplateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SlotMaxQty name="SlotMaxQty">SlotMaxQty</a>

First included in: Main/WHSSlotTemplateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SlotMaxQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SlotMinQty name="SlotMinQty">SlotMinQty</a>

First included in: Main/WHSSlotTemplateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SlotMinQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#OverflowLocation name="OverflowLocation">OverflowLocation</a>

First included in: Main/WHSSlotTemplateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OverflowLocation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SequenceNumber name="SequenceNumber">SequenceNumber</a>

First included in: Main/WHSSlotTemplateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SequenceNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SlotTemplate name="SlotTemplate">SlotTemplate</a>

First included in: Main/WHSSlotTemplateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SlotTemplate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SlotUOMTierId name="SlotUOMTierId">SlotUOMTierId</a>

First included in: Main/WHSSlotTemplateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SlotUOMTierId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PackedQueryRun name="PackedQueryRun">PackedQueryRun</a>

First included in: Main/WHSSlotTemplateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackedQueryRun attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#UnitOfMeasureSymbol name="UnitOfMeasureSymbol">UnitOfMeasureSymbol</a>

First included in: Main/WHSSlotTemplateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitOfMeasureSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LocDirHintCode name="LocDirHintCode">LocDirHintCode</a>

First included in: Main/WHSSlotTemplateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LocDirHintCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseFixedLocation name="UseFixedLocation">UseFixedLocation</a>

First included in: Main/WHSSlotTemplateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseFixedLocation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Main/WHSSlotTemplateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WHSSlotTemplateRelationshipId name="Relationship_WHSSlotTemplateRelationshipId">Relationship_WHSSlotTemplateRelationshipId</a>

First included in: Main/WHSSlotTemplateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WHSSlotTemplateRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="WHSSlotTemplate.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/WHSSlotTemplate.cdm.json/WHSSlotTemplate</a></td><td><a href="WHSSlotTemplate.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WHSSlotUOMTierRelationshipId name="Relationship_WHSSlotUOMTierRelationshipId">Relationship_WHSSlotUOMTierRelationshipId</a>

First included in: Main/WHSSlotTemplateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WHSSlotUOMTierRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="WHSSlotUOMTier.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/WHSSlotUOMTier.cdm.json/WHSSlotUOMTier</a></td><td><a href="WHSSlotUOMTier.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WHSLocDirHintRelationshipId name="Relationship_WHSLocDirHintRelationshipId">Relationship_WHSLocDirHintRelationshipId</a>

First included in: Main/WHSSlotTemplateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WHSLocDirHintRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/WHSLocDirHint.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/WHSLocDirHint.cdm.json/WHSLocDirHint</a></td><td><a href="../Group/WHSLocDirHint.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WMSLocationRelationshipId name="Relationship_WMSLocationRelationshipId">Relationship_WMSLocationRelationshipId</a>

First included in: Main/WHSSlotTemplateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WMSLocationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="WMSLocation.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/WMSLocation.cdm.json/WMSLocation</a></td><td><a href="WMSLocation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Main/WHSSlotTemplateLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CompanyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
