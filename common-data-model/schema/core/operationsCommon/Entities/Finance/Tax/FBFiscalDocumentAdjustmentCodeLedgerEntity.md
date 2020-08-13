---
title: FBFiscalDocumentAdjustmentCodeLedgerEntity in Tax - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Tax adjustment codes by fiscal document posting definition in Tax(FBFiscalDocumentAdjustmentCodeLedgerEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/Tax/FBFiscalDocumentAdjustmentCodeLedgerEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tax adjustment codes by fiscal document posting definition</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[FBFiscalDocumentAdjustmentCodeRecId](#FBFiscalDocumentAdjustmentCodeRecId)||<a href="FBFiscalDocumentAdjustmentCodeLedgerEntity.md" target="_blank">Tax/FBFiscalDocumentAdjustmentCodeLedgerEntity</a>|
|[FBFiscalDocumentAdjustmentCodeIdentification](#FBFiscalDocumentAdjustmentCodeIdentification)||<a href="FBFiscalDocumentAdjustmentCodeLedgerEntity.md" target="_blank">Tax/FBFiscalDocumentAdjustmentCodeLedgerEntity</a>|
|[Company](#Company)||<a href="FBFiscalDocumentAdjustmentCodeLedgerEntity.md" target="_blank">Tax/FBFiscalDocumentAdjustmentCodeLedgerEntity</a>|
|[TaxCode](#TaxCode)||<a href="FBFiscalDocumentAdjustmentCodeLedgerEntity.md" target="_blank">Tax/FBFiscalDocumentAdjustmentCodeLedgerEntity</a>|
|[LedgerDimension](#LedgerDimension)||<a href="FBFiscalDocumentAdjustmentCodeLedgerEntity.md" target="_blank">Tax/FBFiscalDocumentAdjustmentCodeLedgerEntity</a>|
|[LedgerDimensionDisplayValue](#LedgerDimensionDisplayValue)||<a href="FBFiscalDocumentAdjustmentCodeLedgerEntity.md" target="_blank">Tax/FBFiscalDocumentAdjustmentCodeLedgerEntity</a>|
|[Relationship_LedgerDimensionCombinationRelationshipId](#Relationship_LedgerDimensionCombinationRelationshipId)||<a href="FBFiscalDocumentAdjustmentCodeLedgerEntity.md" target="_blank">Tax/FBFiscalDocumentAdjustmentCodeLedgerEntity</a>|
|[BackingTable_FBFiscalDocAdjustmentCodeICMSLedger_BRRelationshipId](#BackingTable_FBFiscalDocAdjustmentCodeICMSLedger_BRRelationshipId)||<a href="FBFiscalDocumentAdjustmentCodeLedgerEntity.md" target="_blank">Tax/FBFiscalDocumentAdjustmentCodeLedgerEntity</a>|

### <a href=#FBFiscalDocumentAdjustmentCodeRecId name="FBFiscalDocumentAdjustmentCodeRecId">FBFiscalDocumentAdjustmentCodeRecId</a>

First included in: Tax/FBFiscalDocumentAdjustmentCodeLedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FBFiscalDocumentAdjustmentCodeRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FBFiscalDocumentAdjustmentCodeIdentification name="FBFiscalDocumentAdjustmentCodeIdentification">FBFiscalDocumentAdjustmentCodeIdentification</a>

First included in: Tax/FBFiscalDocumentAdjustmentCodeLedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FBFiscalDocumentAdjustmentCodeIdentification attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Company name="Company">Company</a>

First included in: Tax/FBFiscalDocumentAdjustmentCodeLedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Company attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxCode name="TaxCode">TaxCode</a>

First included in: Tax/FBFiscalDocumentAdjustmentCodeLedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerDimension name="LedgerDimension">LedgerDimension</a>

First included in: Tax/FBFiscalDocumentAdjustmentCodeLedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerDimensionDisplayValue name="LedgerDimensionDisplayValue">LedgerDimensionDisplayValue</a>

First included in: Tax/FBFiscalDocumentAdjustmentCodeLedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Main account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Main account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerDimensionCombinationRelationshipId name="Relationship_LedgerDimensionCombinationRelationshipId">Relationship_LedgerDimensionCombinationRelationshipId</a>

First included in: Tax/FBFiscalDocumentAdjustmentCodeLedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_FBFiscalDocAdjustmentCodeICMSLedger_BRRelationshipId name="BackingTable_FBFiscalDocAdjustmentCodeICMSLedger_BRRelationshipId">BackingTable_FBFiscalDocAdjustmentCodeICMSLedger_BRRelationshipId</a>

First included in: Tax/FBFiscalDocumentAdjustmentCodeLedgerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_FBFiscalDocAdjustmentCodeICMSLedger_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/FiscalBooksBrazil/Miscellaneous/FBFiscalDocAdjustmentCodeICMSLedger_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Miscellaneous/FBFiscalDocAdjustmentCodeICMSLedger_BR.cdm.json/FBFiscalDocAdjustmentCodeICMSLedger_BR</a></td><td><a href="../../../Tables/Finance/FiscalBooksBrazil/Miscellaneous/FBFiscalDocAdjustmentCodeICMSLedger_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
