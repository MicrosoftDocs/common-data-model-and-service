---
title: LedgerRRGEFormatPeriods_W - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# LedgerRRGEFormatPeriods_W

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Finance/Ledger/Group/LedgerRRGEFormatPeriods_W.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[LedgerRRGEFormatPeriods_W/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="LedgerRRGEFormatPeriods_W.md" target="_blank">Group/LedgerRRGEFormatPeriods_W</a>|
|[ApplyDateEnd](#ApplyDateEnd)||<a href="LedgerRRGEFormatPeriods_W.md" target="_blank">Group/LedgerRRGEFormatPeriods_W</a>|
|[ApplyDateStart](#ApplyDateStart)||<a href="LedgerRRGEFormatPeriods_W.md" target="_blank">Group/LedgerRRGEFormatPeriods_W</a>|
|[CodeKND](#CodeKND)||<a href="LedgerRRGEFormatPeriods_W.md" target="_blank">Group/LedgerRRGEFormatPeriods_W</a>|
|[Comment](#Comment)||<a href="LedgerRRGEFormatPeriods_W.md" target="_blank">Group/LedgerRRGEFormatPeriods_W</a>|
|[FileNameLedgerRRGEProperties_W](#FileNameLedgerRRGEProperties_W)||<a href="LedgerRRGEFormatPeriods_W.md" target="_blank">Group/LedgerRRGEFormatPeriods_W</a>|
|[FileNamePrefix](#FileNamePrefix)||<a href="LedgerRRGEFormatPeriods_W.md" target="_blank">Group/LedgerRRGEFormatPeriods_W</a>|
|[FirstPeriod](#FirstPeriod)||<a href="LedgerRRGEFormatPeriods_W.md" target="_blank">Group/LedgerRRGEFormatPeriods_W</a>|
|[FormatOrderNum](#FormatOrderNum)||<a href="LedgerRRGEFormatPeriods_W.md" target="_blank">Group/LedgerRRGEFormatPeriods_W</a>|
|[FormatRegNumber](#FormatRegNumber)||<a href="LedgerRRGEFormatPeriods_W.md" target="_blank">Group/LedgerRRGEFormatPeriods_W</a>|
|[FormatVersionID](#FormatVersionID)||<a href="LedgerRRGEFormatPeriods_W.md" target="_blank">Group/LedgerRRGEFormatPeriods_W</a>|
|[FormName](#FormName)||<a href="LedgerRRGEFormatPeriods_W.md" target="_blank">Group/LedgerRRGEFormatPeriods_W</a>|
|[FormOrderNum](#FormOrderNum)||<a href="LedgerRRGEFormatPeriods_W.md" target="_blank">Group/LedgerRRGEFormatPeriods_W</a>|
|[LedgerRRGEPropertyLayouts_W](#LedgerRRGEPropertyLayouts_W)||<a href="LedgerRRGEFormatPeriods_W.md" target="_blank">Group/LedgerRRGEFormatPeriods_W</a>|
|[PartNumber](#PartNumber)||<a href="LedgerRRGEFormatPeriods_W.md" target="_blank">Group/LedgerRRGEFormatPeriods_W</a>|
|[VersionNumber](#VersionNumber)||<a href="LedgerRRGEFormatPeriods_W.md" target="_blank">Group/LedgerRRGEFormatPeriods_W</a>|
|[XSDScheme](#XSDScheme)||<a href="LedgerRRGEFormatPeriods_W.md" target="_blank">Group/LedgerRRGEFormatPeriods_W</a>|
|[XSDSource](#XSDSource)||<a href="LedgerRRGEFormatPeriods_W.md" target="_blank">Group/LedgerRRGEFormatPeriods_W</a>|
|[DataAreaId](#DataAreaId)||<a href="LedgerRRGEFormatPeriods_W.md" target="_blank">Group/LedgerRRGEFormatPeriods_W</a>|
|[Relationship_LedgerRRGEProperties_WRelationshipId](#Relationship_LedgerRRGEProperties_WRelationshipId)||<a href="LedgerRRGEFormatPeriods_W.md" target="_blank">Group/LedgerRRGEFormatPeriods_W</a>|
|[Relationship_LedgerRRGEPropertyLayouts_WRelationshipId](#Relationship_LedgerRRGEPropertyLayouts_WRelationshipId)||<a href="LedgerRRGEFormatPeriods_W.md" target="_blank">Group/LedgerRRGEFormatPeriods_W</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="LedgerRRGEFormatPeriods_W.md" target="_blank">Group/LedgerRRGEFormatPeriods_W</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Group/LedgerRRGEFormatPeriods_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[LedgerRRGEFormatPeriods_W/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ApplyDateEnd name="ApplyDateEnd">ApplyDateEnd</a>

First included in: Group/LedgerRRGEFormatPeriods_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ApplyDateEnd attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#ApplyDateStart name="ApplyDateStart">ApplyDateStart</a>

First included in: Group/LedgerRRGEFormatPeriods_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ApplyDateStart attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#CodeKND name="CodeKND">CodeKND</a>

First included in: Group/LedgerRRGEFormatPeriods_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CodeKND attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Comment name="Comment">Comment</a>

First included in: Group/LedgerRRGEFormatPeriods_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Comment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FileNameLedgerRRGEProperties_W name="FileNameLedgerRRGEProperties_W">FileNameLedgerRRGEProperties_W</a>

First included in: Group/LedgerRRGEFormatPeriods_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FileNameLedgerRRGEProperties_W attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FileNamePrefix name="FileNamePrefix">FileNamePrefix</a>

First included in: Group/LedgerRRGEFormatPeriods_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FileNamePrefix attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FirstPeriod name="FirstPeriod">FirstPeriod</a>

First included in: Group/LedgerRRGEFormatPeriods_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FirstPeriod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FormatOrderNum name="FormatOrderNum">FormatOrderNum</a>

First included in: Group/LedgerRRGEFormatPeriods_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormatOrderNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FormatRegNumber name="FormatRegNumber">FormatRegNumber</a>

First included in: Group/LedgerRRGEFormatPeriods_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormatRegNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FormatVersionID name="FormatVersionID">FormatVersionID</a>

First included in: Group/LedgerRRGEFormatPeriods_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormatVersionID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FormName name="FormName">FormName</a>

First included in: Group/LedgerRRGEFormatPeriods_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FormOrderNum name="FormOrderNum">FormOrderNum</a>

First included in: Group/LedgerRRGEFormatPeriods_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormOrderNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerRRGEPropertyLayouts_W name="LedgerRRGEPropertyLayouts_W">LedgerRRGEPropertyLayouts_W</a>

First included in: Group/LedgerRRGEFormatPeriods_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerRRGEPropertyLayouts_W attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PartNumber name="PartNumber">PartNumber</a>

First included in: Group/LedgerRRGEFormatPeriods_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PartNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VersionNumber name="VersionNumber">VersionNumber</a>

First included in: Group/LedgerRRGEFormatPeriods_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VersionNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#XSDScheme name="XSDScheme">XSDScheme</a>

First included in: Group/LedgerRRGEFormatPeriods_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the XSDScheme attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#XSDSource name="XSDSource">XSDSource</a>

First included in: Group/LedgerRRGEFormatPeriods_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the XSDSource attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Group/LedgerRRGEFormatPeriods_W (this entity)  

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

### <a href=#Relationship_LedgerRRGEProperties_WRelationshipId name="Relationship_LedgerRRGEProperties_WRelationshipId">Relationship_LedgerRRGEProperties_WRelationshipId</a>

First included in: Group/LedgerRRGEFormatPeriods_W (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="LedgerRRGEProperties_W.md" target="_blank">/core/erp/Tables/Finance/Ledger/Group/LedgerRRGEProperties_W.cdm.json/LedgerRRGEProperties_W</a></td><td><a href="LedgerRRGEProperties_W.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerRRGEPropertyLayouts_WRelationshipId name="Relationship_LedgerRRGEPropertyLayouts_WRelationshipId">Relationship_LedgerRRGEPropertyLayouts_WRelationshipId</a>

First included in: Group/LedgerRRGEFormatPeriods_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerRRGEPropertyLayouts_WRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="LedgerRRGEPropertyLayouts_W.md" target="_blank">/core/erp/Tables/Finance/Ledger/Group/LedgerRRGEPropertyLayouts_W.cdm.json/LedgerRRGEPropertyLayouts_W</a></td><td><a href="LedgerRRGEPropertyLayouts_W.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Group/LedgerRRGEFormatPeriods_W (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/CompanyInfo.md" target="_blank">/core/erp/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
