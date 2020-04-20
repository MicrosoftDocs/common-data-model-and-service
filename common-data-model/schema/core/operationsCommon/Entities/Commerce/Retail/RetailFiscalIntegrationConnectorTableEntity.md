---
title: RetailFiscalIntegrationConnectorTableEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# RetailFiscalIntegrationConnectorTableEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Commerce/Retail/RetailFiscalIntegrationConnectorTableEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ConnectorName](#ConnectorName)||<a href="RetailFiscalIntegrationConnectorTableEntity.md" target="_blank">Retail/RetailFiscalIntegrationConnectorTableEntity</a>|
|[Description](#Description)||<a href="RetailFiscalIntegrationConnectorTableEntity.md" target="_blank">Retail/RetailFiscalIntegrationConnectorTableEntity</a>|
|[Manifest](#Manifest)||<a href="RetailFiscalIntegrationConnectorTableEntity.md" target="_blank">Retail/RetailFiscalIntegrationConnectorTableEntity</a>|
|[BackingTable_RetailFiscalIntegrationConnectorTableRelationshipId](#BackingTable_RetailFiscalIntegrationConnectorTableRelationshipId)||<a href="RetailFiscalIntegrationConnectorTableEntity.md" target="_blank">Retail/RetailFiscalIntegrationConnectorTableEntity</a>|

### <a href=#ConnectorName name="ConnectorName">ConnectorName</a>

First included in: Retail/RetailFiscalIntegrationConnectorTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConnectorName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: Retail/RetailFiscalIntegrationConnectorTableEntity (this entity)  

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

### <a href=#Manifest name="Manifest">Manifest</a>

First included in: Retail/RetailFiscalIntegrationConnectorTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Manifest attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_RetailFiscalIntegrationConnectorTableRelationshipId name="BackingTable_RetailFiscalIntegrationConnectorTableRelationshipId">BackingTable_RetailFiscalIntegrationConnectorTableRelationshipId</a>

First included in: Retail/RetailFiscalIntegrationConnectorTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailFiscalIntegrationConnectorTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Commerce/Retail/Miscellaneous/RetailFiscalIntegrationConnectorTable.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Miscellaneous/RetailFiscalIntegrationConnectorTable.cdm.json/RetailFiscalIntegrationConnectorTable</a></td><td><a href="../../../Tables/Commerce/Retail/Miscellaneous/RetailFiscalIntegrationConnectorTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
