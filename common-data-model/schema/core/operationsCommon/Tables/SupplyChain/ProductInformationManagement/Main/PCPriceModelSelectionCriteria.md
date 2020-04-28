---
title: PCPriceModelSelectionCriteria - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Price model criteria

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/PCPriceModelSelectionCriteria.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PCPriceModelSelectionCriteria/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Price model criteria</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="PCPriceModelSelectionCriteria.md" target="_blank">Main/PCPriceModelSelectionCriteria</a>|
|[Description](#Description)||<a href="PCPriceModelSelectionCriteria.md" target="_blank">Main/PCPriceModelSelectionCriteria</a>|
|[Name](#Name)||<a href="PCPriceModelSelectionCriteria.md" target="_blank">Main/PCPriceModelSelectionCriteria</a>|
|[OrderlineTypeSelectionCriteria](#OrderlineTypeSelectionCriteria)||<a href="PCPriceModelSelectionCriteria.md" target="_blank">Main/PCPriceModelSelectionCriteria</a>|
|[packedQuery](#packedQuery)||<a href="PCPriceModelSelectionCriteria.md" target="_blank">Main/PCPriceModelSelectionCriteria</a>|
|[priceModel](#priceModel)||<a href="PCPriceModelSelectionCriteria.md" target="_blank">Main/PCPriceModelSelectionCriteria</a>|
|[ProductConfigurationModel](#ProductConfigurationModel)||<a href="PCPriceModelSelectionCriteria.md" target="_blank">Main/PCPriceModelSelectionCriteria</a>|
|[SearchSequence](#SearchSequence)||<a href="PCPriceModelSelectionCriteria.md" target="_blank">Main/PCPriceModelSelectionCriteria</a>|
|[ValidFromDate](#ValidFromDate)||<a href="PCPriceModelSelectionCriteria.md" target="_blank">Main/PCPriceModelSelectionCriteria</a>|
|[ValidToDate](#ValidToDate)||<a href="PCPriceModelSelectionCriteria.md" target="_blank">Main/PCPriceModelSelectionCriteria</a>|
|[DataAreaId](#DataAreaId)||<a href="PCPriceModelSelectionCriteria.md" target="_blank">Main/PCPriceModelSelectionCriteria</a>|
|[Relationship_PCOrderlineTypeSelectionCriteriaRelationshipId](#Relationship_PCOrderlineTypeSelectionCriteriaRelationshipId)||<a href="PCPriceModelSelectionCriteria.md" target="_blank">Main/PCPriceModelSelectionCriteria</a>|
|[Relationship_PCPriceModelRelationshipId](#Relationship_PCPriceModelRelationshipId)||<a href="PCPriceModelSelectionCriteria.md" target="_blank">Main/PCPriceModelSelectionCriteria</a>|
|[Relationship_PCProductConfigurationModelRelationshipId](#Relationship_PCProductConfigurationModelRelationshipId)||<a href="PCPriceModelSelectionCriteria.md" target="_blank">Main/PCPriceModelSelectionCriteria</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="PCPriceModelSelectionCriteria.md" target="_blank">Main/PCPriceModelSelectionCriteria</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/PCPriceModelSelectionCriteria (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PCPriceModelSelectionCriteria/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: Main/PCPriceModelSelectionCriteria (this entity)  

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

### <a href=#Name name="Name">Name</a>

First included in: Main/PCPriceModelSelectionCriteria (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrderlineTypeSelectionCriteria name="OrderlineTypeSelectionCriteria">OrderlineTypeSelectionCriteria</a>

First included in: Main/PCPriceModelSelectionCriteria (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderlineTypeSelectionCriteria attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#packedQuery name="packedQuery">packedQuery</a>

First included in: Main/PCPriceModelSelectionCriteria (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr></table>

#### Traits

<details>
<summary>List of traits for the packedQuery attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#priceModel name="priceModel">priceModel</a>

First included in: Main/PCPriceModelSelectionCriteria (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the priceModel attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ProductConfigurationModel name="ProductConfigurationModel">ProductConfigurationModel</a>

First included in: Main/PCPriceModelSelectionCriteria (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Product configuration model</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductConfigurationModel attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Product configuration model</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SearchSequence name="SearchSequence">SearchSequence</a>

First included in: Main/PCPriceModelSelectionCriteria (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SearchSequence attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ValidFromDate name="ValidFromDate">ValidFromDate</a>

First included in: Main/PCPriceModelSelectionCriteria (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidFromDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#ValidToDate name="ValidToDate">ValidToDate</a>

First included in: Main/PCPriceModelSelectionCriteria (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidToDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Main/PCPriceModelSelectionCriteria (this entity)  

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

### <a href=#Relationship_PCOrderlineTypeSelectionCriteriaRelationshipId name="Relationship_PCOrderlineTypeSelectionCriteriaRelationshipId">Relationship_PCOrderlineTypeSelectionCriteriaRelationshipId</a>

First included in: Main/PCPriceModelSelectionCriteria (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PCOrderlineTypeSelectionCriteriaRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="PCOrderlineTypeSelectionCriteria.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/PCOrderlineTypeSelectionCriteria.cdm.json/PCOrderlineTypeSelectionCriteria</a></td><td><a href="PCOrderlineTypeSelectionCriteria.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PCPriceModelRelationshipId name="Relationship_PCPriceModelRelationshipId">Relationship_PCPriceModelRelationshipId</a>

First included in: Main/PCPriceModelSelectionCriteria (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PCPriceModelRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="PCPriceModel.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/PCPriceModel.cdm.json/PCPriceModel</a></td><td><a href="PCPriceModel.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PCProductConfigurationModelRelationshipId name="Relationship_PCProductConfigurationModelRelationshipId">Relationship_PCProductConfigurationModelRelationshipId</a>

First included in: Main/PCPriceModelSelectionCriteria (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PCProductConfigurationModelRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="PCProductConfigurationModel.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/PCProductConfigurationModel.cdm.json/PCProductConfigurationModel</a></td><td><a href="PCProductConfigurationModel.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Main/PCPriceModelSelectionCriteria (this entity)  

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
