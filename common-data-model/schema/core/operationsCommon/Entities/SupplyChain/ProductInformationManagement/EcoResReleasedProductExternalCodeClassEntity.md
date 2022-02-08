---
title: EcoResReleasedProductExternalCodeClassEntity in ProductInformationManagement - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# External code classes for released products in ProductInformationManagement(EcoResReleasedProductExternalCodeClassEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductInformationManagement/EcoResReleasedProductExternalCodeClassEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>External code classes for released products</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[CodeClassId](#CodeClassId)||<a href="EcoResReleasedProductExternalCodeClassEntity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductExternalCodeClassEntity</a>|
|[CodeClassDefinition](#CodeClassDefinition)||<a href="EcoResReleasedProductExternalCodeClassEntity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductExternalCodeClassEntity</a>|
|[IsStandardizedCode](#IsStandardizedCode)||<a href="EcoResReleasedProductExternalCodeClassEntity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductExternalCodeClassEntity</a>|
|[CodeClassDescription](#CodeClassDescription)||<a href="EcoResReleasedProductExternalCodeClassEntity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductExternalCodeClassEntity</a>|
|[CodeClassTableId](#CodeClassTableId)||<a href="EcoResReleasedProductExternalCodeClassEntity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductExternalCodeClassEntity</a>|
|[BackingTable_ExtCodeTableRelationshipId](#BackingTable_ExtCodeTableRelationshipId)||<a href="EcoResReleasedProductExternalCodeClassEntity.md" target="_blank">ProductInformationManagement/EcoResReleasedProductExternalCodeClassEntity</a>|

### <a href=#CodeClassId name="CodeClassId">CodeClassId</a>

First included in: ProductInformationManagement/EcoResReleasedProductExternalCodeClassEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CodeClassId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CodeClassDefinition name="CodeClassDefinition">CodeClassDefinition</a>

First included in: ProductInformationManagement/EcoResReleasedProductExternalCodeClassEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CodeClassDefinition attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsStandardizedCode name="IsStandardizedCode">IsStandardizedCode</a>

First included in: ProductInformationManagement/EcoResReleasedProductExternalCodeClassEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsStandardizedCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CodeClassDescription name="CodeClassDescription">CodeClassDescription</a>

First included in: ProductInformationManagement/EcoResReleasedProductExternalCodeClassEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CodeClassDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CodeClassTableId name="CodeClassTableId">CodeClassTableId</a>

First included in: ProductInformationManagement/EcoResReleasedProductExternalCodeClassEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CodeClassTableId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_ExtCodeTableRelationshipId name="BackingTable_ExtCodeTableRelationshipId">BackingTable_ExtCodeTableRelationshipId</a>

First included in: ProductInformationManagement/EcoResReleasedProductExternalCodeClassEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_ExtCodeTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Group/ExtCodeTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Group/ExtCodeTable.cdm.json/ExtCodeTable</a></td><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Group/ExtCodeTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
