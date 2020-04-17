---
title: InventFiscalLIFOJournalTransAdj - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# InventFiscalLIFOJournalTransAdj

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/SupplyChain/Inventory/WorksheetLine/InventFiscalLIFOJournalTransAdj.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[InventFiscalLIFOJournalTransAdj/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="InventFiscalLIFOJournalTransAdj.md" target="_blank">WorksheetLine/InventFiscalLIFOJournalTransAdj</a>|
|[FinalReportClosed](#FinalReportClosed)||<a href="InventFiscalLIFOJournalTransAdj.md" target="_blank">WorksheetLine/InventFiscalLIFOJournalTransAdj</a>|
|[InventFiscalLIFOGroup](#InventFiscalLIFOGroup)||<a href="InventFiscalLIFOJournalTransAdj.md" target="_blank">WorksheetLine/InventFiscalLIFOJournalTransAdj</a>|
|[ItemId](#ItemId)||<a href="InventFiscalLIFOJournalTransAdj.md" target="_blank">WorksheetLine/InventFiscalLIFOJournalTransAdj</a>|
|[JournalId](#JournalId)||<a href="InventFiscalLIFOJournalTransAdj.md" target="_blank">WorksheetLine/InventFiscalLIFOJournalTransAdj</a>|
|[RemainQtyAdj](#RemainQtyAdj)||<a href="InventFiscalLIFOJournalTransAdj.md" target="_blank">WorksheetLine/InventFiscalLIFOJournalTransAdj</a>|
|[Year](#Year)||<a href="InventFiscalLIFOJournalTransAdj.md" target="_blank">WorksheetLine/InventFiscalLIFOJournalTransAdj</a>|
|[YearAdj](#YearAdj)||<a href="InventFiscalLIFOJournalTransAdj.md" target="_blank">WorksheetLine/InventFiscalLIFOJournalTransAdj</a>|
|[DataAreaId](#DataAreaId)||<a href="InventFiscalLIFOJournalTransAdj.md" target="_blank">WorksheetLine/InventFiscalLIFOJournalTransAdj</a>|
|[Relationship_InventFiscalLIFOGroupRelationshipId](#Relationship_InventFiscalLIFOGroupRelationshipId)||<a href="InventFiscalLIFOJournalTransAdj.md" target="_blank">WorksheetLine/InventFiscalLIFOJournalTransAdj</a>|
|[Relationship_InventFiscalLIFOJournalTableRelationshipId](#Relationship_InventFiscalLIFOJournalTableRelationshipId)||<a href="InventFiscalLIFOJournalTransAdj.md" target="_blank">WorksheetLine/InventFiscalLIFOJournalTransAdj</a>|
|[Relationship_InventTableRelationshipId](#Relationship_InventTableRelationshipId)||<a href="InventFiscalLIFOJournalTransAdj.md" target="_blank">WorksheetLine/InventFiscalLIFOJournalTransAdj</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="InventFiscalLIFOJournalTransAdj.md" target="_blank">WorksheetLine/InventFiscalLIFOJournalTransAdj</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetLine/InventFiscalLIFOJournalTransAdj (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[InventFiscalLIFOJournalTransAdj/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FinalReportClosed name="FinalReportClosed">FinalReportClosed</a>

First included in: WorksheetLine/InventFiscalLIFOJournalTransAdj (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FinalReportClosed attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InventFiscalLIFOGroup name="InventFiscalLIFOGroup">InventFiscalLIFOGroup</a>

First included in: WorksheetLine/InventFiscalLIFOJournalTransAdj (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventFiscalLIFOGroup attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ItemId name="ItemId">ItemId</a>

First included in: WorksheetLine/InventFiscalLIFOJournalTransAdj (this entity)  

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

First included in: WorksheetLine/InventFiscalLIFOJournalTransAdj (this entity)  

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

### <a href=#RemainQtyAdj name="RemainQtyAdj">RemainQtyAdj</a>

First included in: WorksheetLine/InventFiscalLIFOJournalTransAdj (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemainQtyAdj attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Year name="Year">Year</a>

First included in: WorksheetLine/InventFiscalLIFOJournalTransAdj (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Year attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#YearAdj name="YearAdj">YearAdj</a>

First included in: WorksheetLine/InventFiscalLIFOJournalTransAdj (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the YearAdj attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetLine/InventFiscalLIFOJournalTransAdj (this entity)  

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

### <a href=#Relationship_InventFiscalLIFOGroupRelationshipId name="Relationship_InventFiscalLIFOGroupRelationshipId">Relationship_InventFiscalLIFOGroupRelationshipId</a>

First included in: WorksheetLine/InventFiscalLIFOJournalTransAdj (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventFiscalLIFOGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/InventFiscalLIFOGroup.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/Group/InventFiscalLIFOGroup.cdm.json/InventFiscalLIFOGroup</a></td><td><a href="../Group/InventFiscalLIFOGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventFiscalLIFOJournalTableRelationshipId name="Relationship_InventFiscalLIFOJournalTableRelationshipId">Relationship_InventFiscalLIFOJournalTableRelationshipId</a>

First included in: WorksheetLine/InventFiscalLIFOJournalTransAdj (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventFiscalLIFOJournalTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/InventFiscalLIFOJournalTable.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/WorksheetHeader/InventFiscalLIFOJournalTable.cdm.json/InventFiscalLIFOJournalTable</a></td><td><a href="../WorksheetHeader/InventFiscalLIFOJournalTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventTableRelationshipId name="Relationship_InventTableRelationshipId">Relationship_InventTableRelationshipId</a>

First included in: WorksheetLine/InventFiscalLIFOJournalTransAdj (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProductInformationManagement/Main/InventTable.md" target="_blank">/core/erp/Tables/SupplyChain/ProductInformationManagement/Main/InventTable.cdm.json/InventTable</a></td><td><a href="../../ProductInformationManagement/Main/InventTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetLine/InventFiscalLIFOJournalTransAdj (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/erp/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
