---
title: EcoResProductNumberIdentifiedReleasedProductVariantExternalCodeEntity in ProductInformationManagement - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/13/2020
ms.author: nebanfic
---

# External codes for released product variants by product number identification in ProductInformationManagement(EcoResProductNumberIdentifiedReleasedProductVariantExternalCodeEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductInformationManagement/EcoResProductNumberIdentifiedReleasedProductVariantExternalCodeEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>External codes for released product variants by product number identification</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ReleasedProductVariantExternalCodeClassId](#ReleasedProductVariantExternalCodeClassId)||<a href="EcoResProductNumberIdentifiedReleasedProductVariantExternalCodeEntity.md" target="_blank">ProductInformationManagement/EcoResProductNumberIdentifiedReleasedProductVariantExternalCodeEntity</a>|
|[ItemNumber](#ItemNumber)||<a href="EcoResProductNumberIdentifiedReleasedProductVariantExternalCodeEntity.md" target="_blank">ProductInformationManagement/EcoResProductNumberIdentifiedReleasedProductVariantExternalCodeEntity</a>|
|[ProductColorId](#ProductColorId)||<a href="EcoResProductNumberIdentifiedReleasedProductVariantExternalCodeEntity.md" target="_blank">ProductInformationManagement/EcoResProductNumberIdentifiedReleasedProductVariantExternalCodeEntity</a>|
|[ProductSizeId](#ProductSizeId)||<a href="EcoResProductNumberIdentifiedReleasedProductVariantExternalCodeEntity.md" target="_blank">ProductInformationManagement/EcoResProductNumberIdentifiedReleasedProductVariantExternalCodeEntity</a>|
|[ProductStyleId](#ProductStyleId)||<a href="EcoResProductNumberIdentifiedReleasedProductVariantExternalCodeEntity.md" target="_blank">ProductInformationManagement/EcoResProductNumberIdentifiedReleasedProductVariantExternalCodeEntity</a>|
|[ProductVersionId](#ProductVersionId)||<a href="EcoResProductNumberIdentifiedReleasedProductVariantExternalCodeEntity.md" target="_blank">ProductInformationManagement/EcoResProductNumberIdentifiedReleasedProductVariantExternalCodeEntity</a>|
|[ProductConfigurationId](#ProductConfigurationId)||<a href="EcoResProductNumberIdentifiedReleasedProductVariantExternalCodeEntity.md" target="_blank">ProductInformationManagement/EcoResProductNumberIdentifiedReleasedProductVariantExternalCodeEntity</a>|
|[ExternalCode](#ExternalCode)||<a href="EcoResProductNumberIdentifiedReleasedProductVariantExternalCodeEntity.md" target="_blank">ProductInformationManagement/EcoResProductNumberIdentifiedReleasedProductVariantExternalCodeEntity</a>|
|[ExtCodeRelationTableId](#ExtCodeRelationTableId)||<a href="EcoResProductNumberIdentifiedReleasedProductVariantExternalCodeEntity.md" target="_blank">ProductInformationManagement/EcoResProductNumberIdentifiedReleasedProductVariantExternalCodeEntity</a>|
|[ExtCodeTableTableId](#ExtCodeTableTableId)||<a href="EcoResProductNumberIdentifiedReleasedProductVariantExternalCodeEntity.md" target="_blank">ProductInformationManagement/EcoResProductNumberIdentifiedReleasedProductVariantExternalCodeEntity</a>|
|[ProductVariantRecId](#ProductVariantRecId)||<a href="EcoResProductNumberIdentifiedReleasedProductVariantExternalCodeEntity.md" target="_blank">ProductInformationManagement/EcoResProductNumberIdentifiedReleasedProductVariantExternalCodeEntity</a>|
|[ProductVariantNumber](#ProductVariantNumber)||<a href="EcoResProductNumberIdentifiedReleasedProductVariantExternalCodeEntity.md" target="_blank">ProductInformationManagement/EcoResProductNumberIdentifiedReleasedProductVariantExternalCodeEntity</a>|
|[Relationship_ProductNumberIdentifiedReleasedProductVariantRelationshipId](#Relationship_ProductNumberIdentifiedReleasedProductVariantRelationshipId)||<a href="EcoResProductNumberIdentifiedReleasedProductVariantExternalCodeEntity.md" target="_blank">ProductInformationManagement/EcoResProductNumberIdentifiedReleasedProductVariantExternalCodeEntity</a>|
|[Relationship_ReleasedProductVariantExternalCodeClassRelationshipId](#Relationship_ReleasedProductVariantExternalCodeClassRelationshipId)||<a href="EcoResProductNumberIdentifiedReleasedProductVariantExternalCodeEntity.md" target="_blank">ProductInformationManagement/EcoResProductNumberIdentifiedReleasedProductVariantExternalCodeEntity</a>|
|[BackingTable_ExtCodeValueTableRelationshipId](#BackingTable_ExtCodeValueTableRelationshipId)||<a href="EcoResProductNumberIdentifiedReleasedProductVariantExternalCodeEntity.md" target="_blank">ProductInformationManagement/EcoResProductNumberIdentifiedReleasedProductVariantExternalCodeEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="EcoResProductNumberIdentifiedReleasedProductVariantExternalCodeEntity.md" target="_blank">ProductInformationManagement/EcoResProductNumberIdentifiedReleasedProductVariantExternalCodeEntity</a>|

### <a href=#ReleasedProductVariantExternalCodeClassId name="ReleasedProductVariantExternalCodeClassId">ReleasedProductVariantExternalCodeClassId</a>

First included in: ProductInformationManagement/EcoResProductNumberIdentifiedReleasedProductVariantExternalCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReleasedProductVariantExternalCodeClassId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemNumber name="ItemNumber">ItemNumber</a>

First included in: ProductInformationManagement/EcoResProductNumberIdentifiedReleasedProductVariantExternalCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductColorId name="ProductColorId">ProductColorId</a>

First included in: ProductInformationManagement/EcoResProductNumberIdentifiedReleasedProductVariantExternalCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductColorId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductSizeId name="ProductSizeId">ProductSizeId</a>

First included in: ProductInformationManagement/EcoResProductNumberIdentifiedReleasedProductVariantExternalCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductSizeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductStyleId name="ProductStyleId">ProductStyleId</a>

First included in: ProductInformationManagement/EcoResProductNumberIdentifiedReleasedProductVariantExternalCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductStyleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductVersionId name="ProductVersionId">ProductVersionId</a>

First included in: ProductInformationManagement/EcoResProductNumberIdentifiedReleasedProductVariantExternalCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductVersionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductConfigurationId name="ProductConfigurationId">ProductConfigurationId</a>

First included in: ProductInformationManagement/EcoResProductNumberIdentifiedReleasedProductVariantExternalCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductConfigurationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExternalCode name="ExternalCode">ExternalCode</a>

First included in: ProductInformationManagement/EcoResProductNumberIdentifiedReleasedProductVariantExternalCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExternalCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExtCodeRelationTableId name="ExtCodeRelationTableId">ExtCodeRelationTableId</a>

First included in: ProductInformationManagement/EcoResProductNumberIdentifiedReleasedProductVariantExternalCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExtCodeRelationTableId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExtCodeTableTableId name="ExtCodeTableTableId">ExtCodeTableTableId</a>

First included in: ProductInformationManagement/EcoResProductNumberIdentifiedReleasedProductVariantExternalCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExtCodeTableTableId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductVariantRecId name="ProductVariantRecId">ProductVariantRecId</a>

First included in: ProductInformationManagement/EcoResProductNumberIdentifiedReleasedProductVariantExternalCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductVariantRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductVariantNumber name="ProductVariantNumber">ProductVariantNumber</a>

First included in: ProductInformationManagement/EcoResProductNumberIdentifiedReleasedProductVariantExternalCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductVariantNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProductNumberIdentifiedReleasedProductVariantRelationshipId name="Relationship_ProductNumberIdentifiedReleasedProductVariantRelationshipId">Relationship_ProductNumberIdentifiedReleasedProductVariantRelationshipId</a>

First included in: ProductInformationManagement/EcoResProductNumberIdentifiedReleasedProductVariantExternalCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProductNumberIdentifiedReleasedProductVariantRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ReleasedProductVariantExternalCodeClassRelationshipId name="Relationship_ReleasedProductVariantExternalCodeClassRelationshipId">Relationship_ReleasedProductVariantExternalCodeClassRelationshipId</a>

First included in: ProductInformationManagement/EcoResProductNumberIdentifiedReleasedProductVariantExternalCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReleasedProductVariantExternalCodeClassRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_ExtCodeValueTableRelationshipId name="BackingTable_ExtCodeValueTableRelationshipId">BackingTable_ExtCodeValueTableRelationshipId</a>

First included in: ProductInformationManagement/EcoResProductNumberIdentifiedReleasedProductVariantExternalCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_ExtCodeValueTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Group/ExtCodeValueTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Group/ExtCodeValueTable.cdm.json/ExtCodeValueTable</a></td><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Group/ExtCodeValueTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProductInformationManagement/EcoResProductNumberIdentifiedReleasedProductVariantExternalCodeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PrimaryCompanyContextRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
