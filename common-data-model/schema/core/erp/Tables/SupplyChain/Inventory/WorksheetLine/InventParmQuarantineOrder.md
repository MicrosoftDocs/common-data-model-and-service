---
title: InventParmQuarantineOrder - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# InventParmQuarantineOrder

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/SupplyChain/Inventory/WorksheetLine/InventParmQuarantineOrder.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[InventParmQuarantineOrder/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="InventParmQuarantineOrder.md" target="_blank">WorksheetLine/InventParmQuarantineOrder</a>|
|[ExecutedDateTime](#ExecutedDateTime)||<a href="InventParmQuarantineOrder.md" target="_blank">WorksheetLine/InventParmQuarantineOrder</a>|
|[JobStatus](#JobStatus)||<a href="InventParmQuarantineOrder.md" target="_blank">WorksheetLine/InventParmQuarantineOrder</a>|
|[LineNum](#LineNum)||<a href="InventParmQuarantineOrder.md" target="_blank">WorksheetLine/InventParmQuarantineOrder</a>|
|[ParmId](#ParmId)||<a href="InventParmQuarantineOrder.md" target="_blank">WorksheetLine/InventParmQuarantineOrder</a>|
|[PdsCWQty](#PdsCWQty)||<a href="InventParmQuarantineOrder.md" target="_blank">WorksheetLine/InventParmQuarantineOrder</a>|
|[Qty](#Qty)||<a href="InventParmQuarantineOrder.md" target="_blank">WorksheetLine/InventParmQuarantineOrder</a>|
|[QuarantineId](#QuarantineId)||<a href="InventParmQuarantineOrder.md" target="_blank">WorksheetLine/InventParmQuarantineOrder</a>|
|[TransDate](#TransDate)||<a href="InventParmQuarantineOrder.md" target="_blank">WorksheetLine/InventParmQuarantineOrder</a>|
|[Type](#Type)||<a href="InventParmQuarantineOrder.md" target="_blank">WorksheetLine/InventParmQuarantineOrder</a>|
|[WMSJournalId](#WMSJournalId)||<a href="InventParmQuarantineOrder.md" target="_blank">WorksheetLine/InventParmQuarantineOrder</a>|
|[WMSJournalNameId](#WMSJournalNameId)||<a href="InventParmQuarantineOrder.md" target="_blank">WorksheetLine/InventParmQuarantineOrder</a>|
|[DataAreaId](#DataAreaId)||<a href="InventParmQuarantineOrder.md" target="_blank">WorksheetLine/InventParmQuarantineOrder</a>|
|[Relationship_InventQuarantineOrderRelationshipId](#Relationship_InventQuarantineOrderRelationshipId)||<a href="InventParmQuarantineOrder.md" target="_blank">WorksheetLine/InventParmQuarantineOrder</a>|
|[Relationship_WMSJournalNameRelationshipId](#Relationship_WMSJournalNameRelationshipId)||<a href="InventParmQuarantineOrder.md" target="_blank">WorksheetLine/InventParmQuarantineOrder</a>|
|[Relationship_WMSJournalTableRelationshipId](#Relationship_WMSJournalTableRelationshipId)||<a href="InventParmQuarantineOrder.md" target="_blank">WorksheetLine/InventParmQuarantineOrder</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="InventParmQuarantineOrder.md" target="_blank">WorksheetLine/InventParmQuarantineOrder</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetLine/InventParmQuarantineOrder (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[InventParmQuarantineOrder/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ExecutedDateTime name="ExecutedDateTime">ExecutedDateTime</a>

First included in: WorksheetLine/InventParmQuarantineOrder (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExecutedDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.dataFormat.date**  
</details>

### <a href=#JobStatus name="JobStatus">JobStatus</a>

First included in: WorksheetLine/InventParmQuarantineOrder (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JobStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#LineNum name="LineNum">LineNum</a>

First included in: WorksheetLine/InventParmQuarantineOrder (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNum attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ParmId name="ParmId">ParmId</a>

First included in: WorksheetLine/InventParmQuarantineOrder (this entity)  

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

First included in: WorksheetLine/InventParmQuarantineOrder (this entity)  

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

### <a href=#Qty name="Qty">Qty</a>

First included in: WorksheetLine/InventParmQuarantineOrder (this entity)  

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

### <a href=#QuarantineId name="QuarantineId">QuarantineId</a>

First included in: WorksheetLine/InventParmQuarantineOrder (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuarantineId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransDate name="TransDate">TransDate</a>

First included in: WorksheetLine/InventParmQuarantineOrder (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#Type name="Type">Type</a>

First included in: WorksheetLine/InventParmQuarantineOrder (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Type attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#WMSJournalId name="WMSJournalId">WMSJournalId</a>

First included in: WorksheetLine/InventParmQuarantineOrder (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WMSJournalId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WMSJournalNameId name="WMSJournalNameId">WMSJournalNameId</a>

First included in: WorksheetLine/InventParmQuarantineOrder (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WMSJournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetLine/InventParmQuarantineOrder (this entity)  

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

### <a href=#Relationship_InventQuarantineOrderRelationshipId name="Relationship_InventQuarantineOrderRelationshipId">Relationship_InventQuarantineOrderRelationshipId</a>

First included in: WorksheetLine/InventParmQuarantineOrder (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventQuarantineOrderRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="InventQuarantineOrder.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/WorksheetLine/InventQuarantineOrder.cdm.json/InventQuarantineOrder</a></td><td><a href="InventQuarantineOrder.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WMSJournalNameRelationshipId name="Relationship_WMSJournalNameRelationshipId">Relationship_WMSJournalNameRelationshipId</a>

First included in: WorksheetLine/InventParmQuarantineOrder (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WMSJournalNameRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/WMSJournalName.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/Group/WMSJournalName.cdm.json/WMSJournalName</a></td><td><a href="../Group/WMSJournalName.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WMSJournalTableRelationshipId name="Relationship_WMSJournalTableRelationshipId">Relationship_WMSJournalTableRelationshipId</a>

First included in: WorksheetLine/InventParmQuarantineOrder (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WMSJournalTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/WMSJournalTable.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/WorksheetHeader/WMSJournalTable.cdm.json/WMSJournalTable</a></td><td><a href="../WorksheetHeader/WMSJournalTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetLine/InventParmQuarantineOrder (this entity)  

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
