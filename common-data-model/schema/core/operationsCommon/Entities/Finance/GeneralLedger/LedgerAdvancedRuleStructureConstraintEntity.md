---
title: LedgerAdvancedRuleStructureConstraintEntity in GeneralLedger - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/20/2020
ms.author: nebanfic
---

# Advanced rule structure allowed values in GeneralLedger(LedgerAdvancedRuleStructureConstraintEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/GeneralLedger/LedgerAdvancedRuleStructureConstraintEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Advanced rule structure allowed values</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AdvancedRuleStructure](#AdvancedRuleStructure)||<a href="LedgerAdvancedRuleStructureConstraintEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureConstraintEntity</a>|
|[ActiveFrom](#ActiveFrom)||<a href="LedgerAdvancedRuleStructureConstraintEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureConstraintEntity</a>|
|[ActiveTo](#ActiveTo)||<a href="LedgerAdvancedRuleStructureConstraintEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureConstraintEntity</a>|
|[Position](#Position)||<a href="LedgerAdvancedRuleStructureConstraintEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureConstraintEntity</a>|
|[DimensionHierarchy](#DimensionHierarchy)||<a href="LedgerAdvancedRuleStructureConstraintEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureConstraintEntity</a>|
|[Status](#Status)||<a href="LedgerAdvancedRuleStructureConstraintEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureConstraintEntity</a>|
|[SegmentCriteria01](#SegmentCriteria01)||<a href="LedgerAdvancedRuleStructureConstraintEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureConstraintEntity</a>|
|[SegmentCriteria02](#SegmentCriteria02)||<a href="LedgerAdvancedRuleStructureConstraintEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureConstraintEntity</a>|
|[SegmentCriteria03](#SegmentCriteria03)||<a href="LedgerAdvancedRuleStructureConstraintEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureConstraintEntity</a>|
|[SegmentCriteria04](#SegmentCriteria04)||<a href="LedgerAdvancedRuleStructureConstraintEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureConstraintEntity</a>|
|[SegmentCriteria05](#SegmentCriteria05)||<a href="LedgerAdvancedRuleStructureConstraintEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureConstraintEntity</a>|
|[SegmentCriteria06](#SegmentCriteria06)||<a href="LedgerAdvancedRuleStructureConstraintEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureConstraintEntity</a>|
|[SegmentCriteria07](#SegmentCriteria07)||<a href="LedgerAdvancedRuleStructureConstraintEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureConstraintEntity</a>|
|[SegmentCriteria08](#SegmentCriteria08)||<a href="LedgerAdvancedRuleStructureConstraintEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureConstraintEntity</a>|
|[SegmentCriteria09](#SegmentCriteria09)||<a href="LedgerAdvancedRuleStructureConstraintEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureConstraintEntity</a>|
|[SegmentCriteria10](#SegmentCriteria10)||<a href="LedgerAdvancedRuleStructureConstraintEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureConstraintEntity</a>|
|[SegmentCriteria11](#SegmentCriteria11)||<a href="LedgerAdvancedRuleStructureConstraintEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureConstraintEntity</a>|
|[Relationship_LedgerAdvancedRuleStructureEntityRelationshipId](#Relationship_LedgerAdvancedRuleStructureEntityRelationshipId)||<a href="LedgerAdvancedRuleStructureConstraintEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureConstraintEntity</a>|
|[Relationship_LedgerAdvancedRuleStructureActiveOnlyEntityRelationshipId](#Relationship_LedgerAdvancedRuleStructureActiveOnlyEntityRelationshipId)||<a href="LedgerAdvancedRuleStructureConstraintEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureConstraintEntity</a>|
|[Relationship_LedgerAdvancedRuleStructureDraftOnlyEntityRelationshipId](#Relationship_LedgerAdvancedRuleStructureDraftOnlyEntityRelationshipId)||<a href="LedgerAdvancedRuleStructureConstraintEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureConstraintEntity</a>|
|[BackingTable_DimensionHierarchyConstraintCriteriaRelationshipId](#BackingTable_DimensionHierarchyConstraintCriteriaRelationshipId)||<a href="LedgerAdvancedRuleStructureConstraintEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleStructureConstraintEntity</a>|

### <a href=#AdvancedRuleStructure name="AdvancedRuleStructure">AdvancedRuleStructure</a>

First included in: GeneralLedger/LedgerAdvancedRuleStructureConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AdvancedRuleStructure attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActiveFrom name="ActiveFrom">ActiveFrom</a>

First included in: GeneralLedger/LedgerAdvancedRuleStructureConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActiveFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActiveTo name="ActiveTo">ActiveTo</a>

First included in: GeneralLedger/LedgerAdvancedRuleStructureConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActiveTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Position name="Position">Position</a>

First included in: GeneralLedger/LedgerAdvancedRuleStructureConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Position attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DimensionHierarchy name="DimensionHierarchy">DimensionHierarchy</a>

First included in: GeneralLedger/LedgerAdvancedRuleStructureConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionHierarchy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Status name="Status">Status</a>

First included in: GeneralLedger/LedgerAdvancedRuleStructureConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Status attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SegmentCriteria01 name="SegmentCriteria01">SegmentCriteria01</a>

First included in: GeneralLedger/LedgerAdvancedRuleStructureConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Segment criteria 1</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SegmentCriteria01 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Segment criteria 1</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SegmentCriteria02 name="SegmentCriteria02">SegmentCriteria02</a>

First included in: GeneralLedger/LedgerAdvancedRuleStructureConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Segment criteria 2</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SegmentCriteria02 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Segment criteria 2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SegmentCriteria03 name="SegmentCriteria03">SegmentCriteria03</a>

First included in: GeneralLedger/LedgerAdvancedRuleStructureConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Segment criteria 3</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SegmentCriteria03 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Segment criteria 3</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SegmentCriteria04 name="SegmentCriteria04">SegmentCriteria04</a>

First included in: GeneralLedger/LedgerAdvancedRuleStructureConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Segment criteria 4</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SegmentCriteria04 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Segment criteria 4</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SegmentCriteria05 name="SegmentCriteria05">SegmentCriteria05</a>

First included in: GeneralLedger/LedgerAdvancedRuleStructureConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Segment criteria 5</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SegmentCriteria05 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Segment criteria 5</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SegmentCriteria06 name="SegmentCriteria06">SegmentCriteria06</a>

First included in: GeneralLedger/LedgerAdvancedRuleStructureConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Segment criteria 6</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SegmentCriteria06 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Segment criteria 6</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SegmentCriteria07 name="SegmentCriteria07">SegmentCriteria07</a>

First included in: GeneralLedger/LedgerAdvancedRuleStructureConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Segment criteria 7</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SegmentCriteria07 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Segment criteria 7</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SegmentCriteria08 name="SegmentCriteria08">SegmentCriteria08</a>

First included in: GeneralLedger/LedgerAdvancedRuleStructureConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Segment criteria 8</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SegmentCriteria08 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Segment criteria 8</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SegmentCriteria09 name="SegmentCriteria09">SegmentCriteria09</a>

First included in: GeneralLedger/LedgerAdvancedRuleStructureConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Segment criteria 9</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SegmentCriteria09 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Segment criteria 9</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SegmentCriteria10 name="SegmentCriteria10">SegmentCriteria10</a>

First included in: GeneralLedger/LedgerAdvancedRuleStructureConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Segment criteria 10</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SegmentCriteria10 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Segment criteria 10</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SegmentCriteria11 name="SegmentCriteria11">SegmentCriteria11</a>

First included in: GeneralLedger/LedgerAdvancedRuleStructureConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Segment criteria 11</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SegmentCriteria11 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Segment criteria 11</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerAdvancedRuleStructureEntityRelationshipId name="Relationship_LedgerAdvancedRuleStructureEntityRelationshipId">Relationship_LedgerAdvancedRuleStructureEntityRelationshipId</a>

First included in: GeneralLedger/LedgerAdvancedRuleStructureConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerAdvancedRuleStructureEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_LedgerAdvancedRuleStructureActiveOnlyEntityRelationshipId name="Relationship_LedgerAdvancedRuleStructureActiveOnlyEntityRelationshipId">Relationship_LedgerAdvancedRuleStructureActiveOnlyEntityRelationshipId</a>

First included in: GeneralLedger/LedgerAdvancedRuleStructureConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerAdvancedRuleStructureActiveOnlyEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_LedgerAdvancedRuleStructureDraftOnlyEntityRelationshipId name="Relationship_LedgerAdvancedRuleStructureDraftOnlyEntityRelationshipId">Relationship_LedgerAdvancedRuleStructureDraftOnlyEntityRelationshipId</a>

First included in: GeneralLedger/LedgerAdvancedRuleStructureConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerAdvancedRuleStructureDraftOnlyEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_DimensionHierarchyConstraintCriteriaRelationshipId name="BackingTable_DimensionHierarchyConstraintCriteriaRelationshipId">BackingTable_DimensionHierarchyConstraintCriteriaRelationshipId</a>

First included in: GeneralLedger/LedgerAdvancedRuleStructureConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_DimensionHierarchyConstraintCriteriaRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/FinancialDimensions/Miscellaneous/DimensionHierarchyConstraintCriteria.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Miscellaneous/DimensionHierarchyConstraintCriteria.cdm.json/DimensionHierarchyConstraintCriteria</a></td><td><a href="../../../Tables/Finance/FinancialDimensions/Miscellaneous/DimensionHierarchyConstraintCriteria.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
