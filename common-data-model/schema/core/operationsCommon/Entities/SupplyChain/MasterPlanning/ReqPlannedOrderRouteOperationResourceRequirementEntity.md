---
title: ReqPlannedOrderRouteOperationResourceRequirementEntity in MasterPlanning - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Resource requirements for planned order route operation in MasterPlanning(ReqPlannedOrderRouteOperationResourceRequirementEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/MasterPlanning/ReqPlannedOrderRouteOperationResourceRequirementEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Resource requirements for planned order route operation</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RelationshipType](#RelationshipType)||<a href="ReqPlannedOrderRouteOperationResourceRequirementEntity.md" target="_blank">MasterPlanning/ReqPlannedOrderRouteOperationResourceRequirementEntity</a>|
|[Capability](#Capability)||<a href="ReqPlannedOrderRouteOperationResourceRequirementEntity.md" target="_blank">MasterPlanning/ReqPlannedOrderRouteOperationResourceRequirementEntity</a>|
|[WillJobSchedulingUseRequirement](#WillJobSchedulingUseRequirement)||<a href="ReqPlannedOrderRouteOperationResourceRequirementEntity.md" target="_blank">MasterPlanning/ReqPlannedOrderRouteOperationResourceRequirementEntity</a>|
|[WillOperationSchedulingUseRequirement](#WillOperationSchedulingUseRequirement)||<a href="ReqPlannedOrderRouteOperationResourceRequirementEntity.md" target="_blank">MasterPlanning/ReqPlannedOrderRouteOperationResourceRequirementEntity</a>|
|[RouteOperationId](#RouteOperationId)||<a href="ReqPlannedOrderRouteOperationResourceRequirementEntity.md" target="_blank">MasterPlanning/ReqPlannedOrderRouteOperationResourceRequirementEntity</a>|
|[RequiredCapabilityName](#RequiredCapabilityName)||<a href="ReqPlannedOrderRouteOperationResourceRequirementEntity.md" target="_blank">MasterPlanning/ReqPlannedOrderRouteOperationResourceRequirementEntity</a>|
|[MinimumRequiredCapabilityLevel](#MinimumRequiredCapabilityLevel)||<a href="ReqPlannedOrderRouteOperationResourceRequirementEntity.md" target="_blank">MasterPlanning/ReqPlannedOrderRouteOperationResourceRequirementEntity</a>|
|[RequiredCertificateType](#RequiredCertificateType)||<a href="ReqPlannedOrderRouteOperationResourceRequirementEntity.md" target="_blank">MasterPlanning/ReqPlannedOrderRouteOperationResourceRequirementEntity</a>|
|[RequiredCourseId](#RequiredCourseId)||<a href="ReqPlannedOrderRouteOperationResourceRequirementEntity.md" target="_blank">MasterPlanning/ReqPlannedOrderRouteOperationResourceRequirementEntity</a>|
|[RequiredTitleId](#RequiredTitleId)||<a href="ReqPlannedOrderRouteOperationResourceRequirementEntity.md" target="_blank">MasterPlanning/ReqPlannedOrderRouteOperationResourceRequirementEntity</a>|
|[RequiredOperationsResourceGroupId](#RequiredOperationsResourceGroupId)||<a href="ReqPlannedOrderRouteOperationResourceRequirementEntity.md" target="_blank">MasterPlanning/ReqPlannedOrderRouteOperationResourceRequirementEntity</a>|
|[RequiredOperationsResourceId](#RequiredOperationsResourceId)||<a href="ReqPlannedOrderRouteOperationResourceRequirementEntity.md" target="_blank">MasterPlanning/ReqPlannedOrderRouteOperationResourceRequirementEntity</a>|
|[RequiredOperationsResourceType](#RequiredOperationsResourceType)||<a href="ReqPlannedOrderRouteOperationResourceRequirementEntity.md" target="_blank">MasterPlanning/ReqPlannedOrderRouteOperationResourceRequirementEntity</a>|
|[RequiredSkillId](#RequiredSkillId)||<a href="ReqPlannedOrderRouteOperationResourceRequirementEntity.md" target="_blank">MasterPlanning/ReqPlannedOrderRouteOperationResourceRequirementEntity</a>|
|[RequiredSkillLevel](#RequiredSkillLevel)||<a href="ReqPlannedOrderRouteOperationResourceRequirementEntity.md" target="_blank">MasterPlanning/ReqPlannedOrderRouteOperationResourceRequirementEntity</a>|
|[RecordId](#RecordId)||<a href="ReqPlannedOrderRouteOperationResourceRequirementEntity.md" target="_blank">MasterPlanning/ReqPlannedOrderRouteOperationResourceRequirementEntity</a>|
|[PlannedOrderNumber](#PlannedOrderNumber)||<a href="ReqPlannedOrderRouteOperationResourceRequirementEntity.md" target="_blank">MasterPlanning/ReqPlannedOrderRouteOperationResourceRequirementEntity</a>|
|[RouteOperationNumber](#RouteOperationNumber)||<a href="ReqPlannedOrderRouteOperationResourceRequirementEntity.md" target="_blank">MasterPlanning/ReqPlannedOrderRouteOperationResourceRequirementEntity</a>|
|[RouteOperationPriority](#RouteOperationPriority)||<a href="ReqPlannedOrderRouteOperationResourceRequirementEntity.md" target="_blank">MasterPlanning/ReqPlannedOrderRouteOperationResourceRequirementEntity</a>|
|[RequirementPlanId](#RequirementPlanId)||<a href="ReqPlannedOrderRouteOperationResourceRequirementEntity.md" target="_blank">MasterPlanning/ReqPlannedOrderRouteOperationResourceRequirementEntity</a>|
|[RouteOperationDataAreaId](#RouteOperationDataAreaId)||<a href="ReqPlannedOrderRouteOperationResourceRequirementEntity.md" target="_blank">MasterPlanning/ReqPlannedOrderRouteOperationResourceRequirementEntity</a>|
|[BackingTable_WrkCtrActivityRequirementRelationshipId](#BackingTable_WrkCtrActivityRequirementRelationshipId)||<a href="ReqPlannedOrderRouteOperationResourceRequirementEntity.md" target="_blank">MasterPlanning/ReqPlannedOrderRouteOperationResourceRequirementEntity</a>|

### <a href=#RelationshipType name="RelationshipType">RelationshipType</a>

First included in: MasterPlanning/ReqPlannedOrderRouteOperationResourceRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RelationshipType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Capability name="Capability">Capability</a>

First included in: MasterPlanning/ReqPlannedOrderRouteOperationResourceRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Capability attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillJobSchedulingUseRequirement name="WillJobSchedulingUseRequirement">WillJobSchedulingUseRequirement</a>

First included in: MasterPlanning/ReqPlannedOrderRouteOperationResourceRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillJobSchedulingUseRequirement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillOperationSchedulingUseRequirement name="WillOperationSchedulingUseRequirement">WillOperationSchedulingUseRequirement</a>

First included in: MasterPlanning/ReqPlannedOrderRouteOperationResourceRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillOperationSchedulingUseRequirement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RouteOperationId name="RouteOperationId">RouteOperationId</a>

First included in: MasterPlanning/ReqPlannedOrderRouteOperationResourceRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RouteOperationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequiredCapabilityName name="RequiredCapabilityName">RequiredCapabilityName</a>

First included in: MasterPlanning/ReqPlannedOrderRouteOperationResourceRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequiredCapabilityName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinimumRequiredCapabilityLevel name="MinimumRequiredCapabilityLevel">MinimumRequiredCapabilityLevel</a>

First included in: MasterPlanning/ReqPlannedOrderRouteOperationResourceRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumRequiredCapabilityLevel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequiredCertificateType name="RequiredCertificateType">RequiredCertificateType</a>

First included in: MasterPlanning/ReqPlannedOrderRouteOperationResourceRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequiredCertificateType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequiredCourseId name="RequiredCourseId">RequiredCourseId</a>

First included in: MasterPlanning/ReqPlannedOrderRouteOperationResourceRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequiredCourseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequiredTitleId name="RequiredTitleId">RequiredTitleId</a>

First included in: MasterPlanning/ReqPlannedOrderRouteOperationResourceRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequiredTitleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequiredOperationsResourceGroupId name="RequiredOperationsResourceGroupId">RequiredOperationsResourceGroupId</a>

First included in: MasterPlanning/ReqPlannedOrderRouteOperationResourceRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequiredOperationsResourceGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequiredOperationsResourceId name="RequiredOperationsResourceId">RequiredOperationsResourceId</a>

First included in: MasterPlanning/ReqPlannedOrderRouteOperationResourceRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequiredOperationsResourceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequiredOperationsResourceType name="RequiredOperationsResourceType">RequiredOperationsResourceType</a>

First included in: MasterPlanning/ReqPlannedOrderRouteOperationResourceRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequiredOperationsResourceType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequiredSkillId name="RequiredSkillId">RequiredSkillId</a>

First included in: MasterPlanning/ReqPlannedOrderRouteOperationResourceRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequiredSkillId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequiredSkillLevel name="RequiredSkillLevel">RequiredSkillLevel</a>

First included in: MasterPlanning/ReqPlannedOrderRouteOperationResourceRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequiredSkillLevel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RecordId name="RecordId">RecordId</a>

First included in: MasterPlanning/ReqPlannedOrderRouteOperationResourceRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecordId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PlannedOrderNumber name="PlannedOrderNumber">PlannedOrderNumber</a>

First included in: MasterPlanning/ReqPlannedOrderRouteOperationResourceRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Planned order number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PlannedOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Planned order number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RouteOperationNumber name="RouteOperationNumber">RouteOperationNumber</a>

First included in: MasterPlanning/ReqPlannedOrderRouteOperationResourceRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Operation number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RouteOperationNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Operation number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RouteOperationPriority name="RouteOperationPriority">RouteOperationPriority</a>

First included in: MasterPlanning/ReqPlannedOrderRouteOperationResourceRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RouteOperationPriority attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequirementPlanId name="RequirementPlanId">RequirementPlanId</a>

First included in: MasterPlanning/ReqPlannedOrderRouteOperationResourceRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Requirement plan ID</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequirementPlanId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Requirement plan ID</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RouteOperationDataAreaId name="RouteOperationDataAreaId">RouteOperationDataAreaId</a>

First included in: MasterPlanning/ReqPlannedOrderRouteOperationResourceRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RouteOperationDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_WrkCtrActivityRequirementRelationshipId name="BackingTable_WrkCtrActivityRequirementRelationshipId">BackingTable_WrkCtrActivityRequirementRelationshipId</a>

First included in: MasterPlanning/ReqPlannedOrderRouteOperationResourceRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_WrkCtrActivityRequirementRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/MasterPlanning/Main/WrkCtrActivityRequirement.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/MasterPlanning/Main/WrkCtrActivityRequirement.cdm.json/WrkCtrActivityRequirement</a></td><td><a href="../../../Tables/SupplyChain/MasterPlanning/Main/WrkCtrActivityRequirement.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
