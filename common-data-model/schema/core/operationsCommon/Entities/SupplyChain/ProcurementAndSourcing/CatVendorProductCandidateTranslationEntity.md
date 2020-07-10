---
title: CatVendorProductCandidateTranslationEntity in ProcurementAndSourcing - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/10/2020
ms.author: nebanfic
---

# Vendor catalog product name and description translations in ProcurementAndSourcing(CatVendorProductCandidateTranslationEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/CatVendorProductCandidateTranslationEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Vendor catalog product name and description translations</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[Description](#Description)||<a href="CatVendorProductCandidateTranslationEntity.md" target="_blank">ProcurementAndSourcing/CatVendorProductCandidateTranslationEntity</a>|
|[LanguageId](#LanguageId)||<a href="CatVendorProductCandidateTranslationEntity.md" target="_blank">ProcurementAndSourcing/CatVendorProductCandidateTranslationEntity</a>|
|[ProductName](#ProductName)||<a href="CatVendorProductCandidateTranslationEntity.md" target="_blank">ProcurementAndSourcing/CatVendorProductCandidateTranslationEntity</a>|
|[ProductCandidate](#ProductCandidate)||<a href="CatVendorProductCandidateTranslationEntity.md" target="_blank">ProcurementAndSourcing/CatVendorProductCandidateTranslationEntity</a>|
|[VendorCatalogMaintenanceRequestUploadDateTime](#VendorCatalogMaintenanceRequestUploadDateTime)||<a href="CatVendorProductCandidateTranslationEntity.md" target="_blank">ProcurementAndSourcing/CatVendorProductCandidateTranslationEntity</a>|
|[ProductCandidateStyleId](#ProductCandidateStyleId)||<a href="CatVendorProductCandidateTranslationEntity.md" target="_blank">ProcurementAndSourcing/CatVendorProductCandidateTranslationEntity</a>|
|[ProductCandidateProductNumber](#ProductCandidateProductNumber)||<a href="CatVendorProductCandidateTranslationEntity.md" target="_blank">ProcurementAndSourcing/CatVendorProductCandidateTranslationEntity</a>|
|[ProductCandidateSizeId](#ProductCandidateSizeId)||<a href="CatVendorProductCandidateTranslationEntity.md" target="_blank">ProcurementAndSourcing/CatVendorProductCandidateTranslationEntity</a>|
|[ProductCandidateProductSubtype](#ProductCandidateProductSubtype)||<a href="CatVendorProductCandidateTranslationEntity.md" target="_blank">ProcurementAndSourcing/CatVendorProductCandidateTranslationEntity</a>|
|[ProductCandidateConfigurationId](#ProductCandidateConfigurationId)||<a href="CatVendorProductCandidateTranslationEntity.md" target="_blank">ProcurementAndSourcing/CatVendorProductCandidateTranslationEntity</a>|
|[ProductCandidateColorId](#ProductCandidateColorId)||<a href="CatVendorProductCandidateTranslationEntity.md" target="_blank">ProcurementAndSourcing/CatVendorProductCandidateTranslationEntity</a>|
|[CatalogMaintenanceRequestRecId](#CatalogMaintenanceRequestRecId)||<a href="CatVendorProductCandidateTranslationEntity.md" target="_blank">ProcurementAndSourcing/CatVendorProductCandidateTranslationEntity</a>|
|[ProductCandidateRecId](#ProductCandidateRecId)||<a href="CatVendorProductCandidateTranslationEntity.md" target="_blank">ProcurementAndSourcing/CatVendorProductCandidateTranslationEntity</a>|
|[Relationship_CatVendorProductCandidateEntityRelationshipId](#Relationship_CatVendorProductCandidateEntityRelationshipId)||<a href="CatVendorProductCandidateTranslationEntity.md" target="_blank">ProcurementAndSourcing/CatVendorProductCandidateTranslationEntity</a>|
|[BackingTable_CatVendorProductTextTranslationRelationshipId](#BackingTable_CatVendorProductTextTranslationRelationshipId)||<a href="CatVendorProductCandidateTranslationEntity.md" target="_blank">ProcurementAndSourcing/CatVendorProductCandidateTranslationEntity</a>|

### <a href=#Description name="Description">Description</a>

First included in: ProcurementAndSourcing/CatVendorProductCandidateTranslationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LanguageId name="LanguageId">LanguageId</a>

First included in: ProcurementAndSourcing/CatVendorProductCandidateTranslationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LanguageId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductName name="ProductName">ProductName</a>

First included in: ProcurementAndSourcing/CatVendorProductCandidateTranslationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductCandidate name="ProductCandidate">ProductCandidate</a>

First included in: ProcurementAndSourcing/CatVendorProductCandidateTranslationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductCandidate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorCatalogMaintenanceRequestUploadDateTime name="VendorCatalogMaintenanceRequestUploadDateTime">VendorCatalogMaintenanceRequestUploadDateTime</a>

First included in: ProcurementAndSourcing/CatVendorProductCandidateTranslationEntity (this entity)  

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

### <a href=#ProductCandidateStyleId name="ProductCandidateStyleId">ProductCandidateStyleId</a>

First included in: ProcurementAndSourcing/CatVendorProductCandidateTranslationEntity (this entity)  

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

First included in: ProcurementAndSourcing/CatVendorProductCandidateTranslationEntity (this entity)  

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

### <a href=#ProductCandidateSizeId name="ProductCandidateSizeId">ProductCandidateSizeId</a>

First included in: ProcurementAndSourcing/CatVendorProductCandidateTranslationEntity (this entity)  

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

### <a href=#ProductCandidateProductSubtype name="ProductCandidateProductSubtype">ProductCandidateProductSubtype</a>

First included in: ProcurementAndSourcing/CatVendorProductCandidateTranslationEntity (this entity)  

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

### <a href=#ProductCandidateConfigurationId name="ProductCandidateConfigurationId">ProductCandidateConfigurationId</a>

First included in: ProcurementAndSourcing/CatVendorProductCandidateTranslationEntity (this entity)  

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

### <a href=#ProductCandidateColorId name="ProductCandidateColorId">ProductCandidateColorId</a>

First included in: ProcurementAndSourcing/CatVendorProductCandidateTranslationEntity (this entity)  

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

### <a href=#CatalogMaintenanceRequestRecId name="CatalogMaintenanceRequestRecId">CatalogMaintenanceRequestRecId</a>

First included in: ProcurementAndSourcing/CatVendorProductCandidateTranslationEntity (this entity)  

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

### <a href=#ProductCandidateRecId name="ProductCandidateRecId">ProductCandidateRecId</a>

First included in: ProcurementAndSourcing/CatVendorProductCandidateTranslationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductCandidateRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CatVendorProductCandidateEntityRelationshipId name="Relationship_CatVendorProductCandidateEntityRelationshipId">Relationship_CatVendorProductCandidateEntityRelationshipId</a>

First included in: ProcurementAndSourcing/CatVendorProductCandidateTranslationEntity (this entity)  

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

### <a href=#BackingTable_CatVendorProductTextTranslationRelationshipId name="BackingTable_CatVendorProductTextTranslationRelationshipId">BackingTable_CatVendorProductTextTranslationRelationshipId</a>

First included in: ProcurementAndSourcing/CatVendorProductCandidateTranslationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_CatVendorProductTextTranslationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Main/CatVendorProductTextTranslation.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Main/CatVendorProductTextTranslation.cdm.json/CatVendorProductTextTranslation</a></td><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Main/CatVendorProductTextTranslation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
