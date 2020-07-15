---
title: WrkCtrSiteSpecificOperationsResourceSchedulingParametersEntity in ProductionControl - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/15/2020
ms.author: nebanfic
---

# Resource parameters by site in ProductionControl(WrkCtrSiteSpecificOperationsResourceSchedulingParametersEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductionControl/WrkCtrSiteSpecificOperationsResourceSchedulingParametersEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Resource parameters by site</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[SiteId](#SiteId)||<a href="WrkCtrSiteSpecificOperationsResourceSchedulingParametersEntity.md" target="_blank">ProductionControl/WrkCtrSiteSpecificOperationsResourceSchedulingParametersEntity</a>|
|[IsSchedulingSequenceTimeoutEnabled](#IsSchedulingSequenceTimeoutEnabled)||<a href="WrkCtrSiteSpecificOperationsResourceSchedulingParametersEntity.md" target="_blank">ProductionControl/WrkCtrSiteSpecificOperationsResourceSchedulingParametersEntity</a>|
|[SchedulingSequenceTimeoutSeconds](#SchedulingSequenceTimeoutSeconds)||<a href="WrkCtrSiteSpecificOperationsResourceSchedulingParametersEntity.md" target="_blank">ProductionControl/WrkCtrSiteSpecificOperationsResourceSchedulingParametersEntity</a>|
|[IsSchedulingOptimizationSequenceTimeoutEnabled](#IsSchedulingOptimizationSequenceTimeoutEnabled)||<a href="WrkCtrSiteSpecificOperationsResourceSchedulingParametersEntity.md" target="_blank">ProductionControl/WrkCtrSiteSpecificOperationsResourceSchedulingParametersEntity</a>|
|[SchedulingOptimizationSequenceTimeoutSeconds](#SchedulingOptimizationSequenceTimeoutSeconds)||<a href="WrkCtrSiteSpecificOperationsResourceSchedulingParametersEntity.md" target="_blank">ProductionControl/WrkCtrSiteSpecificOperationsResourceSchedulingParametersEntity</a>|
|[WillReschedulingPreserveProductionUnit](#WillReschedulingPreserveProductionUnit)||<a href="WrkCtrSiteSpecificOperationsResourceSchedulingParametersEntity.md" target="_blank">ProductionControl/WrkCtrSiteSpecificOperationsResourceSchedulingParametersEntity</a>|
|[WillReschedulingPreserveWarehouse](#WillReschedulingPreserveWarehouse)||<a href="WrkCtrSiteSpecificOperationsResourceSchedulingParametersEntity.md" target="_blank">ProductionControl/WrkCtrSiteSpecificOperationsResourceSchedulingParametersEntity</a>|
|[PrimaryOperationsResourceSelectionMethod](#PrimaryOperationsResourceSelectionMethod)||<a href="WrkCtrSiteSpecificOperationsResourceSchedulingParametersEntity.md" target="_blank">ProductionControl/WrkCtrSiteSpecificOperationsResourceSchedulingParametersEntity</a>|
|[BackingTable_WrkCtrParametersDimRelationshipId](#BackingTable_WrkCtrParametersDimRelationshipId)||<a href="WrkCtrSiteSpecificOperationsResourceSchedulingParametersEntity.md" target="_blank">ProductionControl/WrkCtrSiteSpecificOperationsResourceSchedulingParametersEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="WrkCtrSiteSpecificOperationsResourceSchedulingParametersEntity.md" target="_blank">ProductionControl/WrkCtrSiteSpecificOperationsResourceSchedulingParametersEntity</a>|

### <a href=#SiteId name="SiteId">SiteId</a>

First included in: ProductionControl/WrkCtrSiteSpecificOperationsResourceSchedulingParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSchedulingSequenceTimeoutEnabled name="IsSchedulingSequenceTimeoutEnabled">IsSchedulingSequenceTimeoutEnabled</a>

First included in: ProductionControl/WrkCtrSiteSpecificOperationsResourceSchedulingParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSchedulingSequenceTimeoutEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SchedulingSequenceTimeoutSeconds name="SchedulingSequenceTimeoutSeconds">SchedulingSequenceTimeoutSeconds</a>

First included in: ProductionControl/WrkCtrSiteSpecificOperationsResourceSchedulingParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SchedulingSequenceTimeoutSeconds attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSchedulingOptimizationSequenceTimeoutEnabled name="IsSchedulingOptimizationSequenceTimeoutEnabled">IsSchedulingOptimizationSequenceTimeoutEnabled</a>

First included in: ProductionControl/WrkCtrSiteSpecificOperationsResourceSchedulingParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSchedulingOptimizationSequenceTimeoutEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SchedulingOptimizationSequenceTimeoutSeconds name="SchedulingOptimizationSequenceTimeoutSeconds">SchedulingOptimizationSequenceTimeoutSeconds</a>

First included in: ProductionControl/WrkCtrSiteSpecificOperationsResourceSchedulingParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SchedulingOptimizationSequenceTimeoutSeconds attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillReschedulingPreserveProductionUnit name="WillReschedulingPreserveProductionUnit">WillReschedulingPreserveProductionUnit</a>

First included in: ProductionControl/WrkCtrSiteSpecificOperationsResourceSchedulingParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillReschedulingPreserveProductionUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillReschedulingPreserveWarehouse name="WillReschedulingPreserveWarehouse">WillReschedulingPreserveWarehouse</a>

First included in: ProductionControl/WrkCtrSiteSpecificOperationsResourceSchedulingParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillReschedulingPreserveWarehouse attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryOperationsResourceSelectionMethod name="PrimaryOperationsResourceSelectionMethod">PrimaryOperationsResourceSelectionMethod</a>

First included in: ProductionControl/WrkCtrSiteSpecificOperationsResourceSchedulingParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryOperationsResourceSelectionMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_WrkCtrParametersDimRelationshipId name="BackingTable_WrkCtrParametersDimRelationshipId">BackingTable_WrkCtrParametersDimRelationshipId</a>

First included in: ProductionControl/WrkCtrSiteSpecificOperationsResourceSchedulingParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_WrkCtrParametersDimRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/MasterPlanning/Parameter/WrkCtrParametersDim.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/MasterPlanning/Parameter/WrkCtrParametersDim.cdm.json/WrkCtrParametersDim</a></td><td><a href="../../../Tables/SupplyChain/MasterPlanning/Parameter/WrkCtrParametersDim.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProductionControl/WrkCtrSiteSpecificOperationsResourceSchedulingParametersEntity (this entity)  

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
