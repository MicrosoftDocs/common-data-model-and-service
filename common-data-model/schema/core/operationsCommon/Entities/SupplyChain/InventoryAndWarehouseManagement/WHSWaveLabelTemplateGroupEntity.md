---
title: WHSWaveLabelTemplateGroupEntity in InventoryAndWarehouseManagement - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Wave label template group in InventoryAndWarehouseManagement(WHSWaveLabelTemplateGroupEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/WHSWaveLabelTemplateGroupEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Wave label template group</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[WaveLabelLayoutId](#WaveLabelLayoutId)||<a href="WHSWaveLabelTemplateGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/WHSWaveLabelTemplateGroupEntity</a>|
|[GroupBy](#GroupBy)||<a href="WHSWaveLabelTemplateGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/WHSWaveLabelTemplateGroupEntity</a>|
|[LabelTemplates](#LabelTemplates)||<a href="WHSWaveLabelTemplateGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/WHSWaveLabelTemplateGroupEntity</a>|
|[PrintBreakLabel](#PrintBreakLabel)||<a href="WHSWaveLabelTemplateGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/WHSWaveLabelTemplateGroupEntity</a>|
|[GroupTableFieldId](#GroupTableFieldId)||<a href="WHSWaveLabelTemplateGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/WHSWaveLabelTemplateGroupEntity</a>|
|[GroupTableId](#GroupTableId)||<a href="WHSWaveLabelTemplateGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/WHSWaveLabelTemplateGroupEntity</a>|
|[LineNumber](#LineNumber)||<a href="WHSWaveLabelTemplateGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/WHSWaveLabelTemplateGroupEntity</a>|
|[PrinterName](#PrinterName)||<a href="WHSWaveLabelTemplateGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/WHSWaveLabelTemplateGroupEntity</a>|
|[WaveLabelTemplateName](#WaveLabelTemplateName)||<a href="WHSWaveLabelTemplateGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/WHSWaveLabelTemplateGroupEntity</a>|
|[GroupTableName](#GroupTableName)||<a href="WHSWaveLabelTemplateGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/WHSWaveLabelTemplateGroupEntity</a>|
|[GroupTableFieldName](#GroupTableFieldName)||<a href="WHSWaveLabelTemplateGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/WHSWaveLabelTemplateGroupEntity</a>|
|[IsLabelBuildIdField](#IsLabelBuildIdField)||<a href="WHSWaveLabelTemplateGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/WHSWaveLabelTemplateGroupEntity</a>|
|[BackingTable_WHSWaveLabelTemplateGroupRelationshipId](#BackingTable_WHSWaveLabelTemplateGroupRelationshipId)||<a href="WHSWaveLabelTemplateGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/WHSWaveLabelTemplateGroupEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="WHSWaveLabelTemplateGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/WHSWaveLabelTemplateGroupEntity</a>|

### <a href=#WaveLabelLayoutId name="WaveLabelLayoutId">WaveLabelLayoutId</a>

First included in: InventoryAndWarehouseManagement/WHSWaveLabelTemplateGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WaveLabelLayoutId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GroupBy name="GroupBy">GroupBy</a>

First included in: InventoryAndWarehouseManagement/WHSWaveLabelTemplateGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GroupBy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LabelTemplates name="LabelTemplates">LabelTemplates</a>

First included in: InventoryAndWarehouseManagement/WHSWaveLabelTemplateGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LabelTemplates attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrintBreakLabel name="PrintBreakLabel">PrintBreakLabel</a>

First included in: InventoryAndWarehouseManagement/WHSWaveLabelTemplateGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintBreakLabel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GroupTableFieldId name="GroupTableFieldId">GroupTableFieldId</a>

First included in: InventoryAndWarehouseManagement/WHSWaveLabelTemplateGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GroupTableFieldId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GroupTableId name="GroupTableId">GroupTableId</a>

First included in: InventoryAndWarehouseManagement/WHSWaveLabelTemplateGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GroupTableId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: InventoryAndWarehouseManagement/WHSWaveLabelTemplateGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrinterName name="PrinterName">PrinterName</a>

First included in: InventoryAndWarehouseManagement/WHSWaveLabelTemplateGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrinterName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WaveLabelTemplateName name="WaveLabelTemplateName">WaveLabelTemplateName</a>

First included in: InventoryAndWarehouseManagement/WHSWaveLabelTemplateGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WaveLabelTemplateName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GroupTableName name="GroupTableName">GroupTableName</a>

First included in: InventoryAndWarehouseManagement/WHSWaveLabelTemplateGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GroupTableName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GroupTableFieldName name="GroupTableFieldName">GroupTableFieldName</a>

First included in: InventoryAndWarehouseManagement/WHSWaveLabelTemplateGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GroupTableFieldName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsLabelBuildIdField name="IsLabelBuildIdField">IsLabelBuildIdField</a>

First included in: InventoryAndWarehouseManagement/WHSWaveLabelTemplateGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsLabelBuildIdField attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_WHSWaveLabelTemplateGroupRelationshipId name="BackingTable_WHSWaveLabelTemplateGroupRelationshipId">BackingTable_WHSWaveLabelTemplateGroupRelationshipId</a>

First included in: InventoryAndWarehouseManagement/WHSWaveLabelTemplateGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_WHSWaveLabelTemplateGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Group/WHSWaveLabelTemplateGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/WHSWaveLabelTemplateGroup.cdm.json/WHSWaveLabelTemplateGroup</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Group/WHSWaveLabelTemplateGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/WHSWaveLabelTemplateGroupEntity (this entity)  

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
