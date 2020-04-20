---
title: WMSSpaceUtilReportSetup - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# WMSSpaceUtilReportSetup

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/Inventory/Miscellaneous/WMSSpaceUtilReportSetup.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[WMSSpaceUtilReportSetup/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="WMSSpaceUtilReportSetup.md" target="_blank">Miscellaneous/WMSSpaceUtilReportSetup</a>|
|[InputBlockingLocationPolicyEnabled](#InputBlockingLocationPolicyEnabled)||<a href="WMSSpaceUtilReportSetup.md" target="_blank">Miscellaneous/WMSSpaceUtilReportSetup</a>|
|[LocationTypeBuffer](#LocationTypeBuffer)||<a href="WMSSpaceUtilReportSetup.md" target="_blank">Miscellaneous/WMSSpaceUtilReportSetup</a>|
|[LocationTypeInputPort](#LocationTypeInputPort)||<a href="WMSSpaceUtilReportSetup.md" target="_blank">Miscellaneous/WMSSpaceUtilReportSetup</a>|
|[LocationTypeInspectionLocation](#LocationTypeInspectionLocation)||<a href="WMSSpaceUtilReportSetup.md" target="_blank">Miscellaneous/WMSSpaceUtilReportSetup</a>|
|[LocationTypeKanbanSupermarket](#LocationTypeKanbanSupermarket)||<a href="WMSSpaceUtilReportSetup.md" target="_blank">Miscellaneous/WMSSpaceUtilReportSetup</a>|
|[LocationTypeOutputPort](#LocationTypeOutputPort)||<a href="WMSSpaceUtilReportSetup.md" target="_blank">Miscellaneous/WMSSpaceUtilReportSetup</a>|
|[LocationTypePick](#LocationTypePick)||<a href="WMSSpaceUtilReportSetup.md" target="_blank">Miscellaneous/WMSSpaceUtilReportSetup</a>|
|[LocationTypeProductionInput](#LocationTypeProductionInput)||<a href="WMSSpaceUtilReportSetup.md" target="_blank">Miscellaneous/WMSSpaceUtilReportSetup</a>|
|[StorageLoadUnitType](#StorageLoadUnitType)||<a href="WMSSpaceUtilReportSetup.md" target="_blank">Miscellaneous/WMSSpaceUtilReportSetup</a>|
|[WMSReportSetup](#WMSReportSetup)||<a href="WMSSpaceUtilReportSetup.md" target="_blank">Miscellaneous/WMSSpaceUtilReportSetup</a>|
|[DataAreaId](#DataAreaId)||<a href="WMSSpaceUtilReportSetup.md" target="_blank">Miscellaneous/WMSSpaceUtilReportSetup</a>|
|[Relationship_WMSReportSetupRelationshipId](#Relationship_WMSReportSetupRelationshipId)||<a href="WMSSpaceUtilReportSetup.md" target="_blank">Miscellaneous/WMSSpaceUtilReportSetup</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="WMSSpaceUtilReportSetup.md" target="_blank">Miscellaneous/WMSSpaceUtilReportSetup</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/WMSSpaceUtilReportSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[WMSSpaceUtilReportSetup/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#InputBlockingLocationPolicyEnabled name="InputBlockingLocationPolicyEnabled">InputBlockingLocationPolicyEnabled</a>

First included in: Miscellaneous/WMSSpaceUtilReportSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InputBlockingLocationPolicyEnabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LocationTypeBuffer name="LocationTypeBuffer">LocationTypeBuffer</a>

First included in: Miscellaneous/WMSSpaceUtilReportSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LocationTypeBuffer attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LocationTypeInputPort name="LocationTypeInputPort">LocationTypeInputPort</a>

First included in: Miscellaneous/WMSSpaceUtilReportSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LocationTypeInputPort attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LocationTypeInspectionLocation name="LocationTypeInspectionLocation">LocationTypeInspectionLocation</a>

First included in: Miscellaneous/WMSSpaceUtilReportSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LocationTypeInspectionLocation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LocationTypeKanbanSupermarket name="LocationTypeKanbanSupermarket">LocationTypeKanbanSupermarket</a>

First included in: Miscellaneous/WMSSpaceUtilReportSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LocationTypeKanbanSupermarket attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LocationTypeOutputPort name="LocationTypeOutputPort">LocationTypeOutputPort</a>

First included in: Miscellaneous/WMSSpaceUtilReportSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LocationTypeOutputPort attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LocationTypePick name="LocationTypePick">LocationTypePick</a>

First included in: Miscellaneous/WMSSpaceUtilReportSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LocationTypePick attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LocationTypeProductionInput name="LocationTypeProductionInput">LocationTypeProductionInput</a>

First included in: Miscellaneous/WMSSpaceUtilReportSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LocationTypeProductionInput attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#StorageLoadUnitType name="StorageLoadUnitType">StorageLoadUnitType</a>

First included in: Miscellaneous/WMSSpaceUtilReportSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StorageLoadUnitType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#WMSReportSetup name="WMSReportSetup">WMSReportSetup</a>

First included in: Miscellaneous/WMSSpaceUtilReportSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WMSReportSetup attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Miscellaneous/WMSSpaceUtilReportSetup (this entity)  

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

### <a href=#Relationship_WMSReportSetupRelationshipId name="Relationship_WMSReportSetupRelationshipId">Relationship_WMSReportSetupRelationshipId</a>

First included in: Miscellaneous/WMSSpaceUtilReportSetup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WMSReportSetupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="WMSReportSetup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Miscellaneous/WMSReportSetup.cdm.json/WMSReportSetup</a></td><td><a href="WMSReportSetup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Miscellaneous/WMSSpaceUtilReportSetup (this entity)  

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
