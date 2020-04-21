---
title: InventFiscalLIFOJournalTrans - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# InventFiscalLIFOJournalTrans

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/Inventory/WorksheetLine/InventFiscalLIFOJournalTrans.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[InventFiscalLIFOJournalTrans/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="InventFiscalLIFOJournalTrans.md" target="_blank">WorksheetLine/InventFiscalLIFOJournalTrans</a>|
|[Individual](#Individual)||<a href="InventFiscalLIFOJournalTrans.md" target="_blank">WorksheetLine/InventFiscalLIFOJournalTrans</a>|
|[InventFiscalLIFOGroup](#InventFiscalLIFOGroup)||<a href="InventFiscalLIFOJournalTrans.md" target="_blank">WorksheetLine/InventFiscalLIFOJournalTrans</a>|
|[ItemGroup](#ItemGroup)||<a href="InventFiscalLIFOJournalTrans.md" target="_blank">WorksheetLine/InventFiscalLIFOJournalTrans</a>|
|[ItemId](#ItemId)||<a href="InventFiscalLIFOJournalTrans.md" target="_blank">WorksheetLine/InventFiscalLIFOJournalTrans</a>|
|[JournalId](#JournalId)||<a href="InventFiscalLIFOJournalTrans.md" target="_blank">WorksheetLine/InventFiscalLIFOJournalTrans</a>|
|[LineNum](#LineNum)||<a href="InventFiscalLIFOJournalTrans.md" target="_blank">WorksheetLine/InventFiscalLIFOJournalTrans</a>|
|[NormalValue](#NormalValue)||<a href="InventFiscalLIFOJournalTrans.md" target="_blank">WorksheetLine/InventFiscalLIFOJournalTrans</a>|
|[QtyIssue](#QtyIssue)||<a href="InventFiscalLIFOJournalTrans.md" target="_blank">WorksheetLine/InventFiscalLIFOJournalTrans</a>|
|[QtyPrimo](#QtyPrimo)||<a href="InventFiscalLIFOJournalTrans.md" target="_blank">WorksheetLine/InventFiscalLIFOJournalTrans</a>|
|[QtyReceipt](#QtyReceipt)||<a href="InventFiscalLIFOJournalTrans.md" target="_blank">WorksheetLine/InventFiscalLIFOJournalTrans</a>|
|[RemainQty](#RemainQty)||<a href="InventFiscalLIFOJournalTrans.md" target="_blank">WorksheetLine/InventFiscalLIFOJournalTrans</a>|
|[TransDate](#TransDate)||<a href="InventFiscalLIFOJournalTrans.md" target="_blank">WorksheetLine/InventFiscalLIFOJournalTrans</a>|
|[UnitId](#UnitId)||<a href="InventFiscalLIFOJournalTrans.md" target="_blank">WorksheetLine/InventFiscalLIFOJournalTrans</a>|
|[UnitValue](#UnitValue)||<a href="InventFiscalLIFOJournalTrans.md" target="_blank">WorksheetLine/InventFiscalLIFOJournalTrans</a>|
|[WIPIncluded](#WIPIncluded)||<a href="InventFiscalLIFOJournalTrans.md" target="_blank">WorksheetLine/InventFiscalLIFOJournalTrans</a>|
|[Yr](#Yr)||<a href="InventFiscalLIFOJournalTrans.md" target="_blank">WorksheetLine/InventFiscalLIFOJournalTrans</a>|
|[DataAreaId](#DataAreaId)||<a href="InventFiscalLIFOJournalTrans.md" target="_blank">WorksheetLine/InventFiscalLIFOJournalTrans</a>|
|[Relationship_InventFiscalLIFOGroupRelationshipId](#Relationship_InventFiscalLIFOGroupRelationshipId)||<a href="InventFiscalLIFOJournalTrans.md" target="_blank">WorksheetLine/InventFiscalLIFOJournalTrans</a>|
|[Relationship_InventFiscalLIFOJournalTableRelationshipId](#Relationship_InventFiscalLIFOJournalTableRelationshipId)||<a href="InventFiscalLIFOJournalTrans.md" target="_blank">WorksheetLine/InventFiscalLIFOJournalTrans</a>|
|[Relationship_InventTableRelationshipId](#Relationship_InventTableRelationshipId)||<a href="InventFiscalLIFOJournalTrans.md" target="_blank">WorksheetLine/InventFiscalLIFOJournalTrans</a>|
|[Relationship_JournalErrorRelationshipId](#Relationship_JournalErrorRelationshipId)||<a href="InventFiscalLIFOJournalTrans.md" target="_blank">WorksheetLine/InventFiscalLIFOJournalTrans</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="InventFiscalLIFOJournalTrans.md" target="_blank">WorksheetLine/InventFiscalLIFOJournalTrans</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetLine/InventFiscalLIFOJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[InventFiscalLIFOJournalTrans/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Individual name="Individual">Individual</a>

First included in: WorksheetLine/InventFiscalLIFOJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Individual attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InventFiscalLIFOGroup name="InventFiscalLIFOGroup">InventFiscalLIFOGroup</a>

First included in: WorksheetLine/InventFiscalLIFOJournalTrans (this entity)  

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

### <a href=#ItemGroup name="ItemGroup">ItemGroup</a>

First included in: WorksheetLine/InventFiscalLIFOJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemGroup attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ItemId name="ItemId">ItemId</a>

First included in: WorksheetLine/InventFiscalLIFOJournalTrans (this entity)  

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

First included in: WorksheetLine/InventFiscalLIFOJournalTrans (this entity)  

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

### <a href=#LineNum name="LineNum">LineNum</a>

First included in: WorksheetLine/InventFiscalLIFOJournalTrans (this entity)  

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

### <a href=#NormalValue name="NormalValue">NormalValue</a>

First included in: WorksheetLine/InventFiscalLIFOJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NormalValue attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#QtyIssue name="QtyIssue">QtyIssue</a>

First included in: WorksheetLine/InventFiscalLIFOJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QtyIssue attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#QtyPrimo name="QtyPrimo">QtyPrimo</a>

First included in: WorksheetLine/InventFiscalLIFOJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QtyPrimo attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#QtyReceipt name="QtyReceipt">QtyReceipt</a>

First included in: WorksheetLine/InventFiscalLIFOJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QtyReceipt attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#RemainQty name="RemainQty">RemainQty</a>

First included in: WorksheetLine/InventFiscalLIFOJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemainQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TransDate name="TransDate">TransDate</a>

First included in: WorksheetLine/InventFiscalLIFOJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#UnitId name="UnitId">UnitId</a>

First included in: WorksheetLine/InventFiscalLIFOJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnitValue name="UnitValue">UnitValue</a>

First included in: WorksheetLine/InventFiscalLIFOJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitValue attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#WIPIncluded name="WIPIncluded">WIPIncluded</a>

First included in: WorksheetLine/InventFiscalLIFOJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WIPIncluded attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#Yr name="Yr">Yr</a>

First included in: WorksheetLine/InventFiscalLIFOJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Yr attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetLine/InventFiscalLIFOJournalTrans (this entity)  

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

First included in: WorksheetLine/InventFiscalLIFOJournalTrans (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/InventFiscalLIFOGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/InventFiscalLIFOGroup.cdm.json/InventFiscalLIFOGroup</a></td><td><a href="../Group/InventFiscalLIFOGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventFiscalLIFOJournalTableRelationshipId name="Relationship_InventFiscalLIFOJournalTableRelationshipId">Relationship_InventFiscalLIFOJournalTableRelationshipId</a>

First included in: WorksheetLine/InventFiscalLIFOJournalTrans (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/InventFiscalLIFOJournalTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/WorksheetHeader/InventFiscalLIFOJournalTable.cdm.json/InventFiscalLIFOJournalTable</a></td><td><a href="../WorksheetHeader/InventFiscalLIFOJournalTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventTableRelationshipId name="Relationship_InventTableRelationshipId">Relationship_InventTableRelationshipId</a>

First included in: WorksheetLine/InventFiscalLIFOJournalTrans (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProductInformationManagement/Main/InventTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/InventTable.cdm.json/InventTable</a></td><td><a href="../../ProductInformationManagement/Main/InventTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_JournalErrorRelationshipId name="Relationship_JournalErrorRelationshipId">Relationship_JournalErrorRelationshipId</a>

First included in: WorksheetLine/InventFiscalLIFOJournalTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_JournalErrorRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="JournalError.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/WorksheetLine/JournalError.cdm.json/JournalError</a></td><td><a href="JournalError.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetLine/InventFiscalLIFOJournalTrans (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
