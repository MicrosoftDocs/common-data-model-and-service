---
title: EcoResProductMaster - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# EcoResProductMaster

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/EcoResProductMaster.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[EcoResProductMaster/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="EcoResProductMaster.md" target="_blank">Main/EcoResProductMaster</a>|
|[DisplayProductNumber](#DisplayProductNumber)||<a href="EcoResProductMaster.md" target="_blank">Main/EcoResProductMaster</a>|
|[InstanceRelationType](#InstanceRelationType)||<a href="EcoResProductMaster.md" target="_blank">Main/EcoResProductMaster</a>|
|[PdsCWProduct](#PdsCWProduct)||<a href="EcoResProductMaster.md" target="_blank">Main/EcoResProductMaster</a>|
|[ProductType](#ProductType)||<a href="EcoResProductMaster.md" target="_blank">Main/EcoResProductMaster</a>|
|[SearchName](#SearchName)||<a href="EcoResProductMaster.md" target="_blank">Main/EcoResProductMaster</a>|
|[ServiceType](#ServiceType)||<a href="EcoResProductMaster.md" target="_blank">Main/EcoResProductMaster</a>|
|[EngChgProductOwnerId](#EngChgProductOwnerId)||<a href="EcoResProductMaster.md" target="_blank">Main/EcoResProductMaster</a>|
|[EngChgProductType](#EngChgProductType)||<a href="EcoResProductMaster.md" target="_blank">Main/EcoResProductMaster</a>|
|[RetailColorGroupId](#RetailColorGroupId)||<a href="EcoResProductMaster.md" target="_blank">Main/EcoResProductMaster</a>|
|[RetailSizeGroupId](#RetailSizeGroupId)||<a href="EcoResProductMaster.md" target="_blank">Main/EcoResProductMaster</a>|
|[RetailStyleGroupId](#RetailStyleGroupId)||<a href="EcoResProductMaster.md" target="_blank">Main/EcoResProductMaster</a>|
|[VariantConfigurationTechnology](#VariantConfigurationTechnology)||<a href="EcoResProductMaster.md" target="_blank">Main/EcoResProductMaster</a>|
|[IsProductVariantUnitConversionEnabled](#IsProductVariantUnitConversionEnabled)||<a href="EcoResProductMaster.md" target="_blank">Main/EcoResProductMaster</a>|
|[RetailFlavorGroupId](#RetailFlavorGroupId)||<a href="EcoResProductMaster.md" target="_blank">Main/EcoResProductMaster</a>|
|[Relationship_RetailColorGroupTable_3267RelationshipId](#Relationship_RetailColorGroupTable_3267RelationshipId)||<a href="EcoResProductMaster.md" target="_blank">Main/EcoResProductMaster</a>|
|[Relationship_RetailSizeGroupTable_3267RelationshipId](#Relationship_RetailSizeGroupTable_3267RelationshipId)||<a href="EcoResProductMaster.md" target="_blank">Main/EcoResProductMaster</a>|
|[Relationship_RetailStyleGroupTable_3267RelationshipId](#Relationship_RetailStyleGroupTable_3267RelationshipId)||<a href="EcoResProductMaster.md" target="_blank">Main/EcoResProductMaster</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/EcoResProductMaster (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[EcoResProductMaster/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DisplayProductNumber name="DisplayProductNumber">DisplayProductNumber</a>

First included in: Main/EcoResProductMaster (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisplayProductNumber attribute are listed below.</summary>

</details>

### <a href=#InstanceRelationType name="InstanceRelationType">InstanceRelationType</a>

First included in: Main/EcoResProductMaster (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InstanceRelationType attribute are listed below.</summary>

**is.readOnly**  
</details>

### <a href=#PdsCWProduct name="PdsCWProduct">PdsCWProduct</a>

First included in: Main/EcoResProductMaster (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PdsCWProduct attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ProductType name="ProductType">ProductType</a>

First included in: Main/EcoResProductMaster (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SearchName name="SearchName">SearchName</a>

First included in: Main/EcoResProductMaster (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SearchName attribute are listed below.</summary>

</details>

### <a href=#ServiceType name="ServiceType">ServiceType</a>

First included in: Main/EcoResProductMaster (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EngChgProductOwnerId name="EngChgProductOwnerId">EngChgProductOwnerId</a>

First included in: Main/EcoResProductMaster (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EngChgProductOwnerId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EngChgProductType name="EngChgProductType">EngChgProductType</a>

First included in: Main/EcoResProductMaster (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EngChgProductType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RetailColorGroupId name="RetailColorGroupId">RetailColorGroupId</a>

First included in: Main/EcoResProductMaster (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailColorGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailSizeGroupId name="RetailSizeGroupId">RetailSizeGroupId</a>

First included in: Main/EcoResProductMaster (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailSizeGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailStyleGroupId name="RetailStyleGroupId">RetailStyleGroupId</a>

First included in: Main/EcoResProductMaster (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailStyleGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VariantConfigurationTechnology name="VariantConfigurationTechnology">VariantConfigurationTechnology</a>

First included in: Main/EcoResProductMaster (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VariantConfigurationTechnology attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsProductVariantUnitConversionEnabled name="IsProductVariantUnitConversionEnabled">IsProductVariantUnitConversionEnabled</a>

First included in: Main/EcoResProductMaster (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProductVariantUnitConversionEnabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RetailFlavorGroupId name="RetailFlavorGroupId">RetailFlavorGroupId</a>

First included in: Main/EcoResProductMaster (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailFlavorGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailColorGroupTable_3267RelationshipId name="Relationship_RetailColorGroupTable_3267RelationshipId">Relationship_RetailColorGroupTable_3267RelationshipId</a>

First included in: Main/EcoResProductMaster (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailColorGroupTable_3267RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Commerce/Retail/Group/RetailColorGroupTable.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Group/RetailColorGroupTable.cdm.json/RetailColorGroupTable</a></td><td><a href="../../../Commerce/Retail/Group/RetailColorGroupTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailSizeGroupTable_3267RelationshipId name="Relationship_RetailSizeGroupTable_3267RelationshipId">Relationship_RetailSizeGroupTable_3267RelationshipId</a>

First included in: Main/EcoResProductMaster (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailSizeGroupTable_3267RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Commerce/Retail/Group/RetailSizeGroupTable.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Group/RetailSizeGroupTable.cdm.json/RetailSizeGroupTable</a></td><td><a href="../../../Commerce/Retail/Group/RetailSizeGroupTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailStyleGroupTable_3267RelationshipId name="Relationship_RetailStyleGroupTable_3267RelationshipId">Relationship_RetailStyleGroupTable_3267RelationshipId</a>

First included in: Main/EcoResProductMaster (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailStyleGroupTable_3267RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Commerce/Retail/Group/RetailStyleGroupTable.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Group/RetailStyleGroupTable.cdm.json/RetailStyleGroupTable</a></td><td><a href="../../../Commerce/Retail/Group/RetailStyleGroupTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
