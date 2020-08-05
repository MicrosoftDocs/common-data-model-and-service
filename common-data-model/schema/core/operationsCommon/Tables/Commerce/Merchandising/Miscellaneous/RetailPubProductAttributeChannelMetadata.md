---
title: RetailPubProductAttributeChannelMetadata in Miscellaneous - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Product attribute metadata in Miscellaneous(RetailPubProductAttributeChannelMetadata)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Commerce/Merchandising/Miscellaneous/RetailPubProductAttributeChannelMetadata.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailPubProductAttributeChannelMetadata/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Product attribute metadata</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailPubProductAttributeChannelMetadata.md" target="_blank">Miscellaneous/RetailPubProductAttributeChannelMetadata</a>|
|[Attribute](#Attribute)||<a href="RetailPubProductAttributeChannelMetadata.md" target="_blank">Miscellaneous/RetailPubProductAttributeChannelMetadata</a>|
|[AttributeDisplayOrder](#AttributeDisplayOrder)||<a href="RetailPubProductAttributeChannelMetadata.md" target="_blank">Miscellaneous/RetailPubProductAttributeChannelMetadata</a>|
|[AttributeGroup](#AttributeGroup)||<a href="RetailPubProductAttributeChannelMetadata.md" target="_blank">Miscellaneous/RetailPubProductAttributeChannelMetadata</a>|
|[AttributeGroupDisplayOrder](#AttributeGroupDisplayOrder)||<a href="RetailPubProductAttributeChannelMetadata.md" target="_blank">Miscellaneous/RetailPubProductAttributeChannelMetadata</a>|
|[AttributeRelationType](#AttributeRelationType)||<a href="RetailPubProductAttributeChannelMetadata.md" target="_blank">Miscellaneous/RetailPubProductAttributeChannelMetadata</a>|
|[DataType](#DataType)||<a href="RetailPubProductAttributeChannelMetadata.md" target="_blank">Miscellaneous/RetailPubProductAttributeChannelMetadata</a>|
|[HostChannel](#HostChannel)||<a href="RetailPubProductAttributeChannelMetadata.md" target="_blank">Miscellaneous/RetailPubProductAttributeChannelMetadata</a>|
|[KeyName](#KeyName)||<a href="RetailPubProductAttributeChannelMetadata.md" target="_blank">Miscellaneous/RetailPubProductAttributeChannelMetadata</a>|
|[Metadata](#Metadata)||<a href="RetailPubProductAttributeChannelMetadata.md" target="_blank">Miscellaneous/RetailPubProductAttributeChannelMetadata</a>|
|[MetadataVersion](#MetadataVersion)||<a href="RetailPubProductAttributeChannelMetadata.md" target="_blank">Miscellaneous/RetailPubProductAttributeChannelMetadata</a>|
|[OriginId](#OriginId)||<a href="RetailPubProductAttributeChannelMetadata.md" target="_blank">Miscellaneous/RetailPubProductAttributeChannelMetadata</a>|
|[OriginRecVersion](#OriginRecVersion)||<a href="RetailPubProductAttributeChannelMetadata.md" target="_blank">Miscellaneous/RetailPubProductAttributeChannelMetadata</a>|
|[Relationship_EcoResAttributeRelationshipId](#Relationship_EcoResAttributeRelationshipId)||<a href="RetailPubProductAttributeChannelMetadata.md" target="_blank">Miscellaneous/RetailPubProductAttributeChannelMetadata</a>|
|[Relationship_RetailChannelTableRelationshipId](#Relationship_RetailChannelTableRelationshipId)||<a href="RetailPubProductAttributeChannelMetadata.md" target="_blank">Miscellaneous/RetailPubProductAttributeChannelMetadata</a>|
|[Relationship_RetailProdAttributeInternalOrgMetadataRelationshipId](#Relationship_RetailProdAttributeInternalOrgMetadataRelationshipId)||<a href="RetailPubProductAttributeChannelMetadata.md" target="_blank">Miscellaneous/RetailPubProductAttributeChannelMetadata</a>|
|[Relationship_RetailPubRetailChannelTableRelationshipId](#Relationship_RetailPubRetailChannelTableRelationshipId)||<a href="RetailPubProductAttributeChannelMetadata.md" target="_blank">Miscellaneous/RetailPubProductAttributeChannelMetadata</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/RetailPubProductAttributeChannelMetadata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailPubProductAttributeChannelMetadata/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Attribute name="Attribute">Attribute</a>

First included in: Miscellaneous/RetailPubProductAttributeChannelMetadata (this entity)  

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

### <a href=#AttributeDisplayOrder name="AttributeDisplayOrder">AttributeDisplayOrder</a>

First included in: Miscellaneous/RetailPubProductAttributeChannelMetadata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AttributeDisplayOrder attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#AttributeGroup name="AttributeGroup">AttributeGroup</a>

First included in: Miscellaneous/RetailPubProductAttributeChannelMetadata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AttributeGroup attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AttributeGroupDisplayOrder name="AttributeGroupDisplayOrder">AttributeGroupDisplayOrder</a>

First included in: Miscellaneous/RetailPubProductAttributeChannelMetadata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AttributeGroupDisplayOrder attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#AttributeRelationType name="AttributeRelationType">AttributeRelationType</a>

First included in: Miscellaneous/RetailPubProductAttributeChannelMetadata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AttributeRelationType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DataType name="DataType">DataType</a>

First included in: Miscellaneous/RetailPubProductAttributeChannelMetadata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#HostChannel name="HostChannel">HostChannel</a>

First included in: Miscellaneous/RetailPubProductAttributeChannelMetadata (this entity)  

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

First included in: Miscellaneous/RetailPubProductAttributeChannelMetadata (this entity)  

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

### <a href=#Metadata name="Metadata">Metadata</a>

First included in: Miscellaneous/RetailPubProductAttributeChannelMetadata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Metadata attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MetadataVersion name="MetadataVersion">MetadataVersion</a>

First included in: Miscellaneous/RetailPubProductAttributeChannelMetadata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MetadataVersion attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#OriginId name="OriginId">OriginId</a>

First included in: Miscellaneous/RetailPubProductAttributeChannelMetadata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#OriginRecVersion name="OriginRecVersion">OriginRecVersion</a>

First included in: Miscellaneous/RetailPubProductAttributeChannelMetadata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginRecVersion attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Relationship_EcoResAttributeRelationshipId name="Relationship_EcoResAttributeRelationshipId">Relationship_EcoResAttributeRelationshipId</a>

First included in: Miscellaneous/RetailPubProductAttributeChannelMetadata (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResAttribute.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/EcoResAttribute.cdm.json/EcoResAttribute</a></td><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResAttribute.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailChannelTableRelationshipId name="Relationship_RetailChannelTableRelationshipId">Relationship_RetailChannelTableRelationshipId</a>

First included in: Miscellaneous/RetailPubProductAttributeChannelMetadata (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ChannelManagement/Main/RetailChannelTable.md" target="_blank">/core/operationsCommon/Tables/Commerce/ChannelManagement/Main/RetailChannelTable.cdm.json/RetailChannelTable</a></td><td><a href="../../ChannelManagement/Main/RetailChannelTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailProdAttributeInternalOrgMetadataRelationshipId name="Relationship_RetailProdAttributeInternalOrgMetadataRelationshipId">Relationship_RetailProdAttributeInternalOrgMetadataRelationshipId</a>

First included in: Miscellaneous/RetailPubProductAttributeChannelMetadata (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailProdAttributeInternalOrgMetadataRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/RetailProdAttributeInternalOrgMetadata.md" target="_blank">/core/operationsCommon/Tables/Commerce/Merchandising/Main/RetailProdAttributeInternalOrgMetadata.cdm.json/RetailProdAttributeInternalOrgMetadata</a></td><td><a href="../Main/RetailProdAttributeInternalOrgMetadata.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailPubRetailChannelTableRelationshipId name="Relationship_RetailPubRetailChannelTableRelationshipId">Relationship_RetailPubRetailChannelTableRelationshipId</a>

First included in: Miscellaneous/RetailPubProductAttributeChannelMetadata (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailPubRetailChannelTable.md" target="_blank">/core/operationsCommon/Tables/Commerce/Merchandising/Miscellaneous/RetailPubRetailChannelTable.cdm.json/RetailPubRetailChannelTable</a></td><td><a href="RetailPubRetailChannelTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
