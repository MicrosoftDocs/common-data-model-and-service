---
title: LedgerRRGOperationTable_RUEntity in GeneralLedger - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Financial reports operations in GeneralLedger(LedgerRRGOperationTable_RUEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/GeneralLedger/LedgerRRGOperationTable_RUEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Financial reports operations</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AccountIntervalType](#AccountIntervalType)||<a href="LedgerRRGOperationTable_RUEntity.md" target="_blank">GeneralLedger/LedgerRRGOperationTable_RUEntity</a>|
|[AccountNumMask](#AccountNumMask)||<a href="LedgerRRGOperationTable_RUEntity.md" target="_blank">GeneralLedger/LedgerRRGOperationTable_RUEntity</a>|
|[BalanceDetail](#BalanceDetail)||<a href="LedgerRRGOperationTable_RUEntity.md" target="_blank">GeneralLedger/LedgerRRGOperationTable_RUEntity</a>|
|[BalanceType](#BalanceType)||<a href="LedgerRRGOperationTable_RUEntity.md" target="_blank">GeneralLedger/LedgerRRGOperationTable_RUEntity</a>|
|[CellRecId](#CellRecId)||<a href="LedgerRRGOperationTable_RUEntity.md" target="_blank">GeneralLedger/LedgerRRGOperationTable_RUEntity</a>|
|[CellTableId](#CellTableId)||<a href="LedgerRRGOperationTable_RUEntity.md" target="_blank">GeneralLedger/LedgerRRGOperationTable_RUEntity</a>|
|[ConstantText](#ConstantText)||<a href="LedgerRRGOperationTable_RUEntity.md" target="_blank">GeneralLedger/LedgerRRGOperationTable_RUEntity</a>|
|[ConstantValue](#ConstantValue)||<a href="LedgerRRGOperationTable_RUEntity.md" target="_blank">GeneralLedger/LedgerRRGOperationTable_RUEntity</a>|
|[DataType](#DataType)||<a href="LedgerRRGOperationTable_RUEntity.md" target="_blank">GeneralLedger/LedgerRRGOperationTable_RUEntity</a>|
|[LedgerOperation](#LedgerOperation)||<a href="LedgerRRGOperationTable_RUEntity.md" target="_blank">GeneralLedger/LedgerRRGOperationTable_RUEntity</a>|
|[LedgerPeriodCode](#LedgerPeriodCode)||<a href="LedgerRRGOperationTable_RUEntity.md" target="_blank">GeneralLedger/LedgerRRGOperationTable_RUEntity</a>|
|[LineNum](#LineNum)||<a href="LedgerRRGOperationTable_RUEntity.md" target="_blank">GeneralLedger/LedgerRRGOperationTable_RUEntity</a>|
|[ModelNum](#ModelNum)||<a href="LedgerRRGOperationTable_RUEntity.md" target="_blank">GeneralLedger/LedgerRRGOperationTable_RUEntity</a>|
|[OffsetAccountIntervalType](#OffsetAccountIntervalType)||<a href="LedgerRRGOperationTable_RUEntity.md" target="_blank">GeneralLedger/LedgerRRGOperationTable_RUEntity</a>|
|[OffsetAccountNumMask](#OffsetAccountNumMask)||<a href="LedgerRRGOperationTable_RUEntity.md" target="_blank">GeneralLedger/LedgerRRGOperationTable_RUEntity</a>|
|[Operation](#Operation)||<a href="LedgerRRGOperationTable_RUEntity.md" target="_blank">GeneralLedger/LedgerRRGOperationTable_RUEntity</a>|
|[Query](#Query)||<a href="LedgerRRGOperationTable_RUEntity.md" target="_blank">GeneralLedger/LedgerRRGOperationTable_RUEntity</a>|
|[QueryBaseDateField](#QueryBaseDateField)||<a href="LedgerRRGOperationTable_RUEntity.md" target="_blank">GeneralLedger/LedgerRRGOperationTable_RUEntity</a>|
|[QueryFieldOperation](#QueryFieldOperation)||<a href="LedgerRRGOperationTable_RUEntity.md" target="_blank">GeneralLedger/LedgerRRGOperationTable_RUEntity</a>|
|[QuerySelectedField](#QuerySelectedField)||<a href="LedgerRRGOperationTable_RUEntity.md" target="_blank">GeneralLedger/LedgerRRGOperationTable_RUEntity</a>|
|[RTax25FieldId](#RTax25FieldId)||<a href="LedgerRRGOperationTable_RUEntity.md" target="_blank">GeneralLedger/LedgerRRGOperationTable_RUEntity</a>|
|[RTax25RegisterId](#RTax25RegisterId)||<a href="LedgerRRGOperationTable_RUEntity.md" target="_blank">GeneralLedger/LedgerRRGOperationTable_RUEntity</a>|
|[TypeByCorrect](#TypeByCorrect)||<a href="LedgerRRGOperationTable_RUEntity.md" target="_blank">GeneralLedger/LedgerRRGOperationTable_RUEntity</a>|
|[QuerySelectReportDate](#QuerySelectReportDate)||<a href="LedgerRRGOperationTable_RUEntity.md" target="_blank">GeneralLedger/LedgerRRGOperationTable_RUEntity</a>|
|[LineId](#LineId)||<a href="LedgerRRGOperationTable_RUEntity.md" target="_blank">GeneralLedger/LedgerRRGOperationTable_RUEntity</a>|
|[LedgerRRGEProperties_W_PropertyId](#LedgerRRGEProperties_W_PropertyId)||<a href="LedgerRRGOperationTable_RUEntity.md" target="_blank">GeneralLedger/LedgerRRGOperationTable_RUEntity</a>|
|[RefTableName](#RefTableName)||<a href="LedgerRRGOperationTable_RUEntity.md" target="_blank">GeneralLedger/LedgerRRGOperationTable_RUEntity</a>|
|[RefLineId](#RefLineId)||<a href="LedgerRRGOperationTable_RUEntity.md" target="_blank">GeneralLedger/LedgerRRGOperationTable_RUEntity</a>|
|[BackingTable_LedgerRRGOperationTable_RURelationshipId](#BackingTable_LedgerRRGOperationTable_RURelationshipId)||<a href="LedgerRRGOperationTable_RUEntity.md" target="_blank">GeneralLedger/LedgerRRGOperationTable_RUEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="LedgerRRGOperationTable_RUEntity.md" target="_blank">GeneralLedger/LedgerRRGOperationTable_RUEntity</a>|

### <a href=#AccountIntervalType name="AccountIntervalType">AccountIntervalType</a>

First included in: GeneralLedger/LedgerRRGOperationTable_RUEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountIntervalType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountNumMask name="AccountNumMask">AccountNumMask</a>

First included in: GeneralLedger/LedgerRRGOperationTable_RUEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountNumMask attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BalanceDetail name="BalanceDetail">BalanceDetail</a>

First included in: GeneralLedger/LedgerRRGOperationTable_RUEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BalanceDetail attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BalanceType name="BalanceType">BalanceType</a>

First included in: GeneralLedger/LedgerRRGOperationTable_RUEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BalanceType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CellRecId name="CellRecId">CellRecId</a>

First included in: GeneralLedger/LedgerRRGOperationTable_RUEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CellRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CellTableId name="CellTableId">CellTableId</a>

First included in: GeneralLedger/LedgerRRGOperationTable_RUEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CellTableId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConstantText name="ConstantText">ConstantText</a>

First included in: GeneralLedger/LedgerRRGOperationTable_RUEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConstantText attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConstantValue name="ConstantValue">ConstantValue</a>

First included in: GeneralLedger/LedgerRRGOperationTable_RUEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConstantValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataType name="DataType">DataType</a>

First included in: GeneralLedger/LedgerRRGOperationTable_RUEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerOperation name="LedgerOperation">LedgerOperation</a>

First included in: GeneralLedger/LedgerRRGOperationTable_RUEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerOperation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerPeriodCode name="LedgerPeriodCode">LedgerPeriodCode</a>

First included in: GeneralLedger/LedgerRRGOperationTable_RUEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerPeriodCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNum name="LineNum">LineNum</a>

First included in: GeneralLedger/LedgerRRGOperationTable_RUEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ModelNum name="ModelNum">ModelNum</a>

First included in: GeneralLedger/LedgerRRGOperationTable_RUEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ModelNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OffsetAccountIntervalType name="OffsetAccountIntervalType">OffsetAccountIntervalType</a>

First included in: GeneralLedger/LedgerRRGOperationTable_RUEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OffsetAccountIntervalType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OffsetAccountNumMask name="OffsetAccountNumMask">OffsetAccountNumMask</a>

First included in: GeneralLedger/LedgerRRGOperationTable_RUEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OffsetAccountNumMask attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Operation name="Operation">Operation</a>

First included in: GeneralLedger/LedgerRRGOperationTable_RUEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Operation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Query name="Query">Query</a>

First included in: GeneralLedger/LedgerRRGOperationTable_RUEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Query attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QueryBaseDateField name="QueryBaseDateField">QueryBaseDateField</a>

First included in: GeneralLedger/LedgerRRGOperationTable_RUEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QueryBaseDateField attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QueryFieldOperation name="QueryFieldOperation">QueryFieldOperation</a>

First included in: GeneralLedger/LedgerRRGOperationTable_RUEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QueryFieldOperation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuerySelectedField name="QuerySelectedField">QuerySelectedField</a>

First included in: GeneralLedger/LedgerRRGOperationTable_RUEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuerySelectedField attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RTax25FieldId name="RTax25FieldId">RTax25FieldId</a>

First included in: GeneralLedger/LedgerRRGOperationTable_RUEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RTax25FieldId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RTax25RegisterId name="RTax25RegisterId">RTax25RegisterId</a>

First included in: GeneralLedger/LedgerRRGOperationTable_RUEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RTax25RegisterId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TypeByCorrect name="TypeByCorrect">TypeByCorrect</a>

First included in: GeneralLedger/LedgerRRGOperationTable_RUEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TypeByCorrect attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuerySelectReportDate name="QuerySelectReportDate">QuerySelectReportDate</a>

First included in: GeneralLedger/LedgerRRGOperationTable_RUEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuerySelectReportDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineId name="LineId">LineId</a>

First included in: GeneralLedger/LedgerRRGOperationTable_RUEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerRRGEProperties_W_PropertyId name="LedgerRRGEProperties_W_PropertyId">LedgerRRGEProperties_W_PropertyId</a>

First included in: GeneralLedger/LedgerRRGOperationTable_RUEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerRRGEProperties_W_PropertyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RefTableName name="RefTableName">RefTableName</a>

First included in: GeneralLedger/LedgerRRGOperationTable_RUEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefTableName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RefLineId name="RefLineId">RefLineId</a>

First included in: GeneralLedger/LedgerRRGOperationTable_RUEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefLineId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_LedgerRRGOperationTable_RURelationshipId name="BackingTable_LedgerRRGOperationTable_RURelationshipId">BackingTable_LedgerRRGOperationTable_RURelationshipId</a>

First included in: GeneralLedger/LedgerRRGOperationTable_RUEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_LedgerRRGOperationTable_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/WorksheetLine/LedgerRRGOperationTable_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/WorksheetLine/LedgerRRGOperationTable_RU.cdm.json/LedgerRRGOperationTable_RU</a></td><td><a href="../../../Tables/Finance/Ledger/WorksheetLine/LedgerRRGOperationTable_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: GeneralLedger/LedgerRRGOperationTable_RUEntity (this entity)  

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
