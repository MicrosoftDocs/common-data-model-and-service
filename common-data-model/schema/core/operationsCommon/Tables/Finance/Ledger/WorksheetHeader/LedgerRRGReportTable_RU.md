---
title: LedgerRRGReportTable_RU - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Reports

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Ledger/WorksheetHeader/LedgerRRGReportTable_RU.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[LedgerRRGReportTable_RU/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reports</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="LedgerRRGReportTable_RU.md" target="_blank">WorksheetHeader/LedgerRRGReportTable_RU</a>|
|[CurrencyForCalc](#CurrencyForCalc)||<a href="LedgerRRGReportTable_RU.md" target="_blank">WorksheetHeader/LedgerRRGReportTable_RU</a>|
|[DataType](#DataType)||<a href="LedgerRRGReportTable_RU.md" target="_blank">WorksheetHeader/LedgerRRGReportTable_RU</a>|
|[Description](#Description)||<a href="LedgerRRGReportTable_RU.md" target="_blank">WorksheetHeader/LedgerRRGReportTable_RU</a>|
|[LedgerPeriodCode](#LedgerPeriodCode)||<a href="LedgerRRGReportTable_RU.md" target="_blank">WorksheetHeader/LedgerRRGReportTable_RU</a>|
|[LedgerRRGETemplates_W](#LedgerRRGETemplates_W)||<a href="LedgerRRGReportTable_RU.md" target="_blank">WorksheetHeader/LedgerRRGReportTable_RU</a>|
|[ModelNum](#ModelNum)||<a href="LedgerRRGReportTable_RU.md" target="_blank">WorksheetHeader/LedgerRRGReportTable_RU</a>|
|[PointSignNum](#PointSignNum)||<a href="LedgerRRGReportTable_RU.md" target="_blank">WorksheetHeader/LedgerRRGReportTable_RU</a>|
|[RepCode](#RepCode)||<a href="LedgerRRGReportTable_RU.md" target="_blank">WorksheetHeader/LedgerRRGReportTable_RU</a>|
|[ReportType](#ReportType)||<a href="LedgerRRGReportTable_RU.md" target="_blank">WorksheetHeader/LedgerRRGReportTable_RU</a>|
|[Scale](#Scale)||<a href="LedgerRRGReportTable_RU.md" target="_blank">WorksheetHeader/LedgerRRGReportTable_RU</a>|
|[Template](#Template)||<a href="LedgerRRGReportTable_RU.md" target="_blank">WorksheetHeader/LedgerRRGReportTable_RU</a>|
|[TypeByCorrect](#TypeByCorrect)||<a href="LedgerRRGReportTable_RU.md" target="_blank">WorksheetHeader/LedgerRRGReportTable_RU</a>|
|[DimensionHierarchy](#DimensionHierarchy)||<a href="LedgerRRGReportTable_RU.md" target="_blank">WorksheetHeader/LedgerRRGReportTable_RU</a>|
|[DataAreaId](#DataAreaId)||<a href="LedgerRRGReportTable_RU.md" target="_blank">WorksheetHeader/LedgerRRGReportTable_RU</a>|
|[Relationship_BudgetModelRelationshipId](#Relationship_BudgetModelRelationshipId)||<a href="LedgerRRGReportTable_RU.md" target="_blank">WorksheetHeader/LedgerRRGReportTable_RU</a>|
|[Relationship_LedgerPeriodCodeRelationshipId](#Relationship_LedgerPeriodCodeRelationshipId)||<a href="LedgerRRGReportTable_RU.md" target="_blank">WorksheetHeader/LedgerRRGReportTable_RU</a>|
|[Relationship_LedgerRRGETemplates_WRelationshipId](#Relationship_LedgerRRGETemplates_WRelationshipId)||<a href="LedgerRRGReportTable_RU.md" target="_blank">WorksheetHeader/LedgerRRGReportTable_RU</a>|
|[Relationship_DimensionHierarchyRelationshipId](#Relationship_DimensionHierarchyRelationshipId)||<a href="LedgerRRGReportTable_RU.md" target="_blank">WorksheetHeader/LedgerRRGReportTable_RU</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="LedgerRRGReportTable_RU.md" target="_blank">WorksheetHeader/LedgerRRGReportTable_RU</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetHeader/LedgerRRGReportTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[LedgerRRGReportTable_RU/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CurrencyForCalc name="CurrencyForCalc">CurrencyForCalc</a>

First included in: WorksheetHeader/LedgerRRGReportTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyForCalc attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DataType name="DataType">DataType</a>

First included in: WorksheetHeader/LedgerRRGReportTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: WorksheetHeader/LedgerRRGReportTable_RU (this entity)  

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

### <a href=#LedgerPeriodCode name="LedgerPeriodCode">LedgerPeriodCode</a>

First included in: WorksheetHeader/LedgerRRGReportTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerPeriodCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerRRGETemplates_W name="LedgerRRGETemplates_W">LedgerRRGETemplates_W</a>

First included in: WorksheetHeader/LedgerRRGReportTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerRRGETemplates_W attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ModelNum name="ModelNum">ModelNum</a>

First included in: WorksheetHeader/LedgerRRGReportTable_RU (this entity)  

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

First included in: WorksheetHeader/LedgerRRGReportTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PointSignNum attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RepCode name="RepCode">RepCode</a>

First included in: WorksheetHeader/LedgerRRGReportTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RepCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportType name="ReportType">ReportType</a>

First included in: WorksheetHeader/LedgerRRGReportTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Scale name="Scale">Scale</a>

First included in: WorksheetHeader/LedgerRRGReportTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Scale attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Template name="Template">Template</a>

First included in: WorksheetHeader/LedgerRRGReportTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Template attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TypeByCorrect name="TypeByCorrect">TypeByCorrect</a>

First included in: WorksheetHeader/LedgerRRGReportTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TypeByCorrect attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DimensionHierarchy name="DimensionHierarchy">DimensionHierarchy</a>

First included in: WorksheetHeader/LedgerRRGReportTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionHierarchy attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetHeader/LedgerRRGReportTable_RU (this entity)  

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

First included in: WorksheetHeader/LedgerRRGReportTable_RU (this entity)  

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

First included in: WorksheetHeader/LedgerRRGReportTable_RU (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/LedgerPeriodCode.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Group/LedgerPeriodCode.cdm.json/LedgerPeriodCode</a></td><td><a href="../Group/LedgerPeriodCode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerRRGETemplates_WRelationshipId name="Relationship_LedgerRRGETemplates_WRelationshipId">Relationship_LedgerRRGETemplates_WRelationshipId</a>

First included in: WorksheetHeader/LedgerRRGReportTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerRRGETemplates_WRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/LedgerRRGETemplates_W.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Group/LedgerRRGETemplates_W.cdm.json/LedgerRRGETemplates_W</a></td><td><a href="../Group/LedgerRRGETemplates_W.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DimensionHierarchyRelationshipId name="Relationship_DimensionHierarchyRelationshipId">Relationship_DimensionHierarchyRelationshipId</a>

First included in: WorksheetHeader/LedgerRRGReportTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DimensionHierarchyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Group/DimensionHierarchy.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Group/DimensionHierarchy.cdm.json/DimensionHierarchy</a></td><td><a href="../../FinancialDimensions/Group/DimensionHierarchy.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetHeader/LedgerRRGReportTable_RU (this entity)  

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
