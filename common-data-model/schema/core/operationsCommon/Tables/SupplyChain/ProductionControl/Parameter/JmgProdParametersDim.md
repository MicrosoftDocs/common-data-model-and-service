---
title: JmgProdParametersDim in Parameter - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/13/2020
ms.author: nebanfic
---

# Manufacturing execution production parameters in Parameter(JmgProdParametersDim)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/ProductionControl/Parameter/JmgProdParametersDim.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[JmgProdParametersDim/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Manufacturing execution production parameters</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[StartUpRouteJournalNameId](#StartUpRouteJournalNameId)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[AllowProdOverlap](#AllowProdOverlap)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[AllowProdProcess](#AllowProdProcess)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[AllowProdQueueAfter](#AllowProdQueueAfter)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[AllowProdQueueBefore](#AllowProdQueueBefore)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[AllowProdSetup](#AllowProdSetup)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[AllowProdTransport](#AllowProdTransport)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[AssistantsUseSecondaryOperations](#AssistantsUseSecondaryOperations)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[BOMEditJournal](#BOMEditJournal)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[BOMJournalName](#BOMJournalName)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[BOMPostAutomatically](#BOMPostAutomatically)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[CostUseStandardCost](#CostUseStandardCost)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[FeedbackAcceptOverDelivery](#FeedbackAcceptOverDelivery)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[FeedbackAcceptUnderDelivery](#FeedbackAcceptUnderDelivery)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[FeedbackOverDeliveryPercentage](#FeedbackOverDeliveryPercentage)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[FeedbackUnderDeliveryPercentage](#FeedbackUnderDeliveryPercentage)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[FeedbackValidateMethod](#FeedbackValidateMethod)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[InventDimId](#InventDimId)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[MaxQty](#MaxQty)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[PostTimeAutomatically](#PostTimeAutomatically)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[ProdDimensionFrom](#ProdDimensionFrom)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[ReportFinishAcceptError](#ReportFinishAcceptError)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[ReportFinishBOMAutoConsump](#ReportFinishBOMAutoConsump)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[ReportFinishBOMJournalNameId](#ReportFinishBOMJournalNameId)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[ReportFinishEndJob](#ReportFinishEndJob)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[ReportFinishEndPicklist](#ReportFinishEndPicklist)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[ReportFinishEndRouteCard](#ReportFinishEndRouteCard)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[ReportFinishProdJournalNameId](#ReportFinishProdJournalNameId)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[ReportFinishRouteAutoConsump](#ReportFinishRouteAutoConsump)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[ReportFinishRouteJournalNameId](#ReportFinishRouteJournalNameId)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[ReportFinishStatus](#ReportFinishStatus)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[ReportFinishUseSFCParameters](#ReportFinishUseSFCParameters)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[StartupAcceptOverDelivery](#StartupAcceptOverDelivery)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[StartUpBOMAutoConsump](#StartUpBOMAutoConsump)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[StartUpBomJournalNameId](#StartUpBomJournalNameId)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[StartUpBOMJournalSplit](#StartUpBOMJournalSplit)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[StartUpCompletePickListJournal](#StartUpCompletePickListJournal)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[StartUpDrawNegative](#StartUpDrawNegative)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[StartUpEndPicklist](#StartUpEndPicklist)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[StartUpEndRouteCard](#StartUpEndRouteCard)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[StartupOverDeliveryPercentage](#StartupOverDeliveryPercentage)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[StartUpPostNowBOM](#StartUpPostNowBOM)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[StartUpPostNowRoute](#StartUpPostNowRoute)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[StartUpProduction](#StartUpProduction)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[StartUpReducePhysical](#StartUpReducePhysical)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[StartUpReferences](#StartUpReferences)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[StartUpRouteAutoConsump](#StartUpRouteAutoConsump)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[StartUpShowOpenBOM](#StartUpShowOpenBOM)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[StartUpStatus](#StartUpStatus)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[StartUpUseSFCParameters](#StartUpUseSFCParameters)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[StartupValidateMethod](#StartupValidateMethod)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[StatusQtyAutoConsump](#StatusQtyAutoConsump)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[StatusQtyJournalNameId](#StatusQtyJournalNameId)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[StatusQtyPostAutomatically](#StatusQtyPostAutomatically)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[TimeProdJournalNameId](#TimeProdJournalNameId)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[ValidateFeedbackQuantity](#ValidateFeedbackQuantity)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[ValidateStartupQuantity](#ValidateStartupQuantity)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[DataAreaId](#DataAreaId)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[Relationship_BOMProdJournalNameRelationshipId](#Relationship_BOMProdJournalNameRelationshipId)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[Relationship_InventDimRelationshipId](#Relationship_InventDimRelationshipId)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[Relationship_ReportAsFinishedPickingProdJournalNameRelationshipId](#Relationship_ReportAsFinishedPickingProdJournalNameRelationshipId)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[Relationship_ReportAsFinishedProdJournalNameRelationshipId](#Relationship_ReportAsFinishedProdJournalNameRelationshipId)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[Relationship_ReportAsFinishedRouteProdJournalNameRelationshipId](#Relationship_ReportAsFinishedRouteProdJournalNameRelationshipId)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[Relationship_RouteConsumptionJournalRelationshipId](#Relationship_RouteConsumptionJournalRelationshipId)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[Relationship_StartUpPickingProdJournalNameRelationshipId](#Relationship_StartUpPickingProdJournalNameRelationshipId)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[Relationship_StartUpRouteProdJournalNameRelationshipId](#Relationship_StartUpRouteProdJournalNameRelationshipId)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[Relationship_TimeJournalRelationshipId](#Relationship_TimeJournalRelationshipId)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="JmgProdParametersDim.md" target="_blank">Parameter/JmgProdParametersDim</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[JmgProdParametersDim/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#StartUpRouteJournalNameId name="StartUpRouteJournalNameId">StartUpRouteJournalNameId</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartUpRouteJournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowProdOverlap name="AllowProdOverlap">AllowProdOverlap</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Overlap</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowProdOverlap attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Overlap</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#AllowProdProcess name="AllowProdProcess">AllowProdProcess</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowProdProcess attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Process</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#AllowProdQueueAfter name="AllowProdQueueAfter">AllowProdQueueAfter</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Queue after</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowProdQueueAfter attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Queue after</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#AllowProdQueueBefore name="AllowProdQueueBefore">AllowProdQueueBefore</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Queue before</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowProdQueueBefore attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Queue before</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#AllowProdSetup name="AllowProdSetup">AllowProdSetup</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Setup</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowProdSetup attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Setup</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#AllowProdTransport name="AllowProdTransport">AllowProdTransport</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transport</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowProdTransport attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Transport</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#AssistantsUseSecondaryOperations name="AssistantsUseSecondaryOperations">AssistantsUseSecondaryOperations</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Assistants use secondary operations</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssistantsUseSecondaryOperations attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Assistants use secondary operations</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#BOMEditJournal name="BOMEditJournal">BOMEditJournal</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BOMEditJournal attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#BOMJournalName name="BOMJournalName">BOMJournalName</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BOMJournalName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BOMPostAutomatically name="BOMPostAutomatically">BOMPostAutomatically</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BOMPostAutomatically attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CostUseStandardCost name="CostUseStandardCost">CostUseStandardCost</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cost category</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostUseStandardCost attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Cost category</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#FeedbackAcceptOverDelivery name="FeedbackAcceptOverDelivery">FeedbackAcceptOverDelivery</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Accept surplus production</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FeedbackAcceptOverDelivery attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Accept surplus production</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#FeedbackAcceptUnderDelivery name="FeedbackAcceptUnderDelivery">FeedbackAcceptUnderDelivery</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Accept production shortage</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FeedbackAcceptUnderDelivery attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Accept production shortage</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#FeedbackOverDeliveryPercentage name="FeedbackOverDeliveryPercentage">FeedbackOverDeliveryPercentage</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Accepted surplus in percentage</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FeedbackOverDeliveryPercentage attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Accepted surplus in percentage</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#FeedbackUnderDeliveryPercentage name="FeedbackUnderDeliveryPercentage">FeedbackUnderDeliveryPercentage</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Accepted shortage in percentage</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FeedbackUnderDeliveryPercentage attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Accepted shortage in percentage</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#FeedbackValidateMethod name="FeedbackValidateMethod">FeedbackValidateMethod</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FeedbackValidateMethod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#InventDimId name="InventDimId">InventDimId</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventDimId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaxQty name="MaxQty">MaxQty</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Maximum report quantity</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Maximum report quantity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PostTimeAutomatically name="PostTimeAutomatically">PostTimeAutomatically</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostTimeAutomatically attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ProdDimensionFrom name="ProdDimensionFrom">ProdDimensionFrom</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Dimension</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProdDimensionFrom attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Dimension</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ReportFinishAcceptError name="ReportFinishAcceptError">ReportFinishAcceptError</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Accept error</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportFinishAcceptError attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Accept error</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ReportFinishBOMAutoConsump name="ReportFinishBOMAutoConsump">ReportFinishBOMAutoConsump</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportFinishBOMAutoConsump attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ReportFinishBOMJournalNameId name="ReportFinishBOMJournalNameId">ReportFinishBOMJournalNameId</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportFinishBOMJournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportFinishEndJob name="ReportFinishEndJob">ReportFinishEndJob</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportFinishEndJob attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ReportFinishEndPicklist name="ReportFinishEndPicklist">ReportFinishEndPicklist</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportFinishEndPicklist attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ReportFinishEndRouteCard name="ReportFinishEndRouteCard">ReportFinishEndRouteCard</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportFinishEndRouteCard attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ReportFinishProdJournalNameId name="ReportFinishProdJournalNameId">ReportFinishProdJournalNameId</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportFinishProdJournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportFinishRouteAutoConsump name="ReportFinishRouteAutoConsump">ReportFinishRouteAutoConsump</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportFinishRouteAutoConsump attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ReportFinishRouteJournalNameId name="ReportFinishRouteJournalNameId">ReportFinishRouteJournalNameId</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportFinishRouteJournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportFinishStatus name="ReportFinishStatus">ReportFinishStatus</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportFinishStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ReportFinishUseSFCParameters name="ReportFinishUseSFCParameters">ReportFinishUseSFCParameters</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportFinishUseSFCParameters attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#StartupAcceptOverDelivery name="StartupAcceptOverDelivery">StartupAcceptOverDelivery</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Accept startup deviation</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartupAcceptOverDelivery attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Accept startup deviation</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#StartUpBOMAutoConsump name="StartUpBOMAutoConsump">StartUpBOMAutoConsump</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartUpBOMAutoConsump attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#StartUpBomJournalNameId name="StartUpBomJournalNameId">StartUpBomJournalNameId</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartUpBomJournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StartUpBOMJournalSplit name="StartUpBOMJournalSplit">StartUpBOMJournalSplit</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartUpBOMJournalSplit attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#StartUpCompletePickListJournal name="StartUpCompletePickListJournal">StartUpCompletePickListJournal</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Complete picking list journal</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartUpCompletePickListJournal attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Complete picking list journal</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#StartUpDrawNegative name="StartUpDrawNegative">StartUpDrawNegative</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartUpDrawNegative attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#StartUpEndPicklist name="StartUpEndPicklist">StartUpEndPicklist</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartUpEndPicklist attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#StartUpEndRouteCard name="StartUpEndRouteCard">StartUpEndRouteCard</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartUpEndRouteCard attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#StartupOverDeliveryPercentage name="StartupOverDeliveryPercentage">StartupOverDeliveryPercentage</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Accepted deviation in percentage</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartupOverDeliveryPercentage attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Accepted deviation in percentage</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#StartUpPostNowBOM name="StartUpPostNowBOM">StartUpPostNowBOM</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartUpPostNowBOM attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#StartUpPostNowRoute name="StartUpPostNowRoute">StartUpPostNowRoute</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartUpPostNowRoute attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#StartUpProduction name="StartUpProduction">StartUpProduction</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Start production</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartUpProduction attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Start production</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#StartUpReducePhysical name="StartUpReducePhysical">StartUpReducePhysical</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartUpReducePhysical attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#StartUpReferences name="StartUpReferences">StartUpReferences</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartUpReferences attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#StartUpRouteAutoConsump name="StartUpRouteAutoConsump">StartUpRouteAutoConsump</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartUpRouteAutoConsump attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#StartUpShowOpenBOM name="StartUpShowOpenBOM">StartUpShowOpenBOM</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartUpShowOpenBOM attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#StartUpStatus name="StartUpStatus">StartUpStatus</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Update start on-line</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartUpStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Update start on-line</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#StartUpUseSFCParameters name="StartUpUseSFCParameters">StartUpUseSFCParameters</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartUpUseSFCParameters attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#StartupValidateMethod name="StartupValidateMethod">StartupValidateMethod</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartupValidateMethod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#StatusQtyAutoConsump name="StatusQtyAutoConsump">StatusQtyAutoConsump</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StatusQtyAutoConsump attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#StatusQtyJournalNameId name="StatusQtyJournalNameId">StatusQtyJournalNameId</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Route consumption journal</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StatusQtyJournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Route consumption journal</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StatusQtyPostAutomatically name="StatusQtyPostAutomatically">StatusQtyPostAutomatically</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StatusQtyPostAutomatically attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TimeProdJournalNameId name="TimeProdJournalNameId">TimeProdJournalNameId</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time journal</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeProdJournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Time journal</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidateFeedbackQuantity name="ValidateFeedbackQuantity">ValidateFeedbackQuantity</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Validate feedback quantity</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidateFeedbackQuantity attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Validate feedback quantity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ValidateStartupQuantity name="ValidateStartupQuantity">ValidateStartupQuantity</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Validate startup quantities</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidateStartupQuantity attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Validate startup quantities</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

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

### <a href=#Relationship_BOMProdJournalNameRelationshipId name="Relationship_BOMProdJournalNameRelationshipId">Relationship_BOMProdJournalNameRelationshipId</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BOMProdJournalNameRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/ProdJournalName.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/Group/ProdJournalName.cdm.json/ProdJournalName</a></td><td><a href="../Group/ProdJournalName.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventDimRelationshipId name="Relationship_InventDimRelationshipId">Relationship_InventDimRelationshipId</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventDimRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Inventory/Main/InventDim.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/InventDim.cdm.json/InventDim</a></td><td><a href="../../Inventory/Main/InventDim.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ReportAsFinishedPickingProdJournalNameRelationshipId name="Relationship_ReportAsFinishedPickingProdJournalNameRelationshipId">Relationship_ReportAsFinishedPickingProdJournalNameRelationshipId</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReportAsFinishedPickingProdJournalNameRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/ProdJournalName.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/Group/ProdJournalName.cdm.json/ProdJournalName</a></td><td><a href="../Group/ProdJournalName.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ReportAsFinishedProdJournalNameRelationshipId name="Relationship_ReportAsFinishedProdJournalNameRelationshipId">Relationship_ReportAsFinishedProdJournalNameRelationshipId</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReportAsFinishedProdJournalNameRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/ProdJournalName.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/Group/ProdJournalName.cdm.json/ProdJournalName</a></td><td><a href="../Group/ProdJournalName.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ReportAsFinishedRouteProdJournalNameRelationshipId name="Relationship_ReportAsFinishedRouteProdJournalNameRelationshipId">Relationship_ReportAsFinishedRouteProdJournalNameRelationshipId</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReportAsFinishedRouteProdJournalNameRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/ProdJournalName.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/Group/ProdJournalName.cdm.json/ProdJournalName</a></td><td><a href="../Group/ProdJournalName.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RouteConsumptionJournalRelationshipId name="Relationship_RouteConsumptionJournalRelationshipId">Relationship_RouteConsumptionJournalRelationshipId</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RouteConsumptionJournalRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/ProdJournalName.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/Group/ProdJournalName.cdm.json/ProdJournalName</a></td><td><a href="../Group/ProdJournalName.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_StartUpPickingProdJournalNameRelationshipId name="Relationship_StartUpPickingProdJournalNameRelationshipId">Relationship_StartUpPickingProdJournalNameRelationshipId</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_StartUpPickingProdJournalNameRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/ProdJournalName.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/Group/ProdJournalName.cdm.json/ProdJournalName</a></td><td><a href="../Group/ProdJournalName.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_StartUpRouteProdJournalNameRelationshipId name="Relationship_StartUpRouteProdJournalNameRelationshipId">Relationship_StartUpRouteProdJournalNameRelationshipId</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_StartUpRouteProdJournalNameRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/ProdJournalName.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/Group/ProdJournalName.cdm.json/ProdJournalName</a></td><td><a href="../Group/ProdJournalName.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TimeJournalRelationshipId name="Relationship_TimeJournalRelationshipId">Relationship_TimeJournalRelationshipId</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TimeJournalRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/ProdJournalName.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/Group/ProdJournalName.cdm.json/ProdJournalName</a></td><td><a href="../Group/ProdJournalName.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Parameter/JmgProdParametersDim (this entity)  

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
