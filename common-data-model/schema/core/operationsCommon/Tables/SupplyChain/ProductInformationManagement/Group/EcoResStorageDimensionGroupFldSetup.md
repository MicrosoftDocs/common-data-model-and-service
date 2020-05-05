---
title: EcoResStorageDimensionGroupFldSetup - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 5/5/2020
ms.author: nebanfic
---

# Storage dimension group fields setup

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Group/EcoResStorageDimensionGroupFldSetup.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[EcoResStorageDimensionGroupFldSetup/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Storage dimension group fields setup</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="EcoResStorageDimensionGroupFldSetup.md" target="_blank">Group/EcoResStorageDimensionGroupFldSetup</a>|
|[DimensionFieldId](#DimensionFieldId)||<a href="EcoResStorageDimensionGroupFldSetup.md" target="_blank">Group/EcoResStorageDimensionGroupFldSetup</a>|
|[IsActive](#IsActive)||<a href="EcoResStorageDimensionGroupFldSetup.md" target="_blank">Group/EcoResStorageDimensionGroupFldSetup</a>|
|[IsAllowBlankIssueEnabled](#IsAllowBlankIssueEnabled)||<a href="EcoResStorageDimensionGroupFldSetup.md" target="_blank">Group/EcoResStorageDimensionGroupFldSetup</a>|
|[IsAllowBlankReceiptEnabled](#IsAllowBlankReceiptEnabled)||<a href="EcoResStorageDimensionGroupFldSetup.md" target="_blank">Group/EcoResStorageDimensionGroupFldSetup</a>|
|[IsCoveragePlanByDimensionEnabled](#IsCoveragePlanByDimensionEnabled)||<a href="EcoResStorageDimensionGroupFldSetup.md" target="_blank">Group/EcoResStorageDimensionGroupFldSetup</a>|
|[IsFinancialInventoryEnabled](#IsFinancialInventoryEnabled)||<a href="EcoResStorageDimensionGroupFldSetup.md" target="_blank">Group/EcoResStorageDimensionGroupFldSetup</a>|
|[IsPhysicalInventoryEnabled](#IsPhysicalInventoryEnabled)||<a href="EcoResStorageDimensionGroupFldSetup.md" target="_blank">Group/EcoResStorageDimensionGroupFldSetup</a>|
|[IsPurchPriceSearchEnabled](#IsPurchPriceSearchEnabled)||<a href="EcoResStorageDimensionGroupFldSetup.md" target="_blank">Group/EcoResStorageDimensionGroupFldSetup</a>|
|[IsSalesPriceSearchEnabled](#IsSalesPriceSearchEnabled)||<a href="EcoResStorageDimensionGroupFldSetup.md" target="_blank">Group/EcoResStorageDimensionGroupFldSetup</a>|
|[LineNumber](#LineNumber)||<a href="EcoResStorageDimensionGroupFldSetup.md" target="_blank">Group/EcoResStorageDimensionGroupFldSetup</a>|
|[StorageDimensionGroup](#StorageDimensionGroup)||<a href="EcoResStorageDimensionGroupFldSetup.md" target="_blank">Group/EcoResStorageDimensionGroupFldSetup</a>|
|[Relationship_EcoResStorageDimensionGroupRelationshipId](#Relationship_EcoResStorageDimensionGroupRelationshipId)||<a href="EcoResStorageDimensionGroupFldSetup.md" target="_blank">Group/EcoResStorageDimensionGroupFldSetup</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Group/EcoResStorageDimensionGroupFldSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[EcoResStorageDimensionGroupFldSetup/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DimensionFieldId name="DimensionFieldId">DimensionFieldId</a>

First included in: Group/EcoResStorageDimensionGroupFldSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionFieldId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsActive name="IsActive">IsActive</a>

First included in: Group/EcoResStorageDimensionGroupFldSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Active</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsActive attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Active</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#IsAllowBlankIssueEnabled name="IsAllowBlankIssueEnabled">IsAllowBlankIssueEnabled</a>

First included in: Group/EcoResStorageDimensionGroupFldSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsAllowBlankIssueEnabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#IsAllowBlankReceiptEnabled name="IsAllowBlankReceiptEnabled">IsAllowBlankReceiptEnabled</a>

First included in: Group/EcoResStorageDimensionGroupFldSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsAllowBlankReceiptEnabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#IsCoveragePlanByDimensionEnabled name="IsCoveragePlanByDimensionEnabled">IsCoveragePlanByDimensionEnabled</a>

First included in: Group/EcoResStorageDimensionGroupFldSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCoveragePlanByDimensionEnabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#IsFinancialInventoryEnabled name="IsFinancialInventoryEnabled">IsFinancialInventoryEnabled</a>

First included in: Group/EcoResStorageDimensionGroupFldSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsFinancialInventoryEnabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#IsPhysicalInventoryEnabled name="IsPhysicalInventoryEnabled">IsPhysicalInventoryEnabled</a>

First included in: Group/EcoResStorageDimensionGroupFldSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPhysicalInventoryEnabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#IsPurchPriceSearchEnabled name="IsPurchPriceSearchEnabled">IsPurchPriceSearchEnabled</a>

First included in: Group/EcoResStorageDimensionGroupFldSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPurchPriceSearchEnabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#IsSalesPriceSearchEnabled name="IsSalesPriceSearchEnabled">IsSalesPriceSearchEnabled</a>

First included in: Group/EcoResStorageDimensionGroupFldSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSalesPriceSearchEnabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: Group/EcoResStorageDimensionGroupFldSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNumber attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#StorageDimensionGroup name="StorageDimensionGroup">StorageDimensionGroup</a>

First included in: Group/EcoResStorageDimensionGroupFldSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StorageDimensionGroup attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_EcoResStorageDimensionGroupRelationshipId name="Relationship_EcoResStorageDimensionGroupRelationshipId">Relationship_EcoResStorageDimensionGroupRelationshipId</a>

First included in: Group/EcoResStorageDimensionGroupFldSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EcoResStorageDimensionGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="EcoResStorageDimensionGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Group/EcoResStorageDimensionGroup.cdm.json/EcoResStorageDimensionGroup</a></td><td><a href="EcoResStorageDimensionGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
