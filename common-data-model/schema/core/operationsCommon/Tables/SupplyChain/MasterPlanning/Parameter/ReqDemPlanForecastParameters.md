---
title: ReqDemPlanForecastParameters - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# ReqDemPlanForecastParameters

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/MasterPlanning/Parameter/ReqDemPlanForecastParameters.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ReqDemPlanForecastParameters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="ReqDemPlanForecastParameters.md" target="_blank">Parameter/ReqDemPlanForecastParameters</a>|
|[ForecastingUnitOfMeasure](#ForecastingUnitOfMeasure)||<a href="ReqDemPlanForecastParameters.md" target="_blank">Parameter/ReqDemPlanForecastParameters</a>|
|[Key](#Key)||<a href="ReqDemPlanForecastParameters.md" target="_blank">Parameter/ReqDemPlanForecastParameters</a>|
|[ReqDemplanForecastIAKParameters](#ReqDemplanForecastIAKParameters)||<a href="ReqDemPlanForecastParameters.md" target="_blank">Parameter/ReqDemPlanForecastParameters</a>|
|[AzureMlApiKey](#AzureMlApiKey)||<a href="ReqDemPlanForecastParameters.md" target="_blank">Parameter/ReqDemPlanForecastParameters</a>|
|[AzureMlServiceEndpointUri](#AzureMlServiceEndpointUri)||<a href="ReqDemPlanForecastParameters.md" target="_blank">Parameter/ReqDemPlanForecastParameters</a>|
|[AzureMlUseRequestResponseMode](#AzureMlUseRequestResponseMode)||<a href="ReqDemPlanForecastParameters.md" target="_blank">Parameter/ReqDemPlanForecastParameters</a>|
|[AzureStorageAccountName](#AzureStorageAccountName)||<a href="ReqDemPlanForecastParameters.md" target="_blank">Parameter/ReqDemPlanForecastParameters</a>|
|[AzureStorageAccountKey](#AzureStorageAccountKey)||<a href="ReqDemPlanForecastParameters.md" target="_blank">Parameter/ReqDemPlanForecastParameters</a>|
|[UseCustomAzureStorage](#UseCustomAzureStorage)||<a href="ReqDemPlanForecastParameters.md" target="_blank">Parameter/ReqDemPlanForecastParameters</a>|
|[Relationship_ReqDemPlanForecastIAKParametersRelationshipId](#Relationship_ReqDemPlanForecastIAKParametersRelationshipId)||<a href="ReqDemPlanForecastParameters.md" target="_blank">Parameter/ReqDemPlanForecastParameters</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Parameter/ReqDemPlanForecastParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ReqDemPlanForecastParameters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ForecastingUnitOfMeasure name="ForecastingUnitOfMeasure">ForecastingUnitOfMeasure</a>

First included in: Parameter/ReqDemPlanForecastParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForecastingUnitOfMeasure attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Key name="Key">Key</a>

First included in: Parameter/ReqDemPlanForecastParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Key attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReqDemplanForecastIAKParameters name="ReqDemplanForecastIAKParameters">ReqDemplanForecastIAKParameters</a>

First included in: Parameter/ReqDemPlanForecastParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReqDemplanForecastIAKParameters attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AzureMlApiKey name="AzureMlApiKey">AzureMlApiKey</a>

First included in: Parameter/ReqDemPlanForecastParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AzureMlApiKey attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AzureMlServiceEndpointUri name="AzureMlServiceEndpointUri">AzureMlServiceEndpointUri</a>

First included in: Parameter/ReqDemPlanForecastParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AzureMlServiceEndpointUri attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AzureMlUseRequestResponseMode name="AzureMlUseRequestResponseMode">AzureMlUseRequestResponseMode</a>

First included in: Parameter/ReqDemPlanForecastParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AzureMlUseRequestResponseMode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AzureStorageAccountName name="AzureStorageAccountName">AzureStorageAccountName</a>

First included in: Parameter/ReqDemPlanForecastParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AzureStorageAccountName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AzureStorageAccountKey name="AzureStorageAccountKey">AzureStorageAccountKey</a>

First included in: Parameter/ReqDemPlanForecastParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AzureStorageAccountKey attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseCustomAzureStorage name="UseCustomAzureStorage">UseCustomAzureStorage</a>

First included in: Parameter/ReqDemPlanForecastParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseCustomAzureStorage attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Relationship_ReqDemPlanForecastIAKParametersRelationshipId name="Relationship_ReqDemPlanForecastIAKParametersRelationshipId">Relationship_ReqDemPlanForecastIAKParametersRelationshipId</a>

First included in: Parameter/ReqDemPlanForecastParameters (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/ReqDemplanForecastIAKParameters.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/MasterPlanning/Miscellaneous/ReqDemplanForecastIAKParameters.cdm.json/ReqDemplanForecastIAKParameters</a></td><td><a href="../Miscellaneous/ReqDemplanForecastIAKParameters.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
