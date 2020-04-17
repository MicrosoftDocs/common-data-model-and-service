---
title: RetailInternalOrganizationProductAttributeValue2Entity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/16/2020
ms.author: nebanfic
---

# @Retail:InternalOrgProductAttributeValue2Entity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Entities/Commerce/Retail/RetailInternalOrganizationProductAttributeValue2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.Application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>@Retail:InternalOrgProductAttributeValue2Entity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[InternalOrganizationPartyNumber](#InternalOrganizationPartyNumber)||<a href="RetailInternalOrganizationProductAttributeValue2Entity.md" target="_blank">Retail/RetailInternalOrganizationProductAttributeValue2Entity</a>|
|[DisplayProductNumber](#DisplayProductNumber)||<a href="RetailInternalOrganizationProductAttributeValue2Entity.md" target="_blank">Retail/RetailInternalOrganizationProductAttributeValue2Entity</a>|
|[AttributeTypeName](#AttributeTypeName)||<a href="RetailInternalOrganizationProductAttributeValue2Entity.md" target="_blank">Retail/RetailInternalOrganizationProductAttributeValue2Entity</a>|
|[AttributeName](#AttributeName)||<a href="RetailInternalOrganizationProductAttributeValue2Entity.md" target="_blank">Retail/RetailInternalOrganizationProductAttributeValue2Entity</a>|
|[TextValue](#TextValue)||<a href="RetailInternalOrganizationProductAttributeValue2Entity.md" target="_blank">Retail/RetailInternalOrganizationProductAttributeValue2Entity</a>|
|[CurrencyCode](#CurrencyCode)||<a href="RetailInternalOrganizationProductAttributeValue2Entity.md" target="_blank">Retail/RetailInternalOrganizationProductAttributeValue2Entity</a>|
|[CurrencyValue](#CurrencyValue)||<a href="RetailInternalOrganizationProductAttributeValue2Entity.md" target="_blank">Retail/RetailInternalOrganizationProductAttributeValue2Entity</a>|
|[DateTimeValue](#DateTimeValue)||<a href="RetailInternalOrganizationProductAttributeValue2Entity.md" target="_blank">Retail/RetailInternalOrganizationProductAttributeValue2Entity</a>|
|[DecimalValue](#DecimalValue)||<a href="RetailInternalOrganizationProductAttributeValue2Entity.md" target="_blank">Retail/RetailInternalOrganizationProductAttributeValue2Entity</a>|
|[DecimalUnitOfMeasureSymbol](#DecimalUnitOfMeasureSymbol)||<a href="RetailInternalOrganizationProductAttributeValue2Entity.md" target="_blank">Retail/RetailInternalOrganizationProductAttributeValue2Entity</a>|
|[IntegerValue](#IntegerValue)||<a href="RetailInternalOrganizationProductAttributeValue2Entity.md" target="_blank">Retail/RetailInternalOrganizationProductAttributeValue2Entity</a>|
|[IntegerUnitOfMeasureSymbol](#IntegerUnitOfMeasureSymbol)||<a href="RetailInternalOrganizationProductAttributeValue2Entity.md" target="_blank">Retail/RetailInternalOrganizationProductAttributeValue2Entity</a>|
|[BooleanValue](#BooleanValue)||<a href="RetailInternalOrganizationProductAttributeValue2Entity.md" target="_blank">Retail/RetailInternalOrganizationProductAttributeValue2Entity</a>|
|[Relationship_RetailInternalOrganizationEntityRelationshipId](#Relationship_RetailInternalOrganizationEntityRelationshipId)||<a href="RetailInternalOrganizationProductAttributeValue2Entity.md" target="_blank">Retail/RetailInternalOrganizationProductAttributeValue2Entity</a>|
|[Relationship_RetailInternalOrganizationProductEntityRelationshipId](#Relationship_RetailInternalOrganizationProductEntityRelationshipId)||<a href="RetailInternalOrganizationProductAttributeValue2Entity.md" target="_blank">Retail/RetailInternalOrganizationProductAttributeValue2Entity</a>|
|[Relationship_CurrencyEntityRelationshipId](#Relationship_CurrencyEntityRelationshipId)||<a href="RetailInternalOrganizationProductAttributeValue2Entity.md" target="_blank">Retail/RetailInternalOrganizationProductAttributeValue2Entity</a>|
|[Relationship_DecimalUnitOfMeasureEntityRelationshipId](#Relationship_DecimalUnitOfMeasureEntityRelationshipId)||<a href="RetailInternalOrganizationProductAttributeValue2Entity.md" target="_blank">Retail/RetailInternalOrganizationProductAttributeValue2Entity</a>|
|[Relationship_IntegerUnitOfMeasureEntityRelationshipId](#Relationship_IntegerUnitOfMeasureEntityRelationshipId)||<a href="RetailInternalOrganizationProductAttributeValue2Entity.md" target="_blank">Retail/RetailInternalOrganizationProductAttributeValue2Entity</a>|
|[BackingTable_EcoResAttributeValueRelationshipId](#BackingTable_EcoResAttributeValueRelationshipId)||<a href="RetailInternalOrganizationProductAttributeValue2Entity.md" target="_blank">Retail/RetailInternalOrganizationProductAttributeValue2Entity</a>|

### <a href=#InternalOrganizationPartyNumber name="InternalOrganizationPartyNumber">InternalOrganizationPartyNumber</a>

First included in: Retail/RetailInternalOrganizationProductAttributeValue2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InternalOrganizationPartyNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DisplayProductNumber name="DisplayProductNumber">DisplayProductNumber</a>

First included in: Retail/RetailInternalOrganizationProductAttributeValue2Entity (this entity)  

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

### <a href=#AttributeTypeName name="AttributeTypeName">AttributeTypeName</a>

First included in: Retail/RetailInternalOrganizationProductAttributeValue2Entity (this entity)  

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

### <a href=#AttributeName name="AttributeName">AttributeName</a>

First included in: Retail/RetailInternalOrganizationProductAttributeValue2Entity (this entity)  

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

### <a href=#TextValue name="TextValue">TextValue</a>

First included in: Retail/RetailInternalOrganizationProductAttributeValue2Entity (this entity)  

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

First included in: Retail/RetailInternalOrganizationProductAttributeValue2Entity (this entity)  

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

First included in: Retail/RetailInternalOrganizationProductAttributeValue2Entity (this entity)  

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

First included in: Retail/RetailInternalOrganizationProductAttributeValue2Entity (this entity)  

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

First included in: Retail/RetailInternalOrganizationProductAttributeValue2Entity (this entity)  

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

### <a href=#DecimalUnitOfMeasureSymbol name="DecimalUnitOfMeasureSymbol">DecimalUnitOfMeasureSymbol</a>

First included in: Retail/RetailInternalOrganizationProductAttributeValue2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DecimalUnitOfMeasureSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntegerValue name="IntegerValue">IntegerValue</a>

First included in: Retail/RetailInternalOrganizationProductAttributeValue2Entity (this entity)  

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

### <a href=#IntegerUnitOfMeasureSymbol name="IntegerUnitOfMeasureSymbol">IntegerUnitOfMeasureSymbol</a>

First included in: Retail/RetailInternalOrganizationProductAttributeValue2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntegerUnitOfMeasureSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BooleanValue name="BooleanValue">BooleanValue</a>

First included in: Retail/RetailInternalOrganizationProductAttributeValue2Entity (this entity)  

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

### <a href=#Relationship_RetailInternalOrganizationEntityRelationshipId name="Relationship_RetailInternalOrganizationEntityRelationshipId">Relationship_RetailInternalOrganizationEntityRelationshipId</a>

First included in: Retail/RetailInternalOrganizationProductAttributeValue2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailInternalOrganizationEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_RetailInternalOrganizationProductEntityRelationshipId name="Relationship_RetailInternalOrganizationProductEntityRelationshipId">Relationship_RetailInternalOrganizationProductEntityRelationshipId</a>

First included in: Retail/RetailInternalOrganizationProductAttributeValue2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailInternalOrganizationProductEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_CurrencyEntityRelationshipId name="Relationship_CurrencyEntityRelationshipId">Relationship_CurrencyEntityRelationshipId</a>

First included in: Retail/RetailInternalOrganizationProductAttributeValue2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CurrencyEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DecimalUnitOfMeasureEntityRelationshipId name="Relationship_DecimalUnitOfMeasureEntityRelationshipId">Relationship_DecimalUnitOfMeasureEntityRelationshipId</a>

First included in: Retail/RetailInternalOrganizationProductAttributeValue2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DecimalUnitOfMeasureEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_IntegerUnitOfMeasureEntityRelationshipId name="Relationship_IntegerUnitOfMeasureEntityRelationshipId">Relationship_IntegerUnitOfMeasureEntityRelationshipId</a>

First included in: Retail/RetailInternalOrganizationProductAttributeValue2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_IntegerUnitOfMeasureEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_EcoResAttributeValueRelationshipId name="BackingTable_EcoResAttributeValueRelationshipId">BackingTable_EcoResAttributeValueRelationshipId</a>

First included in: Retail/RetailInternalOrganizationProductAttributeValue2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_EcoResAttributeValueRelationshipId attribute are listed below.</summary>

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
