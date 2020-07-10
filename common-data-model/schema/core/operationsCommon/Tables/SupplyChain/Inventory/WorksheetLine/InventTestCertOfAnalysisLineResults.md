---
title: InventTestCertOfAnalysisLineResults in WorksheetLine - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/10/2020
ms.author: nebanfic
---

# Certificate of analysis line results in WorksheetLine(InventTestCertOfAnalysisLineResults)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/Inventory/WorksheetLine/InventTestCertOfAnalysisLineResults.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[InventTestCertOfAnalysisLineResults/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Certificate of analysis line results</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="InventTestCertOfAnalysisLineResults.md" target="_blank">WorksheetLine/InventTestCertOfAnalysisLineResults</a>|
|[InventCertificateOfAnalysisId](#InventCertificateOfAnalysisId)||<a href="InventTestCertOfAnalysisLineResults.md" target="_blank">WorksheetLine/InventTestCertOfAnalysisLineResults</a>|
|[LineNum](#LineNum)||<a href="InventTestCertOfAnalysisLineResults.md" target="_blank">WorksheetLine/InventTestCertOfAnalysisLineResults</a>|
|[TestId](#TestId)||<a href="InventTestCertOfAnalysisLineResults.md" target="_blank">WorksheetLine/InventTestCertOfAnalysisLineResults</a>|
|[TestResult](#TestResult)||<a href="InventTestCertOfAnalysisLineResults.md" target="_blank">WorksheetLine/InventTestCertOfAnalysisLineResults</a>|
|[TestResultQuantity](#TestResultQuantity)||<a href="InventTestCertOfAnalysisLineResults.md" target="_blank">WorksheetLine/InventTestCertOfAnalysisLineResults</a>|
|[TestResultValueOutcome](#TestResultValueOutcome)||<a href="InventTestCertOfAnalysisLineResults.md" target="_blank">WorksheetLine/InventTestCertOfAnalysisLineResults</a>|
|[TestResultValueReal](#TestResultValueReal)||<a href="InventTestCertOfAnalysisLineResults.md" target="_blank">WorksheetLine/InventTestCertOfAnalysisLineResults</a>|
|[TestSequence](#TestSequence)||<a href="InventTestCertOfAnalysisLineResults.md" target="_blank">WorksheetLine/InventTestCertOfAnalysisLineResults</a>|
|[DataAreaId](#DataAreaId)||<a href="InventTestCertOfAnalysisLineResults.md" target="_blank">WorksheetLine/InventTestCertOfAnalysisLineResults</a>|
|[Relationship_InventTestCertOfAnalysisLineRelationshipId](#Relationship_InventTestCertOfAnalysisLineRelationshipId)||<a href="InventTestCertOfAnalysisLineResults.md" target="_blank">WorksheetLine/InventTestCertOfAnalysisLineResults</a>|
|[Relationship_InventTestCertOfAnalysisTableRelationshipId](#Relationship_InventTestCertOfAnalysisTableRelationshipId)||<a href="InventTestCertOfAnalysisLineResults.md" target="_blank">WorksheetLine/InventTestCertOfAnalysisLineResults</a>|
|[Relationship_InventTestTableRelationshipId](#Relationship_InventTestTableRelationshipId)||<a href="InventTestCertOfAnalysisLineResults.md" target="_blank">WorksheetLine/InventTestCertOfAnalysisLineResults</a>|
|[Relationship_InventTestVariableOutcomeRelationshipId](#Relationship_InventTestVariableOutcomeRelationshipId)||<a href="InventTestCertOfAnalysisLineResults.md" target="_blank">WorksheetLine/InventTestCertOfAnalysisLineResults</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="InventTestCertOfAnalysisLineResults.md" target="_blank">WorksheetLine/InventTestCertOfAnalysisLineResults</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetLine/InventTestCertOfAnalysisLineResults (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[InventTestCertOfAnalysisLineResults/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#InventCertificateOfAnalysisId name="InventCertificateOfAnalysisId">InventCertificateOfAnalysisId</a>

First included in: WorksheetLine/InventTestCertOfAnalysisLineResults (this entity)  

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

### <a href=#LineNum name="LineNum">LineNum</a>

First included in: WorksheetLine/InventTestCertOfAnalysisLineResults (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNum attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TestId name="TestId">TestId</a>

First included in: WorksheetLine/InventTestCertOfAnalysisLineResults (this entity)  

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

First included in: WorksheetLine/InventTestCertOfAnalysisLineResults (this entity)  

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

### <a href=#TestResultQuantity name="TestResultQuantity">TestResultQuantity</a>

First included in: WorksheetLine/InventTestCertOfAnalysisLineResults (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TestResultQuantity attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TestResultValueOutcome name="TestResultValueOutcome">TestResultValueOutcome</a>

First included in: WorksheetLine/InventTestCertOfAnalysisLineResults (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Outcome</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TestResultValueOutcome attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Outcome</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TestResultValueReal name="TestResultValueReal">TestResultValueReal</a>

First included in: WorksheetLine/InventTestCertOfAnalysisLineResults (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TestResultValueReal attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TestSequence name="TestSequence">TestSequence</a>

First included in: WorksheetLine/InventTestCertOfAnalysisLineResults (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TestSequence attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetLine/InventTestCertOfAnalysisLineResults (this entity)  

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

### <a href=#Relationship_InventTestCertOfAnalysisLineRelationshipId name="Relationship_InventTestCertOfAnalysisLineRelationshipId">Relationship_InventTestCertOfAnalysisLineRelationshipId</a>

First included in: WorksheetLine/InventTestCertOfAnalysisLineResults (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventTestCertOfAnalysisLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="InventTestCertOfAnalysisLine.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/WorksheetLine/InventTestCertOfAnalysisLine.cdm.json/InventTestCertOfAnalysisLine</a></td><td><a href="InventTestCertOfAnalysisLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventTestCertOfAnalysisTableRelationshipId name="Relationship_InventTestCertOfAnalysisTableRelationshipId">Relationship_InventTestCertOfAnalysisTableRelationshipId</a>

First included in: WorksheetLine/InventTestCertOfAnalysisLineResults (this entity)  

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

First included in: WorksheetLine/InventTestCertOfAnalysisLineResults (this entity)  

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

First included in: WorksheetLine/InventTestCertOfAnalysisLineResults (this entity)  

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

First included in: WorksheetLine/InventTestCertOfAnalysisLineResults (this entity)  

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
