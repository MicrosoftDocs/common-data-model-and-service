---
title: ReqDemPlanForecastAzureMlParameters - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# Forecasting algorithm parameters

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/MasterPlanning/Miscellaneous/ReqDemPlanForecastAzureMlParameters.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ReqDemPlanForecastAzureMlParameters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Forecasting algorithm parameters</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="ReqDemPlanForecastAzureMlParameters.md" target="_blank">Miscellaneous/ReqDemPlanForecastAzureMlParameters</a>|
|[DefaultAlgorithmParameter](#DefaultAlgorithmParameter)||<a href="ReqDemPlanForecastAzureMlParameters.md" target="_blank">Miscellaneous/ReqDemPlanForecastAzureMlParameters</a>|
|[ForecastIAKParameters](#ForecastIAKParameters)||<a href="ReqDemPlanForecastAzureMlParameters.md" target="_blank">Miscellaneous/ReqDemPlanForecastAzureMlParameters</a>|
|[Value](#Value)||<a href="ReqDemPlanForecastAzureMlParameters.md" target="_blank">Miscellaneous/ReqDemPlanForecastAzureMlParameters</a>|
|[Relationship_ReqDemPlanDefaultAlgorithmParametersRelationshipId](#Relationship_ReqDemPlanDefaultAlgorithmParametersRelationshipId)||<a href="ReqDemPlanForecastAzureMlParameters.md" target="_blank">Miscellaneous/ReqDemPlanForecastAzureMlParameters</a>|
|[Relationship_ReqDemPlanForecastIAKParametersRelationshipId](#Relationship_ReqDemPlanForecastIAKParametersRelationshipId)||<a href="ReqDemPlanForecastAzureMlParameters.md" target="_blank">Miscellaneous/ReqDemPlanForecastAzureMlParameters</a>|
|[Relationship_ReqDemPlanForecastParametersRelationshipId](#Relationship_ReqDemPlanForecastParametersRelationshipId)||<a href="ReqDemPlanForecastAzureMlParameters.md" target="_blank">Miscellaneous/ReqDemPlanForecastAzureMlParameters</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/ReqDemPlanForecastAzureMlParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ReqDemPlanForecastAzureMlParameters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DefaultAlgorithmParameter name="DefaultAlgorithmParameter">DefaultAlgorithmParameter</a>

First included in: Miscellaneous/ReqDemPlanForecastAzureMlParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultAlgorithmParameter attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ForecastIAKParameters name="ForecastIAKParameters">ForecastIAKParameters</a>

First included in: Miscellaneous/ReqDemPlanForecastAzureMlParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForecastIAKParameters attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Value name="Value">Value</a>

First included in: Miscellaneous/ReqDemPlanForecastAzureMlParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Value attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ReqDemPlanDefaultAlgorithmParametersRelationshipId name="Relationship_ReqDemPlanDefaultAlgorithmParametersRelationshipId">Relationship_ReqDemPlanDefaultAlgorithmParametersRelationshipId</a>

First included in: Miscellaneous/ReqDemPlanForecastAzureMlParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReqDemPlanDefaultAlgorithmParametersRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="ReqDemPlanDefaultAlgorithmParameters.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/MasterPlanning/Miscellaneous/ReqDemPlanDefaultAlgorithmParameters.cdm.json/ReqDemPlanDefaultAlgorithmParameters</a></td><td><a href="ReqDemPlanDefaultAlgorithmParameters.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ReqDemPlanForecastIAKParametersRelationshipId name="Relationship_ReqDemPlanForecastIAKParametersRelationshipId">Relationship_ReqDemPlanForecastIAKParametersRelationshipId</a>

First included in: Miscellaneous/ReqDemPlanForecastAzureMlParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReqDemPlanForecastIAKParametersRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ReqDemPlanForecastParametersRelationshipId name="Relationship_ReqDemPlanForecastParametersRelationshipId">Relationship_ReqDemPlanForecastParametersRelationshipId</a>

First included in: Miscellaneous/ReqDemPlanForecastAzureMlParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReqDemPlanForecastParametersRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Parameter/ReqDemPlanForecastParameters.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/MasterPlanning/Parameter/ReqDemPlanForecastParameters.cdm.json/ReqDemPlanForecastParameters</a></td><td><a href="../Parameter/ReqDemPlanForecastParameters.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
