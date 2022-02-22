---
title: WHSCrossDockDemandSourceSelectionCriteria in Miscellaneous - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Selection criteria for cross docking demand source in Miscellaneous(WHSCrossDockDemandSourceSelectionCriteria)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/Inventory/Miscellaneous/WHSCrossDockDemandSourceSelectionCriteria.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[WHSCrossDockDemandSourceSelectionCriteria/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Selection criteria for cross docking demand source</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="WHSCrossDockDemandSourceSelectionCriteria.md" target="_blank">Miscellaneous/WHSCrossDockDemandSourceSelectionCriteria</a>|
|[DemandSourceType](#DemandSourceType)||<a href="WHSCrossDockDemandSourceSelectionCriteria.md" target="_blank">Miscellaneous/WHSCrossDockDemandSourceSelectionCriteria</a>|
|[Priority](#Priority)||<a href="WHSCrossDockDemandSourceSelectionCriteria.md" target="_blank">Miscellaneous/WHSCrossDockDemandSourceSelectionCriteria</a>|
|[CrossDockOpportunityPolicy](#CrossDockOpportunityPolicy)||<a href="WHSCrossDockDemandSourceSelectionCriteria.md" target="_blank">Miscellaneous/WHSCrossDockDemandSourceSelectionCriteria</a>|
|[RequiresLocation](#RequiresLocation)||<a href="WHSCrossDockDemandSourceSelectionCriteria.md" target="_blank">Miscellaneous/WHSCrossDockDemandSourceSelectionCriteria</a>|
|[CrossDockFulfillmentStrategy](#CrossDockFulfillmentStrategy)||<a href="WHSCrossDockDemandSourceSelectionCriteria.md" target="_blank">Miscellaneous/WHSCrossDockDemandSourceSelectionCriteria</a>|
|[DataAreaId](#DataAreaId)||<a href="WHSCrossDockDemandSourceSelectionCriteria.md" target="_blank">Miscellaneous/WHSCrossDockDemandSourceSelectionCriteria</a>|
|[Relationship_WHSCrossDockOpportunityPolicyRelationshipId](#Relationship_WHSCrossDockOpportunityPolicyRelationshipId)||<a href="WHSCrossDockDemandSourceSelectionCriteria.md" target="_blank">Miscellaneous/WHSCrossDockDemandSourceSelectionCriteria</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="WHSCrossDockDemandSourceSelectionCriteria.md" target="_blank">Miscellaneous/WHSCrossDockDemandSourceSelectionCriteria</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/WHSCrossDockDemandSourceSelectionCriteria (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[WHSCrossDockDemandSourceSelectionCriteria/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DemandSourceType name="DemandSourceType">DemandSourceType</a>

First included in: Miscellaneous/WHSCrossDockDemandSourceSelectionCriteria (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandSourceType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Priority name="Priority">Priority</a>

First included in: Miscellaneous/WHSCrossDockDemandSourceSelectionCriteria (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Priority attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CrossDockOpportunityPolicy name="CrossDockOpportunityPolicy">CrossDockOpportunityPolicy</a>

First included in: Miscellaneous/WHSCrossDockDemandSourceSelectionCriteria (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CrossDockOpportunityPolicy attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RequiresLocation name="RequiresLocation">RequiresLocation</a>

First included in: Miscellaneous/WHSCrossDockDemandSourceSelectionCriteria (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequiresLocation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CrossDockFulfillmentStrategy name="CrossDockFulfillmentStrategy">CrossDockFulfillmentStrategy</a>

First included in: Miscellaneous/WHSCrossDockDemandSourceSelectionCriteria (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CrossDockFulfillmentStrategy attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Miscellaneous/WHSCrossDockDemandSourceSelectionCriteria (this entity)  

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

### <a href=#Relationship_WHSCrossDockOpportunityPolicyRelationshipId name="Relationship_WHSCrossDockOpportunityPolicyRelationshipId">Relationship_WHSCrossDockOpportunityPolicyRelationshipId</a>

First included in: Miscellaneous/WHSCrossDockDemandSourceSelectionCriteria (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WHSCrossDockOpportunityPolicyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="WHSCrossDockOpportunityPolicy.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Miscellaneous/WHSCrossDockOpportunityPolicy.cdm.json/WHSCrossDockOpportunityPolicy</a></td><td><a href="WHSCrossDockOpportunityPolicy.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Miscellaneous/WHSCrossDockDemandSourceSelectionCriteria (this entity)  

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
