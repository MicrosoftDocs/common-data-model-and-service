---
title: HcmCompensationPayPerformanceAllocationLineEntity in HRM - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Compensation performance allocation lines in HRM(HcmCompensationPayPerformanceAllocationLineEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/HumanResources/HRM/HcmCompensationPayPerformanceAllocationLineEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Compensation performance allocation lines</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AllocationId](#AllocationId)||<a href="HcmCompensationPayPerformanceAllocationLineEntity.md" target="_blank">HRM/HcmCompensationPayPerformanceAllocationLineEntity</a>|
|[CompPerfRatingId](#CompPerfRatingId)||<a href="HcmCompensationPayPerformanceAllocationLineEntity.md" target="_blank">HRM/HcmCompensationPayPerformanceAllocationLineEntity</a>|
|[PerfFactorPercent](#PerfFactorPercent)||<a href="HcmCompensationPayPerformanceAllocationLineEntity.md" target="_blank">HRM/HcmCompensationPayPerformanceAllocationLineEntity</a>|
|[PlanType](#PlanType)||<a href="HcmCompensationPayPerformanceAllocationLineEntity.md" target="_blank">HRM/HcmCompensationPayPerformanceAllocationLineEntity</a>|
|[RatingLevel](#RatingLevel)||<a href="HcmCompensationPayPerformanceAllocationLineEntity.md" target="_blank">HRM/HcmCompensationPayPerformanceAllocationLineEntity</a>|
|[RatingLevelId](#RatingLevelId)||<a href="HcmCompensationPayPerformanceAllocationLineEntity.md" target="_blank">HRM/HcmCompensationPayPerformanceAllocationLineEntity</a>|
|[RatingModel](#RatingModel)||<a href="HcmCompensationPayPerformanceAllocationLineEntity.md" target="_blank">HRM/HcmCompensationPayPerformanceAllocationLineEntity</a>|
|[RatingModelId](#RatingModelId)||<a href="HcmCompensationPayPerformanceAllocationLineEntity.md" target="_blank">HRM/HcmCompensationPayPerformanceAllocationLineEntity</a>|
|[RatingModelType](#RatingModelType)||<a href="HcmCompensationPayPerformanceAllocationLineEntity.md" target="_blank">HRM/HcmCompensationPayPerformanceAllocationLineEntity</a>|
|[Relationship_HRMCompPerfAllocationRelationshipId](#Relationship_HRMCompPerfAllocationRelationshipId)||<a href="HcmCompensationPayPerformanceAllocationLineEntity.md" target="_blank">HRM/HcmCompensationPayPerformanceAllocationLineEntity</a>|
|[Relationship_HRMCompPerfRatingRelationshipId](#Relationship_HRMCompPerfRatingRelationshipId)||<a href="HcmCompensationPayPerformanceAllocationLineEntity.md" target="_blank">HRM/HcmCompensationPayPerformanceAllocationLineEntity</a>|
|[BackingTable_HRMCompPerfAllocationLineRelationshipId](#BackingTable_HRMCompPerfAllocationLineRelationshipId)||<a href="HcmCompensationPayPerformanceAllocationLineEntity.md" target="_blank">HRM/HcmCompensationPayPerformanceAllocationLineEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="HcmCompensationPayPerformanceAllocationLineEntity.md" target="_blank">HRM/HcmCompensationPayPerformanceAllocationLineEntity</a>|

### <a href=#AllocationId name="AllocationId">AllocationId</a>

First included in: HRM/HcmCompensationPayPerformanceAllocationLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompPerfRatingId name="CompPerfRatingId">CompPerfRatingId</a>

First included in: HRM/HcmCompensationPayPerformanceAllocationLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompPerfRatingId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PerfFactorPercent name="PerfFactorPercent">PerfFactorPercent</a>

First included in: HRM/HcmCompensationPayPerformanceAllocationLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PerfFactorPercent attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PlanType name="PlanType">PlanType</a>

First included in: HRM/HcmCompensationPayPerformanceAllocationLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PlanType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RatingLevel name="RatingLevel">RatingLevel</a>

First included in: HRM/HcmCompensationPayPerformanceAllocationLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RatingLevel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RatingLevelId name="RatingLevelId">RatingLevelId</a>

First included in: HRM/HcmCompensationPayPerformanceAllocationLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RatingLevelId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RatingModel name="RatingModel">RatingModel</a>

First included in: HRM/HcmCompensationPayPerformanceAllocationLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RatingModel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RatingModelId name="RatingModelId">RatingModelId</a>

First included in: HRM/HcmCompensationPayPerformanceAllocationLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rating model</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RatingModelId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Rating model</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RatingModelType name="RatingModelType">RatingModelType</a>

First included in: HRM/HcmCompensationPayPerformanceAllocationLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RatingModelType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_HRMCompPerfAllocationRelationshipId name="Relationship_HRMCompPerfAllocationRelationshipId">Relationship_HRMCompPerfAllocationRelationshipId</a>

First included in: HRM/HcmCompensationPayPerformanceAllocationLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_HRMCompPerfAllocationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_HRMCompPerfRatingRelationshipId name="Relationship_HRMCompPerfRatingRelationshipId">Relationship_HRMCompPerfRatingRelationshipId</a>

First included in: HRM/HcmCompensationPayPerformanceAllocationLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_HRMCompPerfRatingRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_HRMCompPerfAllocationLineRelationshipId name="BackingTable_HRMCompPerfAllocationLineRelationshipId">BackingTable_HRMCompPerfAllocationLineRelationshipId</a>

First included in: HRM/HcmCompensationPayPerformanceAllocationLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_HRMCompPerfAllocationLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/HumanResources/HumanResource/WorksheetLine/HRMCompPerfAllocationLine.md" target="_blank">/core/operationsCommon/Tables/HumanResources/HumanResource/WorksheetLine/HRMCompPerfAllocationLine.cdm.json/HRMCompPerfAllocationLine</a></td><td><a href="../../../Tables/HumanResources/HumanResource/WorksheetLine/HRMCompPerfAllocationLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: HRM/HcmCompensationPayPerformanceAllocationLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PrimaryCompanyContextRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
