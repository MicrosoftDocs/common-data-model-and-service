---
title: InventTestCertOfAnalysisLine in WorksheetLine - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Certificate of analysis lines in WorksheetLine(InventTestCertOfAnalysisLine)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/Inventory/WorksheetLine/InventTestCertOfAnalysisLine.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[InventTestCertOfAnalysisLine/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Certificate of analysis lines</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="InventTestCertOfAnalysisLine.md" target="_blank">WorksheetLine/InventTestCertOfAnalysisLine</a>|
|[InventCertificateOfAnalysisId](#InventCertificateOfAnalysisId)||<a href="InventTestCertOfAnalysisLine.md" target="_blank">WorksheetLine/InventTestCertOfAnalysisLine</a>|
|[LowerLimit](#LowerLimit)||<a href="InventTestCertOfAnalysisLine.md" target="_blank">WorksheetLine/InventTestCertOfAnalysisLine</a>|
|[LowerTolerance](#LowerTolerance)||<a href="InventTestCertOfAnalysisLine.md" target="_blank">WorksheetLine/InventTestCertOfAnalysisLine</a>|
|[StandardValue](#StandardValue)||<a href="InventTestCertOfAnalysisLine.md" target="_blank">WorksheetLine/InventTestCertOfAnalysisLine</a>|
|[TestId](#TestId)||<a href="InventTestCertOfAnalysisLine.md" target="_blank">WorksheetLine/InventTestCertOfAnalysisLine</a>|
|[TestResult](#TestResult)||<a href="InventTestCertOfAnalysisLine.md" target="_blank">WorksheetLine/InventTestCertOfAnalysisLine</a>|
|[TestSequence](#TestSequence)||<a href="InventTestCertOfAnalysisLine.md" target="_blank">WorksheetLine/InventTestCertOfAnalysisLine</a>|
|[TestUnitId](#TestUnitId)||<a href="InventTestCertOfAnalysisLine.md" target="_blank">WorksheetLine/InventTestCertOfAnalysisLine</a>|
|[UpperLimit](#UpperLimit)||<a href="InventTestCertOfAnalysisLine.md" target="_blank">WorksheetLine/InventTestCertOfAnalysisLine</a>|
|[UpperTolerance](#UpperTolerance)||<a href="InventTestCertOfAnalysisLine.md" target="_blank">WorksheetLine/InventTestCertOfAnalysisLine</a>|
|[VariableOutcomeIdStandard](#VariableOutcomeIdStandard)||<a href="InventTestCertOfAnalysisLine.md" target="_blank">WorksheetLine/InventTestCertOfAnalysisLine</a>|
|[DataAreaId](#DataAreaId)||<a href="InventTestCertOfAnalysisLine.md" target="_blank">WorksheetLine/InventTestCertOfAnalysisLine</a>|
|[Relationship_InventTestCertOfAnalysisTableRelationshipId](#Relationship_InventTestCertOfAnalysisTableRelationshipId)||<a href="InventTestCertOfAnalysisLine.md" target="_blank">WorksheetLine/InventTestCertOfAnalysisLine</a>|
|[Relationship_InventTestTableRelationshipId](#Relationship_InventTestTableRelationshipId)||<a href="InventTestCertOfAnalysisLine.md" target="_blank">WorksheetLine/InventTestCertOfAnalysisLine</a>|
|[Relationship_InventTestVariableOutcomeRelationshipId](#Relationship_InventTestVariableOutcomeRelationshipId)||<a href="InventTestCertOfAnalysisLine.md" target="_blank">WorksheetLine/InventTestCertOfAnalysisLine</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="InventTestCertOfAnalysisLine.md" target="_blank">WorksheetLine/InventTestCertOfAnalysisLine</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetLine/InventTestCertOfAnalysisLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[InventTestCertOfAnalysisLine/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#InventCertificateOfAnalysisId name="InventCertificateOfAnalysisId">InventCertificateOfAnalysisId</a>

First included in: WorksheetLine/InventTestCertOfAnalysisLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventCertificateOfAnalysisId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LowerLimit name="LowerLimit">LowerLimit</a>

First included in: WorksheetLine/InventTestCertOfAnalysisLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LowerLimit attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#LowerTolerance name="LowerTolerance">LowerTolerance</a>

First included in: WorksheetLine/InventTestCertOfAnalysisLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LowerTolerance attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#StandardValue name="StandardValue">StandardValue</a>

First included in: WorksheetLine/InventTestCertOfAnalysisLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StandardValue attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TestId name="TestId">TestId</a>

First included in: WorksheetLine/InventTestCertOfAnalysisLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TestId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TestResult name="TestResult">TestResult</a>

First included in: WorksheetLine/InventTestCertOfAnalysisLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Test result</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TestResult attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Test result</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#TestSequence name="TestSequence">TestSequence</a>

First included in: WorksheetLine/InventTestCertOfAnalysisLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TestSequence attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TestUnitId name="TestUnitId">TestUnitId</a>

First included in: WorksheetLine/InventTestCertOfAnalysisLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TestUnitId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UpperLimit name="UpperLimit">UpperLimit</a>

First included in: WorksheetLine/InventTestCertOfAnalysisLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UpperLimit attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#UpperTolerance name="UpperTolerance">UpperTolerance</a>

First included in: WorksheetLine/InventTestCertOfAnalysisLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UpperTolerance attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#VariableOutcomeIdStandard name="VariableOutcomeIdStandard">VariableOutcomeIdStandard</a>

First included in: WorksheetLine/InventTestCertOfAnalysisLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VariableOutcomeIdStandard attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetLine/InventTestCertOfAnalysisLine (this entity)  

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

### <a href=#Relationship_InventTestCertOfAnalysisTableRelationshipId name="Relationship_InventTestCertOfAnalysisTableRelationshipId">Relationship_InventTestCertOfAnalysisTableRelationshipId</a>

First included in: WorksheetLine/InventTestCertOfAnalysisLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventTestCertOfAnalysisTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/InventTestCertOfAnalysisTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/WorksheetHeader/InventTestCertOfAnalysisTable.cdm.json/InventTestCertOfAnalysisTable</a></td><td><a href="../WorksheetHeader/InventTestCertOfAnalysisTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventTestTableRelationshipId name="Relationship_InventTestTableRelationshipId">Relationship_InventTestTableRelationshipId</a>

First included in: WorksheetLine/InventTestCertOfAnalysisLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventTestTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/InventTestTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/InventTestTable.cdm.json/InventTestTable</a></td><td><a href="../Main/InventTestTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventTestVariableOutcomeRelationshipId name="Relationship_InventTestVariableOutcomeRelationshipId">Relationship_InventTestVariableOutcomeRelationshipId</a>

First included in: WorksheetLine/InventTestCertOfAnalysisLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventTestVariableOutcomeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/InventTestVariableOutcome.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/InventTestVariableOutcome.cdm.json/InventTestVariableOutcome</a></td><td><a href="../Main/InventTestVariableOutcome.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetLine/InventTestCertOfAnalysisLine (this entity)  

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
