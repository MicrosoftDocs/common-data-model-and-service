---
title: PdsProductSpecificItemBatchAttributeEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 5/5/2020
ms.author: nebanfic
---

# Product specific item batch attributes

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/PdsProductSpecificItemBatchAttributeEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Product specific item batch attributes</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ItemNumber](#ItemNumber)||<a href="PdsProductSpecificItemBatchAttributeEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsProductSpecificItemBatchAttributeEntity</a>|
|[BatchAttributeCode](#BatchAttributeCode)||<a href="PdsProductSpecificItemBatchAttributeEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsProductSpecificItemBatchAttributeEntity</a>|
|[BatchAttributeRelation](#BatchAttributeRelation)||<a href="PdsProductSpecificItemBatchAttributeEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsProductSpecificItemBatchAttributeEntity</a>|
|[ItemBatchAttributeId](#ItemBatchAttributeId)||<a href="PdsProductSpecificItemBatchAttributeEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsProductSpecificItemBatchAttributeEntity</a>|
|[ItemBatchAttributeGroupId](#ItemBatchAttributeGroupId)||<a href="PdsProductSpecificItemBatchAttributeEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsProductSpecificItemBatchAttributeEntity</a>|
|[MinimumTolerance](#MinimumTolerance)||<a href="PdsProductSpecificItemBatchAttributeEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsProductSpecificItemBatchAttributeEntity</a>|
|[MaximumTolerance](#MaximumTolerance)||<a href="PdsProductSpecificItemBatchAttributeEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsProductSpecificItemBatchAttributeEntity</a>|
|[ToleranceIncrement](#ToleranceIncrement)||<a href="PdsProductSpecificItemBatchAttributeEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsProductSpecificItemBatchAttributeEntity</a>|
|[OptimalValue](#OptimalValue)||<a href="PdsProductSpecificItemBatchAttributeEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsProductSpecificItemBatchAttributeEntity</a>|
|[OptimalText](#OptimalText)||<a href="PdsProductSpecificItemBatchAttributeEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsProductSpecificItemBatchAttributeEntity</a>|
|[OptimalDate](#OptimalDate)||<a href="PdsProductSpecificItemBatchAttributeEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsProductSpecificItemBatchAttributeEntity</a>|
|[OptimalEnumerate](#OptimalEnumerate)||<a href="PdsProductSpecificItemBatchAttributeEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsProductSpecificItemBatchAttributeEntity</a>|
|[MinimumIntegerTolerance](#MinimumIntegerTolerance)||<a href="PdsProductSpecificItemBatchAttributeEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsProductSpecificItemBatchAttributeEntity</a>|
|[MaximumIntegerTolerance](#MaximumIntegerTolerance)||<a href="PdsProductSpecificItemBatchAttributeEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsProductSpecificItemBatchAttributeEntity</a>|
|[IntegerToleranceIncrement](#IntegerToleranceIncrement)||<a href="PdsProductSpecificItemBatchAttributeEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsProductSpecificItemBatchAttributeEntity</a>|
|[OptimalInteger](#OptimalInteger)||<a href="PdsProductSpecificItemBatchAttributeEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsProductSpecificItemBatchAttributeEntity</a>|
|[MinimumDecimalTolerance](#MinimumDecimalTolerance)||<a href="PdsProductSpecificItemBatchAttributeEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsProductSpecificItemBatchAttributeEntity</a>|
|[MaximumDecimalTolerance](#MaximumDecimalTolerance)||<a href="PdsProductSpecificItemBatchAttributeEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsProductSpecificItemBatchAttributeEntity</a>|
|[DecimalToleranceIncrement](#DecimalToleranceIncrement)||<a href="PdsProductSpecificItemBatchAttributeEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsProductSpecificItemBatchAttributeEntity</a>|
|[OptimalDecimal](#OptimalDecimal)||<a href="PdsProductSpecificItemBatchAttributeEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsProductSpecificItemBatchAttributeEntity</a>|
|[ToleranceFailingAction](#ToleranceFailingAction)||<a href="PdsProductSpecificItemBatchAttributeEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsProductSpecificItemBatchAttributeEntity</a>|
|[IsPotencyAttribute](#IsPotencyAttribute)||<a href="PdsProductSpecificItemBatchAttributeEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsProductSpecificItemBatchAttributeEntity</a>|
|[BackingTable_PdsBatchAttribByItemRelationshipId](#BackingTable_PdsBatchAttribByItemRelationshipId)||<a href="PdsProductSpecificItemBatchAttributeEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsProductSpecificItemBatchAttributeEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="PdsProductSpecificItemBatchAttributeEntity.md" target="_blank">InventoryAndWarehouseManagement/PdsProductSpecificItemBatchAttributeEntity</a>|

### <a href=#ItemNumber name="ItemNumber">ItemNumber</a>

First included in: InventoryAndWarehouseManagement/PdsProductSpecificItemBatchAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BatchAttributeCode name="BatchAttributeCode">BatchAttributeCode</a>

First included in: InventoryAndWarehouseManagement/PdsProductSpecificItemBatchAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BatchAttributeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BatchAttributeRelation name="BatchAttributeRelation">BatchAttributeRelation</a>

First included in: InventoryAndWarehouseManagement/PdsProductSpecificItemBatchAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BatchAttributeRelation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemBatchAttributeId name="ItemBatchAttributeId">ItemBatchAttributeId</a>

First included in: InventoryAndWarehouseManagement/PdsProductSpecificItemBatchAttributeEntity (this entity)  

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

### <a href=#ItemBatchAttributeGroupId name="ItemBatchAttributeGroupId">ItemBatchAttributeGroupId</a>

First included in: InventoryAndWarehouseManagement/PdsProductSpecificItemBatchAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemBatchAttributeGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinimumTolerance name="MinimumTolerance">MinimumTolerance</a>

First included in: InventoryAndWarehouseManagement/PdsProductSpecificItemBatchAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumTolerance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumTolerance name="MaximumTolerance">MaximumTolerance</a>

First included in: InventoryAndWarehouseManagement/PdsProductSpecificItemBatchAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumTolerance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ToleranceIncrement name="ToleranceIncrement">ToleranceIncrement</a>

First included in: InventoryAndWarehouseManagement/PdsProductSpecificItemBatchAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToleranceIncrement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OptimalValue name="OptimalValue">OptimalValue</a>

First included in: InventoryAndWarehouseManagement/PdsProductSpecificItemBatchAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OptimalValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OptimalText name="OptimalText">OptimalText</a>

First included in: InventoryAndWarehouseManagement/PdsProductSpecificItemBatchAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>String target</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OptimalText attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>String target</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OptimalDate name="OptimalDate">OptimalDate</a>

First included in: InventoryAndWarehouseManagement/PdsProductSpecificItemBatchAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Date target</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OptimalDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date target</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OptimalEnumerate name="OptimalEnumerate">OptimalEnumerate</a>

First included in: InventoryAndWarehouseManagement/PdsProductSpecificItemBatchAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Enumerate target</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OptimalEnumerate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Enumerate target</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinimumIntegerTolerance name="MinimumIntegerTolerance">MinimumIntegerTolerance</a>

First included in: InventoryAndWarehouseManagement/PdsProductSpecificItemBatchAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Minimum integer tolerance</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumIntegerTolerance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Minimum integer tolerance</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumIntegerTolerance name="MaximumIntegerTolerance">MaximumIntegerTolerance</a>

First included in: InventoryAndWarehouseManagement/PdsProductSpecificItemBatchAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Maximum integer tolerance</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumIntegerTolerance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Maximum integer tolerance</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntegerToleranceIncrement name="IntegerToleranceIncrement">IntegerToleranceIncrement</a>

First included in: InventoryAndWarehouseManagement/PdsProductSpecificItemBatchAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Integer tolerance increment</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntegerToleranceIncrement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Integer tolerance increment</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OptimalInteger name="OptimalInteger">OptimalInteger</a>

First included in: InventoryAndWarehouseManagement/PdsProductSpecificItemBatchAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Integer target</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OptimalInteger attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Integer target</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinimumDecimalTolerance name="MinimumDecimalTolerance">MinimumDecimalTolerance</a>

First included in: InventoryAndWarehouseManagement/PdsProductSpecificItemBatchAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Minimum decimal tolerance</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumDecimalTolerance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Minimum decimal tolerance</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumDecimalTolerance name="MaximumDecimalTolerance">MaximumDecimalTolerance</a>

First included in: InventoryAndWarehouseManagement/PdsProductSpecificItemBatchAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Maximum decimal tolerance</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumDecimalTolerance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Maximum decimal tolerance</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DecimalToleranceIncrement name="DecimalToleranceIncrement">DecimalToleranceIncrement</a>

First included in: InventoryAndWarehouseManagement/PdsProductSpecificItemBatchAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Decimal tolerance increment</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DecimalToleranceIncrement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Decimal tolerance increment</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OptimalDecimal name="OptimalDecimal">OptimalDecimal</a>

First included in: InventoryAndWarehouseManagement/PdsProductSpecificItemBatchAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Decimal target</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OptimalDecimal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Decimal target</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ToleranceFailingAction name="ToleranceFailingAction">ToleranceFailingAction</a>

First included in: InventoryAndWarehouseManagement/PdsProductSpecificItemBatchAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToleranceFailingAction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPotencyAttribute name="IsPotencyAttribute">IsPotencyAttribute</a>

First included in: InventoryAndWarehouseManagement/PdsProductSpecificItemBatchAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPotencyAttribute attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_PdsBatchAttribByItemRelationshipId name="BackingTable_PdsBatchAttribByItemRelationshipId">BackingTable_PdsBatchAttribByItemRelationshipId</a>

First included in: InventoryAndWarehouseManagement/PdsProductSpecificItemBatchAttributeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PdsBatchAttribByItemRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Main/PdsBatchAttribByItem.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/PdsBatchAttribByItem.cdm.json/PdsBatchAttribByItem</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Main/PdsBatchAttribByItem.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/PdsProductSpecificItemBatchAttributeEntity (this entity)  

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
