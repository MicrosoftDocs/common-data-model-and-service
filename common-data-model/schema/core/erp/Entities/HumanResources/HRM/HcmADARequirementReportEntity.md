---
title: HcmADARequirementReportEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# HcmADARequirementReportEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Entities/HumanResources/HRM/HcmADARequirementReportEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[AdverseConditions](#AdverseConditions)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[AtmosphericConditions](#AtmosphericConditions)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[Balancing](#Balancing)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[Climbing](#Climbing)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[CloseQuaters](#CloseQuaters)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[Crawling](#Crawling)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[Crouching](#Crouching)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[EnvironmentBoth](#EnvironmentBoth)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[EnvironmentCold](#EnvironmentCold)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[EnvironmentHeat](#EnvironmentHeat)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[EnvironmentInside](#EnvironmentInside)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[EnvironmentOutside](#EnvironmentOutside)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[Feeling](#Feeling)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[Fingering](#Fingering)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[Grasping](#Grasping)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[Hazards](#Hazards)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[Hearing](#Hearing)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[InfectiousDisease](#InfectiousDisease)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[Kneeling](#Kneeling)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[Lifting](#Lifting)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[MentalPatients](#MentalPatients)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[NarrowAisles](#NarrowAisles)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[Noise](#Noise)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[Oils](#Oils)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[PhysicalRequirement](#PhysicalRequirement)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[Pulling](#Pulling)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[Pushing](#Pushing)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[Reaching](#Reaching)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[ADARecId](#ADARecId)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[RepetitiveMotions](#RepetitiveMotions)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[Respirator](#Respirator)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[Standing](#Standing)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[Stooping](#Stooping)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[Talking](#Talking)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[Vibration](#Vibration)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[VisualAcuity](#VisualAcuity)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[Walking](#Walking)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[JobId](#JobId)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[JobTemplateId](#JobTemplateId)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[Id](#Id)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[ClimbingDescription](#ClimbingDescription)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[VistualAcutiyDescription](#VistualAcutiyDescription)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[PhysicalRequirementDescription](#PhysicalRequirementDescription)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[ReportTitle](#ReportTitle)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[PhysicalActivityGroup](#PhysicalActivityGroup)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[PhysicalRequirementGroup](#PhysicalRequirementGroup)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[VisualAcuityGroup](#VisualAcuityGroup)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[WorkConditionGroup](#WorkConditionGroup)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[BalancingDescription](#BalancingDescription)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[StoopingDescription](#StoopingDescription)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[KneelingDescription](#KneelingDescription)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[CrouchingDescription](#CrouchingDescription)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[CrawlingDescription](#CrawlingDescription)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[ReachingDescription](#ReachingDescription)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[StandingDescription](#StandingDescription)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[WalkingDescription](#WalkingDescription)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[PushingDescription](#PushingDescription)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[PullingDescription](#PullingDescription)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[LiftingDescription](#LiftingDescription)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[FingeringDescription](#FingeringDescription)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[GraspingDescription](#GraspingDescription)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[FeelingDescription](#FeelingDescription)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[TalkingDescription](#TalkingDescription)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[HearingDescription](#HearingDescription)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[RepetitiveMotionsDescription](#RepetitiveMotionsDescription)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[EnvironmentInsideDescription](#EnvironmentInsideDescription)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[EnvironmentOutsideDescription](#EnvironmentOutsideDescription)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[EnvironmentBothDescription](#EnvironmentBothDescription)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[EnvironmentColdDescription](#EnvironmentColdDescription)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[EnvironmentHeatDescription](#EnvironmentHeatDescription)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[NoiseDescription](#NoiseDescription)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[VibrationDescription](#VibrationDescription)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[HazardsDescription](#HazardsDescription)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[AtmosphericConditionsDescription](#AtmosphericConditionsDescription)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[OilsDescription](#OilsDescription)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[RespiratorDescription](#RespiratorDescription)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[CloseQuatersDescription](#CloseQuatersDescription)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[NarrowAislesDescription](#NarrowAislesDescription)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[InfectiousDiseaseDescription](#InfectiousDiseaseDescription)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[MentalPatientsDescription](#MentalPatientsDescription)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[AdverseConditionsDescription](#AdverseConditionsDescription)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[Relationship_JobRelationshipId](#Relationship_JobRelationshipId)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|
|[Relationship_JobTemplateRelationshipId](#Relationship_JobTemplateRelationshipId)||<a href="HcmADARequirementReportEntity.md" target="_blank">HRM/HcmADARequirementReportEntity</a>|

### <a href=#AdverseConditions name="AdverseConditions">AdverseConditions</a>

First included in: HRM/HcmADARequirementReportEntity (this entity)  

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

First included in: HRM/HcmADARequirementReportEntity (this entity)  

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

First included in: HRM/HcmADARequirementReportEntity (this entity)  

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

First included in: HRM/HcmADARequirementReportEntity (this entity)  

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

First included in: HRM/HcmADARequirementReportEntity (this entity)  

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

First included in: HRM/HcmADARequirementReportEntity (this entity)  

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

First included in: HRM/HcmADARequirementReportEntity (this entity)  

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

First included in: HRM/HcmADARequirementReportEntity (this entity)  

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

First included in: HRM/HcmADARequirementReportEntity (this entity)  

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

First included in: HRM/HcmADARequirementReportEntity (this entity)  

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

First included in: HRM/HcmADARequirementReportEntity (this entity)  

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

First included in: HRM/HcmADARequirementReportEntity (this entity)  

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

First included in: HRM/HcmADARequirementReportEntity (this entity)  

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

First included in: HRM/HcmADARequirementReportEntity (this entity)  

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

First included in: HRM/HcmADARequirementReportEntity (this entity)  

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

First included in: HRM/HcmADARequirementReportEntity (this entity)  

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

First included in: HRM/HcmADARequirementReportEntity (this entity)  

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

First included in: HRM/HcmADARequirementReportEntity (this entity)  

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

First included in: HRM/HcmADARequirementReportEntity (this entity)  

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

First included in: HRM/HcmADARequirementReportEntity (this entity)  

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

First included in: HRM/HcmADARequirementReportEntity (this entity)  

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

First included in: HRM/HcmADARequirementReportEntity (this entity)  

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

First included in: HRM/HcmADARequirementReportEntity (this entity)  

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

First included in: HRM/HcmADARequirementReportEntity (this entity)  

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

First included in: HRM/HcmADARequirementReportEntity (this entity)  

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

First included in: HRM/HcmADARequirementReportEntity (this entity)  

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

First included in: HRM/HcmADARequirementReportEntity (this entity)  

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

First included in: HRM/HcmADARequirementReportEntity (this entity)  

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

### <a href=#ADARecId name="ADARecId">ADARecId</a>

First included in: HRM/HcmADARequirementReportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ADARecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RepetitiveMotions name="RepetitiveMotions">RepetitiveMotions</a>

First included in: HRM/HcmADARequirementReportEntity (this entity)  

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

First included in: HRM/HcmADARequirementReportEntity (this entity)  

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

First included in: HRM/HcmADARequirementReportEntity (this entity)  

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

First included in: HRM/HcmADARequirementReportEntity (this entity)  

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

First included in: HRM/HcmADARequirementReportEntity (this entity)  

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

First included in: HRM/HcmADARequirementReportEntity (this entity)  

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

First included in: HRM/HcmADARequirementReportEntity (this entity)  

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

First included in: HRM/HcmADARequirementReportEntity (this entity)  

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

### <a href=#JobId name="JobId">JobId</a>

First included in: HRM/HcmADARequirementReportEntity (this entity)  

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

### <a href=#JobTemplateId name="JobTemplateId">JobTemplateId</a>

First included in: HRM/HcmADARequirementReportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JobTemplateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Id name="Id">Id</a>

First included in: HRM/HcmADARequirementReportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Id attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ClimbingDescription name="ClimbingDescription">ClimbingDescription</a>

First included in: HRM/HcmADARequirementReportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClimbingDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VistualAcutiyDescription name="VistualAcutiyDescription">VistualAcutiyDescription</a>

First included in: HRM/HcmADARequirementReportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VistualAcutiyDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PhysicalRequirementDescription name="PhysicalRequirementDescription">PhysicalRequirementDescription</a>

First included in: HRM/HcmADARequirementReportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhysicalRequirementDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportTitle name="ReportTitle">ReportTitle</a>

First included in: HRM/HcmADARequirementReportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportTitle attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PhysicalActivityGroup name="PhysicalActivityGroup">PhysicalActivityGroup</a>

First included in: HRM/HcmADARequirementReportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhysicalActivityGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PhysicalRequirementGroup name="PhysicalRequirementGroup">PhysicalRequirementGroup</a>

First included in: HRM/HcmADARequirementReportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhysicalRequirementGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VisualAcuityGroup name="VisualAcuityGroup">VisualAcuityGroup</a>

First included in: HRM/HcmADARequirementReportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VisualAcuityGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkConditionGroup name="WorkConditionGroup">WorkConditionGroup</a>

First included in: HRM/HcmADARequirementReportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkConditionGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BalancingDescription name="BalancingDescription">BalancingDescription</a>

First included in: HRM/HcmADARequirementReportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BalancingDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StoopingDescription name="StoopingDescription">StoopingDescription</a>

First included in: HRM/HcmADARequirementReportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StoopingDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#KneelingDescription name="KneelingDescription">KneelingDescription</a>

First included in: HRM/HcmADARequirementReportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the KneelingDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CrouchingDescription name="CrouchingDescription">CrouchingDescription</a>

First included in: HRM/HcmADARequirementReportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CrouchingDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CrawlingDescription name="CrawlingDescription">CrawlingDescription</a>

First included in: HRM/HcmADARequirementReportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CrawlingDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReachingDescription name="ReachingDescription">ReachingDescription</a>

First included in: HRM/HcmADARequirementReportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReachingDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StandingDescription name="StandingDescription">StandingDescription</a>

First included in: HRM/HcmADARequirementReportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StandingDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WalkingDescription name="WalkingDescription">WalkingDescription</a>

First included in: HRM/HcmADARequirementReportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WalkingDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PushingDescription name="PushingDescription">PushingDescription</a>

First included in: HRM/HcmADARequirementReportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PushingDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PullingDescription name="PullingDescription">PullingDescription</a>

First included in: HRM/HcmADARequirementReportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PullingDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LiftingDescription name="LiftingDescription">LiftingDescription</a>

First included in: HRM/HcmADARequirementReportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LiftingDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FingeringDescription name="FingeringDescription">FingeringDescription</a>

First included in: HRM/HcmADARequirementReportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FingeringDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GraspingDescription name="GraspingDescription">GraspingDescription</a>

First included in: HRM/HcmADARequirementReportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GraspingDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FeelingDescription name="FeelingDescription">FeelingDescription</a>

First included in: HRM/HcmADARequirementReportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FeelingDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TalkingDescription name="TalkingDescription">TalkingDescription</a>

First included in: HRM/HcmADARequirementReportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TalkingDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HearingDescription name="HearingDescription">HearingDescription</a>

First included in: HRM/HcmADARequirementReportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HearingDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RepetitiveMotionsDescription name="RepetitiveMotionsDescription">RepetitiveMotionsDescription</a>

First included in: HRM/HcmADARequirementReportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RepetitiveMotionsDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnvironmentInsideDescription name="EnvironmentInsideDescription">EnvironmentInsideDescription</a>

First included in: HRM/HcmADARequirementReportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnvironmentInsideDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnvironmentOutsideDescription name="EnvironmentOutsideDescription">EnvironmentOutsideDescription</a>

First included in: HRM/HcmADARequirementReportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnvironmentOutsideDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnvironmentBothDescription name="EnvironmentBothDescription">EnvironmentBothDescription</a>

First included in: HRM/HcmADARequirementReportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnvironmentBothDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnvironmentColdDescription name="EnvironmentColdDescription">EnvironmentColdDescription</a>

First included in: HRM/HcmADARequirementReportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnvironmentColdDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnvironmentHeatDescription name="EnvironmentHeatDescription">EnvironmentHeatDescription</a>

First included in: HRM/HcmADARequirementReportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnvironmentHeatDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NoiseDescription name="NoiseDescription">NoiseDescription</a>

First included in: HRM/HcmADARequirementReportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NoiseDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VibrationDescription name="VibrationDescription">VibrationDescription</a>

First included in: HRM/HcmADARequirementReportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VibrationDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HazardsDescription name="HazardsDescription">HazardsDescription</a>

First included in: HRM/HcmADARequirementReportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HazardsDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AtmosphericConditionsDescription name="AtmosphericConditionsDescription">AtmosphericConditionsDescription</a>

First included in: HRM/HcmADARequirementReportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AtmosphericConditionsDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OilsDescription name="OilsDescription">OilsDescription</a>

First included in: HRM/HcmADARequirementReportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OilsDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RespiratorDescription name="RespiratorDescription">RespiratorDescription</a>

First included in: HRM/HcmADARequirementReportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RespiratorDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CloseQuatersDescription name="CloseQuatersDescription">CloseQuatersDescription</a>

First included in: HRM/HcmADARequirementReportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CloseQuatersDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NarrowAislesDescription name="NarrowAislesDescription">NarrowAislesDescription</a>

First included in: HRM/HcmADARequirementReportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NarrowAislesDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InfectiousDiseaseDescription name="InfectiousDiseaseDescription">InfectiousDiseaseDescription</a>

First included in: HRM/HcmADARequirementReportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InfectiousDiseaseDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MentalPatientsDescription name="MentalPatientsDescription">MentalPatientsDescription</a>

First included in: HRM/HcmADARequirementReportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MentalPatientsDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AdverseConditionsDescription name="AdverseConditionsDescription">AdverseConditionsDescription</a>

First included in: HRM/HcmADARequirementReportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AdverseConditionsDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_JobRelationshipId name="Relationship_JobRelationshipId">Relationship_JobRelationshipId</a>

First included in: HRM/HcmADARequirementReportEntity (this entity)  

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

### <a href=#Relationship_JobTemplateRelationshipId name="Relationship_JobTemplateRelationshipId">Relationship_JobTemplateRelationshipId</a>

First included in: HRM/HcmADARequirementReportEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_JobTemplateRelationshipId attribute are listed below.</summary>

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
