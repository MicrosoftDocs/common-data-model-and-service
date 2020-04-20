---
title: SysClientPerf - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# SysClientPerf

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/System/SystemAdministration/Framework/SysClientPerf.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[SysClientPerf/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="SysClientPerf.md" target="_blank">Framework/SysClientPerf</a>|
|[AutomaticEnhancedPreviewsEnabled](#AutomaticEnhancedPreviewsEnabled)||<a href="SysClientPerf.md" target="_blank">Framework/SysClientPerf</a>|
|[CurrentVersion](#CurrentVersion)||<a href="SysClientPerf.md" target="_blank">Framework/SysClientPerf</a>|
|[FactBoxesEnabled](#FactBoxesEnabled)||<a href="SysClientPerf.md" target="_blank">Framework/SysClientPerf</a>|
|[FactBoxQueryTimeout](#FactBoxQueryTimeout)||<a href="SysClientPerf.md" target="_blank">Framework/SysClientPerf</a>|
|[TileCountEnabled](#TileCountEnabled)||<a href="SysClientPerf.md" target="_blank">Framework/SysClientPerf</a>|
|[MaxNumberOfTopLevelForms](#MaxNumberOfTopLevelForms)||<a href="SysClientPerf.md" target="_blank">Framework/SysClientPerf</a>|
|[AllowPersonalization](#AllowPersonalization)||<a href="SysClientPerf.md" target="_blank">Framework/SysClientPerf</a>|
|[MaxNumberOfNestedWaitCalls](#MaxNumberOfNestedWaitCalls)||<a href="SysClientPerf.md" target="_blank">Framework/SysClientPerf</a>|
|[AllowRemotePartExecution](#AllowRemotePartExecution)||<a href="SysClientPerf.md" target="_blank">Framework/SysClientPerf</a>|
|[AllowAsyncSandboxExecution](#AllowAsyncSandboxExecution)||<a href="SysClientPerf.md" target="_blank">Framework/SysClientPerf</a>|
|[MaxNumberOfStickyWebSessionsPerUser](#MaxNumberOfStickyWebSessionsPerUser)||<a href="SysClientPerf.md" target="_blank">Framework/SysClientPerf</a>|
|[MaxNumberOfServicesSessionsPerUser](#MaxNumberOfServicesSessionsPerUser)||<a href="SysClientPerf.md" target="_blank">Framework/SysClientPerf</a>|
|[AllowRecursionDepthValidation](#AllowRecursionDepthValidation)||<a href="SysClientPerf.md" target="_blank">Framework/SysClientPerf</a>|
|[MaxNumberOfRecursionDepthPerSession](#MaxNumberOfRecursionDepthPerSession)||<a href="SysClientPerf.md" target="_blank">Framework/SysClientPerf</a>|
|[MaxNumberOfRecursionDepthPerSessionForBatch](#MaxNumberOfRecursionDepthPerSessionForBatch)||<a href="SysClientPerf.md" target="_blank">Framework/SysClientPerf</a>|
|[DocumentHandlingCountEnabled](#DocumentHandlingCountEnabled)||<a href="SysClientPerf.md" target="_blank">Framework/SysClientPerf</a>|
|[SkypeEnabled](#SkypeEnabled)||<a href="SysClientPerf.md" target="_blank">Framework/SysClientPerf</a>|
|[ClientConnectivityEnabled](#ClientConnectivityEnabled)||<a href="SysClientPerf.md" target="_blank">Framework/SysClientPerf</a>|
|[LastValueUserConnection](#LastValueUserConnection)||<a href="SysClientPerf.md" target="_blank">Framework/SysClientPerf</a>|
|[TransactionLogUserConnection](#TransactionLogUserConnection)||<a href="SysClientPerf.md" target="_blank">Framework/SysClientPerf</a>|
|[AllowStickyGridDefaultAction](#AllowStickyGridDefaultAction)||<a href="SysClientPerf.md" target="_blank">Framework/SysClientPerf</a>|
|[MaxNumberOfStaticExportRows](#MaxNumberOfStaticExportRows)||<a href="SysClientPerf.md" target="_blank">Framework/SysClientPerf</a>|
|[OptimizedIsOneOfFiltering](#OptimizedIsOneOfFiltering)||<a href="SysClientPerf.md" target="_blank">Framework/SysClientPerf</a>|
|[FeatureCalloutEnabled](#FeatureCalloutEnabled)||<a href="SysClientPerf.md" target="_blank">Framework/SysClientPerf</a>|
|[LegacyNavBar](#LegacyNavBar)||<a href="SysClientPerf.md" target="_blank">Framework/SysClientPerf</a>|
|[DeferredDeletionEnabled](#DeferredDeletionEnabled)||<a href="SysClientPerf.md" target="_blank">Framework/SysClientPerf</a>|
|[NumDaysToDeferDeletion](#NumDaysToDeferDeletion)||<a href="SysClientPerf.md" target="_blank">Framework/SysClientPerf</a>|
|[MaxNumberOfReactGridRows](#MaxNumberOfReactGridRows)||<a href="SysClientPerf.md" target="_blank">Framework/SysClientPerf</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Framework/SysClientPerf (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[SysClientPerf/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AutomaticEnhancedPreviewsEnabled name="AutomaticEnhancedPreviewsEnabled">AutomaticEnhancedPreviewsEnabled</a>

First included in: Framework/SysClientPerf (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AutomaticEnhancedPreviewsEnabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CurrentVersion name="CurrentVersion">CurrentVersion</a>

First included in: Framework/SysClientPerf (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrentVersion attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#FactBoxesEnabled name="FactBoxesEnabled">FactBoxesEnabled</a>

First included in: Framework/SysClientPerf (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FactBoxesEnabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#FactBoxQueryTimeout name="FactBoxQueryTimeout">FactBoxQueryTimeout</a>

First included in: Framework/SysClientPerf (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FactBoxQueryTimeout attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TileCountEnabled name="TileCountEnabled">TileCountEnabled</a>

First included in: Framework/SysClientPerf (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TileCountEnabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MaxNumberOfTopLevelForms name="MaxNumberOfTopLevelForms">MaxNumberOfTopLevelForms</a>

First included in: Framework/SysClientPerf (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxNumberOfTopLevelForms attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AllowPersonalization name="AllowPersonalization">AllowPersonalization</a>

First included in: Framework/SysClientPerf (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowPersonalization attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MaxNumberOfNestedWaitCalls name="MaxNumberOfNestedWaitCalls">MaxNumberOfNestedWaitCalls</a>

First included in: Framework/SysClientPerf (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxNumberOfNestedWaitCalls attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AllowRemotePartExecution name="AllowRemotePartExecution">AllowRemotePartExecution</a>

First included in: Framework/SysClientPerf (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowRemotePartExecution attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AllowAsyncSandboxExecution name="AllowAsyncSandboxExecution">AllowAsyncSandboxExecution</a>

First included in: Framework/SysClientPerf (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowAsyncSandboxExecution attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MaxNumberOfStickyWebSessionsPerUser name="MaxNumberOfStickyWebSessionsPerUser">MaxNumberOfStickyWebSessionsPerUser</a>

First included in: Framework/SysClientPerf (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxNumberOfStickyWebSessionsPerUser attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MaxNumberOfServicesSessionsPerUser name="MaxNumberOfServicesSessionsPerUser">MaxNumberOfServicesSessionsPerUser</a>

First included in: Framework/SysClientPerf (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxNumberOfServicesSessionsPerUser attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AllowRecursionDepthValidation name="AllowRecursionDepthValidation">AllowRecursionDepthValidation</a>

First included in: Framework/SysClientPerf (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowRecursionDepthValidation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MaxNumberOfRecursionDepthPerSession name="MaxNumberOfRecursionDepthPerSession">MaxNumberOfRecursionDepthPerSession</a>

First included in: Framework/SysClientPerf (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxNumberOfRecursionDepthPerSession attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MaxNumberOfRecursionDepthPerSessionForBatch name="MaxNumberOfRecursionDepthPerSessionForBatch">MaxNumberOfRecursionDepthPerSessionForBatch</a>

First included in: Framework/SysClientPerf (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxNumberOfRecursionDepthPerSessionForBatch attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DocumentHandlingCountEnabled name="DocumentHandlingCountEnabled">DocumentHandlingCountEnabled</a>

First included in: Framework/SysClientPerf (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentHandlingCountEnabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SkypeEnabled name="SkypeEnabled">SkypeEnabled</a>

First included in: Framework/SysClientPerf (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SkypeEnabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ClientConnectivityEnabled name="ClientConnectivityEnabled">ClientConnectivityEnabled</a>

First included in: Framework/SysClientPerf (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClientConnectivityEnabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LastValueUserConnection name="LastValueUserConnection">LastValueUserConnection</a>

First included in: Framework/SysClientPerf (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LastValueUserConnection attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TransactionLogUserConnection name="TransactionLogUserConnection">TransactionLogUserConnection</a>

First included in: Framework/SysClientPerf (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionLogUserConnection attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AllowStickyGridDefaultAction name="AllowStickyGridDefaultAction">AllowStickyGridDefaultAction</a>

First included in: Framework/SysClientPerf (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowStickyGridDefaultAction attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MaxNumberOfStaticExportRows name="MaxNumberOfStaticExportRows">MaxNumberOfStaticExportRows</a>

First included in: Framework/SysClientPerf (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxNumberOfStaticExportRows attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#OptimizedIsOneOfFiltering name="OptimizedIsOneOfFiltering">OptimizedIsOneOfFiltering</a>

First included in: Framework/SysClientPerf (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OptimizedIsOneOfFiltering attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#FeatureCalloutEnabled name="FeatureCalloutEnabled">FeatureCalloutEnabled</a>

First included in: Framework/SysClientPerf (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FeatureCalloutEnabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LegacyNavBar name="LegacyNavBar">LegacyNavBar</a>

First included in: Framework/SysClientPerf (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LegacyNavBar attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DeferredDeletionEnabled name="DeferredDeletionEnabled">DeferredDeletionEnabled</a>

First included in: Framework/SysClientPerf (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeferredDeletionEnabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#NumDaysToDeferDeletion name="NumDaysToDeferDeletion">NumDaysToDeferDeletion</a>

First included in: Framework/SysClientPerf (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumDaysToDeferDeletion attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MaxNumberOfReactGridRows name="MaxNumberOfReactGridRows">MaxNumberOfReactGridRows</a>

First included in: Framework/SysClientPerf (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxNumberOfReactGridRows attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>
