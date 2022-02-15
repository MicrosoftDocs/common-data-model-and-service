---
title: LedgerRRGTransOperationsTax_RU in WorksheetLine - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Accounting profile for ledger transactions to be used in report in WorksheetLine(LedgerRRGTransOperationsTax_RU)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Ledger/WorksheetLine/LedgerRRGTransOperationsTax_RU.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[LedgerRRGTransOperationsTax_RU/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Accounting profile for ledger transactions to be used in report</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="LedgerRRGTransOperationsTax_RU.md" target="_blank">WorksheetLine/LedgerRRGTransOperationsTax_RU</a>|
|[OperationsTax](#OperationsTax)||<a href="LedgerRRGTransOperationsTax_RU.md" target="_blank">WorksheetLine/LedgerRRGTransOperationsTax_RU</a>|
|[OpTaxRecId](#OpTaxRecId)||<a href="LedgerRRGTransOperationsTax_RU.md" target="_blank">WorksheetLine/LedgerRRGTransOperationsTax_RU</a>|
|[OpTaxTableId](#OpTaxTableId)||<a href="LedgerRRGTransOperationsTax_RU.md" target="_blank">WorksheetLine/LedgerRRGTransOperationsTax_RU</a>|
|[DataAreaId](#DataAreaId)||<a href="LedgerRRGTransOperationsTax_RU.md" target="_blank">WorksheetLine/LedgerRRGTransOperationsTax_RU</a>|
|[Relationship_LedgerRRGCellTableRelationshipId](#Relationship_LedgerRRGCellTableRelationshipId)||<a href="LedgerRRGTransOperationsTax_RU.md" target="_blank">WorksheetLine/LedgerRRGTransOperationsTax_RU</a>|
|[Relationship_LedgerRRGEQueries_WRelationshipId](#Relationship_LedgerRRGEQueries_WRelationshipId)||<a href="LedgerRRGTransOperationsTax_RU.md" target="_blank">WorksheetLine/LedgerRRGTransOperationsTax_RU</a>|
|[Relationship_LedgerRRGOperationTableRelationshipId](#Relationship_LedgerRRGOperationTableRelationshipId)||<a href="LedgerRRGTransOperationsTax_RU.md" target="_blank">WorksheetLine/LedgerRRGTransOperationsTax_RU</a>|
|[Relationship_LedgerRRGReportTableRelationshipId](#Relationship_LedgerRRGReportTableRelationshipId)||<a href="LedgerRRGTransOperationsTax_RU.md" target="_blank">WorksheetLine/LedgerRRGTransOperationsTax_RU</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="LedgerRRGTransOperationsTax_RU.md" target="_blank">WorksheetLine/LedgerRRGTransOperationsTax_RU</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetLine/LedgerRRGTransOperationsTax_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[LedgerRRGTransOperationsTax_RU/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#OperationsTax name="OperationsTax">OperationsTax</a>

First included in: WorksheetLine/LedgerRRGTransOperationsTax_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperationsTax attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#OpTaxRecId name="OpTaxRecId">OpTaxRecId</a>

First included in: WorksheetLine/LedgerRRGTransOperationsTax_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OpTaxRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#OpTaxTableId name="OpTaxTableId">OpTaxTableId</a>

First included in: WorksheetLine/LedgerRRGTransOperationsTax_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OpTaxTableId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetLine/LedgerRRGTransOperationsTax_RU (this entity)  

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

### <a href=#Relationship_LedgerRRGCellTableRelationshipId name="Relationship_LedgerRRGCellTableRelationshipId">Relationship_LedgerRRGCellTableRelationshipId</a>

First included in: WorksheetLine/LedgerRRGTransOperationsTax_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerRRGCellTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/LedgerRRGCellTable_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Group/LedgerRRGCellTable_RU.cdm.json/LedgerRRGCellTable_RU</a></td><td><a href="../Group/LedgerRRGCellTable_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerRRGEQueries_WRelationshipId name="Relationship_LedgerRRGEQueries_WRelationshipId">Relationship_LedgerRRGEQueries_WRelationshipId</a>

First included in: WorksheetLine/LedgerRRGTransOperationsTax_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerRRGEQueries_WRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/LedgerRRGEQueries_W.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Group/LedgerRRGEQueries_W.cdm.json/LedgerRRGEQueries_W</a></td><td><a href="../Group/LedgerRRGEQueries_W.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerRRGOperationTableRelationshipId name="Relationship_LedgerRRGOperationTableRelationshipId">Relationship_LedgerRRGOperationTableRelationshipId</a>

First included in: WorksheetLine/LedgerRRGTransOperationsTax_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerRRGOperationTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="LedgerRRGOperationTable_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/WorksheetLine/LedgerRRGOperationTable_RU.cdm.json/LedgerRRGOperationTable_RU</a></td><td><a href="LedgerRRGOperationTable_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerRRGReportTableRelationshipId name="Relationship_LedgerRRGReportTableRelationshipId">Relationship_LedgerRRGReportTableRelationshipId</a>

First included in: WorksheetLine/LedgerRRGTransOperationsTax_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerRRGReportTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/LedgerRRGReportTable_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/WorksheetHeader/LedgerRRGReportTable_RU.cdm.json/LedgerRRGReportTable_RU</a></td><td><a href="../WorksheetHeader/LedgerRRGReportTable_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetLine/LedgerRRGTransOperationsTax_RU (this entity)  

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
