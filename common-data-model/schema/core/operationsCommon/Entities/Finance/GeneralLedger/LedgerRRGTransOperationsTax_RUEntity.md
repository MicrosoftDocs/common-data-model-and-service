---
title: LedgerRRGTransOperationsTax_RUEntity in GeneralLedger - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/13/2020
ms.author: nebanfic
---

# Financial reports posting layers in GeneralLedger(LedgerRRGTransOperationsTax_RUEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/GeneralLedger/LedgerRRGTransOperationsTax_RUEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Financial reports posting layers</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[OperationsTax](#OperationsTax)||<a href="LedgerRRGTransOperationsTax_RUEntity.md" target="_blank">GeneralLedger/LedgerRRGTransOperationsTax_RUEntity</a>|
|[RefTableName](#RefTableName)||<a href="LedgerRRGTransOperationsTax_RUEntity.md" target="_blank">GeneralLedger/LedgerRRGTransOperationsTax_RUEntity</a>|
|[RefLineId](#RefLineId)||<a href="LedgerRRGTransOperationsTax_RUEntity.md" target="_blank">GeneralLedger/LedgerRRGTransOperationsTax_RUEntity</a>|
|[OpTaxRecId](#OpTaxRecId)||<a href="LedgerRRGTransOperationsTax_RUEntity.md" target="_blank">GeneralLedger/LedgerRRGTransOperationsTax_RUEntity</a>|
|[OpTaxTableId](#OpTaxTableId)||<a href="LedgerRRGTransOperationsTax_RUEntity.md" target="_blank">GeneralLedger/LedgerRRGTransOperationsTax_RUEntity</a>|
|[BackingTable_LedgerRRGTransOperationsTax_RURelationshipId](#BackingTable_LedgerRRGTransOperationsTax_RURelationshipId)||<a href="LedgerRRGTransOperationsTax_RUEntity.md" target="_blank">GeneralLedger/LedgerRRGTransOperationsTax_RUEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="LedgerRRGTransOperationsTax_RUEntity.md" target="_blank">GeneralLedger/LedgerRRGTransOperationsTax_RUEntity</a>|

### <a href=#OperationsTax name="OperationsTax">OperationsTax</a>

First included in: GeneralLedger/LedgerRRGTransOperationsTax_RUEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperationsTax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RefTableName name="RefTableName">RefTableName</a>

First included in: GeneralLedger/LedgerRRGTransOperationsTax_RUEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefTableName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RefLineId name="RefLineId">RefLineId</a>

First included in: GeneralLedger/LedgerRRGTransOperationsTax_RUEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefLineId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OpTaxRecId name="OpTaxRecId">OpTaxRecId</a>

First included in: GeneralLedger/LedgerRRGTransOperationsTax_RUEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OpTaxRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OpTaxTableId name="OpTaxTableId">OpTaxTableId</a>

First included in: GeneralLedger/LedgerRRGTransOperationsTax_RUEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OpTaxTableId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_LedgerRRGTransOperationsTax_RURelationshipId name="BackingTable_LedgerRRGTransOperationsTax_RURelationshipId">BackingTable_LedgerRRGTransOperationsTax_RURelationshipId</a>

First included in: GeneralLedger/LedgerRRGTransOperationsTax_RUEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_LedgerRRGTransOperationsTax_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/WorksheetLine/LedgerRRGTransOperationsTax_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/WorksheetLine/LedgerRRGTransOperationsTax_RU.cdm.json/LedgerRRGTransOperationsTax_RU</a></td><td><a href="../../../Tables/Finance/Ledger/WorksheetLine/LedgerRRGTransOperationsTax_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: GeneralLedger/LedgerRRGTransOperationsTax_RUEntity (this entity)  

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
