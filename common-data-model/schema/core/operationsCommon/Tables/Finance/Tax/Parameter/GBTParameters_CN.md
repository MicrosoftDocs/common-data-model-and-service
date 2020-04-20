---
title: GBTParameters_CN - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# GBTParameters_CN

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Tax/Parameter/GBTParameters_CN.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[GBTParameters_CN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="GBTParameters_CN.md" target="_blank">Parameter/GBTParameters_CN</a>|
|[AcquisitionLedgerDimension](#AcquisitionLedgerDimension)||<a href="GBTParameters_CN.md" target="_blank">Parameter/GBTParameters_CN</a>|
|[BalanceSheet](#BalanceSheet)||<a href="GBTParameters_CN.md" target="_blank">Parameter/GBTParameters_CN</a>|
|[CashflowAdditional](#CashflowAdditional)||<a href="GBTParameters_CN.md" target="_blank">Parameter/GBTParameters_CN</a>|
|[CashflowCodeFormat](#CashflowCodeFormat)||<a href="GBTParameters_CN.md" target="_blank">Parameter/GBTParameters_CN</a>|
|[CashFlowDimension](#CashFlowDimension)||<a href="GBTParameters_CN.md" target="_blank">Parameter/GBTParameters_CN</a>|
|[CashflowMajorSheet](#CashflowMajorSheet)||<a href="GBTParameters_CN.md" target="_blank">Parameter/GBTParameters_CN</a>|
|[ChangesOfOwnersEquity](#ChangesOfOwnersEquity)||<a href="GBTParameters_CN.md" target="_blank">Parameter/GBTParameters_CN</a>|
|[DepreciationLedgerDimension](#DepreciationLedgerDimension)||<a href="GBTParameters_CN.md" target="_blank">Parameter/GBTParameters_CN</a>|
|[DisposalLedgerDimension](#DisposalLedgerDimension)||<a href="GBTParameters_CN.md" target="_blank">Parameter/GBTParameters_CN</a>|
|[ExportARAP](#ExportARAP)||<a href="GBTParameters_CN.md" target="_blank">Parameter/GBTParameters_CN</a>|
|[ExportFA](#ExportFA)||<a href="GBTParameters_CN.md" target="_blank">Parameter/GBTParameters_CN</a>|
|[ExportFilePath](#ExportFilePath)||<a href="GBTParameters_CN.md" target="_blank">Parameter/GBTParameters_CN</a>|
|[FixedAssetGroupCodeFormat](#FixedAssetGroupCodeFormat)||<a href="GBTParameters_CN.md" target="_blank">Parameter/GBTParameters_CN</a>|
|[IncomeSheet](#IncomeSheet)||<a href="GBTParameters_CN.md" target="_blank">Parameter/GBTParameters_CN</a>|
|[Industry](#Industry)||<a href="GBTParameters_CN.md" target="_blank">Parameter/GBTParameters_CN</a>|
|[key](#key)||<a href="GBTParameters_CN.md" target="_blank">Parameter/GBTParameters_CN</a>|
|[OrgNumber](#OrgNumber)||<a href="GBTParameters_CN.md" target="_blank">Parameter/GBTParameters_CN</a>|
|[OrgType](#OrgType)||<a href="GBTParameters_CN.md" target="_blank">Parameter/GBTParameters_CN</a>|
|[ERModelName](#ERModelName)||<a href="GBTParameters_CN.md" target="_blank">Parameter/GBTParameters_CN</a>|
|[DataAreaId](#DataAreaId)||<a href="GBTParameters_CN.md" target="_blank">Parameter/GBTParameters_CN</a>|
|[Relationship_AcquisitionLedgerDimensionRelationshipId](#Relationship_AcquisitionLedgerDimensionRelationshipId)||<a href="GBTParameters_CN.md" target="_blank">Parameter/GBTParameters_CN</a>|
|[Relationship_BalanceSheetRelationshipId](#Relationship_BalanceSheetRelationshipId)||<a href="GBTParameters_CN.md" target="_blank">Parameter/GBTParameters_CN</a>|
|[Relationship_CashflowAdditionalRelationshipId](#Relationship_CashflowAdditionalRelationshipId)||<a href="GBTParameters_CN.md" target="_blank">Parameter/GBTParameters_CN</a>|
|[Relationship_CashflowMajorSheetRelationshipId](#Relationship_CashflowMajorSheetRelationshipId)||<a href="GBTParameters_CN.md" target="_blank">Parameter/GBTParameters_CN</a>|
|[Relationship_ChangesOfOwnersEquityRelationshipId](#Relationship_ChangesOfOwnersEquityRelationshipId)||<a href="GBTParameters_CN.md" target="_blank">Parameter/GBTParameters_CN</a>|
|[Relationship_DepreciationLedgerDimensionRelationshipId](#Relationship_DepreciationLedgerDimensionRelationshipId)||<a href="GBTParameters_CN.md" target="_blank">Parameter/GBTParameters_CN</a>|
|[Relationship_DisposalLedgerDimensionRelationshipId](#Relationship_DisposalLedgerDimensionRelationshipId)||<a href="GBTParameters_CN.md" target="_blank">Parameter/GBTParameters_CN</a>|
|[Relationship_IncomeBalanceRelationshipId](#Relationship_IncomeBalanceRelationshipId)||<a href="GBTParameters_CN.md" target="_blank">Parameter/GBTParameters_CN</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="GBTParameters_CN.md" target="_blank">Parameter/GBTParameters_CN</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Parameter/GBTParameters_CN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[GBTParameters_CN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AcquisitionLedgerDimension name="AcquisitionLedgerDimension">AcquisitionLedgerDimension</a>

First included in: Parameter/GBTParameters_CN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AcquisitionLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BalanceSheet name="BalanceSheet">BalanceSheet</a>

First included in: Parameter/GBTParameters_CN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BalanceSheet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashflowAdditional name="CashflowAdditional">CashflowAdditional</a>

First included in: Parameter/GBTParameters_CN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashflowAdditional attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashflowCodeFormat name="CashflowCodeFormat">CashflowCodeFormat</a>

First included in: Parameter/GBTParameters_CN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashflowCodeFormat attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashFlowDimension name="CashFlowDimension">CashFlowDimension</a>

First included in: Parameter/GBTParameters_CN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashFlowDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashflowMajorSheet name="CashflowMajorSheet">CashflowMajorSheet</a>

First included in: Parameter/GBTParameters_CN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashflowMajorSheet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChangesOfOwnersEquity name="ChangesOfOwnersEquity">ChangesOfOwnersEquity</a>

First included in: Parameter/GBTParameters_CN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChangesOfOwnersEquity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DepreciationLedgerDimension name="DepreciationLedgerDimension">DepreciationLedgerDimension</a>

First included in: Parameter/GBTParameters_CN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepreciationLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DisposalLedgerDimension name="DisposalLedgerDimension">DisposalLedgerDimension</a>

First included in: Parameter/GBTParameters_CN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisposalLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ExportARAP name="ExportARAP">ExportARAP</a>

First included in: Parameter/GBTParameters_CN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExportARAP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ExportFA name="ExportFA">ExportFA</a>

First included in: Parameter/GBTParameters_CN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExportFA attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ExportFilePath name="ExportFilePath">ExportFilePath</a>

First included in: Parameter/GBTParameters_CN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExportFilePath attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FixedAssetGroupCodeFormat name="FixedAssetGroupCodeFormat">FixedAssetGroupCodeFormat</a>

First included in: Parameter/GBTParameters_CN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedAssetGroupCodeFormat attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IncomeSheet name="IncomeSheet">IncomeSheet</a>

First included in: Parameter/GBTParameters_CN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IncomeSheet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Industry name="Industry">Industry</a>

First included in: Parameter/GBTParameters_CN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Industry attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#key name="key">key</a>

First included in: Parameter/GBTParameters_CN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the key attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#OrgNumber name="OrgNumber">OrgNumber</a>

First included in: Parameter/GBTParameters_CN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrgNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrgType name="OrgType">OrgType</a>

First included in: Parameter/GBTParameters_CN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrgType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ERModelName name="ERModelName">ERModelName</a>

First included in: Parameter/GBTParameters_CN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ERModelName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Parameter/GBTParameters_CN (this entity)  

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

### <a href=#Relationship_AcquisitionLedgerDimensionRelationshipId name="Relationship_AcquisitionLedgerDimensionRelationshipId">Relationship_AcquisitionLedgerDimensionRelationshipId</a>

First included in: Parameter/GBTParameters_CN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AcquisitionLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BalanceSheetRelationshipId name="Relationship_BalanceSheetRelationshipId">Relationship_BalanceSheetRelationshipId</a>

First included in: Parameter/GBTParameters_CN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BalanceSheetRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialReporting/Miscellaneous/FinancialReports.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialReporting/Miscellaneous/FinancialReports.cdm.json/FinancialReports</a></td><td><a href="../../FinancialReporting/Miscellaneous/FinancialReports.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CashflowAdditionalRelationshipId name="Relationship_CashflowAdditionalRelationshipId">Relationship_CashflowAdditionalRelationshipId</a>

First included in: Parameter/GBTParameters_CN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CashflowAdditionalRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialReporting/Miscellaneous/FinancialReports.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialReporting/Miscellaneous/FinancialReports.cdm.json/FinancialReports</a></td><td><a href="../../FinancialReporting/Miscellaneous/FinancialReports.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CashflowMajorSheetRelationshipId name="Relationship_CashflowMajorSheetRelationshipId">Relationship_CashflowMajorSheetRelationshipId</a>

First included in: Parameter/GBTParameters_CN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CashflowMajorSheetRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialReporting/Miscellaneous/FinancialReports.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialReporting/Miscellaneous/FinancialReports.cdm.json/FinancialReports</a></td><td><a href="../../FinancialReporting/Miscellaneous/FinancialReports.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ChangesOfOwnersEquityRelationshipId name="Relationship_ChangesOfOwnersEquityRelationshipId">Relationship_ChangesOfOwnersEquityRelationshipId</a>

First included in: Parameter/GBTParameters_CN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ChangesOfOwnersEquityRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialReporting/Miscellaneous/FinancialReports.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialReporting/Miscellaneous/FinancialReports.cdm.json/FinancialReports</a></td><td><a href="../../FinancialReporting/Miscellaneous/FinancialReports.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DepreciationLedgerDimensionRelationshipId name="Relationship_DepreciationLedgerDimensionRelationshipId">Relationship_DepreciationLedgerDimensionRelationshipId</a>

First included in: Parameter/GBTParameters_CN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DepreciationLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DisposalLedgerDimensionRelationshipId name="Relationship_DisposalLedgerDimensionRelationshipId">Relationship_DisposalLedgerDimensionRelationshipId</a>

First included in: Parameter/GBTParameters_CN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DisposalLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_IncomeBalanceRelationshipId name="Relationship_IncomeBalanceRelationshipId">Relationship_IncomeBalanceRelationshipId</a>

First included in: Parameter/GBTParameters_CN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_IncomeBalanceRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialReporting/Miscellaneous/FinancialReports.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialReporting/Miscellaneous/FinancialReports.cdm.json/FinancialReports</a></td><td><a href="../../FinancialReporting/Miscellaneous/FinancialReports.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Parameter/GBTParameters_CN (this entity)  

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
