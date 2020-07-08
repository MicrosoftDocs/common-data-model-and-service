---
title: LedgerAdvancedRuleEntity in GeneralLedger - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/8/2020
ms.author: nebanfic
---

# Advanced rules in GeneralLedger(LedgerAdvancedRuleEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/GeneralLedger/LedgerAdvancedRuleEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Advanced rules</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AccountStructure](#AccountStructure)||<a href="LedgerAdvancedRuleEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleEntity</a>|
|[AdvancedRuleName](#AdvancedRuleName)||<a href="LedgerAdvancedRuleEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleEntity</a>|
|[Status](#Status)||<a href="LedgerAdvancedRuleEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleEntity</a>|
|[Description](#Description)||<a href="LedgerAdvancedRuleEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleEntity</a>|
|[RuleType](#RuleType)||<a href="LedgerAdvancedRuleEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleEntity</a>|
|[AdvancedRuleStructure1](#AdvancedRuleStructure1)||<a href="LedgerAdvancedRuleEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleEntity</a>|
|[AdvancedRuleStructure2](#AdvancedRuleStructure2)||<a href="LedgerAdvancedRuleEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleEntity</a>|
|[AdvancedRuleStructure3](#AdvancedRuleStructure3)||<a href="LedgerAdvancedRuleEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleEntity</a>|
|[AdvancedRuleStructure4](#AdvancedRuleStructure4)||<a href="LedgerAdvancedRuleEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleEntity</a>|
|[Relationship_LedgerAccountStructureEntityRelationshipId](#Relationship_LedgerAccountStructureEntityRelationshipId)||<a href="LedgerAdvancedRuleEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleEntity</a>|
|[Relationship_LedgerAdvancedRuleStructureEntity1RelationshipId](#Relationship_LedgerAdvancedRuleStructureEntity1RelationshipId)||<a href="LedgerAdvancedRuleEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleEntity</a>|
|[Relationship_LedgerAdvancedRuleStructureEntity2RelationshipId](#Relationship_LedgerAdvancedRuleStructureEntity2RelationshipId)||<a href="LedgerAdvancedRuleEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleEntity</a>|
|[Relationship_LedgerAdvancedRuleStructureEntity3RelationshipId](#Relationship_LedgerAdvancedRuleStructureEntity3RelationshipId)||<a href="LedgerAdvancedRuleEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleEntity</a>|
|[Relationship_LedgerAdvancedRuleStructureEntity4RelationshipId](#Relationship_LedgerAdvancedRuleStructureEntity4RelationshipId)||<a href="LedgerAdvancedRuleEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleEntity</a>|
|[Relationship_LedgerAccountStructureActiveOnlyEntityRelationshipId](#Relationship_LedgerAccountStructureActiveOnlyEntityRelationshipId)||<a href="LedgerAdvancedRuleEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleEntity</a>|
|[Relationship_LedgerAccountStructureDraftOnlyEntityRelationshipId](#Relationship_LedgerAccountStructureDraftOnlyEntityRelationshipId)||<a href="LedgerAdvancedRuleEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleEntity</a>|
|[Relationship_LedgerAdvancedRuleCriterionEntityRelationshipId](#Relationship_LedgerAdvancedRuleCriterionEntityRelationshipId)||<a href="LedgerAdvancedRuleEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleEntity</a>|
|[BackingTable_DimensionRuleRelationshipId](#BackingTable_DimensionRuleRelationshipId)||<a href="LedgerAdvancedRuleEntity.md" target="_blank">GeneralLedger/LedgerAdvancedRuleEntity</a>|

### <a href=#AccountStructure name="AccountStructure">AccountStructure</a>

First included in: GeneralLedger/LedgerAdvancedRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Account structure</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountStructure attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Account structure</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AdvancedRuleName name="AdvancedRuleName">AdvancedRuleName</a>

First included in: GeneralLedger/LedgerAdvancedRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AdvancedRuleName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Status name="Status">Status</a>

First included in: GeneralLedger/LedgerAdvancedRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Status attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Status</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: GeneralLedger/LedgerAdvancedRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RuleType name="RuleType">RuleType</a>

First included in: GeneralLedger/LedgerAdvancedRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RuleType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AdvancedRuleStructure1 name="AdvancedRuleStructure1">AdvancedRuleStructure1</a>

First included in: GeneralLedger/LedgerAdvancedRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Advanced rule hierarchy 1</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AdvancedRuleStructure1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Advanced rule hierarchy 1</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AdvancedRuleStructure2 name="AdvancedRuleStructure2">AdvancedRuleStructure2</a>

First included in: GeneralLedger/LedgerAdvancedRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Advanced rule hierarchy 2</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AdvancedRuleStructure2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Advanced rule hierarchy 2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AdvancedRuleStructure3 name="AdvancedRuleStructure3">AdvancedRuleStructure3</a>

First included in: GeneralLedger/LedgerAdvancedRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Advanced rule hierarchy 3</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AdvancedRuleStructure3 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Advanced rule hierarchy 3</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AdvancedRuleStructure4 name="AdvancedRuleStructure4">AdvancedRuleStructure4</a>

First included in: GeneralLedger/LedgerAdvancedRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Advanced rule hierarchy 4</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AdvancedRuleStructure4 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Advanced rule hierarchy 4</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerAccountStructureEntityRelationshipId name="Relationship_LedgerAccountStructureEntityRelationshipId">Relationship_LedgerAccountStructureEntityRelationshipId</a>

First included in: GeneralLedger/LedgerAdvancedRuleEntity (this entity)  

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

### <a href=#Relationship_LedgerAdvancedRuleStructureEntity1RelationshipId name="Relationship_LedgerAdvancedRuleStructureEntity1RelationshipId">Relationship_LedgerAdvancedRuleStructureEntity1RelationshipId</a>

First included in: GeneralLedger/LedgerAdvancedRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerAdvancedRuleStructureEntity1RelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_LedgerAdvancedRuleStructureEntity2RelationshipId name="Relationship_LedgerAdvancedRuleStructureEntity2RelationshipId">Relationship_LedgerAdvancedRuleStructureEntity2RelationshipId</a>

First included in: GeneralLedger/LedgerAdvancedRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerAdvancedRuleStructureEntity2RelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_LedgerAdvancedRuleStructureEntity3RelationshipId name="Relationship_LedgerAdvancedRuleStructureEntity3RelationshipId">Relationship_LedgerAdvancedRuleStructureEntity3RelationshipId</a>

First included in: GeneralLedger/LedgerAdvancedRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerAdvancedRuleStructureEntity3RelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_LedgerAdvancedRuleStructureEntity4RelationshipId name="Relationship_LedgerAdvancedRuleStructureEntity4RelationshipId">Relationship_LedgerAdvancedRuleStructureEntity4RelationshipId</a>

First included in: GeneralLedger/LedgerAdvancedRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerAdvancedRuleStructureEntity4RelationshipId attribute are listed below.</summary>

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

First included in: GeneralLedger/LedgerAdvancedRuleEntity (this entity)  

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

First included in: GeneralLedger/LedgerAdvancedRuleEntity (this entity)  

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

### <a href=#Relationship_LedgerAdvancedRuleCriterionEntityRelationshipId name="Relationship_LedgerAdvancedRuleCriterionEntityRelationshipId">Relationship_LedgerAdvancedRuleCriterionEntityRelationshipId</a>

First included in: GeneralLedger/LedgerAdvancedRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerAdvancedRuleCriterionEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_DimensionRuleRelationshipId name="BackingTable_DimensionRuleRelationshipId">BackingTable_DimensionRuleRelationshipId</a>

First included in: GeneralLedger/LedgerAdvancedRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_DimensionRuleRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/FinancialDimensions/Group/DimensionRule.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Group/DimensionRule.cdm.json/DimensionRule</a></td><td><a href="../../../Tables/Finance/FinancialDimensions/Group/DimensionRule.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
