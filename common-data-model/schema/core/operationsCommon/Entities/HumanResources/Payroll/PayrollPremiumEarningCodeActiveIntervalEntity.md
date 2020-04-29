---
title: PayrollPremiumEarningCodeActiveIntervalEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# Premium code active interval

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/HumanResources/Payroll/PayrollPremiumEarningCodeActiveIntervalEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Premium code active interval</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[PremiumEarningCode](#PremiumEarningCode)||<a href="PayrollPremiumEarningCodeActiveIntervalEntity.md" target="_blank">Payroll/PayrollPremiumEarningCodeActiveIntervalEntity</a>|
|[ValidFrom](#ValidFrom)||<a href="PayrollPremiumEarningCodeActiveIntervalEntity.md" target="_blank">Payroll/PayrollPremiumEarningCodeActiveIntervalEntity</a>|
|[ValidTo](#ValidTo)||<a href="PayrollPremiumEarningCodeActiveIntervalEntity.md" target="_blank">Payroll/PayrollPremiumEarningCodeActiveIntervalEntity</a>|
|[PremiumEarningCodeId](#PremiumEarningCodeId)||<a href="PayrollPremiumEarningCodeActiveIntervalEntity.md" target="_blank">Payroll/PayrollPremiumEarningCodeActiveIntervalEntity</a>|
|[Relationship_PremiumEarningCodeRelationshipId](#Relationship_PremiumEarningCodeRelationshipId)||<a href="PayrollPremiumEarningCodeActiveIntervalEntity.md" target="_blank">Payroll/PayrollPremiumEarningCodeActiveIntervalEntity</a>|
|[BackingTable_PayrollPremiumEarningCodeActiveIntervalRelationshipId](#BackingTable_PayrollPremiumEarningCodeActiveIntervalRelationshipId)||<a href="PayrollPremiumEarningCodeActiveIntervalEntity.md" target="_blank">Payroll/PayrollPremiumEarningCodeActiveIntervalEntity</a>|

### <a href=#PremiumEarningCode name="PremiumEarningCode">PremiumEarningCode</a>

First included in: Payroll/PayrollPremiumEarningCodeActiveIntervalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PremiumEarningCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidFrom name="ValidFrom">ValidFrom</a>

First included in: Payroll/PayrollPremiumEarningCodeActiveIntervalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidTo name="ValidTo">ValidTo</a>

First included in: Payroll/PayrollPremiumEarningCodeActiveIntervalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PremiumEarningCodeId name="PremiumEarningCodeId">PremiumEarningCodeId</a>

First included in: Payroll/PayrollPremiumEarningCodeActiveIntervalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PremiumEarningCodeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PremiumEarningCodeRelationshipId name="Relationship_PremiumEarningCodeRelationshipId">Relationship_PremiumEarningCodeRelationshipId</a>

First included in: Payroll/PayrollPremiumEarningCodeActiveIntervalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PremiumEarningCodeRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_PayrollPremiumEarningCodeActiveIntervalRelationshipId name="BackingTable_PayrollPremiumEarningCodeActiveIntervalRelationshipId">BackingTable_PayrollPremiumEarningCodeActiveIntervalRelationshipId</a>

First included in: Payroll/PayrollPremiumEarningCodeActiveIntervalEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PayrollPremiumEarningCodeActiveIntervalRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/HumanResources/Payroll/Reference/PayrollPremiumEarningCodeActiveInterval.md" target="_blank">/core/operationsCommon/Tables/HumanResources/Payroll/Reference/PayrollPremiumEarningCodeActiveInterval.cdm.json/PayrollPremiumEarningCodeActiveInterval</a></td><td><a href="../../../Tables/HumanResources/Payroll/Reference/PayrollPremiumEarningCodeActiveInterval.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
