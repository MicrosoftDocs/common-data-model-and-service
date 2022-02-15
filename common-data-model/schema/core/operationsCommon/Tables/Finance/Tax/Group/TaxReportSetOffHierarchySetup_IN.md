---
title: TaxReportSetOffHierarchySetup_IN in Group - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Setoff hierarchy profile in Group(TaxReportSetOffHierarchySetup_IN)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Tax/Group/TaxReportSetOffHierarchySetup_IN.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxReportSetOffHierarchySetup_IN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Setoff hierarchy profile</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="TaxReportSetOffHierarchySetup_IN.md" target="_blank">Group/TaxReportSetOffHierarchySetup_IN</a>|
|[EffectiveDate](#EffectiveDate)||<a href="TaxReportSetOffHierarchySetup_IN.md" target="_blank">Group/TaxReportSetOffHierarchySetup_IN</a>|
|[IsDraft](#IsDraft)||<a href="TaxReportSetOffHierarchySetup_IN.md" target="_blank">Group/TaxReportSetOffHierarchySetup_IN</a>|
|[TaxReportHierarchyVersion](#TaxReportHierarchyVersion)||<a href="TaxReportSetOffHierarchySetup_IN.md" target="_blank">Group/TaxReportSetOffHierarchySetup_IN</a>|
|[TaxReportSetOffHrchySetupHistory](#TaxReportSetOffHrchySetupHistory)||<a href="TaxReportSetOffHierarchySetup_IN.md" target="_blank">Group/TaxReportSetOffHierarchySetup_IN</a>|
|[HierarchClassId](#HierarchClassId)||<a href="TaxReportSetOffHierarchySetup_IN.md" target="_blank">Group/TaxReportSetOffHierarchySetup_IN</a>|
|[DataAreaId](#DataAreaId)||<a href="TaxReportSetOffHierarchySetup_IN.md" target="_blank">Group/TaxReportSetOffHierarchySetup_IN</a>|
|[Relationship_TaxReportHierarchyVersion_INRelationshipId](#Relationship_TaxReportHierarchyVersion_INRelationshipId)||<a href="TaxReportSetOffHierarchySetup_IN.md" target="_blank">Group/TaxReportSetOffHierarchySetup_IN</a>|
|[Relationship_TaxReportSetOffHrchySetupHistory_INRelationshipId](#Relationship_TaxReportSetOffHrchySetupHistory_INRelationshipId)||<a href="TaxReportSetOffHierarchySetup_IN.md" target="_blank">Group/TaxReportSetOffHierarchySetup_IN</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="TaxReportSetOffHierarchySetup_IN.md" target="_blank">Group/TaxReportSetOffHierarchySetup_IN</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Group/TaxReportSetOffHierarchySetup_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxReportSetOffHierarchySetup_IN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#EffectiveDate name="EffectiveDate">EffectiveDate</a>

First included in: Group/TaxReportSetOffHierarchySetup_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Effective date</td></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EffectiveDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Effective date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.date**  
</details>

### <a href=#IsDraft name="IsDraft">IsDraft</a>

First included in: Group/TaxReportSetOffHierarchySetup_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDraft attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TaxReportHierarchyVersion name="TaxReportHierarchyVersion">TaxReportHierarchyVersion</a>

First included in: Group/TaxReportSetOffHierarchySetup_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxReportHierarchyVersion attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxReportSetOffHrchySetupHistory name="TaxReportSetOffHrchySetupHistory">TaxReportSetOffHrchySetupHistory</a>

First included in: Group/TaxReportSetOffHierarchySetup_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxReportSetOffHrchySetupHistory attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#HierarchClassId name="HierarchClassId">HierarchClassId</a>

First included in: Group/TaxReportSetOffHierarchySetup_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HierarchClassId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Group/TaxReportSetOffHierarchySetup_IN (this entity)  

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

### <a href=#Relationship_TaxReportHierarchyVersion_INRelationshipId name="Relationship_TaxReportHierarchyVersion_INRelationshipId">Relationship_TaxReportHierarchyVersion_INRelationshipId</a>

First included in: Group/TaxReportSetOffHierarchySetup_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxReportHierarchyVersion_INRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TaxReportHierarchyVersion_IN.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxReportHierarchyVersion_IN.cdm.json/TaxReportHierarchyVersion_IN</a></td><td><a href="TaxReportHierarchyVersion_IN.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxReportSetOffHrchySetupHistory_INRelationshipId name="Relationship_TaxReportSetOffHrchySetupHistory_INRelationshipId">Relationship_TaxReportSetOffHrchySetupHistory_INRelationshipId</a>

First included in: Group/TaxReportSetOffHierarchySetup_IN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxReportSetOffHrchySetupHistory_INRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/TaxReportSetOffHrchySetupHistory_IN.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Miscellaneous/TaxReportSetOffHrchySetupHistory_IN.cdm.json/TaxReportSetOffHrchySetupHistory_IN</a></td><td><a href="../Miscellaneous/TaxReportSetOffHrchySetupHistory_IN.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Group/TaxReportSetOffHierarchySetup_IN (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
