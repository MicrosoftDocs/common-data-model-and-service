---
title: EngChgCaseBOMRouteVersionApproval in Miscellaneous - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/21/2020
ms.author: nebanfic
---

# Product change approvals for BOM versions, formula versions, and route versions in Miscellaneous(EngChgCaseBOMRouteVersionApproval)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Miscellaneous/EngChgCaseBOMRouteVersionApproval.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[EngChgCaseBOMRouteVersionApproval/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Product change approvals for BOM versions, formula versions, and route versions</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="EngChgCaseBOMRouteVersionApproval.md" target="_blank">Miscellaneous/EngChgCaseBOMRouteVersionApproval</a>|
|[ApprovalVersionAction](#ApprovalVersionAction)||<a href="EngChgCaseBOMRouteVersionApproval.md" target="_blank">Miscellaneous/EngChgCaseBOMRouteVersionApproval</a>|
|[EntityCaseAssociation](#EntityCaseAssociation)||<a href="EngChgCaseBOMRouteVersionApproval.md" target="_blank">Miscellaneous/EngChgCaseBOMRouteVersionApproval</a>|
|[EntityType](#EntityType)||<a href="EngChgCaseBOMRouteVersionApproval.md" target="_blank">Miscellaneous/EngChgCaseBOMRouteVersionApproval</a>|
|[EntityVersion](#EntityVersion)||<a href="EngChgCaseBOMRouteVersionApproval.md" target="_blank">Miscellaneous/EngChgCaseBOMRouteVersionApproval</a>|
|[ItemCaseAssociation](#ItemCaseAssociation)||<a href="EngChgCaseBOMRouteVersionApproval.md" target="_blank">Miscellaneous/EngChgCaseBOMRouteVersionApproval</a>|
|[OverrideEffectiveDate](#OverrideEffectiveDate)||<a href="EngChgCaseBOMRouteVersionApproval.md" target="_blank">Miscellaneous/EngChgCaseBOMRouteVersionApproval</a>|
|[Relationship_BOMFormulaVersionRelationshipId](#Relationship_BOMFormulaVersionRelationshipId)||<a href="EngChgCaseBOMRouteVersionApproval.md" target="_blank">Miscellaneous/EngChgCaseBOMRouteVersionApproval</a>|
|[Relationship_RouteVersionRelationshipId](#Relationship_RouteVersionRelationshipId)||<a href="EngChgCaseBOMRouteVersionApproval.md" target="_blank">Miscellaneous/EngChgCaseBOMRouteVersionApproval</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/EngChgCaseBOMRouteVersionApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[EngChgCaseBOMRouteVersionApproval/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ApprovalVersionAction name="ApprovalVersionAction">ApprovalVersionAction</a>

First included in: Miscellaneous/EngChgCaseBOMRouteVersionApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Action</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ApprovalVersionAction attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Action</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#EntityCaseAssociation name="EntityCaseAssociation">EntityCaseAssociation</a>

First included in: Miscellaneous/EngChgCaseBOMRouteVersionApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EntityCaseAssociation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#EntityType name="EntityType">EntityType</a>

First included in: Miscellaneous/EngChgCaseBOMRouteVersionApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EntityType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#EntityVersion name="EntityVersion">EntityVersion</a>

First included in: Miscellaneous/EngChgCaseBOMRouteVersionApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EntityVersion attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ItemCaseAssociation name="ItemCaseAssociation">ItemCaseAssociation</a>

First included in: Miscellaneous/EngChgCaseBOMRouteVersionApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemCaseAssociation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#OverrideEffectiveDate name="OverrideEffectiveDate">OverrideEffectiveDate</a>

First included in: Miscellaneous/EngChgCaseBOMRouteVersionApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OverrideEffectiveDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#Relationship_BOMFormulaVersionRelationshipId name="Relationship_BOMFormulaVersionRelationshipId">Relationship_BOMFormulaVersionRelationshipId</a>

First included in: Miscellaneous/EngChgCaseBOMRouteVersionApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BOMFormulaVersionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/BOMVersion.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/BOMVersion.cdm.json/BOMVersion</a></td><td><a href="../Main/BOMVersion.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RouteVersionRelationshipId name="Relationship_RouteVersionRelationshipId">Relationship_RouteVersionRelationshipId</a>

First included in: Miscellaneous/EngChgCaseBOMRouteVersionApproval (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RouteVersionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProductionControl/Main/RouteVersion.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/Main/RouteVersion.cdm.json/RouteVersion</a></td><td><a href="../../ProductionControl/Main/RouteVersion.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
