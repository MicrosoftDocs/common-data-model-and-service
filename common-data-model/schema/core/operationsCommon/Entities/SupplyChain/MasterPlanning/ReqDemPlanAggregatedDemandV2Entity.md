---
title: ReqDemPlanAggregatedDemandV2Entity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Aggregated demand

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/MasterPlanning/ReqDemPlanAggregatedDemandV2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Aggregated demand</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[DemandCategory](#DemandCategory)||<a href="ReqDemPlanAggregatedDemandV2Entity.md" target="_blank">MasterPlanning/ReqDemPlanAggregatedDemandV2Entity</a>|
|[CustomerAddressCountryRegionCode](#CustomerAddressCountryRegionCode)||<a href="ReqDemPlanAggregatedDemandV2Entity.md" target="_blank">MasterPlanning/ReqDemPlanAggregatedDemandV2Entity</a>|
|[CustomerAddressStateId](#CustomerAddressStateId)||<a href="ReqDemPlanAggregatedDemandV2Entity.md" target="_blank">MasterPlanning/ReqDemPlanAggregatedDemandV2Entity</a>|
|[CustomerGroupId](#CustomerGroupId)||<a href="ReqDemPlanAggregatedDemandV2Entity.md" target="_blank">MasterPlanning/ReqDemPlanAggregatedDemandV2Entity</a>|
|[CustomerAccountNumber](#CustomerAccountNumber)||<a href="ReqDemPlanAggregatedDemandV2Entity.md" target="_blank">MasterPlanning/ReqDemPlanAggregatedDemandV2Entity</a>|
|[ProductAllocationKeyId](#ProductAllocationKeyId)||<a href="ReqDemPlanAggregatedDemandV2Entity.md" target="_blank">MasterPlanning/ReqDemPlanAggregatedDemandV2Entity</a>|
|[ItemNumber](#ItemNumber)||<a href="ReqDemPlanAggregatedDemandV2Entity.md" target="_blank">MasterPlanning/ReqDemPlanAggregatedDemandV2Entity</a>|
|[ProductConfigurationId](#ProductConfigurationId)||<a href="ReqDemPlanAggregatedDemandV2Entity.md" target="_blank">MasterPlanning/ReqDemPlanAggregatedDemandV2Entity</a>|
|[ProductColorId](#ProductColorId)||<a href="ReqDemPlanAggregatedDemandV2Entity.md" target="_blank">MasterPlanning/ReqDemPlanAggregatedDemandV2Entity</a>|
|[ProductSizeId](#ProductSizeId)||<a href="ReqDemPlanAggregatedDemandV2Entity.md" target="_blank">MasterPlanning/ReqDemPlanAggregatedDemandV2Entity</a>|
|[ProductStyleId](#ProductStyleId)||<a href="ReqDemPlanAggregatedDemandV2Entity.md" target="_blank">MasterPlanning/ReqDemPlanAggregatedDemandV2Entity</a>|
|[ProductVersionId](#ProductVersionId)||<a href="ReqDemPlanAggregatedDemandV2Entity.md" target="_blank">MasterPlanning/ReqDemPlanAggregatedDemandV2Entity</a>|
|[DeliveringWarehouseId](#DeliveringWarehouseId)||<a href="ReqDemPlanAggregatedDemandV2Entity.md" target="_blank">MasterPlanning/ReqDemPlanAggregatedDemandV2Entity</a>|
|[DeliveringSiteId](#DeliveringSiteId)||<a href="ReqDemPlanAggregatedDemandV2Entity.md" target="_blank">MasterPlanning/ReqDemPlanAggregatedDemandV2Entity</a>|
|[InventoryStatusId](#InventoryStatusId)||<a href="ReqDemPlanAggregatedDemandV2Entity.md" target="_blank">MasterPlanning/ReqDemPlanAggregatedDemandV2Entity</a>|
|[DemandDate](#DemandDate)||<a href="ReqDemPlanAggregatedDemandV2Entity.md" target="_blank">MasterPlanning/ReqDemPlanAggregatedDemandV2Entity</a>|
|[DemandQuantity](#DemandQuantity)||<a href="ReqDemPlanAggregatedDemandV2Entity.md" target="_blank">MasterPlanning/ReqDemPlanAggregatedDemandV2Entity</a>|
|[DemandQuantityConfidenceIntervalLowerBound](#DemandQuantityConfidenceIntervalLowerBound)||<a href="ReqDemPlanAggregatedDemandV2Entity.md" target="_blank">MasterPlanning/ReqDemPlanAggregatedDemandV2Entity</a>|
|[DemandQuantityConfidenceIntervalUpperBound](#DemandQuantityConfidenceIntervalUpperBound)||<a href="ReqDemPlanAggregatedDemandV2Entity.md" target="_blank">MasterPlanning/ReqDemPlanAggregatedDemandV2Entity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="ReqDemPlanAggregatedDemandV2Entity.md" target="_blank">MasterPlanning/ReqDemPlanAggregatedDemandV2Entity</a>|

### <a href=#DemandCategory name="DemandCategory">DemandCategory</a>

First included in: MasterPlanning/ReqDemPlanAggregatedDemandV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Demand category</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Demand category</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerAddressCountryRegionCode name="CustomerAddressCountryRegionCode">CustomerAddressCountryRegionCode</a>

First included in: MasterPlanning/ReqDemPlanAggregatedDemandV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerAddressCountryRegionCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerAddressStateId name="CustomerAddressStateId">CustomerAddressStateId</a>

First included in: MasterPlanning/ReqDemPlanAggregatedDemandV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerAddressStateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerGroupId name="CustomerGroupId">CustomerGroupId</a>

First included in: MasterPlanning/ReqDemPlanAggregatedDemandV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerAccountNumber name="CustomerAccountNumber">CustomerAccountNumber</a>

First included in: MasterPlanning/ReqDemPlanAggregatedDemandV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductAllocationKeyId name="ProductAllocationKeyId">ProductAllocationKeyId</a>

First included in: MasterPlanning/ReqDemPlanAggregatedDemandV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductAllocationKeyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemNumber name="ItemNumber">ItemNumber</a>

First included in: MasterPlanning/ReqDemPlanAggregatedDemandV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductConfigurationId name="ProductConfigurationId">ProductConfigurationId</a>

First included in: MasterPlanning/ReqDemPlanAggregatedDemandV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductConfigurationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductColorId name="ProductColorId">ProductColorId</a>

First included in: MasterPlanning/ReqDemPlanAggregatedDemandV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductColorId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductSizeId name="ProductSizeId">ProductSizeId</a>

First included in: MasterPlanning/ReqDemPlanAggregatedDemandV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductSizeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductStyleId name="ProductStyleId">ProductStyleId</a>

First included in: MasterPlanning/ReqDemPlanAggregatedDemandV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductStyleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductVersionId name="ProductVersionId">ProductVersionId</a>

First included in: MasterPlanning/ReqDemPlanAggregatedDemandV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductVersionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveringWarehouseId name="DeliveringWarehouseId">DeliveringWarehouseId</a>

First included in: MasterPlanning/ReqDemPlanAggregatedDemandV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveringWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveringSiteId name="DeliveringSiteId">DeliveringSiteId</a>

First included in: MasterPlanning/ReqDemPlanAggregatedDemandV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveringSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryStatusId name="InventoryStatusId">InventoryStatusId</a>

First included in: MasterPlanning/ReqDemPlanAggregatedDemandV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryStatusId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DemandDate name="DemandDate">DemandDate</a>

First included in: MasterPlanning/ReqDemPlanAggregatedDemandV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DemandQuantity name="DemandQuantity">DemandQuantity</a>

First included in: MasterPlanning/ReqDemPlanAggregatedDemandV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DemandQuantityConfidenceIntervalLowerBound name="DemandQuantityConfidenceIntervalLowerBound">DemandQuantityConfidenceIntervalLowerBound</a>

First included in: MasterPlanning/ReqDemPlanAggregatedDemandV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Confidence interval lower bound</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandQuantityConfidenceIntervalLowerBound attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Confidence interval lower bound</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DemandQuantityConfidenceIntervalUpperBound name="DemandQuantityConfidenceIntervalUpperBound">DemandQuantityConfidenceIntervalUpperBound</a>

First included in: MasterPlanning/ReqDemPlanAggregatedDemandV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Confidence interval upper bound</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DemandQuantityConfidenceIntervalUpperBound attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Confidence interval upper bound</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: MasterPlanning/ReqDemPlanAggregatedDemandV2Entity (this entity)  

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
