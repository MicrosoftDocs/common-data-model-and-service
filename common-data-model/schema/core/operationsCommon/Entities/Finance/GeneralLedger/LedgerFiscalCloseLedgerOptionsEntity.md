---
title: LedgerFiscalCloseLedgerOptionsEntity in GeneralLedger - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Fiscal close ledger options in GeneralLedger(LedgerFiscalCloseLedgerOptionsEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/GeneralLedger/LedgerFiscalCloseLedgerOptionsEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Fiscal close ledger options</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[LedgerFiscalCloseGroup](#LedgerFiscalCloseGroup)||<a href="LedgerFiscalCloseLedgerOptionsEntity.md" target="_blank">GeneralLedger/LedgerFiscalCloseLedgerOptionsEntity</a>|
|[Ledger](#Ledger)||<a href="LedgerFiscalCloseLedgerOptionsEntity.md" target="_blank">GeneralLedger/LedgerFiscalCloseLedgerOptionsEntity</a>|
|[RetainedEarningsMainAccount](#RetainedEarningsMainAccount)||<a href="LedgerFiscalCloseLedgerOptionsEntity.md" target="_blank">GeneralLedger/LedgerFiscalCloseLedgerOptionsEntity</a>|
|[TransferBalanceSheetDimensions](#TransferBalanceSheetDimensions)||<a href="LedgerFiscalCloseLedgerOptionsEntity.md" target="_blank">GeneralLedger/LedgerFiscalCloseLedgerOptionsEntity</a>|
|[ProfitLossCloseDimension](#ProfitLossCloseDimension)||<a href="LedgerFiscalCloseLedgerOptionsEntity.md" target="_blank">GeneralLedger/LedgerFiscalCloseLedgerOptionsEntity</a>|
|[ProfitLossDefaultDimension](#ProfitLossDefaultDimension)||<a href="LedgerFiscalCloseLedgerOptionsEntity.md" target="_blank">GeneralLedger/LedgerFiscalCloseLedgerOptionsEntity</a>|
|[LedgerFiscalCloseGroupName](#LedgerFiscalCloseGroupName)||<a href="LedgerFiscalCloseLedgerOptionsEntity.md" target="_blank">GeneralLedger/LedgerFiscalCloseLedgerOptionsEntity</a>|
|[LedgerName](#LedgerName)||<a href="LedgerFiscalCloseLedgerOptionsEntity.md" target="_blank">GeneralLedger/LedgerFiscalCloseLedgerOptionsEntity</a>|
|[ProfitLossDefaultDimensionDisplayValue](#ProfitLossDefaultDimensionDisplayValue)||<a href="LedgerFiscalCloseLedgerOptionsEntity.md" target="_blank">GeneralLedger/LedgerFiscalCloseLedgerOptionsEntity</a>|
|[LegalEntity](#LegalEntity)||<a href="LedgerFiscalCloseLedgerOptionsEntity.md" target="_blank">GeneralLedger/LedgerFiscalCloseLedgerOptionsEntity</a>|
|[ProfitLossCloseDimensionDisplayValue](#ProfitLossCloseDimensionDisplayValue)||<a href="LedgerFiscalCloseLedgerOptionsEntity.md" target="_blank">GeneralLedger/LedgerFiscalCloseLedgerOptionsEntity</a>|
|[Relationship_ProfitLossDefaultDimensionDimensionSetRelationshipId](#Relationship_ProfitLossDefaultDimensionDimensionSetRelationshipId)||<a href="LedgerFiscalCloseLedgerOptionsEntity.md" target="_blank">GeneralLedger/LedgerFiscalCloseLedgerOptionsEntity</a>|
|[BackingTable_LedgerFiscalCloseLedgerOptionsRelationshipId](#BackingTable_LedgerFiscalCloseLedgerOptionsRelationshipId)||<a href="LedgerFiscalCloseLedgerOptionsEntity.md" target="_blank">GeneralLedger/LedgerFiscalCloseLedgerOptionsEntity</a>|

### <a href=#LedgerFiscalCloseGroup name="LedgerFiscalCloseGroup">LedgerFiscalCloseGroup</a>

First included in: GeneralLedger/LedgerFiscalCloseLedgerOptionsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerFiscalCloseGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Ledger name="Ledger">Ledger</a>

First included in: GeneralLedger/LedgerFiscalCloseLedgerOptionsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Ledger attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetainedEarningsMainAccount name="RetainedEarningsMainAccount">RetainedEarningsMainAccount</a>

First included in: GeneralLedger/LedgerFiscalCloseLedgerOptionsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetainedEarningsMainAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransferBalanceSheetDimensions name="TransferBalanceSheetDimensions">TransferBalanceSheetDimensions</a>

First included in: GeneralLedger/LedgerFiscalCloseLedgerOptionsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferBalanceSheetDimensions attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProfitLossCloseDimension name="ProfitLossCloseDimension">ProfitLossCloseDimension</a>

First included in: GeneralLedger/LedgerFiscalCloseLedgerOptionsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProfitLossCloseDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProfitLossDefaultDimension name="ProfitLossDefaultDimension">ProfitLossDefaultDimension</a>

First included in: GeneralLedger/LedgerFiscalCloseLedgerOptionsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProfitLossDefaultDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerFiscalCloseGroupName name="LedgerFiscalCloseGroupName">LedgerFiscalCloseGroupName</a>

First included in: GeneralLedger/LedgerFiscalCloseLedgerOptionsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerFiscalCloseGroupName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerName name="LedgerName">LedgerName</a>

First included in: GeneralLedger/LedgerFiscalCloseLedgerOptionsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProfitLossDefaultDimensionDisplayValue name="ProfitLossDefaultDimensionDisplayValue">ProfitLossDefaultDimensionDisplayValue</a>

First included in: GeneralLedger/LedgerFiscalCloseLedgerOptionsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProfitLossDefaultDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LegalEntity name="LegalEntity">LegalEntity</a>

First included in: GeneralLedger/LedgerFiscalCloseLedgerOptionsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LegalEntity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProfitLossCloseDimensionDisplayValue name="ProfitLossCloseDimensionDisplayValue">ProfitLossCloseDimensionDisplayValue</a>

First included in: GeneralLedger/LedgerFiscalCloseLedgerOptionsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProfitLossCloseDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProfitLossDefaultDimensionDimensionSetRelationshipId name="Relationship_ProfitLossDefaultDimensionDimensionSetRelationshipId">Relationship_ProfitLossDefaultDimensionDimensionSetRelationshipId</a>

First included in: GeneralLedger/LedgerFiscalCloseLedgerOptionsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProfitLossDefaultDimensionDimensionSetRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_LedgerFiscalCloseLedgerOptionsRelationshipId name="BackingTable_LedgerFiscalCloseLedgerOptionsRelationshipId">BackingTable_LedgerFiscalCloseLedgerOptionsRelationshipId</a>

First included in: GeneralLedger/LedgerFiscalCloseLedgerOptionsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_LedgerFiscalCloseLedgerOptionsRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Main/LedgerFiscalCloseLedgerOptions.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/LedgerFiscalCloseLedgerOptions.cdm.json/LedgerFiscalCloseLedgerOptions</a></td><td><a href="../../../Tables/Finance/Ledger/Main/LedgerFiscalCloseLedgerOptions.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
