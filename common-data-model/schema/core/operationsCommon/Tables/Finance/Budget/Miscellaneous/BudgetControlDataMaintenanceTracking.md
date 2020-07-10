---
title: BudgetControlDataMaintenanceTracking in Miscellaneous - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/10/2020
ms.author: nebanfic
---

# Budget control data maintenance documents in Miscellaneous(BudgetControlDataMaintenanceTracking)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Budget/Miscellaneous/BudgetControlDataMaintenanceTracking.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BudgetControlDataMaintenanceTracking/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Budget control data maintenance documents</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="BudgetControlDataMaintenanceTracking.md" target="_blank">Miscellaneous/BudgetControlDataMaintenanceTracking</a>|
|[BudgetControlDataMaintenance](#BudgetControlDataMaintenance)||<a href="BudgetControlDataMaintenanceTracking.md" target="_blank">Miscellaneous/BudgetControlDataMaintenanceTracking</a>|
|[DataMaintenanceProvider](#DataMaintenanceProvider)||<a href="BudgetControlDataMaintenanceTracking.md" target="_blank">Miscellaneous/BudgetControlDataMaintenanceTracking</a>|
|[DataMaintenanceProviderDescription](#DataMaintenanceProviderDescription)||<a href="BudgetControlDataMaintenanceTracking.md" target="_blank">Miscellaneous/BudgetControlDataMaintenanceTracking</a>|
|[DataMaintenanceProviderDetectionDateTime](#DataMaintenanceProviderDetectionDateTime)||<a href="BudgetControlDataMaintenanceTracking.md" target="_blank">Miscellaneous/BudgetControlDataMaintenanceTracking</a>|
|[DataMaintenanceProviderName](#DataMaintenanceProviderName)||<a href="BudgetControlDataMaintenanceTracking.md" target="_blank">Miscellaneous/BudgetControlDataMaintenanceTracking</a>|
|[OriginatingTrackingNumber](#OriginatingTrackingNumber)||<a href="BudgetControlDataMaintenanceTracking.md" target="_blank">Miscellaneous/BudgetControlDataMaintenanceTracking</a>|
|[OriginatingTrackingSourceIntegrator](#OriginatingTrackingSourceIntegrator)||<a href="BudgetControlDataMaintenanceTracking.md" target="_blank">Miscellaneous/BudgetControlDataMaintenanceTracking</a>|
|[ProcessCheckResult](#ProcessCheckResult)||<a href="BudgetControlDataMaintenanceTracking.md" target="_blank">Miscellaneous/BudgetControlDataMaintenanceTracking</a>|
|[ProcessStatus](#ProcessStatus)||<a href="BudgetControlDataMaintenanceTracking.md" target="_blank">Miscellaneous/BudgetControlDataMaintenanceTracking</a>|
|[Selected](#Selected)||<a href="BudgetControlDataMaintenanceTracking.md" target="_blank">Miscellaneous/BudgetControlDataMaintenanceTracking</a>|
|[TrackingDocument](#TrackingDocument)||<a href="BudgetControlDataMaintenanceTracking.md" target="_blank">Miscellaneous/BudgetControlDataMaintenanceTracking</a>|
|[TrackingNumber](#TrackingNumber)||<a href="BudgetControlDataMaintenanceTracking.md" target="_blank">Miscellaneous/BudgetControlDataMaintenanceTracking</a>|
|[TrackingSourceIntegrator](#TrackingSourceIntegrator)||<a href="BudgetControlDataMaintenanceTracking.md" target="_blank">Miscellaneous/BudgetControlDataMaintenanceTracking</a>|
|[TrackingStatus](#TrackingStatus)||<a href="BudgetControlDataMaintenanceTracking.md" target="_blank">Miscellaneous/BudgetControlDataMaintenanceTracking</a>|
|[Relationship_BudgetControlDataMaintenanceRelationshipId](#Relationship_BudgetControlDataMaintenanceRelationshipId)||<a href="BudgetControlDataMaintenanceTracking.md" target="_blank">Miscellaneous/BudgetControlDataMaintenanceTracking</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/BudgetControlDataMaintenanceTracking (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BudgetControlDataMaintenanceTracking/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BudgetControlDataMaintenance name="BudgetControlDataMaintenance">BudgetControlDataMaintenance</a>

First included in: Miscellaneous/BudgetControlDataMaintenanceTracking (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetControlDataMaintenance attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DataMaintenanceProvider name="DataMaintenanceProvider">DataMaintenanceProvider</a>

First included in: Miscellaneous/BudgetControlDataMaintenanceTracking (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Scenario</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataMaintenanceProvider attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Scenario</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataMaintenanceProviderDescription name="DataMaintenanceProviderDescription">DataMaintenanceProviderDescription</a>

First included in: Miscellaneous/BudgetControlDataMaintenanceTracking (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataMaintenanceProviderDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataMaintenanceProviderDetectionDateTime name="DataMaintenanceProviderDetectionDateTime">DataMaintenanceProviderDetectionDateTime</a>

First included in: Miscellaneous/BudgetControlDataMaintenanceTracking (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Date found</td></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataMaintenanceProviderDetectionDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date found</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.date**  
</details>

### <a href=#DataMaintenanceProviderName name="DataMaintenanceProviderName">DataMaintenanceProviderName</a>

First included in: Miscellaneous/BudgetControlDataMaintenanceTracking (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Scenario name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataMaintenanceProviderName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Scenario name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OriginatingTrackingNumber name="OriginatingTrackingNumber">OriginatingTrackingNumber</a>

First included in: Miscellaneous/BudgetControlDataMaintenanceTracking (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Originating number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginatingTrackingNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Originating number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OriginatingTrackingSourceIntegrator name="OriginatingTrackingSourceIntegrator">OriginatingTrackingSourceIntegrator</a>

First included in: Miscellaneous/BudgetControlDataMaintenanceTracking (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Originating document type</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginatingTrackingSourceIntegrator attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Originating document type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ProcessCheckResult name="ProcessCheckResult">ProcessCheckResult</a>

First included in: Miscellaneous/BudgetControlDataMaintenanceTracking (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcessCheckResult attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ProcessStatus name="ProcessStatus">ProcessStatus</a>

First included in: Miscellaneous/BudgetControlDataMaintenanceTracking (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcessStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Selected name="Selected">Selected</a>

First included in: Miscellaneous/BudgetControlDataMaintenanceTracking (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Select</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Selected attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Select</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#TrackingDocument name="TrackingDocument">TrackingDocument</a>

First included in: Miscellaneous/BudgetControlDataMaintenanceTracking (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TrackingDocument attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TrackingNumber name="TrackingNumber">TrackingNumber</a>

First included in: Miscellaneous/BudgetControlDataMaintenanceTracking (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TrackingNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TrackingSourceIntegrator name="TrackingSourceIntegrator">TrackingSourceIntegrator</a>

First included in: Miscellaneous/BudgetControlDataMaintenanceTracking (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Document type</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TrackingSourceIntegrator attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Document type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#TrackingStatus name="TrackingStatus">TrackingStatus</a>

First included in: Miscellaneous/BudgetControlDataMaintenanceTracking (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Document status</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TrackingStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Document status</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#Relationship_BudgetControlDataMaintenanceRelationshipId name="Relationship_BudgetControlDataMaintenanceRelationshipId">Relationship_BudgetControlDataMaintenanceRelationshipId</a>

First included in: Miscellaneous/BudgetControlDataMaintenanceTracking (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BudgetControlDataMaintenanceRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="BudgetControlDataMaintenance.md" target="_blank">/core/operationsCommon/Tables/Finance/Budget/Miscellaneous/BudgetControlDataMaintenance.cdm.json/BudgetControlDataMaintenance</a></td><td><a href="BudgetControlDataMaintenance.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
