---
title: PCTableConstraintColumnCategoryAttribute - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# Attached table constraint attribute

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/PCTableConstraintColumnCategoryAttribute.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PCTableConstraintColumnCategoryAttribute/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Attached table constraint attribute</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="PCTableConstraintColumnCategoryAttribute.md" target="_blank">Main/PCTableConstraintColumnCategoryAttribute</a>|
|[CategoryAttribute](#CategoryAttribute)||<a href="PCTableConstraintColumnCategoryAttribute.md" target="_blank">Main/PCTableConstraintColumnCategoryAttribute</a>|
|[SubComponentPath](#SubComponentPath)||<a href="PCTableConstraintColumnCategoryAttribute.md" target="_blank">Main/PCTableConstraintColumnCategoryAttribute</a>|
|[TableConstraint](#TableConstraint)||<a href="PCTableConstraintColumnCategoryAttribute.md" target="_blank">Main/PCTableConstraintColumnCategoryAttribute</a>|
|[TableConstraintColumnDefinition](#TableConstraintColumnDefinition)||<a href="PCTableConstraintColumnCategoryAttribute.md" target="_blank">Main/PCTableConstraintColumnCategoryAttribute</a>|
|[Relationship_CategoryAttributeRelationshipId](#Relationship_CategoryAttributeRelationshipId)||<a href="PCTableConstraintColumnCategoryAttribute.md" target="_blank">Main/PCTableConstraintColumnCategoryAttribute</a>|
|[Relationship_SubComponentPathRelationshipId](#Relationship_SubComponentPathRelationshipId)||<a href="PCTableConstraintColumnCategoryAttribute.md" target="_blank">Main/PCTableConstraintColumnCategoryAttribute</a>|
|[Relationship_TableConstraintRelationshipId](#Relationship_TableConstraintRelationshipId)||<a href="PCTableConstraintColumnCategoryAttribute.md" target="_blank">Main/PCTableConstraintColumnCategoryAttribute</a>|
|[Relationship_TableConstraintColumnRelationshipId](#Relationship_TableConstraintColumnRelationshipId)||<a href="PCTableConstraintColumnCategoryAttribute.md" target="_blank">Main/PCTableConstraintColumnCategoryAttribute</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/PCTableConstraintColumnCategoryAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PCTableConstraintColumnCategoryAttribute/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CategoryAttribute name="CategoryAttribute">CategoryAttribute</a>

First included in: Main/PCTableConstraintColumnCategoryAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Category attribute reference</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CategoryAttribute attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Category attribute reference</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SubComponentPath name="SubComponentPath">SubComponentPath</a>

First included in: Main/PCTableConstraintColumnCategoryAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubComponentPath attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TableConstraint name="TableConstraint">TableConstraint</a>

First included in: Main/PCTableConstraintColumnCategoryAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Table constraint reference</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TableConstraint attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Table constraint reference</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TableConstraintColumnDefinition name="TableConstraintColumnDefinition">TableConstraintColumnDefinition</a>

First included in: Main/PCTableConstraintColumnCategoryAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Table constraint column reference</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TableConstraintColumnDefinition attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Table constraint column reference</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_CategoryAttributeRelationshipId name="Relationship_CategoryAttributeRelationshipId">Relationship_CategoryAttributeRelationshipId</a>

First included in: Main/PCTableConstraintColumnCategoryAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CategoryAttributeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="EcoResCategoryAttribute.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/EcoResCategoryAttribute.cdm.json/EcoResCategoryAttribute</a></td><td><a href="EcoResCategoryAttribute.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SubComponentPathRelationshipId name="Relationship_SubComponentPathRelationshipId">Relationship_SubComponentPathRelationshipId</a>

First included in: Main/PCTableConstraintColumnCategoryAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SubComponentPathRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="PCSubComponentPath.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/PCSubComponentPath.cdm.json/PCSubComponentPath</a></td><td><a href="PCSubComponentPath.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TableConstraintRelationshipId name="Relationship_TableConstraintRelationshipId">Relationship_TableConstraintRelationshipId</a>

First included in: Main/PCTableConstraintColumnCategoryAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TableConstraintRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="PCTableConstraint.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/PCTableConstraint.cdm.json/PCTableConstraint</a></td><td><a href="PCTableConstraint.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TableConstraintColumnRelationshipId name="Relationship_TableConstraintColumnRelationshipId">Relationship_TableConstraintColumnRelationshipId</a>

First included in: Main/PCTableConstraintColumnCategoryAttribute (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TableConstraintColumnRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="PCTableConstraintColumnDefinition.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/PCTableConstraintColumnDefinition.cdm.json/PCTableConstraintColumnDefinition</a></td><td><a href="PCTableConstraintColumnDefinition.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
