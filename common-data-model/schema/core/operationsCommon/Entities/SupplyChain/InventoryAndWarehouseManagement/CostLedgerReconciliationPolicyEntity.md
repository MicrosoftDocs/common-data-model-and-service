---
title: CostLedgerReconciliationPolicyEntity in InventoryAndWarehouseManagement - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/21/2020
ms.author: nebanfic
---

# Reconciliation parameters in InventoryAndWarehouseManagement(CostLedgerReconciliationPolicyEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/CostLedgerReconciliationPolicyEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reconciliation parameters</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ReconciliationPrinciple](#ReconciliationPrinciple)||<a href="CostLedgerReconciliationPolicyEntity.md" target="_blank">InventoryAndWarehouseManagement/CostLedgerReconciliationPolicyEntity</a>|
|[InventoryMainAccountIdDisplayValue](#InventoryMainAccountIdDisplayValue)||<a href="CostLedgerReconciliationPolicyEntity.md" target="_blank">InventoryAndWarehouseManagement/CostLedgerReconciliationPolicyEntity</a>|
|[WIPMainAccountIdDisplayValue](#WIPMainAccountIdDisplayValue)||<a href="CostLedgerReconciliationPolicyEntity.md" target="_blank">InventoryAndWarehouseManagement/CostLedgerReconciliationPolicyEntity</a>|
|[InventoryMainAccountCategoryReferenceId](#InventoryMainAccountCategoryReferenceId)||<a href="CostLedgerReconciliationPolicyEntity.md" target="_blank">InventoryAndWarehouseManagement/CostLedgerReconciliationPolicyEntity</a>|
|[WIPMainAccountCategoryReferenceId](#WIPMainAccountCategoryReferenceId)||<a href="CostLedgerReconciliationPolicyEntity.md" target="_blank">InventoryAndWarehouseManagement/CostLedgerReconciliationPolicyEntity</a>|
|[BackingTable_CostParametersRelationshipId](#BackingTable_CostParametersRelationshipId)||<a href="CostLedgerReconciliationPolicyEntity.md" target="_blank">InventoryAndWarehouseManagement/CostLedgerReconciliationPolicyEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="CostLedgerReconciliationPolicyEntity.md" target="_blank">InventoryAndWarehouseManagement/CostLedgerReconciliationPolicyEntity</a>|

### <a href=#ReconciliationPrinciple name="ReconciliationPrinciple">ReconciliationPrinciple</a>

First included in: InventoryAndWarehouseManagement/CostLedgerReconciliationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReconciliationPrinciple attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryMainAccountIdDisplayValue name="InventoryMainAccountIdDisplayValue">InventoryMainAccountIdDisplayValue</a>

First included in: InventoryAndWarehouseManagement/CostLedgerReconciliationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WIPMainAccountIdDisplayValue name="WIPMainAccountIdDisplayValue">WIPMainAccountIdDisplayValue</a>

First included in: InventoryAndWarehouseManagement/CostLedgerReconciliationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WIPMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryMainAccountCategoryReferenceId name="InventoryMainAccountCategoryReferenceId">InventoryMainAccountCategoryReferenceId</a>

First included in: InventoryAndWarehouseManagement/CostLedgerReconciliationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryMainAccountCategoryReferenceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WIPMainAccountCategoryReferenceId name="WIPMainAccountCategoryReferenceId">WIPMainAccountCategoryReferenceId</a>

First included in: InventoryAndWarehouseManagement/CostLedgerReconciliationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WIPMainAccountCategoryReferenceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_CostParametersRelationshipId name="BackingTable_CostParametersRelationshipId">BackingTable_CostParametersRelationshipId</a>

First included in: InventoryAndWarehouseManagement/CostLedgerReconciliationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_CostParametersRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Parameter/CostParameters.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Parameter/CostParameters.cdm.json/CostParameters</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Parameter/CostParameters.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/CostLedgerReconciliationPolicyEntity (this entity)  

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
