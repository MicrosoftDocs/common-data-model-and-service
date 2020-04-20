---
title: WHSShipConsolidationProposedShipmentContent - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# WHSShipConsolidationProposedShipmentContent

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/Inventory/Main/WHSShipConsolidationProposedShipmentContent.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[WHSShipConsolidationProposedShipmentContent/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="WHSShipConsolidationProposedShipmentContent.md" target="_blank">Main/WHSShipConsolidationProposedShipmentContent</a>|
|[DefaultProposedGroup](#DefaultProposedGroup)||<a href="WHSShipConsolidationProposedShipmentContent.md" target="_blank">Main/WHSShipConsolidationProposedShipmentContent</a>|
|[ProposedGroup](#ProposedGroup)||<a href="WHSShipConsolidationProposedShipmentContent.md" target="_blank">Main/WHSShipConsolidationProposedShipmentContent</a>|
|[ProposedShipment](#ProposedShipment)||<a href="WHSShipConsolidationProposedShipmentContent.md" target="_blank">Main/WHSShipConsolidationProposedShipmentContent</a>|
|[ShipConsolidationSession](#ShipConsolidationSession)||<a href="WHSShipConsolidationProposedShipmentContent.md" target="_blank">Main/WHSShipConsolidationProposedShipmentContent</a>|
|[ShipmentId](#ShipmentId)||<a href="WHSShipConsolidationProposedShipmentContent.md" target="_blank">Main/WHSShipConsolidationProposedShipmentContent</a>|
|[TotalVolume](#TotalVolume)||<a href="WHSShipConsolidationProposedShipmentContent.md" target="_blank">Main/WHSShipConsolidationProposedShipmentContent</a>|
|[TotalWeight](#TotalWeight)||<a href="WHSShipConsolidationProposedShipmentContent.md" target="_blank">Main/WHSShipConsolidationProposedShipmentContent</a>|
|[DataAreaId](#DataAreaId)||<a href="WHSShipConsolidationProposedShipmentContent.md" target="_blank">Main/WHSShipConsolidationProposedShipmentContent</a>|
|[Relationship_WHSShipConsolidationSessionRelationshipId](#Relationship_WHSShipConsolidationSessionRelationshipId)||<a href="WHSShipConsolidationProposedShipmentContent.md" target="_blank">Main/WHSShipConsolidationProposedShipmentContent</a>|
|[Relationship_WHSShipConsolidationProposedShipmentRelationshipId](#Relationship_WHSShipConsolidationProposedShipmentRelationshipId)||<a href="WHSShipConsolidationProposedShipmentContent.md" target="_blank">Main/WHSShipConsolidationProposedShipmentContent</a>|
|[Relationship_WHSShipmentTableRelationshipId](#Relationship_WHSShipmentTableRelationshipId)||<a href="WHSShipConsolidationProposedShipmentContent.md" target="_blank">Main/WHSShipConsolidationProposedShipmentContent</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="WHSShipConsolidationProposedShipmentContent.md" target="_blank">Main/WHSShipConsolidationProposedShipmentContent</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/WHSShipConsolidationProposedShipmentContent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[WHSShipConsolidationProposedShipmentContent/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DefaultProposedGroup name="DefaultProposedGroup">DefaultProposedGroup</a>

First included in: Main/WHSShipConsolidationProposedShipmentContent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultProposedGroup attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ProposedGroup name="ProposedGroup">ProposedGroup</a>

First included in: Main/WHSShipConsolidationProposedShipmentContent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProposedGroup attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ProposedShipment name="ProposedShipment">ProposedShipment</a>

First included in: Main/WHSShipConsolidationProposedShipmentContent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProposedShipment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ShipConsolidationSession name="ShipConsolidationSession">ShipConsolidationSession</a>

First included in: Main/WHSShipConsolidationProposedShipmentContent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShipConsolidationSession attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ShipmentId name="ShipmentId">ShipmentId</a>

First included in: Main/WHSShipConsolidationProposedShipmentContent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShipmentId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalVolume name="TotalVolume">TotalVolume</a>

First included in: Main/WHSShipConsolidationProposedShipmentContent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalVolume attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TotalWeight name="TotalWeight">TotalWeight</a>

First included in: Main/WHSShipConsolidationProposedShipmentContent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalWeight attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Main/WHSShipConsolidationProposedShipmentContent (this entity)  

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

### <a href=#Relationship_WHSShipConsolidationSessionRelationshipId name="Relationship_WHSShipConsolidationSessionRelationshipId">Relationship_WHSShipConsolidationSessionRelationshipId</a>

First included in: Main/WHSShipConsolidationProposedShipmentContent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WHSShipConsolidationSessionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="WHSShipConsolidationSession.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/WHSShipConsolidationSession.cdm.json/WHSShipConsolidationSession</a></td><td><a href="WHSShipConsolidationSession.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WHSShipConsolidationProposedShipmentRelationshipId name="Relationship_WHSShipConsolidationProposedShipmentRelationshipId">Relationship_WHSShipConsolidationProposedShipmentRelationshipId</a>

First included in: Main/WHSShipConsolidationProposedShipmentContent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WHSShipConsolidationProposedShipmentRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="WHSShipConsolidationProposedShipment.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/WHSShipConsolidationProposedShipment.cdm.json/WHSShipConsolidationProposedShipment</a></td><td><a href="WHSShipConsolidationProposedShipment.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WHSShipmentTableRelationshipId name="Relationship_WHSShipmentTableRelationshipId">Relationship_WHSShipmentTableRelationshipId</a>

First included in: Main/WHSShipConsolidationProposedShipmentContent (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WHSShipmentTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/WHSShipmentTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/WorksheetHeader/WHSShipmentTable.cdm.json/WHSShipmentTable</a></td><td><a href="../WorksheetHeader/WHSShipmentTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Main/WHSShipConsolidationProposedShipmentContent (this entity)  

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
