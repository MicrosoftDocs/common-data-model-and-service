---
title: InventQualityOrderLine in WorksheetLine - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Quality order lines in WorksheetLine(InventQualityOrderLine)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/Inventory/WorksheetLine/InventQualityOrderLine.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[InventQualityOrderLine/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Quality order lines</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="InventQualityOrderLine.md" target="_blank">WorksheetLine/InventQualityOrderLine</a>|
|[AcceptableQualityLevel](#AcceptableQualityLevel)||<a href="InventQualityOrderLine.md" target="_blank">WorksheetLine/InventQualityOrderLine</a>|
|[ActionOnFailure](#ActionOnFailure)||<a href="InventQualityOrderLine.md" target="_blank">WorksheetLine/InventQualityOrderLine</a>|
|[CertificateOfAnalysisReport](#CertificateOfAnalysisReport)||<a href="InventQualityOrderLine.md" target="_blank">WorksheetLine/InventQualityOrderLine</a>|
|[IncludeResults](#IncludeResults)||<a href="InventQualityOrderLine.md" target="_blank">WorksheetLine/InventQualityOrderLine</a>|
|[LowerLimit](#LowerLimit)||<a href="InventQualityOrderLine.md" target="_blank">WorksheetLine/InventQualityOrderLine</a>|
|[LowerTolerance](#LowerTolerance)||<a href="InventQualityOrderLine.md" target="_blank">WorksheetLine/InventQualityOrderLine</a>|
|[PdsAttribValue](#PdsAttribValue)||<a href="InventQualityOrderLine.md" target="_blank">WorksheetLine/InventQualityOrderLine</a>|
|[PdsBatchAttribId](#PdsBatchAttribId)||<a href="InventQualityOrderLine.md" target="_blank">WorksheetLine/InventQualityOrderLine</a>|
|[PdsBatchAttribOverride](#PdsBatchAttribOverride)||<a href="InventQualityOrderLine.md" target="_blank">WorksheetLine/InventQualityOrderLine</a>|
|[PdsCWTestResultQuantity](#PdsCWTestResultQuantity)||<a href="InventQualityOrderLine.md" target="_blank">WorksheetLine/InventQualityOrderLine</a>|
|[PdsOrderLineResult](#PdsOrderLineResult)||<a href="InventQualityOrderLine.md" target="_blank">WorksheetLine/InventQualityOrderLine</a>|
|[PdsUpdateBatchAttributes](#PdsUpdateBatchAttributes)||<a href="InventQualityOrderLine.md" target="_blank">WorksheetLine/InventQualityOrderLine</a>|
|[QualityOrderId](#QualityOrderId)||<a href="InventQualityOrderLine.md" target="_blank">WorksheetLine/InventQualityOrderLine</a>|
|[StandardValue](#StandardValue)||<a href="InventQualityOrderLine.md" target="_blank">WorksheetLine/InventQualityOrderLine</a>|
|[TestId](#TestId)||<a href="InventQualityOrderLine.md" target="_blank">WorksheetLine/InventQualityOrderLine</a>|
|[TestInstrumentId](#TestInstrumentId)||<a href="InventQualityOrderLine.md" target="_blank">WorksheetLine/InventQualityOrderLine</a>|
|[TestResult](#TestResult)||<a href="InventQualityOrderLine.md" target="_blank">WorksheetLine/InventQualityOrderLine</a>|
|[TestSequence](#TestSequence)||<a href="InventQualityOrderLine.md" target="_blank">WorksheetLine/InventQualityOrderLine</a>|
|[TestUnitId](#TestUnitId)||<a href="InventQualityOrderLine.md" target="_blank">WorksheetLine/InventQualityOrderLine</a>|
|[UpperLimit](#UpperLimit)||<a href="InventQualityOrderLine.md" target="_blank">WorksheetLine/InventQualityOrderLine</a>|
|[UpperTolerance](#UpperTolerance)||<a href="InventQualityOrderLine.md" target="_blank">WorksheetLine/InventQualityOrderLine</a>|
|[VariableId](#VariableId)||<a href="InventQualityOrderLine.md" target="_blank">WorksheetLine/InventQualityOrderLine</a>|
|[VariableOutcomeIdStandard](#VariableOutcomeIdStandard)||<a href="InventQualityOrderLine.md" target="_blank">WorksheetLine/InventQualityOrderLine</a>|
|[DataAreaId](#DataAreaId)||<a href="InventQualityOrderLine.md" target="_blank">WorksheetLine/InventQualityOrderLine</a>|
|[Relationship_InventQualityOrderTableRelationshipId](#Relationship_InventQualityOrderTableRelationshipId)||<a href="InventQualityOrderLine.md" target="_blank">WorksheetLine/InventQualityOrderLine</a>|
|[Relationship_InventTestInstrumentRelationshipId](#Relationship_InventTestInstrumentRelationshipId)||<a href="InventQualityOrderLine.md" target="_blank">WorksheetLine/InventQualityOrderLine</a>|
|[Relationship_InventTestTableRelationshipId](#Relationship_InventTestTableRelationshipId)||<a href="InventQualityOrderLine.md" target="_blank">WorksheetLine/InventQualityOrderLine</a>|
|[Relationship_InventTestVariableRelationshipId](#Relationship_InventTestVariableRelationshipId)||<a href="InventQualityOrderLine.md" target="_blank">WorksheetLine/InventQualityOrderLine</a>|
|[Relationship_InventTestVariableOutcomeRelationshipId](#Relationship_InventTestVariableOutcomeRelationshipId)||<a href="InventQualityOrderLine.md" target="_blank">WorksheetLine/InventQualityOrderLine</a>|
|[Relationship_PdsBatchAttribRelationshipId](#Relationship_PdsBatchAttribRelationshipId)||<a href="InventQualityOrderLine.md" target="_blank">WorksheetLine/InventQualityOrderLine</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="InventQualityOrderLine.md" target="_blank">WorksheetLine/InventQualityOrderLine</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetLine/InventQualityOrderLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[InventQualityOrderLine/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AcceptableQualityLevel name="AcceptableQualityLevel">AcceptableQualityLevel</a>

First included in: WorksheetLine/InventQualityOrderLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AcceptableQualityLevel attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ActionOnFailure name="ActionOnFailure">ActionOnFailure</a>

First included in: WorksheetLine/InventQualityOrderLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActionOnFailure attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CertificateOfAnalysisReport name="CertificateOfAnalysisReport">CertificateOfAnalysisReport</a>

First included in: WorksheetLine/InventQualityOrderLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CertificateOfAnalysisReport attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#IncludeResults name="IncludeResults">IncludeResults</a>

First included in: WorksheetLine/InventQualityOrderLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Include results</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IncludeResults attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Include results</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#LowerLimit name="LowerLimit">LowerLimit</a>

First included in: WorksheetLine/InventQualityOrderLine (this entity)  

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

First included in: WorksheetLine/InventQualityOrderLine (this entity)  

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

### <a href=#PdsAttribValue name="PdsAttribValue">PdsAttribValue</a>

First included in: WorksheetLine/InventQualityOrderLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Batch attribute value</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PdsAttribValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Batch attribute value</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PdsBatchAttribId name="PdsBatchAttribId">PdsBatchAttribId</a>

First included in: WorksheetLine/InventQualityOrderLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PdsBatchAttribId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PdsBatchAttribOverride name="PdsBatchAttribOverride">PdsBatchAttribOverride</a>

First included in: WorksheetLine/InventQualityOrderLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Override</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PdsBatchAttribOverride attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Override</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#PdsCWTestResultQuantity name="PdsCWTestResultQuantity">PdsCWTestResultQuantity</a>

First included in: WorksheetLine/InventQualityOrderLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PdsCWTestResultQuantity attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PdsOrderLineResult name="PdsOrderLineResult">PdsOrderLineResult</a>

First included in: WorksheetLine/InventQualityOrderLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PdsOrderLineResult attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PdsUpdateBatchAttributes name="PdsUpdateBatchAttributes">PdsUpdateBatchAttributes</a>

First included in: WorksheetLine/InventQualityOrderLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PdsUpdateBatchAttributes attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#QualityOrderId name="QualityOrderId">QualityOrderId</a>

First included in: WorksheetLine/InventQualityOrderLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QualityOrderId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StandardValue name="StandardValue">StandardValue</a>

First included in: WorksheetLine/InventQualityOrderLine (this entity)  

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

First included in: WorksheetLine/InventQualityOrderLine (this entity)  

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

### <a href=#TestInstrumentId name="TestInstrumentId">TestInstrumentId</a>

First included in: WorksheetLine/InventQualityOrderLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TestInstrumentId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TestResult name="TestResult">TestResult</a>

First included in: WorksheetLine/InventQualityOrderLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Include in result</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TestResult attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Include in result</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#TestSequence name="TestSequence">TestSequence</a>

First included in: WorksheetLine/InventQualityOrderLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TestSequence attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TestUnitId name="TestUnitId">TestUnitId</a>

First included in: WorksheetLine/InventQualityOrderLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TestUnitId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UpperLimit name="UpperLimit">UpperLimit</a>

First included in: WorksheetLine/InventQualityOrderLine (this entity)  

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

First included in: WorksheetLine/InventQualityOrderLine (this entity)  

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

### <a href=#VariableId name="VariableId">VariableId</a>

First included in: WorksheetLine/InventQualityOrderLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VariableId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VariableOutcomeIdStandard name="VariableOutcomeIdStandard">VariableOutcomeIdStandard</a>

First included in: WorksheetLine/InventQualityOrderLine (this entity)  

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

First included in: WorksheetLine/InventQualityOrderLine (this entity)  

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

### <a href=#Relationship_InventQualityOrderTableRelationshipId name="Relationship_InventQualityOrderTableRelationshipId">Relationship_InventQualityOrderTableRelationshipId</a>

First included in: WorksheetLine/InventQualityOrderLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventQualityOrderTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/InventQualityOrderTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/WorksheetHeader/InventQualityOrderTable.cdm.json/InventQualityOrderTable</a></td><td><a href="../WorksheetHeader/InventQualityOrderTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventTestInstrumentRelationshipId name="Relationship_InventTestInstrumentRelationshipId">Relationship_InventTestInstrumentRelationshipId</a>

First included in: WorksheetLine/InventQualityOrderLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventTestInstrumentRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/InventTestInstrument.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/InventTestInstrument.cdm.json/InventTestInstrument</a></td><td><a href="../Group/InventTestInstrument.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventTestTableRelationshipId name="Relationship_InventTestTableRelationshipId">Relationship_InventTestTableRelationshipId</a>

First included in: WorksheetLine/InventQualityOrderLine (this entity)  

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

### <a href=#Relationship_InventTestVariableRelationshipId name="Relationship_InventTestVariableRelationshipId">Relationship_InventTestVariableRelationshipId</a>

First included in: WorksheetLine/InventQualityOrderLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventTestVariableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/InventTestVariable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/InventTestVariable.cdm.json/InventTestVariable</a></td><td><a href="../Main/InventTestVariable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventTestVariableOutcomeRelationshipId name="Relationship_InventTestVariableOutcomeRelationshipId">Relationship_InventTestVariableOutcomeRelationshipId</a>

First included in: WorksheetLine/InventQualityOrderLine (this entity)  

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

### <a href=#Relationship_PdsBatchAttribRelationshipId name="Relationship_PdsBatchAttribRelationshipId">Relationship_PdsBatchAttribRelationshipId</a>

First included in: WorksheetLine/InventQualityOrderLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PdsBatchAttribRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/PdsBatchAttrib.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/PdsBatchAttrib.cdm.json/PdsBatchAttrib</a></td><td><a href="../Main/PdsBatchAttrib.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetLine/InventQualityOrderLine (this entity)  

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
