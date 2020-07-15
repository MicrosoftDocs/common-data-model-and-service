---
title: EcoResProductAttributeGroupAttributeAssignmentEntity in ProductInformationManagement - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/15/2020
ms.author: nebanfic
---

# Product attribute group attribute assignments in ProductInformationManagement(EcoResProductAttributeGroupAttributeAssignmentEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductInformationManagement/EcoResProductAttributeGroupAttributeAssignmentEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Product attribute group attribute assignments</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ProductAttributeGroupName](#ProductAttributeGroupName)||<a href="EcoResProductAttributeGroupAttributeAssignmentEntity.md" target="_blank">ProductInformationManagement/EcoResProductAttributeGroupAttributeAssignmentEntity</a>|
|[ProductAttributeName](#ProductAttributeName)||<a href="EcoResProductAttributeGroupAttributeAssignmentEntity.md" target="_blank">ProductInformationManagement/EcoResProductAttributeGroupAttributeAssignmentEntity</a>|
|[ProductAttributeTypeName](#ProductAttributeTypeName)||<a href="EcoResProductAttributeGroupAttributeAssignmentEntity.md" target="_blank">ProductInformationManagement/EcoResProductAttributeGroupAttributeAssignmentEntity</a>|
|[CurrencyCode](#CurrencyCode)||<a href="EcoResProductAttributeGroupAttributeAssignmentEntity.md" target="_blank">ProductInformationManagement/EcoResProductAttributeGroupAttributeAssignmentEntity</a>|
|[CurrencyValue](#CurrencyValue)||<a href="EcoResProductAttributeGroupAttributeAssignmentEntity.md" target="_blank">ProductInformationManagement/EcoResProductAttributeGroupAttributeAssignmentEntity</a>|
|[BooleanValue](#BooleanValue)||<a href="EcoResProductAttributeGroupAttributeAssignmentEntity.md" target="_blank">ProductInformationManagement/EcoResProductAttributeGroupAttributeAssignmentEntity</a>|
|[DateTimeValue](#DateTimeValue)||<a href="EcoResProductAttributeGroupAttributeAssignmentEntity.md" target="_blank">ProductInformationManagement/EcoResProductAttributeGroupAttributeAssignmentEntity</a>|
|[DecimalValue](#DecimalValue)||<a href="EcoResProductAttributeGroupAttributeAssignmentEntity.md" target="_blank">ProductInformationManagement/EcoResProductAttributeGroupAttributeAssignmentEntity</a>|
|[IntegerValue](#IntegerValue)||<a href="EcoResProductAttributeGroupAttributeAssignmentEntity.md" target="_blank">ProductInformationManagement/EcoResProductAttributeGroupAttributeAssignmentEntity</a>|
|[TextValue](#TextValue)||<a href="EcoResProductAttributeGroupAttributeAssignmentEntity.md" target="_blank">ProductInformationManagement/EcoResProductAttributeGroupAttributeAssignmentEntity</a>|
|[ProductAttributeRetailDisplayOrder](#ProductAttributeRetailDisplayOrder)||<a href="EcoResProductAttributeGroupAttributeAssignmentEntity.md" target="_blank">ProductInformationManagement/EcoResProductAttributeGroupAttributeAssignmentEntity</a>|
|[BackingTable_EcoResAttributeGroupAttributeRelationshipId](#BackingTable_EcoResAttributeGroupAttributeRelationshipId)||<a href="EcoResProductAttributeGroupAttributeAssignmentEntity.md" target="_blank">ProductInformationManagement/EcoResProductAttributeGroupAttributeAssignmentEntity</a>|

### <a href=#ProductAttributeGroupName name="ProductAttributeGroupName">ProductAttributeGroupName</a>

First included in: ProductInformationManagement/EcoResProductAttributeGroupAttributeAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductAttributeGroupName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductAttributeName name="ProductAttributeName">ProductAttributeName</a>

First included in: ProductInformationManagement/EcoResProductAttributeGroupAttributeAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductAttributeName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductAttributeTypeName name="ProductAttributeTypeName">ProductAttributeTypeName</a>

First included in: ProductInformationManagement/EcoResProductAttributeGroupAttributeAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Attribute type name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductAttributeTypeName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Attribute type name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: ProductInformationManagement/EcoResProductAttributeGroupAttributeAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyValue name="CurrencyValue">CurrencyValue</a>

First included in: ProductInformationManagement/EcoResProductAttributeGroupAttributeAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BooleanValue name="BooleanValue">BooleanValue</a>

First included in: ProductInformationManagement/EcoResProductAttributeGroupAttributeAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BooleanValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DateTimeValue name="DateTimeValue">DateTimeValue</a>

First included in: ProductInformationManagement/EcoResProductAttributeGroupAttributeAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DateTimeValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DecimalValue name="DecimalValue">DecimalValue</a>

First included in: ProductInformationManagement/EcoResProductAttributeGroupAttributeAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DecimalValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntegerValue name="IntegerValue">IntegerValue</a>

First included in: ProductInformationManagement/EcoResProductAttributeGroupAttributeAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntegerValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TextValue name="TextValue">TextValue</a>

First included in: ProductInformationManagement/EcoResProductAttributeGroupAttributeAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TextValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductAttributeRetailDisplayOrder name="ProductAttributeRetailDisplayOrder">ProductAttributeRetailDisplayOrder</a>

First included in: ProductInformationManagement/EcoResProductAttributeGroupAttributeAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductAttributeRetailDisplayOrder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_EcoResAttributeGroupAttributeRelationshipId name="BackingTable_EcoResAttributeGroupAttributeRelationshipId">BackingTable_EcoResAttributeGroupAttributeRelationshipId</a>

First included in: ProductInformationManagement/EcoResProductAttributeGroupAttributeAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_EcoResAttributeGroupAttributeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProductInformationManagement/Main/EcoResAttributeGroupAttribute.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/EcoResAttributeGroupAttribute.cdm.json/EcoResAttributeGroupAttribute</a></td><td><a href="../../../Tables/SupplyChain/ProductInformationManagement/Main/EcoResAttributeGroupAttribute.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
