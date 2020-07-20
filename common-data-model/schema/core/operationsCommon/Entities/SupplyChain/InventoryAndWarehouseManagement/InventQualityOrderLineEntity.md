---
title: InventQualityOrderLineEntity in InventoryAndWarehouseManagement - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/20/2020
ms.author: nebanfic
---

# Quality order line in InventoryAndWarehouseManagement(InventQualityOrderLineEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/InventQualityOrderLineEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Quality order line</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AcceptableQualityLevelPercentage](#AcceptableQualityLevelPercentage)||<a href="InventQualityOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderLineEntity</a>|
|[FailureAction](#FailureAction)||<a href="InventQualityOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderLineEntity</a>|
|[IsCertificateOfAnalysisReportIncludingTestMeasurement](#IsCertificateOfAnalysisReportIncludingTestMeasurement)||<a href="InventQualityOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderLineEntity</a>|
|[IsTestResultValidationIncludingLine](#IsTestResultValidationIncludingLine)||<a href="InventQualityOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderLineEntity</a>|
|[AcceptableQuantitativeLowerTestMeasurementLimit](#AcceptableQuantitativeLowerTestMeasurementLimit)||<a href="InventQualityOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderLineEntity</a>|
|[AcceptableQuantitativeLowerTestMeasurementLimitPercentage](#AcceptableQuantitativeLowerTestMeasurementLimitPercentage)||<a href="InventQualityOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderLineEntity</a>|
|[ItemBatchAttributeId](#ItemBatchAttributeId)||<a href="InventQualityOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderLineEntity</a>|
|[IsItemBatchAttributeValueOverridden](#IsItemBatchAttributeValueOverridden)||<a href="InventQualityOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderLineEntity</a>|
|[QualityTestResultValue](#QualityTestResultValue)||<a href="InventQualityOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderLineEntity</a>|
|[IsBatchAttributeValueDefaultedWithTestMeasurement](#IsBatchAttributeValueDefaultedWithTestMeasurement)||<a href="InventQualityOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderLineEntity</a>|
|[QualityOrderNumber](#QualityOrderNumber)||<a href="InventQualityOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderLineEntity</a>|
|[StandardQuantitativeTestMeasurement](#StandardQuantitativeTestMeasurement)||<a href="InventQualityOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderLineEntity</a>|
|[QualityTestId](#QualityTestId)||<a href="InventQualityOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderLineEntity</a>|
|[QualityTestInstrumentId](#QualityTestInstrumentId)||<a href="InventQualityOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderLineEntity</a>|
|[QualityTestOutcomeStatus](#QualityTestOutcomeStatus)||<a href="InventQualityOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderLineEntity</a>|
|[QualityOrderSequenceNumber](#QualityOrderSequenceNumber)||<a href="InventQualityOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderLineEntity</a>|
|[TestMeasurementUnitSymbol](#TestMeasurementUnitSymbol)||<a href="InventQualityOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderLineEntity</a>|
|[AcceptableQuantitativeUpperTestMeasurementLimit](#AcceptableQuantitativeUpperTestMeasurementLimit)||<a href="InventQualityOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderLineEntity</a>|
|[AcceptableQuantitativeUpperTestMeasurementLimitPercentage](#AcceptableQuantitativeUpperTestMeasurementLimitPercentage)||<a href="InventQualityOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderLineEntity</a>|
|[QualityTestVariableId](#QualityTestVariableId)||<a href="InventQualityOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderLineEntity</a>|
|[DefaultQualitativeTestMeasurementOutcome](#DefaultQualitativeTestMeasurementOutcome)||<a href="InventQualityOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderLineEntity</a>|
|[ItemBatchAttributeIntegerValue](#ItemBatchAttributeIntegerValue)||<a href="InventQualityOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderLineEntity</a>|
|[QualityTestResultIntegerValue](#QualityTestResultIntegerValue)||<a href="InventQualityOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderLineEntity</a>|
|[QualityTestResultDecimalValue](#QualityTestResultDecimalValue)||<a href="InventQualityOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderLineEntity</a>|
|[QualityTestResultDateValue](#QualityTestResultDateValue)||<a href="InventQualityOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderLineEntity</a>|
|[ItemBatchAttributeDecimalValue](#ItemBatchAttributeDecimalValue)||<a href="InventQualityOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderLineEntity</a>|
|[ItemBatchAttributeDateValue](#ItemBatchAttributeDateValue)||<a href="InventQualityOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderLineEntity</a>|
|[PdsBatchAttribType](#PdsBatchAttribType)||<a href="InventQualityOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderLineEntity</a>|
|[ItemBatchAttributeValue](#ItemBatchAttributeValue)||<a href="InventQualityOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderLineEntity</a>|
|[BackingTable_InventQualityOrderLineRelationshipId](#BackingTable_InventQualityOrderLineRelationshipId)||<a href="InventQualityOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderLineEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="InventQualityOrderLineEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderLineEntity</a>|

### <a href=#AcceptableQualityLevelPercentage name="AcceptableQualityLevelPercentage">AcceptableQualityLevelPercentage</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AcceptableQualityLevelPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FailureAction name="FailureAction">FailureAction</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FailureAction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCertificateOfAnalysisReportIncludingTestMeasurement name="IsCertificateOfAnalysisReportIncludingTestMeasurement">IsCertificateOfAnalysisReportIncludingTestMeasurement</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCertificateOfAnalysisReportIncludingTestMeasurement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsTestResultValidationIncludingLine name="IsTestResultValidationIncludingLine">IsTestResultValidationIncludingLine</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsTestResultValidationIncludingLine attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AcceptableQuantitativeLowerTestMeasurementLimit name="AcceptableQuantitativeLowerTestMeasurementLimit">AcceptableQuantitativeLowerTestMeasurementLimit</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AcceptableQuantitativeLowerTestMeasurementLimit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AcceptableQuantitativeLowerTestMeasurementLimitPercentage name="AcceptableQuantitativeLowerTestMeasurementLimitPercentage">AcceptableQuantitativeLowerTestMeasurementLimitPercentage</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AcceptableQuantitativeLowerTestMeasurementLimitPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemBatchAttributeId name="ItemBatchAttributeId">ItemBatchAttributeId</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemBatchAttributeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsItemBatchAttributeValueOverridden name="IsItemBatchAttributeValueOverridden">IsItemBatchAttributeValueOverridden</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsItemBatchAttributeValueOverridden attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QualityTestResultValue name="QualityTestResultValue">QualityTestResultValue</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QualityTestResultValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsBatchAttributeValueDefaultedWithTestMeasurement name="IsBatchAttributeValueDefaultedWithTestMeasurement">IsBatchAttributeValueDefaultedWithTestMeasurement</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsBatchAttributeValueDefaultedWithTestMeasurement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QualityOrderNumber name="QualityOrderNumber">QualityOrderNumber</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QualityOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StandardQuantitativeTestMeasurement name="StandardQuantitativeTestMeasurement">StandardQuantitativeTestMeasurement</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StandardQuantitativeTestMeasurement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QualityTestId name="QualityTestId">QualityTestId</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QualityTestId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QualityTestInstrumentId name="QualityTestInstrumentId">QualityTestInstrumentId</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QualityTestInstrumentId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QualityTestOutcomeStatus name="QualityTestOutcomeStatus">QualityTestOutcomeStatus</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QualityTestOutcomeStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QualityOrderSequenceNumber name="QualityOrderSequenceNumber">QualityOrderSequenceNumber</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QualityOrderSequenceNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TestMeasurementUnitSymbol name="TestMeasurementUnitSymbol">TestMeasurementUnitSymbol</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TestMeasurementUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AcceptableQuantitativeUpperTestMeasurementLimit name="AcceptableQuantitativeUpperTestMeasurementLimit">AcceptableQuantitativeUpperTestMeasurementLimit</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AcceptableQuantitativeUpperTestMeasurementLimit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AcceptableQuantitativeUpperTestMeasurementLimitPercentage name="AcceptableQuantitativeUpperTestMeasurementLimitPercentage">AcceptableQuantitativeUpperTestMeasurementLimitPercentage</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AcceptableQuantitativeUpperTestMeasurementLimitPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QualityTestVariableId name="QualityTestVariableId">QualityTestVariableId</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QualityTestVariableId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultQualitativeTestMeasurementOutcome name="DefaultQualitativeTestMeasurementOutcome">DefaultQualitativeTestMeasurementOutcome</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultQualitativeTestMeasurementOutcome attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemBatchAttributeIntegerValue name="ItemBatchAttributeIntegerValue">ItemBatchAttributeIntegerValue</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemBatchAttributeIntegerValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QualityTestResultIntegerValue name="QualityTestResultIntegerValue">QualityTestResultIntegerValue</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QualityTestResultIntegerValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QualityTestResultDecimalValue name="QualityTestResultDecimalValue">QualityTestResultDecimalValue</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QualityTestResultDecimalValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QualityTestResultDateValue name="QualityTestResultDateValue">QualityTestResultDateValue</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QualityTestResultDateValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemBatchAttributeDecimalValue name="ItemBatchAttributeDecimalValue">ItemBatchAttributeDecimalValue</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemBatchAttributeDecimalValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemBatchAttributeDateValue name="ItemBatchAttributeDateValue">ItemBatchAttributeDateValue</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemBatchAttributeDateValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PdsBatchAttribType name="PdsBatchAttribType">PdsBatchAttribType</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PdsBatchAttribType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemBatchAttributeValue name="ItemBatchAttributeValue">ItemBatchAttributeValue</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemBatchAttributeValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_InventQualityOrderLineRelationshipId name="BackingTable_InventQualityOrderLineRelationshipId">BackingTable_InventQualityOrderLineRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_InventQualityOrderLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/WorksheetLine/InventQualityOrderLine.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/WorksheetLine/InventQualityOrderLine.cdm.json/InventQualityOrderLine</a></td><td><a href="../../../Tables/SupplyChain/Inventory/WorksheetLine/InventQualityOrderLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderLineEntity (this entity)  

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
