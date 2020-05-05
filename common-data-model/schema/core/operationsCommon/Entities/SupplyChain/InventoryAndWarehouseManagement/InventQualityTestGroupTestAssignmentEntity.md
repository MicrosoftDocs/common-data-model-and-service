---
title: InventQualityTestGroupTestAssignmentEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 5/5/2020
ms.author: nebanfic
---

# Test group test assignments

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/InventQualityTestGroupTestAssignmentEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Test group test assignments</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AcceptableQualityLevelPercentage](#AcceptableQualityLevelPercentage)||<a href="InventQualityTestGroupTestAssignmentEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityTestGroupTestAssignmentEntity</a>|
|[FailureAction](#FailureAction)||<a href="InventQualityTestGroupTestAssignmentEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityTestGroupTestAssignmentEntity</a>|
|[IsCertificateOfAnalysisReportIncludingTestMeasurement](#IsCertificateOfAnalysisReportIncludingTestMeasurement)||<a href="InventQualityTestGroupTestAssignmentEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityTestGroupTestAssignmentEntity</a>|
|[AcceptableQuantitativeLowerTestMeasurementLimit](#AcceptableQuantitativeLowerTestMeasurementLimit)||<a href="InventQualityTestGroupTestAssignmentEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityTestGroupTestAssignmentEntity</a>|
|[AcceptableQuantitativeLowerTestMeasurementLimitPercentage](#AcceptableQuantitativeLowerTestMeasurementLimitPercentage)||<a href="InventQualityTestGroupTestAssignmentEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityTestGroupTestAssignmentEntity</a>|
|[ItemBatchAttributeId](#ItemBatchAttributeId)||<a href="InventQualityTestGroupTestAssignmentEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityTestGroupTestAssignmentEntity</a>|
|[TestResultDeterminationMethod](#TestResultDeterminationMethod)||<a href="InventQualityTestGroupTestAssignmentEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityTestGroupTestAssignmentEntity</a>|
|[IsBatchAttributeValueDefaultedWithTestMeasurement](#IsBatchAttributeValueDefaultedWithTestMeasurement)||<a href="InventQualityTestGroupTestAssignmentEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityTestGroupTestAssignmentEntity</a>|
|[StandardQuantitativeTestMeasurement](#StandardQuantitativeTestMeasurement)||<a href="InventQualityTestGroupTestAssignmentEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityTestGroupTestAssignmentEntity</a>|
|[QualityTestGroupId](#QualityTestGroupId)||<a href="InventQualityTestGroupTestAssignmentEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityTestGroupTestAssignmentEntity</a>|
|[QualityTestId](#QualityTestId)||<a href="InventQualityTestGroupTestAssignmentEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityTestGroupTestAssignmentEntity</a>|
|[DefaultQualityTestInstrumentId](#DefaultQualityTestInstrumentId)||<a href="InventQualityTestGroupTestAssignmentEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityTestGroupTestAssignmentEntity</a>|
|[SequenceNumber](#SequenceNumber)||<a href="InventQualityTestGroupTestAssignmentEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityTestGroupTestAssignmentEntity</a>|
|[TestMeasurementUnitSymbol](#TestMeasurementUnitSymbol)||<a href="InventQualityTestGroupTestAssignmentEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityTestGroupTestAssignmentEntity</a>|
|[AcceptableQuantitativeUpperTestMeasurementLimit](#AcceptableQuantitativeUpperTestMeasurementLimit)||<a href="InventQualityTestGroupTestAssignmentEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityTestGroupTestAssignmentEntity</a>|
|[AcceptableQuantitativeUpperTestMeasurementLimitPercentage](#AcceptableQuantitativeUpperTestMeasurementLimitPercentage)||<a href="InventQualityTestGroupTestAssignmentEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityTestGroupTestAssignmentEntity</a>|
|[EffectiveDateTime](#EffectiveDateTime)||<a href="InventQualityTestGroupTestAssignmentEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityTestGroupTestAssignmentEntity</a>|
|[ExpirationDateTime](#ExpirationDateTime)||<a href="InventQualityTestGroupTestAssignmentEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityTestGroupTestAssignmentEntity</a>|
|[QualitativeTestVariableId](#QualitativeTestVariableId)||<a href="InventQualityTestGroupTestAssignmentEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityTestGroupTestAssignmentEntity</a>|
|[DefaultQualitativeTestMeasurementOutcome](#DefaultQualitativeTestMeasurementOutcome)||<a href="InventQualityTestGroupTestAssignmentEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityTestGroupTestAssignmentEntity</a>|
|[BackingTable_InventTestGroupMemberRelationshipId](#BackingTable_InventTestGroupMemberRelationshipId)||<a href="InventQualityTestGroupTestAssignmentEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityTestGroupTestAssignmentEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="InventQualityTestGroupTestAssignmentEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityTestGroupTestAssignmentEntity</a>|

### <a href=#AcceptableQualityLevelPercentage name="AcceptableQualityLevelPercentage">AcceptableQualityLevelPercentage</a>

First included in: InventoryAndWarehouseManagement/InventQualityTestGroupTestAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AcceptableQualityLevelPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FailureAction name="FailureAction">FailureAction</a>

First included in: InventoryAndWarehouseManagement/InventQualityTestGroupTestAssignmentEntity (this entity)  

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

First included in: InventoryAndWarehouseManagement/InventQualityTestGroupTestAssignmentEntity (this entity)  

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

### <a href=#AcceptableQuantitativeLowerTestMeasurementLimit name="AcceptableQuantitativeLowerTestMeasurementLimit">AcceptableQuantitativeLowerTestMeasurementLimit</a>

First included in: InventoryAndWarehouseManagement/InventQualityTestGroupTestAssignmentEntity (this entity)  

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

First included in: InventoryAndWarehouseManagement/InventQualityTestGroupTestAssignmentEntity (this entity)  

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

First included in: InventoryAndWarehouseManagement/InventQualityTestGroupTestAssignmentEntity (this entity)  

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

### <a href=#TestResultDeterminationMethod name="TestResultDeterminationMethod">TestResultDeterminationMethod</a>

First included in: InventoryAndWarehouseManagement/InventQualityTestGroupTestAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TestResultDeterminationMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsBatchAttributeValueDefaultedWithTestMeasurement name="IsBatchAttributeValueDefaultedWithTestMeasurement">IsBatchAttributeValueDefaultedWithTestMeasurement</a>

First included in: InventoryAndWarehouseManagement/InventQualityTestGroupTestAssignmentEntity (this entity)  

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

### <a href=#StandardQuantitativeTestMeasurement name="StandardQuantitativeTestMeasurement">StandardQuantitativeTestMeasurement</a>

First included in: InventoryAndWarehouseManagement/InventQualityTestGroupTestAssignmentEntity (this entity)  

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

### <a href=#QualityTestGroupId name="QualityTestGroupId">QualityTestGroupId</a>

First included in: InventoryAndWarehouseManagement/InventQualityTestGroupTestAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QualityTestGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QualityTestId name="QualityTestId">QualityTestId</a>

First included in: InventoryAndWarehouseManagement/InventQualityTestGroupTestAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QualityTestId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultQualityTestInstrumentId name="DefaultQualityTestInstrumentId">DefaultQualityTestInstrumentId</a>

First included in: InventoryAndWarehouseManagement/InventQualityTestGroupTestAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultQualityTestInstrumentId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SequenceNumber name="SequenceNumber">SequenceNumber</a>

First included in: InventoryAndWarehouseManagement/InventQualityTestGroupTestAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SequenceNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TestMeasurementUnitSymbol name="TestMeasurementUnitSymbol">TestMeasurementUnitSymbol</a>

First included in: InventoryAndWarehouseManagement/InventQualityTestGroupTestAssignmentEntity (this entity)  

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

First included in: InventoryAndWarehouseManagement/InventQualityTestGroupTestAssignmentEntity (this entity)  

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

First included in: InventoryAndWarehouseManagement/InventQualityTestGroupTestAssignmentEntity (this entity)  

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

### <a href=#EffectiveDateTime name="EffectiveDateTime">EffectiveDateTime</a>

First included in: InventoryAndWarehouseManagement/InventQualityTestGroupTestAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EffectiveDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExpirationDateTime name="ExpirationDateTime">ExpirationDateTime</a>

First included in: InventoryAndWarehouseManagement/InventQualityTestGroupTestAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpirationDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QualitativeTestVariableId name="QualitativeTestVariableId">QualitativeTestVariableId</a>

First included in: InventoryAndWarehouseManagement/InventQualityTestGroupTestAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QualitativeTestVariableId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultQualitativeTestMeasurementOutcome name="DefaultQualitativeTestMeasurementOutcome">DefaultQualitativeTestMeasurementOutcome</a>

First included in: InventoryAndWarehouseManagement/InventQualityTestGroupTestAssignmentEntity (this entity)  

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

### <a href=#BackingTable_InventTestGroupMemberRelationshipId name="BackingTable_InventTestGroupMemberRelationshipId">BackingTable_InventTestGroupMemberRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventQualityTestGroupTestAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_InventTestGroupMemberRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Group/InventTestGroupMember.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/InventTestGroupMember.cdm.json/InventTestGroupMember</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Group/InventTestGroupMember.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventQualityTestGroupTestAssignmentEntity (this entity)  

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
