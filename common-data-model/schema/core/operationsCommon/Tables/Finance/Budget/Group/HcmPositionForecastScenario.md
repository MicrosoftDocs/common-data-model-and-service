---
title: HcmPositionForecastScenario in Group - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/13/2020
ms.author: nebanfic
---

# Forecast scenario in Group(HcmPositionForecastScenario)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Budget/Group/HcmPositionForecastScenario.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[HcmPositionForecastScenario/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Forecast scenario</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="HcmPositionForecastScenario.md" target="_blank">Group/HcmPositionForecastScenario</a>|
|[ActivationDateTime](#ActivationDateTime)||<a href="HcmPositionForecastScenario.md" target="_blank">Group/HcmPositionForecastScenario</a>|
|[AnniversaryDate](#AnniversaryDate)||<a href="HcmPositionForecastScenario.md" target="_blank">Group/HcmPositionForecastScenario</a>|
|[CompensationGroupDataAreaId](#CompensationGroupDataAreaId)||<a href="HcmPositionForecastScenario.md" target="_blank">Group/HcmPositionForecastScenario</a>|
|[CompensationGroupId](#CompensationGroupId)||<a href="HcmPositionForecastScenario.md" target="_blank">Group/HcmPositionForecastScenario</a>|
|[ForecastScenario](#ForecastScenario)||<a href="HcmPositionForecastScenario.md" target="_blank">Group/HcmPositionForecastScenario</a>|
|[FullTimeEquivalency](#FullTimeEquivalency)||<a href="HcmPositionForecastScenario.md" target="_blank">Group/HcmPositionForecastScenario</a>|
|[LegalEntity](#LegalEntity)||<a href="HcmPositionForecastScenario.md" target="_blank">Group/HcmPositionForecastScenario</a>|
|[NextIncreaseDate](#NextIncreaseDate)||<a href="HcmPositionForecastScenario.md" target="_blank">Group/HcmPositionForecastScenario</a>|
|[PositionForecast](#PositionForecast)||<a href="HcmPositionForecastScenario.md" target="_blank">Group/HcmPositionForecastScenario</a>|
|[PositionForecastCompensationGrid](#PositionForecastCompensationGrid)||<a href="HcmPositionForecastScenario.md" target="_blank">Group/HcmPositionForecastScenario</a>|
|[RetirementDateTime](#RetirementDateTime)||<a href="HcmPositionForecastScenario.md" target="_blank">Group/HcmPositionForecastScenario</a>|
|[VersionDateTime](#VersionDateTime)||<a href="HcmPositionForecastScenario.md" target="_blank">Group/HcmPositionForecastScenario</a>|
|[WorkerName](#WorkerName)||<a href="HcmPositionForecastScenario.md" target="_blank">Group/HcmPositionForecastScenario</a>|
|[HourlyWageRate](#HourlyWageRate)||<a href="HcmPositionForecastScenario.md" target="_blank">Group/HcmPositionForecastScenario</a>|
|[Relationship_CompensationGroupRelationshipId](#Relationship_CompensationGroupRelationshipId)||<a href="HcmPositionForecastScenario.md" target="_blank">Group/HcmPositionForecastScenario</a>|
|[Relationship_ForecastScenarioRelationshipId](#Relationship_ForecastScenarioRelationshipId)||<a href="HcmPositionForecastScenario.md" target="_blank">Group/HcmPositionForecastScenario</a>|
|[Relationship_HcmPositionForecastCompensationGridRelationshipId](#Relationship_HcmPositionForecastCompensationGridRelationshipId)||<a href="HcmPositionForecastScenario.md" target="_blank">Group/HcmPositionForecastScenario</a>|
|[Relationship_LegalEntityRelationshipId](#Relationship_LegalEntityRelationshipId)||<a href="HcmPositionForecastScenario.md" target="_blank">Group/HcmPositionForecastScenario</a>|
|[Relationship_PositionForecastRelationshipId](#Relationship_PositionForecastRelationshipId)||<a href="HcmPositionForecastScenario.md" target="_blank">Group/HcmPositionForecastScenario</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Group/HcmPositionForecastScenario (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[HcmPositionForecastScenario/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ActivationDateTime name="ActivationDateTime">ActivationDateTime</a>

First included in: Group/HcmPositionForecastScenario (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActivationDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#AnniversaryDate name="AnniversaryDate">AnniversaryDate</a>

First included in: Group/HcmPositionForecastScenario (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AnniversaryDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#CompensationGroupDataAreaId name="CompensationGroupDataAreaId">CompensationGroupDataAreaId</a>

First included in: Group/HcmPositionForecastScenario (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompensationGroupDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompensationGroupId name="CompensationGroupId">CompensationGroupId</a>

First included in: Group/HcmPositionForecastScenario (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompensationGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ForecastScenario name="ForecastScenario">ForecastScenario</a>

First included in: Group/HcmPositionForecastScenario (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForecastScenario attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FullTimeEquivalency name="FullTimeEquivalency">FullTimeEquivalency</a>

First included in: Group/HcmPositionForecastScenario (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FullTimeEquivalency attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#LegalEntity name="LegalEntity">LegalEntity</a>

First included in: Group/HcmPositionForecastScenario (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Legal entity</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LegalEntity attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Legal entity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#NextIncreaseDate name="NextIncreaseDate">NextIncreaseDate</a>

First included in: Group/HcmPositionForecastScenario (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NextIncreaseDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#PositionForecast name="PositionForecast">PositionForecast</a>

First included in: Group/HcmPositionForecastScenario (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PositionForecast attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PositionForecastCompensationGrid name="PositionForecastCompensationGrid">PositionForecastCompensationGrid</a>

First included in: Group/HcmPositionForecastScenario (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Compensation level</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PositionForecastCompensationGrid attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Compensation level</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RetirementDateTime name="RetirementDateTime">RetirementDateTime</a>

First included in: Group/HcmPositionForecastScenario (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetirementDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#VersionDateTime name="VersionDateTime">VersionDateTime</a>

First included in: Group/HcmPositionForecastScenario (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VersionDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#WorkerName name="WorkerName">WorkerName</a>

First included in: Group/HcmPositionForecastScenario (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HourlyWageRate name="HourlyWageRate">HourlyWageRate</a>

First included in: Group/HcmPositionForecastScenario (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HourlyWageRate attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Relationship_CompensationGroupRelationshipId name="Relationship_CompensationGroupRelationshipId">Relationship_CompensationGroupRelationshipId</a>

First included in: Group/HcmPositionForecastScenario (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CompensationGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="HcmPositionForecastCompensationGroup.md" target="_blank">/core/operationsCommon/Tables/Finance/Budget/Group/HcmPositionForecastCompensationGroup.cdm.json/HcmPositionForecastCompensationGroup</a></td><td><a href="HcmPositionForecastCompensationGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ForecastScenarioRelationshipId name="Relationship_ForecastScenarioRelationshipId">Relationship_ForecastScenarioRelationshipId</a>

First included in: Group/HcmPositionForecastScenario (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ForecastScenarioRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="HcmForecastScenario.md" target="_blank">/core/operationsCommon/Tables/Finance/Budget/Group/HcmForecastScenario.cdm.json/HcmForecastScenario</a></td><td><a href="HcmForecastScenario.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_HcmPositionForecastCompensationGridRelationshipId name="Relationship_HcmPositionForecastCompensationGridRelationshipId">Relationship_HcmPositionForecastCompensationGridRelationshipId</a>

First included in: Group/HcmPositionForecastScenario (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_HcmPositionForecastCompensationGridRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Reference/HcmPositionForecastCompensationGrid.md" target="_blank">/core/operationsCommon/Tables/Finance/Budget/Reference/HcmPositionForecastCompensationGrid.cdm.json/HcmPositionForecastCompensationGrid</a></td><td><a href="../Reference/HcmPositionForecastCompensationGrid.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LegalEntityRelationshipId name="Relationship_LegalEntityRelationshipId">Relationship_LegalEntityRelationshipId</a>

First included in: Group/HcmPositionForecastScenario (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LegalEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PositionForecastRelationshipId name="Relationship_PositionForecastRelationshipId">Relationship_PositionForecastRelationshipId</a>

First included in: Group/HcmPositionForecastScenario (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PositionForecastRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/HcmPositionForecast.md" target="_blank">/core/operationsCommon/Tables/Finance/Budget/Main/HcmPositionForecast.cdm.json/HcmPositionForecast</a></td><td><a href="../Main/HcmPositionForecast.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
