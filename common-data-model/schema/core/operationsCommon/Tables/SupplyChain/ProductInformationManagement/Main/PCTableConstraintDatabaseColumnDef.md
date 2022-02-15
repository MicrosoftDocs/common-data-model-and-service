---
title: PCTableConstraintDatabaseColumnDef in Main - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# System defined table constraint column in Main(PCTableConstraintDatabaseColumnDef)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/PCTableConstraintDatabaseColumnDef.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PCTableConstraintDatabaseColumnDef/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Table constraint column</td></tr><tr><td>en</td><td>System defined table constraint column</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="PCTableConstraintDatabaseColumnDef.md" target="_blank">Main/PCTableConstraintDatabaseColumnDef</a>|
|[AttributeType](#AttributeType)||<a href="PCTableConstraintDatabaseColumnDef.md" target="_blank">Main/PCTableConstraintDatabaseColumnDef</a>|
|[InstanceRelationType](#InstanceRelationType)||<a href="PCTableConstraintDatabaseColumnDef.md" target="_blank">Main/PCTableConstraintDatabaseColumnDef</a>|
|[Name](#Name)||<a href="PCTableConstraintDatabaseColumnDef.md" target="_blank">Main/PCTableConstraintDatabaseColumnDef</a>|
|[TableConstraintDefinition](#TableConstraintDefinition)||<a href="PCTableConstraintDatabaseColumnDef.md" target="_blank">Main/PCTableConstraintDatabaseColumnDef</a>|
|[Relationship_AttributeTypeRelationshipId](#Relationship_AttributeTypeRelationshipId)||<a href="PCTableConstraintDatabaseColumnDef.md" target="_blank">Main/PCTableConstraintDatabaseColumnDef</a>|
|[Relationship_TableConstraintDefinitionRelationshipId](#Relationship_TableConstraintDefinitionRelationshipId)||<a href="PCTableConstraintDatabaseColumnDef.md" target="_blank">Main/PCTableConstraintDatabaseColumnDef</a>|
|[ReferencedFieldId](#ReferencedFieldId)||<a href="PCTableConstraintDatabaseColumnDef.md" target="_blank">Main/PCTableConstraintDatabaseColumnDef</a>|
|[ReferencedTableId](#ReferencedTableId)||<a href="PCTableConstraintDatabaseColumnDef.md" target="_blank">Main/PCTableConstraintDatabaseColumnDef</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/PCTableConstraintDatabaseColumnDef (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PCTableConstraintDatabaseColumnDef/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AttributeType name="AttributeType">AttributeType</a>

First included in: Main/PCTableConstraintDatabaseColumnDef (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Domain</td></tr><tr><td>dataFormat</td><td>unknown</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AttributeType attribute are listed below.</summary>

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Domain</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

### <a href=#InstanceRelationType name="InstanceRelationType">InstanceRelationType</a>

First included in: Main/PCTableConstraintDatabaseColumnDef (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InstanceRelationType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: Main/PCTableConstraintDatabaseColumnDef (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TableConstraintDefinition name="TableConstraintDefinition">TableConstraintDefinition</a>

First included in: Main/PCTableConstraintDatabaseColumnDef (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Table constraint definition</td></tr><tr><td>dataFormat</td><td>unknown</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TableConstraintDefinition attribute are listed below.</summary>

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Table constraint definition</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

### <a href=#Relationship_AttributeTypeRelationshipId name="Relationship_AttributeTypeRelationshipId">Relationship_AttributeTypeRelationshipId</a>

First included in: Main/PCTableConstraintDatabaseColumnDef (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AttributeTypeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="EcoResAttributeType.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/EcoResAttributeType.cdm.json/EcoResAttributeType</a></td><td><a href="EcoResAttributeType.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TableConstraintDefinitionRelationshipId name="Relationship_TableConstraintDefinitionRelationshipId">Relationship_TableConstraintDefinitionRelationshipId</a>

First included in: Main/PCTableConstraintDatabaseColumnDef (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TableConstraintDefinitionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="PCTableConstraintDefinition.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/PCTableConstraintDefinition.cdm.json/PCTableConstraintDefinition</a></td><td><a href="PCTableConstraintDefinition.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReferencedFieldId name="ReferencedFieldId">ReferencedFieldId</a>

First included in: Main/PCTableConstraintDatabaseColumnDef (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReferencedFieldId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReferencedTableId name="ReferencedTableId">ReferencedTableId</a>

First included in: Main/PCTableConstraintDatabaseColumnDef (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReferencedTableId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>
