---
title: HcmPositionForecastBudgetAcctLine - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# HcmPositionForecastBudgetAcctLine

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Budget/Group/HcmPositionForecastBudgetAcctLine.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[HcmPositionForecastBudgetAcctLine/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="HcmPositionForecastBudgetAcctLine.md" target="_blank">Group/HcmPositionForecastBudgetAcctLine</a>|
|[AmountCur](#AmountCur)||<a href="HcmPositionForecastBudgetAcctLine.md" target="_blank">Group/HcmPositionForecastBudgetAcctLine</a>|
|[BudgetAmountCur](#BudgetAmountCur)||<a href="HcmPositionForecastBudgetAcctLine.md" target="_blank">Group/HcmPositionForecastBudgetAcctLine</a>|
|[BudgetPurposeTypeDetail](#BudgetPurposeTypeDetail)||<a href="HcmPositionForecastBudgetAcctLine.md" target="_blank">Group/HcmPositionForecastBudgetAcctLine</a>|
|[EffectiveDate](#EffectiveDate)||<a href="HcmPositionForecastBudgetAcctLine.md" target="_blank">Group/HcmPositionForecastBudgetAcctLine</a>|
|[ExpirationDate](#ExpirationDate)||<a href="HcmPositionForecastBudgetAcctLine.md" target="_blank">Group/HcmPositionForecastBudgetAcctLine</a>|
|[IsLineLockedForRecalculation](#IsLineLockedForRecalculation)||<a href="HcmPositionForecastBudgetAcctLine.md" target="_blank">Group/HcmPositionForecastBudgetAcctLine</a>|
|[isPercentageBased](#isPercentageBased)||<a href="HcmPositionForecastBudgetAcctLine.md" target="_blank">Group/HcmPositionForecastBudgetAcctLine</a>|
|[isPositionLineOverridden](#isPositionLineOverridden)||<a href="HcmPositionForecastBudgetAcctLine.md" target="_blank">Group/HcmPositionForecastBudgetAcctLine</a>|
|[IsSystemGenerated](#IsSystemGenerated)||<a href="HcmPositionForecastBudgetAcctLine.md" target="_blank">Group/HcmPositionForecastBudgetAcctLine</a>|
|[LedgerDimension](#LedgerDimension)||<a href="HcmPositionForecastBudgetAcctLine.md" target="_blank">Group/HcmPositionForecastBudgetAcctLine</a>|
|[LegalEntity](#LegalEntity)||<a href="HcmPositionForecastBudgetAcctLine.md" target="_blank">Group/HcmPositionForecastBudgetAcctLine</a>|
|[PercentageOfDefaultBasisAmount](#PercentageOfDefaultBasisAmount)||<a href="HcmPositionForecastBudgetAcctLine.md" target="_blank">Group/HcmPositionForecastBudgetAcctLine</a>|
|[PositionForecastScenario](#PositionForecastScenario)||<a href="HcmPositionForecastBudgetAcctLine.md" target="_blank">Group/HcmPositionForecastBudgetAcctLine</a>|
|[CostLineSource](#CostLineSource)||<a href="HcmPositionForecastBudgetAcctLine.md" target="_blank">Group/HcmPositionForecastBudgetAcctLine</a>|
|[PositionForecastCompensationGrid](#PositionForecastCompensationGrid)||<a href="HcmPositionForecastBudgetAcctLine.md" target="_blank">Group/HcmPositionForecastBudgetAcctLine</a>|
|[Relationship_CompanyInfoRelationshipId](#Relationship_CompanyInfoRelationshipId)||<a href="HcmPositionForecastBudgetAcctLine.md" target="_blank">Group/HcmPositionForecastBudgetAcctLine</a>|
|[Relationship_HcmBudgetPurposeTypeDetailRelationshipId](#Relationship_HcmBudgetPurposeTypeDetailRelationshipId)||<a href="HcmPositionForecastBudgetAcctLine.md" target="_blank">Group/HcmPositionForecastBudgetAcctLine</a>|
|[Relationship_HcmPositionForecastScenarioRelationshipId](#Relationship_HcmPositionForecastScenarioRelationshipId)||<a href="HcmPositionForecastBudgetAcctLine.md" target="_blank">Group/HcmPositionForecastBudgetAcctLine</a>|
|[Relationship_LedgerDimensionRelationshipId](#Relationship_LedgerDimensionRelationshipId)||<a href="HcmPositionForecastBudgetAcctLine.md" target="_blank">Group/HcmPositionForecastBudgetAcctLine</a>|
|[Relationship_HcmPositionForecastCompensationGridRelationshipId](#Relationship_HcmPositionForecastCompensationGridRelationshipId)||<a href="HcmPositionForecastBudgetAcctLine.md" target="_blank">Group/HcmPositionForecastBudgetAcctLine</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Group/HcmPositionForecastBudgetAcctLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[HcmPositionForecastBudgetAcctLine/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AmountCur name="AmountCur">AmountCur</a>

First included in: Group/HcmPositionForecastBudgetAcctLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountCur attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#BudgetAmountCur name="BudgetAmountCur">BudgetAmountCur</a>

First included in: Group/HcmPositionForecastBudgetAcctLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetAmountCur attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#BudgetPurposeTypeDetail name="BudgetPurposeTypeDetail">BudgetPurposeTypeDetail</a>

First included in: Group/HcmPositionForecastBudgetAcctLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetPurposeTypeDetail attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#EffectiveDate name="EffectiveDate">EffectiveDate</a>

First included in: Group/HcmPositionForecastBudgetAcctLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EffectiveDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#ExpirationDate name="ExpirationDate">ExpirationDate</a>

First included in: Group/HcmPositionForecastBudgetAcctLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpirationDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#IsLineLockedForRecalculation name="IsLineLockedForRecalculation">IsLineLockedForRecalculation</a>

First included in: Group/HcmPositionForecastBudgetAcctLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsLineLockedForRecalculation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#isPercentageBased name="isPercentageBased">isPercentageBased</a>

First included in: Group/HcmPositionForecastBudgetAcctLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the isPercentageBased attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#isPositionLineOverridden name="isPositionLineOverridden">isPositionLineOverridden</a>

First included in: Group/HcmPositionForecastBudgetAcctLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the isPositionLineOverridden attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsSystemGenerated name="IsSystemGenerated">IsSystemGenerated</a>

First included in: Group/HcmPositionForecastBudgetAcctLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSystemGenerated attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LedgerDimension name="LedgerDimension">LedgerDimension</a>

First included in: Group/HcmPositionForecastBudgetAcctLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LegalEntity name="LegalEntity">LegalEntity</a>

First included in: Group/HcmPositionForecastBudgetAcctLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LegalEntity attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PercentageOfDefaultBasisAmount name="PercentageOfDefaultBasisAmount">PercentageOfDefaultBasisAmount</a>

First included in: Group/HcmPositionForecastBudgetAcctLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PercentageOfDefaultBasisAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PositionForecastScenario name="PositionForecastScenario">PositionForecastScenario</a>

First included in: Group/HcmPositionForecastBudgetAcctLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PositionForecastScenario attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CostLineSource name="CostLineSource">CostLineSource</a>

First included in: Group/HcmPositionForecastBudgetAcctLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostLineSource attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PositionForecastCompensationGrid name="PositionForecastCompensationGrid">PositionForecastCompensationGrid</a>

First included in: Group/HcmPositionForecastBudgetAcctLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PositionForecastCompensationGrid attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_CompanyInfoRelationshipId name="Relationship_CompanyInfoRelationshipId">Relationship_CompanyInfoRelationshipId</a>

First included in: Group/HcmPositionForecastBudgetAcctLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CompanyInfoRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_HcmBudgetPurposeTypeDetailRelationshipId name="Relationship_HcmBudgetPurposeTypeDetailRelationshipId">Relationship_HcmBudgetPurposeTypeDetailRelationshipId</a>

First included in: Group/HcmPositionForecastBudgetAcctLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_HcmBudgetPurposeTypeDetailRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="HcmBudgetPurposeTypeDetail.md" target="_blank">/core/operationsCommon/Tables/Finance/Budget/Group/HcmBudgetPurposeTypeDetail.cdm.json/HcmBudgetPurposeTypeDetail</a></td><td><a href="HcmBudgetPurposeTypeDetail.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_HcmPositionForecastScenarioRelationshipId name="Relationship_HcmPositionForecastScenarioRelationshipId">Relationship_HcmPositionForecastScenarioRelationshipId</a>

First included in: Group/HcmPositionForecastBudgetAcctLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_HcmPositionForecastScenarioRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="HcmPositionForecastScenario.md" target="_blank">/core/operationsCommon/Tables/Finance/Budget/Group/HcmPositionForecastScenario.cdm.json/HcmPositionForecastScenario</a></td><td><a href="HcmPositionForecastScenario.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerDimensionRelationshipId name="Relationship_LedgerDimensionRelationshipId">Relationship_LedgerDimensionRelationshipId</a>

First included in: Group/HcmPositionForecastBudgetAcctLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_HcmPositionForecastCompensationGridRelationshipId name="Relationship_HcmPositionForecastCompensationGridRelationshipId">Relationship_HcmPositionForecastCompensationGridRelationshipId</a>

First included in: Group/HcmPositionForecastBudgetAcctLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_HcmPositionForecastCompensationGridRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Reference/HcmPositionForecastCompensationGrid.md" target="_blank">/core/operationsCommon/Tables/Finance/Budget/Reference/HcmPositionForecastCompensationGrid.cdm.json/HcmPositionForecastCompensationGrid</a></td><td><a href="../Reference/HcmPositionForecastCompensationGrid.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
