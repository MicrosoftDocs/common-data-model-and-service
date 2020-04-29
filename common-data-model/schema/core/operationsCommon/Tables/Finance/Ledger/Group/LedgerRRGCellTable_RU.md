---
title: LedgerRRGCellTable_RU - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# Reports cells

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Ledger/Group/LedgerRRGCellTable_RU.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[LedgerRRGCellTable_RU/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reports cells</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="LedgerRRGCellTable_RU.md" target="_blank">Group/LedgerRRGCellTable_RU</a>|
|[Alignment](#Alignment)||<a href="LedgerRRGCellTable_RU.md" target="_blank">Group/LedgerRRGCellTable_RU</a>|
|[CellCode](#CellCode)||<a href="LedgerRRGCellTable_RU.md" target="_blank">Group/LedgerRRGCellTable_RU</a>|
|[DataType](#DataType)||<a href="LedgerRRGCellTable_RU.md" target="_blank">Group/LedgerRRGCellTable_RU</a>|
|[Description](#Description)||<a href="LedgerRRGCellTable_RU.md" target="_blank">Group/LedgerRRGCellTable_RU</a>|
|[EmptyChar](#EmptyChar)||<a href="LedgerRRGCellTable_RU.md" target="_blank">Group/LedgerRRGCellTable_RU</a>|
|[IsStatic](#IsStatic)||<a href="LedgerRRGCellTable_RU.md" target="_blank">Group/LedgerRRGCellTable_RU</a>|
|[LedgerPeriodCode](#LedgerPeriodCode)||<a href="LedgerRRGCellTable_RU.md" target="_blank">Group/LedgerRRGCellTable_RU</a>|
|[Length](#Length)||<a href="LedgerRRGCellTable_RU.md" target="_blank">Group/LedgerRRGCellTable_RU</a>|
|[ModelNum](#ModelNum)||<a href="LedgerRRGCellTable_RU.md" target="_blank">Group/LedgerRRGCellTable_RU</a>|
|[PointSignNum](#PointSignNum)||<a href="LedgerRRGCellTable_RU.md" target="_blank">Group/LedgerRRGCellTable_RU</a>|
|[PropertyRefRecId](#PropertyRefRecId)||<a href="LedgerRRGCellTable_RU.md" target="_blank">Group/LedgerRRGCellTable_RU</a>|
|[ReportRecId](#ReportRecId)||<a href="LedgerRRGCellTable_RU.md" target="_blank">Group/LedgerRRGCellTable_RU</a>|
|[RTax25FieldId](#RTax25FieldId)||<a href="LedgerRRGCellTable_RU.md" target="_blank">Group/LedgerRRGCellTable_RU</a>|
|[RTax25RegisterId](#RTax25RegisterId)||<a href="LedgerRRGCellTable_RU.md" target="_blank">Group/LedgerRRGCellTable_RU</a>|
|[TypeByCorrect](#TypeByCorrect)||<a href="LedgerRRGCellTable_RU.md" target="_blank">Group/LedgerRRGCellTable_RU</a>|
|[LineId](#LineId)||<a href="LedgerRRGCellTable_RU.md" target="_blank">Group/LedgerRRGCellTable_RU</a>|
|[DataAreaId](#DataAreaId)||<a href="LedgerRRGCellTable_RU.md" target="_blank">Group/LedgerRRGCellTable_RU</a>|
|[Relationship_BudgetModelRelationshipId](#Relationship_BudgetModelRelationshipId)||<a href="LedgerRRGCellTable_RU.md" target="_blank">Group/LedgerRRGCellTable_RU</a>|
|[Relationship_LedgerPeriodCodeRelationshipId](#Relationship_LedgerPeriodCodeRelationshipId)||<a href="LedgerRRGCellTable_RU.md" target="_blank">Group/LedgerRRGCellTable_RU</a>|
|[Relationship_LedgerRRGESectionProperties_WRelationshipId](#Relationship_LedgerRRGESectionProperties_WRelationshipId)||<a href="LedgerRRGCellTable_RU.md" target="_blank">Group/LedgerRRGCellTable_RU</a>|
|[Relationship_LedgerRRGReportTable_RURelationshipId](#Relationship_LedgerRRGReportTable_RURelationshipId)||<a href="LedgerRRGCellTable_RU.md" target="_blank">Group/LedgerRRGCellTable_RU</a>|
|[Relationship_RTax25RegisterTableRelationshipId](#Relationship_RTax25RegisterTableRelationshipId)||<a href="LedgerRRGCellTable_RU.md" target="_blank">Group/LedgerRRGCellTable_RU</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="LedgerRRGCellTable_RU.md" target="_blank">Group/LedgerRRGCellTable_RU</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Group/LedgerRRGCellTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[LedgerRRGCellTable_RU/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Alignment name="Alignment">Alignment</a>

First included in: Group/LedgerRRGCellTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Alignment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CellCode name="CellCode">CellCode</a>

First included in: Group/LedgerRRGCellTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CellCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataType name="DataType">DataType</a>

First included in: Group/LedgerRRGCellTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: Group/LedgerRRGCellTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmptyChar name="EmptyChar">EmptyChar</a>

First included in: Group/LedgerRRGCellTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmptyChar attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsStatic name="IsStatic">IsStatic</a>

First included in: Group/LedgerRRGCellTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Manual data input</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsStatic attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Manual data input</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#LedgerPeriodCode name="LedgerPeriodCode">LedgerPeriodCode</a>

First included in: Group/LedgerRRGCellTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Period</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerPeriodCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Period</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Length name="Length">Length</a>

First included in: Group/LedgerRRGCellTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Length attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ModelNum name="ModelNum">ModelNum</a>

First included in: Group/LedgerRRGCellTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ModelNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PointSignNum name="PointSignNum">PointSignNum</a>

First included in: Group/LedgerRRGCellTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PointSignNum attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PropertyRefRecId name="PropertyRefRecId">PropertyRefRecId</a>

First included in: Group/LedgerRRGCellTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PropertyRefRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ReportRecId name="ReportRecId">ReportRecId</a>

First included in: Group/LedgerRRGCellTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RTax25FieldId name="RTax25FieldId">RTax25FieldId</a>

First included in: Group/LedgerRRGCellTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RTax25FieldId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#RTax25RegisterId name="RTax25RegisterId">RTax25RegisterId</a>

First included in: Group/LedgerRRGCellTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RTax25RegisterId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TypeByCorrect name="TypeByCorrect">TypeByCorrect</a>

First included in: Group/LedgerRRGCellTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TypeByCorrect attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LineId name="LineId">LineId</a>

First included in: Group/LedgerRRGCellTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Group/LedgerRRGCellTable_RU (this entity)  

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

### <a href=#Relationship_BudgetModelRelationshipId name="Relationship_BudgetModelRelationshipId">Relationship_BudgetModelRelationshipId</a>

First included in: Group/LedgerRRGCellTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BudgetModelRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Budget/Group/BudgetModel.md" target="_blank">/core/operationsCommon/Tables/Finance/Budget/Group/BudgetModel.cdm.json/BudgetModel</a></td><td><a href="../../Budget/Group/BudgetModel.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerPeriodCodeRelationshipId name="Relationship_LedgerPeriodCodeRelationshipId">Relationship_LedgerPeriodCodeRelationshipId</a>

First included in: Group/LedgerRRGCellTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerPeriodCodeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="LedgerPeriodCode.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Group/LedgerPeriodCode.cdm.json/LedgerPeriodCode</a></td><td><a href="LedgerPeriodCode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerRRGESectionProperties_WRelationshipId name="Relationship_LedgerRRGESectionProperties_WRelationshipId">Relationship_LedgerRRGESectionProperties_WRelationshipId</a>

First included in: Group/LedgerRRGCellTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerRRGESectionProperties_WRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/LedgerRRGESectionProperties_W.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Miscellaneous/LedgerRRGESectionProperties_W.cdm.json/LedgerRRGESectionProperties_W</a></td><td><a href="../Miscellaneous/LedgerRRGESectionProperties_W.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerRRGReportTable_RURelationshipId name="Relationship_LedgerRRGReportTable_RURelationshipId">Relationship_LedgerRRGReportTable_RURelationshipId</a>

First included in: Group/LedgerRRGCellTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerRRGReportTable_RURelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_RTax25RegisterTableRelationshipId name="Relationship_RTax25RegisterTableRelationshipId">Relationship_RTax25RegisterTableRelationshipId</a>

First included in: Group/LedgerRRGCellTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RTax25RegisterTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../RTax25/Main/RTax25RegisterTable.md" target="_blank">/core/operationsCommon/Tables/Finance/RTax25/Main/RTax25RegisterTable.cdm.json/RTax25RegisterTable</a></td><td><a href="../../RTax25/Main/RTax25RegisterTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Group/LedgerRRGCellTable_RU (this entity)  

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
