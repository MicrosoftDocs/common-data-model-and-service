---
title: EximParameters_IN - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# EximParameters_IN

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Finance/ExportImportIndia/Parameter/EximParameters_IN.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[EximParameters_IN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="EximParameters_IN.md" target="_blank">Parameter/EximParameters_IN</a>|
|[AAAllowPurchase](#AAAllowPurchase)||<a href="EximParameters_IN.md" target="_blank">Parameter/EximParameters_IN</a>|
|[AAAllowSale](#AAAllowSale)||<a href="EximParameters_IN.md" target="_blank">Parameter/EximParameters_IN</a>|
|[AAAssessableValuePct](#AAAssessableValuePct)||<a href="EximParameters_IN.md" target="_blank">Parameter/EximParameters_IN</a>|
|[AABenefitLedgerDimension](#AABenefitLedgerDimension)||<a href="EximParameters_IN.md" target="_blank">Parameter/EximParameters_IN</a>|
|[AAExportPeriod](#AAExportPeriod)||<a href="EximParameters_IN.md" target="_blank">Parameter/EximParameters_IN</a>|
|[AAExportPeriodUnit](#AAExportPeriodUnit)||<a href="EximParameters_IN.md" target="_blank">Parameter/EximParameters_IN</a>|
|[AAImportPeriod](#AAImportPeriod)||<a href="EximParameters_IN.md" target="_blank">Parameter/EximParameters_IN</a>|
|[AAImportPeriodUnit](#AAImportPeriodUnit)||<a href="EximParameters_IN.md" target="_blank">Parameter/EximParameters_IN</a>|
|[AAPostVoucher](#AAPostVoucher)||<a href="EximParameters_IN.md" target="_blank">Parameter/EximParameters_IN</a>|
|[ActivateAA](#ActivateAA)||<a href="EximParameters_IN.md" target="_blank">Parameter/EximParameters_IN</a>|
|[ActivateDEPB](#ActivateDEPB)||<a href="EximParameters_IN.md" target="_blank">Parameter/EximParameters_IN</a>|
|[ActivateDFIA](#ActivateDFIA)||<a href="EximParameters_IN.md" target="_blank">Parameter/EximParameters_IN</a>|
|[ActivateDutyDrawback](#ActivateDutyDrawback)||<a href="EximParameters_IN.md" target="_blank">Parameter/EximParameters_IN</a>|
|[ActivateEPCG](#ActivateEPCG)||<a href="EximParameters_IN.md" target="_blank">Parameter/EximParameters_IN</a>|
|[DBKBenefitLedgerDimension](#DBKBenefitLedgerDimension)||<a href="EximParameters_IN.md" target="_blank">Parameter/EximParameters_IN</a>|
|[DBKMinAmount](#DBKMinAmount)||<a href="EximParameters_IN.md" target="_blank">Parameter/EximParameters_IN</a>|
|[DBKMinPercent](#DBKMinPercent)||<a href="EximParameters_IN.md" target="_blank">Parameter/EximParameters_IN</a>|
|[DBKReceivableLedgerDimension](#DBKReceivableLedgerDimension)||<a href="EximParameters_IN.md" target="_blank">Parameter/EximParameters_IN</a>|
|[DEPBBenefitLedgerDimension](#DEPBBenefitLedgerDimension)||<a href="EximParameters_IN.md" target="_blank">Parameter/EximParameters_IN</a>|
|[DEPBImportPeriod](#DEPBImportPeriod)||<a href="EximParameters_IN.md" target="_blank">Parameter/EximParameters_IN</a>|
|[DEPBImportPeriodUnit](#DEPBImportPeriodUnit)||<a href="EximParameters_IN.md" target="_blank">Parameter/EximParameters_IN</a>|
|[DEPBMarketValuePct](#DEPBMarketValuePct)||<a href="EximParameters_IN.md" target="_blank">Parameter/EximParameters_IN</a>|
|[DFIAAllowPurchase](#DFIAAllowPurchase)||<a href="EximParameters_IN.md" target="_blank">Parameter/EximParameters_IN</a>|
|[DFIAAllowSale](#DFIAAllowSale)||<a href="EximParameters_IN.md" target="_blank">Parameter/EximParameters_IN</a>|
|[DFIAAssessableValuePct](#DFIAAssessableValuePct)||<a href="EximParameters_IN.md" target="_blank">Parameter/EximParameters_IN</a>|
|[DFIABenefitLedgerDimension](#DFIABenefitLedgerDimension)||<a href="EximParameters_IN.md" target="_blank">Parameter/EximParameters_IN</a>|
|[DFIAExportPeriod](#DFIAExportPeriod)||<a href="EximParameters_IN.md" target="_blank">Parameter/EximParameters_IN</a>|
|[DFIAExportPeriodUnit](#DFIAExportPeriodUnit)||<a href="EximParameters_IN.md" target="_blank">Parameter/EximParameters_IN</a>|
|[DFIAImportPeriod](#DFIAImportPeriod)||<a href="EximParameters_IN.md" target="_blank">Parameter/EximParameters_IN</a>|
|[DFIAImportPeriodUnit](#DFIAImportPeriodUnit)||<a href="EximParameters_IN.md" target="_blank">Parameter/EximParameters_IN</a>|
|[DFIAPostVoucher](#DFIAPostVoucher)||<a href="EximParameters_IN.md" target="_blank">Parameter/EximParameters_IN</a>|
|[EPCGCIFFactor](#EPCGCIFFactor)||<a href="EximParameters_IN.md" target="_blank">Parameter/EximParameters_IN</a>|
|[EPCGEnableTechUpgrade](#EPCGEnableTechUpgrade)||<a href="EximParameters_IN.md" target="_blank">Parameter/EximParameters_IN</a>|
|[EPCGExportObligationBasis](#EPCGExportObligationBasis)||<a href="EximParameters_IN.md" target="_blank">Parameter/EximParameters_IN</a>|
|[EPCGExportPeriod](#EPCGExportPeriod)||<a href="EximParameters_IN.md" target="_blank">Parameter/EximParameters_IN</a>|
|[EPCGExportPeriodUnit](#EPCGExportPeriodUnit)||<a href="EximParameters_IN.md" target="_blank">Parameter/EximParameters_IN</a>|
|[EPCGImportPeriod](#EPCGImportPeriod)||<a href="EximParameters_IN.md" target="_blank">Parameter/EximParameters_IN</a>|
|[EPCGImportPeriodUnit](#EPCGImportPeriodUnit)||<a href="EximParameters_IN.md" target="_blank">Parameter/EximParameters_IN</a>|
|[EPCGMaxUtilizationPct](#EPCGMaxUtilizationPct)||<a href="EximParameters_IN.md" target="_blank">Parameter/EximParameters_IN</a>|
|[EPCGTechUpgradeMinExportPct](#EPCGTechUpgradeMinExportPct)||<a href="EximParameters_IN.md" target="_blank">Parameter/EximParameters_IN</a>|
|[EPCGTechUpgradeMinPeriod](#EPCGTechUpgradeMinPeriod)||<a href="EximParameters_IN.md" target="_blank">Parameter/EximParameters_IN</a>|
|[EPCGTechUpgradePeriodUnit](#EPCGTechUpgradePeriodUnit)||<a href="EximParameters_IN.md" target="_blank">Parameter/EximParameters_IN</a>|
|[EPCGUseCustomsExchRate](#EPCGUseCustomsExchRate)||<a href="EximParameters_IN.md" target="_blank">Parameter/EximParameters_IN</a>|
|[Key](#Key)||<a href="EximParameters_IN.md" target="_blank">Parameter/EximParameters_IN</a>|
|[DataAreaId](#DataAreaId)||<a href="EximParameters_IN.md" target="_blank">Parameter/EximParameters_IN</a>|
|[Relationship_AABenefitLedgerDimensionRelationshipId](#Relationship_AABenefitLedgerDimensionRelationshipId)||<a href="EximParameters_IN.md" target="_blank">Parameter/EximParameters_IN</a>|
|[Relationship_DBKBenefitLedgerDimensionRelationshipId](#Relationship_DBKBenefitLedgerDimensionRelationshipId)||<a href="EximParameters_IN.md" target="_blank">Parameter/EximParameters_IN</a>|
|[Relationship_DBKReceivableLedgerDimensionRelationshipId](#Relationship_DBKReceivableLedgerDimensionRelationshipId)||<a href="EximParameters_IN.md" target="_blank">Parameter/EximParameters_IN</a>|
|[Relationship_DEPBBenefitLedgerDimensionRelationshipId](#Relationship_DEPBBenefitLedgerDimensionRelationshipId)||<a href="EximParameters_IN.md" target="_blank">Parameter/EximParameters_IN</a>|
|[Relationship_DFIABenefitLedgerDimensionRelationshipId](#Relationship_DFIABenefitLedgerDimensionRelationshipId)||<a href="EximParameters_IN.md" target="_blank">Parameter/EximParameters_IN</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="EximParameters_IN.md" target="_blank">Parameter/EximParameters_IN</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Parameter/EximParameters_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[EximParameters_IN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AAAllowPurchase name="AAAllowPurchase">AAAllowPurchase</a>

First included in: Parameter/EximParameters_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AAAllowPurchase attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AAAllowSale name="AAAllowSale">AAAllowSale</a>

First included in: Parameter/EximParameters_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AAAllowSale attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AAAssessableValuePct name="AAAssessableValuePct">AAAssessableValuePct</a>

First included in: Parameter/EximParameters_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AAAssessableValuePct attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#AABenefitLedgerDimension name="AABenefitLedgerDimension">AABenefitLedgerDimension</a>

First included in: Parameter/EximParameters_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AABenefitLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AAExportPeriod name="AAExportPeriod">AAExportPeriod</a>

First included in: Parameter/EximParameters_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AAExportPeriod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AAExportPeriodUnit name="AAExportPeriodUnit">AAExportPeriodUnit</a>

First included in: Parameter/EximParameters_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AAExportPeriodUnit attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AAImportPeriod name="AAImportPeriod">AAImportPeriod</a>

First included in: Parameter/EximParameters_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AAImportPeriod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AAImportPeriodUnit name="AAImportPeriodUnit">AAImportPeriodUnit</a>

First included in: Parameter/EximParameters_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AAImportPeriodUnit attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AAPostVoucher name="AAPostVoucher">AAPostVoucher</a>

First included in: Parameter/EximParameters_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AAPostVoucher attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ActivateAA name="ActivateAA">ActivateAA</a>

First included in: Parameter/EximParameters_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActivateAA attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ActivateDEPB name="ActivateDEPB">ActivateDEPB</a>

First included in: Parameter/EximParameters_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActivateDEPB attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ActivateDFIA name="ActivateDFIA">ActivateDFIA</a>

First included in: Parameter/EximParameters_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActivateDFIA attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ActivateDutyDrawback name="ActivateDutyDrawback">ActivateDutyDrawback</a>

First included in: Parameter/EximParameters_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActivateDutyDrawback attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ActivateEPCG name="ActivateEPCG">ActivateEPCG</a>

First included in: Parameter/EximParameters_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActivateEPCG attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DBKBenefitLedgerDimension name="DBKBenefitLedgerDimension">DBKBenefitLedgerDimension</a>

First included in: Parameter/EximParameters_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DBKBenefitLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DBKMinAmount name="DBKMinAmount">DBKMinAmount</a>

First included in: Parameter/EximParameters_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DBKMinAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DBKMinPercent name="DBKMinPercent">DBKMinPercent</a>

First included in: Parameter/EximParameters_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DBKMinPercent attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DBKReceivableLedgerDimension name="DBKReceivableLedgerDimension">DBKReceivableLedgerDimension</a>

First included in: Parameter/EximParameters_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DBKReceivableLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DEPBBenefitLedgerDimension name="DEPBBenefitLedgerDimension">DEPBBenefitLedgerDimension</a>

First included in: Parameter/EximParameters_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DEPBBenefitLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DEPBImportPeriod name="DEPBImportPeriod">DEPBImportPeriod</a>

First included in: Parameter/EximParameters_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DEPBImportPeriod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DEPBImportPeriodUnit name="DEPBImportPeriodUnit">DEPBImportPeriodUnit</a>

First included in: Parameter/EximParameters_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DEPBImportPeriodUnit attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DEPBMarketValuePct name="DEPBMarketValuePct">DEPBMarketValuePct</a>

First included in: Parameter/EximParameters_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DEPBMarketValuePct attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DFIAAllowPurchase name="DFIAAllowPurchase">DFIAAllowPurchase</a>

First included in: Parameter/EximParameters_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DFIAAllowPurchase attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DFIAAllowSale name="DFIAAllowSale">DFIAAllowSale</a>

First included in: Parameter/EximParameters_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DFIAAllowSale attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DFIAAssessableValuePct name="DFIAAssessableValuePct">DFIAAssessableValuePct</a>

First included in: Parameter/EximParameters_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DFIAAssessableValuePct attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DFIABenefitLedgerDimension name="DFIABenefitLedgerDimension">DFIABenefitLedgerDimension</a>

First included in: Parameter/EximParameters_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DFIABenefitLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DFIAExportPeriod name="DFIAExportPeriod">DFIAExportPeriod</a>

First included in: Parameter/EximParameters_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DFIAExportPeriod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DFIAExportPeriodUnit name="DFIAExportPeriodUnit">DFIAExportPeriodUnit</a>

First included in: Parameter/EximParameters_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DFIAExportPeriodUnit attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DFIAImportPeriod name="DFIAImportPeriod">DFIAImportPeriod</a>

First included in: Parameter/EximParameters_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DFIAImportPeriod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DFIAImportPeriodUnit name="DFIAImportPeriodUnit">DFIAImportPeriodUnit</a>

First included in: Parameter/EximParameters_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DFIAImportPeriodUnit attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DFIAPostVoucher name="DFIAPostVoucher">DFIAPostVoucher</a>

First included in: Parameter/EximParameters_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DFIAPostVoucher attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EPCGCIFFactor name="EPCGCIFFactor">EPCGCIFFactor</a>

First included in: Parameter/EximParameters_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EPCGCIFFactor attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#EPCGEnableTechUpgrade name="EPCGEnableTechUpgrade">EPCGEnableTechUpgrade</a>

First included in: Parameter/EximParameters_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EPCGEnableTechUpgrade attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EPCGExportObligationBasis name="EPCGExportObligationBasis">EPCGExportObligationBasis</a>

First included in: Parameter/EximParameters_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EPCGExportObligationBasis attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EPCGExportPeriod name="EPCGExportPeriod">EPCGExportPeriod</a>

First included in: Parameter/EximParameters_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EPCGExportPeriod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EPCGExportPeriodUnit name="EPCGExportPeriodUnit">EPCGExportPeriodUnit</a>

First included in: Parameter/EximParameters_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EPCGExportPeriodUnit attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EPCGImportPeriod name="EPCGImportPeriod">EPCGImportPeriod</a>

First included in: Parameter/EximParameters_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EPCGImportPeriod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EPCGImportPeriodUnit name="EPCGImportPeriodUnit">EPCGImportPeriodUnit</a>

First included in: Parameter/EximParameters_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EPCGImportPeriodUnit attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EPCGMaxUtilizationPct name="EPCGMaxUtilizationPct">EPCGMaxUtilizationPct</a>

First included in: Parameter/EximParameters_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EPCGMaxUtilizationPct attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#EPCGTechUpgradeMinExportPct name="EPCGTechUpgradeMinExportPct">EPCGTechUpgradeMinExportPct</a>

First included in: Parameter/EximParameters_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EPCGTechUpgradeMinExportPct attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#EPCGTechUpgradeMinPeriod name="EPCGTechUpgradeMinPeriod">EPCGTechUpgradeMinPeriod</a>

First included in: Parameter/EximParameters_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EPCGTechUpgradeMinPeriod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EPCGTechUpgradePeriodUnit name="EPCGTechUpgradePeriodUnit">EPCGTechUpgradePeriodUnit</a>

First included in: Parameter/EximParameters_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EPCGTechUpgradePeriodUnit attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EPCGUseCustomsExchRate name="EPCGUseCustomsExchRate">EPCGUseCustomsExchRate</a>

First included in: Parameter/EximParameters_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EPCGUseCustomsExchRate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Key name="Key">Key</a>

First included in: Parameter/EximParameters_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Key attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Parameter/EximParameters_IN (this entity)  

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

### <a href=#Relationship_AABenefitLedgerDimensionRelationshipId name="Relationship_AABenefitLedgerDimensionRelationshipId">Relationship_AABenefitLedgerDimensionRelationshipId</a>

First included in: Parameter/EximParameters_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AABenefitLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DBKBenefitLedgerDimensionRelationshipId name="Relationship_DBKBenefitLedgerDimensionRelationshipId">Relationship_DBKBenefitLedgerDimensionRelationshipId</a>

First included in: Parameter/EximParameters_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DBKBenefitLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DBKReceivableLedgerDimensionRelationshipId name="Relationship_DBKReceivableLedgerDimensionRelationshipId">Relationship_DBKReceivableLedgerDimensionRelationshipId</a>

First included in: Parameter/EximParameters_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DBKReceivableLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DEPBBenefitLedgerDimensionRelationshipId name="Relationship_DEPBBenefitLedgerDimensionRelationshipId">Relationship_DEPBBenefitLedgerDimensionRelationshipId</a>

First included in: Parameter/EximParameters_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DEPBBenefitLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DFIABenefitLedgerDimensionRelationshipId name="Relationship_DFIABenefitLedgerDimensionRelationshipId">Relationship_DFIABenefitLedgerDimensionRelationshipId</a>

First included in: Parameter/EximParameters_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DFIABenefitLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Parameter/EximParameters_IN (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Ledger/Main/CompanyInfo.md" target="_blank">/core/erp/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
