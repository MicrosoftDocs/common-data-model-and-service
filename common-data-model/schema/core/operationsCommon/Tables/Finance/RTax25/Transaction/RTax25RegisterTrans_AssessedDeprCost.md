---
title: RTax25RegisterTrans_AssessedDeprCost - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# RTax25RegisterTrans_AssessedDeprCost

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/RTax25/Transaction/RTax25RegisterTrans_AssessedDeprCost.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RTax25RegisterTrans_AssessedDeprCost/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RTax25RegisterTrans_AssessedDeprCost.md" target="_blank">Transaction/RTax25RegisterTrans_AssessedDeprCost</a>|
|[AcquisitionDate](#AcquisitionDate)||<a href="RTax25RegisterTrans_AssessedDeprCost.md" target="_blank">Transaction/RTax25RegisterTrans_AssessedDeprCost</a>|
|[AssetId](#AssetId)||<a href="RTax25RegisterTrans_AssessedDeprCost.md" target="_blank">Transaction/RTax25RegisterTrans_AssessedDeprCost</a>|
|[AssetKind](#AssetKind)||<a href="RTax25RegisterTrans_AssessedDeprCost.md" target="_blank">Transaction/RTax25RegisterTrans_AssessedDeprCost</a>|
|[AssetTypeStr](#AssetTypeStr)||<a href="RTax25RegisterTrans_AssessedDeprCost.md" target="_blank">Transaction/RTax25RegisterTrans_AssessedDeprCost</a>|
|[BlockType](#BlockType)||<a href="RTax25RegisterTrans_AssessedDeprCost.md" target="_blank">Transaction/RTax25RegisterTrans_AssessedDeprCost</a>|
|[BranchId](#BranchId)||<a href="RTax25RegisterTrans_AssessedDeprCost.md" target="_blank">Transaction/RTax25RegisterTrans_AssessedDeprCost</a>|
|[BudgetRevenueCode](#BudgetRevenueCode)||<a href="RTax25RegisterTrans_AssessedDeprCost.md" target="_blank">Transaction/RTax25RegisterTrans_AssessedDeprCost</a>|
|[CadastralValue](#CadastralValue)||<a href="RTax25RegisterTrans_AssessedDeprCost.md" target="_blank">Transaction/RTax25RegisterTrans_AssessedDeprCost</a>|
|[CadastralValueTotal](#CadastralValueTotal)||<a href="RTax25RegisterTrans_AssessedDeprCost.md" target="_blank">Transaction/RTax25RegisterTrans_AssessedDeprCost</a>|
|[Corrected](#Corrected)||<a href="RTax25RegisterTrans_AssessedDeprCost.md" target="_blank">Transaction/RTax25RegisterTrans_AssessedDeprCost</a>|
|[CostChangePeriod](#CostChangePeriod)||<a href="RTax25RegisterTrans_AssessedDeprCost.md" target="_blank">Transaction/RTax25RegisterTrans_AssessedDeprCost</a>|
|[CostChangeFactor](#CostChangeFactor)||<a href="RTax25RegisterTrans_AssessedDeprCost.md" target="_blank">Transaction/RTax25RegisterTrans_AssessedDeprCost</a>|
|[DistributedPropertyShare](#DistributedPropertyShare)||<a href="RTax25RegisterTrans_AssessedDeprCost.md" target="_blank">Transaction/RTax25RegisterTrans_AssessedDeprCost</a>|
|[Immovable](#Immovable)||<a href="RTax25RegisterTrans_AssessedDeprCost.md" target="_blank">Transaction/RTax25RegisterTrans_AssessedDeprCost</a>|
|[IsDistributed](#IsDistributed)||<a href="RTax25RegisterTrans_AssessedDeprCost.md" target="_blank">Transaction/RTax25RegisterTrans_AssessedDeprCost</a>|
|[JournalTransRefRecId](#JournalTransRefRecId)||<a href="RTax25RegisterTrans_AssessedDeprCost.md" target="_blank">Transaction/RTax25RegisterTrans_AssessedDeprCost</a>|
|[LineDescription](#LineDescription)||<a href="RTax25RegisterTrans_AssessedDeprCost.md" target="_blank">Transaction/RTax25RegisterTrans_AssessedDeprCost</a>|
|[LineNumber](#LineNumber)||<a href="RTax25RegisterTrans_AssessedDeprCost.md" target="_blank">Transaction/RTax25RegisterTrans_AssessedDeprCost</a>|
|[Location](#Location)||<a href="RTax25RegisterTrans_AssessedDeprCost.md" target="_blank">Transaction/RTax25RegisterTrans_AssessedDeprCost</a>|
|[ManualInput](#ManualInput)||<a href="RTax25RegisterTrans_AssessedDeprCost.md" target="_blank">Transaction/RTax25RegisterTrans_AssessedDeprCost</a>|
|[Movables](#Movables)||<a href="RTax25RegisterTrans_AssessedDeprCost.md" target="_blank">Transaction/RTax25RegisterTrans_AssessedDeprCost</a>|
|[Name](#Name)||<a href="RTax25RegisterTrans_AssessedDeprCost.md" target="_blank">Transaction/RTax25RegisterTrans_AssessedDeprCost</a>|
|[NetBookValue](#NetBookValue)||<a href="RTax25RegisterTrans_AssessedDeprCost.md" target="_blank">Transaction/RTax25RegisterTrans_AssessedDeprCost</a>|
|[NetBookValueTotal](#NetBookValueTotal)||<a href="RTax25RegisterTrans_AssessedDeprCost.md" target="_blank">Transaction/RTax25RegisterTrans_AssessedDeprCost</a>|
|[NonTaxable](#NonTaxable)||<a href="RTax25RegisterTrans_AssessedDeprCost.md" target="_blank">Transaction/RTax25RegisterTrans_AssessedDeprCost</a>|
|[OwnedShare](#OwnedShare)||<a href="RTax25RegisterTrans_AssessedDeprCost.md" target="_blank">Transaction/RTax25RegisterTrans_AssessedDeprCost</a>|
|[OwnershipPeriod](#OwnershipPeriod)||<a href="RTax25RegisterTrans_AssessedDeprCost.md" target="_blank">Transaction/RTax25RegisterTrans_AssessedDeprCost</a>|
|[OwnershipFactor](#OwnershipFactor)||<a href="RTax25RegisterTrans_AssessedDeprCost.md" target="_blank">Transaction/RTax25RegisterTrans_AssessedDeprCost</a>|
|[Period](#Period)||<a href="RTax25RegisterTrans_AssessedDeprCost.md" target="_blank">Transaction/RTax25RegisterTrans_AssessedDeprCost</a>|
|[ProfitAmount](#ProfitAmount)||<a href="RTax25RegisterTrans_AssessedDeprCost.md" target="_blank">Transaction/RTax25RegisterTrans_AssessedDeprCost</a>|
|[RailwayAsset](#RailwayAsset)||<a href="RTax25RegisterTrans_AssessedDeprCost.md" target="_blank">Transaction/RTax25RegisterTrans_AssessedDeprCost</a>|
|[RailwayFactor](#RailwayFactor)||<a href="RTax25RegisterTrans_AssessedDeprCost.md" target="_blank">Transaction/RTax25RegisterTrans_AssessedDeprCost</a>|
|[RCOAD](#RCOAD)||<a href="RTax25RegisterTrans_AssessedDeprCost.md" target="_blank">Transaction/RTax25RegisterTrans_AssessedDeprCost</a>|
|[RefRecId](#RefRecId)||<a href="RTax25RegisterTrans_AssessedDeprCost.md" target="_blank">Transaction/RTax25RegisterTrans_AssessedDeprCost</a>|
|[RefTableId](#RefTableId)||<a href="RTax25RegisterTrans_AssessedDeprCost.md" target="_blank">Transaction/RTax25RegisterTrans_AssessedDeprCost</a>|
|[RTax25ProfitTable](#RTax25ProfitTable)||<a href="RTax25RegisterTrans_AssessedDeprCost.md" target="_blank">Transaction/RTax25RegisterTrans_AssessedDeprCost</a>|
|[SalesTaxCode](#SalesTaxCode)||<a href="RTax25RegisterTrans_AssessedDeprCost.md" target="_blank">Transaction/RTax25RegisterTrans_AssessedDeprCost</a>|
|[Section](#Section)||<a href="RTax25RegisterTrans_AssessedDeprCost.md" target="_blank">Transaction/RTax25RegisterTrans_AssessedDeprCost</a>|
|[TaxAllowanceId](#TaxAllowanceId)||<a href="RTax25RegisterTrans_AssessedDeprCost.md" target="_blank">Transaction/RTax25RegisterTrans_AssessedDeprCost</a>|
|[TaxAuthority](#TaxAuthority)||<a href="RTax25RegisterTrans_AssessedDeprCost.md" target="_blank">Transaction/RTax25RegisterTrans_AssessedDeprCost</a>|
|[RAssetLocation](#RAssetLocation)||<a href="RTax25RegisterTrans_AssessedDeprCost.md" target="_blank">Transaction/RTax25RegisterTrans_AssessedDeprCost</a>|
|[RefLineNumber](#RefLineNumber)||<a href="RTax25RegisterTrans_AssessedDeprCost.md" target="_blank">Transaction/RTax25RegisterTrans_AssessedDeprCost</a>|
|[DataAreaId](#DataAreaId)||<a href="RTax25RegisterTrans_AssessedDeprCost.md" target="_blank">Transaction/RTax25RegisterTrans_AssessedDeprCost</a>|
|[Relationship_Branches_RURelationshipId](#Relationship_Branches_RURelationshipId)||<a href="RTax25RegisterTrans_AssessedDeprCost.md" target="_blank">Transaction/RTax25RegisterTrans_AssessedDeprCost</a>|
|[Relationship_PaymentOrderBudgetReceiptClassTable_RURelationshipId](#Relationship_PaymentOrderBudgetReceiptClassTable_RURelationshipId)||<a href="RTax25RegisterTrans_AssessedDeprCost.md" target="_blank">Transaction/RTax25RegisterTrans_AssessedDeprCost</a>|
|[Relationship_RAssetLocationRelationshipId](#Relationship_RAssetLocationRelationshipId)||<a href="RTax25RegisterTrans_AssessedDeprCost.md" target="_blank">Transaction/RTax25RegisterTrans_AssessedDeprCost</a>|
|[Relationship_RAssetTableRelationshipId](#Relationship_RAssetTableRelationshipId)||<a href="RTax25RegisterTrans_AssessedDeprCost.md" target="_blank">Transaction/RTax25RegisterTrans_AssessedDeprCost</a>|
|[Relationship_RAssetTableAccountNumRelationshipId](#Relationship_RAssetTableAccountNumRelationshipId)||<a href="RTax25RegisterTrans_AssessedDeprCost.md" target="_blank">Transaction/RTax25RegisterTrans_AssessedDeprCost</a>|
|[Relationship_RTax25ProfitTableRelationshipId](#Relationship_RTax25ProfitTableRelationshipId)||<a href="RTax25RegisterTrans_AssessedDeprCost.md" target="_blank">Transaction/RTax25RegisterTrans_AssessedDeprCost</a>|
|[Relationship_RTax25RegisterJournalTransRecIdRelationshipId](#Relationship_RTax25RegisterJournalTransRecIdRelationshipId)||<a href="RTax25RegisterTrans_AssessedDeprCost.md" target="_blank">Transaction/RTax25RegisterTrans_AssessedDeprCost</a>|
|[Relationship_TaxAuthorityAddressRelationshipId](#Relationship_TaxAuthorityAddressRelationshipId)||<a href="RTax25RegisterTrans_AssessedDeprCost.md" target="_blank">Transaction/RTax25RegisterTrans_AssessedDeprCost</a>|
|[Relationship_TaxTableRelationshipId](#Relationship_TaxTableRelationshipId)||<a href="RTax25RegisterTrans_AssessedDeprCost.md" target="_blank">Transaction/RTax25RegisterTrans_AssessedDeprCost</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="RTax25RegisterTrans_AssessedDeprCost.md" target="_blank">Transaction/RTax25RegisterTrans_AssessedDeprCost</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/RTax25RegisterTrans_AssessedDeprCost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RTax25RegisterTrans_AssessedDeprCost/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AcquisitionDate name="AcquisitionDate">AcquisitionDate</a>

First included in: Transaction/RTax25RegisterTrans_AssessedDeprCost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AcquisitionDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#AssetId name="AssetId">AssetId</a>

First included in: Transaction/RTax25RegisterTrans_AssessedDeprCost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AssetKind name="AssetKind">AssetKind</a>

First included in: Transaction/RTax25RegisterTrans_AssessedDeprCost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetKind attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AssetTypeStr name="AssetTypeStr">AssetTypeStr</a>

First included in: Transaction/RTax25RegisterTrans_AssessedDeprCost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetTypeStr attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BlockType name="BlockType">BlockType</a>

First included in: Transaction/RTax25RegisterTrans_AssessedDeprCost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BlockType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#BranchId name="BranchId">BranchId</a>

First included in: Transaction/RTax25RegisterTrans_AssessedDeprCost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BranchId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BudgetRevenueCode name="BudgetRevenueCode">BudgetRevenueCode</a>

First included in: Transaction/RTax25RegisterTrans_AssessedDeprCost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetRevenueCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CadastralValue name="CadastralValue">CadastralValue</a>

First included in: Transaction/RTax25RegisterTrans_AssessedDeprCost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CadastralValue attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CadastralValueTotal name="CadastralValueTotal">CadastralValueTotal</a>

First included in: Transaction/RTax25RegisterTrans_AssessedDeprCost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CadastralValueTotal attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Corrected name="Corrected">Corrected</a>

First included in: Transaction/RTax25RegisterTrans_AssessedDeprCost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Corrected attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#CostChangePeriod name="CostChangePeriod">CostChangePeriod</a>

First included in: Transaction/RTax25RegisterTrans_AssessedDeprCost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostChangePeriod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CostChangeFactor name="CostChangeFactor">CostChangeFactor</a>

First included in: Transaction/RTax25RegisterTrans_AssessedDeprCost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostChangeFactor attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DistributedPropertyShare name="DistributedPropertyShare">DistributedPropertyShare</a>

First included in: Transaction/RTax25RegisterTrans_AssessedDeprCost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DistributedPropertyShare attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Immovable name="Immovable">Immovable</a>

First included in: Transaction/RTax25RegisterTrans_AssessedDeprCost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Immovable attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDistributed name="IsDistributed">IsDistributed</a>

First included in: Transaction/RTax25RegisterTrans_AssessedDeprCost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDistributed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JournalTransRefRecId name="JournalTransRefRecId">JournalTransRefRecId</a>

First included in: Transaction/RTax25RegisterTrans_AssessedDeprCost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalTransRefRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LineDescription name="LineDescription">LineDescription</a>

First included in: Transaction/RTax25RegisterTrans_AssessedDeprCost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: Transaction/RTax25RegisterTrans_AssessedDeprCost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Location name="Location">Location</a>

First included in: Transaction/RTax25RegisterTrans_AssessedDeprCost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Location attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ManualInput name="ManualInput">ManualInput</a>

First included in: Transaction/RTax25RegisterTrans_AssessedDeprCost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ManualInput attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#Movables name="Movables">Movables</a>

First included in: Transaction/RTax25RegisterTrans_AssessedDeprCost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Movables attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: Transaction/RTax25RegisterTrans_AssessedDeprCost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NetBookValue name="NetBookValue">NetBookValue</a>

First included in: Transaction/RTax25RegisterTrans_AssessedDeprCost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NetBookValue attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#NetBookValueTotal name="NetBookValueTotal">NetBookValueTotal</a>

First included in: Transaction/RTax25RegisterTrans_AssessedDeprCost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NetBookValueTotal attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#NonTaxable name="NonTaxable">NonTaxable</a>

First included in: Transaction/RTax25RegisterTrans_AssessedDeprCost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NonTaxable attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OwnedShare name="OwnedShare">OwnedShare</a>

First included in: Transaction/RTax25RegisterTrans_AssessedDeprCost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OwnedShare attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OwnershipPeriod name="OwnershipPeriod">OwnershipPeriod</a>

First included in: Transaction/RTax25RegisterTrans_AssessedDeprCost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OwnershipPeriod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#OwnershipFactor name="OwnershipFactor">OwnershipFactor</a>

First included in: Transaction/RTax25RegisterTrans_AssessedDeprCost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OwnershipFactor attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Period name="Period">Period</a>

First included in: Transaction/RTax25RegisterTrans_AssessedDeprCost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Period attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#ProfitAmount name="ProfitAmount">ProfitAmount</a>

First included in: Transaction/RTax25RegisterTrans_AssessedDeprCost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProfitAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#RailwayAsset name="RailwayAsset">RailwayAsset</a>

First included in: Transaction/RTax25RegisterTrans_AssessedDeprCost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RailwayAsset attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RailwayFactor name="RailwayFactor">RailwayFactor</a>

First included in: Transaction/RTax25RegisterTrans_AssessedDeprCost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RailwayFactor attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#RCOAD name="RCOAD">RCOAD</a>

First included in: Transaction/RTax25RegisterTrans_AssessedDeprCost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RCOAD attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RefRecId name="RefRecId">RefRecId</a>

First included in: Transaction/RTax25RegisterTrans_AssessedDeprCost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RefTableId name="RefTableId">RefTableId</a>

First included in: Transaction/RTax25RegisterTrans_AssessedDeprCost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefTableId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#RTax25ProfitTable name="RTax25ProfitTable">RTax25ProfitTable</a>

First included in: Transaction/RTax25RegisterTrans_AssessedDeprCost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RTax25ProfitTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SalesTaxCode name="SalesTaxCode">SalesTaxCode</a>

First included in: Transaction/RTax25RegisterTrans_AssessedDeprCost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Section name="Section">Section</a>

First included in: Transaction/RTax25RegisterTrans_AssessedDeprCost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Section attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxAllowanceId name="TaxAllowanceId">TaxAllowanceId</a>

First included in: Transaction/RTax25RegisterTrans_AssessedDeprCost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAllowanceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxAuthority name="TaxAuthority">TaxAuthority</a>

First included in: Transaction/RTax25RegisterTrans_AssessedDeprCost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAuthority attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RAssetLocation name="RAssetLocation">RAssetLocation</a>

First included in: Transaction/RTax25RegisterTrans_AssessedDeprCost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RAssetLocation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RefLineNumber name="RefLineNumber">RefLineNumber</a>

First included in: Transaction/RTax25RegisterTrans_AssessedDeprCost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefLineNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/RTax25RegisterTrans_AssessedDeprCost (this entity)  

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

### <a href=#Relationship_Branches_RURelationshipId name="Relationship_Branches_RURelationshipId">Relationship_Branches_RURelationshipId</a>

First included in: Transaction/RTax25RegisterTrans_AssessedDeprCost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_Branches_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../APARShared/Group/Branches_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/APARShared/Group/Branches_RU.cdm.json/Branches_RU</a></td><td><a href="../../APARShared/Group/Branches_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PaymentOrderBudgetReceiptClassTable_RURelationshipId name="Relationship_PaymentOrderBudgetReceiptClassTable_RURelationshipId">Relationship_PaymentOrderBudgetReceiptClassTable_RURelationshipId</a>

First included in: Transaction/RTax25RegisterTrans_AssessedDeprCost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PaymentOrderBudgetReceiptClassTable_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Bank/Main/PaymentOrderBudgetReceiptClassTable_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Main/PaymentOrderBudgetReceiptClassTable_RU.cdm.json/PaymentOrderBudgetReceiptClassTable_RU</a></td><td><a href="../../Bank/Main/PaymentOrderBudgetReceiptClassTable_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RAssetLocationRelationshipId name="Relationship_RAssetLocationRelationshipId">Relationship_RAssetLocationRelationshipId</a>

First included in: Transaction/RTax25RegisterTrans_AssessedDeprCost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RAssetLocationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../RAsset/Group/RAssetLocation.md" target="_blank">/core/operationsCommon/Tables/Finance/RAsset/Group/RAssetLocation.cdm.json/RAssetLocation</a></td><td><a href="../../RAsset/Group/RAssetLocation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RAssetTableRelationshipId name="Relationship_RAssetTableRelationshipId">Relationship_RAssetTableRelationshipId</a>

First included in: Transaction/RTax25RegisterTrans_AssessedDeprCost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RAssetTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../RAsset/Main/RAssetTable.md" target="_blank">/core/operationsCommon/Tables/Finance/RAsset/Main/RAssetTable.cdm.json/RAssetTable</a></td><td><a href="../../RAsset/Main/RAssetTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RAssetTableAccountNumRelationshipId name="Relationship_RAssetTableAccountNumRelationshipId">Relationship_RAssetTableAccountNumRelationshipId</a>

First included in: Transaction/RTax25RegisterTrans_AssessedDeprCost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RAssetTableAccountNumRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../RAsset/Main/RAssetTable.md" target="_blank">/core/operationsCommon/Tables/Finance/RAsset/Main/RAssetTable.cdm.json/RAssetTable</a></td><td><a href="../../RAsset/Main/RAssetTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RTax25ProfitTableRelationshipId name="Relationship_RTax25ProfitTableRelationshipId">Relationship_RTax25ProfitTableRelationshipId</a>

First included in: Transaction/RTax25RegisterTrans_AssessedDeprCost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RTax25ProfitTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/RTax25ProfitTable.md" target="_blank">/core/operationsCommon/Tables/Finance/RTax25/Group/RTax25ProfitTable.cdm.json/RTax25ProfitTable</a></td><td><a href="../Group/RTax25ProfitTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RTax25RegisterJournalTransRecIdRelationshipId name="Relationship_RTax25RegisterJournalTransRecIdRelationshipId">Relationship_RTax25RegisterJournalTransRecIdRelationshipId</a>

First included in: Transaction/RTax25RegisterTrans_AssessedDeprCost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RTax25RegisterJournalTransRecIdRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetLine/RTax25RegisterJournalTrans.md" target="_blank">/core/operationsCommon/Tables/Finance/RTax25/WorksheetLine/RTax25RegisterJournalTrans.cdm.json/RTax25RegisterJournalTrans</a></td><td><a href="../WorksheetLine/RTax25RegisterJournalTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxAuthorityAddressRelationshipId name="Relationship_TaxAuthorityAddressRelationshipId">Relationship_TaxAuthorityAddressRelationshipId</a>

First included in: Transaction/RTax25RegisterTrans_AssessedDeprCost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxAuthorityAddressRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Tax/Group/TaxAuthorityAddress.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxAuthorityAddress.cdm.json/TaxAuthorityAddress</a></td><td><a href="../../Tax/Group/TaxAuthorityAddress.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxTableRelationshipId name="Relationship_TaxTableRelationshipId">Relationship_TaxTableRelationshipId</a>

First included in: Transaction/RTax25RegisterTrans_AssessedDeprCost (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Tax/Group/TaxTable.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxTable.cdm.json/TaxTable</a></td><td><a href="../../Tax/Group/TaxTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Transaction/RTax25RegisterTrans_AssessedDeprCost (this entity)  

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
