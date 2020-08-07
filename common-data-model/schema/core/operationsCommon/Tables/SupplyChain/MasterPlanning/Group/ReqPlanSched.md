---
title: ReqPlanSched in Group - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Master plan setup in Group(ReqPlanSched)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/MasterPlanning/Group/ReqPlanSched.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ReqPlanSched/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Master plan setup</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[ActionUpdReqDatePurch](#ActionUpdReqDatePurch)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[BottleneckScheduling](#BottleneckScheduling)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[CovCapLimited](#CovCapLimited)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[CovPropertyLimited](#CovPropertyLimited)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[CovSchedMethod](#CovSchedMethod)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[CovTimeFenceSchedBack](#CovTimeFenceSchedBack)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[FuturesSched](#FuturesSched)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[FuturesUpdReqDatePurch](#FuturesUpdReqDatePurch)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[FuturesUpdReqDateTransfer](#FuturesUpdReqDateTransfer)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[IncludePlannedIntercompanyDemand](#IncludePlannedIntercompanyDemand)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[IncludeRequisitions](#IncludeRequisitions)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[IssueMargin](#IssueMargin)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[MCRIncludePastDueContinuity](#MCRIncludePastDueContinuity)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[MCRPastDueContinuityDays](#MCRPastDueContinuityDays)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[MCRPlanVersionContinuity](#MCRPlanVersionContinuity)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[MCRTimeFenceContinuityPlan](#MCRTimeFenceContinuityPlan)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[MCRTimeFenceContinuityPlanFixed](#MCRTimeFenceContinuityPlanFixed)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[MCRUseContinuityPlan](#MCRUseContinuityPlan)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[Name](#Name)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[OnHandConsumptionStrategy](#OnHandConsumptionStrategy)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[OnHandConsumptionStrategyFixed](#OnHandConsumptionStrategyFixed)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[OrderingMargin](#OrderingMargin)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[PdsUseShelfLife](#PdsUseShelfLife)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[PlannedOrderSequenceRecId](#PlannedOrderSequenceRecId)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[PMFSeqBucketPeriod](#PMFSeqBucketPeriod)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[PMFSeqBucketType](#PMFSeqBucketType)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[PMFSeqCovSequencing](#PMFSeqCovSequencing)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[PMFSeqSequencingBucket](#PMFSeqSequencingBucket)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[PMFSeqTimeFenceSequencing](#PMFSeqTimeFenceSequencing)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[PMFSeqTimeFenceSequencingFixed](#PMFSeqTimeFenceSequencingFixed)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[PostponeKanbanToFutureDate](#PostponeKanbanToFutureDate)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[ReceiptMargin](#ReceiptMargin)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[ReqPlanIdSched](#ReqPlanIdSched)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[ReqPlanSequenceRecId](#ReqPlanSequenceRecId)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[smmQuotationProbabilityId](#smmQuotationProbabilityId)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[TimeFenceAction](#TimeFenceAction)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[TimeFenceActionFixed](#TimeFenceActionFixed)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[TimeFenceAuthorization](#TimeFenceAuthorization)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[TimeFenceAuthorizationFixed](#TimeFenceAuthorizationFixed)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[TimeFenceBackRequisition](#TimeFenceBackRequisition)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[TimeFenceBackRequisitionFixed](#TimeFenceBackRequisitionFixed)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[TimeFenceBottleneckCap](#TimeFenceBottleneckCap)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[TimeFenceCapacity](#TimeFenceCapacity)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[TimeFenceCapacityFixed](#TimeFenceCapacityFixed)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[TimeFenceCov](#TimeFenceCov)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[TimeFenceCovFixed](#TimeFenceCovFixed)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[TimeFenceExplosion](#TimeFenceExplosion)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[TimeFenceExplosionFixed](#TimeFenceExplosionFixed)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[TimeFenceFiniteCap](#TimeFenceFiniteCap)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[TimeFenceFutures](#TimeFenceFutures)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[TimeFenceFuturesFixed](#TimeFenceFuturesFixed)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[TimeFenceLocking](#TimeFenceLocking)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[TimeFenceLockingFixed](#TimeFenceLockingFixed)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[TimeFenceMasterPlan](#TimeFenceMasterPlan)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[TimeFenceMasterPlanFixed](#TimeFenceMasterPlanFixed)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[UseInventOnHand](#UseInventOnHand)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[UseMovements](#UseMovements)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[UseQuotations](#UseQuotations)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[UseRequestsForQuote](#UseRequestsForQuote)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[PreventScheduleBeforeToday](#PreventScheduleBeforeToday)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[DataAreaId](#DataAreaId)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[Relationship_MCRReqTransRelationshipId](#Relationship_MCRReqTransRelationshipId)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[Relationship_PlannedOrderNumberSequenceRelationshipId](#Relationship_PlannedOrderNumberSequenceRelationshipId)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[Relationship_ReqLogRelationshipId](#Relationship_ReqLogRelationshipId)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[Relationship_ReqPlanRelationshipId](#Relationship_ReqPlanRelationshipId)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[Relationship_ReqPlanNumberSequenceRelationshipId](#Relationship_ReqPlanNumberSequenceRelationshipId)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[Relationship_smmQuotationProbabilityGroupRelationshipId](#Relationship_smmQuotationProbabilityGroupRelationshipId)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="ReqPlanSched.md" target="_blank">Group/ReqPlanSched</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ReqPlanSched/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ActionUpdReqDatePurch name="ActionUpdReqDatePurch">ActionUpdReqDatePurch</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Update postponed date as requirement date</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActionUpdReqDatePurch attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Update postponed date as requirement date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#BottleneckScheduling name="BottleneckScheduling">BottleneckScheduling</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BottleneckScheduling attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CovCapLimited name="CovCapLimited">CovCapLimited</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CovCapLimited attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CovPropertyLimited name="CovPropertyLimited">CovPropertyLimited</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CovPropertyLimited attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CovSchedMethod name="CovSchedMethod">CovSchedMethod</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CovSchedMethod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CovTimeFenceSchedBack name="CovTimeFenceSchedBack">CovTimeFenceSchedBack</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CovTimeFenceSchedBack attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#FuturesSched name="FuturesSched">FuturesSched</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Update planning</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FuturesSched attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Update planning</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#FuturesUpdReqDatePurch name="FuturesUpdReqDatePurch">FuturesUpdReqDatePurch</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Update requirement date on planned purchase order</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FuturesUpdReqDatePurch attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Update requirement date on planned purchase order</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#FuturesUpdReqDateTransfer name="FuturesUpdReqDateTransfer">FuturesUpdReqDateTransfer</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Add the calculated delay to the requirement date</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FuturesUpdReqDateTransfer attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Add the calculated delay to the requirement date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#IncludePlannedIntercompanyDemand name="IncludePlannedIntercompanyDemand">IncludePlannedIntercompanyDemand</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IncludePlannedIntercompanyDemand attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#IncludeRequisitions name="IncludeRequisitions">IncludeRequisitions</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IncludeRequisitions attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#IssueMargin name="IssueMargin">IssueMargin</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IssueMargin attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#MCRIncludePastDueContinuity name="MCRIncludePastDueContinuity">MCRIncludePastDueContinuity</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRIncludePastDueContinuity attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#MCRPastDueContinuityDays name="MCRPastDueContinuityDays">MCRPastDueContinuityDays</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRPastDueContinuityDays attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#MCRPlanVersionContinuity name="MCRPlanVersionContinuity">MCRPlanVersionContinuity</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRPlanVersionContinuity attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#MCRTimeFenceContinuityPlan name="MCRTimeFenceContinuityPlan">MCRTimeFenceContinuityPlan</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Plan continuity time fence</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRTimeFenceContinuityPlan attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Plan continuity time fence</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#MCRTimeFenceContinuityPlanFixed name="MCRTimeFenceContinuityPlanFixed">MCRTimeFenceContinuityPlanFixed</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRTimeFenceContinuityPlanFixed attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#MCRUseContinuityPlan name="MCRUseContinuityPlan">MCRUseContinuityPlan</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Include continuity plan</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRUseContinuityPlan attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Include continuity plan</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OnHandConsumptionStrategy name="OnHandConsumptionStrategy">OnHandConsumptionStrategy</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OnHandConsumptionStrategy attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#OnHandConsumptionStrategyFixed name="OnHandConsumptionStrategyFixed">OnHandConsumptionStrategyFixed</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Consume on-hand inventory</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OnHandConsumptionStrategyFixed attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Consume on-hand inventory</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#OrderingMargin name="OrderingMargin">OrderingMargin</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderingMargin attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PdsUseShelfLife name="PdsUseShelfLife">PdsUseShelfLife</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PdsUseShelfLife attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PlannedOrderSequenceRecId name="PlannedOrderSequenceRecId">PlannedOrderSequenceRecId</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PlannedOrderSequenceRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PMFSeqBucketPeriod name="PMFSeqBucketPeriod">PMFSeqBucketPeriod</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PMFSeqBucketPeriod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PMFSeqBucketType name="PMFSeqBucketType">PMFSeqBucketType</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PMFSeqBucketType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PMFSeqCovSequencing name="PMFSeqCovSequencing">PMFSeqCovSequencing</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sequence planned orders after master planning</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PMFSeqCovSequencing attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sequence planned orders after master planning</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#PMFSeqSequencingBucket name="PMFSeqSequencingBucket">PMFSeqSequencingBucket</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PMFSeqSequencingBucket attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PMFSeqTimeFenceSequencing name="PMFSeqTimeFenceSequencing">PMFSeqTimeFenceSequencing</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PMFSeqTimeFenceSequencing attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PMFSeqTimeFenceSequencingFixed name="PMFSeqTimeFenceSequencingFixed">PMFSeqTimeFenceSequencingFixed</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sequencing</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PMFSeqTimeFenceSequencingFixed attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sequencing</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#PostponeKanbanToFutureDate name="PostponeKanbanToFutureDate">PostponeKanbanToFutureDate</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostponeKanbanToFutureDate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ReceiptMargin name="ReceiptMargin">ReceiptMargin</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceiptMargin attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ReqPlanIdSched name="ReqPlanIdSched">ReqPlanIdSched</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReqPlanIdSched attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReqPlanSequenceRecId name="ReqPlanSequenceRecId">ReqPlanSequenceRecId</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReqPlanSequenceRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#smmQuotationProbabilityId name="smmQuotationProbabilityId">smmQuotationProbabilityId</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the smmQuotationProbabilityId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TimeFenceAction name="TimeFenceAction">TimeFenceAction</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeFenceAction attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TimeFenceActionFixed name="TimeFenceActionFixed">TimeFenceActionFixed</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fixed action time fence</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeFenceActionFixed attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Fixed action time fence</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#TimeFenceAuthorization name="TimeFenceAuthorization">TimeFenceAuthorization</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeFenceAuthorization attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TimeFenceAuthorizationFixed name="TimeFenceAuthorizationFixed">TimeFenceAuthorizationFixed</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fixed firming time fence</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeFenceAuthorizationFixed attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Fixed firming time fence</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#TimeFenceBackRequisition name="TimeFenceBackRequisition">TimeFenceBackRequisition</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeFenceBackRequisition attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TimeFenceBackRequisitionFixed name="TimeFenceBackRequisitionFixed">TimeFenceBackRequisitionFixed</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Approved requisitions time fence (days)</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeFenceBackRequisitionFixed attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Approved requisitions time fence (days)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#TimeFenceBottleneckCap name="TimeFenceBottleneckCap">TimeFenceBottleneckCap</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeFenceBottleneckCap attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TimeFenceCapacity name="TimeFenceCapacity">TimeFenceCapacity</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeFenceCapacity attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TimeFenceCapacityFixed name="TimeFenceCapacityFixed">TimeFenceCapacityFixed</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fixed capacity time fence</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeFenceCapacityFixed attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Fixed capacity time fence</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#TimeFenceCov name="TimeFenceCov">TimeFenceCov</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeFenceCov attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TimeFenceCovFixed name="TimeFenceCovFixed">TimeFenceCovFixed</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fixed coverage time fence</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeFenceCovFixed attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Fixed coverage time fence</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#TimeFenceExplosion name="TimeFenceExplosion">TimeFenceExplosion</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeFenceExplosion attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TimeFenceExplosionFixed name="TimeFenceExplosionFixed">TimeFenceExplosionFixed</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fixed explosion time fence</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeFenceExplosionFixed attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Fixed explosion time fence</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#TimeFenceFiniteCap name="TimeFenceFiniteCap">TimeFenceFiniteCap</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeFenceFiniteCap attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TimeFenceFutures name="TimeFenceFutures">TimeFenceFutures</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeFenceFutures attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TimeFenceFuturesFixed name="TimeFenceFuturesFixed">TimeFenceFuturesFixed</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fixed calculate delays time fence (days)</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeFenceFuturesFixed attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Fixed calculate delays time fence (days)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#TimeFenceLocking name="TimeFenceLocking">TimeFenceLocking</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeFenceLocking attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TimeFenceLockingFixed name="TimeFenceLockingFixed">TimeFenceLockingFixed</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fixed locking time fence</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeFenceLockingFixed attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Fixed locking time fence</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#TimeFenceMasterPlan name="TimeFenceMasterPlan">TimeFenceMasterPlan</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeFenceMasterPlan attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TimeFenceMasterPlanFixed name="TimeFenceMasterPlanFixed">TimeFenceMasterPlanFixed</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fixed forecast plan time fence</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeFenceMasterPlanFixed attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Fixed forecast plan time fence</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#UseInventOnHand name="UseInventOnHand">UseInventOnHand</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Include on-hand inventory</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseInventOnHand attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Include on-hand inventory</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#UseMovements name="UseMovements">UseMovements</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Include inventory transactions</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseMovements attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Include inventory transactions</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#UseQuotations name="UseQuotations">UseQuotations</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Include sales quotations</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseQuotations attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Include sales quotations</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#UseRequestsForQuote name="UseRequestsForQuote">UseRequestsForQuote</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Include requests for quotations</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseRequestsForQuote attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Include requests for quotations</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#PreventScheduleBeforeToday name="PreventScheduleBeforeToday">PreventScheduleBeforeToday</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ensure that the planned orders are not created prior to the master planning run date</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PreventScheduleBeforeToday attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Ensure that the planned orders are not created prior to the master planning run date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Group/ReqPlanSched (this entity)  

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

### <a href=#Relationship_MCRReqTransRelationshipId name="Relationship_MCRReqTransRelationshipId">Relationship_MCRReqTransRelationshipId</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MCRReqTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/ReqTrans.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/MasterPlanning/Transaction/ReqTrans.cdm.json/ReqTrans</a></td><td><a href="../Transaction/ReqTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PlannedOrderNumberSequenceRelationshipId name="Relationship_PlannedOrderNumberSequenceRelationshipId">Relationship_PlannedOrderNumberSequenceRelationshipId</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PlannedOrderNumberSequenceRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Framework/NumberSequenceTable.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Framework/NumberSequenceTable.cdm.json/NumberSequenceTable</a></td><td><a href="../../../System/SystemAdministration/Framework/NumberSequenceTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ReqLogRelationshipId name="Relationship_ReqLogRelationshipId">Relationship_ReqLogRelationshipId</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReqLogRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/ReqLog.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/MasterPlanning/Transaction/ReqLog.cdm.json/ReqLog</a></td><td><a href="../Transaction/ReqLog.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ReqPlanRelationshipId name="Relationship_ReqPlanRelationshipId">Relationship_ReqPlanRelationshipId</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReqPlanRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="ReqPlan.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/MasterPlanning/Group/ReqPlan.cdm.json/ReqPlan</a></td><td><a href="ReqPlan.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ReqPlanNumberSequenceRelationshipId name="Relationship_ReqPlanNumberSequenceRelationshipId">Relationship_ReqPlanNumberSequenceRelationshipId</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReqPlanNumberSequenceRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Framework/NumberSequenceTable.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Framework/NumberSequenceTable.cdm.json/NumberSequenceTable</a></td><td><a href="../../../System/SystemAdministration/Framework/NumberSequenceTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_smmQuotationProbabilityGroupRelationshipId name="Relationship_smmQuotationProbabilityGroupRelationshipId">Relationship_smmQuotationProbabilityGroupRelationshipId</a>

First included in: Group/ReqPlanSched (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_smmQuotationProbabilityGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../SalesAndMarketing/Group/smmQuotationProbabilityGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Group/smmQuotationProbabilityGroup.cdm.json/smmQuotationProbabilityGroup</a></td><td><a href="../../SalesAndMarketing/Group/smmQuotationProbabilityGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Group/ReqPlanSched (this entity)  

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
