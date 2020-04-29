---
title: LedgerAccountStructureConstraintEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# Account structure allowed values

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/GeneralLedger/LedgerAccountStructureConstraintEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Account structure allowed values</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AccountStructure](#AccountStructure)||<a href="LedgerAccountStructureConstraintEntity.md" target="_blank">GeneralLedger/LedgerAccountStructureConstraintEntity</a>|
|[ActiveFrom](#ActiveFrom)||<a href="LedgerAccountStructureConstraintEntity.md" target="_blank">GeneralLedger/LedgerAccountStructureConstraintEntity</a>|
|[ActiveTo](#ActiveTo)||<a href="LedgerAccountStructureConstraintEntity.md" target="_blank">GeneralLedger/LedgerAccountStructureConstraintEntity</a>|
|[Position](#Position)||<a href="LedgerAccountStructureConstraintEntity.md" target="_blank">GeneralLedger/LedgerAccountStructureConstraintEntity</a>|
|[DimensionHierarchy](#DimensionHierarchy)||<a href="LedgerAccountStructureConstraintEntity.md" target="_blank">GeneralLedger/LedgerAccountStructureConstraintEntity</a>|
|[Status](#Status)||<a href="LedgerAccountStructureConstraintEntity.md" target="_blank">GeneralLedger/LedgerAccountStructureConstraintEntity</a>|
|[SegmentCriteria01](#SegmentCriteria01)||<a href="LedgerAccountStructureConstraintEntity.md" target="_blank">GeneralLedger/LedgerAccountStructureConstraintEntity</a>|
|[SegmentCriteria02](#SegmentCriteria02)||<a href="LedgerAccountStructureConstraintEntity.md" target="_blank">GeneralLedger/LedgerAccountStructureConstraintEntity</a>|
|[SegmentCriteria03](#SegmentCriteria03)||<a href="LedgerAccountStructureConstraintEntity.md" target="_blank">GeneralLedger/LedgerAccountStructureConstraintEntity</a>|
|[SegmentCriteria04](#SegmentCriteria04)||<a href="LedgerAccountStructureConstraintEntity.md" target="_blank">GeneralLedger/LedgerAccountStructureConstraintEntity</a>|
|[SegmentCriteria05](#SegmentCriteria05)||<a href="LedgerAccountStructureConstraintEntity.md" target="_blank">GeneralLedger/LedgerAccountStructureConstraintEntity</a>|
|[SegmentCriteria06](#SegmentCriteria06)||<a href="LedgerAccountStructureConstraintEntity.md" target="_blank">GeneralLedger/LedgerAccountStructureConstraintEntity</a>|
|[SegmentCriteria07](#SegmentCriteria07)||<a href="LedgerAccountStructureConstraintEntity.md" target="_blank">GeneralLedger/LedgerAccountStructureConstraintEntity</a>|
|[SegmentCriteria08](#SegmentCriteria08)||<a href="LedgerAccountStructureConstraintEntity.md" target="_blank">GeneralLedger/LedgerAccountStructureConstraintEntity</a>|
|[SegmentCriteria09](#SegmentCriteria09)||<a href="LedgerAccountStructureConstraintEntity.md" target="_blank">GeneralLedger/LedgerAccountStructureConstraintEntity</a>|
|[SegmentCriteria10](#SegmentCriteria10)||<a href="LedgerAccountStructureConstraintEntity.md" target="_blank">GeneralLedger/LedgerAccountStructureConstraintEntity</a>|
|[SegmentCriteria11](#SegmentCriteria11)||<a href="LedgerAccountStructureConstraintEntity.md" target="_blank">GeneralLedger/LedgerAccountStructureConstraintEntity</a>|
|[Relationship_LedgerAccountStructureEntityRelationshipId](#Relationship_LedgerAccountStructureEntityRelationshipId)||<a href="LedgerAccountStructureConstraintEntity.md" target="_blank">GeneralLedger/LedgerAccountStructureConstraintEntity</a>|
|[Relationship_LedgerAccountStructureActiveOnlyEntityRelationshipId](#Relationship_LedgerAccountStructureActiveOnlyEntityRelationshipId)||<a href="LedgerAccountStructureConstraintEntity.md" target="_blank">GeneralLedger/LedgerAccountStructureConstraintEntity</a>|
|[Relationship_LedgerAccountStructureDraftOnlyEntityRelationshipId](#Relationship_LedgerAccountStructureDraftOnlyEntityRelationshipId)||<a href="LedgerAccountStructureConstraintEntity.md" target="_blank">GeneralLedger/LedgerAccountStructureConstraintEntity</a>|
|[BackingTable_DimensionHierarchyConstraintCriteriaRelationshipId](#BackingTable_DimensionHierarchyConstraintCriteriaRelationshipId)||<a href="LedgerAccountStructureConstraintEntity.md" target="_blank">GeneralLedger/LedgerAccountStructureConstraintEntity</a>|

### <a href=#AccountStructure name="AccountStructure">AccountStructure</a>

First included in: GeneralLedger/LedgerAccountStructureConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountStructure attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActiveFrom name="ActiveFrom">ActiveFrom</a>

First included in: GeneralLedger/LedgerAccountStructureConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActiveFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActiveTo name="ActiveTo">ActiveTo</a>

First included in: GeneralLedger/LedgerAccountStructureConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActiveTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Position name="Position">Position</a>

First included in: GeneralLedger/LedgerAccountStructureConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Position attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DimensionHierarchy name="DimensionHierarchy">DimensionHierarchy</a>

First included in: GeneralLedger/LedgerAccountStructureConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionHierarchy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Status name="Status">Status</a>

First included in: GeneralLedger/LedgerAccountStructureConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Status attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SegmentCriteria01 name="SegmentCriteria01">SegmentCriteria01</a>

First included in: GeneralLedger/LedgerAccountStructureConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Segment criteria 1</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SegmentCriteria01 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Segment criteria 1</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SegmentCriteria02 name="SegmentCriteria02">SegmentCriteria02</a>

First included in: GeneralLedger/LedgerAccountStructureConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Segment criteria 2</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SegmentCriteria02 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Segment criteria 2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SegmentCriteria03 name="SegmentCriteria03">SegmentCriteria03</a>

First included in: GeneralLedger/LedgerAccountStructureConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Segment criteria 3</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SegmentCriteria03 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Segment criteria 3</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SegmentCriteria04 name="SegmentCriteria04">SegmentCriteria04</a>

First included in: GeneralLedger/LedgerAccountStructureConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Segment criteria 4</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SegmentCriteria04 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Segment criteria 4</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SegmentCriteria05 name="SegmentCriteria05">SegmentCriteria05</a>

First included in: GeneralLedger/LedgerAccountStructureConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Segment criteria 5</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SegmentCriteria05 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Segment criteria 5</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SegmentCriteria06 name="SegmentCriteria06">SegmentCriteria06</a>

First included in: GeneralLedger/LedgerAccountStructureConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Segment criteria 6</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SegmentCriteria06 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Segment criteria 6</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SegmentCriteria07 name="SegmentCriteria07">SegmentCriteria07</a>

First included in: GeneralLedger/LedgerAccountStructureConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Segment criteria 7</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SegmentCriteria07 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Segment criteria 7</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SegmentCriteria08 name="SegmentCriteria08">SegmentCriteria08</a>

First included in: GeneralLedger/LedgerAccountStructureConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Segment criteria 8</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SegmentCriteria08 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Segment criteria 8</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SegmentCriteria09 name="SegmentCriteria09">SegmentCriteria09</a>

First included in: GeneralLedger/LedgerAccountStructureConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Segment criteria 9</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SegmentCriteria09 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Segment criteria 9</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SegmentCriteria10 name="SegmentCriteria10">SegmentCriteria10</a>

First included in: GeneralLedger/LedgerAccountStructureConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Segment criteria 10</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SegmentCriteria10 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Segment criteria 10</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SegmentCriteria11 name="SegmentCriteria11">SegmentCriteria11</a>

First included in: GeneralLedger/LedgerAccountStructureConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Segment criteria 11</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SegmentCriteria11 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Segment criteria 11</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerAccountStructureEntityRelationshipId name="Relationship_LedgerAccountStructureEntityRelationshipId">Relationship_LedgerAccountStructureEntityRelationshipId</a>

First included in: GeneralLedger/LedgerAccountStructureConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerAccountStructureEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_LedgerAccountStructureActiveOnlyEntityRelationshipId name="Relationship_LedgerAccountStructureActiveOnlyEntityRelationshipId">Relationship_LedgerAccountStructureActiveOnlyEntityRelationshipId</a>

First included in: GeneralLedger/LedgerAccountStructureConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerAccountStructureActiveOnlyEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_LedgerAccountStructureDraftOnlyEntityRelationshipId name="Relationship_LedgerAccountStructureDraftOnlyEntityRelationshipId">Relationship_LedgerAccountStructureDraftOnlyEntityRelationshipId</a>

First included in: GeneralLedger/LedgerAccountStructureConstraintEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerAccountStructureDraftOnlyEntityRelationshipId attribute are listed below.</summary>

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

First included in: GeneralLedger/LedgerAccountStructureConstraintEntity (this entity)  

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
