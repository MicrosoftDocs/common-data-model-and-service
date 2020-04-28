---
title: CostMonthlyCostStatementEntryV2Entity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Monthly cost statement entries V2

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/CostMonthlyCostStatementEntryV2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Monthly cost statement entries V2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AccountingMonthStartDate](#AccountingMonthStartDate)||<a href="CostMonthlyCostStatementEntryV2Entity.md" target="_blank">InventoryAndWarehouseManagement/CostMonthlyCostStatementEntryV2Entity</a>|
|[CostAmount](#CostAmount)||<a href="CostMonthlyCostStatementEntryV2Entity.md" target="_blank">InventoryAndWarehouseManagement/CostMonthlyCostStatementEntryV2Entity</a>|
|[CostResourceNumber](#CostResourceNumber)||<a href="CostMonthlyCostStatementEntryV2Entity.md" target="_blank">InventoryAndWarehouseManagement/CostMonthlyCostStatementEntryV2Entity</a>|
|[CostResourceType](#CostResourceType)||<a href="CostMonthlyCostStatementEntryV2Entity.md" target="_blank">InventoryAndWarehouseManagement/CostMonthlyCostStatementEntryV2Entity</a>|
|[Quantity](#Quantity)||<a href="CostMonthlyCostStatementEntryV2Entity.md" target="_blank">InventoryAndWarehouseManagement/CostMonthlyCostStatementEntryV2Entity</a>|
|[CostStatementType](#CostStatementType)||<a href="CostMonthlyCostStatementEntryV2Entity.md" target="_blank">InventoryAndWarehouseManagement/CostMonthlyCostStatementEntryV2Entity</a>|
|[LevelOneCostStatementLineCategoryName](#LevelOneCostStatementLineCategoryName)||<a href="CostMonthlyCostStatementEntryV2Entity.md" target="_blank">InventoryAndWarehouseManagement/CostMonthlyCostStatementEntryV2Entity</a>|
|[LevelTwoCostStatementLineCategoryName](#LevelTwoCostStatementLineCategoryName)||<a href="CostMonthlyCostStatementEntryV2Entity.md" target="_blank">InventoryAndWarehouseManagement/CostMonthlyCostStatementEntryV2Entity</a>|
|[LevelThreeCostStatementLineCategoryName](#LevelThreeCostStatementLineCategoryName)||<a href="CostMonthlyCostStatementEntryV2Entity.md" target="_blank">InventoryAndWarehouseManagement/CostMonthlyCostStatementEntryV2Entity</a>|
|[CostResourceGroupId](#CostResourceGroupId)||<a href="CostMonthlyCostStatementEntryV2Entity.md" target="_blank">InventoryAndWarehouseManagement/CostMonthlyCostStatementEntryV2Entity</a>|
|[ProductConfigurationId](#ProductConfigurationId)||<a href="CostMonthlyCostStatementEntryV2Entity.md" target="_blank">InventoryAndWarehouseManagement/CostMonthlyCostStatementEntryV2Entity</a>|
|[ProductColorId](#ProductColorId)||<a href="CostMonthlyCostStatementEntryV2Entity.md" target="_blank">InventoryAndWarehouseManagement/CostMonthlyCostStatementEntryV2Entity</a>|
|[OperationalSiteId](#OperationalSiteId)||<a href="CostMonthlyCostStatementEntryV2Entity.md" target="_blank">InventoryAndWarehouseManagement/CostMonthlyCostStatementEntryV2Entity</a>|
|[ProductSizeId](#ProductSizeId)||<a href="CostMonthlyCostStatementEntryV2Entity.md" target="_blank">InventoryAndWarehouseManagement/CostMonthlyCostStatementEntryV2Entity</a>|
|[ProductStyleId](#ProductStyleId)||<a href="CostMonthlyCostStatementEntryV2Entity.md" target="_blank">InventoryAndWarehouseManagement/CostMonthlyCostStatementEntryV2Entity</a>|
|[ProductVersionId](#ProductVersionId)||<a href="CostMonthlyCostStatementEntryV2Entity.md" target="_blank">InventoryAndWarehouseManagement/CostMonthlyCostStatementEntryV2Entity</a>|
|[Relationship_OperationalSiteRelationshipId](#Relationship_OperationalSiteRelationshipId)||<a href="CostMonthlyCostStatementEntryV2Entity.md" target="_blank">InventoryAndWarehouseManagement/CostMonthlyCostStatementEntryV2Entity</a>|
|[Relationship_ProductConfigurationRelationshipId](#Relationship_ProductConfigurationRelationshipId)||<a href="CostMonthlyCostStatementEntryV2Entity.md" target="_blank">InventoryAndWarehouseManagement/CostMonthlyCostStatementEntryV2Entity</a>|
|[Relationship_ProductColorRelationshipId](#Relationship_ProductColorRelationshipId)||<a href="CostMonthlyCostStatementEntryV2Entity.md" target="_blank">InventoryAndWarehouseManagement/CostMonthlyCostStatementEntryV2Entity</a>|
|[Relationship_ProductStyleRelationshipId](#Relationship_ProductStyleRelationshipId)||<a href="CostMonthlyCostStatementEntryV2Entity.md" target="_blank">InventoryAndWarehouseManagement/CostMonthlyCostStatementEntryV2Entity</a>|
|[Relationship_ProductVersionRelationshipId](#Relationship_ProductVersionRelationshipId)||<a href="CostMonthlyCostStatementEntryV2Entity.md" target="_blank">InventoryAndWarehouseManagement/CostMonthlyCostStatementEntryV2Entity</a>|
|[Relationship_ProductSizeRelationshipId](#Relationship_ProductSizeRelationshipId)||<a href="CostMonthlyCostStatementEntryV2Entity.md" target="_blank">InventoryAndWarehouseManagement/CostMonthlyCostStatementEntryV2Entity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="CostMonthlyCostStatementEntryV2Entity.md" target="_blank">InventoryAndWarehouseManagement/CostMonthlyCostStatementEntryV2Entity</a>|

### <a href=#AccountingMonthStartDate name="AccountingMonthStartDate">AccountingMonthStartDate</a>

First included in: InventoryAndWarehouseManagement/CostMonthlyCostStatementEntryV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountingMonthStartDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostAmount name="CostAmount">CostAmount</a>

First included in: InventoryAndWarehouseManagement/CostMonthlyCostStatementEntryV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostResourceNumber name="CostResourceNumber">CostResourceNumber</a>

First included in: InventoryAndWarehouseManagement/CostMonthlyCostStatementEntryV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostResourceNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostResourceType name="CostResourceType">CostResourceType</a>

First included in: InventoryAndWarehouseManagement/CostMonthlyCostStatementEntryV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostResourceType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Quantity name="Quantity">Quantity</a>

First included in: InventoryAndWarehouseManagement/CostMonthlyCostStatementEntryV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Quantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostStatementType name="CostStatementType">CostStatementType</a>

First included in: InventoryAndWarehouseManagement/CostMonthlyCostStatementEntryV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostStatementType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LevelOneCostStatementLineCategoryName name="LevelOneCostStatementLineCategoryName">LevelOneCostStatementLineCategoryName</a>

First included in: InventoryAndWarehouseManagement/CostMonthlyCostStatementEntryV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LevelOneCostStatementLineCategoryName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LevelTwoCostStatementLineCategoryName name="LevelTwoCostStatementLineCategoryName">LevelTwoCostStatementLineCategoryName</a>

First included in: InventoryAndWarehouseManagement/CostMonthlyCostStatementEntryV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LevelTwoCostStatementLineCategoryName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LevelThreeCostStatementLineCategoryName name="LevelThreeCostStatementLineCategoryName">LevelThreeCostStatementLineCategoryName</a>

First included in: InventoryAndWarehouseManagement/CostMonthlyCostStatementEntryV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LevelThreeCostStatementLineCategoryName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostResourceGroupId name="CostResourceGroupId">CostResourceGroupId</a>

First included in: InventoryAndWarehouseManagement/CostMonthlyCostStatementEntryV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostResourceGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductConfigurationId name="ProductConfigurationId">ProductConfigurationId</a>

First included in: InventoryAndWarehouseManagement/CostMonthlyCostStatementEntryV2Entity (this entity)  

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

First included in: InventoryAndWarehouseManagement/CostMonthlyCostStatementEntryV2Entity (this entity)  

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

### <a href=#OperationalSiteId name="OperationalSiteId">OperationalSiteId</a>

First included in: InventoryAndWarehouseManagement/CostMonthlyCostStatementEntryV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperationalSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductSizeId name="ProductSizeId">ProductSizeId</a>

First included in: InventoryAndWarehouseManagement/CostMonthlyCostStatementEntryV2Entity (this entity)  

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

First included in: InventoryAndWarehouseManagement/CostMonthlyCostStatementEntryV2Entity (this entity)  

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

First included in: InventoryAndWarehouseManagement/CostMonthlyCostStatementEntryV2Entity (this entity)  

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

### <a href=#Relationship_OperationalSiteRelationshipId name="Relationship_OperationalSiteRelationshipId">Relationship_OperationalSiteRelationshipId</a>

First included in: InventoryAndWarehouseManagement/CostMonthlyCostStatementEntryV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OperationalSiteRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ProductConfigurationRelationshipId name="Relationship_ProductConfigurationRelationshipId">Relationship_ProductConfigurationRelationshipId</a>

First included in: InventoryAndWarehouseManagement/CostMonthlyCostStatementEntryV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProductConfigurationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ProductColorRelationshipId name="Relationship_ProductColorRelationshipId">Relationship_ProductColorRelationshipId</a>

First included in: InventoryAndWarehouseManagement/CostMonthlyCostStatementEntryV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProductColorRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ProductStyleRelationshipId name="Relationship_ProductStyleRelationshipId">Relationship_ProductStyleRelationshipId</a>

First included in: InventoryAndWarehouseManagement/CostMonthlyCostStatementEntryV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProductStyleRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ProductVersionRelationshipId name="Relationship_ProductVersionRelationshipId">Relationship_ProductVersionRelationshipId</a>

First included in: InventoryAndWarehouseManagement/CostMonthlyCostStatementEntryV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProductVersionRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ProductSizeRelationshipId name="Relationship_ProductSizeRelationshipId">Relationship_ProductSizeRelationshipId</a>

First included in: InventoryAndWarehouseManagement/CostMonthlyCostStatementEntryV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProductSizeRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/CostMonthlyCostStatementEntryV2Entity (this entity)  

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
