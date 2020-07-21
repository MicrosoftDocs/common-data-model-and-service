---
title: LedgerRRGEPropertyVersions_W in WorksheetLine - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/21/2020
ms.author: nebanfic
---

# Requisites in WorksheetLine(LedgerRRGEPropertyVersions_W)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Ledger/WorksheetLine/LedgerRRGEPropertyVersions_W.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[LedgerRRGEPropertyVersions_W/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Requisites</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="LedgerRRGEPropertyVersions_W.md" target="_blank">WorksheetLine/LedgerRRGEPropertyVersions_W</a>|
|[CompareRefRecId](#CompareRefRecId)||<a href="LedgerRRGEPropertyVersions_W.md" target="_blank">WorksheetLine/LedgerRRGEPropertyVersions_W</a>|
|[CompareValue](#CompareValue)||<a href="LedgerRRGEPropertyVersions_W.md" target="_blank">WorksheetLine/LedgerRRGEPropertyVersions_W</a>|
|[Description](#Description)||<a href="LedgerRRGEPropertyVersions_W.md" target="_blank">WorksheetLine/LedgerRRGEPropertyVersions_W</a>|
|[DescriptionError](#DescriptionError)||<a href="LedgerRRGEPropertyVersions_W.md" target="_blank">WorksheetLine/LedgerRRGEPropertyVersions_W</a>|
|[Dynamic](#Dynamic)||<a href="LedgerRRGEPropertyVersions_W.md" target="_blank">WorksheetLine/LedgerRRGEPropertyVersions_W</a>|
|[DynamicSectionId](#DynamicSectionId)||<a href="LedgerRRGEPropertyVersions_W.md" target="_blank">WorksheetLine/LedgerRRGEPropertyVersions_W</a>|
|[ExcelSheet](#ExcelSheet)||<a href="LedgerRRGEPropertyVersions_W.md" target="_blank">WorksheetLine/LedgerRRGEPropertyVersions_W</a>|
|[LedgerRRGEDocuments_W](#LedgerRRGEDocuments_W)||<a href="LedgerRRGEPropertyVersions_W.md" target="_blank">WorksheetLine/LedgerRRGEPropertyVersions_W</a>|
|[LedgerRRGETemplates_W](#LedgerRRGETemplates_W)||<a href="LedgerRRGEPropertyVersions_W.md" target="_blank">WorksheetLine/LedgerRRGEPropertyVersions_W</a>|
|[LineNum](#LineNum)||<a href="LedgerRRGEPropertyVersions_W.md" target="_blank">WorksheetLine/LedgerRRGEPropertyVersions_W</a>|
|[ParentRefRecId](#ParentRefRecId)||<a href="LedgerRRGEPropertyVersions_W.md" target="_blank">WorksheetLine/LedgerRRGEPropertyVersions_W</a>|
|[ParentSectionId](#ParentSectionId)||<a href="LedgerRRGEPropertyVersions_W.md" target="_blank">WorksheetLine/LedgerRRGEPropertyVersions_W</a>|
|[PropertyId](#PropertyId)||<a href="LedgerRRGEPropertyVersions_W.md" target="_blank">WorksheetLine/LedgerRRGEPropertyVersions_W</a>|
|[PropertyRefRecId](#PropertyRefRecId)||<a href="LedgerRRGEPropertyVersions_W.md" target="_blank">WorksheetLine/LedgerRRGEPropertyVersions_W</a>|
|[PropertyType](#PropertyType)||<a href="LedgerRRGEPropertyVersions_W.md" target="_blank">WorksheetLine/LedgerRRGEPropertyVersions_W</a>|
|[SectionId](#SectionId)||<a href="LedgerRRGEPropertyVersions_W.md" target="_blank">WorksheetLine/LedgerRRGEPropertyVersions_W</a>|
|[SectionRefRecId](#SectionRefRecId)||<a href="LedgerRRGEPropertyVersions_W.md" target="_blank">WorksheetLine/LedgerRRGEPropertyVersions_W</a>|
|[Value](#Value)||<a href="LedgerRRGEPropertyVersions_W.md" target="_blank">WorksheetLine/LedgerRRGEPropertyVersions_W</a>|
|[VersionRefRecId](#VersionRefRecId)||<a href="LedgerRRGEPropertyVersions_W.md" target="_blank">WorksheetLine/LedgerRRGEPropertyVersions_W</a>|
|[DataAreaId](#DataAreaId)||<a href="LedgerRRGEPropertyVersions_W.md" target="_blank">WorksheetLine/LedgerRRGEPropertyVersions_W</a>|
|[Relationship_LedgerRRGEDocuments_WRelationshipId](#Relationship_LedgerRRGEDocuments_WRelationshipId)||<a href="LedgerRRGEPropertyVersions_W.md" target="_blank">WorksheetLine/LedgerRRGEPropertyVersions_W</a>|
|[Relationship_LedgerRRGEDocumentVersions_WRelationshipId](#Relationship_LedgerRRGEDocumentVersions_WRelationshipId)||<a href="LedgerRRGEPropertyVersions_W.md" target="_blank">WorksheetLine/LedgerRRGEPropertyVersions_W</a>|
|[Relationship_LedgerRRGEProperties_WRelationshipId](#Relationship_LedgerRRGEProperties_WRelationshipId)||<a href="LedgerRRGEPropertyVersions_W.md" target="_blank">WorksheetLine/LedgerRRGEPropertyVersions_W</a>|
|[Relationship_LedgerRRGESectionProperties_WRelationshipId](#Relationship_LedgerRRGESectionProperties_WRelationshipId)||<a href="LedgerRRGEPropertyVersions_W.md" target="_blank">WorksheetLine/LedgerRRGEPropertyVersions_W</a>|
|[Relationship_LedgerRRGETemplates_WRelationshipId](#Relationship_LedgerRRGETemplates_WRelationshipId)||<a href="LedgerRRGEPropertyVersions_W.md" target="_blank">WorksheetLine/LedgerRRGEPropertyVersions_W</a>|
|[Relationship_LedgerRRGETemplateSections_WRelationshipId](#Relationship_LedgerRRGETemplateSections_WRelationshipId)||<a href="LedgerRRGEPropertyVersions_W.md" target="_blank">WorksheetLine/LedgerRRGEPropertyVersions_W</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="LedgerRRGEPropertyVersions_W.md" target="_blank">WorksheetLine/LedgerRRGEPropertyVersions_W</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetLine/LedgerRRGEPropertyVersions_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[LedgerRRGEPropertyVersions_W/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CompareRefRecId name="CompareRefRecId">CompareRefRecId</a>

First included in: WorksheetLine/LedgerRRGEPropertyVersions_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompareRefRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CompareValue name="CompareValue">CompareValue</a>

First included in: WorksheetLine/LedgerRRGEPropertyVersions_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Compare</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompareValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Compare</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: WorksheetLine/LedgerRRGEPropertyVersions_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Description</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Description</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DescriptionError name="DescriptionError">DescriptionError</a>

First included in: WorksheetLine/LedgerRRGEPropertyVersions_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DescriptionError attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Dynamic name="Dynamic">Dynamic</a>

First included in: WorksheetLine/LedgerRRGEPropertyVersions_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Dynamic attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DynamicSectionId name="DynamicSectionId">DynamicSectionId</a>

First included in: WorksheetLine/LedgerRRGEPropertyVersions_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DynamicSectionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExcelSheet name="ExcelSheet">ExcelSheet</a>

First included in: WorksheetLine/LedgerRRGEPropertyVersions_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExcelSheet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerRRGEDocuments_W name="LedgerRRGEDocuments_W">LedgerRRGEDocuments_W</a>

First included in: WorksheetLine/LedgerRRGEPropertyVersions_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerRRGEDocuments_W attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LedgerRRGETemplates_W name="LedgerRRGETemplates_W">LedgerRRGETemplates_W</a>

First included in: WorksheetLine/LedgerRRGEPropertyVersions_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerRRGETemplates_W attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LineNum name="LineNum">LineNum</a>

First included in: WorksheetLine/LedgerRRGEPropertyVersions_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNum attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ParentRefRecId name="ParentRefRecId">ParentRefRecId</a>

First included in: WorksheetLine/LedgerRRGEPropertyVersions_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParentRefRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ParentSectionId name="ParentSectionId">ParentSectionId</a>

First included in: WorksheetLine/LedgerRRGEPropertyVersions_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParentSectionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PropertyId name="PropertyId">PropertyId</a>

First included in: WorksheetLine/LedgerRRGEPropertyVersions_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PropertyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PropertyRefRecId name="PropertyRefRecId">PropertyRefRecId</a>

First included in: WorksheetLine/LedgerRRGEPropertyVersions_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PropertyRefRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PropertyType name="PropertyType">PropertyType</a>

First included in: WorksheetLine/LedgerRRGEPropertyVersions_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PropertyType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#SectionId name="SectionId">SectionId</a>

First included in: WorksheetLine/LedgerRRGEPropertyVersions_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SectionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SectionRefRecId name="SectionRefRecId">SectionRefRecId</a>

First included in: WorksheetLine/LedgerRRGEPropertyVersions_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SectionRefRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Value name="Value">Value</a>

First included in: WorksheetLine/LedgerRRGEPropertyVersions_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Value attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VersionRefRecId name="VersionRefRecId">VersionRefRecId</a>

First included in: WorksheetLine/LedgerRRGEPropertyVersions_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VersionRefRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetLine/LedgerRRGEPropertyVersions_W (this entity)  

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

### <a href=#Relationship_LedgerRRGEDocuments_WRelationshipId name="Relationship_LedgerRRGEDocuments_WRelationshipId">Relationship_LedgerRRGEDocuments_WRelationshipId</a>

First included in: WorksheetLine/LedgerRRGEPropertyVersions_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerRRGEDocuments_WRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/LedgerRRGEDocuments_W.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/LedgerRRGEDocuments_W.cdm.json/LedgerRRGEDocuments_W</a></td><td><a href="../Main/LedgerRRGEDocuments_W.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerRRGEDocumentVersions_WRelationshipId name="Relationship_LedgerRRGEDocumentVersions_WRelationshipId">Relationship_LedgerRRGEDocumentVersions_WRelationshipId</a>

First included in: WorksheetLine/LedgerRRGEPropertyVersions_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerRRGEDocumentVersions_WRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/LedgerRRGEDocumentVersions_W.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Miscellaneous/LedgerRRGEDocumentVersions_W.cdm.json/LedgerRRGEDocumentVersions_W</a></td><td><a href="../Miscellaneous/LedgerRRGEDocumentVersions_W.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerRRGEProperties_WRelationshipId name="Relationship_LedgerRRGEProperties_WRelationshipId">Relationship_LedgerRRGEProperties_WRelationshipId</a>

First included in: WorksheetLine/LedgerRRGEPropertyVersions_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerRRGEProperties_WRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/LedgerRRGEProperties_W.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Group/LedgerRRGEProperties_W.cdm.json/LedgerRRGEProperties_W</a></td><td><a href="../Group/LedgerRRGEProperties_W.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerRRGESectionProperties_WRelationshipId name="Relationship_LedgerRRGESectionProperties_WRelationshipId">Relationship_LedgerRRGESectionProperties_WRelationshipId</a>

First included in: WorksheetLine/LedgerRRGEPropertyVersions_W (this entity)  

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

### <a href=#Relationship_LedgerRRGETemplates_WRelationshipId name="Relationship_LedgerRRGETemplates_WRelationshipId">Relationship_LedgerRRGETemplates_WRelationshipId</a>

First included in: WorksheetLine/LedgerRRGEPropertyVersions_W (this entity)  

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

### <a href=#Relationship_LedgerRRGETemplateSections_WRelationshipId name="Relationship_LedgerRRGETemplateSections_WRelationshipId">Relationship_LedgerRRGETemplateSections_WRelationshipId</a>

First included in: WorksheetLine/LedgerRRGEPropertyVersions_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerRRGETemplateSections_WRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/LedgerRRGETemplateSections_W.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Miscellaneous/LedgerRRGETemplateSections_W.cdm.json/LedgerRRGETemplateSections_W</a></td><td><a href="../Miscellaneous/LedgerRRGETemplateSections_W.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetLine/LedgerRRGEPropertyVersions_W (this entity)  

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
