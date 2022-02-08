---
title: ReqDemPlanForecastIAKMap in Miscellaneous - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Demand Forecasting Item Allocation Key Map in Miscellaneous(ReqDemPlanForecastIAKMap)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/MasterPlanning/Miscellaneous/ReqDemPlanForecastIAKMap.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ReqDemPlanForecastIAKMap/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Demand Forecasting Item Allocation Key Map</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="ReqDemPlanForecastIAKMap.md" target="_blank">Miscellaneous/ReqDemPlanForecastIAKMap</a>|
|[ForecastItemAllocation](#ForecastItemAllocation)||<a href="ReqDemPlanForecastIAKMap.md" target="_blank">Miscellaneous/ReqDemPlanForecastIAKMap</a>|
|[ForecastItemAllocationDataAreaID](#ForecastItemAllocationDataAreaID)||<a href="ReqDemPlanForecastIAKMap.md" target="_blank">Miscellaneous/ReqDemPlanForecastIAKMap</a>|
|[ReqDemplanForecastIAKParameters](#ReqDemplanForecastIAKParameters)||<a href="ReqDemPlanForecastIAKMap.md" target="_blank">Miscellaneous/ReqDemPlanForecastIAKMap</a>|
|[Relationship_ForecastItemAllocationRelationshipId](#Relationship_ForecastItemAllocationRelationshipId)||<a href="ReqDemPlanForecastIAKMap.md" target="_blank">Miscellaneous/ReqDemPlanForecastIAKMap</a>|
|[Relationship_ReqDemplanForecastIAKParametersRelationshipId](#Relationship_ReqDemplanForecastIAKParametersRelationshipId)||<a href="ReqDemPlanForecastIAKMap.md" target="_blank">Miscellaneous/ReqDemPlanForecastIAKMap</a>|
|[Relationship_ReqDemPlanForecastAzureMlParametersRelationshipId](#Relationship_ReqDemPlanForecastAzureMlParametersRelationshipId)||<a href="ReqDemPlanForecastIAKMap.md" target="_blank">Miscellaneous/ReqDemPlanForecastIAKMap</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/ReqDemPlanForecastIAKMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ReqDemPlanForecastIAKMap/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ForecastItemAllocation name="ForecastItemAllocation">ForecastItemAllocation</a>

First included in: Miscellaneous/ReqDemPlanForecastIAKMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForecastItemAllocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ForecastItemAllocationDataAreaID name="ForecastItemAllocationDataAreaID">ForecastItemAllocationDataAreaID</a>

First included in: Miscellaneous/ReqDemPlanForecastIAKMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForecastItemAllocationDataAreaID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReqDemplanForecastIAKParameters name="ReqDemplanForecastIAKParameters">ReqDemplanForecastIAKParameters</a>

First included in: Miscellaneous/ReqDemPlanForecastIAKMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReqDemplanForecastIAKParameters attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_ForecastItemAllocationRelationshipId name="Relationship_ForecastItemAllocationRelationshipId">Relationship_ForecastItemAllocationRelationshipId</a>

First included in: Miscellaneous/ReqDemPlanForecastIAKMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ForecastItemAllocationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/ForecastItemAllocation.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/MasterPlanning/Group/ForecastItemAllocation.cdm.json/ForecastItemAllocation</a></td><td><a href="../Group/ForecastItemAllocation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ReqDemplanForecastIAKParametersRelationshipId name="Relationship_ReqDemplanForecastIAKParametersRelationshipId">Relationship_ReqDemplanForecastIAKParametersRelationshipId</a>

First included in: Miscellaneous/ReqDemPlanForecastIAKMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReqDemplanForecastIAKParametersRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="ReqDemplanForecastIAKParameters.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/MasterPlanning/Miscellaneous/ReqDemplanForecastIAKParameters.cdm.json/ReqDemplanForecastIAKParameters</a></td><td><a href="ReqDemplanForecastIAKParameters.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ReqDemPlanForecastAzureMlParametersRelationshipId name="Relationship_ReqDemPlanForecastAzureMlParametersRelationshipId">Relationship_ReqDemPlanForecastAzureMlParametersRelationshipId</a>

First included in: Miscellaneous/ReqDemPlanForecastIAKMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReqDemPlanForecastAzureMlParametersRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="ReqDemPlanForecastAzureMlParameters.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/MasterPlanning/Miscellaneous/ReqDemPlanForecastAzureMlParameters.cdm.json/ReqDemPlanForecastAzureMlParameters</a></td><td><a href="ReqDemPlanForecastAzureMlParameters.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
