---
title: SMAServiceOrderStageEntity in ServiceManagement - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/7/2020
ms.author: nebanfic
---

# Service stages in ServiceManagement

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ServiceManagement/SMAServiceOrderStageEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Service stages</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[StageId](#StageId)||<a href="SMAServiceOrderStageEntity.md" target="_blank">ServiceManagement/SMAServiceOrderStageEntity</a>|
|[ParentServiceOrderStageId](#ParentServiceOrderStageId)||<a href="SMAServiceOrderStageEntity.md" target="_blank">ServiceManagement/SMAServiceOrderStageEntity</a>|
|[DefaultServiceOrderActivityPhaseCode](#DefaultServiceOrderActivityPhaseCode)||<a href="SMAServiceOrderStageEntity.md" target="_blank">ServiceManagement/SMAServiceOrderStageEntity</a>|
|[IsStageAllowingServiceOrderCancelation](#IsStageAllowingServiceOrderCancelation)||<a href="SMAServiceOrderStageEntity.md" target="_blank">ServiceManagement/SMAServiceOrderStageEntity</a>|
|[IsStageAllowingServiceOrderDeletion](#IsStageAllowingServiceOrderDeletion)||<a href="SMAServiceOrderStageEntity.md" target="_blank">ServiceManagement/SMAServiceOrderStageEntity</a>|
|[IsStageAllowingServiceOrderModification](#IsStageAllowingServiceOrderModification)||<a href="SMAServiceOrderStageEntity.md" target="_blank">ServiceManagement/SMAServiceOrderStageEntity</a>|
|[IsStageAllowingServiceOrderPosting](#IsStageAllowingServiceOrderPosting)||<a href="SMAServiceOrderStageEntity.md" target="_blank">ServiceManagement/SMAServiceOrderStageEntity</a>|
|[IsStageStoppingServiceOrderTimeRecording](#IsStageStoppingServiceOrderTimeRecording)||<a href="SMAServiceOrderStageEntity.md" target="_blank">ServiceManagement/SMAServiceOrderStageEntity</a>|
|[StageDescription](#StageDescription)||<a href="SMAServiceOrderStageEntity.md" target="_blank">ServiceManagement/SMAServiceOrderStageEntity</a>|
|[IsStageRequiringServiceOrderReasonCodeEntry](#IsStageRequiringServiceOrderReasonCodeEntry)||<a href="SMAServiceOrderStageEntity.md" target="_blank">ServiceManagement/SMAServiceOrderStageEntity</a>|
|[BackingTable_SMAStageTableRelationshipId](#BackingTable_SMAStageTableRelationshipId)||<a href="SMAServiceOrderStageEntity.md" target="_blank">ServiceManagement/SMAServiceOrderStageEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="SMAServiceOrderStageEntity.md" target="_blank">ServiceManagement/SMAServiceOrderStageEntity</a>|

### <a href=#StageId name="StageId">StageId</a>

First included in: ServiceManagement/SMAServiceOrderStageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StageId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ParentServiceOrderStageId name="ParentServiceOrderStageId">ParentServiceOrderStageId</a>

First included in: ServiceManagement/SMAServiceOrderStageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParentServiceOrderStageId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultServiceOrderActivityPhaseCode name="DefaultServiceOrderActivityPhaseCode">DefaultServiceOrderActivityPhaseCode</a>

First included in: ServiceManagement/SMAServiceOrderStageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultServiceOrderActivityPhaseCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsStageAllowingServiceOrderCancelation name="IsStageAllowingServiceOrderCancelation">IsStageAllowingServiceOrderCancelation</a>

First included in: ServiceManagement/SMAServiceOrderStageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsStageAllowingServiceOrderCancelation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsStageAllowingServiceOrderDeletion name="IsStageAllowingServiceOrderDeletion">IsStageAllowingServiceOrderDeletion</a>

First included in: ServiceManagement/SMAServiceOrderStageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsStageAllowingServiceOrderDeletion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsStageAllowingServiceOrderModification name="IsStageAllowingServiceOrderModification">IsStageAllowingServiceOrderModification</a>

First included in: ServiceManagement/SMAServiceOrderStageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsStageAllowingServiceOrderModification attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsStageAllowingServiceOrderPosting name="IsStageAllowingServiceOrderPosting">IsStageAllowingServiceOrderPosting</a>

First included in: ServiceManagement/SMAServiceOrderStageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsStageAllowingServiceOrderPosting attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsStageStoppingServiceOrderTimeRecording name="IsStageStoppingServiceOrderTimeRecording">IsStageStoppingServiceOrderTimeRecording</a>

First included in: ServiceManagement/SMAServiceOrderStageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsStageStoppingServiceOrderTimeRecording attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StageDescription name="StageDescription">StageDescription</a>

First included in: ServiceManagement/SMAServiceOrderStageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StageDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsStageRequiringServiceOrderReasonCodeEntry name="IsStageRequiringServiceOrderReasonCodeEntry">IsStageRequiringServiceOrderReasonCodeEntry</a>

First included in: ServiceManagement/SMAServiceOrderStageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsStageRequiringServiceOrderReasonCodeEntry attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_SMAStageTableRelationshipId name="BackingTable_SMAStageTableRelationshipId">BackingTable_SMAStageTableRelationshipId</a>

First included in: ServiceManagement/SMAServiceOrderStageEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_SMAStageTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ServiceManagement/Group/SMAStageTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ServiceManagement/Group/SMAStageTable.cdm.json/SMAStageTable</a></td><td><a href="../../../Tables/SupplyChain/ServiceManagement/Group/SMAStageTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ServiceManagement/SMAServiceOrderStageEntity (this entity)  

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
