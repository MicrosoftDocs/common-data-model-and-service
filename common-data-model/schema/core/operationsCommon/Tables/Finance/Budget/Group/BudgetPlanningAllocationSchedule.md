---
title: BudgetPlanningAllocationSchedule - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# BudgetPlanningAllocationSchedule

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Budget/Group/BudgetPlanningAllocationSchedule.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BudgetPlanningAllocationSchedule/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="BudgetPlanningAllocationSchedule.md" target="_blank">Group/BudgetPlanningAllocationSchedule</a>|
|[AllocationMethod](#AllocationMethod)||<a href="BudgetPlanningAllocationSchedule.md" target="_blank">Group/BudgetPlanningAllocationSchedule</a>|
|[AllocationTerm](#AllocationTerm)||<a href="BudgetPlanningAllocationSchedule.md" target="_blank">Group/BudgetPlanningAllocationSchedule</a>|
|[BasisPlanScenario](#BasisPlanScenario)||<a href="BudgetPlanningAllocationSchedule.md" target="_blank">Group/BudgetPlanningAllocationSchedule</a>|
|[DestinationPlanScenario](#DestinationPlanScenario)||<a href="BudgetPlanningAllocationSchedule.md" target="_blank">Group/BudgetPlanningAllocationSchedule</a>|
|[Factor](#Factor)||<a href="BudgetPlanningAllocationSchedule.md" target="_blank">Group/BudgetPlanningAllocationSchedule</a>|
|[Ledger](#Ledger)||<a href="BudgetPlanningAllocationSchedule.md" target="_blank">Group/BudgetPlanningAllocationSchedule</a>|
|[LedgerAllocationKey](#LedgerAllocationKey)||<a href="BudgetPlanningAllocationSchedule.md" target="_blank">Group/BudgetPlanningAllocationSchedule</a>|
|[LedgerAllocationKeyDataAreaId](#LedgerAllocationKeyDataAreaId)||<a href="BudgetPlanningAllocationSchedule.md" target="_blank">Group/BudgetPlanningAllocationSchedule</a>|
|[LedgerAllocationRule](#LedgerAllocationRule)||<a href="BudgetPlanningAllocationSchedule.md" target="_blank">Group/BudgetPlanningAllocationSchedule</a>|
|[LedgerAllocationRuleDataAreaId](#LedgerAllocationRuleDataAreaId)||<a href="BudgetPlanningAllocationSchedule.md" target="_blank">Group/BudgetPlanningAllocationSchedule</a>|
|[Name](#Name)||<a href="BudgetPlanningAllocationSchedule.md" target="_blank">Group/BudgetPlanningAllocationSchedule</a>|
|[SourcePlanScenario](#SourcePlanScenario)||<a href="BudgetPlanningAllocationSchedule.md" target="_blank">Group/BudgetPlanningAllocationSchedule</a>|
|[UseSourceEffectiveDate](#UseSourceEffectiveDate)||<a href="BudgetPlanningAllocationSchedule.md" target="_blank">Group/BudgetPlanningAllocationSchedule</a>|
|[AncestorLevel](#AncestorLevel)||<a href="BudgetPlanningAllocationSchedule.md" target="_blank">Group/BudgetPlanningAllocationSchedule</a>|
|[AppendLines](#AppendLines)||<a href="BudgetPlanningAllocationSchedule.md" target="_blank">Group/BudgetPlanningAllocationSchedule</a>|
|[Relationship_BasisPlanScenarioRelationshipId](#Relationship_BasisPlanScenarioRelationshipId)||<a href="BudgetPlanningAllocationSchedule.md" target="_blank">Group/BudgetPlanningAllocationSchedule</a>|
|[Relationship_BudgetAllocationTermRelationshipId](#Relationship_BudgetAllocationTermRelationshipId)||<a href="BudgetPlanningAllocationSchedule.md" target="_blank">Group/BudgetPlanningAllocationSchedule</a>|
|[Relationship_DestinationPlanScenarioRelationshipId](#Relationship_DestinationPlanScenarioRelationshipId)||<a href="BudgetPlanningAllocationSchedule.md" target="_blank">Group/BudgetPlanningAllocationSchedule</a>|
|[Relationship_LedgerRelationshipId](#Relationship_LedgerRelationshipId)||<a href="BudgetPlanningAllocationSchedule.md" target="_blank">Group/BudgetPlanningAllocationSchedule</a>|
|[Relationship_LedgerAllocateKeyRelationshipId](#Relationship_LedgerAllocateKeyRelationshipId)||<a href="BudgetPlanningAllocationSchedule.md" target="_blank">Group/BudgetPlanningAllocationSchedule</a>|
|[Relationship_LedgerAllocationRuleRelationshipId](#Relationship_LedgerAllocationRuleRelationshipId)||<a href="BudgetPlanningAllocationSchedule.md" target="_blank">Group/BudgetPlanningAllocationSchedule</a>|
|[Relationship_SourcePlanScenarioRelationshipId](#Relationship_SourcePlanScenarioRelationshipId)||<a href="BudgetPlanningAllocationSchedule.md" target="_blank">Group/BudgetPlanningAllocationSchedule</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Group/BudgetPlanningAllocationSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BudgetPlanningAllocationSchedule/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AllocationMethod name="AllocationMethod">AllocationMethod</a>

First included in: Group/BudgetPlanningAllocationSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllocationMethod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AllocationTerm name="AllocationTerm">AllocationTerm</a>

First included in: Group/BudgetPlanningAllocationSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllocationTerm attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BasisPlanScenario name="BasisPlanScenario">BasisPlanScenario</a>

First included in: Group/BudgetPlanningAllocationSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BasisPlanScenario attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DestinationPlanScenario name="DestinationPlanScenario">DestinationPlanScenario</a>

First included in: Group/BudgetPlanningAllocationSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationPlanScenario attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Factor name="Factor">Factor</a>

First included in: Group/BudgetPlanningAllocationSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Factor attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Ledger name="Ledger">Ledger</a>

First included in: Group/BudgetPlanningAllocationSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Ledger attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LedgerAllocationKey name="LedgerAllocationKey">LedgerAllocationKey</a>

First included in: Group/BudgetPlanningAllocationSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerAllocationKey attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerAllocationKeyDataAreaId name="LedgerAllocationKeyDataAreaId">LedgerAllocationKeyDataAreaId</a>

First included in: Group/BudgetPlanningAllocationSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerAllocationKeyDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerAllocationRule name="LedgerAllocationRule">LedgerAllocationRule</a>

First included in: Group/BudgetPlanningAllocationSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerAllocationRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerAllocationRuleDataAreaId name="LedgerAllocationRuleDataAreaId">LedgerAllocationRuleDataAreaId</a>

First included in: Group/BudgetPlanningAllocationSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerAllocationRuleDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: Group/BudgetPlanningAllocationSchedule (this entity)  

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

### <a href=#SourcePlanScenario name="SourcePlanScenario">SourcePlanScenario</a>

First included in: Group/BudgetPlanningAllocationSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourcePlanScenario attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#UseSourceEffectiveDate name="UseSourceEffectiveDate">UseSourceEffectiveDate</a>

First included in: Group/BudgetPlanningAllocationSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseSourceEffectiveDate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AncestorLevel name="AncestorLevel">AncestorLevel</a>

First included in: Group/BudgetPlanningAllocationSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AncestorLevel attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AppendLines name="AppendLines">AppendLines</a>

First included in: Group/BudgetPlanningAllocationSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AppendLines attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Relationship_BasisPlanScenarioRelationshipId name="Relationship_BasisPlanScenarioRelationshipId">Relationship_BasisPlanScenarioRelationshipId</a>

First included in: Group/BudgetPlanningAllocationSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BasisPlanScenarioRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="BudgetPlanScenario.md" target="_blank">/core/operationsCommon/Tables/Finance/Budget/Group/BudgetPlanScenario.cdm.json/BudgetPlanScenario</a></td><td><a href="BudgetPlanScenario.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BudgetAllocationTermRelationshipId name="Relationship_BudgetAllocationTermRelationshipId">Relationship_BudgetAllocationTermRelationshipId</a>

First included in: Group/BudgetPlanningAllocationSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BudgetAllocationTermRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="BudgetAllocationTerm.md" target="_blank">/core/operationsCommon/Tables/Finance/Budget/Group/BudgetAllocationTerm.cdm.json/BudgetAllocationTerm</a></td><td><a href="BudgetAllocationTerm.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DestinationPlanScenarioRelationshipId name="Relationship_DestinationPlanScenarioRelationshipId">Relationship_DestinationPlanScenarioRelationshipId</a>

First included in: Group/BudgetPlanningAllocationSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DestinationPlanScenarioRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="BudgetPlanScenario.md" target="_blank">/core/operationsCommon/Tables/Finance/Budget/Group/BudgetPlanScenario.cdm.json/BudgetPlanScenario</a></td><td><a href="BudgetPlanScenario.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerRelationshipId name="Relationship_LedgerRelationshipId">Relationship_LedgerRelationshipId</a>

First included in: Group/BudgetPlanningAllocationSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Ledger/Main/Ledger.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/Ledger.cdm.json/Ledger</a></td><td><a href="../../Ledger/Main/Ledger.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerAllocateKeyRelationshipId name="Relationship_LedgerAllocateKeyRelationshipId">Relationship_LedgerAllocateKeyRelationshipId</a>

First included in: Group/BudgetPlanningAllocationSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerAllocateKeyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Ledger/Group/LedgerAllocateKey.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Group/LedgerAllocateKey.cdm.json/LedgerAllocateKey</a></td><td><a href="../../Ledger/Group/LedgerAllocateKey.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerAllocationRuleRelationshipId name="Relationship_LedgerAllocationRuleRelationshipId">Relationship_LedgerAllocationRuleRelationshipId</a>

First included in: Group/BudgetPlanningAllocationSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerAllocationRuleRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Ledger/Main/LedgerAllocationRule.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/LedgerAllocationRule.cdm.json/LedgerAllocationRule</a></td><td><a href="../../Ledger/Main/LedgerAllocationRule.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SourcePlanScenarioRelationshipId name="Relationship_SourcePlanScenarioRelationshipId">Relationship_SourcePlanScenarioRelationshipId</a>

First included in: Group/BudgetPlanningAllocationSchedule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SourcePlanScenarioRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="BudgetPlanScenario.md" target="_blank">/core/operationsCommon/Tables/Finance/Budget/Group/BudgetPlanScenario.cdm.json/BudgetPlanScenario</a></td><td><a href="BudgetPlanScenario.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
