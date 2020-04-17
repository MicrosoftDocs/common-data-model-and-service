---
title: RetailCatalogInternalOrganizationProductAttributeValueEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/16/2020
ms.author: nebanfic
---

# @RETAIL:CatalogInternalOrgProductAttributeValue

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Entities/Commerce/Retail/RetailCatalogInternalOrganizationProductAttributeValueEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.Application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>@RETAIL:CatalogInternalOrgProductAttributeValue</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[CatalogNumber](#CatalogNumber)||<a href="RetailCatalogInternalOrganizationProductAttributeValueEntity.md" target="_blank">Retail/RetailCatalogInternalOrganizationProductAttributeValueEntity</a>|
|[PartyNumber](#PartyNumber)||<a href="RetailCatalogInternalOrganizationProductAttributeValueEntity.md" target="_blank">Retail/RetailCatalogInternalOrganizationProductAttributeValueEntity</a>|
|[DisplayProductNumber](#DisplayProductNumber)||<a href="RetailCatalogInternalOrganizationProductAttributeValueEntity.md" target="_blank">Retail/RetailCatalogInternalOrganizationProductAttributeValueEntity</a>|
|[AttributeGroupName](#AttributeGroupName)||<a href="RetailCatalogInternalOrganizationProductAttributeValueEntity.md" target="_blank">Retail/RetailCatalogInternalOrganizationProductAttributeValueEntity</a>|
|[AttributeName](#AttributeName)||<a href="RetailCatalogInternalOrganizationProductAttributeValueEntity.md" target="_blank">Retail/RetailCatalogInternalOrganizationProductAttributeValueEntity</a>|
|[AttributeTypeName](#AttributeTypeName)||<a href="RetailCatalogInternalOrganizationProductAttributeValueEntity.md" target="_blank">Retail/RetailCatalogInternalOrganizationProductAttributeValueEntity</a>|
|[TextValue](#TextValue)||<a href="RetailCatalogInternalOrganizationProductAttributeValueEntity.md" target="_blank">Retail/RetailCatalogInternalOrganizationProductAttributeValueEntity</a>|
|[CurrencyCode](#CurrencyCode)||<a href="RetailCatalogInternalOrganizationProductAttributeValueEntity.md" target="_blank">Retail/RetailCatalogInternalOrganizationProductAttributeValueEntity</a>|
|[CurrencyValue](#CurrencyValue)||<a href="RetailCatalogInternalOrganizationProductAttributeValueEntity.md" target="_blank">Retail/RetailCatalogInternalOrganizationProductAttributeValueEntity</a>|
|[DateTimeValue](#DateTimeValue)||<a href="RetailCatalogInternalOrganizationProductAttributeValueEntity.md" target="_blank">Retail/RetailCatalogInternalOrganizationProductAttributeValueEntity</a>|
|[DecimalValue](#DecimalValue)||<a href="RetailCatalogInternalOrganizationProductAttributeValueEntity.md" target="_blank">Retail/RetailCatalogInternalOrganizationProductAttributeValueEntity</a>|
|[IntegerValue](#IntegerValue)||<a href="RetailCatalogInternalOrganizationProductAttributeValueEntity.md" target="_blank">Retail/RetailCatalogInternalOrganizationProductAttributeValueEntity</a>|
|[BooleanValue](#BooleanValue)||<a href="RetailCatalogInternalOrganizationProductAttributeValueEntity.md" target="_blank">Retail/RetailCatalogInternalOrganizationProductAttributeValueEntity</a>|
|[InternalOrganizationRecId](#InternalOrganizationRecId)||<a href="RetailCatalogInternalOrganizationProductAttributeValueEntity.md" target="_blank">Retail/RetailCatalogInternalOrganizationProductAttributeValueEntity</a>|
|[EcoResAttributeRecId](#EcoResAttributeRecId)||<a href="RetailCatalogInternalOrganizationProductAttributeValueEntity.md" target="_blank">Retail/RetailCatalogInternalOrganizationProductAttributeValueEntity</a>|
|[DataType](#DataType)||<a href="RetailCatalogInternalOrganizationProductAttributeValueEntity.md" target="_blank">Retail/RetailCatalogInternalOrganizationProductAttributeValueEntity</a>|
|[Relationship_CatalogInternalOrganizationEntityRelationshipId](#Relationship_CatalogInternalOrganizationEntityRelationshipId)||<a href="RetailCatalogInternalOrganizationProductAttributeValueEntity.md" target="_blank">Retail/RetailCatalogInternalOrganizationProductAttributeValueEntity</a>|
|[Relationship_CatalogProductEntityRelationshipId](#Relationship_CatalogProductEntityRelationshipId)||<a href="RetailCatalogInternalOrganizationProductAttributeValueEntity.md" target="_blank">Retail/RetailCatalogInternalOrganizationProductAttributeValueEntity</a>|
|[Relationship_RetailCatalogEntityRelationshipId](#Relationship_RetailCatalogEntityRelationshipId)||<a href="RetailCatalogInternalOrganizationProductAttributeValueEntity.md" target="_blank">Retail/RetailCatalogInternalOrganizationProductAttributeValueEntity</a>|
|[BackingTable_RetailCatalogInternalOrganizationEntityRelationshipId](#BackingTable_RetailCatalogInternalOrganizationEntityRelationshipId)||<a href="RetailCatalogInternalOrganizationProductAttributeValueEntity.md" target="_blank">Retail/RetailCatalogInternalOrganizationProductAttributeValueEntity</a>|

### <a href=#CatalogNumber name="CatalogNumber">CatalogNumber</a>

First included in: Retail/RetailCatalogInternalOrganizationProductAttributeValueEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CatalogNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PartyNumber name="PartyNumber">PartyNumber</a>

First included in: Retail/RetailCatalogInternalOrganizationProductAttributeValueEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PartyNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DisplayProductNumber name="DisplayProductNumber">DisplayProductNumber</a>

First included in: Retail/RetailCatalogInternalOrganizationProductAttributeValueEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisplayProductNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AttributeGroupName name="AttributeGroupName">AttributeGroupName</a>

First included in: Retail/RetailCatalogInternalOrganizationProductAttributeValueEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AttributeGroupName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AttributeName name="AttributeName">AttributeName</a>

First included in: Retail/RetailCatalogInternalOrganizationProductAttributeValueEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AttributeName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AttributeTypeName name="AttributeTypeName">AttributeTypeName</a>

First included in: Retail/RetailCatalogInternalOrganizationProductAttributeValueEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AttributeTypeName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TextValue name="TextValue">TextValue</a>

First included in: Retail/RetailCatalogInternalOrganizationProductAttributeValueEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TextValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: Retail/RetailCatalogInternalOrganizationProductAttributeValueEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyValue name="CurrencyValue">CurrencyValue</a>

First included in: Retail/RetailCatalogInternalOrganizationProductAttributeValueEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DateTimeValue name="DateTimeValue">DateTimeValue</a>

First included in: Retail/RetailCatalogInternalOrganizationProductAttributeValueEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DateTimeValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DecimalValue name="DecimalValue">DecimalValue</a>

First included in: Retail/RetailCatalogInternalOrganizationProductAttributeValueEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DecimalValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntegerValue name="IntegerValue">IntegerValue</a>

First included in: Retail/RetailCatalogInternalOrganizationProductAttributeValueEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntegerValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BooleanValue name="BooleanValue">BooleanValue</a>

First included in: Retail/RetailCatalogInternalOrganizationProductAttributeValueEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BooleanValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InternalOrganizationRecId name="InternalOrganizationRecId">InternalOrganizationRecId</a>

First included in: Retail/RetailCatalogInternalOrganizationProductAttributeValueEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InternalOrganizationRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EcoResAttributeRecId name="EcoResAttributeRecId">EcoResAttributeRecId</a>

First included in: Retail/RetailCatalogInternalOrganizationProductAttributeValueEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EcoResAttributeRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataType name="DataType">DataType</a>

First included in: Retail/RetailCatalogInternalOrganizationProductAttributeValueEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CatalogInternalOrganizationEntityRelationshipId name="Relationship_CatalogInternalOrganizationEntityRelationshipId">Relationship_CatalogInternalOrganizationEntityRelationshipId</a>

First included in: Retail/RetailCatalogInternalOrganizationProductAttributeValueEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CatalogInternalOrganizationEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_CatalogProductEntityRelationshipId name="Relationship_CatalogProductEntityRelationshipId">Relationship_CatalogProductEntityRelationshipId</a>

First included in: Retail/RetailCatalogInternalOrganizationProductAttributeValueEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CatalogProductEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_RetailCatalogEntityRelationshipId name="Relationship_RetailCatalogEntityRelationshipId">Relationship_RetailCatalogEntityRelationshipId</a>

First included in: Retail/RetailCatalogInternalOrganizationProductAttributeValueEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailCatalogEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_RetailCatalogInternalOrganizationEntityRelationshipId name="BackingTable_RetailCatalogInternalOrganizationEntityRelationshipId">BackingTable_RetailCatalogInternalOrganizationEntityRelationshipId</a>

First included in: Retail/RetailCatalogInternalOrganizationProductAttributeValueEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailCatalogInternalOrganizationEntityRelationshipId attribute are listed below.</summary>

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
