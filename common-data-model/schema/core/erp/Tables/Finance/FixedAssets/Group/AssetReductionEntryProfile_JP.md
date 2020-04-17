---
title: AssetReductionEntryProfile_JP - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# AssetReductionEntryProfile_JP

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Finance/FixedAssets/Group/AssetReductionEntryProfile_JP.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[AssetReductionEntryProfile_JP/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="AssetReductionEntryProfile_JP.md" target="_blank">Group/AssetReductionEntryProfile_JP</a>|
|[AllocationConvention](#AllocationConvention)||<a href="AssetReductionEntryProfile_JP.md" target="_blank">Group/AssetReductionEntryProfile_JP</a>|
|[AssetDocumentTable_JP](#AssetDocumentTable_JP)||<a href="AssetReductionEntryProfile_JP.md" target="_blank">Group/AssetReductionEntryProfile_JP</a>|
|[GrantReason](#GrantReason)||<a href="AssetReductionEntryProfile_JP.md" target="_blank">Group/AssetReductionEntryProfile_JP</a>|
|[MaxAmt](#MaxAmt)||<a href="AssetReductionEntryProfile_JP.md" target="_blank">Group/AssetReductionEntryProfile_JP</a>|
|[MaxPer](#MaxPer)||<a href="AssetReductionEntryProfile_JP.md" target="_blank">Group/AssetReductionEntryProfile_JP</a>|
|[Method](#Method)||<a href="AssetReductionEntryProfile_JP.md" target="_blank">Group/AssetReductionEntryProfile_JP</a>|
|[Profile](#Profile)||<a href="AssetReductionEntryProfile_JP.md" target="_blank">Group/AssetReductionEntryProfile_JP</a>|
|[RepaymentType](#RepaymentType)||<a href="AssetReductionEntryProfile_JP.md" target="_blank">Group/AssetReductionEntryProfile_JP</a>|
|[RetentionPeriodAmt](#RetentionPeriodAmt)||<a href="AssetReductionEntryProfile_JP.md" target="_blank">Group/AssetReductionEntryProfile_JP</a>|
|[RetentionPeriodMeasure](#RetentionPeriodMeasure)||<a href="AssetReductionEntryProfile_JP.md" target="_blank">Group/AssetReductionEntryProfile_JP</a>|
|[RetentionStartFrom](#RetentionStartFrom)||<a href="AssetReductionEntryProfile_JP.md" target="_blank">Group/AssetReductionEntryProfile_JP</a>|
|[ValidFrom](#ValidFrom)||<a href="AssetReductionEntryProfile_JP.md" target="_blank">Group/AssetReductionEntryProfile_JP</a>|
|[ValidTo](#ValidTo)||<a href="AssetReductionEntryProfile_JP.md" target="_blank">Group/AssetReductionEntryProfile_JP</a>|
|[DataAreaId](#DataAreaId)||<a href="AssetReductionEntryProfile_JP.md" target="_blank">Group/AssetReductionEntryProfile_JP</a>|
|[Relationship_AssetDocumentTable_JPRelationshipId](#Relationship_AssetDocumentTable_JPRelationshipId)||<a href="AssetReductionEntryProfile_JP.md" target="_blank">Group/AssetReductionEntryProfile_JP</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="AssetReductionEntryProfile_JP.md" target="_blank">Group/AssetReductionEntryProfile_JP</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Group/AssetReductionEntryProfile_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[AssetReductionEntryProfile_JP/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AllocationConvention name="AllocationConvention">AllocationConvention</a>

First included in: Group/AssetReductionEntryProfile_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllocationConvention attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AssetDocumentTable_JP name="AssetDocumentTable_JP">AssetDocumentTable_JP</a>

First included in: Group/AssetReductionEntryProfile_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetDocumentTable_JP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#GrantReason name="GrantReason">GrantReason</a>

First included in: Group/AssetReductionEntryProfile_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GrantReason attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaxAmt name="MaxAmt">MaxAmt</a>

First included in: Group/AssetReductionEntryProfile_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxAmt attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#MaxPer name="MaxPer">MaxPer</a>

First included in: Group/AssetReductionEntryProfile_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxPer attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Method name="Method">Method</a>

First included in: Group/AssetReductionEntryProfile_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Method attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Profile name="Profile">Profile</a>

First included in: Group/AssetReductionEntryProfile_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Profile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RepaymentType name="RepaymentType">RepaymentType</a>

First included in: Group/AssetReductionEntryProfile_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RepaymentType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RetentionPeriodAmt name="RetentionPeriodAmt">RetentionPeriodAmt</a>

First included in: Group/AssetReductionEntryProfile_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetentionPeriodAmt attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RetentionPeriodMeasure name="RetentionPeriodMeasure">RetentionPeriodMeasure</a>

First included in: Group/AssetReductionEntryProfile_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetentionPeriodMeasure attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RetentionStartFrom name="RetentionStartFrom">RetentionStartFrom</a>

First included in: Group/AssetReductionEntryProfile_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetentionStartFrom attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ValidFrom name="ValidFrom">ValidFrom</a>

First included in: Group/AssetReductionEntryProfile_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidFrom attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#ValidTo name="ValidTo">ValidTo</a>

First included in: Group/AssetReductionEntryProfile_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidTo attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Group/AssetReductionEntryProfile_JP (this entity)  

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

### <a href=#Relationship_AssetDocumentTable_JPRelationshipId name="Relationship_AssetDocumentTable_JPRelationshipId">Relationship_AssetDocumentTable_JPRelationshipId</a>

First included in: Group/AssetReductionEntryProfile_JP (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetDocumentTable_JPRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/AssetDocumentTable_JP.md" target="_blank">/core/erp/Tables/Finance/FixedAssets/WorksheetHeader/AssetDocumentTable_JP.cdm.json/AssetDocumentTable_JP</a></td><td><a href="../WorksheetHeader/AssetDocumentTable_JP.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Group/AssetReductionEntryProfile_JP (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Ledger/Main/CompanyInfo.md" target="_blank">/core/erp/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
