---
title: EcoResProductParametersEntity in InventoryAndWarehouseManagement - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/13/2020
ms.author: nebanfic
---

# Product parameters in InventoryAndWarehouseManagement(EcoResProductParametersEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/EcoResProductParametersEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Product parameters</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[SingletonKey](#SingletonKey)||<a href="EcoResProductParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/EcoResProductParametersEntity</a>|
|[AreProductNumberShownOnForms](#AreProductNumberShownOnForms)||<a href="EcoResProductParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/EcoResProductParametersEntity</a>|
|[ProductEntityAttributeMasterCompanyId](#ProductEntityAttributeMasterCompanyId)||<a href="EcoResProductParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/EcoResProductParametersEntity</a>|
|[ProductVariantUnitConversionProcesses](#ProductVariantUnitConversionProcesses)||<a href="EcoResProductParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/EcoResProductParametersEntity</a>|
|[BackingTable_EcoResProductParametersRelationshipId](#BackingTable_EcoResProductParametersRelationshipId)||<a href="EcoResProductParametersEntity.md" target="_blank">InventoryAndWarehouseManagement/EcoResProductParametersEntity</a>|

### <a href=#SingletonKey name="SingletonKey">SingletonKey</a>

First included in: InventoryAndWarehouseManagement/EcoResProductParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SingletonKey attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreProductNumberShownOnForms name="AreProductNumberShownOnForms">AreProductNumberShownOnForms</a>

First included in: InventoryAndWarehouseManagement/EcoResProductParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreProductNumberShownOnForms attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductEntityAttributeMasterCompanyId name="ProductEntityAttributeMasterCompanyId">ProductEntityAttributeMasterCompanyId</a>

First included in: InventoryAndWarehouseManagement/EcoResProductParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductEntityAttributeMasterCompanyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductVariantUnitConversionProcesses name="ProductVariantUnitConversionProcesses">ProductVariantUnitConversionProcesses</a>

First included in: InventoryAndWarehouseManagement/EcoResProductParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductVariantUnitConversionProcesses attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_EcoResProductParametersRelationshipId name="BackingTable_EcoResProductParametersRelationshipId">BackingTable_EcoResProductParametersRelationshipId</a>

First included in: InventoryAndWarehouseManagement/EcoResProductParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_EcoResProductParametersRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProductInformationManagement/Parameter/EcoResProductParameters.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Parameter/EcoResProductParameters.cdm.json/EcoResProductParameters</a></td><td><a href="../../../Tables/SupplyChain/ProductInformationManagement/Parameter/EcoResProductParameters.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
