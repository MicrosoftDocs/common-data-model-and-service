---
title: ReqDemPlanAggregatedDemandPerAllocationKeyEntity in MasterPlanning - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Aggregated demand per allocation key in MasterPlanning(ReqDemPlanAggregatedDemandPerAllocationKeyEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/MasterPlanning/ReqDemPlanAggregatedDemandPerAllocationKeyEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Aggregated demand per allocation key</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[DemandCategory](#DemandCategory)||<a href="ReqDemPlanAggregatedDemandPerAllocationKeyEntity.md" target="_blank">MasterPlanning/ReqDemPlanAggregatedDemandPerAllocationKeyEntity</a>|
|[DeliveringSiteId](#DeliveringSiteId)||<a href="ReqDemPlanAggregatedDemandPerAllocationKeyEntity.md" target="_blank">MasterPlanning/ReqDemPlanAggregatedDemandPerAllocationKeyEntity</a>|
|[ProductAllocationKeyId](#ProductAllocationKeyId)||<a href="ReqDemPlanAggregatedDemandPerAllocationKeyEntity.md" target="_blank">MasterPlanning/ReqDemPlanAggregatedDemandPerAllocationKeyEntity</a>|
|[DemandDate](#DemandDate)||<a href="ReqDemPlanAggregatedDemandPerAllocationKeyEntity.md" target="_blank">MasterPlanning/ReqDemPlanAggregatedDemandPerAllocationKeyEntity</a>|
|[DemandQuantity](#DemandQuantity)||<a href="ReqDemPlanAggregatedDemandPerAllocationKeyEntity.md" target="_blank">MasterPlanning/ReqDemPlanAggregatedDemandPerAllocationKeyEntity</a>|
|[DemandQuantityConfidenceIntervalLowerBound](#DemandQuantityConfidenceIntervalLowerBound)||<a href="ReqDemPlanAggregatedDemandPerAllocationKeyEntity.md" target="_blank">MasterPlanning/ReqDemPlanAggregatedDemandPerAllocationKeyEntity</a>|
|[DemandQuantityConfidenceIntervalUpperBound](#DemandQuantityConfidenceIntervalUpperBound)||<a href="ReqDemPlanAggregatedDemandPerAllocationKeyEntity.md" target="_blank">MasterPlanning/ReqDemPlanAggregatedDemandPerAllocationKeyEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="ReqDemPlanAggregatedDemandPerAllocationKeyEntity.md" target="_blank">MasterPlanning/ReqDemPlanAggregatedDemandPerAllocationKeyEntity</a>|

### <a href=#DemandCategory name="DemandCategory">DemandCategory</a>

First included in: MasterPlanning/ReqDemPlanAggregatedDemandPerAllocationKeyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Demand category</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Demand category</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveringSiteId name="DeliveringSiteId">DeliveringSiteId</a>

First included in: MasterPlanning/ReqDemPlanAggregatedDemandPerAllocationKeyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveringSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductAllocationKeyId name="ProductAllocationKeyId">ProductAllocationKeyId</a>

First included in: MasterPlanning/ReqDemPlanAggregatedDemandPerAllocationKeyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductAllocationKeyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DemandDate name="DemandDate">DemandDate</a>

First included in: MasterPlanning/ReqDemPlanAggregatedDemandPerAllocationKeyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DemandQuantity name="DemandQuantity">DemandQuantity</a>

First included in: MasterPlanning/ReqDemPlanAggregatedDemandPerAllocationKeyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DemandQuantityConfidenceIntervalLowerBound name="DemandQuantityConfidenceIntervalLowerBound">DemandQuantityConfidenceIntervalLowerBound</a>

First included in: MasterPlanning/ReqDemPlanAggregatedDemandPerAllocationKeyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Confidence interval lower bound</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandQuantityConfidenceIntervalLowerBound attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Confidence interval lower bound</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DemandQuantityConfidenceIntervalUpperBound name="DemandQuantityConfidenceIntervalUpperBound">DemandQuantityConfidenceIntervalUpperBound</a>

First included in: MasterPlanning/ReqDemPlanAggregatedDemandPerAllocationKeyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Confidence interval upper bound</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandQuantityConfidenceIntervalUpperBound attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Confidence interval upper bound</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: MasterPlanning/ReqDemPlanAggregatedDemandPerAllocationKeyEntity (this entity)  

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
