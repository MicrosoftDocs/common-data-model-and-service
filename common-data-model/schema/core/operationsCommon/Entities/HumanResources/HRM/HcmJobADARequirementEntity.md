---
title: HcmJobADARequirementEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# HcmJobADARequirementEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/HumanResources/HRM/HcmJobADARequirementEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[Job](#Job)||<a href="HcmJobADARequirementEntity.md" target="_blank">HRM/HcmJobADARequirementEntity</a>|
|[JobId](#JobId)||<a href="HcmJobADARequirementEntity.md" target="_blank">HRM/HcmJobADARequirementEntity</a>|
|[AdverseConditions](#AdverseConditions)||<a href="HcmJobADARequirementEntity.md" target="_blank">HRM/HcmJobADARequirementEntity</a>|
|[AtmosphericConditions](#AtmosphericConditions)||<a href="HcmJobADARequirementEntity.md" target="_blank">HRM/HcmJobADARequirementEntity</a>|
|[Balancing](#Balancing)||<a href="HcmJobADARequirementEntity.md" target="_blank">HRM/HcmJobADARequirementEntity</a>|
|[Climbing](#Climbing)||<a href="HcmJobADARequirementEntity.md" target="_blank">HRM/HcmJobADARequirementEntity</a>|
|[CloseQuaters](#CloseQuaters)||<a href="HcmJobADARequirementEntity.md" target="_blank">HRM/HcmJobADARequirementEntity</a>|
|[Crawling](#Crawling)||<a href="HcmJobADARequirementEntity.md" target="_blank">HRM/HcmJobADARequirementEntity</a>|
|[Crouching](#Crouching)||<a href="HcmJobADARequirementEntity.md" target="_blank">HRM/HcmJobADARequirementEntity</a>|
|[EnvironmentBoth](#EnvironmentBoth)||<a href="HcmJobADARequirementEntity.md" target="_blank">HRM/HcmJobADARequirementEntity</a>|
|[EnvironmentCold](#EnvironmentCold)||<a href="HcmJobADARequirementEntity.md" target="_blank">HRM/HcmJobADARequirementEntity</a>|
|[EnvironmentHeat](#EnvironmentHeat)||<a href="HcmJobADARequirementEntity.md" target="_blank">HRM/HcmJobADARequirementEntity</a>|
|[EnvironmentInside](#EnvironmentInside)||<a href="HcmJobADARequirementEntity.md" target="_blank">HRM/HcmJobADARequirementEntity</a>|
|[EnvironmentOutside](#EnvironmentOutside)||<a href="HcmJobADARequirementEntity.md" target="_blank">HRM/HcmJobADARequirementEntity</a>|
|[Feeling](#Feeling)||<a href="HcmJobADARequirementEntity.md" target="_blank">HRM/HcmJobADARequirementEntity</a>|
|[Fingering](#Fingering)||<a href="HcmJobADARequirementEntity.md" target="_blank">HRM/HcmJobADARequirementEntity</a>|
|[Grasping](#Grasping)||<a href="HcmJobADARequirementEntity.md" target="_blank">HRM/HcmJobADARequirementEntity</a>|
|[Hazards](#Hazards)||<a href="HcmJobADARequirementEntity.md" target="_blank">HRM/HcmJobADARequirementEntity</a>|
|[Hearing](#Hearing)||<a href="HcmJobADARequirementEntity.md" target="_blank">HRM/HcmJobADARequirementEntity</a>|
|[InfectiousDisease](#InfectiousDisease)||<a href="HcmJobADARequirementEntity.md" target="_blank">HRM/HcmJobADARequirementEntity</a>|
|[Kneeling](#Kneeling)||<a href="HcmJobADARequirementEntity.md" target="_blank">HRM/HcmJobADARequirementEntity</a>|
|[Lifting](#Lifting)||<a href="HcmJobADARequirementEntity.md" target="_blank">HRM/HcmJobADARequirementEntity</a>|
|[MentalPatients](#MentalPatients)||<a href="HcmJobADARequirementEntity.md" target="_blank">HRM/HcmJobADARequirementEntity</a>|
|[NarrowAisles](#NarrowAisles)||<a href="HcmJobADARequirementEntity.md" target="_blank">HRM/HcmJobADARequirementEntity</a>|
|[Noise](#Noise)||<a href="HcmJobADARequirementEntity.md" target="_blank">HRM/HcmJobADARequirementEntity</a>|
|[Oils](#Oils)||<a href="HcmJobADARequirementEntity.md" target="_blank">HRM/HcmJobADARequirementEntity</a>|
|[PhysicalRequirement](#PhysicalRequirement)||<a href="HcmJobADARequirementEntity.md" target="_blank">HRM/HcmJobADARequirementEntity</a>|
|[Pulling](#Pulling)||<a href="HcmJobADARequirementEntity.md" target="_blank">HRM/HcmJobADARequirementEntity</a>|
|[Pushing](#Pushing)||<a href="HcmJobADARequirementEntity.md" target="_blank">HRM/HcmJobADARequirementEntity</a>|
|[Reaching](#Reaching)||<a href="HcmJobADARequirementEntity.md" target="_blank">HRM/HcmJobADARequirementEntity</a>|
|[RepetitiveMotions](#RepetitiveMotions)||<a href="HcmJobADARequirementEntity.md" target="_blank">HRM/HcmJobADARequirementEntity</a>|
|[Respirator](#Respirator)||<a href="HcmJobADARequirementEntity.md" target="_blank">HRM/HcmJobADARequirementEntity</a>|
|[Standing](#Standing)||<a href="HcmJobADARequirementEntity.md" target="_blank">HRM/HcmJobADARequirementEntity</a>|
|[Stooping](#Stooping)||<a href="HcmJobADARequirementEntity.md" target="_blank">HRM/HcmJobADARequirementEntity</a>|
|[Talking](#Talking)||<a href="HcmJobADARequirementEntity.md" target="_blank">HRM/HcmJobADARequirementEntity</a>|
|[Vibration](#Vibration)||<a href="HcmJobADARequirementEntity.md" target="_blank">HRM/HcmJobADARequirementEntity</a>|
|[VisualAcuity](#VisualAcuity)||<a href="HcmJobADARequirementEntity.md" target="_blank">HRM/HcmJobADARequirementEntity</a>|
|[Walking](#Walking)||<a href="HcmJobADARequirementEntity.md" target="_blank">HRM/HcmJobADARequirementEntity</a>|
|[Relationship_JobRelationshipId](#Relationship_JobRelationshipId)||<a href="HcmJobADARequirementEntity.md" target="_blank">HRM/HcmJobADARequirementEntity</a>|

### <a href=#Job name="Job">Job</a>

First included in: HRM/HcmJobADARequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Job attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JobId name="JobId">JobId</a>

First included in: HRM/HcmJobADARequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JobId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AdverseConditions name="AdverseConditions">AdverseConditions</a>

First included in: HRM/HcmJobADARequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AdverseConditions attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AtmosphericConditions name="AtmosphericConditions">AtmosphericConditions</a>

First included in: HRM/HcmJobADARequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AtmosphericConditions attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Balancing name="Balancing">Balancing</a>

First included in: HRM/HcmJobADARequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Balancing attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Climbing name="Climbing">Climbing</a>

First included in: HRM/HcmJobADARequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Climbing attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CloseQuaters name="CloseQuaters">CloseQuaters</a>

First included in: HRM/HcmJobADARequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CloseQuaters attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Crawling name="Crawling">Crawling</a>

First included in: HRM/HcmJobADARequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Crawling attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Crouching name="Crouching">Crouching</a>

First included in: HRM/HcmJobADARequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Crouching attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnvironmentBoth name="EnvironmentBoth">EnvironmentBoth</a>

First included in: HRM/HcmJobADARequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnvironmentBoth attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnvironmentCold name="EnvironmentCold">EnvironmentCold</a>

First included in: HRM/HcmJobADARequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnvironmentCold attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnvironmentHeat name="EnvironmentHeat">EnvironmentHeat</a>

First included in: HRM/HcmJobADARequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnvironmentHeat attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnvironmentInside name="EnvironmentInside">EnvironmentInside</a>

First included in: HRM/HcmJobADARequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnvironmentInside attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnvironmentOutside name="EnvironmentOutside">EnvironmentOutside</a>

First included in: HRM/HcmJobADARequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnvironmentOutside attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Feeling name="Feeling">Feeling</a>

First included in: HRM/HcmJobADARequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Feeling attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Fingering name="Fingering">Fingering</a>

First included in: HRM/HcmJobADARequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Fingering attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Grasping name="Grasping">Grasping</a>

First included in: HRM/HcmJobADARequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Grasping attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Hazards name="Hazards">Hazards</a>

First included in: HRM/HcmJobADARequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Hazards attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Hearing name="Hearing">Hearing</a>

First included in: HRM/HcmJobADARequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Hearing attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InfectiousDisease name="InfectiousDisease">InfectiousDisease</a>

First included in: HRM/HcmJobADARequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InfectiousDisease attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Kneeling name="Kneeling">Kneeling</a>

First included in: HRM/HcmJobADARequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Kneeling attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Lifting name="Lifting">Lifting</a>

First included in: HRM/HcmJobADARequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Lifting attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MentalPatients name="MentalPatients">MentalPatients</a>

First included in: HRM/HcmJobADARequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MentalPatients attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NarrowAisles name="NarrowAisles">NarrowAisles</a>

First included in: HRM/HcmJobADARequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NarrowAisles attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Noise name="Noise">Noise</a>

First included in: HRM/HcmJobADARequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Noise attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Oils name="Oils">Oils</a>

First included in: HRM/HcmJobADARequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Oils attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PhysicalRequirement name="PhysicalRequirement">PhysicalRequirement</a>

First included in: HRM/HcmJobADARequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhysicalRequirement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Pulling name="Pulling">Pulling</a>

First included in: HRM/HcmJobADARequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Pulling attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Pushing name="Pushing">Pushing</a>

First included in: HRM/HcmJobADARequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Pushing attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Reaching name="Reaching">Reaching</a>

First included in: HRM/HcmJobADARequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Reaching attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RepetitiveMotions name="RepetitiveMotions">RepetitiveMotions</a>

First included in: HRM/HcmJobADARequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RepetitiveMotions attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Respirator name="Respirator">Respirator</a>

First included in: HRM/HcmJobADARequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Respirator attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Standing name="Standing">Standing</a>

First included in: HRM/HcmJobADARequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Standing attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Stooping name="Stooping">Stooping</a>

First included in: HRM/HcmJobADARequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Stooping attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Talking name="Talking">Talking</a>

First included in: HRM/HcmJobADARequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Talking attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Vibration name="Vibration">Vibration</a>

First included in: HRM/HcmJobADARequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Vibration attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VisualAcuity name="VisualAcuity">VisualAcuity</a>

First included in: HRM/HcmJobADARequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VisualAcuity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Walking name="Walking">Walking</a>

First included in: HRM/HcmJobADARequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Walking attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_JobRelationshipId name="Relationship_JobRelationshipId">Relationship_JobRelationshipId</a>

First included in: HRM/HcmJobADARequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_JobRelationshipId attribute are listed below.</summary>

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
