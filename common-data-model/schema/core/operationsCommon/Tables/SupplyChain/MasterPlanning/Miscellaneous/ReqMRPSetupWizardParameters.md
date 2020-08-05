---
title: ReqMRPSetupWizardParameters in Miscellaneous - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# ReqMRPSetupWizardParameters in Miscellaneous

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/MasterPlanning/Miscellaneous/ReqMRPSetupWizardParameters.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ReqMRPSetupWizardParameters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="ReqMRPSetupWizardParameters.md" target="_blank">Miscellaneous/ReqMRPSetupWizardParameters</a>|
|[IsManufacturer](#IsManufacturer)||<a href="ReqMRPSetupWizardParameters.md" target="_blank">Miscellaneous/ReqMRPSetupWizardParameters</a>|
|[NumberOfItems](#NumberOfItems)||<a href="ReqMRPSetupWizardParameters.md" target="_blank">Miscellaneous/ReqMRPSetupWizardParameters</a>|
|[NumberOfPlannedOrders](#NumberOfPlannedOrders)||<a href="ReqMRPSetupWizardParameters.md" target="_blank">Miscellaneous/ReqMRPSetupWizardParameters</a>|
|[IsFreezeActive](#IsFreezeActive)||<a href="ReqMRPSetupWizardParameters.md" target="_blank">Miscellaneous/ReqMRPSetupWizardParameters</a>|
|[IsForecastPlanActive](#IsForecastPlanActive)||<a href="ReqMRPSetupWizardParameters.md" target="_blank">Miscellaneous/ReqMRPSetupWizardParameters</a>|
|[IsRequisitionsActive](#IsRequisitionsActive)||<a href="ReqMRPSetupWizardParameters.md" target="_blank">Miscellaneous/ReqMRPSetupWizardParameters</a>|
|[IsCapacityActive](#IsCapacityActive)||<a href="ReqMRPSetupWizardParameters.md" target="_blank">Miscellaneous/ReqMRPSetupWizardParameters</a>|
|[IsSequencingActive](#IsSequencingActive)||<a href="ReqMRPSetupWizardParameters.md" target="_blank">Miscellaneous/ReqMRPSetupWizardParameters</a>|
|[IsFirmingActive](#IsFirmingActive)||<a href="ReqMRPSetupWizardParameters.md" target="_blank">Miscellaneous/ReqMRPSetupWizardParameters</a>|
|[IsActionMessageActive](#IsActionMessageActive)||<a href="ReqMRPSetupWizardParameters.md" target="_blank">Miscellaneous/ReqMRPSetupWizardParameters</a>|
|[IsCalculatedDelaysActive](#IsCalculatedDelaysActive)||<a href="ReqMRPSetupWizardParameters.md" target="_blank">Miscellaneous/ReqMRPSetupWizardParameters</a>|
|[IsJobSchedulingActive](#IsJobSchedulingActive)||<a href="ReqMRPSetupWizardParameters.md" target="_blank">Miscellaneous/ReqMRPSetupWizardParameters</a>|
|[MaxBomLevel](#MaxBomLevel)||<a href="ReqMRPSetupWizardParameters.md" target="_blank">Miscellaneous/ReqMRPSetupWizardParameters</a>|
|[IsCoverageOverriden](#IsCoverageOverriden)||<a href="ReqMRPSetupWizardParameters.md" target="_blank">Miscellaneous/ReqMRPSetupWizardParameters</a>|
|[IsExplosionActive](#IsExplosionActive)||<a href="ReqMRPSetupWizardParameters.md" target="_blank">Miscellaneous/ReqMRPSetupWizardParameters</a>|
|[DataAreaId](#DataAreaId)||<a href="ReqMRPSetupWizardParameters.md" target="_blank">Miscellaneous/ReqMRPSetupWizardParameters</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="ReqMRPSetupWizardParameters.md" target="_blank">Miscellaneous/ReqMRPSetupWizardParameters</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/ReqMRPSetupWizardParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ReqMRPSetupWizardParameters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#IsManufacturer name="IsManufacturer">IsManufacturer</a>

First included in: Miscellaneous/ReqMRPSetupWizardParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Manufacturer</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsManufacturer attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Manufacturer</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#NumberOfItems name="NumberOfItems">NumberOfItems</a>

First included in: Miscellaneous/ReqMRPSetupWizardParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Number of items</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberOfItems attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Number of items</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#NumberOfPlannedOrders name="NumberOfPlannedOrders">NumberOfPlannedOrders</a>

First included in: Miscellaneous/ReqMRPSetupWizardParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Number of planned orders</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberOfPlannedOrders attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Number of planned orders</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#IsFreezeActive name="IsFreezeActive">IsFreezeActive</a>

First included in: Miscellaneous/ReqMRPSetupWizardParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Freeze</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsFreezeActive attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Freeze</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#IsForecastPlanActive name="IsForecastPlanActive">IsForecastPlanActive</a>

First included in: Miscellaneous/ReqMRPSetupWizardParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Forecast plan</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsForecastPlanActive attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Forecast plan</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#IsRequisitionsActive name="IsRequisitionsActive">IsRequisitionsActive</a>

First included in: Miscellaneous/ReqMRPSetupWizardParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Requisitions</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsRequisitionsActive attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Requisitions</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#IsCapacityActive name="IsCapacityActive">IsCapacityActive</a>

First included in: Miscellaneous/ReqMRPSetupWizardParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Capacity</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCapacityActive attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Capacity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#IsSequencingActive name="IsSequencingActive">IsSequencingActive</a>

First included in: Miscellaneous/ReqMRPSetupWizardParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sequencing</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSequencingActive attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sequencing</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#IsFirmingActive name="IsFirmingActive">IsFirmingActive</a>

First included in: Miscellaneous/ReqMRPSetupWizardParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Firming</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsFirmingActive attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Firming</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#IsActionMessageActive name="IsActionMessageActive">IsActionMessageActive</a>

First included in: Miscellaneous/ReqMRPSetupWizardParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Action message</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsActionMessageActive attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Action message</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#IsCalculatedDelaysActive name="IsCalculatedDelaysActive">IsCalculatedDelaysActive</a>

First included in: Miscellaneous/ReqMRPSetupWizardParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Calculated delays</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCalculatedDelaysActive attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Calculated delays</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#IsJobSchedulingActive name="IsJobSchedulingActive">IsJobSchedulingActive</a>

First included in: Miscellaneous/ReqMRPSetupWizardParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Job scheduling</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsJobSchedulingActive attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Job scheduling</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#MaxBomLevel name="MaxBomLevel">MaxBomLevel</a>

First included in: Miscellaneous/ReqMRPSetupWizardParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>BOM level</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxBomLevel attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>BOM level</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#IsCoverageOverriden name="IsCoverageOverriden">IsCoverageOverriden</a>

First included in: Miscellaneous/ReqMRPSetupWizardParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Freeze</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCoverageOverriden attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Freeze</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#IsExplosionActive name="IsExplosionActive">IsExplosionActive</a>

First included in: Miscellaneous/ReqMRPSetupWizardParameters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Firming</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsExplosionActive attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Firming</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Miscellaneous/ReqMRPSetupWizardParameters (this entity)  

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

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Miscellaneous/ReqMRPSetupWizardParameters (this entity)  

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
