---
title: RetailPubRetailChannelCategoryAttribute - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# RetailPubRetailChannelCategoryAttribute

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Commerce/Retail/Miscellaneous/RetailPubRetailChannelCategoryAttribute.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailPubRetailChannelCategoryAttribute/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailPubRetailChannelCategoryAttribute.md" target="_blank">Miscellaneous/RetailPubRetailChannelCategoryAttribute</a>|
|[Attribute](#Attribute)||<a href="RetailPubRetailChannelCategoryAttribute.md" target="_blank">Miscellaneous/RetailPubRetailChannelCategoryAttribute</a>|
|[AttributeValue](#AttributeValue)||<a href="RetailPubRetailChannelCategoryAttribute.md" target="_blank">Miscellaneous/RetailPubRetailChannelCategoryAttribute</a>|
|[Category](#Category)||<a href="RetailPubRetailChannelCategoryAttribute.md" target="_blank">Miscellaneous/RetailPubRetailChannelCategoryAttribute</a>|
|[HostChannel](#HostChannel)||<a href="RetailPubRetailChannelCategoryAttribute.md" target="_blank">Miscellaneous/RetailPubRetailChannelCategoryAttribute</a>|
|[KeyName](#KeyName)||<a href="RetailPubRetailChannelCategoryAttribute.md" target="_blank">Miscellaneous/RetailPubRetailChannelCategoryAttribute</a>|
|[OriginId](#OriginId)||<a href="RetailPubRetailChannelCategoryAttribute.md" target="_blank">Miscellaneous/RetailPubRetailChannelCategoryAttribute</a>|
|[OriginRecVersion](#OriginRecVersion)||<a href="RetailPubRetailChannelCategoryAttribute.md" target="_blank">Miscellaneous/RetailPubRetailChannelCategoryAttribute</a>|
|[Relationship_EcoResAttributeRelationshipId](#Relationship_EcoResAttributeRelationshipId)||<a href="RetailPubRetailChannelCategoryAttribute.md" target="_blank">Miscellaneous/RetailPubRetailChannelCategoryAttribute</a>|
|[Relationship_EcoResCategoryRelationshipId](#Relationship_EcoResCategoryRelationshipId)||<a href="RetailPubRetailChannelCategoryAttribute.md" target="_blank">Miscellaneous/RetailPubRetailChannelCategoryAttribute</a>|
|[Relationship_EcoResValueRelationshipId](#Relationship_EcoResValueRelationshipId)||<a href="RetailPubRetailChannelCategoryAttribute.md" target="_blank">Miscellaneous/RetailPubRetailChannelCategoryAttribute</a>|
|[Relationship_RetailChannelTableRelationshipId](#Relationship_RetailChannelTableRelationshipId)||<a href="RetailPubRetailChannelCategoryAttribute.md" target="_blank">Miscellaneous/RetailPubRetailChannelCategoryAttribute</a>|
|[Relationship_RetailPubRetailChannelTableRelationshipId](#Relationship_RetailPubRetailChannelTableRelationshipId)||<a href="RetailPubRetailChannelCategoryAttribute.md" target="_blank">Miscellaneous/RetailPubRetailChannelCategoryAttribute</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/RetailPubRetailChannelCategoryAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailPubRetailChannelCategoryAttribute/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Attribute name="Attribute">Attribute</a>

First included in: Miscellaneous/RetailPubRetailChannelCategoryAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Attribute attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AttributeValue name="AttributeValue">AttributeValue</a>

First included in: Miscellaneous/RetailPubRetailChannelCategoryAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AttributeValue attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Category name="Category">Category</a>

First included in: Miscellaneous/RetailPubRetailChannelCategoryAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Category attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#HostChannel name="HostChannel">HostChannel</a>

First included in: Miscellaneous/RetailPubRetailChannelCategoryAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HostChannel attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#KeyName name="KeyName">KeyName</a>

First included in: Miscellaneous/RetailPubRetailChannelCategoryAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the KeyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OriginId name="OriginId">OriginId</a>

First included in: Miscellaneous/RetailPubRetailChannelCategoryAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#OriginRecVersion name="OriginRecVersion">OriginRecVersion</a>

First included in: Miscellaneous/RetailPubRetailChannelCategoryAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginRecVersion attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Relationship_EcoResAttributeRelationshipId name="Relationship_EcoResAttributeRelationshipId">Relationship_EcoResAttributeRelationshipId</a>

First included in: Miscellaneous/RetailPubRetailChannelCategoryAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EcoResAttributeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResAttribute.md" target="_blank">/core/erp/Tables/SupplyChain/ProductInformationManagement/Main/EcoResAttribute.cdm.json/EcoResAttribute</a></td><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResAttribute.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_EcoResCategoryRelationshipId name="Relationship_EcoResCategoryRelationshipId">Relationship_EcoResCategoryRelationshipId</a>

First included in: Miscellaneous/RetailPubRetailChannelCategoryAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EcoResCategoryRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResCategory.md" target="_blank">/core/erp/Tables/SupplyChain/ProductInformationManagement/Main/EcoResCategory.cdm.json/EcoResCategory</a></td><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResCategory.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_EcoResValueRelationshipId name="Relationship_EcoResValueRelationshipId">Relationship_EcoResValueRelationshipId</a>

First included in: Miscellaneous/RetailPubRetailChannelCategoryAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EcoResValueRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResValue.md" target="_blank">/core/erp/Tables/SupplyChain/ProductInformationManagement/Main/EcoResValue.cdm.json/EcoResValue</a></td><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResValue.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailChannelTableRelationshipId name="Relationship_RetailChannelTableRelationshipId">Relationship_RetailChannelTableRelationshipId</a>

First included in: Miscellaneous/RetailPubRetailChannelCategoryAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailChannelTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/RetailChannelTable.md" target="_blank">/core/erp/Tables/Commerce/Retail/Main/RetailChannelTable.cdm.json/RetailChannelTable</a></td><td><a href="../Main/RetailChannelTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailPubRetailChannelTableRelationshipId name="Relationship_RetailPubRetailChannelTableRelationshipId">Relationship_RetailPubRetailChannelTableRelationshipId</a>

First included in: Miscellaneous/RetailPubRetailChannelCategoryAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailPubRetailChannelTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailPubRetailChannelTable.md" target="_blank">/core/erp/Tables/Commerce/Retail/Miscellaneous/RetailPubRetailChannelTable.cdm.json/RetailPubRetailChannelTable</a></td><td><a href="RetailPubRetailChannelTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
