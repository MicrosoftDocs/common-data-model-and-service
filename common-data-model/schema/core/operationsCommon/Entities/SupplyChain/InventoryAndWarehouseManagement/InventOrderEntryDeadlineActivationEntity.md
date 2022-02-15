---
title: InventOrderEntryDeadlineActivationEntity in InventoryAndWarehouseManagement - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Order entry deadline parameters in InventoryAndWarehouseManagement(InventOrderEntryDeadlineActivationEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/InventOrderEntryDeadlineActivationEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Order entry deadline parameters</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[IsSpecificSiteSpecificOrderGroupCombinationActivated](#IsSpecificSiteSpecificOrderGroupCombinationActivated)||<a href="InventOrderEntryDeadlineActivationEntity.md" target="_blank">InventoryAndWarehouseManagement/InventOrderEntryDeadlineActivationEntity</a>|
|[IsSpecificSiteCrossOrderGroupCombinationActivated](#IsSpecificSiteCrossOrderGroupCombinationActivated)||<a href="InventOrderEntryDeadlineActivationEntity.md" target="_blank">InventoryAndWarehouseManagement/InventOrderEntryDeadlineActivationEntity</a>|
|[IsCrossSiteSpecificOrderGroupCombinationActivated](#IsCrossSiteSpecificOrderGroupCombinationActivated)||<a href="InventOrderEntryDeadlineActivationEntity.md" target="_blank">InventoryAndWarehouseManagement/InventOrderEntryDeadlineActivationEntity</a>|
|[BackingTable_InventorderentrydeadlineparametersRelationshipId](#BackingTable_InventorderentrydeadlineparametersRelationshipId)||<a href="InventOrderEntryDeadlineActivationEntity.md" target="_blank">InventoryAndWarehouseManagement/InventOrderEntryDeadlineActivationEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="InventOrderEntryDeadlineActivationEntity.md" target="_blank">InventoryAndWarehouseManagement/InventOrderEntryDeadlineActivationEntity</a>|

### <a href=#IsSpecificSiteSpecificOrderGroupCombinationActivated name="IsSpecificSiteSpecificOrderGroupCombinationActivated">IsSpecificSiteSpecificOrderGroupCombinationActivated</a>

First included in: InventoryAndWarehouseManagement/InventOrderEntryDeadlineActivationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSpecificSiteSpecificOrderGroupCombinationActivated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSpecificSiteCrossOrderGroupCombinationActivated name="IsSpecificSiteCrossOrderGroupCombinationActivated">IsSpecificSiteCrossOrderGroupCombinationActivated</a>

First included in: InventoryAndWarehouseManagement/InventOrderEntryDeadlineActivationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSpecificSiteCrossOrderGroupCombinationActivated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCrossSiteSpecificOrderGroupCombinationActivated name="IsCrossSiteSpecificOrderGroupCombinationActivated">IsCrossSiteSpecificOrderGroupCombinationActivated</a>

First included in: InventoryAndWarehouseManagement/InventOrderEntryDeadlineActivationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCrossSiteSpecificOrderGroupCombinationActivated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_InventorderentrydeadlineparametersRelationshipId name="BackingTable_InventorderentrydeadlineparametersRelationshipId">BackingTable_InventorderentrydeadlineparametersRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventOrderEntryDeadlineActivationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_InventorderentrydeadlineparametersRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Parameter/Inventorderentrydeadlineparameters.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Parameter/Inventorderentrydeadlineparameters.cdm.json/Inventorderentrydeadlineparameters</a></td><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Parameter/Inventorderentrydeadlineparameters.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventOrderEntryDeadlineActivationEntity (this entity)  

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
