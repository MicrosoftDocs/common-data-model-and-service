---
title: CatVendorProductCandidateDefaultOrderSettingsEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 5/5/2020
ms.author: nebanfic
---

# Vendor catalog product purchase default order settings

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/CatVendorProductCandidateDefaultOrderSettingsEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Vendor catalog product purchase default order settings</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[VendorProductCandidate](#VendorProductCandidate)||<a href="CatVendorProductCandidateDefaultOrderSettingsEntity.md" target="_blank">ProcurementAndSourcing/CatVendorProductCandidateDefaultOrderSettingsEntity</a>|
|[UnitOfMeasure](#UnitOfMeasure)||<a href="CatVendorProductCandidateDefaultOrderSettingsEntity.md" target="_blank">ProcurementAndSourcing/CatVendorProductCandidateDefaultOrderSettingsEntity</a>|
|[OrderQuantityMultiples](#OrderQuantityMultiples)||<a href="CatVendorProductCandidateDefaultOrderSettingsEntity.md" target="_blank">ProcurementAndSourcing/CatVendorProductCandidateDefaultOrderSettingsEntity</a>|
|[MinimumOrderQuantity](#MinimumOrderQuantity)||<a href="CatVendorProductCandidateDefaultOrderSettingsEntity.md" target="_blank">ProcurementAndSourcing/CatVendorProductCandidateDefaultOrderSettingsEntity</a>|
|[StandardOrderQuantity](#StandardOrderQuantity)||<a href="CatVendorProductCandidateDefaultOrderSettingsEntity.md" target="_blank">ProcurementAndSourcing/CatVendorProductCandidateDefaultOrderSettingsEntity</a>|
|[MaximumOrderQuantity](#MaximumOrderQuantity)||<a href="CatVendorProductCandidateDefaultOrderSettingsEntity.md" target="_blank">ProcurementAndSourcing/CatVendorProductCandidateDefaultOrderSettingsEntity</a>|
|[LeadTime](#LeadTime)||<a href="CatVendorProductCandidateDefaultOrderSettingsEntity.md" target="_blank">ProcurementAndSourcing/CatVendorProductCandidateDefaultOrderSettingsEntity</a>|
|[CatalogMaintenanceRequestRecId](#CatalogMaintenanceRequestRecId)||<a href="CatVendorProductCandidateDefaultOrderSettingsEntity.md" target="_blank">ProcurementAndSourcing/CatVendorProductCandidateDefaultOrderSettingsEntity</a>|
|[ProductCandidateColorId](#ProductCandidateColorId)||<a href="CatVendorProductCandidateDefaultOrderSettingsEntity.md" target="_blank">ProcurementAndSourcing/CatVendorProductCandidateDefaultOrderSettingsEntity</a>|
|[ProductCandidateConfigurationId](#ProductCandidateConfigurationId)||<a href="CatVendorProductCandidateDefaultOrderSettingsEntity.md" target="_blank">ProcurementAndSourcing/CatVendorProductCandidateDefaultOrderSettingsEntity</a>|
|[ProductCandidateProductSubtype](#ProductCandidateProductSubtype)||<a href="CatVendorProductCandidateDefaultOrderSettingsEntity.md" target="_blank">ProcurementAndSourcing/CatVendorProductCandidateDefaultOrderSettingsEntity</a>|
|[ProductCandidateSizeId](#ProductCandidateSizeId)||<a href="CatVendorProductCandidateDefaultOrderSettingsEntity.md" target="_blank">ProcurementAndSourcing/CatVendorProductCandidateDefaultOrderSettingsEntity</a>|
|[ProductCandidateStyleId](#ProductCandidateStyleId)||<a href="CatVendorProductCandidateDefaultOrderSettingsEntity.md" target="_blank">ProcurementAndSourcing/CatVendorProductCandidateDefaultOrderSettingsEntity</a>|
|[ProductCandidateProductNumber](#ProductCandidateProductNumber)||<a href="CatVendorProductCandidateDefaultOrderSettingsEntity.md" target="_blank">ProcurementAndSourcing/CatVendorProductCandidateDefaultOrderSettingsEntity</a>|
|[VendorCatalogMaintenanceRequestUploadDateTime](#VendorCatalogMaintenanceRequestUploadDateTime)||<a href="CatVendorProductCandidateDefaultOrderSettingsEntity.md" target="_blank">ProcurementAndSourcing/CatVendorProductCandidateDefaultOrderSettingsEntity</a>|
|[UnitSymbol](#UnitSymbol)||<a href="CatVendorProductCandidateDefaultOrderSettingsEntity.md" target="_blank">ProcurementAndSourcing/CatVendorProductCandidateDefaultOrderSettingsEntity</a>|
|[Relationship_CatVendorProductCandidateEntityRelationshipId](#Relationship_CatVendorProductCandidateEntityRelationshipId)||<a href="CatVendorProductCandidateDefaultOrderSettingsEntity.md" target="_blank">ProcurementAndSourcing/CatVendorProductCandidateDefaultOrderSettingsEntity</a>|
|[BackingTable_CatVendorProductCandidateDefaultOrderSettingsRelationshipId](#BackingTable_CatVendorProductCandidateDefaultOrderSettingsRelationshipId)||<a href="CatVendorProductCandidateDefaultOrderSettingsEntity.md" target="_blank">ProcurementAndSourcing/CatVendorProductCandidateDefaultOrderSettingsEntity</a>|

### <a href=#VendorProductCandidate name="VendorProductCandidate">VendorProductCandidate</a>

First included in: ProcurementAndSourcing/CatVendorProductCandidateDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorProductCandidate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnitOfMeasure name="UnitOfMeasure">UnitOfMeasure</a>

First included in: ProcurementAndSourcing/CatVendorProductCandidateDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitOfMeasure attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrderQuantityMultiples name="OrderQuantityMultiples">OrderQuantityMultiples</a>

First included in: ProcurementAndSourcing/CatVendorProductCandidateDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderQuantityMultiples attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinimumOrderQuantity name="MinimumOrderQuantity">MinimumOrderQuantity</a>

First included in: ProcurementAndSourcing/CatVendorProductCandidateDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumOrderQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StandardOrderQuantity name="StandardOrderQuantity">StandardOrderQuantity</a>

First included in: ProcurementAndSourcing/CatVendorProductCandidateDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StandardOrderQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumOrderQuantity name="MaximumOrderQuantity">MaximumOrderQuantity</a>

First included in: ProcurementAndSourcing/CatVendorProductCandidateDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumOrderQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LeadTime name="LeadTime">LeadTime</a>

First included in: ProcurementAndSourcing/CatVendorProductCandidateDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LeadTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CatalogMaintenanceRequestRecId name="CatalogMaintenanceRequestRecId">CatalogMaintenanceRequestRecId</a>

First included in: ProcurementAndSourcing/CatVendorProductCandidateDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CatalogMaintenanceRequestRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductCandidateColorId name="ProductCandidateColorId">ProductCandidateColorId</a>

First included in: ProcurementAndSourcing/CatVendorProductCandidateDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductCandidateColorId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductCandidateConfigurationId name="ProductCandidateConfigurationId">ProductCandidateConfigurationId</a>

First included in: ProcurementAndSourcing/CatVendorProductCandidateDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductCandidateConfigurationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductCandidateProductSubtype name="ProductCandidateProductSubtype">ProductCandidateProductSubtype</a>

First included in: ProcurementAndSourcing/CatVendorProductCandidateDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductCandidateProductSubtype attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductCandidateSizeId name="ProductCandidateSizeId">ProductCandidateSizeId</a>

First included in: ProcurementAndSourcing/CatVendorProductCandidateDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductCandidateSizeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductCandidateStyleId name="ProductCandidateStyleId">ProductCandidateStyleId</a>

First included in: ProcurementAndSourcing/CatVendorProductCandidateDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductCandidateStyleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductCandidateProductNumber name="ProductCandidateProductNumber">ProductCandidateProductNumber</a>

First included in: ProcurementAndSourcing/CatVendorProductCandidateDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductCandidateProductNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorCatalogMaintenanceRequestUploadDateTime name="VendorCatalogMaintenanceRequestUploadDateTime">VendorCatalogMaintenanceRequestUploadDateTime</a>

First included in: ProcurementAndSourcing/CatVendorProductCandidateDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorCatalogMaintenanceRequestUploadDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnitSymbol name="UnitSymbol">UnitSymbol</a>

First included in: ProcurementAndSourcing/CatVendorProductCandidateDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CatVendorProductCandidateEntityRelationshipId name="Relationship_CatVendorProductCandidateEntityRelationshipId">Relationship_CatVendorProductCandidateEntityRelationshipId</a>

First included in: ProcurementAndSourcing/CatVendorProductCandidateDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CatVendorProductCandidateEntityRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_CatVendorProductCandidateDefaultOrderSettingsRelationshipId name="BackingTable_CatVendorProductCandidateDefaultOrderSettingsRelationshipId">BackingTable_CatVendorProductCandidateDefaultOrderSettingsRelationshipId</a>

First included in: ProcurementAndSourcing/CatVendorProductCandidateDefaultOrderSettingsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_CatVendorProductCandidateDefaultOrderSettingsRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Main/CatVendorProductCandidateDefaultOrderSettings.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Main/CatVendorProductCandidateDefaultOrderSettings.cdm.json/CatVendorProductCandidateDefaultOrderSettings</a></td><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Main/CatVendorProductCandidateDefaultOrderSettings.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
