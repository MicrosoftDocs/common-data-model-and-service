---
title: KanbanSourceRequirement - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# KanbanSourceRequirement

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/SupplyChain/ProductionControl/WorksheetLine/KanbanSourceRequirement.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[KanbanSourceRequirement/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="KanbanSourceRequirement.md" target="_blank">WorksheetLine/KanbanSourceRequirement</a>|
|[Kanban](#Kanban)||<a href="KanbanSourceRequirement.md" target="_blank">WorksheetLine/KanbanSourceRequirement</a>|
|[ParentSourceRequirementRecId](#ParentSourceRequirementRecId)||<a href="KanbanSourceRequirement.md" target="_blank">WorksheetLine/KanbanSourceRequirement</a>|
|[ParentSourceRequirementTableId](#ParentSourceRequirementTableId)||<a href="KanbanSourceRequirement.md" target="_blank">WorksheetLine/KanbanSourceRequirement</a>|
|[RootSourceRequirementRecId](#RootSourceRequirementRecId)||<a href="KanbanSourceRequirement.md" target="_blank">WorksheetLine/KanbanSourceRequirement</a>|
|[RootSourceRequirementTableId](#RootSourceRequirementTableId)||<a href="KanbanSourceRequirement.md" target="_blank">WorksheetLine/KanbanSourceRequirement</a>|
|[SourceRequirementRecId](#SourceRequirementRecId)||<a href="KanbanSourceRequirement.md" target="_blank">WorksheetLine/KanbanSourceRequirement</a>|
|[SourceRequirementTableId](#SourceRequirementTableId)||<a href="KanbanSourceRequirement.md" target="_blank">WorksheetLine/KanbanSourceRequirement</a>|
|[Relationship_KanbanRelationshipId](#Relationship_KanbanRelationshipId)||<a href="KanbanSourceRequirement.md" target="_blank">WorksheetLine/KanbanSourceRequirement</a>|
|[Relationship_KanbanJobPickingListSourceRequirementRelationshipId](#Relationship_KanbanJobPickingListSourceRequirementRelationshipId)||<a href="KanbanSourceRequirement.md" target="_blank">WorksheetLine/KanbanSourceRequirement</a>|
|[Relationship_KanbanJobSourceRequirementRelationshipId](#Relationship_KanbanJobSourceRequirementRelationshipId)||<a href="KanbanSourceRequirement.md" target="_blank">WorksheetLine/KanbanSourceRequirement</a>|
|[Relationship_KanbanParentSourceRequirementRelationshipId](#Relationship_KanbanParentSourceRequirementRelationshipId)||<a href="KanbanSourceRequirement.md" target="_blank">WorksheetLine/KanbanSourceRequirement</a>|
|[Relationship_KanbanRootSourceRequirementRelationshipId](#Relationship_KanbanRootSourceRequirementRelationshipId)||<a href="KanbanSourceRequirement.md" target="_blank">WorksheetLine/KanbanSourceRequirement</a>|
|[Relationship_KanbanSourceRequirementRelationshipId](#Relationship_KanbanSourceRequirementRelationshipId)||<a href="KanbanSourceRequirement.md" target="_blank">WorksheetLine/KanbanSourceRequirement</a>|
|[Relationship_ProdBOMParentSourceRequirementRelationshipId](#Relationship_ProdBOMParentSourceRequirementRelationshipId)||<a href="KanbanSourceRequirement.md" target="_blank">WorksheetLine/KanbanSourceRequirement</a>|
|[Relationship_ProdBOMRootSourceRequirementRelationshipId](#Relationship_ProdBOMRootSourceRequirementRelationshipId)||<a href="KanbanSourceRequirement.md" target="_blank">WorksheetLine/KanbanSourceRequirement</a>|
|[Relationship_ProdBOMSourceRequirementRelationshipId](#Relationship_ProdBOMSourceRequirementRelationshipId)||<a href="KanbanSourceRequirement.md" target="_blank">WorksheetLine/KanbanSourceRequirement</a>|
|[Relationship_SalesLineParentSourceRequirementRelationshipId](#Relationship_SalesLineParentSourceRequirementRelationshipId)||<a href="KanbanSourceRequirement.md" target="_blank">WorksheetLine/KanbanSourceRequirement</a>|
|[Relationship_SalesLineRootSourceRequirementRelationshipId](#Relationship_SalesLineRootSourceRequirementRelationshipId)||<a href="KanbanSourceRequirement.md" target="_blank">WorksheetLine/KanbanSourceRequirement</a>|
|[Relationship_SalesLineSourceRequirementRelationshipId](#Relationship_SalesLineSourceRequirementRelationshipId)||<a href="KanbanSourceRequirement.md" target="_blank">WorksheetLine/KanbanSourceRequirement</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetLine/KanbanSourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[KanbanSourceRequirement/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Kanban name="Kanban">Kanban</a>

First included in: WorksheetLine/KanbanSourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Kanban attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ParentSourceRequirementRecId name="ParentSourceRequirementRecId">ParentSourceRequirementRecId</a>

First included in: WorksheetLine/KanbanSourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParentSourceRequirementRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ParentSourceRequirementTableId name="ParentSourceRequirementTableId">ParentSourceRequirementTableId</a>

First included in: WorksheetLine/KanbanSourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParentSourceRequirementTableId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#RootSourceRequirementRecId name="RootSourceRequirementRecId">RootSourceRequirementRecId</a>

First included in: WorksheetLine/KanbanSourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RootSourceRequirementRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RootSourceRequirementTableId name="RootSourceRequirementTableId">RootSourceRequirementTableId</a>

First included in: WorksheetLine/KanbanSourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RootSourceRequirementTableId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#SourceRequirementRecId name="SourceRequirementRecId">SourceRequirementRecId</a>

First included in: WorksheetLine/KanbanSourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceRequirementRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SourceRequirementTableId name="SourceRequirementTableId">SourceRequirementTableId</a>

First included in: WorksheetLine/KanbanSourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceRequirementTableId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#Relationship_KanbanRelationshipId name="Relationship_KanbanRelationshipId">Relationship_KanbanRelationshipId</a>

First included in: WorksheetLine/KanbanSourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_KanbanRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/Kanban.md" target="_blank">/core/erp/Tables/SupplyChain/ProductionControl/WorksheetHeader/Kanban.cdm.json/Kanban</a></td><td><a href="../WorksheetHeader/Kanban.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_KanbanJobPickingListSourceRequirementRelationshipId name="Relationship_KanbanJobPickingListSourceRequirementRelationshipId">Relationship_KanbanJobPickingListSourceRequirementRelationshipId</a>

First included in: WorksheetLine/KanbanSourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_KanbanJobPickingListSourceRequirementRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/KanbanJobPickingList.md" target="_blank">/core/erp/Tables/SupplyChain/ProductionControl/Transaction/KanbanJobPickingList.cdm.json/KanbanJobPickingList</a></td><td><a href="../Transaction/KanbanJobPickingList.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_KanbanJobSourceRequirementRelationshipId name="Relationship_KanbanJobSourceRequirementRelationshipId">Relationship_KanbanJobSourceRequirementRelationshipId</a>

First included in: WorksheetLine/KanbanSourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_KanbanJobSourceRequirementRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="KanbanJob.md" target="_blank">/core/erp/Tables/SupplyChain/ProductionControl/WorksheetLine/KanbanJob.cdm.json/KanbanJob</a></td><td><a href="KanbanJob.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_KanbanParentSourceRequirementRelationshipId name="Relationship_KanbanParentSourceRequirementRelationshipId">Relationship_KanbanParentSourceRequirementRelationshipId</a>

First included in: WorksheetLine/KanbanSourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_KanbanParentSourceRequirementRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/Kanban.md" target="_blank">/core/erp/Tables/SupplyChain/ProductionControl/WorksheetHeader/Kanban.cdm.json/Kanban</a></td><td><a href="../WorksheetHeader/Kanban.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_KanbanRootSourceRequirementRelationshipId name="Relationship_KanbanRootSourceRequirementRelationshipId">Relationship_KanbanRootSourceRequirementRelationshipId</a>

First included in: WorksheetLine/KanbanSourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_KanbanRootSourceRequirementRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/Kanban.md" target="_blank">/core/erp/Tables/SupplyChain/ProductionControl/WorksheetHeader/Kanban.cdm.json/Kanban</a></td><td><a href="../WorksheetHeader/Kanban.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_KanbanSourceRequirementRelationshipId name="Relationship_KanbanSourceRequirementRelationshipId">Relationship_KanbanSourceRequirementRelationshipId</a>

First included in: WorksheetLine/KanbanSourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_KanbanSourceRequirementRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/Kanban.md" target="_blank">/core/erp/Tables/SupplyChain/ProductionControl/WorksheetHeader/Kanban.cdm.json/Kanban</a></td><td><a href="../WorksheetHeader/Kanban.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProdBOMParentSourceRequirementRelationshipId name="Relationship_ProdBOMParentSourceRequirementRelationshipId">Relationship_ProdBOMParentSourceRequirementRelationshipId</a>

First included in: WorksheetLine/KanbanSourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProdBOMParentSourceRequirementRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="ProdBOM.md" target="_blank">/core/erp/Tables/SupplyChain/ProductionControl/WorksheetLine/ProdBOM.cdm.json/ProdBOM</a></td><td><a href="ProdBOM.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProdBOMRootSourceRequirementRelationshipId name="Relationship_ProdBOMRootSourceRequirementRelationshipId">Relationship_ProdBOMRootSourceRequirementRelationshipId</a>

First included in: WorksheetLine/KanbanSourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProdBOMRootSourceRequirementRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="ProdBOM.md" target="_blank">/core/erp/Tables/SupplyChain/ProductionControl/WorksheetLine/ProdBOM.cdm.json/ProdBOM</a></td><td><a href="ProdBOM.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProdBOMSourceRequirementRelationshipId name="Relationship_ProdBOMSourceRequirementRelationshipId">Relationship_ProdBOMSourceRequirementRelationshipId</a>

First included in: WorksheetLine/KanbanSourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProdBOMSourceRequirementRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="ProdBOM.md" target="_blank">/core/erp/Tables/SupplyChain/ProductionControl/WorksheetLine/ProdBOM.cdm.json/ProdBOM</a></td><td><a href="ProdBOM.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SalesLineParentSourceRequirementRelationshipId name="Relationship_SalesLineParentSourceRequirementRelationshipId">Relationship_SalesLineParentSourceRequirementRelationshipId</a>

First included in: WorksheetLine/KanbanSourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SalesLineParentSourceRequirementRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../SalesAndMarketing/WorksheetLine/SalesLine.md" target="_blank">/core/erp/Tables/SupplyChain/SalesAndMarketing/WorksheetLine/SalesLine.cdm.json/SalesLine</a></td><td><a href="../../SalesAndMarketing/WorksheetLine/SalesLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SalesLineRootSourceRequirementRelationshipId name="Relationship_SalesLineRootSourceRequirementRelationshipId">Relationship_SalesLineRootSourceRequirementRelationshipId</a>

First included in: WorksheetLine/KanbanSourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SalesLineRootSourceRequirementRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../SalesAndMarketing/WorksheetLine/SalesLine.md" target="_blank">/core/erp/Tables/SupplyChain/SalesAndMarketing/WorksheetLine/SalesLine.cdm.json/SalesLine</a></td><td><a href="../../SalesAndMarketing/WorksheetLine/SalesLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SalesLineSourceRequirementRelationshipId name="Relationship_SalesLineSourceRequirementRelationshipId">Relationship_SalesLineSourceRequirementRelationshipId</a>

First included in: WorksheetLine/KanbanSourceRequirement (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SalesLineSourceRequirementRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../SalesAndMarketing/WorksheetLine/SalesLine.md" target="_blank">/core/erp/Tables/SupplyChain/SalesAndMarketing/WorksheetLine/SalesLine.cdm.json/SalesLine</a></td><td><a href="../../SalesAndMarketing/WorksheetLine/SalesLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
