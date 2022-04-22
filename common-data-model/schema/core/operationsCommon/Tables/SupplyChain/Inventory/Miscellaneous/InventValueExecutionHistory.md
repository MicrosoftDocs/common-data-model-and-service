---
title: InventValueExecutionHistory in Miscellaneous - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# InventValueExecutionHistory in Miscellaneous

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/Inventory/Miscellaneous/InventValueExecutionHistory.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[InventValueExecutionHistory/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="InventValueExecutionHistory.md" target="_blank">Miscellaneous/InventValueExecutionHistory</a>|
|[TransactionId](#TransactionId)||<a href="InventValueExecutionHistory.md" target="_blank">Miscellaneous/InventValueExecutionHistory</a>|
|[ExecutionName](#ExecutionName)||<a href="InventValueExecutionHistory.md" target="_blank">Miscellaneous/InventValueExecutionHistory</a>|
|[ExecutionTime](#ExecutionTime)||<a href="InventValueExecutionHistory.md" target="_blank">Miscellaneous/InventValueExecutionHistory</a>|
|[FromDate](#FromDate)||<a href="InventValueExecutionHistory.md" target="_blank">Miscellaneous/InventValueExecutionHistory</a>|
|[ToDate](#ToDate)||<a href="InventValueExecutionHistory.md" target="_blank">Miscellaneous/InventValueExecutionHistory</a>|
|[CalcAvgUnitCost](#CalcAvgUnitCost)||<a href="InventValueExecutionHistory.md" target="_blank">Miscellaneous/InventValueExecutionHistory</a>|
|[DetailLevel](#DetailLevel)||<a href="InventValueExecutionHistory.md" target="_blank">Miscellaneous/InventValueExecutionHistory</a>|
|[DimensionFocus](#DimensionFocus)||<a href="InventValueExecutionHistory.md" target="_blank">Miscellaneous/InventValueExecutionHistory</a>|
|[IncludeBeginningBalance](#IncludeBeginningBalance)||<a href="InventValueExecutionHistory.md" target="_blank">Miscellaneous/InventValueExecutionHistory</a>|
|[IncludeNotPostedValue](#IncludeNotPostedValue)||<a href="InventValueExecutionHistory.md" target="_blank">Miscellaneous/InventValueExecutionHistory</a>|
|[PrintTotalQtyValue](#PrintTotalQtyValue)||<a href="InventValueExecutionHistory.md" target="_blank">Miscellaneous/InventValueExecutionHistory</a>|
|[SummarizePhysFinValues](#SummarizePhysFinValues)||<a href="InventValueExecutionHistory.md" target="_blank">Miscellaneous/InventValueExecutionHistory</a>|
|[ViewCOGS](#ViewCOGS)||<a href="InventValueExecutionHistory.md" target="_blank">Miscellaneous/InventValueExecutionHistory</a>|
|[ViewDeferredCOGS](#ViewDeferredCOGS)||<a href="InventValueExecutionHistory.md" target="_blank">Miscellaneous/InventValueExecutionHistory</a>|
|[ViewDirectOutsourcing](#ViewDirectOutsourcing)||<a href="InventValueExecutionHistory.md" target="_blank">Miscellaneous/InventValueExecutionHistory</a>|
|[ViewIndirect](#ViewIndirect)||<a href="InventValueExecutionHistory.md" target="_blank">Miscellaneous/InventValueExecutionHistory</a>|
|[ViewInventory](#ViewInventory)||<a href="InventValueExecutionHistory.md" target="_blank">Miscellaneous/InventValueExecutionHistory</a>|
|[ViewLabor](#ViewLabor)||<a href="InventValueExecutionHistory.md" target="_blank">Miscellaneous/InventValueExecutionHistory</a>|
|[ViewMaterial](#ViewMaterial)||<a href="InventValueExecutionHistory.md" target="_blank">Miscellaneous/InventValueExecutionHistory</a>|
|[ViewProfitLoss](#ViewProfitLoss)||<a href="InventValueExecutionHistory.md" target="_blank">Miscellaneous/InventValueExecutionHistory</a>|
|[ViewResourceGroup](#ViewResourceGroup)||<a href="InventValueExecutionHistory.md" target="_blank">Miscellaneous/InventValueExecutionHistory</a>|
|[ViewResourceGroupTotal](#ViewResourceGroupTotal)||<a href="InventValueExecutionHistory.md" target="_blank">Miscellaneous/InventValueExecutionHistory</a>|
|[ViewResourceId](#ViewResourceId)||<a href="InventValueExecutionHistory.md" target="_blank">Miscellaneous/InventValueExecutionHistory</a>|
|[ViewResourceIdTotal](#ViewResourceIdTotal)||<a href="InventValueExecutionHistory.md" target="_blank">Miscellaneous/InventValueExecutionHistory</a>|
|[ViewWIP](#ViewWIP)||<a href="InventValueExecutionHistory.md" target="_blank">Miscellaneous/InventValueExecutionHistory</a>|
|[ViewConfigId](#ViewConfigId)||<a href="InventValueExecutionHistory.md" target="_blank">Miscellaneous/InventValueExecutionHistory</a>|
|[ViewInventBatchId](#ViewInventBatchId)||<a href="InventValueExecutionHistory.md" target="_blank">Miscellaneous/InventValueExecutionHistory</a>|
|[ViewInventColorId](#ViewInventColorId)||<a href="InventValueExecutionHistory.md" target="_blank">Miscellaneous/InventValueExecutionHistory</a>|
|[ViewInventGTDId_RU](#ViewInventGTDId_RU)||<a href="InventValueExecutionHistory.md" target="_blank">Miscellaneous/InventValueExecutionHistory</a>|
|[ViewInventOwnerId_RU](#ViewInventOwnerId_RU)||<a href="InventValueExecutionHistory.md" target="_blank">Miscellaneous/InventValueExecutionHistory</a>|
|[ViewInventProfileId_RU](#ViewInventProfileId_RU)||<a href="InventValueExecutionHistory.md" target="_blank">Miscellaneous/InventValueExecutionHistory</a>|
|[ViewInventLocationId](#ViewInventLocationId)||<a href="InventValueExecutionHistory.md" target="_blank">Miscellaneous/InventValueExecutionHistory</a>|
|[ViewInventSerialId](#ViewInventSerialId)||<a href="InventValueExecutionHistory.md" target="_blank">Miscellaneous/InventValueExecutionHistory</a>|
|[ViewInventSiteId](#ViewInventSiteId)||<a href="InventValueExecutionHistory.md" target="_blank">Miscellaneous/InventValueExecutionHistory</a>|
|[ViewInventSizeId](#ViewInventSizeId)||<a href="InventValueExecutionHistory.md" target="_blank">Miscellaneous/InventValueExecutionHistory</a>|
|[ViewInventStatus](#ViewInventStatus)||<a href="InventValueExecutionHistory.md" target="_blank">Miscellaneous/InventValueExecutionHistory</a>|
|[ViewInventStyleId](#ViewInventStyleId)||<a href="InventValueExecutionHistory.md" target="_blank">Miscellaneous/InventValueExecutionHistory</a>|
|[ViewInventVersionId](#ViewInventVersionId)||<a href="InventValueExecutionHistory.md" target="_blank">Miscellaneous/InventValueExecutionHistory</a>|
|[ViewLicensePlate](#ViewLicensePlate)||<a href="InventValueExecutionHistory.md" target="_blank">Miscellaneous/InventValueExecutionHistory</a>|
|[ViewWMSLocationId](#ViewWMSLocationId)||<a href="InventValueExecutionHistory.md" target="_blank">Miscellaneous/InventValueExecutionHistory</a>|
|[ViewInventDimension1](#ViewInventDimension1)||<a href="InventValueExecutionHistory.md" target="_blank">Miscellaneous/InventValueExecutionHistory</a>|
|[ViewInventDimension2](#ViewInventDimension2)||<a href="InventValueExecutionHistory.md" target="_blank">Miscellaneous/InventValueExecutionHistory</a>|
|[ViewInventDimension3](#ViewInventDimension3)||<a href="InventValueExecutionHistory.md" target="_blank">Miscellaneous/InventValueExecutionHistory</a>|
|[ViewInventDimension4](#ViewInventDimension4)||<a href="InventValueExecutionHistory.md" target="_blank">Miscellaneous/InventValueExecutionHistory</a>|
|[ViewInventDimension5](#ViewInventDimension5)||<a href="InventValueExecutionHistory.md" target="_blank">Miscellaneous/InventValueExecutionHistory</a>|
|[ViewInventDimension6](#ViewInventDimension6)||<a href="InventValueExecutionHistory.md" target="_blank">Miscellaneous/InventValueExecutionHistory</a>|
|[ViewInventDimension7](#ViewInventDimension7)||<a href="InventValueExecutionHistory.md" target="_blank">Miscellaneous/InventValueExecutionHistory</a>|
|[ViewInventDimension8](#ViewInventDimension8)||<a href="InventValueExecutionHistory.md" target="_blank">Miscellaneous/InventValueExecutionHistory</a>|
|[ViewInventDimension9](#ViewInventDimension9)||<a href="InventValueExecutionHistory.md" target="_blank">Miscellaneous/InventValueExecutionHistory</a>|
|[ViewInventDimension10](#ViewInventDimension10)||<a href="InventValueExecutionHistory.md" target="_blank">Miscellaneous/InventValueExecutionHistory</a>|
|[ViewInventDimension11](#ViewInventDimension11)||<a href="InventValueExecutionHistory.md" target="_blank">Miscellaneous/InventValueExecutionHistory</a>|
|[ViewInventDimension12](#ViewInventDimension12)||<a href="InventValueExecutionHistory.md" target="_blank">Miscellaneous/InventValueExecutionHistory</a>|
|[Filters](#Filters)||<a href="InventValueExecutionHistory.md" target="_blank">Miscellaneous/InventValueExecutionHistory</a>|
|[DataAreaId](#DataAreaId)||<a href="InventValueExecutionHistory.md" target="_blank">Miscellaneous/InventValueExecutionHistory</a>|
|[Relationship_InventValueReportTmpLineRelationshipId](#Relationship_InventValueReportTmpLineRelationshipId)||<a href="InventValueExecutionHistory.md" target="_blank">Miscellaneous/InventValueExecutionHistory</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="InventValueExecutionHistory.md" target="_blank">Miscellaneous/InventValueExecutionHistory</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/InventValueExecutionHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[InventValueExecutionHistory/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TransactionId name="TransactionId">TransactionId</a>

First included in: Miscellaneous/InventValueExecutionHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ExecutionName name="ExecutionName">ExecutionName</a>

First included in: Miscellaneous/InventValueExecutionHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExecutionName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExecutionTime name="ExecutionTime">ExecutionTime</a>

First included in: Miscellaneous/InventValueExecutionHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExecutionTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#FromDate name="FromDate">FromDate</a>

First included in: Miscellaneous/InventValueExecutionHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#ToDate name="ToDate">ToDate</a>

First included in: Miscellaneous/InventValueExecutionHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#CalcAvgUnitCost name="CalcAvgUnitCost">CalcAvgUnitCost</a>

First included in: Miscellaneous/InventValueExecutionHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Calculate average unit cost</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalcAvgUnitCost attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Calculate average unit cost</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#DetailLevel name="DetailLevel">DetailLevel</a>

First included in: Miscellaneous/InventValueExecutionHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Level</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DetailLevel attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Level</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#DimensionFocus name="DimensionFocus">DimensionFocus</a>

First included in: Miscellaneous/InventValueExecutionHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Dimension set</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionFocus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Dimension set</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#IncludeBeginningBalance name="IncludeBeginningBalance">IncludeBeginningBalance</a>

First included in: Miscellaneous/InventValueExecutionHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Include beginning balance</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IncludeBeginningBalance attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Include beginning balance</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#IncludeNotPostedValue name="IncludeNotPostedValue">IncludeNotPostedValue</a>

First included in: Miscellaneous/InventValueExecutionHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Include not posted to ledger</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IncludeNotPostedValue attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Include not posted to ledger</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#PrintTotalQtyValue name="PrintTotalQtyValue">PrintTotalQtyValue</a>

First included in: Miscellaneous/InventValueExecutionHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total quantity and value</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintTotalQtyValue attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Total quantity and value</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#SummarizePhysFinValues name="SummarizePhysFinValues">SummarizePhysFinValues</a>

First included in: Miscellaneous/InventValueExecutionHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Summarize physical and financial values</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SummarizePhysFinValues attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Summarize physical and financial values</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ViewCOGS name="ViewCOGS">ViewCOGS</a>

First included in: Miscellaneous/InventValueExecutionHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>COGS</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewCOGS attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>COGS</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ViewDeferredCOGS name="ViewDeferredCOGS">ViewDeferredCOGS</a>

First included in: Miscellaneous/InventValueExecutionHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Deferred COGS</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewDeferredCOGS attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Deferred COGS</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ViewDirectOutsourcing name="ViewDirectOutsourcing">ViewDirectOutsourcing</a>

First included in: Miscellaneous/InventValueExecutionHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Direct outsourcing</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewDirectOutsourcing attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Direct outsourcing</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ViewIndirect name="ViewIndirect">ViewIndirect</a>

First included in: Miscellaneous/InventValueExecutionHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Indirect cost</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewIndirect attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Indirect cost</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ViewInventory name="ViewInventory">ViewInventory</a>

First included in: Miscellaneous/InventValueExecutionHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Inventory</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewInventory attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Inventory</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ViewLabor name="ViewLabor">ViewLabor</a>

First included in: Miscellaneous/InventValueExecutionHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Labor</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewLabor attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Labor</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ViewMaterial name="ViewMaterial">ViewMaterial</a>

First included in: Miscellaneous/InventValueExecutionHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Material</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewMaterial attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Material</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ViewProfitLoss name="ViewProfitLoss">ViewProfitLoss</a>

First included in: Miscellaneous/InventValueExecutionHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Profit and loss</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewProfitLoss attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Profit and loss</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ViewResourceGroup name="ViewResourceGroup">ViewResourceGroup</a>

First included in: Miscellaneous/InventValueExecutionHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>View</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewResourceGroup attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>View</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ViewResourceGroupTotal name="ViewResourceGroupTotal">ViewResourceGroupTotal</a>

First included in: Miscellaneous/InventValueExecutionHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewResourceGroupTotal attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Total</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ViewResourceId name="ViewResourceId">ViewResourceId</a>

First included in: Miscellaneous/InventValueExecutionHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>View</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewResourceId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>View</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ViewResourceIdTotal name="ViewResourceIdTotal">ViewResourceIdTotal</a>

First included in: Miscellaneous/InventValueExecutionHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewResourceIdTotal attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Total</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ViewWIP name="ViewWIP">ViewWIP</a>

First included in: Miscellaneous/InventValueExecutionHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>WIP</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewWIP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>WIP</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ViewConfigId name="ViewConfigId">ViewConfigId</a>

First included in: Miscellaneous/InventValueExecutionHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewConfigId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ViewInventBatchId name="ViewInventBatchId">ViewInventBatchId</a>

First included in: Miscellaneous/InventValueExecutionHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewInventBatchId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ViewInventColorId name="ViewInventColorId">ViewInventColorId</a>

First included in: Miscellaneous/InventValueExecutionHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewInventColorId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ViewInventGTDId_RU name="ViewInventGTDId_RU">ViewInventGTDId_RU</a>

First included in: Miscellaneous/InventValueExecutionHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewInventGTDId_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ViewInventOwnerId_RU name="ViewInventOwnerId_RU">ViewInventOwnerId_RU</a>

First included in: Miscellaneous/InventValueExecutionHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewInventOwnerId_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ViewInventProfileId_RU name="ViewInventProfileId_RU">ViewInventProfileId_RU</a>

First included in: Miscellaneous/InventValueExecutionHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewInventProfileId_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ViewInventLocationId name="ViewInventLocationId">ViewInventLocationId</a>

First included in: Miscellaneous/InventValueExecutionHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewInventLocationId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ViewInventSerialId name="ViewInventSerialId">ViewInventSerialId</a>

First included in: Miscellaneous/InventValueExecutionHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewInventSerialId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ViewInventSiteId name="ViewInventSiteId">ViewInventSiteId</a>

First included in: Miscellaneous/InventValueExecutionHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewInventSiteId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ViewInventSizeId name="ViewInventSizeId">ViewInventSizeId</a>

First included in: Miscellaneous/InventValueExecutionHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewInventSizeId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ViewInventStatus name="ViewInventStatus">ViewInventStatus</a>

First included in: Miscellaneous/InventValueExecutionHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewInventStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ViewInventStyleId name="ViewInventStyleId">ViewInventStyleId</a>

First included in: Miscellaneous/InventValueExecutionHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewInventStyleId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ViewInventVersionId name="ViewInventVersionId">ViewInventVersionId</a>

First included in: Miscellaneous/InventValueExecutionHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewInventVersionId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ViewLicensePlate name="ViewLicensePlate">ViewLicensePlate</a>

First included in: Miscellaneous/InventValueExecutionHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewLicensePlate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ViewWMSLocationId name="ViewWMSLocationId">ViewWMSLocationId</a>

First included in: Miscellaneous/InventValueExecutionHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewWMSLocationId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ViewInventDimension1 name="ViewInventDimension1">ViewInventDimension1</a>

First included in: Miscellaneous/InventValueExecutionHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewInventDimension1 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ViewInventDimension2 name="ViewInventDimension2">ViewInventDimension2</a>

First included in: Miscellaneous/InventValueExecutionHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewInventDimension2 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ViewInventDimension3 name="ViewInventDimension3">ViewInventDimension3</a>

First included in: Miscellaneous/InventValueExecutionHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewInventDimension3 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ViewInventDimension4 name="ViewInventDimension4">ViewInventDimension4</a>

First included in: Miscellaneous/InventValueExecutionHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewInventDimension4 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ViewInventDimension5 name="ViewInventDimension5">ViewInventDimension5</a>

First included in: Miscellaneous/InventValueExecutionHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewInventDimension5 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ViewInventDimension6 name="ViewInventDimension6">ViewInventDimension6</a>

First included in: Miscellaneous/InventValueExecutionHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewInventDimension6 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ViewInventDimension7 name="ViewInventDimension7">ViewInventDimension7</a>

First included in: Miscellaneous/InventValueExecutionHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewInventDimension7 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ViewInventDimension8 name="ViewInventDimension8">ViewInventDimension8</a>

First included in: Miscellaneous/InventValueExecutionHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewInventDimension8 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ViewInventDimension9 name="ViewInventDimension9">ViewInventDimension9</a>

First included in: Miscellaneous/InventValueExecutionHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewInventDimension9 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ViewInventDimension10 name="ViewInventDimension10">ViewInventDimension10</a>

First included in: Miscellaneous/InventValueExecutionHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewInventDimension10 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ViewInventDimension11 name="ViewInventDimension11">ViewInventDimension11</a>

First included in: Miscellaneous/InventValueExecutionHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewInventDimension11 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ViewInventDimension12 name="ViewInventDimension12">ViewInventDimension12</a>

First included in: Miscellaneous/InventValueExecutionHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewInventDimension12 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Filters name="Filters">Filters</a>

First included in: Miscellaneous/InventValueExecutionHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Filters attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Miscellaneous/InventValueExecutionHistory (this entity)  

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

### <a href=#Relationship_InventValueReportTmpLineRelationshipId name="Relationship_InventValueReportTmpLineRelationshipId">Relationship_InventValueReportTmpLineRelationshipId</a>

First included in: Miscellaneous/InventValueExecutionHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventValueReportTmpLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/InventValueReportTmpLine.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Transaction/InventValueReportTmpLine.cdm.json/InventValueReportTmpLine</a></td><td><a href="../Transaction/InventValueReportTmpLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Miscellaneous/InventValueExecutionHistory (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
