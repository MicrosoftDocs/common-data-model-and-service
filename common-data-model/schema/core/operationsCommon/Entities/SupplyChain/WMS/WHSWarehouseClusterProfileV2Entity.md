---
title: WHSWarehouseClusterProfileV2Entity in WMS - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/13/2020
ms.author: nebanfic
---

# Warehouse cluster profiles V2 in WMS(WHSWarehouseClusterProfileV2Entity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/WMS/WHSWarehouseClusterProfileV2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Warehouse cluster profiles V2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ClusterBreakingAction](#ClusterBreakingAction)||<a href="WHSWarehouseClusterProfileV2Entity.md" target="_blank">WMS/WHSWarehouseClusterProfileV2Entity</a>|
|[ClusterPositionCount](#ClusterPositionCount)||<a href="WHSWarehouseClusterProfileV2Entity.md" target="_blank">WMS/WHSWarehouseClusterProfileV2Entity</a>|
|[ClusterPositionNameType](#ClusterPositionNameType)||<a href="WHSWarehouseClusterProfileV2Entity.md" target="_blank">WMS/WHSWarehouseClusterProfileV2Entity</a>|
|[WillClusterPickingGeneratePositionNames](#WillClusterPickingGeneratePositionNames)||<a href="WHSWarehouseClusterProfileV2Entity.md" target="_blank">WMS/WHSWarehouseClusterProfileV2Entity</a>|
|[ClusterProfileId](#ClusterProfileId)||<a href="WHSWarehouseClusterProfileV2Entity.md" target="_blank">WMS/WHSWarehouseClusterProfileV2Entity</a>|
|[ClusterProfileName](#ClusterProfileName)||<a href="WHSWarehouseClusterProfileV2Entity.md" target="_blank">WMS/WHSWarehouseClusterProfileV2Entity</a>|
|[ClusterSortingVerificationType](#ClusterSortingVerificationType)||<a href="WHSWarehouseClusterProfileV2Entity.md" target="_blank">WMS/WHSWarehouseClusterProfileV2Entity</a>|
|[WillClusterPickingRegisterClusterId](#WillClusterPickingRegisterClusterId)||<a href="WHSWarehouseClusterProfileV2Entity.md" target="_blank">WMS/WHSWarehouseClusterProfileV2Entity</a>|
|[ClusterType](#ClusterType)||<a href="WHSWarehouseClusterProfileV2Entity.md" target="_blank">WMS/WHSWarehouseClusterProfileV2Entity</a>|
|[PutawayClusterAssignmentRule](#PutawayClusterAssignmentRule)||<a href="WHSWarehouseClusterProfileV2Entity.md" target="_blank">WMS/WHSWarehouseClusterProfileV2Entity</a>|
|[PutawayClusterAssignmentTiming](#PutawayClusterAssignmentTiming)||<a href="WHSWarehouseClusterProfileV2Entity.md" target="_blank">WMS/WHSWarehouseClusterProfileV2Entity</a>|
|[PutawayClusterLocateRule](#PutawayClusterLocateRule)||<a href="WHSWarehouseClusterProfileV2Entity.md" target="_blank">WMS/WHSWarehouseClusterProfileV2Entity</a>|
|[IsPutawayClusterAssignedPerUser](#IsPutawayClusterAssignedPerUser)||<a href="WHSWarehouseClusterProfileV2Entity.md" target="_blank">WMS/WHSWarehouseClusterProfileV2Entity</a>|
|[IsClusterIdPersistedAsParentLicensePlateNumber](#IsClusterIdPersistedAsParentLicensePlateNumber)||<a href="WHSWarehouseClusterProfileV2Entity.md" target="_blank">WMS/WHSWarehouseClusterProfileV2Entity</a>|
|[PutawayRestrictingUnitSymbol](#PutawayRestrictingUnitSymbol)||<a href="WHSWarehouseClusterProfileV2Entity.md" target="_blank">WMS/WHSWarehouseClusterProfileV2Entity</a>|
|[PutawayWorkUnitBreakRule](#PutawayWorkUnitBreakRule)||<a href="WHSWarehouseClusterProfileV2Entity.md" target="_blank">WMS/WHSWarehouseClusterProfileV2Entity</a>|
|[ProfileSequenceNumber](#ProfileSequenceNumber)||<a href="WHSWarehouseClusterProfileV2Entity.md" target="_blank">WMS/WHSWarehouseClusterProfileV2Entity</a>|
|[WarehouseLocationDirectiveCode](#WarehouseLocationDirectiveCode)||<a href="WHSWarehouseClusterProfileV2Entity.md" target="_blank">WMS/WHSWarehouseClusterProfileV2Entity</a>|
|[ProfileQuery](#ProfileQuery)||<a href="WHSWarehouseClusterProfileV2Entity.md" target="_blank">WMS/WHSWarehouseClusterProfileV2Entity</a>|
|[BackingTable_WHSClusterProfileRelationshipId](#BackingTable_WHSClusterProfileRelationshipId)||<a href="WHSWarehouseClusterProfileV2Entity.md" target="_blank">WMS/WHSWarehouseClusterProfileV2Entity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="WHSWarehouseClusterProfileV2Entity.md" target="_blank">WMS/WHSWarehouseClusterProfileV2Entity</a>|

### <a href=#ClusterBreakingAction name="ClusterBreakingAction">ClusterBreakingAction</a>

First included in: WMS/WHSWarehouseClusterProfileV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClusterBreakingAction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ClusterPositionCount name="ClusterPositionCount">ClusterPositionCount</a>

First included in: WMS/WHSWarehouseClusterProfileV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClusterPositionCount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ClusterPositionNameType name="ClusterPositionNameType">ClusterPositionNameType</a>

First included in: WMS/WHSWarehouseClusterProfileV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClusterPositionNameType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillClusterPickingGeneratePositionNames name="WillClusterPickingGeneratePositionNames">WillClusterPickingGeneratePositionNames</a>

First included in: WMS/WHSWarehouseClusterProfileV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillClusterPickingGeneratePositionNames attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ClusterProfileId name="ClusterProfileId">ClusterProfileId</a>

First included in: WMS/WHSWarehouseClusterProfileV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClusterProfileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ClusterProfileName name="ClusterProfileName">ClusterProfileName</a>

First included in: WMS/WHSWarehouseClusterProfileV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClusterProfileName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ClusterSortingVerificationType name="ClusterSortingVerificationType">ClusterSortingVerificationType</a>

First included in: WMS/WHSWarehouseClusterProfileV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClusterSortingVerificationType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillClusterPickingRegisterClusterId name="WillClusterPickingRegisterClusterId">WillClusterPickingRegisterClusterId</a>

First included in: WMS/WHSWarehouseClusterProfileV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillClusterPickingRegisterClusterId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ClusterType name="ClusterType">ClusterType</a>

First included in: WMS/WHSWarehouseClusterProfileV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClusterType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PutawayClusterAssignmentRule name="PutawayClusterAssignmentRule">PutawayClusterAssignmentRule</a>

First included in: WMS/WHSWarehouseClusterProfileV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PutawayClusterAssignmentRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PutawayClusterAssignmentTiming name="PutawayClusterAssignmentTiming">PutawayClusterAssignmentTiming</a>

First included in: WMS/WHSWarehouseClusterProfileV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PutawayClusterAssignmentTiming attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PutawayClusterLocateRule name="PutawayClusterLocateRule">PutawayClusterLocateRule</a>

First included in: WMS/WHSWarehouseClusterProfileV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PutawayClusterLocateRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPutawayClusterAssignedPerUser name="IsPutawayClusterAssignedPerUser">IsPutawayClusterAssignedPerUser</a>

First included in: WMS/WHSWarehouseClusterProfileV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPutawayClusterAssignedPerUser attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsClusterIdPersistedAsParentLicensePlateNumber name="IsClusterIdPersistedAsParentLicensePlateNumber">IsClusterIdPersistedAsParentLicensePlateNumber</a>

First included in: WMS/WHSWarehouseClusterProfileV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsClusterIdPersistedAsParentLicensePlateNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PutawayRestrictingUnitSymbol name="PutawayRestrictingUnitSymbol">PutawayRestrictingUnitSymbol</a>

First included in: WMS/WHSWarehouseClusterProfileV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PutawayRestrictingUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PutawayWorkUnitBreakRule name="PutawayWorkUnitBreakRule">PutawayWorkUnitBreakRule</a>

First included in: WMS/WHSWarehouseClusterProfileV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PutawayWorkUnitBreakRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProfileSequenceNumber name="ProfileSequenceNumber">ProfileSequenceNumber</a>

First included in: WMS/WHSWarehouseClusterProfileV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProfileSequenceNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseLocationDirectiveCode name="WarehouseLocationDirectiveCode">WarehouseLocationDirectiveCode</a>

First included in: WMS/WHSWarehouseClusterProfileV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseLocationDirectiveCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProfileQuery name="ProfileQuery">ProfileQuery</a>

First included in: WMS/WHSWarehouseClusterProfileV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProfileQuery attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_WHSClusterProfileRelationshipId name="BackingTable_WHSClusterProfileRelationshipId">BackingTable_WHSClusterProfileRelationshipId</a>

First included in: WMS/WHSWarehouseClusterProfileV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_WHSClusterProfileRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Group/WHSClusterProfile.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/WHSClusterProfile.cdm.json/WHSClusterProfile</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Group/WHSClusterProfile.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: WMS/WHSWarehouseClusterProfileV2Entity (this entity)  

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
