---
title: WHSWarehouseWorkTemplateLineEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Warehouse work template line

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/WMS/WHSWarehouseWorkTemplateLineEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Warehouse work template line</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[WarehouseWorkOrderType](#WarehouseWorkOrderType)||<a href="WHSWarehouseWorkTemplateLineEntity.md" target="_blank">WMS/WHSWarehouseWorkTemplateLineEntity</a>|
|[WarehouseWorkTemplateId](#WarehouseWorkTemplateId)||<a href="WHSWarehouseWorkTemplateLineEntity.md" target="_blank">WMS/WHSWarehouseWorkTemplateLineEntity</a>|
|[LineNumber](#LineNumber)||<a href="WHSWarehouseWorkTemplateLineEntity.md" target="_blank">WMS/WHSWarehouseWorkTemplateLineEntity</a>|
|[WorkOrderLineType](#WorkOrderLineType)||<a href="WHSWarehouseWorkTemplateLineEntity.md" target="_blank">WMS/WHSWarehouseWorkTemplateLineEntity</a>|
|[CustomWorkOrderLineType](#CustomWorkOrderLineType)||<a href="WHSWarehouseWorkTemplateLineEntity.md" target="_blank">WMS/WHSWarehouseWorkTemplateLineEntity</a>|
|[IsWorkLineMandatory](#IsWorkLineMandatory)||<a href="WHSWarehouseWorkTemplateLineEntity.md" target="_blank">WMS/WHSWarehouseWorkTemplateLineEntity</a>|
|[IsWorkExecutionStopped](#IsWorkExecutionStopped)||<a href="WHSWarehouseWorkTemplateLineEntity.md" target="_blank">WMS/WHSWarehouseWorkTemplateLineEntity</a>|
|[CanFreezeWork](#CanFreezeWork)||<a href="WHSWarehouseWorkTemplateLineEntity.md" target="_blank">WMS/WHSWarehouseWorkTemplateLineEntity</a>|
|[WarehouseLocationDirectiveCode](#WarehouseLocationDirectiveCode)||<a href="WHSWarehouseWorkTemplateLineEntity.md" target="_blank">WMS/WHSWarehouseWorkTemplateLineEntity</a>|
|[WarehouseWorkClassId](#WarehouseWorkClassId)||<a href="WHSWarehouseWorkTemplateLineEntity.md" target="_blank">WMS/WHSWarehouseWorkTemplateLineEntity</a>|
|[QualityCheckTemplateId](#QualityCheckTemplateId)||<a href="WHSWarehouseWorkTemplateLineEntity.md" target="_blank">WMS/WHSWarehouseWorkTemplateLineEntity</a>|
|[Relationship_WarehouseLocationDirectiveCodeRelationshipId](#Relationship_WarehouseLocationDirectiveCodeRelationshipId)||<a href="WHSWarehouseWorkTemplateLineEntity.md" target="_blank">WMS/WHSWarehouseWorkTemplateLineEntity</a>|
|[Relationship_WarehouseWorkClassRelationshipId](#Relationship_WarehouseWorkClassRelationshipId)||<a href="WHSWarehouseWorkTemplateLineEntity.md" target="_blank">WMS/WHSWarehouseWorkTemplateLineEntity</a>|
|[Relationship_CustomWarehouseWorkTypeRelationshipId](#Relationship_CustomWarehouseWorkTypeRelationshipId)||<a href="WHSWarehouseWorkTemplateLineEntity.md" target="_blank">WMS/WHSWarehouseWorkTemplateLineEntity</a>|
|[BackingTable_WHSWorkTemplateLineRelationshipId](#BackingTable_WHSWorkTemplateLineRelationshipId)||<a href="WHSWarehouseWorkTemplateLineEntity.md" target="_blank">WMS/WHSWarehouseWorkTemplateLineEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="WHSWarehouseWorkTemplateLineEntity.md" target="_blank">WMS/WHSWarehouseWorkTemplateLineEntity</a>|

### <a href=#WarehouseWorkOrderType name="WarehouseWorkOrderType">WarehouseWorkOrderType</a>

First included in: WMS/WHSWarehouseWorkTemplateLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseWorkOrderType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseWorkTemplateId name="WarehouseWorkTemplateId">WarehouseWorkTemplateId</a>

First included in: WMS/WHSWarehouseWorkTemplateLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseWorkTemplateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: WMS/WHSWarehouseWorkTemplateLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkOrderLineType name="WorkOrderLineType">WorkOrderLineType</a>

First included in: WMS/WHSWarehouseWorkTemplateLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkOrderLineType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomWorkOrderLineType name="CustomWorkOrderLineType">CustomWorkOrderLineType</a>

First included in: WMS/WHSWarehouseWorkTemplateLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomWorkOrderLineType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsWorkLineMandatory name="IsWorkLineMandatory">IsWorkLineMandatory</a>

First included in: WMS/WHSWarehouseWorkTemplateLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsWorkLineMandatory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsWorkExecutionStopped name="IsWorkExecutionStopped">IsWorkExecutionStopped</a>

First included in: WMS/WHSWarehouseWorkTemplateLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsWorkExecutionStopped attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CanFreezeWork name="CanFreezeWork">CanFreezeWork</a>

First included in: WMS/WHSWarehouseWorkTemplateLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CanFreezeWork attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseLocationDirectiveCode name="WarehouseLocationDirectiveCode">WarehouseLocationDirectiveCode</a>

First included in: WMS/WHSWarehouseWorkTemplateLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseLocationDirectiveCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseWorkClassId name="WarehouseWorkClassId">WarehouseWorkClassId</a>

First included in: WMS/WHSWarehouseWorkTemplateLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseWorkClassId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QualityCheckTemplateId name="QualityCheckTemplateId">QualityCheckTemplateId</a>

First included in: WMS/WHSWarehouseWorkTemplateLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QualityCheckTemplateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WarehouseLocationDirectiveCodeRelationshipId name="Relationship_WarehouseLocationDirectiveCodeRelationshipId">Relationship_WarehouseLocationDirectiveCodeRelationshipId</a>

First included in: WMS/WHSWarehouseWorkTemplateLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WarehouseLocationDirectiveCodeRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_WarehouseWorkClassRelationshipId name="Relationship_WarehouseWorkClassRelationshipId">Relationship_WarehouseWorkClassRelationshipId</a>

First included in: WMS/WHSWarehouseWorkTemplateLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WarehouseWorkClassRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_CustomWarehouseWorkTypeRelationshipId name="Relationship_CustomWarehouseWorkTypeRelationshipId">Relationship_CustomWarehouseWorkTypeRelationshipId</a>

First included in: WMS/WHSWarehouseWorkTemplateLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustomWarehouseWorkTypeRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_WHSWorkTemplateLineRelationshipId name="BackingTable_WHSWorkTemplateLineRelationshipId">BackingTable_WHSWorkTemplateLineRelationshipId</a>

First included in: WMS/WHSWarehouseWorkTemplateLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_WHSWorkTemplateLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Main/WHSWorkTemplateLine.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/WHSWorkTemplateLine.cdm.json/WHSWorkTemplateLine</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Main/WHSWorkTemplateLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: WMS/WHSWarehouseWorkTemplateLineEntity (this entity)  

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
