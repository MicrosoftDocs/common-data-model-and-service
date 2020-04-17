---
title: ProjForecastEmplEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# ProjForecastEmplEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Entities/ProfessionalServices/ProjectManagementAndAccounting/ProjForecastEmplEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[Active](#Active)||<a href="ProjForecastEmplEntity.md" target="_blank">ProjectManagementAndAccounting/ProjForecastEmplEntity</a>|
|[ActivityNumber](#ActivityNumber)||<a href="ProjForecastEmplEntity.md" target="_blank">ProjectManagementAndAccounting/ProjForecastEmplEntity</a>|
|[Category](#Category)||<a href="ProjForecastEmplEntity.md" target="_blank">ProjectManagementAndAccounting/ProjForecastEmplEntity</a>|
|[CostPaymentDate](#CostPaymentDate)||<a href="ProjForecastEmplEntity.md" target="_blank">ProjectManagementAndAccounting/ProjForecastEmplEntity</a>|
|[CostPrice](#CostPrice)||<a href="ProjForecastEmplEntity.md" target="_blank">ProjectManagementAndAccounting/ProjForecastEmplEntity</a>|
|[CashFlowForecastStatus](#CashFlowForecastStatus)||<a href="ProjForecastEmplEntity.md" target="_blank">ProjectManagementAndAccounting/ProjForecastEmplEntity</a>|
|[SalesCurrency](#SalesCurrency)||<a href="ProjForecastEmplEntity.md" target="_blank">ProjectManagementAndAccounting/ProjForecastEmplEntity</a>|
|[DefaultDimension](#DefaultDimension)||<a href="ProjForecastEmplEntity.md" target="_blank">ProjectManagementAndAccounting/ProjForecastEmplEntity</a>|
|[EliminationDate](#EliminationDate)||<a href="ProjForecastEmplEntity.md" target="_blank">ProjectManagementAndAccounting/ProjForecastEmplEntity</a>|
|[ExchangeRate](#ExchangeRate)||<a href="ProjForecastEmplEntity.md" target="_blank">ProjectManagementAndAccounting/ProjForecastEmplEntity</a>|
|[InvoiceDate](#InvoiceDate)||<a href="ProjForecastEmplEntity.md" target="_blank">ProjectManagementAndAccounting/ProjForecastEmplEntity</a>|
|[JobIdentification](#JobIdentification)||<a href="ProjForecastEmplEntity.md" target="_blank">ProjectManagementAndAccounting/ProjForecastEmplEntity</a>|
|[LineNumber](#LineNumber)||<a href="ProjForecastEmplEntity.md" target="_blank">ProjectManagementAndAccounting/ProjForecastEmplEntity</a>|
|[LineProperty](#LineProperty)||<a href="ProjForecastEmplEntity.md" target="_blank">ProjectManagementAndAccounting/ProjForecastEmplEntity</a>|
|[ForecastModel](#ForecastModel)||<a href="ProjForecastEmplEntity.md" target="_blank">ProjectManagementAndAccounting/ProjForecastEmplEntity</a>|
|[BudgetType](#BudgetType)||<a href="ProjForecastEmplEntity.md" target="_blank">ProjectManagementAndAccounting/ProjForecastEmplEntity</a>|
|[FundingSource](#FundingSource)||<a href="ProjForecastEmplEntity.md" target="_blank">ProjectManagementAndAccounting/ProjForecastEmplEntity</a>|
|[ProjectID](#ProjectID)||<a href="ProjForecastEmplEntity.md" target="_blank">ProjectManagementAndAccounting/ProjForecastEmplEntity</a>|
|[Hours](#Hours)||<a href="ProjForecastEmplEntity.md" target="_blank">ProjectManagementAndAccounting/ProjForecastEmplEntity</a>|
|[SpecialReport](#SpecialReport)||<a href="ProjForecastEmplEntity.md" target="_blank">ProjectManagementAndAccounting/ProjForecastEmplEntity</a>|
|[SalesPaymentDate](#SalesPaymentDate)||<a href="ProjForecastEmplEntity.md" target="_blank">ProjectManagementAndAccounting/ProjForecastEmplEntity</a>|
|[SalesPrice](#SalesPrice)||<a href="ProjForecastEmplEntity.md" target="_blank">ProjectManagementAndAccounting/ProjForecastEmplEntity</a>|
|[Capacity](#Capacity)||<a href="ProjForecastEmplEntity.md" target="_blank">ProjectManagementAndAccounting/ProjForecastEmplEntity</a>|
|[ProjectDate](#ProjectDate)||<a href="ProjForecastEmplEntity.md" target="_blank">ProjectManagementAndAccounting/ProjForecastEmplEntity</a>|
|[StartTime](#StartTime)||<a href="ProjForecastEmplEntity.md" target="_blank">ProjectManagementAndAccounting/ProjForecastEmplEntity</a>|
|[Link](#Link)||<a href="ProjForecastEmplEntity.md" target="_blank">ProjectManagementAndAccounting/ProjForecastEmplEntity</a>|
|[LinkType](#LinkType)||<a href="ProjForecastEmplEntity.md" target="_blank">ProjectManagementAndAccounting/ProjForecastEmplEntity</a>|
|[HoursScheduled](#HoursScheduled)||<a href="ProjForecastEmplEntity.md" target="_blank">ProjectManagementAndAccounting/ProjForecastEmplEntity</a>|
|[EndDate](#EndDate)||<a href="ProjForecastEmplEntity.md" target="_blank">ProjectManagementAndAccounting/ProjForecastEmplEntity</a>|
|[EndTime](#EndTime)||<a href="ProjForecastEmplEntity.md" target="_blank">ProjectManagementAndAccounting/ProjForecastEmplEntity</a>|
|[WorkingTime](#WorkingTime)||<a href="ProjForecastEmplEntity.md" target="_blank">ProjectManagementAndAccounting/ProjForecastEmplEntity</a>|
|[SchedulingResource](#SchedulingResource)||<a href="ProjForecastEmplEntity.md" target="_blank">ProjectManagementAndAccounting/ProjForecastEmplEntity</a>|
|[SalesTaxGroup](#SalesTaxGroup)||<a href="ProjForecastEmplEntity.md" target="_blank">ProjectManagementAndAccounting/ProjForecastEmplEntity</a>|
|[TransactionID](#TransactionID)||<a href="ProjForecastEmplEntity.md" target="_blank">ProjectManagementAndAccounting/ProjForecastEmplEntity</a>|
|[Description](#Description)||<a href="ProjForecastEmplEntity.md" target="_blank">ProjectManagementAndAccounting/ProjForecastEmplEntity</a>|
|[Resource](#Resource)||<a href="ProjForecastEmplEntity.md" target="_blank">ProjectManagementAndAccounting/ProjForecastEmplEntity</a>|
|[ResourceCategory](#ResourceCategory)||<a href="ProjForecastEmplEntity.md" target="_blank">ProjectManagementAndAccounting/ProjForecastEmplEntity</a>|
|[ProjectContractID](#ProjectContractID)||<a href="ProjForecastEmplEntity.md" target="_blank">ProjectManagementAndAccounting/ProjForecastEmplEntity</a>|
|[FundingSourceID](#FundingSourceID)||<a href="ProjForecastEmplEntity.md" target="_blank">ProjectManagementAndAccounting/ProjForecastEmplEntity</a>|
|[DefaultDimensionDisplayValue](#DefaultDimensionDisplayValue)||<a href="ProjForecastEmplEntity.md" target="_blank">ProjectManagementAndAccounting/ProjForecastEmplEntity</a>|
|[ResourceId](#ResourceId)||<a href="ProjForecastEmplEntity.md" target="_blank">ProjectManagementAndAccounting/ProjForecastEmplEntity</a>|
|[ResourceCompanyId](#ResourceCompanyId)||<a href="ProjForecastEmplEntity.md" target="_blank">ProjectManagementAndAccounting/ProjForecastEmplEntity</a>|
|[ResourceCategoryId](#ResourceCategoryId)||<a href="ProjForecastEmplEntity.md" target="_blank">ProjectManagementAndAccounting/ProjForecastEmplEntity</a>|
|[Relationship_DimensionDimensionSetRelationshipId](#Relationship_DimensionDimensionSetRelationshipId)||<a href="ProjForecastEmplEntity.md" target="_blank">ProjectManagementAndAccounting/ProjForecastEmplEntity</a>|
|[Relationship_ProjectEntityRelationshipId](#Relationship_ProjectEntityRelationshipId)||<a href="ProjForecastEmplEntity.md" target="_blank">ProjectManagementAndAccounting/ProjForecastEmplEntity</a>|
|[Relationship_ProjProjectLinePropertyEntityRelationshipId](#Relationship_ProjProjectLinePropertyEntityRelationshipId)||<a href="ProjForecastEmplEntity.md" target="_blank">ProjectManagementAndAccounting/ProjForecastEmplEntity</a>|
|[Relationship_OMLegalEntityRelationshipId](#Relationship_OMLegalEntityRelationshipId)||<a href="ProjForecastEmplEntity.md" target="_blank">ProjectManagementAndAccounting/ProjForecastEmplEntity</a>|
|[Relationship_ResResourceDataEntityRelationshipId](#Relationship_ResResourceDataEntityRelationshipId)||<a href="ProjForecastEmplEntity.md" target="_blank">ProjectManagementAndAccounting/ProjForecastEmplEntity</a>|
|[Relationship_ResResourceCategoryDataEntityRelationshipId](#Relationship_ResResourceCategoryDataEntityRelationshipId)||<a href="ProjForecastEmplEntity.md" target="_blank">ProjectManagementAndAccounting/ProjForecastEmplEntity</a>|
|[BackingTable_ProjForecastEmplRelationshipId](#BackingTable_ProjForecastEmplRelationshipId)||<a href="ProjForecastEmplEntity.md" target="_blank">ProjectManagementAndAccounting/ProjForecastEmplEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="ProjForecastEmplEntity.md" target="_blank">ProjectManagementAndAccounting/ProjForecastEmplEntity</a>|

### <a href=#Active name="Active">Active</a>

First included in: ProjectManagementAndAccounting/ProjForecastEmplEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Active attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActivityNumber name="ActivityNumber">ActivityNumber</a>

First included in: ProjectManagementAndAccounting/ProjForecastEmplEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActivityNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Category name="Category">Category</a>

First included in: ProjectManagementAndAccounting/ProjForecastEmplEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Category attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostPaymentDate name="CostPaymentDate">CostPaymentDate</a>

First included in: ProjectManagementAndAccounting/ProjForecastEmplEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostPaymentDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostPrice name="CostPrice">CostPrice</a>

First included in: ProjectManagementAndAccounting/ProjForecastEmplEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostPrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashFlowForecastStatus name="CashFlowForecastStatus">CashFlowForecastStatus</a>

First included in: ProjectManagementAndAccounting/ProjForecastEmplEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashFlowForecastStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesCurrency name="SalesCurrency">SalesCurrency</a>

First included in: ProjectManagementAndAccounting/ProjForecastEmplEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimension name="DefaultDimension">DefaultDimension</a>

First included in: ProjectManagementAndAccounting/ProjForecastEmplEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EliminationDate name="EliminationDate">EliminationDate</a>

First included in: ProjectManagementAndAccounting/ProjForecastEmplEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EliminationDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExchangeRate name="ExchangeRate">ExchangeRate</a>

First included in: ProjectManagementAndAccounting/ProjForecastEmplEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchangeRate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceDate name="InvoiceDate">InvoiceDate</a>

First included in: ProjectManagementAndAccounting/ProjForecastEmplEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JobIdentification name="JobIdentification">JobIdentification</a>

First included in: ProjectManagementAndAccounting/ProjForecastEmplEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JobIdentification attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: ProjectManagementAndAccounting/ProjForecastEmplEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineProperty name="LineProperty">LineProperty</a>

First included in: ProjectManagementAndAccounting/ProjForecastEmplEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineProperty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ForecastModel name="ForecastModel">ForecastModel</a>

First included in: ProjectManagementAndAccounting/ProjForecastEmplEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForecastModel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BudgetType name="BudgetType">BudgetType</a>

First included in: ProjectManagementAndAccounting/ProjForecastEmplEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FundingSource name="FundingSource">FundingSource</a>

First included in: ProjectManagementAndAccounting/ProjForecastEmplEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FundingSource attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectID name="ProjectID">ProjectID</a>

First included in: ProjectManagementAndAccounting/ProjForecastEmplEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Hours name="Hours">Hours</a>

First included in: ProjectManagementAndAccounting/ProjForecastEmplEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Hours attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SpecialReport name="SpecialReport">SpecialReport</a>

First included in: ProjectManagementAndAccounting/ProjForecastEmplEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SpecialReport attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesPaymentDate name="SalesPaymentDate">SalesPaymentDate</a>

First included in: ProjectManagementAndAccounting/ProjForecastEmplEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPaymentDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesPrice name="SalesPrice">SalesPrice</a>

First included in: ProjectManagementAndAccounting/ProjForecastEmplEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Capacity name="Capacity">Capacity</a>

First included in: ProjectManagementAndAccounting/ProjForecastEmplEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Capacity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectDate name="ProjectDate">ProjectDate</a>

First included in: ProjectManagementAndAccounting/ProjForecastEmplEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StartTime name="StartTime">StartTime</a>

First included in: ProjectManagementAndAccounting/ProjForecastEmplEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Link name="Link">Link</a>

First included in: ProjectManagementAndAccounting/ProjForecastEmplEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Link attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LinkType name="LinkType">LinkType</a>

First included in: ProjectManagementAndAccounting/ProjForecastEmplEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LinkType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HoursScheduled name="HoursScheduled">HoursScheduled</a>

First included in: ProjectManagementAndAccounting/ProjForecastEmplEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HoursScheduled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EndDate name="EndDate">EndDate</a>

First included in: ProjectManagementAndAccounting/ProjForecastEmplEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EndTime name="EndTime">EndTime</a>

First included in: ProjectManagementAndAccounting/ProjForecastEmplEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkingTime name="WorkingTime">WorkingTime</a>

First included in: ProjectManagementAndAccounting/ProjForecastEmplEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkingTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SchedulingResource name="SchedulingResource">SchedulingResource</a>

First included in: ProjectManagementAndAccounting/ProjForecastEmplEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SchedulingResource attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxGroup name="SalesTaxGroup">SalesTaxGroup</a>

First included in: ProjectManagementAndAccounting/ProjForecastEmplEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionID name="TransactionID">TransactionID</a>

First included in: ProjectManagementAndAccounting/ProjForecastEmplEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: ProjectManagementAndAccounting/ProjForecastEmplEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Resource name="Resource">Resource</a>

First included in: ProjectManagementAndAccounting/ProjForecastEmplEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Resource attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResourceCategory name="ResourceCategory">ResourceCategory</a>

First included in: ProjectManagementAndAccounting/ProjForecastEmplEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResourceCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectContractID name="ProjectContractID">ProjectContractID</a>

First included in: ProjectManagementAndAccounting/ProjForecastEmplEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectContractID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FundingSourceID name="FundingSourceID">FundingSourceID</a>

First included in: ProjectManagementAndAccounting/ProjForecastEmplEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FundingSourceID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimensionDisplayValue name="DefaultDimensionDisplayValue">DefaultDimensionDisplayValue</a>

First included in: ProjectManagementAndAccounting/ProjForecastEmplEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResourceId name="ResourceId">ResourceId</a>

First included in: ProjectManagementAndAccounting/ProjForecastEmplEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResourceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResourceCompanyId name="ResourceCompanyId">ResourceCompanyId</a>

First included in: ProjectManagementAndAccounting/ProjForecastEmplEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResourceCompanyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResourceCategoryId name="ResourceCategoryId">ResourceCategoryId</a>

First included in: ProjectManagementAndAccounting/ProjForecastEmplEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResourceCategoryId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DimensionDimensionSetRelationshipId name="Relationship_DimensionDimensionSetRelationshipId">Relationship_DimensionDimensionSetRelationshipId</a>

First included in: ProjectManagementAndAccounting/ProjForecastEmplEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DimensionDimensionSetRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ProjectEntityRelationshipId name="Relationship_ProjectEntityRelationshipId">Relationship_ProjectEntityRelationshipId</a>

First included in: ProjectManagementAndAccounting/ProjForecastEmplEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProjectEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ProjProjectLinePropertyEntityRelationshipId name="Relationship_ProjProjectLinePropertyEntityRelationshipId">Relationship_ProjProjectLinePropertyEntityRelationshipId</a>

First included in: ProjectManagementAndAccounting/ProjForecastEmplEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProjProjectLinePropertyEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_OMLegalEntityRelationshipId name="Relationship_OMLegalEntityRelationshipId">Relationship_OMLegalEntityRelationshipId</a>

First included in: ProjectManagementAndAccounting/ProjForecastEmplEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OMLegalEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ResResourceDataEntityRelationshipId name="Relationship_ResResourceDataEntityRelationshipId">Relationship_ResResourceDataEntityRelationshipId</a>

First included in: ProjectManagementAndAccounting/ProjForecastEmplEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ResResourceDataEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ResResourceCategoryDataEntityRelationshipId name="Relationship_ResResourceCategoryDataEntityRelationshipId">Relationship_ResResourceCategoryDataEntityRelationshipId</a>

First included in: ProjectManagementAndAccounting/ProjForecastEmplEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ResResourceCategoryDataEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_ProjForecastEmplRelationshipId name="BackingTable_ProjForecastEmplRelationshipId">BackingTable_ProjForecastEmplRelationshipId</a>

First included in: ProjectManagementAndAccounting/ProjForecastEmplEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_ProjForecastEmplRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/ProfessionalServices/ProjectManagementAndAccounting/Transaction/ProjForecastEmpl.md" target="_blank">/core/erp/Tables/ProfessionalServices/ProjectManagementAndAccounting/Transaction/ProjForecastEmpl.cdm.json/ProjForecastEmpl</a></td><td><a href="../../../Tables/ProfessionalServices/ProjectManagementAndAccounting/Transaction/ProjForecastEmpl.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProjectManagementAndAccounting/ProjForecastEmplEntity (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/erp/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
