---
title: TSTimesheetLineEntity in ProductionControl - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Timesheet Lines in ProductionControl(TSTimesheetLineEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductionControl/TSTimesheetLineEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Timesheet Lines</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[Resource](#Resource)||<a href="TSTimesheetLineEntity.md" target="_blank">ProductionControl/TSTimesheetLineEntity</a>|
|[CategoryId](#CategoryId)||<a href="TSTimesheetLineEntity.md" target="_blank">ProductionControl/TSTimesheetLineEntity</a>|
|[Dimension](#Dimension)||<a href="TSTimesheetLineEntity.md" target="_blank">ProductionControl/TSTimesheetLineEntity</a>|
|[LineNumber](#LineNumber)||<a href="TSTimesheetLineEntity.md" target="_blank">ProductionControl/TSTimesheetLineEntity</a>|
|[LineProperty](#LineProperty)||<a href="TSTimesheetLineEntity.md" target="_blank">ProductionControl/TSTimesheetLineEntity</a>|
|[ProjectDataArea](#ProjectDataArea)||<a href="TSTimesheetLineEntity.md" target="_blank">ProductionControl/TSTimesheetLineEntity</a>|
|[ProjectId](#ProjectId)||<a href="TSTimesheetLineEntity.md" target="_blank">ProductionControl/TSTimesheetLineEntity</a>|
|[Timesheet](#Timesheet)||<a href="TSTimesheetLineEntity.md" target="_blank">ProductionControl/TSTimesheetLineEntity</a>|
|[TimesheetNumber](#TimesheetNumber)||<a href="TSTimesheetLineEntity.md" target="_blank">ProductionControl/TSTimesheetLineEntity</a>|
|[Favorites](#Favorites)||<a href="TSTimesheetLineEntity.md" target="_blank">ProductionControl/TSTimesheetLineEntity</a>|
|[DimensionDisplayValue](#DimensionDisplayValue)||<a href="TSTimesheetLineEntity.md" target="_blank">ProductionControl/TSTimesheetLineEntity</a>|
|[ActivityNumber](#ActivityNumber)||<a href="TSTimesheetLineEntity.md" target="_blank">ProductionControl/TSTimesheetLineEntity</a>|
|[ProjPeriodTimesheetWeek](#ProjPeriodTimesheetWeek)||<a href="TSTimesheetLineEntity.md" target="_blank">ProductionControl/TSTimesheetLineEntity</a>|
|[TaxGroupId](#TaxGroupId)||<a href="TSTimesheetLineEntity.md" target="_blank">ProductionControl/TSTimesheetLineEntity</a>|
|[TaxItemGroup](#TaxItemGroup)||<a href="TSTimesheetLineEntity.md" target="_blank">ProductionControl/TSTimesheetLineEntity</a>|
|[ExternalComments](#ExternalComments)||<a href="TSTimesheetLineEntity.md" target="_blank">ProductionControl/TSTimesheetLineEntity</a>|
|[Hours](#Hours)||<a href="TSTimesheetLineEntity.md" target="_blank">ProductionControl/TSTimesheetLineEntity</a>|
|[InternalComments](#InternalComments)||<a href="TSTimesheetLineEntity.md" target="_blank">ProductionControl/TSTimesheetLineEntity</a>|
|[LegalEntity](#LegalEntity)||<a href="TSTimesheetLineEntity.md" target="_blank">ProductionControl/TSTimesheetLineEntity</a>|
|[Relationship_DimensionDimensionSetRelationshipId](#Relationship_DimensionDimensionSetRelationshipId)||<a href="TSTimesheetLineEntity.md" target="_blank">ProductionControl/TSTimesheetLineEntity</a>|
|[BackingTable_TSTimesheetLineRelationshipId](#BackingTable_TSTimesheetLineRelationshipId)||<a href="TSTimesheetLineEntity.md" target="_blank">ProductionControl/TSTimesheetLineEntity</a>|

### <a href=#Resource name="Resource">Resource</a>

First included in: ProductionControl/TSTimesheetLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Resource attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CategoryId name="CategoryId">CategoryId</a>

First included in: ProductionControl/TSTimesheetLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CategoryId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Dimension name="Dimension">Dimension</a>

First included in: ProductionControl/TSTimesheetLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Dimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: ProductionControl/TSTimesheetLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineProperty name="LineProperty">LineProperty</a>

First included in: ProductionControl/TSTimesheetLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineProperty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectDataArea name="ProjectDataArea">ProjectDataArea</a>

First included in: ProductionControl/TSTimesheetLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectDataArea attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectId name="ProjectId">ProjectId</a>

First included in: ProductionControl/TSTimesheetLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Timesheet name="Timesheet">Timesheet</a>

First included in: ProductionControl/TSTimesheetLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Timesheet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimesheetNumber name="TimesheetNumber">TimesheetNumber</a>

First included in: ProductionControl/TSTimesheetLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimesheetNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Favorites name="Favorites">Favorites</a>

First included in: ProductionControl/TSTimesheetLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Favorites attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DimensionDisplayValue name="DimensionDisplayValue">DimensionDisplayValue</a>

First included in: ProductionControl/TSTimesheetLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActivityNumber name="ActivityNumber">ActivityNumber</a>

First included in: ProductionControl/TSTimesheetLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActivityNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjPeriodTimesheetWeek name="ProjPeriodTimesheetWeek">ProjPeriodTimesheetWeek</a>

First included in: ProductionControl/TSTimesheetLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjPeriodTimesheetWeek attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxGroupId name="TaxGroupId">TaxGroupId</a>

First included in: ProductionControl/TSTimesheetLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxItemGroup name="TaxItemGroup">TaxItemGroup</a>

First included in: ProductionControl/TSTimesheetLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxItemGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExternalComments name="ExternalComments">ExternalComments</a>

First included in: ProductionControl/TSTimesheetLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExternalComments attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Hours name="Hours">Hours</a>

First included in: ProductionControl/TSTimesheetLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Hours attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InternalComments name="InternalComments">InternalComments</a>

First included in: ProductionControl/TSTimesheetLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InternalComments attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LegalEntity name="LegalEntity">LegalEntity</a>

First included in: ProductionControl/TSTimesheetLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LegalEntity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DimensionDimensionSetRelationshipId name="Relationship_DimensionDimensionSetRelationshipId">Relationship_DimensionDimensionSetRelationshipId</a>

First included in: ProductionControl/TSTimesheetLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DimensionDimensionSetRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_TSTimesheetLineRelationshipId name="BackingTable_TSTimesheetLineRelationshipId">BackingTable_TSTimesheetLineRelationshipId</a>

First included in: ProductionControl/TSTimesheetLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_TSTimesheetLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/ProfessionalServices/ProjectManagementAndAccounting/Transaction/TSTimesheetLine.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Transaction/TSTimesheetLine.cdm.json/TSTimesheetLine</a></td><td><a href="../../../Tables/ProfessionalServices/ProjectManagementAndAccounting/Transaction/TSTimesheetLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
