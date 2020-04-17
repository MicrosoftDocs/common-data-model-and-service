---
title: RetailInternalOrganizationProductAttributeMetadataEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/16/2020
ms.author: nebanfic
---

# @Retail:InternalOrganizationProductAttributeMetadataEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Entities/Commerce/Retail/RetailInternalOrganizationProductAttributeMetadataEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.Application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>@Retail:InternalOrganizationProductAttributeMetadataEntity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[PartyNumber](#PartyNumber)||<a href="RetailInternalOrganizationProductAttributeMetadataEntity.md" target="_blank">Retail/RetailInternalOrganizationProductAttributeMetadataEntity</a>|
|[OrganizationName](#OrganizationName)||<a href="RetailInternalOrganizationProductAttributeMetadataEntity.md" target="_blank">Retail/RetailInternalOrganizationProductAttributeMetadataEntity</a>|
|[AttributeName](#AttributeName)||<a href="RetailInternalOrganizationProductAttributeMetadataEntity.md" target="_blank">Retail/RetailInternalOrganizationProductAttributeMetadataEntity</a>|
|[AttributeTypeName](#AttributeTypeName)||<a href="RetailInternalOrganizationProductAttributeMetadataEntity.md" target="_blank">Retail/RetailInternalOrganizationProductAttributeMetadataEntity</a>|
|[AttributeRelationType](#AttributeRelationType)||<a href="RetailInternalOrganizationProductAttributeMetadataEntity.md" target="_blank">Retail/RetailInternalOrganizationProductAttributeMetadataEntity</a>|
|[IsRequired](#IsRequired)||<a href="RetailInternalOrganizationProductAttributeMetadataEntity.md" target="_blank">Retail/RetailInternalOrganizationProductAttributeMetadataEntity</a>|
|[KeyName](#KeyName)||<a href="RetailInternalOrganizationProductAttributeMetadataEntity.md" target="_blank">Retail/RetailInternalOrganizationProductAttributeMetadataEntity</a>|
|[XmlMetadata](#XmlMetadata)||<a href="RetailInternalOrganizationProductAttributeMetadataEntity.md" target="_blank">Retail/RetailInternalOrganizationProductAttributeMetadataEntity</a>|
|[XmlMetadataVersionNumber](#XmlMetadataVersionNumber)||<a href="RetailInternalOrganizationProductAttributeMetadataEntity.md" target="_blank">Retail/RetailInternalOrganizationProductAttributeMetadataEntity</a>|
|[Relationship_OperatingUnitRelationshipId](#Relationship_OperatingUnitRelationshipId)||<a href="RetailInternalOrganizationProductAttributeMetadataEntity.md" target="_blank">Retail/RetailInternalOrganizationProductAttributeMetadataEntity</a>|
|[Relationship_DepartmentRelationshipId](#Relationship_DepartmentRelationshipId)||<a href="RetailInternalOrganizationProductAttributeMetadataEntity.md" target="_blank">Retail/RetailInternalOrganizationProductAttributeMetadataEntity</a>|
|[Relationship_ProductAttributeRelationshipId](#Relationship_ProductAttributeRelationshipId)||<a href="RetailInternalOrganizationProductAttributeMetadataEntity.md" target="_blank">Retail/RetailInternalOrganizationProductAttributeMetadataEntity</a>|
|[BackingTable_RetailProdAttributeInternalOrgMetadataRelationshipId](#BackingTable_RetailProdAttributeInternalOrgMetadataRelationshipId)||<a href="RetailInternalOrganizationProductAttributeMetadataEntity.md" target="_blank">Retail/RetailInternalOrganizationProductAttributeMetadataEntity</a>|

### <a href=#PartyNumber name="PartyNumber">PartyNumber</a>

First included in: Retail/RetailInternalOrganizationProductAttributeMetadataEntity (this entity)  

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

### <a href=#OrganizationName name="OrganizationName">OrganizationName</a>

First included in: Retail/RetailInternalOrganizationProductAttributeMetadataEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrganizationName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AttributeName name="AttributeName">AttributeName</a>

First included in: Retail/RetailInternalOrganizationProductAttributeMetadataEntity (this entity)  

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

First included in: Retail/RetailInternalOrganizationProductAttributeMetadataEntity (this entity)  

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

### <a href=#AttributeRelationType name="AttributeRelationType">AttributeRelationType</a>

First included in: Retail/RetailInternalOrganizationProductAttributeMetadataEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AttributeRelationType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsRequired name="IsRequired">IsRequired</a>

First included in: Retail/RetailInternalOrganizationProductAttributeMetadataEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsRequired attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#KeyName name="KeyName">KeyName</a>

First included in: Retail/RetailInternalOrganizationProductAttributeMetadataEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the KeyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#XmlMetadata name="XmlMetadata">XmlMetadata</a>

First included in: Retail/RetailInternalOrganizationProductAttributeMetadataEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the XmlMetadata attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#XmlMetadataVersionNumber name="XmlMetadataVersionNumber">XmlMetadataVersionNumber</a>

First included in: Retail/RetailInternalOrganizationProductAttributeMetadataEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the XmlMetadataVersionNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_OperatingUnitRelationshipId name="Relationship_OperatingUnitRelationshipId">Relationship_OperatingUnitRelationshipId</a>

First included in: Retail/RetailInternalOrganizationProductAttributeMetadataEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OperatingUnitRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DepartmentRelationshipId name="Relationship_DepartmentRelationshipId">Relationship_DepartmentRelationshipId</a>

First included in: Retail/RetailInternalOrganizationProductAttributeMetadataEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DepartmentRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ProductAttributeRelationshipId name="Relationship_ProductAttributeRelationshipId">Relationship_ProductAttributeRelationshipId</a>

First included in: Retail/RetailInternalOrganizationProductAttributeMetadataEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProductAttributeRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_RetailProdAttributeInternalOrgMetadataRelationshipId name="BackingTable_RetailProdAttributeInternalOrgMetadataRelationshipId">BackingTable_RetailProdAttributeInternalOrgMetadataRelationshipId</a>

First included in: Retail/RetailInternalOrganizationProductAttributeMetadataEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailProdAttributeInternalOrgMetadataRelationshipId attribute are listed below.</summary>

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
