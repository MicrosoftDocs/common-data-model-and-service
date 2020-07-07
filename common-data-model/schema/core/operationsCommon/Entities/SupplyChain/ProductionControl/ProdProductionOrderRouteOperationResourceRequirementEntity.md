---
title: ProdProductionOrderRouteOperationResourceRequirementEntity in ProductionControl - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/7/2020
ms.author: nebanfic
---

# Production route operation resource requirements in ProductionControl

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductionControl/ProdProductionOrderRouteOperationResourceRequirementEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Production route operation resource requirements</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RelationshipType](#RelationshipType)||<a href="ProdProductionOrderRouteOperationResourceRequirementEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationResourceRequirementEntity</a>|
|[Capability](#Capability)||<a href="ProdProductionOrderRouteOperationResourceRequirementEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationResourceRequirementEntity</a>|
|[WillJobSchedulingUseRequirement](#WillJobSchedulingUseRequirement)||<a href="ProdProductionOrderRouteOperationResourceRequirementEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationResourceRequirementEntity</a>|
|[WillOperationSchedulingUseRequirement](#WillOperationSchedulingUseRequirement)||<a href="ProdProductionOrderRouteOperationResourceRequirementEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationResourceRequirementEntity</a>|
|[ProductionOrderNumber](#ProductionOrderNumber)||<a href="ProdProductionOrderRouteOperationResourceRequirementEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationResourceRequirementEntity</a>|
|[ProductionOrderRouteOperationNumber](#ProductionOrderRouteOperationNumber)||<a href="ProdProductionOrderRouteOperationResourceRequirementEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationResourceRequirementEntity</a>|
|[ProductionOrderRouteOperationPriority](#ProductionOrderRouteOperationPriority)||<a href="ProdProductionOrderRouteOperationResourceRequirementEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationResourceRequirementEntity</a>|
|[RequiredCapabilityName](#RequiredCapabilityName)||<a href="ProdProductionOrderRouteOperationResourceRequirementEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationResourceRequirementEntity</a>|
|[MinimumRequiredCapabilityLevel](#MinimumRequiredCapabilityLevel)||<a href="ProdProductionOrderRouteOperationResourceRequirementEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationResourceRequirementEntity</a>|
|[RequiredCertificateType](#RequiredCertificateType)||<a href="ProdProductionOrderRouteOperationResourceRequirementEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationResourceRequirementEntity</a>|
|[RequiredCourseId](#RequiredCourseId)||<a href="ProdProductionOrderRouteOperationResourceRequirementEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationResourceRequirementEntity</a>|
|[RequiredTitleId](#RequiredTitleId)||<a href="ProdProductionOrderRouteOperationResourceRequirementEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationResourceRequirementEntity</a>|
|[RequiredOperationsResourceGroupId](#RequiredOperationsResourceGroupId)||<a href="ProdProductionOrderRouteOperationResourceRequirementEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationResourceRequirementEntity</a>|
|[RequiredOperationsResourceId](#RequiredOperationsResourceId)||<a href="ProdProductionOrderRouteOperationResourceRequirementEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationResourceRequirementEntity</a>|
|[RequiredOperationsResourceType](#RequiredOperationsResourceType)||<a href="ProdProductionOrderRouteOperationResourceRequirementEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationResourceRequirementEntity</a>|
|[RequiredSkillId](#RequiredSkillId)||<a href="ProdProductionOrderRouteOperationResourceRequirementEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationResourceRequirementEntity</a>|
|[RequiredSkillLevel](#RequiredSkillLevel)||<a href="ProdProductionOrderRouteOperationResourceRequirementEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationResourceRequirementEntity</a>|
|[RecordId](#RecordId)||<a href="ProdProductionOrderRouteOperationResourceRequirementEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationResourceRequirementEntity</a>|
|[ProductionOrderRouteOperationDataAreaId](#ProductionOrderRouteOperationDataAreaId)||<a href="ProdProductionOrderRouteOperationResourceRequirementEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationResourceRequirementEntity</a>|
|[BackingTable_WrkCtrActivityRequirementRelationshipId](#BackingTable_WrkCtrActivityRequirementRelationshipId)||<a href="ProdProductionOrderRouteOperationResourceRequirementEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationResourceRequirementEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="ProdProductionOrderRouteOperationResourceRequirementEntity.md" target="_blank">ProductionControl/ProdProductionOrderRouteOperationResourceRequirementEntity</a>|

### <a href=#RelationshipType name="RelationshipType">RelationshipType</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationResourceRequirementEntity (this entity)  

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

First included in: ProductionControl/ProdProductionOrderRouteOperationResourceRequirementEntity (this entity)  

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

First included in: ProductionControl/ProdProductionOrderRouteOperationResourceRequirementEntity (this entity)  

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

First included in: ProductionControl/ProdProductionOrderRouteOperationResourceRequirementEntity (this entity)  

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

### <a href=#ProductionOrderNumber name="ProductionOrderNumber">ProductionOrderNumber</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationResourceRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductionOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductionOrderRouteOperationNumber name="ProductionOrderRouteOperationNumber">ProductionOrderRouteOperationNumber</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationResourceRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Operation number</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductionOrderRouteOperationNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Operation number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductionOrderRouteOperationPriority name="ProductionOrderRouteOperationPriority">ProductionOrderRouteOperationPriority</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationResourceRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductionOrderRouteOperationPriority attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequiredCapabilityName name="RequiredCapabilityName">RequiredCapabilityName</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationResourceRequirementEntity (this entity)  

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

First included in: ProductionControl/ProdProductionOrderRouteOperationResourceRequirementEntity (this entity)  

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

First included in: ProductionControl/ProdProductionOrderRouteOperationResourceRequirementEntity (this entity)  

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

First included in: ProductionControl/ProdProductionOrderRouteOperationResourceRequirementEntity (this entity)  

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

First included in: ProductionControl/ProdProductionOrderRouteOperationResourceRequirementEntity (this entity)  

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

First included in: ProductionControl/ProdProductionOrderRouteOperationResourceRequirementEntity (this entity)  

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

First included in: ProductionControl/ProdProductionOrderRouteOperationResourceRequirementEntity (this entity)  

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

First included in: ProductionControl/ProdProductionOrderRouteOperationResourceRequirementEntity (this entity)  

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

First included in: ProductionControl/ProdProductionOrderRouteOperationResourceRequirementEntity (this entity)  

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

First included in: ProductionControl/ProdProductionOrderRouteOperationResourceRequirementEntity (this entity)  

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

First included in: ProductionControl/ProdProductionOrderRouteOperationResourceRequirementEntity (this entity)  

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

### <a href=#ProductionOrderRouteOperationDataAreaId name="ProductionOrderRouteOperationDataAreaId">ProductionOrderRouteOperationDataAreaId</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationResourceRequirementEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductionOrderRouteOperationDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_WrkCtrActivityRequirementRelationshipId name="BackingTable_WrkCtrActivityRequirementRelationshipId">BackingTable_WrkCtrActivityRequirementRelationshipId</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationResourceRequirementEntity (this entity)  

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

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProductionControl/ProdProductionOrderRouteOperationResourceRequirementEntity (this entity)  

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
