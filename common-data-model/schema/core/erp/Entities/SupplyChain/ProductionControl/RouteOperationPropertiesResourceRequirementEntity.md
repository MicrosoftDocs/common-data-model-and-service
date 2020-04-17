---
title: RouteOperationPropertiesResourceRequirementEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# RouteOperationPropertiesResourceRequirementEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Entities/SupplyChain/ProductionControl/RouteOperationPropertiesResourceRequirementEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[RelationshipType](#RelationshipType)||<a href="RouteOperationPropertiesResourceRequirementEntity.md" target="_blank">ProductionControl/RouteOperationPropertiesResourceRequirementEntity</a>|
|[Capability](#Capability)||<a href="RouteOperationPropertiesResourceRequirementEntity.md" target="_blank">ProductionControl/RouteOperationPropertiesResourceRequirementEntity</a>|
|[WillJobSchedulingUseRequirement](#WillJobSchedulingUseRequirement)||<a href="RouteOperationPropertiesResourceRequirementEntity.md" target="_blank">ProductionControl/RouteOperationPropertiesResourceRequirementEntity</a>|
|[WillOperationSchedulingUseRequirement](#WillOperationSchedulingUseRequirement)||<a href="RouteOperationPropertiesResourceRequirementEntity.md" target="_blank">ProductionControl/RouteOperationPropertiesResourceRequirementEntity</a>|
|[ItemNumber](#ItemNumber)||<a href="RouteOperationPropertiesResourceRequirementEntity.md" target="_blank">ProductionControl/RouteOperationPropertiesResourceRequirementEntity</a>|
|[ProductGroupId](#ProductGroupId)||<a href="RouteOperationPropertiesResourceRequirementEntity.md" target="_blank">ProductionControl/RouteOperationPropertiesResourceRequirementEntity</a>|
|[RouteId](#RouteId)||<a href="RouteOperationPropertiesResourceRequirementEntity.md" target="_blank">ProductionControl/RouteOperationPropertiesResourceRequirementEntity</a>|
|[ProductionSiteId](#ProductionSiteId)||<a href="RouteOperationPropertiesResourceRequirementEntity.md" target="_blank">ProductionControl/RouteOperationPropertiesResourceRequirementEntity</a>|
|[ProductConfigurationId](#ProductConfigurationId)||<a href="RouteOperationPropertiesResourceRequirementEntity.md" target="_blank">ProductionControl/RouteOperationPropertiesResourceRequirementEntity</a>|
|[RouteOperationId](#RouteOperationId)||<a href="RouteOperationPropertiesResourceRequirementEntity.md" target="_blank">ProductionControl/RouteOperationPropertiesResourceRequirementEntity</a>|
|[RequiredCapabilityName](#RequiredCapabilityName)||<a href="RouteOperationPropertiesResourceRequirementEntity.md" target="_blank">ProductionControl/RouteOperationPropertiesResourceRequirementEntity</a>|
|[MinimumRequiredCapabilityLevel](#MinimumRequiredCapabilityLevel)||<a href="RouteOperationPropertiesResourceRequirementEntity.md" target="_blank">ProductionControl/RouteOperationPropertiesResourceRequirementEntity</a>|
|[RequiredCertificateType](#RequiredCertificateType)||<a href="RouteOperationPropertiesResourceRequirementEntity.md" target="_blank">ProductionControl/RouteOperationPropertiesResourceRequirementEntity</a>|
|[RequiredCourseId](#RequiredCourseId)||<a href="RouteOperationPropertiesResourceRequirementEntity.md" target="_blank">ProductionControl/RouteOperationPropertiesResourceRequirementEntity</a>|
|[RequiredTitleId](#RequiredTitleId)||<a href="RouteOperationPropertiesResourceRequirementEntity.md" target="_blank">ProductionControl/RouteOperationPropertiesResourceRequirementEntity</a>|
|[RequiredOperationsResourceGroupId](#RequiredOperationsResourceGroupId)||<a href="RouteOperationPropertiesResourceRequirementEntity.md" target="_blank">ProductionControl/RouteOperationPropertiesResourceRequirementEntity</a>|
|[RequiredOperationsResourceId](#RequiredOperationsResourceId)||<a href="RouteOperationPropertiesResourceRequirementEntity.md" target="_blank">ProductionControl/RouteOperationPropertiesResourceRequirementEntity</a>|
|[RequiredOperationsResourceType](#RequiredOperationsResourceType)||<a href="RouteOperationPropertiesResourceRequirementEntity.md" target="_blank">ProductionControl/RouteOperationPropertiesResourceRequirementEntity</a>|
|[RequiredSkillId](#RequiredSkillId)||<a href="RouteOperationPropertiesResourceRequirementEntity.md" target="_blank">ProductionControl/RouteOperationPropertiesResourceRequirementEntity</a>|
|[RequiredSkillLevel](#RequiredSkillLevel)||<a href="RouteOperationPropertiesResourceRequirementEntity.md" target="_blank">ProductionControl/RouteOperationPropertiesResourceRequirementEntity</a>|
|[RecordId](#RecordId)||<a href="RouteOperationPropertiesResourceRequirementEntity.md" target="_blank">ProductionControl/RouteOperationPropertiesResourceRequirementEntity</a>|
|[RouteOperationDataAreaId](#RouteOperationDataAreaId)||<a href="RouteOperationPropertiesResourceRequirementEntity.md" target="_blank">ProductionControl/RouteOperationPropertiesResourceRequirementEntity</a>|
|[BackingTable_WrkCtrActivityRequirementRelationshipId](#BackingTable_WrkCtrActivityRequirementRelationshipId)||<a href="RouteOperationPropertiesResourceRequirementEntity.md" target="_blank">ProductionControl/RouteOperationPropertiesResourceRequirementEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="RouteOperationPropertiesResourceRequirementEntity.md" target="_blank">ProductionControl/RouteOperationPropertiesResourceRequirementEntity</a>|

### <a href=#RelationshipType name="RelationshipType">RelationshipType</a>

First included in: ProductionControl/RouteOperationPropertiesResourceRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RelationshipType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Capability name="Capability">Capability</a>

First included in: ProductionControl/RouteOperationPropertiesResourceRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Capability attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillJobSchedulingUseRequirement name="WillJobSchedulingUseRequirement">WillJobSchedulingUseRequirement</a>

First included in: ProductionControl/RouteOperationPropertiesResourceRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillJobSchedulingUseRequirement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillOperationSchedulingUseRequirement name="WillOperationSchedulingUseRequirement">WillOperationSchedulingUseRequirement</a>

First included in: ProductionControl/RouteOperationPropertiesResourceRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillOperationSchedulingUseRequirement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemNumber name="ItemNumber">ItemNumber</a>

First included in: ProductionControl/RouteOperationPropertiesResourceRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductGroupId name="ProductGroupId">ProductGroupId</a>

First included in: ProductionControl/RouteOperationPropertiesResourceRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RouteId name="RouteId">RouteId</a>

First included in: ProductionControl/RouteOperationPropertiesResourceRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RouteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductionSiteId name="ProductionSiteId">ProductionSiteId</a>

First included in: ProductionControl/RouteOperationPropertiesResourceRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductionSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductConfigurationId name="ProductConfigurationId">ProductConfigurationId</a>

First included in: ProductionControl/RouteOperationPropertiesResourceRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductConfigurationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RouteOperationId name="RouteOperationId">RouteOperationId</a>

First included in: ProductionControl/RouteOperationPropertiesResourceRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RouteOperationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequiredCapabilityName name="RequiredCapabilityName">RequiredCapabilityName</a>

First included in: ProductionControl/RouteOperationPropertiesResourceRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequiredCapabilityName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinimumRequiredCapabilityLevel name="MinimumRequiredCapabilityLevel">MinimumRequiredCapabilityLevel</a>

First included in: ProductionControl/RouteOperationPropertiesResourceRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumRequiredCapabilityLevel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequiredCertificateType name="RequiredCertificateType">RequiredCertificateType</a>

First included in: ProductionControl/RouteOperationPropertiesResourceRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequiredCertificateType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequiredCourseId name="RequiredCourseId">RequiredCourseId</a>

First included in: ProductionControl/RouteOperationPropertiesResourceRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequiredCourseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequiredTitleId name="RequiredTitleId">RequiredTitleId</a>

First included in: ProductionControl/RouteOperationPropertiesResourceRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequiredTitleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequiredOperationsResourceGroupId name="RequiredOperationsResourceGroupId">RequiredOperationsResourceGroupId</a>

First included in: ProductionControl/RouteOperationPropertiesResourceRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequiredOperationsResourceGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequiredOperationsResourceId name="RequiredOperationsResourceId">RequiredOperationsResourceId</a>

First included in: ProductionControl/RouteOperationPropertiesResourceRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequiredOperationsResourceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequiredOperationsResourceType name="RequiredOperationsResourceType">RequiredOperationsResourceType</a>

First included in: ProductionControl/RouteOperationPropertiesResourceRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequiredOperationsResourceType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequiredSkillId name="RequiredSkillId">RequiredSkillId</a>

First included in: ProductionControl/RouteOperationPropertiesResourceRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequiredSkillId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequiredSkillLevel name="RequiredSkillLevel">RequiredSkillLevel</a>

First included in: ProductionControl/RouteOperationPropertiesResourceRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequiredSkillLevel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RecordId name="RecordId">RecordId</a>

First included in: ProductionControl/RouteOperationPropertiesResourceRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecordId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RouteOperationDataAreaId name="RouteOperationDataAreaId">RouteOperationDataAreaId</a>

First included in: ProductionControl/RouteOperationPropertiesResourceRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RouteOperationDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_WrkCtrActivityRequirementRelationshipId name="BackingTable_WrkCtrActivityRequirementRelationshipId">BackingTable_WrkCtrActivityRequirementRelationshipId</a>

First included in: ProductionControl/RouteOperationPropertiesResourceRequirementEntity (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/MasterPlanning/Main/WrkCtrActivityRequirement.md" target="_blank">/core/erp/Tables/SupplyChain/MasterPlanning/Main/WrkCtrActivityRequirement.cdm.json/WrkCtrActivityRequirement</a></td><td><a href="../../../Tables/SupplyChain/MasterPlanning/Main/WrkCtrActivityRequirement.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProductionControl/RouteOperationPropertiesResourceRequirementEntity (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/erp/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
