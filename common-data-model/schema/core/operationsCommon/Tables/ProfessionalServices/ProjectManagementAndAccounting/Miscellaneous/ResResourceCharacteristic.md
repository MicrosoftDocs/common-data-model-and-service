---
title: ResResourceCharacteristic in Miscellaneous - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# ResResourceCharacteristic in Miscellaneous

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Miscellaneous/ResResourceCharacteristic.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ResResourceCharacteristic/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="ResResourceCharacteristic.md" target="_blank">Miscellaneous/ResResourceCharacteristic</a>|
|[Resource](#Resource)||<a href="ResResourceCharacteristic.md" target="_blank">Miscellaneous/ResResourceCharacteristic</a>|
|[Characteristic](#Characteristic)||<a href="ResResourceCharacteristic.md" target="_blank">Miscellaneous/ResResourceCharacteristic</a>|
|[ValidFrom](#ValidFrom)||<a href="ResResourceCharacteristic.md" target="_blank">Miscellaneous/ResResourceCharacteristic</a>|
|[ValidTo](#ValidTo)||<a href="ResResourceCharacteristic.md" target="_blank">Miscellaneous/ResResourceCharacteristic</a>|
|[Rating](#Rating)||<a href="ResResourceCharacteristic.md" target="_blank">Miscellaneous/ResResourceCharacteristic</a>|
|[Note](#Note)||<a href="ResResourceCharacteristic.md" target="_blank">Miscellaneous/ResResourceCharacteristic</a>|
|[ResourceIdExt](#ResourceIdExt)||<a href="ResResourceCharacteristic.md" target="_blank">Miscellaneous/ResResourceCharacteristic</a>|
|[Relationship_CharacteristicRelationshipId](#Relationship_CharacteristicRelationshipId)||<a href="ResResourceCharacteristic.md" target="_blank">Miscellaneous/ResResourceCharacteristic</a>|
|[Relationship_RatingLevelRelationshipId](#Relationship_RatingLevelRelationshipId)||<a href="ResResourceCharacteristic.md" target="_blank">Miscellaneous/ResResourceCharacteristic</a>|
|[Relationship_ResProjectResourceRelationshipId](#Relationship_ResProjectResourceRelationshipId)||<a href="ResResourceCharacteristic.md" target="_blank">Miscellaneous/ResResourceCharacteristic</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/ResResourceCharacteristic (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ResResourceCharacteristic/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Resource name="Resource">Resource</a>

First included in: Miscellaneous/ResResourceCharacteristic (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Resource attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Characteristic name="Characteristic">Characteristic</a>

First included in: Miscellaneous/ResResourceCharacteristic (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Characteristic attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ValidFrom name="ValidFrom">ValidFrom</a>

First included in: Miscellaneous/ResResourceCharacteristic (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidFrom attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#ValidTo name="ValidTo">ValidTo</a>

First included in: Miscellaneous/ResResourceCharacteristic (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidTo attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#Rating name="Rating">Rating</a>

First included in: Miscellaneous/ResResourceCharacteristic (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Rating attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Note name="Note">Note</a>

First included in: Miscellaneous/ResResourceCharacteristic (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Note attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResourceIdExt name="ResourceIdExt">ResourceIdExt</a>

First included in: Miscellaneous/ResResourceCharacteristic (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResourceIdExt attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CharacteristicRelationshipId name="Relationship_CharacteristicRelationshipId">Relationship_CharacteristicRelationshipId</a>

First included in: Miscellaneous/ResResourceCharacteristic (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CharacteristicRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="ResCharacteristic.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Miscellaneous/ResCharacteristic.cdm.json/ResCharacteristic</a></td><td><a href="ResCharacteristic.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RatingLevelRelationshipId name="Relationship_RatingLevelRelationshipId">Relationship_RatingLevelRelationshipId</a>

First included in: Miscellaneous/ResResourceCharacteristic (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RatingLevelRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="ResRatingLevel.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Miscellaneous/ResRatingLevel.cdm.json/ResRatingLevel</a></td><td><a href="ResRatingLevel.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ResProjectResourceRelationshipId name="Relationship_ResProjectResourceRelationshipId">Relationship_ResProjectResourceRelationshipId</a>

First included in: Miscellaneous/ResResourceCharacteristic (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ResProjectResourceRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="ResProjectResource.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Miscellaneous/ResProjectResource.cdm.json/ResProjectResource</a></td><td><a href="ResProjectResource.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
