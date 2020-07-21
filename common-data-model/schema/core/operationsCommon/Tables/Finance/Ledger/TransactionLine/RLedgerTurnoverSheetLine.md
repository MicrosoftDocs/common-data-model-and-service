---
title: RLedgerTurnoverSheetLine in TransactionLine - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/21/2020
ms.author: nebanfic
---

# Turnover and balances statement snapshot lines in TransactionLine(RLedgerTurnoverSheetLine)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Ledger/TransactionLine/RLedgerTurnoverSheetLine.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RLedgerTurnoverSheetLine/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Turnover and balances statement snapshot lines</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RLedgerTurnoverSheetLine.md" target="_blank">TransactionLine/RLedgerTurnoverSheetLine</a>|
|[BalanceCreditEnd](#BalanceCreditEnd)||<a href="RLedgerTurnoverSheetLine.md" target="_blank">TransactionLine/RLedgerTurnoverSheetLine</a>|
|[BalanceCreditStart](#BalanceCreditStart)||<a href="RLedgerTurnoverSheetLine.md" target="_blank">TransactionLine/RLedgerTurnoverSheetLine</a>|
|[BalanceDebitEnd](#BalanceDebitEnd)||<a href="RLedgerTurnoverSheetLine.md" target="_blank">TransactionLine/RLedgerTurnoverSheetLine</a>|
|[BalanceDebitStart](#BalanceDebitStart)||<a href="RLedgerTurnoverSheetLine.md" target="_blank">TransactionLine/RLedgerTurnoverSheetLine</a>|
|[Description](#Description)||<a href="RLedgerTurnoverSheetLine.md" target="_blank">TransactionLine/RLedgerTurnoverSheetLine</a>|
|[DocumentDate](#DocumentDate)||<a href="RLedgerTurnoverSheetLine.md" target="_blank">TransactionLine/RLedgerTurnoverSheetLine</a>|
|[DocumentNum](#DocumentNum)||<a href="RLedgerTurnoverSheetLine.md" target="_blank">TransactionLine/RLedgerTurnoverSheetLine</a>|
|[Level](#Level)||<a href="RLedgerTurnoverSheetLine.md" target="_blank">TransactionLine/RLedgerTurnoverSheetLine</a>|
|[LineID](#LineID)||<a href="RLedgerTurnoverSheetLine.md" target="_blank">TransactionLine/RLedgerTurnoverSheetLine</a>|
|[LineNum](#LineNum)||<a href="RLedgerTurnoverSheetLine.md" target="_blank">TransactionLine/RLedgerTurnoverSheetLine</a>|
|[LineType](#LineType)||<a href="RLedgerTurnoverSheetLine.md" target="_blank">TransactionLine/RLedgerTurnoverSheetLine</a>|
|[Name](#Name)||<a href="RLedgerTurnoverSheetLine.md" target="_blank">TransactionLine/RLedgerTurnoverSheetLine</a>|
|[Parameter](#Parameter)||<a href="RLedgerTurnoverSheetLine.md" target="_blank">TransactionLine/RLedgerTurnoverSheetLine</a>|
|[ParentLineNum](#ParentLineNum)||<a href="RLedgerTurnoverSheetLine.md" target="_blank">TransactionLine/RLedgerTurnoverSheetLine</a>|
|[RefRecId](#RefRecId)||<a href="RLedgerTurnoverSheetLine.md" target="_blank">TransactionLine/RLedgerTurnoverSheetLine</a>|
|[SettlementCredit](#SettlementCredit)||<a href="RLedgerTurnoverSheetLine.md" target="_blank">TransactionLine/RLedgerTurnoverSheetLine</a>|
|[SettlementDebit](#SettlementDebit)||<a href="RLedgerTurnoverSheetLine.md" target="_blank">TransactionLine/RLedgerTurnoverSheetLine</a>|
|[TransDate](#TransDate)||<a href="RLedgerTurnoverSheetLine.md" target="_blank">TransactionLine/RLedgerTurnoverSheetLine</a>|
|[TurnoverCredit](#TurnoverCredit)||<a href="RLedgerTurnoverSheetLine.md" target="_blank">TransactionLine/RLedgerTurnoverSheetLine</a>|
|[TurnoverDebit](#TurnoverDebit)||<a href="RLedgerTurnoverSheetLine.md" target="_blank">TransactionLine/RLedgerTurnoverSheetLine</a>|
|[Txt](#Txt)||<a href="RLedgerTurnoverSheetLine.md" target="_blank">TransactionLine/RLedgerTurnoverSheetLine</a>|
|[DataAreaId](#DataAreaId)||<a href="RLedgerTurnoverSheetLine.md" target="_blank">TransactionLine/RLedgerTurnoverSheetLine</a>|
|[Relationship_RLedgerTurnoverSheetRelationshipId](#Relationship_RLedgerTurnoverSheetRelationshipId)||<a href="RLedgerTurnoverSheetLine.md" target="_blank">TransactionLine/RLedgerTurnoverSheetLine</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="RLedgerTurnoverSheetLine.md" target="_blank">TransactionLine/RLedgerTurnoverSheetLine</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: TransactionLine/RLedgerTurnoverSheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RLedgerTurnoverSheetLine/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BalanceCreditEnd name="BalanceCreditEnd">BalanceCreditEnd</a>

First included in: TransactionLine/RLedgerTurnoverSheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BalanceCreditEnd attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#BalanceCreditStart name="BalanceCreditStart">BalanceCreditStart</a>

First included in: TransactionLine/RLedgerTurnoverSheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BalanceCreditStart attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#BalanceDebitEnd name="BalanceDebitEnd">BalanceDebitEnd</a>

First included in: TransactionLine/RLedgerTurnoverSheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BalanceDebitEnd attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#BalanceDebitStart name="BalanceDebitStart">BalanceDebitStart</a>

First included in: TransactionLine/RLedgerTurnoverSheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BalanceDebitStart attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Description name="Description">Description</a>

First included in: TransactionLine/RLedgerTurnoverSheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentDate name="DocumentDate">DocumentDate</a>

First included in: TransactionLine/RLedgerTurnoverSheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentNum name="DocumentNum">DocumentNum</a>

First included in: TransactionLine/RLedgerTurnoverSheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Level name="Level">Level</a>

First included in: TransactionLine/RLedgerTurnoverSheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Level attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#LineID name="LineID">LineID</a>

First included in: TransactionLine/RLedgerTurnoverSheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineID attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LineNum name="LineNum">LineNum</a>

First included in: TransactionLine/RLedgerTurnoverSheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNum attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LineType name="LineType">LineType</a>

First included in: TransactionLine/RLedgerTurnoverSheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: TransactionLine/RLedgerTurnoverSheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Parameter name="Parameter">Parameter</a>

First included in: TransactionLine/RLedgerTurnoverSheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Parameter attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ParentLineNum name="ParentLineNum">ParentLineNum</a>

First included in: TransactionLine/RLedgerTurnoverSheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParentLineNum attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RefRecId name="RefRecId">RefRecId</a>

First included in: TransactionLine/RLedgerTurnoverSheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SettlementCredit name="SettlementCredit">SettlementCredit</a>

First included in: TransactionLine/RLedgerTurnoverSheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SettlementCredit attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SettlementDebit name="SettlementDebit">SettlementDebit</a>

First included in: TransactionLine/RLedgerTurnoverSheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SettlementDebit attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TransDate name="TransDate">TransDate</a>

First included in: TransactionLine/RLedgerTurnoverSheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TurnoverCredit name="TurnoverCredit">TurnoverCredit</a>

First included in: TransactionLine/RLedgerTurnoverSheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TurnoverCredit attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TurnoverDebit name="TurnoverDebit">TurnoverDebit</a>

First included in: TransactionLine/RLedgerTurnoverSheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TurnoverDebit attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Txt name="Txt">Txt</a>

First included in: TransactionLine/RLedgerTurnoverSheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Txt attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: TransactionLine/RLedgerTurnoverSheetLine (this entity)  

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

### <a href=#Relationship_RLedgerTurnoverSheetRelationshipId name="Relationship_RLedgerTurnoverSheetRelationshipId">Relationship_RLedgerTurnoverSheetRelationshipId</a>

First included in: TransactionLine/RLedgerTurnoverSheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RLedgerTurnoverSheetRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../TransactionHeader/RLedgerTurnoverSheet.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/TransactionHeader/RLedgerTurnoverSheet.cdm.json/RLedgerTurnoverSheet</a></td><td><a href="../TransactionHeader/RLedgerTurnoverSheet.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: TransactionLine/RLedgerTurnoverSheetLine (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
