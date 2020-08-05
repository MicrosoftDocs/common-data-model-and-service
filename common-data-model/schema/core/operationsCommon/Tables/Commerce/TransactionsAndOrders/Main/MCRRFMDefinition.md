---
title: MCRRFMDefinition in Main - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# RFM definition table in Main(MCRRFMDefinition)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Commerce/TransactionsAndOrders/Main/MCRRFMDefinition.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[MCRRFMDefinition/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>RFM definition table</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="MCRRFMDefinition.md" target="_blank">Main/MCRRFMDefinition</a>|
|[Active](#Active)||<a href="MCRRFMDefinition.md" target="_blank">Main/MCRRFMDefinition</a>|
|[AddScores](#AddScores)||<a href="MCRRFMDefinition.md" target="_blank">Main/MCRRFMDefinition</a>|
|[EndDate](#EndDate)||<a href="MCRRFMDefinition.md" target="_blank">Main/MCRRFMDefinition</a>|
|[EvenDistribution](#EvenDistribution)||<a href="MCRRFMDefinition.md" target="_blank">Main/MCRRFMDefinition</a>|
|[FrequencyDivisions](#FrequencyDivisions)||<a href="MCRRFMDefinition.md" target="_blank">Main/MCRRFMDefinition</a>|
|[FrequencyMultiplier](#FrequencyMultiplier)||<a href="MCRRFMDefinition.md" target="_blank">Main/MCRRFMDefinition</a>|
|[FrequencyPrecedence](#FrequencyPrecedence)||<a href="MCRRFMDefinition.md" target="_blank">Main/MCRRFMDefinition</a>|
|[MonetaryDivisions](#MonetaryDivisions)||<a href="MCRRFMDefinition.md" target="_blank">Main/MCRRFMDefinition</a>|
|[MonetaryMultiplier](#MonetaryMultiplier)||<a href="MCRRFMDefinition.md" target="_blank">Main/MCRRFMDefinition</a>|
|[MonetaryPrecedence](#MonetaryPrecedence)||<a href="MCRRFMDefinition.md" target="_blank">Main/MCRRFMDefinition</a>|
|[RecencyDatePart](#RecencyDatePart)||<a href="MCRRFMDefinition.md" target="_blank">Main/MCRRFMDefinition</a>|
|[RecencyDivisions](#RecencyDivisions)||<a href="MCRRFMDefinition.md" target="_blank">Main/MCRRFMDefinition</a>|
|[RecencyMultiplier](#RecencyMultiplier)||<a href="MCRRFMDefinition.md" target="_blank">Main/MCRRFMDefinition</a>|
|[RecencyPrecedence](#RecencyPrecedence)||<a href="MCRRFMDefinition.md" target="_blank">Main/MCRRFMDefinition</a>|
|[RFMDefinitionName](#RFMDefinitionName)||<a href="MCRRFMDefinition.md" target="_blank">Main/MCRRFMDefinition</a>|
|[RFMGrossOrNet](#RFMGrossOrNet)||<a href="MCRRFMDefinition.md" target="_blank">Main/MCRRFMDefinition</a>|
|[RFMSubtractReturns](#RFMSubtractReturns)||<a href="MCRRFMDefinition.md" target="_blank">Main/MCRRFMDefinition</a>|
|[SaveHistory](#SaveHistory)||<a href="MCRRFMDefinition.md" target="_blank">Main/MCRRFMDefinition</a>|
|[StartDate](#StartDate)||<a href="MCRRFMDefinition.md" target="_blank">Main/MCRRFMDefinition</a>|
|[DataAreaId](#DataAreaId)||<a href="MCRRFMDefinition.md" target="_blank">Main/MCRRFMDefinition</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="MCRRFMDefinition.md" target="_blank">Main/MCRRFMDefinition</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/MCRRFMDefinition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[MCRRFMDefinition/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Active name="Active">Active</a>

First included in: Main/MCRRFMDefinition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Active</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Active attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Active</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#AddScores name="AddScores">AddScores</a>

First included in: Main/MCRRFMDefinition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddScores attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#EndDate name="EndDate">EndDate</a>

First included in: Main/MCRRFMDefinition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#EvenDistribution name="EvenDistribution">EvenDistribution</a>

First included in: Main/MCRRFMDefinition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EvenDistribution attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#FrequencyDivisions name="FrequencyDivisions">FrequencyDivisions</a>

First included in: Main/MCRRFMDefinition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Divisions</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FrequencyDivisions attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Divisions</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#FrequencyMultiplier name="FrequencyMultiplier">FrequencyMultiplier</a>

First included in: Main/MCRRFMDefinition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Multiplier</td></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FrequencyMultiplier attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Multiplier</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#FrequencyPrecedence name="FrequencyPrecedence">FrequencyPrecedence</a>

First included in: Main/MCRRFMDefinition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Priority</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FrequencyPrecedence attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Priority</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#MonetaryDivisions name="MonetaryDivisions">MonetaryDivisions</a>

First included in: Main/MCRRFMDefinition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Divisions</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MonetaryDivisions attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Divisions</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#MonetaryMultiplier name="MonetaryMultiplier">MonetaryMultiplier</a>

First included in: Main/MCRRFMDefinition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Multiplier</td></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MonetaryMultiplier attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Multiplier</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#MonetaryPrecedence name="MonetaryPrecedence">MonetaryPrecedence</a>

First included in: Main/MCRRFMDefinition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Priority</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MonetaryPrecedence attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Priority</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#RecencyDatePart name="RecencyDatePart">RecencyDatePart</a>

First included in: Main/MCRRFMDefinition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecencyDatePart attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RecencyDivisions name="RecencyDivisions">RecencyDivisions</a>

First included in: Main/MCRRFMDefinition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Divisions</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecencyDivisions attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Divisions</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#RecencyMultiplier name="RecencyMultiplier">RecencyMultiplier</a>

First included in: Main/MCRRFMDefinition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Multiplier</td></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecencyMultiplier attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Multiplier</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#RecencyPrecedence name="RecencyPrecedence">RecencyPrecedence</a>

First included in: Main/MCRRFMDefinition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Priority</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecencyPrecedence attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Priority</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#RFMDefinitionName name="RFMDefinitionName">RFMDefinitionName</a>

First included in: Main/MCRRFMDefinition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFMDefinitionName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RFMGrossOrNet name="RFMGrossOrNet">RFMGrossOrNet</a>

First included in: Main/MCRRFMDefinition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFMGrossOrNet attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RFMSubtractReturns name="RFMSubtractReturns">RFMSubtractReturns</a>

First included in: Main/MCRRFMDefinition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFMSubtractReturns attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#SaveHistory name="SaveHistory">SaveHistory</a>

First included in: Main/MCRRFMDefinition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Save history</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SaveHistory attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Save history</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#StartDate name="StartDate">StartDate</a>

First included in: Main/MCRRFMDefinition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Main/MCRRFMDefinition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Main/MCRRFMDefinition (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CompanyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
