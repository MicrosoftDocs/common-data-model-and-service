---
title: BudgetControlConfigurationEntity in Budgeting - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/15/2020
ms.author: nebanfic
---

# Budget control configuration in Budgeting(BudgetControlConfigurationEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/Budgeting/BudgetControlConfigurationEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Budget control configuration</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[DefaultBudgetCycleTimeSpan](#DefaultBudgetCycleTimeSpan)||<a href="BudgetControlConfigurationEntity.md" target="_blank">Budgeting/BudgetControlConfigurationEntity</a>|
|[DefaultBudgetCycleTimeSpanFiscalCalendarId](#DefaultBudgetCycleTimeSpanFiscalCalendarId)||<a href="BudgetControlConfigurationEntity.md" target="_blank">Budgeting/BudgetControlConfigurationEntity</a>|
|[DefaultBudgetCycleTimeSpanName](#DefaultBudgetCycleTimeSpanName)||<a href="BudgetControlConfigurationEntity.md" target="_blank">Budgeting/BudgetControlConfigurationEntity</a>|
|[DefaultBudgetControlInterval](#DefaultBudgetControlInterval)||<a href="BudgetControlConfigurationEntity.md" target="_blank">Budgeting/BudgetControlConfigurationEntity</a>|
|[DefaultBudgetManager](#DefaultBudgetManager)||<a href="BudgetControlConfigurationEntity.md" target="_blank">Budgeting/BudgetControlConfigurationEntity</a>|
|[DefaultBudgetThresholdPercent](#DefaultBudgetThresholdPercent)||<a href="BudgetControlConfigurationEntity.md" target="_blank">Budgeting/BudgetControlConfigurationEntity</a>|
|[DimensionHierarchyAccountStructure](#DimensionHierarchyAccountStructure)||<a href="BudgetControlConfigurationEntity.md" target="_blank">Budgeting/BudgetControlConfigurationEntity</a>|
|[AccountStructure](#AccountStructure)||<a href="BudgetControlConfigurationEntity.md" target="_blank">Budgeting/BudgetControlConfigurationEntity</a>|
|[DisplayAMessageWhenExceedingBudgetThreshold](#DisplayAMessageWhenExceedingBudgetThreshold)||<a href="BudgetControlConfigurationEntity.md" target="_blank">Budgeting/BudgetControlConfigurationEntity</a>|
|[InUseBy](#InUseBy)||<a href="BudgetControlConfigurationEntity.md" target="_blank">Budgeting/BudgetControlConfigurationEntity</a>|
|[InUseSinceDateTime](#InUseSinceDateTime)||<a href="BudgetControlConfigurationEntity.md" target="_blank">Budgeting/BudgetControlConfigurationEntity</a>|
|[Status](#Status)||<a href="BudgetControlConfigurationEntity.md" target="_blank">Budgeting/BudgetControlConfigurationEntity</a>|
|[LegalEntityId](#LegalEntityId)||<a href="BudgetControlConfigurationEntity.md" target="_blank">Budgeting/BudgetControlConfigurationEntity</a>|
|[PrimaryLedger](#PrimaryLedger)||<a href="BudgetControlConfigurationEntity.md" target="_blank">Budgeting/BudgetControlConfigurationEntity</a>|
|[SumOriginalBudgetInBudgetFundsAvailableCalculation](#SumOriginalBudgetInBudgetFundsAvailableCalculation)||<a href="BudgetControlConfigurationEntity.md" target="_blank">Budgeting/BudgetControlConfigurationEntity</a>|
|[SumPreliminaryBudgetInBudgetFundsAvailableCalculation](#SumPreliminaryBudgetInBudgetFundsAvailableCalculation)||<a href="BudgetControlConfigurationEntity.md" target="_blank">Budgeting/BudgetControlConfigurationEntity</a>|
|[SumRevisionsInBudgetFundsAvailableCalculation](#SumRevisionsInBudgetFundsAvailableCalculation)||<a href="BudgetControlConfigurationEntity.md" target="_blank">Budgeting/BudgetControlConfigurationEntity</a>|
|[SumDraftRevisionsInBudgetFundsAvailableCalculation](#SumDraftRevisionsInBudgetFundsAvailableCalculation)||<a href="BudgetControlConfigurationEntity.md" target="_blank">Budgeting/BudgetControlConfigurationEntity</a>|
|[SumTransfersInBudgetFundsAvailableCalculation](#SumTransfersInBudgetFundsAvailableCalculation)||<a href="BudgetControlConfigurationEntity.md" target="_blank">Budgeting/BudgetControlConfigurationEntity</a>|
|[SumDraftTransfersInInBudgetFundsAvailableCalculation](#SumDraftTransfersInInBudgetFundsAvailableCalculation)||<a href="BudgetControlConfigurationEntity.md" target="_blank">Budgeting/BudgetControlConfigurationEntity</a>|
|[SumDraftTransfersOutInBudgetFundsAvailableCalculation](#SumDraftTransfersOutInBudgetFundsAvailableCalculation)||<a href="BudgetControlConfigurationEntity.md" target="_blank">Budgeting/BudgetControlConfigurationEntity</a>|
|[IncludeCarryforwardAmountsInBudgetFundsAvailableCalculation](#IncludeCarryforwardAmountsInBudgetFundsAvailableCalculation)||<a href="BudgetControlConfigurationEntity.md" target="_blank">Budgeting/BudgetControlConfigurationEntity</a>|
|[SubtractActualExpendituresInBudgetFundsAvailableCalculation](#SubtractActualExpendituresInBudgetFundsAvailableCalculation)||<a href="BudgetControlConfigurationEntity.md" target="_blank">Budgeting/BudgetControlConfigurationEntity</a>|
|[SubtractUnpostedActualExpendituresInBudgetFundsAvailableCalculation](#SubtractUnpostedActualExpendituresInBudgetFundsAvailableCalculation)||<a href="BudgetControlConfigurationEntity.md" target="_blank">Budgeting/BudgetControlConfigurationEntity</a>|
|[SubtractEncumbrancesInBudgetFundsAvailableCalculation](#SubtractEncumbrancesInBudgetFundsAvailableCalculation)||<a href="BudgetControlConfigurationEntity.md" target="_blank">Budgeting/BudgetControlConfigurationEntity</a>|
|[SubtractUnconfirmedEncumbrancesInBudgetFundsAvailableCalculation](#SubtractUnconfirmedEncumbrancesInBudgetFundsAvailableCalculation)||<a href="BudgetControlConfigurationEntity.md" target="_blank">Budgeting/BudgetControlConfigurationEntity</a>|
|[SubtractUnconfirmedEncumbranceReductionsInBudgetFundsAvailableCalculation](#SubtractUnconfirmedEncumbranceReductionsInBudgetFundsAvailableCalculation)||<a href="BudgetControlConfigurationEntity.md" target="_blank">Budgeting/BudgetControlConfigurationEntity</a>|
|[SubtractPreencumbrancesInBudgetFundsAvailableCalculation](#SubtractPreencumbrancesInBudgetFundsAvailableCalculation)||<a href="BudgetControlConfigurationEntity.md" target="_blank">Budgeting/BudgetControlConfigurationEntity</a>|
|[SubtractUnconfirmedPreencumbrancesInBudgetFundsAvailableCalculation](#SubtractUnconfirmedPreencumbrancesInBudgetFundsAvailableCalculation)||<a href="BudgetControlConfigurationEntity.md" target="_blank">Budgeting/BudgetControlConfigurationEntity</a>|
|[UseOnlyApportionedAmountInBudgetFundsAvailableCalculation](#UseOnlyApportionedAmountInBudgetFundsAvailableCalculation)||<a href="BudgetControlConfigurationEntity.md" target="_blank">Budgeting/BudgetControlConfigurationEntity</a>|
|[Relationship_LedgerEntityRelationshipId](#Relationship_LedgerEntityRelationshipId)||<a href="BudgetControlConfigurationEntity.md" target="_blank">Budgeting/BudgetControlConfigurationEntity</a>|
|[Relationship_SystemUserEntityDefaultBudgetManagerRelationshipId](#Relationship_SystemUserEntityDefaultBudgetManagerRelationshipId)||<a href="BudgetControlConfigurationEntity.md" target="_blank">Budgeting/BudgetControlConfigurationEntity</a>|
|[Relationship_BudgetCycleTimeSpanRelationshipId](#Relationship_BudgetCycleTimeSpanRelationshipId)||<a href="BudgetControlConfigurationEntity.md" target="_blank">Budgeting/BudgetControlConfigurationEntity</a>|
|[Relationship_LedgerAccountStructureEntityRelationshipId](#Relationship_LedgerAccountStructureEntityRelationshipId)||<a href="BudgetControlConfigurationEntity.md" target="_blank">Budgeting/BudgetControlConfigurationEntity</a>|
|[BackingTable_BudgetControlConfigurationRelationshipId](#BackingTable_BudgetControlConfigurationRelationshipId)||<a href="BudgetControlConfigurationEntity.md" target="_blank">Budgeting/BudgetControlConfigurationEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="BudgetControlConfigurationEntity.md" target="_blank">Budgeting/BudgetControlConfigurationEntity</a>|

### <a href=#DefaultBudgetCycleTimeSpan name="DefaultBudgetCycleTimeSpan">DefaultBudgetCycleTimeSpan</a>

First included in: Budgeting/BudgetControlConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultBudgetCycleTimeSpan attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultBudgetCycleTimeSpanFiscalCalendarId name="DefaultBudgetCycleTimeSpanFiscalCalendarId">DefaultBudgetCycleTimeSpanFiscalCalendarId</a>

First included in: Budgeting/BudgetControlConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Budget cycle time span fiscal calendar</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultBudgetCycleTimeSpanFiscalCalendarId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Budget cycle time span fiscal calendar</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultBudgetCycleTimeSpanName name="DefaultBudgetCycleTimeSpanName">DefaultBudgetCycleTimeSpanName</a>

First included in: Budgeting/BudgetControlConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Budget cycle time span name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultBudgetCycleTimeSpanName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Budget cycle time span name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultBudgetControlInterval name="DefaultBudgetControlInterval">DefaultBudgetControlInterval</a>

First included in: Budgeting/BudgetControlConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultBudgetControlInterval attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultBudgetManager name="DefaultBudgetManager">DefaultBudgetManager</a>

First included in: Budgeting/BudgetControlConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultBudgetManager attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultBudgetThresholdPercent name="DefaultBudgetThresholdPercent">DefaultBudgetThresholdPercent</a>

First included in: Budgeting/BudgetControlConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultBudgetThresholdPercent attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DimensionHierarchyAccountStructure name="DimensionHierarchyAccountStructure">DimensionHierarchyAccountStructure</a>

First included in: Budgeting/BudgetControlConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionHierarchyAccountStructure attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountStructure name="AccountStructure">AccountStructure</a>

First included in: Budgeting/BudgetControlConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Account structure</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountStructure attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Account structure</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DisplayAMessageWhenExceedingBudgetThreshold name="DisplayAMessageWhenExceedingBudgetThreshold">DisplayAMessageWhenExceedingBudgetThreshold</a>

First included in: Budgeting/BudgetControlConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisplayAMessageWhenExceedingBudgetThreshold attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InUseBy name="InUseBy">InUseBy</a>

First included in: Budgeting/BudgetControlConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InUseBy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InUseSinceDateTime name="InUseSinceDateTime">InUseSinceDateTime</a>

First included in: Budgeting/BudgetControlConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InUseSinceDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Status name="Status">Status</a>

First included in: Budgeting/BudgetControlConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Status attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Status</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LegalEntityId name="LegalEntityId">LegalEntityId</a>

First included in: Budgeting/BudgetControlConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LegalEntityId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryLedger name="PrimaryLedger">PrimaryLedger</a>

First included in: Budgeting/BudgetControlConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryLedger attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SumOriginalBudgetInBudgetFundsAvailableCalculation name="SumOriginalBudgetInBudgetFundsAvailableCalculation">SumOriginalBudgetInBudgetFundsAvailableCalculation</a>

First included in: Budgeting/BudgetControlConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sum original budget</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SumOriginalBudgetInBudgetFundsAvailableCalculation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sum original budget</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SumPreliminaryBudgetInBudgetFundsAvailableCalculation name="SumPreliminaryBudgetInBudgetFundsAvailableCalculation">SumPreliminaryBudgetInBudgetFundsAvailableCalculation</a>

First included in: Budgeting/BudgetControlConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sum preliminary budget</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SumPreliminaryBudgetInBudgetFundsAvailableCalculation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sum preliminary budget</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SumRevisionsInBudgetFundsAvailableCalculation name="SumRevisionsInBudgetFundsAvailableCalculation">SumRevisionsInBudgetFundsAvailableCalculation</a>

First included in: Budgeting/BudgetControlConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sum budget revisions</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SumRevisionsInBudgetFundsAvailableCalculation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sum budget revisions</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SumDraftRevisionsInBudgetFundsAvailableCalculation name="SumDraftRevisionsInBudgetFundsAvailableCalculation">SumDraftRevisionsInBudgetFundsAvailableCalculation</a>

First included in: Budgeting/BudgetControlConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sum draft budget revisions</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SumDraftRevisionsInBudgetFundsAvailableCalculation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sum draft budget revisions</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SumTransfersInBudgetFundsAvailableCalculation name="SumTransfersInBudgetFundsAvailableCalculation">SumTransfersInBudgetFundsAvailableCalculation</a>

First included in: Budgeting/BudgetControlConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sum budget transfers</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SumTransfersInBudgetFundsAvailableCalculation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sum budget transfers</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SumDraftTransfersInInBudgetFundsAvailableCalculation name="SumDraftTransfersInInBudgetFundsAvailableCalculation">SumDraftTransfersInInBudgetFundsAvailableCalculation</a>

First included in: Budgeting/BudgetControlConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sum draft budget transfers in</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SumDraftTransfersInInBudgetFundsAvailableCalculation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sum draft budget transfers in</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SumDraftTransfersOutInBudgetFundsAvailableCalculation name="SumDraftTransfersOutInBudgetFundsAvailableCalculation">SumDraftTransfersOutInBudgetFundsAvailableCalculation</a>

First included in: Budgeting/BudgetControlConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sum draft budget transfers out</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SumDraftTransfersOutInBudgetFundsAvailableCalculation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sum draft budget transfers out</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IncludeCarryforwardAmountsInBudgetFundsAvailableCalculation name="IncludeCarryforwardAmountsInBudgetFundsAvailableCalculation">IncludeCarryforwardAmountsInBudgetFundsAvailableCalculation</a>

First included in: Budgeting/BudgetControlConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Include carry-forward amounts</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IncludeCarryforwardAmountsInBudgetFundsAvailableCalculation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Include carry-forward amounts</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SubtractActualExpendituresInBudgetFundsAvailableCalculation name="SubtractActualExpendituresInBudgetFundsAvailableCalculation">SubtractActualExpendituresInBudgetFundsAvailableCalculation</a>

First included in: Budgeting/BudgetControlConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Subtract actual expenditures</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubtractActualExpendituresInBudgetFundsAvailableCalculation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Subtract actual expenditures</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SubtractUnpostedActualExpendituresInBudgetFundsAvailableCalculation name="SubtractUnpostedActualExpendituresInBudgetFundsAvailableCalculation">SubtractUnpostedActualExpendituresInBudgetFundsAvailableCalculation</a>

First included in: Budgeting/BudgetControlConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Subtract unposted actual expenditures</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubtractUnpostedActualExpendituresInBudgetFundsAvailableCalculation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Subtract unposted actual expenditures</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SubtractEncumbrancesInBudgetFundsAvailableCalculation name="SubtractEncumbrancesInBudgetFundsAvailableCalculation">SubtractEncumbrancesInBudgetFundsAvailableCalculation</a>

First included in: Budgeting/BudgetControlConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Subtract budget reservations for encumbrances</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubtractEncumbrancesInBudgetFundsAvailableCalculation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Subtract budget reservations for encumbrances</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SubtractUnconfirmedEncumbrancesInBudgetFundsAvailableCalculation name="SubtractUnconfirmedEncumbrancesInBudgetFundsAvailableCalculation">SubtractUnconfirmedEncumbrancesInBudgetFundsAvailableCalculation</a>

First included in: Budgeting/BudgetControlConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Subtract budget reservations for unconfirmed encumbrances</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubtractUnconfirmedEncumbrancesInBudgetFundsAvailableCalculation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Subtract budget reservations for unconfirmed encumbrances</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SubtractUnconfirmedEncumbranceReductionsInBudgetFundsAvailableCalculation name="SubtractUnconfirmedEncumbranceReductionsInBudgetFundsAvailableCalculation">SubtractUnconfirmedEncumbranceReductionsInBudgetFundsAvailableCalculation</a>

First included in: Budgeting/BudgetControlConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Subtract reduction to budget reservations for unconfirmed encumbrances</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubtractUnconfirmedEncumbranceReductionsInBudgetFundsAvailableCalculation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Subtract reduction to budget reservations for unconfirmed encumbrances</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SubtractPreencumbrancesInBudgetFundsAvailableCalculation name="SubtractPreencumbrancesInBudgetFundsAvailableCalculation">SubtractPreencumbrancesInBudgetFundsAvailableCalculation</a>

First included in: Budgeting/BudgetControlConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Subtract budget reservations for pre-encumbrances</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubtractPreencumbrancesInBudgetFundsAvailableCalculation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Subtract budget reservations for pre-encumbrances</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SubtractUnconfirmedPreencumbrancesInBudgetFundsAvailableCalculation name="SubtractUnconfirmedPreencumbrancesInBudgetFundsAvailableCalculation">SubtractUnconfirmedPreencumbrancesInBudgetFundsAvailableCalculation</a>

First included in: Budgeting/BudgetControlConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Subtract budget reservations for unconfirmed pre-encumbrances</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubtractUnconfirmedPreencumbrancesInBudgetFundsAvailableCalculation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Subtract budget reservations for unconfirmed pre-encumbrances</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseOnlyApportionedAmountInBudgetFundsAvailableCalculation name="UseOnlyApportionedAmountInBudgetFundsAvailableCalculation">UseOnlyApportionedAmountInBudgetFundsAvailableCalculation</a>

First included in: Budgeting/BudgetControlConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseOnlyApportionedAmountInBudgetFundsAvailableCalculation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerEntityRelationshipId name="Relationship_LedgerEntityRelationshipId">Relationship_LedgerEntityRelationshipId</a>

First included in: Budgeting/BudgetControlConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_SystemUserEntityDefaultBudgetManagerRelationshipId name="Relationship_SystemUserEntityDefaultBudgetManagerRelationshipId">Relationship_SystemUserEntityDefaultBudgetManagerRelationshipId</a>

First included in: Budgeting/BudgetControlConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SystemUserEntityDefaultBudgetManagerRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_BudgetCycleTimeSpanRelationshipId name="Relationship_BudgetCycleTimeSpanRelationshipId">Relationship_BudgetCycleTimeSpanRelationshipId</a>

First included in: Budgeting/BudgetControlConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BudgetCycleTimeSpanRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_LedgerAccountStructureEntityRelationshipId name="Relationship_LedgerAccountStructureEntityRelationshipId">Relationship_LedgerAccountStructureEntityRelationshipId</a>

First included in: Budgeting/BudgetControlConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerAccountStructureEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_BudgetControlConfigurationRelationshipId name="BackingTable_BudgetControlConfigurationRelationshipId">BackingTable_BudgetControlConfigurationRelationshipId</a>

First included in: Budgeting/BudgetControlConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_BudgetControlConfigurationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Budget/Group/BudgetControlConfiguration.md" target="_blank">/core/operationsCommon/Tables/Finance/Budget/Group/BudgetControlConfiguration.cdm.json/BudgetControlConfiguration</a></td><td><a href="../../../Tables/Finance/Budget/Group/BudgetControlConfiguration.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: Budgeting/BudgetControlConfigurationEntity (this entity)  

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
