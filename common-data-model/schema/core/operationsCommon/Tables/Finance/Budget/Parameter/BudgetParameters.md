---
title: BudgetParameters - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# BudgetParameters

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Budget/Parameter/BudgetParameters.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BudgetParameters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="BudgetParameters.md" target="_blank">Parameter/BudgetParameters</a>|
|[CashFlowForecastPeriodAllocationKey](#CashFlowForecastPeriodAllocationKey)||<a href="BudgetParameters.md" target="_blank">Parameter/BudgetParameters</a>|
|[CheckRevenueBudgetBalanceInterval](#CheckRevenueBudgetBalanceInterval)||<a href="BudgetParameters.md" target="_blank">Parameter/BudgetParameters</a>|
|[CheckRevenueBudgetBalanceOption](#CheckRevenueBudgetBalanceOption)||<a href="BudgetParameters.md" target="_blank">Parameter/BudgetParameters</a>|
|[IsAllowTransferRuleEnabled](#IsAllowTransferRuleEnabled)||<a href="BudgetParameters.md" target="_blank">Parameter/BudgetParameters</a>|
|[IsAssetBudgetTransCreateAsCompleted](#IsAssetBudgetTransCreateAsCompleted)||<a href="BudgetParameters.md" target="_blank">Parameter/BudgetParameters</a>|
|[IsDemandFcstBudgetTransCreateAsCompleted](#IsDemandFcstBudgetTransCreateAsCompleted)||<a href="BudgetParameters.md" target="_blank">Parameter/BudgetParameters</a>|
|[IsFrenchRegulatoryEnabled](#IsFrenchRegulatoryEnabled)||<a href="BudgetParameters.md" target="_blank">Parameter/BudgetParameters</a>|
|[IsProjectBudgetTransCreateAsCompleted](#IsProjectBudgetTransCreateAsCompleted)||<a href="BudgetParameters.md" target="_blank">Parameter/BudgetParameters</a>|
|[IsSupplyFcstBudgetTransCreateAsCompleted](#IsSupplyFcstBudgetTransCreateAsCompleted)||<a href="BudgetParameters.md" target="_blank">Parameter/BudgetParameters</a>|
|[Key](#Key)||<a href="BudgetParameters.md" target="_blank">Parameter/BudgetParameters</a>|
|[LedgerJournalName](#LedgerJournalName)||<a href="BudgetParameters.md" target="_blank">Parameter/BudgetParameters</a>|
|[SumPreliminaryBudget](#SumPreliminaryBudget)||<a href="BudgetParameters.md" target="_blank">Parameter/BudgetParameters</a>|
|[UseOnlyApportionment](#UseOnlyApportionment)||<a href="BudgetParameters.md" target="_blank">Parameter/BudgetParameters</a>|
|[IsBudgetReservationEnabled](#IsBudgetReservationEnabled)||<a href="BudgetParameters.md" target="_blank">Parameter/BudgetParameters</a>|
|[PreventIncreaseToCarryForwardEncumbrance](#PreventIncreaseToCarryForwardEncumbrance)||<a href="BudgetParameters.md" target="_blank">Parameter/BudgetParameters</a>|
|[DisplayLegacyBudgetAnalysis](#DisplayLegacyBudgetAnalysis)||<a href="BudgetParameters.md" target="_blank">Parameter/BudgetParameters</a>|
|[IsAssetBudgetTransCreateAsCompleted_RU](#IsAssetBudgetTransCreateAsCompleted_RU)||<a href="BudgetParameters.md" target="_blank">Parameter/BudgetParameters</a>|
|[UseSessionDateForAccounting](#UseSessionDateForAccounting)||<a href="BudgetParameters.md" target="_blank">Parameter/BudgetParameters</a>|
|[PSNBudgetModelDataAreaId](#PSNBudgetModelDataAreaId)||<a href="BudgetParameters.md" target="_blank">Parameter/BudgetParameters</a>|
|[PSNBudgetModelId](#PSNBudgetModelId)||<a href="BudgetParameters.md" target="_blank">Parameter/BudgetParameters</a>|
|[PSNBudgetTransactionCode](#PSNBudgetTransactionCode)||<a href="BudgetParameters.md" target="_blank">Parameter/BudgetParameters</a>|
|[PSNAllowPriorYearCorrection](#PSNAllowPriorYearCorrection)||<a href="BudgetParameters.md" target="_blank">Parameter/BudgetParameters</a>|
|[DataAreaId](#DataAreaId)||<a href="BudgetParameters.md" target="_blank">Parameter/BudgetParameters</a>|
|[Relationship_LedgerAllocateKeyRelationshipId](#Relationship_LedgerAllocateKeyRelationshipId)||<a href="BudgetParameters.md" target="_blank">Parameter/BudgetParameters</a>|
|[Relationship_LedgerJournalNameRelationshipId](#Relationship_LedgerJournalNameRelationshipId)||<a href="BudgetParameters.md" target="_blank">Parameter/BudgetParameters</a>|
|[Relationship_BudgetTransactionCodeRelationshipId](#Relationship_BudgetTransactionCodeRelationshipId)||<a href="BudgetParameters.md" target="_blank">Parameter/BudgetParameters</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="BudgetParameters.md" target="_blank">Parameter/BudgetParameters</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Parameter/BudgetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BudgetParameters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CashFlowForecastPeriodAllocationKey name="CashFlowForecastPeriodAllocationKey">CashFlowForecastPeriodAllocationKey</a>

First included in: Parameter/BudgetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashFlowForecastPeriodAllocationKey attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CheckRevenueBudgetBalanceInterval name="CheckRevenueBudgetBalanceInterval">CheckRevenueBudgetBalanceInterval</a>

First included in: Parameter/BudgetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CheckRevenueBudgetBalanceInterval attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CheckRevenueBudgetBalanceOption name="CheckRevenueBudgetBalanceOption">CheckRevenueBudgetBalanceOption</a>

First included in: Parameter/BudgetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CheckRevenueBudgetBalanceOption attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsAllowTransferRuleEnabled name="IsAllowTransferRuleEnabled">IsAllowTransferRuleEnabled</a>

First included in: Parameter/BudgetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsAllowTransferRuleEnabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsAssetBudgetTransCreateAsCompleted name="IsAssetBudgetTransCreateAsCompleted">IsAssetBudgetTransCreateAsCompleted</a>

First included in: Parameter/BudgetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsAssetBudgetTransCreateAsCompleted attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsDemandFcstBudgetTransCreateAsCompleted name="IsDemandFcstBudgetTransCreateAsCompleted">IsDemandFcstBudgetTransCreateAsCompleted</a>

First included in: Parameter/BudgetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDemandFcstBudgetTransCreateAsCompleted attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsFrenchRegulatoryEnabled name="IsFrenchRegulatoryEnabled">IsFrenchRegulatoryEnabled</a>

First included in: Parameter/BudgetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsFrenchRegulatoryEnabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsProjectBudgetTransCreateAsCompleted name="IsProjectBudgetTransCreateAsCompleted">IsProjectBudgetTransCreateAsCompleted</a>

First included in: Parameter/BudgetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProjectBudgetTransCreateAsCompleted attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsSupplyFcstBudgetTransCreateAsCompleted name="IsSupplyFcstBudgetTransCreateAsCompleted">IsSupplyFcstBudgetTransCreateAsCompleted</a>

First included in: Parameter/BudgetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSupplyFcstBudgetTransCreateAsCompleted attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Key name="Key">Key</a>

First included in: Parameter/BudgetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Key attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#LedgerJournalName name="LedgerJournalName">LedgerJournalName</a>

First included in: Parameter/BudgetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerJournalName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SumPreliminaryBudget name="SumPreliminaryBudget">SumPreliminaryBudget</a>

First included in: Parameter/BudgetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SumPreliminaryBudget attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#UseOnlyApportionment name="UseOnlyApportionment">UseOnlyApportionment</a>

First included in: Parameter/BudgetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseOnlyApportionment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsBudgetReservationEnabled name="IsBudgetReservationEnabled">IsBudgetReservationEnabled</a>

First included in: Parameter/BudgetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsBudgetReservationEnabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PreventIncreaseToCarryForwardEncumbrance name="PreventIncreaseToCarryForwardEncumbrance">PreventIncreaseToCarryForwardEncumbrance</a>

First included in: Parameter/BudgetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PreventIncreaseToCarryForwardEncumbrance attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DisplayLegacyBudgetAnalysis name="DisplayLegacyBudgetAnalysis">DisplayLegacyBudgetAnalysis</a>

First included in: Parameter/BudgetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisplayLegacyBudgetAnalysis attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsAssetBudgetTransCreateAsCompleted_RU name="IsAssetBudgetTransCreateAsCompleted_RU">IsAssetBudgetTransCreateAsCompleted_RU</a>

First included in: Parameter/BudgetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsAssetBudgetTransCreateAsCompleted_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#UseSessionDateForAccounting name="UseSessionDateForAccounting">UseSessionDateForAccounting</a>

First included in: Parameter/BudgetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseSessionDateForAccounting attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PSNBudgetModelDataAreaId name="PSNBudgetModelDataAreaId">PSNBudgetModelDataAreaId</a>

First included in: Parameter/BudgetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PSNBudgetModelDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PSNBudgetModelId name="PSNBudgetModelId">PSNBudgetModelId</a>

First included in: Parameter/BudgetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PSNBudgetModelId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PSNBudgetTransactionCode name="PSNBudgetTransactionCode">PSNBudgetTransactionCode</a>

First included in: Parameter/BudgetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PSNBudgetTransactionCode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PSNAllowPriorYearCorrection name="PSNAllowPriorYearCorrection">PSNAllowPriorYearCorrection</a>

First included in: Parameter/BudgetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PSNAllowPriorYearCorrection attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Parameter/BudgetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerAllocateKeyRelationshipId name="Relationship_LedgerAllocateKeyRelationshipId">Relationship_LedgerAllocateKeyRelationshipId</a>

First included in: Parameter/BudgetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerAllocateKeyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Ledger/Group/LedgerAllocateKey.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Group/LedgerAllocateKey.cdm.json/LedgerAllocateKey</a></td><td><a href="../../Ledger/Group/LedgerAllocateKey.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerJournalNameRelationshipId name="Relationship_LedgerJournalNameRelationshipId">Relationship_LedgerJournalNameRelationshipId</a>

First included in: Parameter/BudgetParameters (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../AccountingFoundation/Group/LedgerJournalName.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountingFoundation/Group/LedgerJournalName.cdm.json/LedgerJournalName</a></td><td><a href="../../AccountingFoundation/Group/LedgerJournalName.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BudgetTransactionCodeRelationshipId name="Relationship_BudgetTransactionCodeRelationshipId">Relationship_BudgetTransactionCodeRelationshipId</a>

First included in: Parameter/BudgetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BudgetTransactionCodeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/BudgetTransactionCode.md" target="_blank">/core/operationsCommon/Tables/Finance/Budget/Group/BudgetTransactionCode.cdm.json/BudgetTransactionCode</a></td><td><a href="../Group/BudgetTransactionCode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Parameter/BudgetParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CompanyRelationshipId attribute are listed below.</summary>

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
