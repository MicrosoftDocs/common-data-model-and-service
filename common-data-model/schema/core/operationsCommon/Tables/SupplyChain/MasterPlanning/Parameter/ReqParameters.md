---
title: ReqParameters in Parameter - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/14/2020
ms.author: nebanfic
---

# Master planning parameters in Parameter(ReqParameters)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/MasterPlanning/Parameter/ReqParameters.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ReqParameters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Master planning parameters</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="ReqParameters.md" target="_blank">Parameter/ReqParameters</a>|
|[AutoCopyStaticPlan](#AutoCopyStaticPlan)||<a href="ReqParameters.md" target="_blank">Parameter/ReqParameters</a>|
|[BundleSize](#BundleSize)||<a href="ReqParameters.md" target="_blank">Parameter/ReqParameters</a>|
|[CurrentDaySchedFrom](#CurrentDaySchedFrom)||<a href="ReqParameters.md" target="_blank">Parameter/ReqParameters</a>|
|[CurrentReqPlanIdForecast](#CurrentReqPlanIdForecast)||<a href="ReqParameters.md" target="_blank">Parameter/ReqParameters</a>|
|[CurrentReqPlanIdSchedDynamic](#CurrentReqPlanIdSchedDynamic)||<a href="ReqParameters.md" target="_blank">Parameter/ReqParameters</a>|
|[CurrentReqPlanIdSchedStatic](#CurrentReqPlanIdSchedStatic)||<a href="ReqParameters.md" target="_blank">Parameter/ReqParameters</a>|
|[DefaultCollectPerPeriodJournal](#DefaultCollectPerPeriodJournal)||<a href="ReqParameters.md" target="_blank">Parameter/ReqParameters</a>|
|[DefaultCollectPerPeriodPurch](#DefaultCollectPerPeriodPurch)||<a href="ReqParameters.md" target="_blank">Parameter/ReqParameters</a>|
|[DefaultMarkUpdate](#DefaultMarkUpdate)||<a href="ReqParameters.md" target="_blank">Parameter/ReqParameters</a>|
|[DynamicNegativeDays](#DynamicNegativeDays)||<a href="ReqParameters.md" target="_blank">Parameter/ReqParameters</a>|
|[Key](#Key)||<a href="ReqParameters.md" target="_blank">Parameter/ReqParameters</a>|
|[MarginCalendarDays](#MarginCalendarDays)||<a href="ReqParameters.md" target="_blank">Parameter/ReqParameters</a>|
|[MCRCurrentReqPlanIdContinuity](#MCRCurrentReqPlanIdContinuity)||<a href="ReqParameters.md" target="_blank">Parameter/ReqParameters</a>|
|[ReqAbortFirmIfError](#ReqAbortFirmIfError)||<a href="ReqParameters.md" target="_blank">Parameter/ReqParameters</a>|
|[ReqPOCollectPerBuyer](#ReqPOCollectPerBuyer)||<a href="ReqParameters.md" target="_blank">Parameter/ReqParameters</a>|
|[ReqPOCollectPerPurchAgreement](#ReqPOCollectPerPurchAgreement)||<a href="ReqParameters.md" target="_blank">Parameter/ReqParameters</a>|
|[ReqPOCollectPerVendor](#ReqPOCollectPerVendor)||<a href="ReqParameters.md" target="_blank">Parameter/ReqParameters</a>|
|[ReqPOSearchPurchAgreement](#ReqPOSearchPurchAgreement)||<a href="ReqParameters.md" target="_blank">Parameter/ReqParameters</a>|
|[ReqSearchTradeAgreement](#ReqSearchTradeAgreement)||<a href="ReqParameters.md" target="_blank">Parameter/ReqParameters</a>|
|[ReqSearchTradeMethod](#ReqSearchTradeMethod)||<a href="ReqParameters.md" target="_blank">Parameter/ReqParameters</a>|
|[ReqTimeFutures](#ReqTimeFutures)||<a href="ReqParameters.md" target="_blank">Parameter/ReqParameters</a>|
|[ReqTimePoDefault](#ReqTimePoDefault)||<a href="ReqParameters.md" target="_blank">Parameter/ReqParameters</a>|
|[StandardReqGroupId](#StandardReqGroupId)||<a href="ReqParameters.md" target="_blank">Parameter/ReqParameters</a>|
|[TodaysdateCalendarId](#TodaysdateCalendarId)||<a href="ReqParameters.md" target="_blank">Parameter/ReqParameters</a>|
|[UseCache](#UseCache)||<a href="ReqParameters.md" target="_blank">Parameter/ReqParameters</a>|
|[ItemFilterPreUpdate](#ItemFilterPreUpdate)||<a href="ReqParameters.md" target="_blank">Parameter/ReqParameters</a>|
|[ItemFilterPreCoverage](#ItemFilterPreCoverage)||<a href="ReqParameters.md" target="_blank">Parameter/ReqParameters</a>|
|[ReqInactive](#ReqInactive)||<a href="ReqParameters.md" target="_blank">Parameter/ReqParameters</a>|
|[FirmingBundleSize](#FirmingBundleSize)||<a href="ReqParameters.md" target="_blank">Parameter/ReqParameters</a>|
|[SkipPreallocatingRecIds](#SkipPreallocatingRecIds)||<a href="ReqParameters.md" target="_blank">Parameter/ReqParameters</a>|
|[PreallocatedRecIdBlockSize](#PreallocatedRecIdBlockSize)||<a href="ReqParameters.md" target="_blank">Parameter/ReqParameters</a>|
|[AccurateOpSchedFiniteCapacity](#AccurateOpSchedFiniteCapacity)||<a href="ReqParameters.md" target="_blank">Parameter/ReqParameters</a>|
|[DefaultNumberOfThreads](#DefaultNumberOfThreads)||<a href="ReqParameters.md" target="_blank">Parameter/ReqParameters</a>|
|[ReqCalcTimeoutInMinutes](#ReqCalcTimeoutInMinutes)||<a href="ReqParameters.md" target="_blank">Parameter/ReqParameters</a>|
|[PriceType_IN](#PriceType_IN)||<a href="ReqParameters.md" target="_blank">Parameter/ReqParameters</a>|
|[TransferType_IN](#TransferType_IN)||<a href="ReqParameters.md" target="_blank">Parameter/ReqParameters</a>|
|[DataAreaId](#DataAreaId)||<a href="ReqParameters.md" target="_blank">Parameter/ReqParameters</a>|
|[Relationship_CurrentDynamicMasterPlanRelationshipId](#Relationship_CurrentDynamicMasterPlanRelationshipId)||<a href="ReqParameters.md" target="_blank">Parameter/ReqParameters</a>|
|[Relationship_CurrentForecastPlanRelationshipId](#Relationship_CurrentForecastPlanRelationshipId)||<a href="ReqParameters.md" target="_blank">Parameter/ReqParameters</a>|
|[Relationship_CurrentStaticMasterPlanRelationshipId](#Relationship_CurrentStaticMasterPlanRelationshipId)||<a href="ReqParameters.md" target="_blank">Parameter/ReqParameters</a>|
|[Relationship_ReqGroupRelationshipId](#Relationship_ReqGroupRelationshipId)||<a href="ReqParameters.md" target="_blank">Parameter/ReqParameters</a>|
|[Relationship_TodaysDateWorkCalendarTableRelationshipId](#Relationship_TodaysDateWorkCalendarTableRelationshipId)||<a href="ReqParameters.md" target="_blank">Parameter/ReqParameters</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="ReqParameters.md" target="_blank">Parameter/ReqParameters</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Parameter/ReqParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ReqParameters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AutoCopyStaticPlan name="AutoCopyStaticPlan">AutoCopyStaticPlan</a>

First included in: Parameter/ReqParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Copy the complete and updated static master plan to the dynamic master plan</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AutoCopyStaticPlan attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Copy the complete and updated static master plan to the dynamic master plan</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#BundleSize name="BundleSize">BundleSize</a>

First included in: Parameter/ReqParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BundleSize attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CurrentDaySchedFrom name="CurrentDaySchedFrom">CurrentDaySchedFrom</a>

First included in: Parameter/ReqParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrentDaySchedFrom attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CurrentReqPlanIdForecast name="CurrentReqPlanIdForecast">CurrentReqPlanIdForecast</a>

First included in: Parameter/ReqParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Current forecast plan</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrentReqPlanIdForecast attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Current forecast plan</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrentReqPlanIdSchedDynamic name="CurrentReqPlanIdSchedDynamic">CurrentReqPlanIdSchedDynamic</a>

First included in: Parameter/ReqParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Current dynamic master plan</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrentReqPlanIdSchedDynamic attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Current dynamic master plan</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrentReqPlanIdSchedStatic name="CurrentReqPlanIdSchedStatic">CurrentReqPlanIdSchedStatic</a>

First included in: Parameter/ReqParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Current static master plan</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrentReqPlanIdSchedStatic attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Current static master plan</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultCollectPerPeriodJournal name="DefaultCollectPerPeriodJournal">DefaultCollectPerPeriodJournal</a>

First included in: Parameter/ReqParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultCollectPerPeriodJournal attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DefaultCollectPerPeriodPurch name="DefaultCollectPerPeriodPurch">DefaultCollectPerPeriodPurch</a>

First included in: Parameter/ReqParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultCollectPerPeriodPurch attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DefaultMarkUpdate name="DefaultMarkUpdate">DefaultMarkUpdate</a>

First included in: Parameter/ReqParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultMarkUpdate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DynamicNegativeDays name="DynamicNegativeDays">DynamicNegativeDays</a>

First included in: Parameter/ReqParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DynamicNegativeDays attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Key name="Key">Key</a>

First included in: Parameter/ReqParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Key attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#MarginCalendarDays name="MarginCalendarDays">MarginCalendarDays</a>

First included in: Parameter/ReqParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MarginCalendarDays attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#MCRCurrentReqPlanIdContinuity name="MCRCurrentReqPlanIdContinuity">MCRCurrentReqPlanIdContinuity</a>

First included in: Parameter/ReqParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRCurrentReqPlanIdContinuity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReqAbortFirmIfError name="ReqAbortFirmIfError">ReqAbortFirmIfError</a>

First included in: Parameter/ReqParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReqAbortFirmIfError attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ReqPOCollectPerBuyer name="ReqPOCollectPerBuyer">ReqPOCollectPerBuyer</a>

First included in: Parameter/ReqParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReqPOCollectPerBuyer attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ReqPOCollectPerPurchAgreement name="ReqPOCollectPerPurchAgreement">ReqPOCollectPerPurchAgreement</a>

First included in: Parameter/ReqParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReqPOCollectPerPurchAgreement attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ReqPOCollectPerVendor name="ReqPOCollectPerVendor">ReqPOCollectPerVendor</a>

First included in: Parameter/ReqParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReqPOCollectPerVendor attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ReqPOSearchPurchAgreement name="ReqPOSearchPurchAgreement">ReqPOSearchPurchAgreement</a>

First included in: Parameter/ReqParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReqPOSearchPurchAgreement attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ReqSearchTradeAgreement name="ReqSearchTradeAgreement">ReqSearchTradeAgreement</a>

First included in: Parameter/ReqParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReqSearchTradeAgreement attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ReqSearchTradeMethod name="ReqSearchTradeMethod">ReqSearchTradeMethod</a>

First included in: Parameter/ReqParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReqSearchTradeMethod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ReqTimeFutures name="ReqTimeFutures">ReqTimeFutures</a>

First included in: Parameter/ReqParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Start time for calculating delays</td></tr><tr><td>dataFormat</td><td>time</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReqTimeFutures attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Start time for calculating delays</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.time**  
</details>

### <a href=#ReqTimePoDefault name="ReqTimePoDefault">ReqTimePoDefault</a>

First included in: Parameter/ReqParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReqTimePoDefault attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
</details>

### <a href=#StandardReqGroupId name="StandardReqGroupId">StandardReqGroupId</a>

First included in: Parameter/ReqParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>General coverage group</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StandardReqGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>General coverage group</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TodaysdateCalendarId name="TodaysdateCalendarId">TodaysdateCalendarId</a>

First included in: Parameter/ReqParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Today's date calendar</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TodaysdateCalendarId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Today's date calendar</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseCache name="UseCache">UseCache</a>

First included in: Parameter/ReqParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseCache attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ItemFilterPreUpdate name="ItemFilterPreUpdate">ItemFilterPreUpdate</a>

First included in: Parameter/ReqParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Pre-processing: Automatically filter by items with direct demand</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemFilterPreUpdate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Pre-processing: Automatically filter by items with direct demand</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ItemFilterPreCoverage name="ItemFilterPreCoverage">ItemFilterPreCoverage</a>

First included in: Parameter/ReqParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Post-processing: Automatically filter by items with direct demand</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemFilterPreCoverage attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Post-processing: Automatically filter by items with direct demand</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ReqInactive name="ReqInactive">ReqInactive</a>

First included in: Parameter/ReqParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Disable all planning processes</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReqInactive attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Disable all planning processes</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#FirmingBundleSize name="FirmingBundleSize">FirmingBundleSize</a>

First included in: Parameter/ReqParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FirmingBundleSize attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#SkipPreallocatingRecIds name="SkipPreallocatingRecIds">SkipPreallocatingRecIds</a>

First included in: Parameter/ReqParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SkipPreallocatingRecIds attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PreallocatedRecIdBlockSize name="PreallocatedRecIdBlockSize">PreallocatedRecIdBlockSize</a>

First included in: Parameter/ReqParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PreallocatedRecIdBlockSize attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AccurateOpSchedFiniteCapacity name="AccurateOpSchedFiniteCapacity">AccurateOpSchedFiniteCapacity</a>

First included in: Parameter/ReqParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Accurate finite capacity for Operation Scheduling</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccurateOpSchedFiniteCapacity attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Accurate finite capacity for Operation Scheduling</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#DefaultNumberOfThreads name="DefaultNumberOfThreads">DefaultNumberOfThreads</a>

First included in: Parameter/ReqParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Number of threads</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultNumberOfThreads attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Number of threads</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ReqCalcTimeoutInMinutes name="ReqCalcTimeoutInMinutes">ReqCalcTimeoutInMinutes</a>

First included in: Parameter/ReqParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Planning process timeout in minutes.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReqCalcTimeoutInMinutes attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Planning process timeout in minutes.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#PriceType_IN name="PriceType_IN">PriceType_IN</a>

First included in: Parameter/ReqParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceType_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TransferType_IN name="TransferType_IN">TransferType_IN</a>

First included in: Parameter/ReqParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferType_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Parameter/ReqParameters (this entity)  

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

### <a href=#Relationship_CurrentDynamicMasterPlanRelationshipId name="Relationship_CurrentDynamicMasterPlanRelationshipId">Relationship_CurrentDynamicMasterPlanRelationshipId</a>

First included in: Parameter/ReqParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CurrentDynamicMasterPlanRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/ReqPlanSched.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/MasterPlanning/Group/ReqPlanSched.cdm.json/ReqPlanSched</a></td><td><a href="../Group/ReqPlanSched.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CurrentForecastPlanRelationshipId name="Relationship_CurrentForecastPlanRelationshipId">Relationship_CurrentForecastPlanRelationshipId</a>

First included in: Parameter/ReqParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CurrentForecastPlanRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/ReqPlanForecast.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/MasterPlanning/Group/ReqPlanForecast.cdm.json/ReqPlanForecast</a></td><td><a href="../Group/ReqPlanForecast.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CurrentStaticMasterPlanRelationshipId name="Relationship_CurrentStaticMasterPlanRelationshipId">Relationship_CurrentStaticMasterPlanRelationshipId</a>

First included in: Parameter/ReqParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CurrentStaticMasterPlanRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/ReqPlanSched.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/MasterPlanning/Group/ReqPlanSched.cdm.json/ReqPlanSched</a></td><td><a href="../Group/ReqPlanSched.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ReqGroupRelationshipId name="Relationship_ReqGroupRelationshipId">Relationship_ReqGroupRelationshipId</a>

First included in: Parameter/ReqParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReqGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/ReqGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/MasterPlanning/Group/ReqGroup.cdm.json/ReqGroup</a></td><td><a href="../Group/ReqGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TodaysDateWorkCalendarTableRelationshipId name="Relationship_TodaysDateWorkCalendarTableRelationshipId">Relationship_TodaysDateWorkCalendarTableRelationshipId</a>

First included in: Parameter/ReqParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TodaysDateWorkCalendarTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProductionControl/Group/WorkCalendarTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/Group/WorkCalendarTable.cdm.json/WorkCalendarTable</a></td><td><a href="../../ProductionControl/Group/WorkCalendarTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Parameter/ReqParameters (this entity)  

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
