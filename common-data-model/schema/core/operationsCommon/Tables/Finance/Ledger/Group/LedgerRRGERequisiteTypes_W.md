---
title: LedgerRRGERequisiteTypes_W - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Extended data types

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Ledger/Group/LedgerRRGERequisiteTypes_W.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[LedgerRRGERequisiteTypes_W/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Extended data types</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="LedgerRRGERequisiteTypes_W.md" target="_blank">Group/LedgerRRGERequisiteTypes_W</a>|
|[AutomaticCreate](#AutomaticCreate)||<a href="LedgerRRGERequisiteTypes_W.md" target="_blank">Group/LedgerRRGERequisiteTypes_W</a>|
|[BaseType](#BaseType)||<a href="LedgerRRGERequisiteTypes_W.md" target="_blank">Group/LedgerRRGERequisiteTypes_W</a>|
|[FractionDigits](#FractionDigits)||<a href="LedgerRRGERequisiteTypes_W.md" target="_blank">Group/LedgerRRGERequisiteTypes_W</a>|
|[Length](#Length)||<a href="LedgerRRGERequisiteTypes_W.md" target="_blank">Group/LedgerRRGERequisiteTypes_W</a>|
|[MaxExclusive](#MaxExclusive)||<a href="LedgerRRGERequisiteTypes_W.md" target="_blank">Group/LedgerRRGERequisiteTypes_W</a>|
|[MaxInclusive](#MaxInclusive)||<a href="LedgerRRGERequisiteTypes_W.md" target="_blank">Group/LedgerRRGERequisiteTypes_W</a>|
|[MaxLength](#MaxLength)||<a href="LedgerRRGERequisiteTypes_W.md" target="_blank">Group/LedgerRRGERequisiteTypes_W</a>|
|[MinExclusive](#MinExclusive)||<a href="LedgerRRGERequisiteTypes_W.md" target="_blank">Group/LedgerRRGERequisiteTypes_W</a>|
|[MinInclusive](#MinInclusive)||<a href="LedgerRRGERequisiteTypes_W.md" target="_blank">Group/LedgerRRGERequisiteTypes_W</a>|
|[MinLength](#MinLength)||<a href="LedgerRRGERequisiteTypes_W.md" target="_blank">Group/LedgerRRGERequisiteTypes_W</a>|
|[RequisiteTypeId](#RequisiteTypeId)||<a href="LedgerRRGERequisiteTypes_W.md" target="_blank">Group/LedgerRRGERequisiteTypes_W</a>|
|[TotalDigits](#TotalDigits)||<a href="LedgerRRGERequisiteTypes_W.md" target="_blank">Group/LedgerRRGERequisiteTypes_W</a>|
|[TypeAnnotation](#TypeAnnotation)||<a href="LedgerRRGERequisiteTypes_W.md" target="_blank">Group/LedgerRRGERequisiteTypes_W</a>|
|[DataAreaId](#DataAreaId)||<a href="LedgerRRGERequisiteTypes_W.md" target="_blank">Group/LedgerRRGERequisiteTypes_W</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="LedgerRRGERequisiteTypes_W.md" target="_blank">Group/LedgerRRGERequisiteTypes_W</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Group/LedgerRRGERequisiteTypes_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[LedgerRRGERequisiteTypes_W/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AutomaticCreate name="AutomaticCreate">AutomaticCreate</a>

First included in: Group/LedgerRRGERequisiteTypes_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Automatic creation</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AutomaticCreate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Automatic creation</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#BaseType name="BaseType">BaseType</a>

First included in: Group/LedgerRRGERequisiteTypes_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BaseType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#FractionDigits name="FractionDigits">FractionDigits</a>

First included in: Group/LedgerRRGERequisiteTypes_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FractionDigits attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Length name="Length">Length</a>

First included in: Group/LedgerRRGERequisiteTypes_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Length attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MaxExclusive name="MaxExclusive">MaxExclusive</a>

First included in: Group/LedgerRRGERequisiteTypes_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxExclusive attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#MaxInclusive name="MaxInclusive">MaxInclusive</a>

First included in: Group/LedgerRRGERequisiteTypes_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxInclusive attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#MaxLength name="MaxLength">MaxLength</a>

First included in: Group/LedgerRRGERequisiteTypes_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxLength attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MinExclusive name="MinExclusive">MinExclusive</a>

First included in: Group/LedgerRRGERequisiteTypes_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinExclusive attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#MinInclusive name="MinInclusive">MinInclusive</a>

First included in: Group/LedgerRRGERequisiteTypes_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinInclusive attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#MinLength name="MinLength">MinLength</a>

First included in: Group/LedgerRRGERequisiteTypes_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinLength attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RequisiteTypeId name="RequisiteTypeId">RequisiteTypeId</a>

First included in: Group/LedgerRRGERequisiteTypes_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequisiteTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalDigits name="TotalDigits">TotalDigits</a>

First included in: Group/LedgerRRGERequisiteTypes_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalDigits attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TypeAnnotation name="TypeAnnotation">TypeAnnotation</a>

First included in: Group/LedgerRRGERequisiteTypes_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TypeAnnotation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Group/LedgerRRGERequisiteTypes_W (this entity)  

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

First included in: Group/LedgerRRGERequisiteTypes_W (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
