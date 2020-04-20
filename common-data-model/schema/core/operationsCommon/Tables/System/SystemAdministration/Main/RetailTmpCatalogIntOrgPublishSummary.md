---
title: RetailTmpCatalogIntOrgPublishSummary - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# RetailTmpCatalogIntOrgPublishSummary

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/System/SystemAdministration/Main/RetailTmpCatalogIntOrgPublishSummary.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailTmpCatalogIntOrgPublishSummary/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailTmpCatalogIntOrgPublishSummary.md" target="_blank">Main/RetailTmpCatalogIntOrgPublishSummary</a>|
|[Catalog](#Catalog)||<a href="RetailTmpCatalogIntOrgPublishSummary.md" target="_blank">Main/RetailTmpCatalogIntOrgPublishSummary</a>|
|[CatalogInternalOrg](#CatalogInternalOrg)||<a href="RetailTmpCatalogIntOrgPublishSummary.md" target="_blank">Main/RetailTmpCatalogIntOrgPublishSummary</a>|
|[InternalOrgName](#InternalOrgName)||<a href="RetailTmpCatalogIntOrgPublishSummary.md" target="_blank">Main/RetailTmpCatalogIntOrgPublishSummary</a>|
|[LastValidationDateTime](#LastValidationDateTime)||<a href="RetailTmpCatalogIntOrgPublishSummary.md" target="_blank">Main/RetailTmpCatalogIntOrgPublishSummary</a>|
|[ProductDeleteCount](#ProductDeleteCount)||<a href="RetailTmpCatalogIntOrgPublishSummary.md" target="_blank">Main/RetailTmpCatalogIntOrgPublishSummary</a>|
|[ProductNewCount](#ProductNewCount)||<a href="RetailTmpCatalogIntOrgPublishSummary.md" target="_blank">Main/RetailTmpCatalogIntOrgPublishSummary</a>|
|[ProductUpdateCount](#ProductUpdateCount)||<a href="RetailTmpCatalogIntOrgPublishSummary.md" target="_blank">Main/RetailTmpCatalogIntOrgPublishSummary</a>|
|[Relationship_CatalogRelationshipId](#Relationship_CatalogRelationshipId)||<a href="RetailTmpCatalogIntOrgPublishSummary.md" target="_blank">Main/RetailTmpCatalogIntOrgPublishSummary</a>|
|[Relationship_CatalogInternalOrgRelationshipId](#Relationship_CatalogInternalOrgRelationshipId)||<a href="RetailTmpCatalogIntOrgPublishSummary.md" target="_blank">Main/RetailTmpCatalogIntOrgPublishSummary</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/RetailTmpCatalogIntOrgPublishSummary (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailTmpCatalogIntOrgPublishSummary/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Catalog name="Catalog">Catalog</a>

First included in: Main/RetailTmpCatalogIntOrgPublishSummary (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Catalog attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CatalogInternalOrg name="CatalogInternalOrg">CatalogInternalOrg</a>

First included in: Main/RetailTmpCatalogIntOrgPublishSummary (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CatalogInternalOrg attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#InternalOrgName name="InternalOrgName">InternalOrgName</a>

First included in: Main/RetailTmpCatalogIntOrgPublishSummary (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InternalOrgName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LastValidationDateTime name="LastValidationDateTime">LastValidationDateTime</a>

First included in: Main/RetailTmpCatalogIntOrgPublishSummary (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LastValidationDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.dataFormat.date**  
</details>

### <a href=#ProductDeleteCount name="ProductDeleteCount">ProductDeleteCount</a>

First included in: Main/RetailTmpCatalogIntOrgPublishSummary (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductDeleteCount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ProductNewCount name="ProductNewCount">ProductNewCount</a>

First included in: Main/RetailTmpCatalogIntOrgPublishSummary (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductNewCount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ProductUpdateCount name="ProductUpdateCount">ProductUpdateCount</a>

First included in: Main/RetailTmpCatalogIntOrgPublishSummary (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductUpdateCount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_CatalogRelationshipId name="Relationship_CatalogRelationshipId">Relationship_CatalogRelationshipId</a>

First included in: Main/RetailTmpCatalogIntOrgPublishSummary (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CatalogRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Commerce/Retail/Main/Catalog.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Main/Catalog.cdm.json/Catalog</a></td><td><a href="../../../Commerce/Retail/Main/Catalog.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CatalogInternalOrgRelationshipId name="Relationship_CatalogInternalOrgRelationshipId">Relationship_CatalogInternalOrgRelationshipId</a>

First included in: Main/RetailTmpCatalogIntOrgPublishSummary (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CatalogInternalOrgRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Commerce/Retail/Main/RetailCatalogInternalOrg.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Main/RetailCatalogInternalOrg.cdm.json/RetailCatalogInternalOrg</a></td><td><a href="../../../Commerce/Retail/Main/RetailCatalogInternalOrg.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
