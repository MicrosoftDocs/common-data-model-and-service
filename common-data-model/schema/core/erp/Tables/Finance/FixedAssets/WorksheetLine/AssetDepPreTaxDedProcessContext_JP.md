---
title: AssetDepPreTaxDedProcessContext_JP - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# AssetDepPreTaxDedProcessContext_JP

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Finance/FixedAssets/WorksheetLine/AssetDepPreTaxDedProcessContext_JP.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[AssetDepPreTaxDedProcessContext_JP/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="AssetDepPreTaxDedProcessContext_JP.md" target="_blank">WorksheetLine/AssetDepPreTaxDedProcessContext_JP</a>|
|[AssetDepPreTaxDedProcess_JP](#AssetDepPreTaxDedProcess_JP)||<a href="AssetDepPreTaxDedProcessContext_JP.md" target="_blank">WorksheetLine/AssetDepPreTaxDedProcessContext_JP</a>|
|[AssetId](#AssetId)||<a href="AssetDepPreTaxDedProcessContext_JP.md" target="_blank">WorksheetLine/AssetDepPreTaxDedProcessContext_JP</a>|
|[BookId](#BookId)||<a href="AssetDepPreTaxDedProcessContext_JP.md" target="_blank">WorksheetLine/AssetDepPreTaxDedProcessContext_JP</a>|
|[BroughtForwardOverUnderAmount](#BroughtForwardOverUnderAmount)||<a href="AssetDepPreTaxDedProcessContext_JP.md" target="_blank">WorksheetLine/AssetDepPreTaxDedProcessContext_JP</a>|
|[BroughtForwardOverUnderAmountManualAdj](#BroughtForwardOverUnderAmountManualAdj)||<a href="AssetDepPreTaxDedProcessContext_JP.md" target="_blank">WorksheetLine/AssetDepPreTaxDedProcessContext_JP</a>|
|[BroughtForwardOverUnderAmountSettled](#BroughtForwardOverUnderAmountSettled)||<a href="AssetDepPreTaxDedProcessContext_JP.md" target="_blank">WorksheetLine/AssetDepPreTaxDedProcessContext_JP</a>|
|[CarryForwardOverUnderAmountManualAdj](#CarryForwardOverUnderAmountManualAdj)||<a href="AssetDepPreTaxDedProcessContext_JP.md" target="_blank">WorksheetLine/AssetDepPreTaxDedProcessContext_JP</a>|
|[CarryForwardOverUnderAmountRuleAdj](#CarryForwardOverUnderAmountRuleAdj)||<a href="AssetDepPreTaxDedProcessContext_JP.md" target="_blank">WorksheetLine/AssetDepPreTaxDedProcessContext_JP</a>|
|[CurrentTermAllowableLimit](#CurrentTermAllowableLimit)||<a href="AssetDepPreTaxDedProcessContext_JP.md" target="_blank">WorksheetLine/AssetDepPreTaxDedProcessContext_JP</a>|
|[CurrentTermCurrentLayerPostedAmount](#CurrentTermCurrentLayerPostedAmount)||<a href="AssetDepPreTaxDedProcessContext_JP.md" target="_blank">WorksheetLine/AssetDepPreTaxDedProcessContext_JP</a>|
|[CurrentTermOverUnderAmount](#CurrentTermOverUnderAmount)||<a href="AssetDepPreTaxDedProcessContext_JP.md" target="_blank">WorksheetLine/AssetDepPreTaxDedProcessContext_JP</a>|
|[CurrentTermOverUnderAmountSettled](#CurrentTermOverUnderAmountSettled)||<a href="AssetDepPreTaxDedProcessContext_JP.md" target="_blank">WorksheetLine/AssetDepPreTaxDedProcessContext_JP</a>|
|[CurrentTermPreTaxDedAmount](#CurrentTermPreTaxDedAmount)||<a href="AssetDepPreTaxDedProcessContext_JP.md" target="_blank">WorksheetLine/AssetDepPreTaxDedProcessContext_JP</a>|
|[CurrentTermTaxLayerNewAmountToPost](#CurrentTermTaxLayerNewAmountToPost)||<a href="AssetDepPreTaxDedProcessContext_JP.md" target="_blank">WorksheetLine/AssetDepPreTaxDedProcessContext_JP</a>|
|[CurrentTermTaxLayerPostedAmount](#CurrentTermTaxLayerPostedAmount)||<a href="AssetDepPreTaxDedProcessContext_JP.md" target="_blank">WorksheetLine/AssetDepPreTaxDedProcessContext_JP</a>|
|[DepType](#DepType)||<a href="AssetDepPreTaxDedProcessContext_JP.md" target="_blank">WorksheetLine/AssetDepPreTaxDedProcessContext_JP</a>|
|[InclusionByOverUnderDepreciation](#InclusionByOverUnderDepreciation)||<a href="AssetDepPreTaxDedProcessContext_JP.md" target="_blank">WorksheetLine/AssetDepPreTaxDedProcessContext_JP</a>|
|[ReserveAllocationAmount](#ReserveAllocationAmount)||<a href="AssetDepPreTaxDedProcessContext_JP.md" target="_blank">WorksheetLine/AssetDepPreTaxDedProcessContext_JP</a>|
|[TotalRemainingOverUnderAmountManualAdj](#TotalRemainingOverUnderAmountManualAdj)||<a href="AssetDepPreTaxDedProcessContext_JP.md" target="_blank">WorksheetLine/AssetDepPreTaxDedProcessContext_JP</a>|
|[DataAreaId](#DataAreaId)||<a href="AssetDepPreTaxDedProcessContext_JP.md" target="_blank">WorksheetLine/AssetDepPreTaxDedProcessContext_JP</a>|
|[Relationship_AssetBookTableRelationshipId](#Relationship_AssetBookTableRelationshipId)||<a href="AssetDepPreTaxDedProcessContext_JP.md" target="_blank">WorksheetLine/AssetDepPreTaxDedProcessContext_JP</a>|
|[Relationship_AssetDepPreTaxDedProcess_JPRelationshipId](#Relationship_AssetDepPreTaxDedProcess_JPRelationshipId)||<a href="AssetDepPreTaxDedProcessContext_JP.md" target="_blank">WorksheetLine/AssetDepPreTaxDedProcessContext_JP</a>|
|[Relationship_AssetTableRelationshipId](#Relationship_AssetTableRelationshipId)||<a href="AssetDepPreTaxDedProcessContext_JP.md" target="_blank">WorksheetLine/AssetDepPreTaxDedProcessContext_JP</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="AssetDepPreTaxDedProcessContext_JP.md" target="_blank">WorksheetLine/AssetDepPreTaxDedProcessContext_JP</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetLine/AssetDepPreTaxDedProcessContext_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[AssetDepPreTaxDedProcessContext_JP/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AssetDepPreTaxDedProcess_JP name="AssetDepPreTaxDedProcess_JP">AssetDepPreTaxDedProcess_JP</a>

First included in: WorksheetLine/AssetDepPreTaxDedProcessContext_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetDepPreTaxDedProcess_JP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AssetId name="AssetId">AssetId</a>

First included in: WorksheetLine/AssetDepPreTaxDedProcessContext_JP (this entity)  

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

### <a href=#BookId name="BookId">BookId</a>

First included in: WorksheetLine/AssetDepPreTaxDedProcessContext_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BookId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BroughtForwardOverUnderAmount name="BroughtForwardOverUnderAmount">BroughtForwardOverUnderAmount</a>

First included in: WorksheetLine/AssetDepPreTaxDedProcessContext_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BroughtForwardOverUnderAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#BroughtForwardOverUnderAmountManualAdj name="BroughtForwardOverUnderAmountManualAdj">BroughtForwardOverUnderAmountManualAdj</a>

First included in: WorksheetLine/AssetDepPreTaxDedProcessContext_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BroughtForwardOverUnderAmountManualAdj attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#BroughtForwardOverUnderAmountSettled name="BroughtForwardOverUnderAmountSettled">BroughtForwardOverUnderAmountSettled</a>

First included in: WorksheetLine/AssetDepPreTaxDedProcessContext_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BroughtForwardOverUnderAmountSettled attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CarryForwardOverUnderAmountManualAdj name="CarryForwardOverUnderAmountManualAdj">CarryForwardOverUnderAmountManualAdj</a>

First included in: WorksheetLine/AssetDepPreTaxDedProcessContext_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CarryForwardOverUnderAmountManualAdj attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CarryForwardOverUnderAmountRuleAdj name="CarryForwardOverUnderAmountRuleAdj">CarryForwardOverUnderAmountRuleAdj</a>

First included in: WorksheetLine/AssetDepPreTaxDedProcessContext_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CarryForwardOverUnderAmountRuleAdj attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CurrentTermAllowableLimit name="CurrentTermAllowableLimit">CurrentTermAllowableLimit</a>

First included in: WorksheetLine/AssetDepPreTaxDedProcessContext_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrentTermAllowableLimit attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CurrentTermCurrentLayerPostedAmount name="CurrentTermCurrentLayerPostedAmount">CurrentTermCurrentLayerPostedAmount</a>

First included in: WorksheetLine/AssetDepPreTaxDedProcessContext_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrentTermCurrentLayerPostedAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CurrentTermOverUnderAmount name="CurrentTermOverUnderAmount">CurrentTermOverUnderAmount</a>

First included in: WorksheetLine/AssetDepPreTaxDedProcessContext_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrentTermOverUnderAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CurrentTermOverUnderAmountSettled name="CurrentTermOverUnderAmountSettled">CurrentTermOverUnderAmountSettled</a>

First included in: WorksheetLine/AssetDepPreTaxDedProcessContext_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrentTermOverUnderAmountSettled attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CurrentTermPreTaxDedAmount name="CurrentTermPreTaxDedAmount">CurrentTermPreTaxDedAmount</a>

First included in: WorksheetLine/AssetDepPreTaxDedProcessContext_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrentTermPreTaxDedAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CurrentTermTaxLayerNewAmountToPost name="CurrentTermTaxLayerNewAmountToPost">CurrentTermTaxLayerNewAmountToPost</a>

First included in: WorksheetLine/AssetDepPreTaxDedProcessContext_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrentTermTaxLayerNewAmountToPost attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CurrentTermTaxLayerPostedAmount name="CurrentTermTaxLayerPostedAmount">CurrentTermTaxLayerPostedAmount</a>

First included in: WorksheetLine/AssetDepPreTaxDedProcessContext_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrentTermTaxLayerPostedAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DepType name="DepType">DepType</a>

First included in: WorksheetLine/AssetDepPreTaxDedProcessContext_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InclusionByOverUnderDepreciation name="InclusionByOverUnderDepreciation">InclusionByOverUnderDepreciation</a>

First included in: WorksheetLine/AssetDepPreTaxDedProcessContext_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InclusionByOverUnderDepreciation attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ReserveAllocationAmount name="ReserveAllocationAmount">ReserveAllocationAmount</a>

First included in: WorksheetLine/AssetDepPreTaxDedProcessContext_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReserveAllocationAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TotalRemainingOverUnderAmountManualAdj name="TotalRemainingOverUnderAmountManualAdj">TotalRemainingOverUnderAmountManualAdj</a>

First included in: WorksheetLine/AssetDepPreTaxDedProcessContext_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalRemainingOverUnderAmountManualAdj attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetLine/AssetDepPreTaxDedProcessContext_JP (this entity)  

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

### <a href=#Relationship_AssetBookTableRelationshipId name="Relationship_AssetBookTableRelationshipId">Relationship_AssetBookTableRelationshipId</a>

First included in: WorksheetLine/AssetDepPreTaxDedProcessContext_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetBookTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/AssetBookTable.md" target="_blank">/core/erp/Tables/Finance/FixedAssets/Main/AssetBookTable.cdm.json/AssetBookTable</a></td><td><a href="../Main/AssetBookTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AssetDepPreTaxDedProcess_JPRelationshipId name="Relationship_AssetDepPreTaxDedProcess_JPRelationshipId">Relationship_AssetDepPreTaxDedProcess_JPRelationshipId</a>

First included in: WorksheetLine/AssetDepPreTaxDedProcessContext_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetDepPreTaxDedProcess_JPRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/AssetDepPreTaxDedProcess_JP.md" target="_blank">/core/erp/Tables/Finance/FixedAssets/WorksheetHeader/AssetDepPreTaxDedProcess_JP.cdm.json/AssetDepPreTaxDedProcess_JP</a></td><td><a href="../WorksheetHeader/AssetDepPreTaxDedProcess_JP.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AssetTableRelationshipId name="Relationship_AssetTableRelationshipId">Relationship_AssetTableRelationshipId</a>

First included in: WorksheetLine/AssetDepPreTaxDedProcessContext_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/AssetTable.md" target="_blank">/core/erp/Tables/Finance/FixedAssets/Main/AssetTable.cdm.json/AssetTable</a></td><td><a href="../Main/AssetTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetLine/AssetDepPreTaxDedProcessContext_JP (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Ledger/Main/CompanyInfo.md" target="_blank">/core/erp/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
