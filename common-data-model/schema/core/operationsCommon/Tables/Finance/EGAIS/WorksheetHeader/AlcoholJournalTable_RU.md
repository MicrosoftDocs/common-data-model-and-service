---
title: AlcoholJournalTable_RU in WorksheetHeader - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Quarterly journal for alcohol production turnover in WorksheetHeader(AlcoholJournalTable_RU)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/EGAIS/WorksheetHeader/AlcoholJournalTable_RU.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[AlcoholJournalTable_RU/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Quarterly journal for alcohol production turnover</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="AlcoholJournalTable_RU.md" target="_blank">WorksheetHeader/AlcoholJournalTable_RU</a>|
|[BranchId](#BranchId)||<a href="AlcoholJournalTable_RU.md" target="_blank">WorksheetHeader/AlcoholJournalTable_RU</a>|
|[Description](#Description)||<a href="AlcoholJournalTable_RU.md" target="_blank">WorksheetHeader/AlcoholJournalTable_RU</a>|
|[FiscalYear](#FiscalYear)||<a href="AlcoholJournalTable_RU.md" target="_blank">WorksheetHeader/AlcoholJournalTable_RU</a>|
|[JournalId](#JournalId)||<a href="AlcoholJournalTable_RU.md" target="_blank">WorksheetHeader/AlcoholJournalTable_RU</a>|
|[PeriodNum](#PeriodNum)||<a href="AlcoholJournalTable_RU.md" target="_blank">WorksheetHeader/AlcoholJournalTable_RU</a>|
|[PeriodType](#PeriodType)||<a href="AlcoholJournalTable_RU.md" target="_blank">WorksheetHeader/AlcoholJournalTable_RU</a>|
|[Status](#Status)||<a href="AlcoholJournalTable_RU.md" target="_blank">WorksheetHeader/AlcoholJournalTable_RU</a>|
|[DataAreaId](#DataAreaId)||<a href="AlcoholJournalTable_RU.md" target="_blank">WorksheetHeader/AlcoholJournalTable_RU</a>|
|[Relationship_Branches_RURelationshipId](#Relationship_Branches_RURelationshipId)||<a href="AlcoholJournalTable_RU.md" target="_blank">WorksheetHeader/AlcoholJournalTable_RU</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="AlcoholJournalTable_RU.md" target="_blank">WorksheetHeader/AlcoholJournalTable_RU</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetHeader/AlcoholJournalTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[AlcoholJournalTable_RU/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BranchId name="BranchId">BranchId</a>

First included in: WorksheetHeader/AlcoholJournalTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BranchId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: WorksheetHeader/AlcoholJournalTable_RU (this entity)  

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

### <a href=#FiscalYear name="FiscalYear">FiscalYear</a>

First included in: WorksheetHeader/AlcoholJournalTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalYear attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#JournalId name="JournalId">JournalId</a>

First included in: WorksheetHeader/AlcoholJournalTable_RU (this entity)  

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

### <a href=#PeriodNum name="PeriodNum">PeriodNum</a>

First included in: WorksheetHeader/AlcoholJournalTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodNum attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PeriodType name="PeriodType">PeriodType</a>

First included in: WorksheetHeader/AlcoholJournalTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Status name="Status">Status</a>

First included in: WorksheetHeader/AlcoholJournalTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Status attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetHeader/AlcoholJournalTable_RU (this entity)  

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

### <a href=#Relationship_Branches_RURelationshipId name="Relationship_Branches_RURelationshipId">Relationship_Branches_RURelationshipId</a>

First included in: WorksheetHeader/AlcoholJournalTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_Branches_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../APARShared/Group/Branches_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/APARShared/Group/Branches_RU.cdm.json/Branches_RU</a></td><td><a href="../../APARShared/Group/Branches_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetHeader/AlcoholJournalTable_RU (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
