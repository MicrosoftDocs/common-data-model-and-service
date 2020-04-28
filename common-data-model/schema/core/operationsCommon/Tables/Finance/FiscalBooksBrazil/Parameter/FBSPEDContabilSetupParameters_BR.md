---
title: FBSPEDContabilSetupParameters_BR - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# SPED ECD setup parameters

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Parameter/FBSPEDContabilSetupParameters_BR.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FBSPEDContabilSetupParameters_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>SPED ECD setup parameters</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="FBSPEDContabilSetupParameters_BR.md" target="_blank">Parameter/FBSPEDContabilSetupParameters_BR</a>|
|[AuditorCVMNumber](#AuditorCVMNumber)||<a href="FBSPEDContabilSetupParameters_BR.md" target="_blank">Parameter/FBSPEDContabilSetupParameters_BR</a>|
|[AuditorName](#AuditorName)||<a href="FBSPEDContabilSetupParameters_BR.md" target="_blank">Parameter/FBSPEDContabilSetupParameters_BR</a>|
|[DataArea](#DataArea)||<a href="FBSPEDContabilSetupParameters_BR.md" target="_blank">Parameter/FBSPEDContabilSetupParameters_BR</a>|
|[DimensionSetName](#DimensionSetName)||<a href="FBSPEDContabilSetupParameters_BR.md" target="_blank">Parameter/FBSPEDContabilSetupParameters_BR</a>|
|[FiscalOrganization](#FiscalOrganization)||<a href="FBSPEDContabilSetupParameters_BR.md" target="_blank">Parameter/FBSPEDContabilSetupParameters_BR</a>|
|[IsLargeCompany](#IsLargeCompany)||<a href="FBSPEDContabilSetupParameters_BR.md" target="_blank">Parameter/FBSPEDContabilSetupParameters_BR</a>|
|[LayoutVersion](#LayoutVersion)||<a href="FBSPEDContabilSetupParameters_BR.md" target="_blank">Parameter/FBSPEDContabilSetupParameters_BR</a>|
|[OpeningPeriodSituation](#OpeningPeriodSituation)||<a href="FBSPEDContabilSetupParameters_BR.md" target="_blank">Parameter/FBSPEDContabilSetupParameters_BR</a>|
|[SituationType](#SituationType)||<a href="FBSPEDContabilSetupParameters_BR.md" target="_blank">Parameter/FBSPEDContabilSetupParameters_BR</a>|
|[Type](#Type)||<a href="FBSPEDContabilSetupParameters_BR.md" target="_blank">Parameter/FBSPEDContabilSetupParameters_BR</a>|
|[Relationship_FiscalOrganization_BRRelationshipId](#Relationship_FiscalOrganization_BRRelationshipId)||<a href="FBSPEDContabilSetupParameters_BR.md" target="_blank">Parameter/FBSPEDContabilSetupParameters_BR</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Parameter/FBSPEDContabilSetupParameters_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FBSPEDContabilSetupParameters_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AuditorCVMNumber name="AuditorCVMNumber">AuditorCVMNumber</a>

First included in: Parameter/FBSPEDContabilSetupParameters_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AuditorCVMNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AuditorName name="AuditorName">AuditorName</a>

First included in: Parameter/FBSPEDContabilSetupParameters_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AuditorName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataArea name="DataArea">DataArea</a>

First included in: Parameter/FBSPEDContabilSetupParameters_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataArea attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DimensionSetName name="DimensionSetName">DimensionSetName</a>

First included in: Parameter/FBSPEDContabilSetupParameters_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionSetName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalOrganization name="FiscalOrganization">FiscalOrganization</a>

First included in: Parameter/FBSPEDContabilSetupParameters_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalOrganization attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#IsLargeCompany name="IsLargeCompany">IsLargeCompany</a>

First included in: Parameter/FBSPEDContabilSetupParameters_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsLargeCompany attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LayoutVersion name="LayoutVersion">LayoutVersion</a>

First included in: Parameter/FBSPEDContabilSetupParameters_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LayoutVersion attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#OpeningPeriodSituation name="OpeningPeriodSituation">OpeningPeriodSituation</a>

First included in: Parameter/FBSPEDContabilSetupParameters_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OpeningPeriodSituation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SituationType name="SituationType">SituationType</a>

First included in: Parameter/FBSPEDContabilSetupParameters_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SituationType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Type name="Type">Type</a>

First included in: Parameter/FBSPEDContabilSetupParameters_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Type attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#Relationship_FiscalOrganization_BRRelationshipId name="Relationship_FiscalOrganization_BRRelationshipId">Relationship_FiscalOrganization_BRRelationshipId</a>

First included in: Parameter/FBSPEDContabilSetupParameters_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FiscalOrganization_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/FiscalOrganization_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Main/FiscalOrganization_BR.cdm.json/FiscalOrganization_BR</a></td><td><a href="../Main/FiscalOrganization_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
