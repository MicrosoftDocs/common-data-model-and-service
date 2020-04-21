---
title: EcoResProductMasterSize - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# EcoResProductMasterSize

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/EcoResProductMasterSize.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[EcoResProductMasterSize/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="EcoResProductMasterSize.md" target="_blank">Main/EcoResProductMasterSize</a>|
|[InstanceRelationType](#InstanceRelationType)||<a href="EcoResProductMasterSize.md" target="_blank">Main/EcoResProductMasterSize</a>|
|[RetailDisplayOrder](#RetailDisplayOrder)||<a href="EcoResProductMasterSize.md" target="_blank">Main/EcoResProductMasterSize</a>|
|[RetailWeight](#RetailWeight)||<a href="EcoResProductMasterSize.md" target="_blank">Main/EcoResProductMasterSize</a>|
|[Size](#Size)||<a href="EcoResProductMasterSize.md" target="_blank">Main/EcoResProductMasterSize</a>|
|[SizeProductDimensionAttribute](#SizeProductDimensionAttribute)||<a href="EcoResProductMasterSize.md" target="_blank">Main/EcoResProductMasterSize</a>|
|[SizeProductMaster](#SizeProductMaster)||<a href="EcoResProductMasterSize.md" target="_blank">Main/EcoResProductMasterSize</a>|
|[ExtensionSizeDimensionGroupId](#ExtensionSizeDimensionGroupId)||<a href="EcoResProductMasterSize.md" target="_blank">Main/EcoResProductMasterSize</a>|
|[Relationship_EcoResSizeRelationshipId](#Relationship_EcoResSizeRelationshipId)||<a href="EcoResProductMasterSize.md" target="_blank">Main/EcoResProductMasterSize</a>|
|[Relationship_SizeEcoResProductDimensionAttributeRelationshipId](#Relationship_SizeEcoResProductDimensionAttributeRelationshipId)||<a href="EcoResProductMasterSize.md" target="_blank">Main/EcoResProductMasterSize</a>|
|[Relationship_SizeEcoResProductMasterRelationshipId](#Relationship_SizeEcoResProductMasterRelationshipId)||<a href="EcoResProductMasterSize.md" target="_blank">Main/EcoResProductMasterSize</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/EcoResProductMasterSize (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[EcoResProductMasterSize/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#InstanceRelationType name="InstanceRelationType">InstanceRelationType</a>

First included in: Main/EcoResProductMasterSize (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InstanceRelationType attribute are listed below.</summary>

**is.readOnly**  
</details>

### <a href=#RetailDisplayOrder name="RetailDisplayOrder">RetailDisplayOrder</a>

First included in: Main/EcoResProductMasterSize (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailDisplayOrder attribute are listed below.</summary>

</details>

### <a href=#RetailWeight name="RetailWeight">RetailWeight</a>

First included in: Main/EcoResProductMasterSize (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailWeight attribute are listed below.</summary>

</details>

### <a href=#Size name="Size">Size</a>

First included in: Main/EcoResProductMasterSize (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Size attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SizeProductDimensionAttribute name="SizeProductDimensionAttribute">SizeProductDimensionAttribute</a>

First included in: Main/EcoResProductMasterSize (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SizeProductDimensionAttribute attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SizeProductMaster name="SizeProductMaster">SizeProductMaster</a>

First included in: Main/EcoResProductMasterSize (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SizeProductMaster attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ExtensionSizeDimensionGroupId name="ExtensionSizeDimensionGroupId">ExtensionSizeDimensionGroupId</a>

First included in: Main/EcoResProductMasterSize (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExtensionSizeDimensionGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_EcoResSizeRelationshipId name="Relationship_EcoResSizeRelationshipId">Relationship_EcoResSizeRelationshipId</a>

First included in: Main/EcoResProductMasterSize (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EcoResSizeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="EcoResSize.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/EcoResSize.cdm.json/EcoResSize</a></td><td><a href="EcoResSize.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SizeEcoResProductDimensionAttributeRelationshipId name="Relationship_SizeEcoResProductDimensionAttributeRelationshipId">Relationship_SizeEcoResProductDimensionAttributeRelationshipId</a>

First included in: Main/EcoResProductMasterSize (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SizeEcoResProductDimensionAttributeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/EcoResProductDimensionAttribute.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Group/EcoResProductDimensionAttribute.cdm.json/EcoResProductDimensionAttribute</a></td><td><a href="../Group/EcoResProductDimensionAttribute.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SizeEcoResProductMasterRelationshipId name="Relationship_SizeEcoResProductMasterRelationshipId">Relationship_SizeEcoResProductMasterRelationshipId</a>

First included in: Main/EcoResProductMasterSize (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SizeEcoResProductMasterRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="EcoResProductMaster.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/EcoResProductMaster.cdm.json/EcoResProductMaster</a></td><td><a href="EcoResProductMaster.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
