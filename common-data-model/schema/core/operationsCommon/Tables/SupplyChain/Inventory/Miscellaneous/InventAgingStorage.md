---
title: InventAgingStorage in Miscellaneous - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/7/2020
ms.author: nebanfic
---

# InventAgingStorage in Miscellaneous

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/Inventory/Miscellaneous/InventAgingStorage.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[InventAgingStorage/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="InventAgingStorage.md" target="_blank">Miscellaneous/InventAgingStorage</a>|
|[TransactionId](#TransactionId)||<a href="InventAgingStorage.md" target="_blank">Miscellaneous/InventAgingStorage</a>|
|[ExecutionName](#ExecutionName)||<a href="InventAgingStorage.md" target="_blank">Miscellaneous/InventAgingStorage</a>|
|[ExecutionTime](#ExecutionTime)||<a href="InventAgingStorage.md" target="_blank">Miscellaneous/InventAgingStorage</a>|
|[AsOnDate](#AsOnDate)||<a href="InventAgingStorage.md" target="_blank">Miscellaneous/InventAgingStorage</a>|
|[AgingPeriodUnit](#AgingPeriodUnit)||<a href="InventAgingStorage.md" target="_blank">Miscellaneous/InventAgingStorage</a>|
|[IntervalDateOne](#IntervalDateOne)||<a href="InventAgingStorage.md" target="_blank">Miscellaneous/InventAgingStorage</a>|
|[IntervalDateTwo](#IntervalDateTwo)||<a href="InventAgingStorage.md" target="_blank">Miscellaneous/InventAgingStorage</a>|
|[IntervalDateThree](#IntervalDateThree)||<a href="InventAgingStorage.md" target="_blank">Miscellaneous/InventAgingStorage</a>|
|[IntervalDateFour](#IntervalDateFour)||<a href="InventAgingStorage.md" target="_blank">Miscellaneous/InventAgingStorage</a>|
|[IntervalDatePeriodOne](#IntervalDatePeriodOne)||<a href="InventAgingStorage.md" target="_blank">Miscellaneous/InventAgingStorage</a>|
|[IntervalDatePeriodTwo](#IntervalDatePeriodTwo)||<a href="InventAgingStorage.md" target="_blank">Miscellaneous/InventAgingStorage</a>|
|[IntervalDatePeriodThree](#IntervalDatePeriodThree)||<a href="InventAgingStorage.md" target="_blank">Miscellaneous/InventAgingStorage</a>|
|[IntervalDatePeriodFour](#IntervalDatePeriodFour)||<a href="InventAgingStorage.md" target="_blank">Miscellaneous/InventAgingStorage</a>|
|[IntervalDaysOne](#IntervalDaysOne)||<a href="InventAgingStorage.md" target="_blank">Miscellaneous/InventAgingStorage</a>|
|[IntervalDaysTwo](#IntervalDaysTwo)||<a href="InventAgingStorage.md" target="_blank">Miscellaneous/InventAgingStorage</a>|
|[IntervalDaysThree](#IntervalDaysThree)||<a href="InventAgingStorage.md" target="_blank">Miscellaneous/InventAgingStorage</a>|
|[IntervalDaysFour](#IntervalDaysFour)||<a href="InventAgingStorage.md" target="_blank">Miscellaneous/InventAgingStorage</a>|
|[ViewConfigId](#ViewConfigId)||<a href="InventAgingStorage.md" target="_blank">Miscellaneous/InventAgingStorage</a>|
|[ViewInventBatchId](#ViewInventBatchId)||<a href="InventAgingStorage.md" target="_blank">Miscellaneous/InventAgingStorage</a>|
|[ViewInventColorId](#ViewInventColorId)||<a href="InventAgingStorage.md" target="_blank">Miscellaneous/InventAgingStorage</a>|
|[ViewInventLocationId](#ViewInventLocationId)||<a href="InventAgingStorage.md" target="_blank">Miscellaneous/InventAgingStorage</a>|
|[ViewInventSerialId](#ViewInventSerialId)||<a href="InventAgingStorage.md" target="_blank">Miscellaneous/InventAgingStorage</a>|
|[ViewInventSiteId](#ViewInventSiteId)||<a href="InventAgingStorage.md" target="_blank">Miscellaneous/InventAgingStorage</a>|
|[ViewInventSizeId](#ViewInventSizeId)||<a href="InventAgingStorage.md" target="_blank">Miscellaneous/InventAgingStorage</a>|
|[ViewInventStatusId](#ViewInventStatusId)||<a href="InventAgingStorage.md" target="_blank">Miscellaneous/InventAgingStorage</a>|
|[ViewInventStyleId](#ViewInventStyleId)||<a href="InventAgingStorage.md" target="_blank">Miscellaneous/InventAgingStorage</a>|
|[ViewInventVersionId](#ViewInventVersionId)||<a href="InventAgingStorage.md" target="_blank">Miscellaneous/InventAgingStorage</a>|
|[ViewInventGTDId_RU](#ViewInventGTDId_RU)||<a href="InventAgingStorage.md" target="_blank">Miscellaneous/InventAgingStorage</a>|
|[ViewInventOwnerId_RU](#ViewInventOwnerId_RU)||<a href="InventAgingStorage.md" target="_blank">Miscellaneous/InventAgingStorage</a>|
|[ViewInventProfileId_RU](#ViewInventProfileId_RU)||<a href="InventAgingStorage.md" target="_blank">Miscellaneous/InventAgingStorage</a>|
|[ViewLicensePlateId](#ViewLicensePlateId)||<a href="InventAgingStorage.md" target="_blank">Miscellaneous/InventAgingStorage</a>|
|[ViewWMSLocationId](#ViewWMSLocationId)||<a href="InventAgingStorage.md" target="_blank">Miscellaneous/InventAgingStorage</a>|
|[ViewItem](#ViewItem)||<a href="InventAgingStorage.md" target="_blank">Miscellaneous/InventAgingStorage</a>|
|[ViewItemGroup](#ViewItemGroup)||<a href="InventAgingStorage.md" target="_blank">Miscellaneous/InventAgingStorage</a>|
|[ViewDimension1](#ViewDimension1)||<a href="InventAgingStorage.md" target="_blank">Miscellaneous/InventAgingStorage</a>|
|[ViewDimension2](#ViewDimension2)||<a href="InventAgingStorage.md" target="_blank">Miscellaneous/InventAgingStorage</a>|
|[ViewDimension3](#ViewDimension3)||<a href="InventAgingStorage.md" target="_blank">Miscellaneous/InventAgingStorage</a>|
|[ViewDimension4](#ViewDimension4)||<a href="InventAgingStorage.md" target="_blank">Miscellaneous/InventAgingStorage</a>|
|[ViewDimension5](#ViewDimension5)||<a href="InventAgingStorage.md" target="_blank">Miscellaneous/InventAgingStorage</a>|
|[ViewDimension6](#ViewDimension6)||<a href="InventAgingStorage.md" target="_blank">Miscellaneous/InventAgingStorage</a>|
|[ViewDimension7](#ViewDimension7)||<a href="InventAgingStorage.md" target="_blank">Miscellaneous/InventAgingStorage</a>|
|[ViewDimension8](#ViewDimension8)||<a href="InventAgingStorage.md" target="_blank">Miscellaneous/InventAgingStorage</a>|
|[ViewDimension9](#ViewDimension9)||<a href="InventAgingStorage.md" target="_blank">Miscellaneous/InventAgingStorage</a>|
|[ViewDimension10](#ViewDimension10)||<a href="InventAgingStorage.md" target="_blank">Miscellaneous/InventAgingStorage</a>|
|[ViewDimension11](#ViewDimension11)||<a href="InventAgingStorage.md" target="_blank">Miscellaneous/InventAgingStorage</a>|
|[ViewDimension12](#ViewDimension12)||<a href="InventAgingStorage.md" target="_blank">Miscellaneous/InventAgingStorage</a>|
|[Filters](#Filters)||<a href="InventAgingStorage.md" target="_blank">Miscellaneous/InventAgingStorage</a>|
|[DataAreaId](#DataAreaId)||<a href="InventAgingStorage.md" target="_blank">Miscellaneous/InventAgingStorage</a>|
|[Relationship_InventAgingTmpRelationshipId](#Relationship_InventAgingTmpRelationshipId)||<a href="InventAgingStorage.md" target="_blank">Miscellaneous/InventAgingStorage</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="InventAgingStorage.md" target="_blank">Miscellaneous/InventAgingStorage</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/InventAgingStorage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[InventAgingStorage/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TransactionId name="TransactionId">TransactionId</a>

First included in: Miscellaneous/InventAgingStorage (this entity)  

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

First included in: Miscellaneous/InventAgingStorage (this entity)  

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

First included in: Miscellaneous/InventAgingStorage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExecutionTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AsOnDate name="AsOnDate">AsOnDate</a>

First included in: Miscellaneous/InventAgingStorage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>As of date</td></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AsOnDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>As of date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.date**  
</details>

### <a href=#AgingPeriodUnit name="AgingPeriodUnit">AgingPeriodUnit</a>

First included in: Miscellaneous/InventAgingStorage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Unit of aging period</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgingPeriodUnit attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unit of aging period</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#IntervalDateOne name="IntervalDateOne">IntervalDateOne</a>

First included in: Miscellaneous/InventAgingStorage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Aging period 1</td></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntervalDateOne attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Aging period 1</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.date**  
</details>

### <a href=#IntervalDateTwo name="IntervalDateTwo">IntervalDateTwo</a>

First included in: Miscellaneous/InventAgingStorage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Aging period 2</td></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntervalDateTwo attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Aging period 2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.date**  
</details>

### <a href=#IntervalDateThree name="IntervalDateThree">IntervalDateThree</a>

First included in: Miscellaneous/InventAgingStorage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Aging period 3</td></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntervalDateThree attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Aging period 3</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.date**  
</details>

### <a href=#IntervalDateFour name="IntervalDateFour">IntervalDateFour</a>

First included in: Miscellaneous/InventAgingStorage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Aging period 4</td></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntervalDateFour attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Aging period 4</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.date**  
</details>

### <a href=#IntervalDatePeriodOne name="IntervalDatePeriodOne">IntervalDatePeriodOne</a>

First included in: Miscellaneous/InventAgingStorage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Aging period 1</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntervalDatePeriodOne attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Aging period 1</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntervalDatePeriodTwo name="IntervalDatePeriodTwo">IntervalDatePeriodTwo</a>

First included in: Miscellaneous/InventAgingStorage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Aging period 2</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntervalDatePeriodTwo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Aging period 2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntervalDatePeriodThree name="IntervalDatePeriodThree">IntervalDatePeriodThree</a>

First included in: Miscellaneous/InventAgingStorage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Aging period 3</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntervalDatePeriodThree attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Aging period 3</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntervalDatePeriodFour name="IntervalDatePeriodFour">IntervalDatePeriodFour</a>

First included in: Miscellaneous/InventAgingStorage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Aging period 4</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntervalDatePeriodFour attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Aging period 4</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntervalDaysOne name="IntervalDaysOne">IntervalDaysOne</a>

First included in: Miscellaneous/InventAgingStorage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Aging period 1</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntervalDaysOne attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Aging period 1</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#IntervalDaysTwo name="IntervalDaysTwo">IntervalDaysTwo</a>

First included in: Miscellaneous/InventAgingStorage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Aging period 2</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntervalDaysTwo attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Aging period 2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#IntervalDaysThree name="IntervalDaysThree">IntervalDaysThree</a>

First included in: Miscellaneous/InventAgingStorage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Aging period 3</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntervalDaysThree attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Aging period 3</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#IntervalDaysFour name="IntervalDaysFour">IntervalDaysFour</a>

First included in: Miscellaneous/InventAgingStorage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Aging period 4</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntervalDaysFour attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Aging period 4</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ViewConfigId name="ViewConfigId">ViewConfigId</a>

First included in: Miscellaneous/InventAgingStorage (this entity)  

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

First included in: Miscellaneous/InventAgingStorage (this entity)  

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

First included in: Miscellaneous/InventAgingStorage (this entity)  

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

### <a href=#ViewInventLocationId name="ViewInventLocationId">ViewInventLocationId</a>

First included in: Miscellaneous/InventAgingStorage (this entity)  

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

First included in: Miscellaneous/InventAgingStorage (this entity)  

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

First included in: Miscellaneous/InventAgingStorage (this entity)  

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

First included in: Miscellaneous/InventAgingStorage (this entity)  

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

### <a href=#ViewInventStatusId name="ViewInventStatusId">ViewInventStatusId</a>

First included in: Miscellaneous/InventAgingStorage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewInventStatusId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ViewInventStyleId name="ViewInventStyleId">ViewInventStyleId</a>

First included in: Miscellaneous/InventAgingStorage (this entity)  

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

First included in: Miscellaneous/InventAgingStorage (this entity)  

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

### <a href=#ViewInventGTDId_RU name="ViewInventGTDId_RU">ViewInventGTDId_RU</a>

First included in: Miscellaneous/InventAgingStorage (this entity)  

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

First included in: Miscellaneous/InventAgingStorage (this entity)  

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

First included in: Miscellaneous/InventAgingStorage (this entity)  

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

### <a href=#ViewLicensePlateId name="ViewLicensePlateId">ViewLicensePlateId</a>

First included in: Miscellaneous/InventAgingStorage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewLicensePlateId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ViewWMSLocationId name="ViewWMSLocationId">ViewWMSLocationId</a>

First included in: Miscellaneous/InventAgingStorage (this entity)  

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

### <a href=#ViewItem name="ViewItem">ViewItem</a>

First included in: Miscellaneous/InventAgingStorage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Item number</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewItem attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Item number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ViewItemGroup name="ViewItemGroup">ViewItemGroup</a>

First included in: Miscellaneous/InventAgingStorage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Item group</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewItemGroup attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Item group</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ViewDimension1 name="ViewDimension1">ViewDimension1</a>

First included in: Miscellaneous/InventAgingStorage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewDimension1 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ViewDimension2 name="ViewDimension2">ViewDimension2</a>

First included in: Miscellaneous/InventAgingStorage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewDimension2 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ViewDimension3 name="ViewDimension3">ViewDimension3</a>

First included in: Miscellaneous/InventAgingStorage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewDimension3 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ViewDimension4 name="ViewDimension4">ViewDimension4</a>

First included in: Miscellaneous/InventAgingStorage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewDimension4 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ViewDimension5 name="ViewDimension5">ViewDimension5</a>

First included in: Miscellaneous/InventAgingStorage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewDimension5 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ViewDimension6 name="ViewDimension6">ViewDimension6</a>

First included in: Miscellaneous/InventAgingStorage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewDimension6 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ViewDimension7 name="ViewDimension7">ViewDimension7</a>

First included in: Miscellaneous/InventAgingStorage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewDimension7 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ViewDimension8 name="ViewDimension8">ViewDimension8</a>

First included in: Miscellaneous/InventAgingStorage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewDimension8 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ViewDimension9 name="ViewDimension9">ViewDimension9</a>

First included in: Miscellaneous/InventAgingStorage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewDimension9 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ViewDimension10 name="ViewDimension10">ViewDimension10</a>

First included in: Miscellaneous/InventAgingStorage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewDimension10 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ViewDimension11 name="ViewDimension11">ViewDimension11</a>

First included in: Miscellaneous/InventAgingStorage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewDimension11 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ViewDimension12 name="ViewDimension12">ViewDimension12</a>

First included in: Miscellaneous/InventAgingStorage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ViewDimension12 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Filters name="Filters">Filters</a>

First included in: Miscellaneous/InventAgingStorage (this entity)  

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

First included in: Miscellaneous/InventAgingStorage (this entity)  

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

### <a href=#Relationship_InventAgingTmpRelationshipId name="Relationship_InventAgingTmpRelationshipId">Relationship_InventAgingTmpRelationshipId</a>

First included in: Miscellaneous/InventAgingStorage (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventAgingTmpRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="InventAgingTmp.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Miscellaneous/InventAgingTmp.cdm.json/InventAgingTmp</a></td><td><a href="InventAgingTmp.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Miscellaneous/InventAgingStorage (this entity)  

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
