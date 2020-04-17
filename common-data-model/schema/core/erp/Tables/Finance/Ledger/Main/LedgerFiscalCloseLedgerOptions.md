---
title: LedgerFiscalCloseLedgerOptions - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# LedgerFiscalCloseLedgerOptions

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Finance/Ledger/Main/LedgerFiscalCloseLedgerOptions.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[LedgerFiscalCloseLedgerOptions/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="LedgerFiscalCloseLedgerOptions.md" target="_blank">Main/LedgerFiscalCloseLedgerOptions</a>|
|[LedgerFiscalCloseGroup](#LedgerFiscalCloseGroup)||<a href="LedgerFiscalCloseLedgerOptions.md" target="_blank">Main/LedgerFiscalCloseLedgerOptions</a>|
|[Ledger](#Ledger)||<a href="LedgerFiscalCloseLedgerOptions.md" target="_blank">Main/LedgerFiscalCloseLedgerOptions</a>|
|[RetainedEarningsMainAccount](#RetainedEarningsMainAccount)||<a href="LedgerFiscalCloseLedgerOptions.md" target="_blank">Main/LedgerFiscalCloseLedgerOptions</a>|
|[TransferBalanceSheetDimensions](#TransferBalanceSheetDimensions)||<a href="LedgerFiscalCloseLedgerOptions.md" target="_blank">Main/LedgerFiscalCloseLedgerOptions</a>|
|[ProfitLossCloseDimension](#ProfitLossCloseDimension)||<a href="LedgerFiscalCloseLedgerOptions.md" target="_blank">Main/LedgerFiscalCloseLedgerOptions</a>|
|[ProfitLossDefaultDimension](#ProfitLossDefaultDimension)||<a href="LedgerFiscalCloseLedgerOptions.md" target="_blank">Main/LedgerFiscalCloseLedgerOptions</a>|
|[Relationship_LedgerFiscalCloseGroupRelationshipId](#Relationship_LedgerFiscalCloseGroupRelationshipId)||<a href="LedgerFiscalCloseLedgerOptions.md" target="_blank">Main/LedgerFiscalCloseLedgerOptions</a>|
|[Relationship_LedgerRelationshipId](#Relationship_LedgerRelationshipId)||<a href="LedgerFiscalCloseLedgerOptions.md" target="_blank">Main/LedgerFiscalCloseLedgerOptions</a>|
|[Relationship_ProfitLossDefaultDimensionRelationshipId](#Relationship_ProfitLossDefaultDimensionRelationshipId)||<a href="LedgerFiscalCloseLedgerOptions.md" target="_blank">Main/LedgerFiscalCloseLedgerOptions</a>|
|[Relationship_ProfitLossCloseDimensionRelationshipId](#Relationship_ProfitLossCloseDimensionRelationshipId)||<a href="LedgerFiscalCloseLedgerOptions.md" target="_blank">Main/LedgerFiscalCloseLedgerOptions</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/LedgerFiscalCloseLedgerOptions (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[LedgerFiscalCloseLedgerOptions/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LedgerFiscalCloseGroup name="LedgerFiscalCloseGroup">LedgerFiscalCloseGroup</a>

First included in: Main/LedgerFiscalCloseLedgerOptions (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerFiscalCloseGroup attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Ledger name="Ledger">Ledger</a>

First included in: Main/LedgerFiscalCloseLedgerOptions (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Ledger attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RetainedEarningsMainAccount name="RetainedEarningsMainAccount">RetainedEarningsMainAccount</a>

First included in: Main/LedgerFiscalCloseLedgerOptions (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetainedEarningsMainAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransferBalanceSheetDimensions name="TransferBalanceSheetDimensions">TransferBalanceSheetDimensions</a>

First included in: Main/LedgerFiscalCloseLedgerOptions (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferBalanceSheetDimensions attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ProfitLossCloseDimension name="ProfitLossCloseDimension">ProfitLossCloseDimension</a>

First included in: Main/LedgerFiscalCloseLedgerOptions (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProfitLossCloseDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ProfitLossDefaultDimension name="ProfitLossDefaultDimension">ProfitLossDefaultDimension</a>

First included in: Main/LedgerFiscalCloseLedgerOptions (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProfitLossDefaultDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_LedgerFiscalCloseGroupRelationshipId name="Relationship_LedgerFiscalCloseGroupRelationshipId">Relationship_LedgerFiscalCloseGroupRelationshipId</a>

First included in: Main/LedgerFiscalCloseLedgerOptions (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerFiscalCloseGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="LedgerFiscalCloseGroup.md" target="_blank">/core/erp/Tables/Finance/Ledger/Main/LedgerFiscalCloseGroup.cdm.json/LedgerFiscalCloseGroup</a></td><td><a href="LedgerFiscalCloseGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerRelationshipId name="Relationship_LedgerRelationshipId">Relationship_LedgerRelationshipId</a>

First included in: Main/LedgerFiscalCloseLedgerOptions (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="Ledger.md" target="_blank">/core/erp/Tables/Finance/Ledger/Main/Ledger.cdm.json/Ledger</a></td><td><a href="Ledger.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProfitLossDefaultDimensionRelationshipId name="Relationship_ProfitLossDefaultDimensionRelationshipId">Relationship_ProfitLossDefaultDimensionRelationshipId</a>

First included in: Main/LedgerFiscalCloseLedgerOptions (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProfitLossDefaultDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueSet.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueSet.cdm.json/DimensionAttributeValueSet</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueSet.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProfitLossCloseDimensionRelationshipId name="Relationship_ProfitLossCloseDimensionRelationshipId">Relationship_ProfitLossCloseDimensionRelationshipId</a>

First included in: Main/LedgerFiscalCloseLedgerOptions (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProfitLossCloseDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Reference/DimensionAttributeSet.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Reference/DimensionAttributeSet.cdm.json/DimensionAttributeSet</a></td><td><a href="../../FinancialDimensions/Reference/DimensionAttributeSet.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
