---
title: InventQualityOrderLineResultEntity in InventoryAndWarehouseManagement - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Quality order line results in InventoryAndWarehouseManagement(InventQualityOrderLineResultEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/InventQualityOrderLineResultEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Quality order line results</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[IsTestValidationIncludingResult](#IsTestValidationIncludingResult)||<a href="InventQualityOrderLineResultEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderLineResultEntity</a>|
|[ResultLineNumber](#ResultLineNumber)||<a href="InventQualityOrderLineResultEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderLineResultEntity</a>|
|[ResultCatchWeightQuantity](#ResultCatchWeightQuantity)||<a href="InventQualityOrderLineResultEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderLineResultEntity</a>|
|[QualityOrderNumber](#QualityOrderNumber)||<a href="InventQualityOrderLineResultEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderLineResultEntity</a>|
|[QualityTestId](#QualityTestId)||<a href="InventQualityOrderLineResultEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderLineResultEntity</a>|
|[TestResult](#TestResult)||<a href="InventQualityOrderLineResultEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderLineResultEntity</a>|
|[ResultInventoryQuantity](#ResultInventoryQuantity)||<a href="InventQualityOrderLineResultEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderLineResultEntity</a>|
|[QualityTestVariableOutcomeId](#QualityTestVariableOutcomeId)||<a href="InventQualityOrderLineResultEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderLineResultEntity</a>|
|[ResultValue](#ResultValue)||<a href="InventQualityOrderLineResultEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderLineResultEntity</a>|
|[QualityOrderSequenceNumber](#QualityOrderSequenceNumber)||<a href="InventQualityOrderLineResultEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderLineResultEntity</a>|
|[BackingTable_InventQualityOrderLineResultsRelationshipId](#BackingTable_InventQualityOrderLineResultsRelationshipId)||<a href="InventQualityOrderLineResultEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderLineResultEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="InventQualityOrderLineResultEntity.md" target="_blank">InventoryAndWarehouseManagement/InventQualityOrderLineResultEntity</a>|

### <a href=#IsTestValidationIncludingResult name="IsTestValidationIncludingResult">IsTestValidationIncludingResult</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderLineResultEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsTestValidationIncludingResult attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResultLineNumber name="ResultLineNumber">ResultLineNumber</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderLineResultEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResultLineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResultCatchWeightQuantity name="ResultCatchWeightQuantity">ResultCatchWeightQuantity</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderLineResultEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResultCatchWeightQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QualityOrderNumber name="QualityOrderNumber">QualityOrderNumber</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderLineResultEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QualityOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QualityTestId name="QualityTestId">QualityTestId</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderLineResultEntity (this entity)  

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

### <a href=#TestResult name="TestResult">TestResult</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderLineResultEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TestResult attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResultInventoryQuantity name="ResultInventoryQuantity">ResultInventoryQuantity</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderLineResultEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResultInventoryQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QualityTestVariableOutcomeId name="QualityTestVariableOutcomeId">QualityTestVariableOutcomeId</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderLineResultEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QualityTestVariableOutcomeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResultValue name="ResultValue">ResultValue</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderLineResultEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResultValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QualityOrderSequenceNumber name="QualityOrderSequenceNumber">QualityOrderSequenceNumber</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderLineResultEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QualityOrderSequenceNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_InventQualityOrderLineResultsRelationshipId name="BackingTable_InventQualityOrderLineResultsRelationshipId">BackingTable_InventQualityOrderLineResultsRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderLineResultEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_InventQualityOrderLineResultsRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/TransactionLine/InventQualityOrderLineResults.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/TransactionLine/InventQualityOrderLineResults.cdm.json/InventQualityOrderLineResults</a></td><td><a href="../../../Tables/SupplyChain/Inventory/TransactionLine/InventQualityOrderLineResults.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventQualityOrderLineResultEntity (this entity)  

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
