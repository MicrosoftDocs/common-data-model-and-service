---
title: RetailTmpBulkProductAttributeValueEntity in Merchandising - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/21/2020
ms.author: nebanfic
---

# Retail catalog product attributes in Merchandising(RetailTmpBulkProductAttributeValueEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Commerce/Merchandising/RetailTmpBulkProductAttributeValueEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Retail catalog product attributes</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[CatalogName](#CatalogName)||<a href="RetailTmpBulkProductAttributeValueEntity.md" target="_blank">Merchandising/RetailTmpBulkProductAttributeValueEntity</a>|
|[CatalogNumber](#CatalogNumber)||<a href="RetailTmpBulkProductAttributeValueEntity.md" target="_blank">Merchandising/RetailTmpBulkProductAttributeValueEntity</a>|
|[AttributeName](#AttributeName)||<a href="RetailTmpBulkProductAttributeValueEntity.md" target="_blank">Merchandising/RetailTmpBulkProductAttributeValueEntity</a>|
|[AttributeTypeName](#AttributeTypeName)||<a href="RetailTmpBulkProductAttributeValueEntity.md" target="_blank">Merchandising/RetailTmpBulkProductAttributeValueEntity</a>|
|[DisplayProductNumber](#DisplayProductNumber)||<a href="RetailTmpBulkProductAttributeValueEntity.md" target="_blank">Merchandising/RetailTmpBulkProductAttributeValueEntity</a>|
|[InternalOrgNumber](#InternalOrgNumber)||<a href="RetailTmpBulkProductAttributeValueEntity.md" target="_blank">Merchandising/RetailTmpBulkProductAttributeValueEntity</a>|
|[LanguageId](#LanguageId)||<a href="RetailTmpBulkProductAttributeValueEntity.md" target="_blank">Merchandising/RetailTmpBulkProductAttributeValueEntity</a>|
|[ValueAsText](#ValueAsText)||<a href="RetailTmpBulkProductAttributeValueEntity.md" target="_blank">Merchandising/RetailTmpBulkProductAttributeValueEntity</a>|
|[AttributeProperty](#AttributeProperty)||<a href="RetailTmpBulkProductAttributeValueEntity.md" target="_blank">Merchandising/RetailTmpBulkProductAttributeValueEntity</a>|
|[ProductName](#ProductName)||<a href="RetailTmpBulkProductAttributeValueEntity.md" target="_blank">Merchandising/RetailTmpBulkProductAttributeValueEntity</a>|
|[AttributeSourceName](#AttributeSourceName)||<a href="RetailTmpBulkProductAttributeValueEntity.md" target="_blank">Merchandising/RetailTmpBulkProductAttributeValueEntity</a>|
|[AttributeSourceTypeAsLabel](#AttributeSourceTypeAsLabel)||<a href="RetailTmpBulkProductAttributeValueEntity.md" target="_blank">Merchandising/RetailTmpBulkProductAttributeValueEntity</a>|
|[RequiredAsLabel](#RequiredAsLabel)||<a href="RetailTmpBulkProductAttributeValueEntity.md" target="_blank">Merchandising/RetailTmpBulkProductAttributeValueEntity</a>|
|[DataTypeAsLabel](#DataTypeAsLabel)||<a href="RetailTmpBulkProductAttributeValueEntity.md" target="_blank">Merchandising/RetailTmpBulkProductAttributeValueEntity</a>|
|[TmpCatBulkAttrib](#TmpCatBulkAttrib)||<a href="RetailTmpBulkProductAttributeValueEntity.md" target="_blank">Merchandising/RetailTmpBulkProductAttributeValueEntity</a>|
|[BackingTable_RetailTmpBulkProductAttributeValueRelationshipId](#BackingTable_RetailTmpBulkProductAttributeValueRelationshipId)||<a href="RetailTmpBulkProductAttributeValueEntity.md" target="_blank">Merchandising/RetailTmpBulkProductAttributeValueEntity</a>|

### <a href=#CatalogName name="CatalogName">CatalogName</a>

First included in: Merchandising/RetailTmpBulkProductAttributeValueEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CatalogName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CatalogNumber name="CatalogNumber">CatalogNumber</a>

First included in: Merchandising/RetailTmpBulkProductAttributeValueEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CatalogNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AttributeName name="AttributeName">AttributeName</a>

First included in: Merchandising/RetailTmpBulkProductAttributeValueEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Attribute name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AttributeName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Attribute name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AttributeTypeName name="AttributeTypeName">AttributeTypeName</a>

First included in: Merchandising/RetailTmpBulkProductAttributeValueEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AttributeTypeName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DisplayProductNumber name="DisplayProductNumber">DisplayProductNumber</a>

First included in: Merchandising/RetailTmpBulkProductAttributeValueEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisplayProductNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InternalOrgNumber name="InternalOrgNumber">InternalOrgNumber</a>

First included in: Merchandising/RetailTmpBulkProductAttributeValueEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InternalOrgNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LanguageId name="LanguageId">LanguageId</a>

First included in: Merchandising/RetailTmpBulkProductAttributeValueEntity (this entity)  

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

### <a href=#ValueAsText name="ValueAsText">ValueAsText</a>

First included in: Merchandising/RetailTmpBulkProductAttributeValueEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Attribute value</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValueAsText attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Attribute value</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AttributeProperty name="AttributeProperty">AttributeProperty</a>

First included in: Merchandising/RetailTmpBulkProductAttributeValueEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UOM/Lang/Currency</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AttributeProperty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>UOM/Lang/Currency</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductName name="ProductName">ProductName</a>

First included in: Merchandising/RetailTmpBulkProductAttributeValueEntity (this entity)  

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

### <a href=#AttributeSourceName name="AttributeSourceName">AttributeSourceName</a>

First included in: Merchandising/RetailTmpBulkProductAttributeValueEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Source name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AttributeSourceName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Source name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AttributeSourceTypeAsLabel name="AttributeSourceTypeAsLabel">AttributeSourceTypeAsLabel</a>

First included in: Merchandising/RetailTmpBulkProductAttributeValueEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Source type</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AttributeSourceTypeAsLabel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Source type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequiredAsLabel name="RequiredAsLabel">RequiredAsLabel</a>

First included in: Merchandising/RetailTmpBulkProductAttributeValueEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Required</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequiredAsLabel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Required</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataTypeAsLabel name="DataTypeAsLabel">DataTypeAsLabel</a>

First included in: Merchandising/RetailTmpBulkProductAttributeValueEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Attribute type</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataTypeAsLabel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Attribute type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TmpCatBulkAttrib name="TmpCatBulkAttrib">TmpCatBulkAttrib</a>

First included in: Merchandising/RetailTmpBulkProductAttributeValueEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TmpCatBulkAttrib attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_RetailTmpBulkProductAttributeValueRelationshipId name="BackingTable_RetailTmpBulkProductAttributeValueRelationshipId">BackingTable_RetailTmpBulkProductAttributeValueRelationshipId</a>

First included in: Merchandising/RetailTmpBulkProductAttributeValueEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailTmpBulkProductAttributeValueRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/System/SystemAdministration/Main/RetailTmpBulkProductAttributeValue.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Main/RetailTmpBulkProductAttributeValue.cdm.json/RetailTmpBulkProductAttributeValue</a></td><td><a href="../../../Tables/System/SystemAdministration/Main/RetailTmpBulkProductAttributeValue.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
