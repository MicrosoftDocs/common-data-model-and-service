---
title: ForecastModelEntity in MasterPlanning - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Forecast models in MasterPlanning(ForecastModelEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/MasterPlanning/ForecastModelEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Forecast models</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ModelId](#ModelId)||<a href="ForecastModelEntity.md" target="_blank">MasterPlanning/ForecastModelEntity</a>|
|[ModelName](#ModelName)||<a href="ForecastModelEntity.md" target="_blank">MasterPlanning/ForecastModelEntity</a>|
|[IsModelStopped](#IsModelStopped)||<a href="ForecastModelEntity.md" target="_blank">MasterPlanning/ForecastModelEntity</a>|
|[IsCashFlowForecastGenerated](#IsCashFlowForecastGenerated)||<a href="ForecastModelEntity.md" target="_blank">MasterPlanning/ForecastModelEntity</a>|
|[BudgetControlType](#BudgetControlType)||<a href="ForecastModelEntity.md" target="_blank">MasterPlanning/ForecastModelEntity</a>|
|[AreSufficientProjectExpenseFundsRequired](#AreSufficientProjectExpenseFundsRequired)||<a href="ForecastModelEntity.md" target="_blank">MasterPlanning/ForecastModelEntity</a>|
|[AreSufficientProjectHourFundsRequired](#AreSufficientProjectHourFundsRequired)||<a href="ForecastModelEntity.md" target="_blank">MasterPlanning/ForecastModelEntity</a>|
|[AreSufficientProjectItemFundsRequired](#AreSufficientProjectItemFundsRequired)||<a href="ForecastModelEntity.md" target="_blank">MasterPlanning/ForecastModelEntity</a>|
|[IsProjectExpenseForecastAutomaticallyReduced](#IsProjectExpenseForecastAutomaticallyReduced)||<a href="ForecastModelEntity.md" target="_blank">MasterPlanning/ForecastModelEntity</a>|
|[IsFixedPriceProjectWIPIncluded](#IsFixedPriceProjectWIPIncluded)||<a href="ForecastModelEntity.md" target="_blank">MasterPlanning/ForecastModelEntity</a>|
|[IsInvestmentProjectWIPIncluded](#IsInvestmentProjectWIPIncluded)||<a href="ForecastModelEntity.md" target="_blank">MasterPlanning/ForecastModelEntity</a>|
|[IsTimeAndMaterialProjectIncluded](#IsTimeAndMaterialProjectIncluded)||<a href="ForecastModelEntity.md" target="_blank">MasterPlanning/ForecastModelEntity</a>|
|[IsProjectHourForecastAutomaticallyReduced](#IsProjectHourForecastAutomaticallyReduced)||<a href="ForecastModelEntity.md" target="_blank">MasterPlanning/ForecastModelEntity</a>|
|[IsProjectItemForecastAutomaticallyReduced](#IsProjectItemForecastAutomaticallyReduced)||<a href="ForecastModelEntity.md" target="_blank">MasterPlanning/ForecastModelEntity</a>|
|[WillProjectForecastGenerationUseProjectDate](#WillProjectForecastGenerationUseProjectDate)||<a href="ForecastModelEntity.md" target="_blank">MasterPlanning/ForecastModelEntity</a>|
|[BackingTable_ForecastModelRelationshipId](#BackingTable_ForecastModelRelationshipId)||<a href="ForecastModelEntity.md" target="_blank">MasterPlanning/ForecastModelEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="ForecastModelEntity.md" target="_blank">MasterPlanning/ForecastModelEntity</a>|

### <a href=#ModelId name="ModelId">ModelId</a>

First included in: MasterPlanning/ForecastModelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ModelId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ModelName name="ModelName">ModelName</a>

First included in: MasterPlanning/ForecastModelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ModelName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsModelStopped name="IsModelStopped">IsModelStopped</a>

First included in: MasterPlanning/ForecastModelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsModelStopped attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCashFlowForecastGenerated name="IsCashFlowForecastGenerated">IsCashFlowForecastGenerated</a>

First included in: MasterPlanning/ForecastModelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCashFlowForecastGenerated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BudgetControlType name="BudgetControlType">BudgetControlType</a>

First included in: MasterPlanning/ForecastModelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetControlType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreSufficientProjectExpenseFundsRequired name="AreSufficientProjectExpenseFundsRequired">AreSufficientProjectExpenseFundsRequired</a>

First included in: MasterPlanning/ForecastModelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreSufficientProjectExpenseFundsRequired attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreSufficientProjectHourFundsRequired name="AreSufficientProjectHourFundsRequired">AreSufficientProjectHourFundsRequired</a>

First included in: MasterPlanning/ForecastModelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreSufficientProjectHourFundsRequired attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreSufficientProjectItemFundsRequired name="AreSufficientProjectItemFundsRequired">AreSufficientProjectItemFundsRequired</a>

First included in: MasterPlanning/ForecastModelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreSufficientProjectItemFundsRequired attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProjectExpenseForecastAutomaticallyReduced name="IsProjectExpenseForecastAutomaticallyReduced">IsProjectExpenseForecastAutomaticallyReduced</a>

First included in: MasterPlanning/ForecastModelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProjectExpenseForecastAutomaticallyReduced attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsFixedPriceProjectWIPIncluded name="IsFixedPriceProjectWIPIncluded">IsFixedPriceProjectWIPIncluded</a>

First included in: MasterPlanning/ForecastModelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsFixedPriceProjectWIPIncluded attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsInvestmentProjectWIPIncluded name="IsInvestmentProjectWIPIncluded">IsInvestmentProjectWIPIncluded</a>

First included in: MasterPlanning/ForecastModelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsInvestmentProjectWIPIncluded attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsTimeAndMaterialProjectIncluded name="IsTimeAndMaterialProjectIncluded">IsTimeAndMaterialProjectIncluded</a>

First included in: MasterPlanning/ForecastModelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsTimeAndMaterialProjectIncluded attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProjectHourForecastAutomaticallyReduced name="IsProjectHourForecastAutomaticallyReduced">IsProjectHourForecastAutomaticallyReduced</a>

First included in: MasterPlanning/ForecastModelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProjectHourForecastAutomaticallyReduced attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProjectItemForecastAutomaticallyReduced name="IsProjectItemForecastAutomaticallyReduced">IsProjectItemForecastAutomaticallyReduced</a>

First included in: MasterPlanning/ForecastModelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProjectItemForecastAutomaticallyReduced attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillProjectForecastGenerationUseProjectDate name="WillProjectForecastGenerationUseProjectDate">WillProjectForecastGenerationUseProjectDate</a>

First included in: MasterPlanning/ForecastModelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillProjectForecastGenerationUseProjectDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_ForecastModelRelationshipId name="BackingTable_ForecastModelRelationshipId">BackingTable_ForecastModelRelationshipId</a>

First included in: MasterPlanning/ForecastModelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_ForecastModelRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/MasterPlanning/Group/ForecastModel.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/MasterPlanning/Group/ForecastModel.cdm.json/ForecastModel</a></td><td><a href="../../../Tables/SupplyChain/MasterPlanning/Group/ForecastModel.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: MasterPlanning/ForecastModelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PrimaryCompanyContextRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
