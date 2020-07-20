---
title: HcmPositionForecastAcctLineNote in Miscellaneous - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/20/2020
ms.author: nebanfic
---

# Information about the cost element line associated with the forecast position in Miscellaneous(HcmPositionForecastAcctLineNote)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Budget/Miscellaneous/HcmPositionForecastAcctLineNote.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[HcmPositionForecastAcctLineNote/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Information about the cost element line associated with the forecast position</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="HcmPositionForecastAcctLineNote.md" target="_blank">Miscellaneous/HcmPositionForecastAcctLineNote</a>|
|[HcmPositionForecastBudgetAcctLine](#HcmPositionForecastBudgetAcctLine)||<a href="HcmPositionForecastAcctLineNote.md" target="_blank">Miscellaneous/HcmPositionForecastAcctLineNote</a>|
|[Note](#Note)||<a href="HcmPositionForecastAcctLineNote.md" target="_blank">Miscellaneous/HcmPositionForecastAcctLineNote</a>|
|[Relationship_HcmPositionForecastBudgetAcctLineRelationshipId](#Relationship_HcmPositionForecastBudgetAcctLineRelationshipId)||<a href="HcmPositionForecastAcctLineNote.md" target="_blank">Miscellaneous/HcmPositionForecastAcctLineNote</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/HcmPositionForecastAcctLineNote (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[HcmPositionForecastAcctLineNote/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#HcmPositionForecastBudgetAcctLine name="HcmPositionForecastBudgetAcctLine">HcmPositionForecastBudgetAcctLine</a>

First included in: Miscellaneous/HcmPositionForecastAcctLineNote (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HcmPositionForecastBudgetAcctLine attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Note name="Note">Note</a>

First included in: Miscellaneous/HcmPositionForecastAcctLineNote (this entity)  

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

### <a href=#Relationship_HcmPositionForecastBudgetAcctLineRelationshipId name="Relationship_HcmPositionForecastBudgetAcctLineRelationshipId">Relationship_HcmPositionForecastBudgetAcctLineRelationshipId</a>

First included in: Miscellaneous/HcmPositionForecastAcctLineNote (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_HcmPositionForecastBudgetAcctLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/HcmPositionForecastBudgetAcctLine.md" target="_blank">/core/operationsCommon/Tables/Finance/Budget/Group/HcmPositionForecastBudgetAcctLine.cdm.json/HcmPositionForecastBudgetAcctLine</a></td><td><a href="../Group/HcmPositionForecastBudgetAcctLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
