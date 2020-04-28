---
title: BudgetParametersEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Budget parameters

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/Budgeting/BudgetParametersEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Budget parameters</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AllocationKey](#AllocationKey)||<a href="BudgetParametersEntity.md" target="_blank">Budgeting/BudgetParametersEntity</a>|
|[BudgetJournal](#BudgetJournal)||<a href="BudgetParametersEntity.md" target="_blank">Budgeting/BudgetParametersEntity</a>|
|[CheckRevenueBudgetForZeroBudgetBalances](#CheckRevenueBudgetForZeroBudgetBalances)||<a href="BudgetParametersEntity.md" target="_blank">Budgeting/BudgetParametersEntity</a>|
|[DoCompleteRegisterEntriesOnTransferFromDemandForecast](#DoCompleteRegisterEntriesOnTransferFromDemandForecast)||<a href="BudgetParametersEntity.md" target="_blank">Budgeting/BudgetParametersEntity</a>|
|[DoCompleteRegisterEntriesOnTransferFromFixedAssets](#DoCompleteRegisterEntriesOnTransferFromFixedAssets)||<a href="BudgetParametersEntity.md" target="_blank">Budgeting/BudgetParametersEntity</a>|
|[DoCompleteRegisterEntriesOnTransferFromProject](#DoCompleteRegisterEntriesOnTransferFromProject)||<a href="BudgetParametersEntity.md" target="_blank">Budgeting/BudgetParametersEntity</a>|
|[DoCompleteRegisterEntriesOnTransferFromSupplyForecast](#DoCompleteRegisterEntriesOnTransferFromSupplyForecast)||<a href="BudgetParametersEntity.md" target="_blank">Budgeting/BudgetParametersEntity</a>|
|[ID](#ID)||<a href="BudgetParametersEntity.md" target="_blank">Budgeting/BudgetParametersEntity</a>|
|[TimePeriodForBudgetBalances](#TimePeriodForBudgetBalances)||<a href="BudgetParametersEntity.md" target="_blank">Budgeting/BudgetParametersEntity</a>|
|[UseFrenchPublicSectorAccountingRules](#UseFrenchPublicSectorAccountingRules)||<a href="BudgetParametersEntity.md" target="_blank">Budgeting/BudgetParametersEntity</a>|
|[UseRulesForBudgetTransfers](#UseRulesForBudgetTransfers)||<a href="BudgetParametersEntity.md" target="_blank">Budgeting/BudgetParametersEntity</a>|
|[UseGeneralBudgetReservationPublicSectorAccountingRules](#UseGeneralBudgetReservationPublicSectorAccountingRules)||<a href="BudgetParametersEntity.md" target="_blank">Budgeting/BudgetParametersEntity</a>|
|[DoCompleteRegisterEntriesOnTransferFromFixedAssetsRU](#DoCompleteRegisterEntriesOnTransferFromFixedAssetsRU)||<a href="BudgetParametersEntity.md" target="_blank">Budgeting/BudgetParametersEntity</a>|
|[Relationship_LedgerJournalNameRelationshipId](#Relationship_LedgerJournalNameRelationshipId)||<a href="BudgetParametersEntity.md" target="_blank">Budgeting/BudgetParametersEntity</a>|
|[Relationship_LedgerPeriodAllocationCategoryRelationshipId](#Relationship_LedgerPeriodAllocationCategoryRelationshipId)||<a href="BudgetParametersEntity.md" target="_blank">Budgeting/BudgetParametersEntity</a>|
|[BackingTable_BudgetParametersRelationshipId](#BackingTable_BudgetParametersRelationshipId)||<a href="BudgetParametersEntity.md" target="_blank">Budgeting/BudgetParametersEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="BudgetParametersEntity.md" target="_blank">Budgeting/BudgetParametersEntity</a>|

### <a href=#AllocationKey name="AllocationKey">AllocationKey</a>

First included in: Budgeting/BudgetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllocationKey attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BudgetJournal name="BudgetJournal">BudgetJournal</a>

First included in: Budgeting/BudgetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetJournal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CheckRevenueBudgetForZeroBudgetBalances name="CheckRevenueBudgetForZeroBudgetBalances">CheckRevenueBudgetForZeroBudgetBalances</a>

First included in: Budgeting/BudgetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CheckRevenueBudgetForZeroBudgetBalances attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DoCompleteRegisterEntriesOnTransferFromDemandForecast name="DoCompleteRegisterEntriesOnTransferFromDemandForecast">DoCompleteRegisterEntriesOnTransferFromDemandForecast</a>

First included in: Budgeting/BudgetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DoCompleteRegisterEntriesOnTransferFromDemandForecast attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DoCompleteRegisterEntriesOnTransferFromFixedAssets name="DoCompleteRegisterEntriesOnTransferFromFixedAssets">DoCompleteRegisterEntriesOnTransferFromFixedAssets</a>

First included in: Budgeting/BudgetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DoCompleteRegisterEntriesOnTransferFromFixedAssets attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DoCompleteRegisterEntriesOnTransferFromProject name="DoCompleteRegisterEntriesOnTransferFromProject">DoCompleteRegisterEntriesOnTransferFromProject</a>

First included in: Budgeting/BudgetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DoCompleteRegisterEntriesOnTransferFromProject attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DoCompleteRegisterEntriesOnTransferFromSupplyForecast name="DoCompleteRegisterEntriesOnTransferFromSupplyForecast">DoCompleteRegisterEntriesOnTransferFromSupplyForecast</a>

First included in: Budgeting/BudgetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DoCompleteRegisterEntriesOnTransferFromSupplyForecast attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ID name="ID">ID</a>

First included in: Budgeting/BudgetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimePeriodForBudgetBalances name="TimePeriodForBudgetBalances">TimePeriodForBudgetBalances</a>

First included in: Budgeting/BudgetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimePeriodForBudgetBalances attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseFrenchPublicSectorAccountingRules name="UseFrenchPublicSectorAccountingRules">UseFrenchPublicSectorAccountingRules</a>

First included in: Budgeting/BudgetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseFrenchPublicSectorAccountingRules attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseRulesForBudgetTransfers name="UseRulesForBudgetTransfers">UseRulesForBudgetTransfers</a>

First included in: Budgeting/BudgetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseRulesForBudgetTransfers attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseGeneralBudgetReservationPublicSectorAccountingRules name="UseGeneralBudgetReservationPublicSectorAccountingRules">UseGeneralBudgetReservationPublicSectorAccountingRules</a>

First included in: Budgeting/BudgetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseGeneralBudgetReservationPublicSectorAccountingRules attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DoCompleteRegisterEntriesOnTransferFromFixedAssetsRU name="DoCompleteRegisterEntriesOnTransferFromFixedAssetsRU">DoCompleteRegisterEntriesOnTransferFromFixedAssetsRU</a>

First included in: Budgeting/BudgetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DoCompleteRegisterEntriesOnTransferFromFixedAssetsRU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerJournalNameRelationshipId name="Relationship_LedgerJournalNameRelationshipId">Relationship_LedgerJournalNameRelationshipId</a>

First included in: Budgeting/BudgetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerJournalNameRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_LedgerPeriodAllocationCategoryRelationshipId name="Relationship_LedgerPeriodAllocationCategoryRelationshipId">Relationship_LedgerPeriodAllocationCategoryRelationshipId</a>

First included in: Budgeting/BudgetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerPeriodAllocationCategoryRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_BudgetParametersRelationshipId name="BackingTable_BudgetParametersRelationshipId">BackingTable_BudgetParametersRelationshipId</a>

First included in: Budgeting/BudgetParametersEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_BudgetParametersRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Budget/Parameter/BudgetParameters.md" target="_blank">/core/operationsCommon/Tables/Finance/Budget/Parameter/BudgetParameters.cdm.json/BudgetParameters</a></td><td><a href="../../../Tables/Finance/Budget/Parameter/BudgetParameters.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: Budgeting/BudgetParametersEntity (this entity)  

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
