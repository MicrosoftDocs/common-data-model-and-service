---
title: BOMParmReportFinish - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# BOMParmReportFinish

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Worksheet/BOMParmReportFinish.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BOMParmReportFinish/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="BOMParmReportFinish.md" target="_blank">Worksheet/BOMParmReportFinish</a>|
|[BOMId](#BOMId)||<a href="BOMParmReportFinish.md" target="_blank">Worksheet/BOMParmReportFinish</a>|
|[DefaultDimension](#DefaultDimension)||<a href="BOMParmReportFinish.md" target="_blank">Worksheet/BOMParmReportFinish</a>|
|[Density](#Density)||<a href="BOMParmReportFinish.md" target="_blank">Worksheet/BOMParmReportFinish</a>|
|[Depth](#Depth)||<a href="BOMParmReportFinish.md" target="_blank">Worksheet/BOMParmReportFinish</a>|
|[Explode](#Explode)||<a href="BOMParmReportFinish.md" target="_blank">Worksheet/BOMParmReportFinish</a>|
|[Height](#Height)||<a href="BOMParmReportFinish.md" target="_blank">Worksheet/BOMParmReportFinish</a>|
|[Info](#Info)||<a href="BOMParmReportFinish.md" target="_blank">Worksheet/BOMParmReportFinish</a>|
|[InventDimId](#InventDimId)||<a href="BOMParmReportFinish.md" target="_blank">Worksheet/BOMParmReportFinish</a>|
|[InventTransIdReturn](#InventTransIdReturn)||<a href="BOMParmReportFinish.md" target="_blank">Worksheet/BOMParmReportFinish</a>|
|[ItemId](#ItemId)||<a href="BOMParmReportFinish.md" target="_blank">Worksheet/BOMParmReportFinish</a>|
|[JournalId](#JournalId)||<a href="BOMParmReportFinish.md" target="_blank">Worksheet/BOMParmReportFinish</a>|
|[JournalNameId](#JournalNameId)||<a href="BOMParmReportFinish.md" target="_blank">Worksheet/BOMParmReportFinish</a>|
|[LineNum](#LineNum)||<a href="BOMParmReportFinish.md" target="_blank">Worksheet/BOMParmReportFinish</a>|
|[OverrideDimension](#OverrideDimension)||<a href="BOMParmReportFinish.md" target="_blank">Worksheet/BOMParmReportFinish</a>|
|[ParmId](#ParmId)||<a href="BOMParmReportFinish.md" target="_blank">Worksheet/BOMParmReportFinish</a>|
|[PdsCWQty](#PdsCWQty)||<a href="BOMParmReportFinish.md" target="_blank">Worksheet/BOMParmReportFinish</a>|
|[PostNow](#PostNow)||<a href="BOMParmReportFinish.md" target="_blank">Worksheet/BOMParmReportFinish</a>|
|[ProfitSet](#ProfitSet)||<a href="BOMParmReportFinish.md" target="_blank">Worksheet/BOMParmReportFinish</a>|
|[Qty](#Qty)||<a href="BOMParmReportFinish.md" target="_blank">Worksheet/BOMParmReportFinish</a>|
|[ReturnCostPrice](#ReturnCostPrice)||<a href="BOMParmReportFinish.md" target="_blank">Worksheet/BOMParmReportFinish</a>|
|[TransDate](#TransDate)||<a href="BOMParmReportFinish.md" target="_blank">Worksheet/BOMParmReportFinish</a>|
|[Width](#Width)||<a href="BOMParmReportFinish.md" target="_blank">Worksheet/BOMParmReportFinish</a>|
|[PackedExtensions](#PackedExtensions)||<a href="BOMParmReportFinish.md" target="_blank">Worksheet/BOMParmReportFinish</a>|
|[DataAreaId](#DataAreaId)||<a href="BOMParmReportFinish.md" target="_blank">Worksheet/BOMParmReportFinish</a>|
|[Relationship_BOMTableRelationshipId](#Relationship_BOMTableRelationshipId)||<a href="BOMParmReportFinish.md" target="_blank">Worksheet/BOMParmReportFinish</a>|
|[Relationship_DefaultDimensionRelationshipId](#Relationship_DefaultDimensionRelationshipId)||<a href="BOMParmReportFinish.md" target="_blank">Worksheet/BOMParmReportFinish</a>|
|[Relationship_InventDimRelationshipId](#Relationship_InventDimRelationshipId)||<a href="BOMParmReportFinish.md" target="_blank">Worksheet/BOMParmReportFinish</a>|
|[Relationship_InventJournalNameRelationshipId](#Relationship_InventJournalNameRelationshipId)||<a href="BOMParmReportFinish.md" target="_blank">Worksheet/BOMParmReportFinish</a>|
|[Relationship_InventJournalTableRelationshipId](#Relationship_InventJournalTableRelationshipId)||<a href="BOMParmReportFinish.md" target="_blank">Worksheet/BOMParmReportFinish</a>|
|[Relationship_InventTableRelationshipId](#Relationship_InventTableRelationshipId)||<a href="BOMParmReportFinish.md" target="_blank">Worksheet/BOMParmReportFinish</a>|
|[Relationship_InventTransOriginRelationshipId](#Relationship_InventTransOriginRelationshipId)||<a href="BOMParmReportFinish.md" target="_blank">Worksheet/BOMParmReportFinish</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="BOMParmReportFinish.md" target="_blank">Worksheet/BOMParmReportFinish</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Worksheet/BOMParmReportFinish (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BOMParmReportFinish/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BOMId name="BOMId">BOMId</a>

First included in: Worksheet/BOMParmReportFinish (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BOMId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimension name="DefaultDimension">DefaultDimension</a>

First included in: Worksheet/BOMParmReportFinish (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Density name="Density">Density</a>

First included in: Worksheet/BOMParmReportFinish (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Density attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Depth name="Depth">Depth</a>

First included in: Worksheet/BOMParmReportFinish (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Depth attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Explode name="Explode">Explode</a>

First included in: Worksheet/BOMParmReportFinish (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Explode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Height name="Height">Height</a>

First included in: Worksheet/BOMParmReportFinish (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Height attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Info name="Info">Info</a>

First included in: Worksheet/BOMParmReportFinish (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Info attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InventDimId name="InventDimId">InventDimId</a>

First included in: Worksheet/BOMParmReportFinish (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventDimId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventTransIdReturn name="InventTransIdReturn">InventTransIdReturn</a>

First included in: Worksheet/BOMParmReportFinish (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTransIdReturn attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemId name="ItemId">ItemId</a>

First included in: Worksheet/BOMParmReportFinish (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JournalId name="JournalId">JournalId</a>

First included in: Worksheet/BOMParmReportFinish (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JournalNameId name="JournalNameId">JournalNameId</a>

First included in: Worksheet/BOMParmReportFinish (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNum name="LineNum">LineNum</a>

First included in: Worksheet/BOMParmReportFinish (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNum attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#OverrideDimension name="OverrideDimension">OverrideDimension</a>

First included in: Worksheet/BOMParmReportFinish (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OverrideDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ParmId name="ParmId">ParmId</a>

First included in: Worksheet/BOMParmReportFinish (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParmId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PdsCWQty name="PdsCWQty">PdsCWQty</a>

First included in: Worksheet/BOMParmReportFinish (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PdsCWQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PostNow name="PostNow">PostNow</a>

First included in: Worksheet/BOMParmReportFinish (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostNow attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ProfitSet name="ProfitSet">ProfitSet</a>

First included in: Worksheet/BOMParmReportFinish (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProfitSet attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Qty name="Qty">Qty</a>

First included in: Worksheet/BOMParmReportFinish (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Qty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ReturnCostPrice name="ReturnCostPrice">ReturnCostPrice</a>

First included in: Worksheet/BOMParmReportFinish (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnCostPrice attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TransDate name="TransDate">TransDate</a>

First included in: Worksheet/BOMParmReportFinish (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#Width name="Width">Width</a>

First included in: Worksheet/BOMParmReportFinish (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Width attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PackedExtensions name="PackedExtensions">PackedExtensions</a>

First included in: Worksheet/BOMParmReportFinish (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackedExtensions attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Worksheet/BOMParmReportFinish (this entity)  

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

### <a href=#Relationship_BOMTableRelationshipId name="Relationship_BOMTableRelationshipId">Relationship_BOMTableRelationshipId</a>

First included in: Worksheet/BOMParmReportFinish (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BOMTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/BOMTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/BOMTable.cdm.json/BOMTable</a></td><td><a href="../Main/BOMTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultDimensionRelationshipId name="Relationship_DefaultDimensionRelationshipId">Relationship_DefaultDimensionRelationshipId</a>

First included in: Worksheet/BOMParmReportFinish (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/FinancialDimensions/Main/DimensionAttributeValueSet.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueSet.cdm.json/DimensionAttributeValueSet</a></td><td><a href="../../../Finance/FinancialDimensions/Main/DimensionAttributeValueSet.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventDimRelationshipId name="Relationship_InventDimRelationshipId">Relationship_InventDimRelationshipId</a>

First included in: Worksheet/BOMParmReportFinish (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventDimRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Inventory/Main/InventDim.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/InventDim.cdm.json/InventDim</a></td><td><a href="../../Inventory/Main/InventDim.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventJournalNameRelationshipId name="Relationship_InventJournalNameRelationshipId">Relationship_InventJournalNameRelationshipId</a>

First included in: Worksheet/BOMParmReportFinish (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventJournalNameRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Inventory/Group/InventJournalName.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/InventJournalName.cdm.json/InventJournalName</a></td><td><a href="../../Inventory/Group/InventJournalName.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventJournalTableRelationshipId name="Relationship_InventJournalTableRelationshipId">Relationship_InventJournalTableRelationshipId</a>

First included in: Worksheet/BOMParmReportFinish (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventJournalTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Inventory/WorksheetHeader/InventJournalTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/WorksheetHeader/InventJournalTable.cdm.json/InventJournalTable</a></td><td><a href="../../Inventory/WorksheetHeader/InventJournalTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventTableRelationshipId name="Relationship_InventTableRelationshipId">Relationship_InventTableRelationshipId</a>

First included in: Worksheet/BOMParmReportFinish (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/InventTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/InventTable.cdm.json/InventTable</a></td><td><a href="../Main/InventTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventTransOriginRelationshipId name="Relationship_InventTransOriginRelationshipId">Relationship_InventTransOriginRelationshipId</a>

First included in: Worksheet/BOMParmReportFinish (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventTransOriginRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Inventory/Transaction/InventTransOrigin.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Transaction/InventTransOrigin.cdm.json/InventTransOrigin</a></td><td><a href="../../Inventory/Transaction/InventTransOrigin.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Worksheet/BOMParmReportFinish (this entity)  

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
