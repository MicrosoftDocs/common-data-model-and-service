---
title: RetailTmpCatProdInternalOrgInstanceVal - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# RetailTmpCatProdInternalOrgInstanceVal

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/System/SystemAdministration/Main/RetailTmpCatProdInternalOrgInstanceVal.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailTmpCatProdInternalOrgInstanceVal/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailTmpCatProdInternalOrgInstanceVal.md" target="_blank">Main/RetailTmpCatProdInternalOrgInstanceVal</a>|
|[CatalogProduct](#CatalogProduct)||<a href="RetailTmpCatProdInternalOrgInstanceVal.md" target="_blank">Main/RetailTmpCatProdInternalOrgInstanceVal</a>|
|[InstanceValue](#InstanceValue)||<a href="RetailTmpCatProdInternalOrgInstanceVal.md" target="_blank">Main/RetailTmpCatProdInternalOrgInstanceVal</a>|
|[InternalOrganization](#InternalOrganization)||<a href="RetailTmpCatProdInternalOrgInstanceVal.md" target="_blank">Main/RetailTmpCatProdInternalOrgInstanceVal</a>|
|[Relationship_CatalogProductRelationshipId](#Relationship_CatalogProductRelationshipId)||<a href="RetailTmpCatProdInternalOrgInstanceVal.md" target="_blank">Main/RetailTmpCatProdInternalOrgInstanceVal</a>|
|[Relationship_InternalOrganizationRelationshipId](#Relationship_InternalOrganizationRelationshipId)||<a href="RetailTmpCatProdInternalOrgInstanceVal.md" target="_blank">Main/RetailTmpCatProdInternalOrgInstanceVal</a>|
|[Relationship_RetailCatalogProdInternalOrgInstanceValRelationshipId](#Relationship_RetailCatalogProdInternalOrgInstanceValRelationshipId)||<a href="RetailTmpCatProdInternalOrgInstanceVal.md" target="_blank">Main/RetailTmpCatProdInternalOrgInstanceVal</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/RetailTmpCatProdInternalOrgInstanceVal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailTmpCatProdInternalOrgInstanceVal/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CatalogProduct name="CatalogProduct">CatalogProduct</a>

First included in: Main/RetailTmpCatProdInternalOrgInstanceVal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CatalogProduct attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#InstanceValue name="InstanceValue">InstanceValue</a>

First included in: Main/RetailTmpCatProdInternalOrgInstanceVal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InstanceValue attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#InternalOrganization name="InternalOrganization">InternalOrganization</a>

First included in: Main/RetailTmpCatProdInternalOrgInstanceVal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InternalOrganization attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_CatalogProductRelationshipId name="Relationship_CatalogProductRelationshipId">Relationship_CatalogProductRelationshipId</a>

First included in: Main/RetailTmpCatProdInternalOrgInstanceVal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CatalogProductRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Commerce/Retail/Miscellaneous/CatalogProduct.md" target="_blank">/core/erp/Tables/Commerce/Retail/Miscellaneous/CatalogProduct.cdm.json/CatalogProduct</a></td><td><a href="../../../Commerce/Retail/Miscellaneous/CatalogProduct.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InternalOrganizationRelationshipId name="Relationship_InternalOrganizationRelationshipId">Relationship_InternalOrganizationRelationshipId</a>

First included in: Main/RetailTmpCatProdInternalOrgInstanceVal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InternalOrganizationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Commerce/Retail/Main/RetailInternalOrganization.md" target="_blank">/core/erp/Tables/Commerce/Retail/Main/RetailInternalOrganization.cdm.json/RetailInternalOrganization</a></td><td><a href="../../../Commerce/Retail/Main/RetailInternalOrganization.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailCatalogProdInternalOrgInstanceValRelationshipId name="Relationship_RetailCatalogProdInternalOrgInstanceValRelationshipId">Relationship_RetailCatalogProdInternalOrgInstanceValRelationshipId</a>

First included in: Main/RetailTmpCatProdInternalOrgInstanceVal (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailCatalogProdInternalOrgInstanceValRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Commerce/Retail/Main/RetailCatalogProdInternalOrgInstanceVal.md" target="_blank">/core/erp/Tables/Commerce/Retail/Main/RetailCatalogProdInternalOrgInstanceVal.cdm.json/RetailCatalogProdInternalOrgInstanceVal</a></td><td><a href="../../../Commerce/Retail/Main/RetailCatalogProdInternalOrgInstanceVal.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
