---
title: RetailHardwareStation - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# RetailHardwareStation

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Commerce/Retail/Miscellaneous/RetailHardwareStation.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailHardwareStation/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailHardwareStation.md" target="_blank">Miscellaneous/RetailHardwareStation</a>|
|[HardwareStationId](#HardwareStationId)||<a href="RetailHardwareStation.md" target="_blank">Miscellaneous/RetailHardwareStation</a>|
|[HardwareStationName](#HardwareStationName)||<a href="RetailHardwareStation.md" target="_blank">Miscellaneous/RetailHardwareStation</a>|
|[HardwareProfileId](#HardwareProfileId)||<a href="RetailHardwareStation.md" target="_blank">Miscellaneous/RetailHardwareStation</a>|
|[HardwareStationPortNumber](#HardwareStationPortNumber)||<a href="RetailHardwareStation.md" target="_blank">Miscellaneous/RetailHardwareStation</a>|
|[SelfServicePackage](#SelfServicePackage)||<a href="RetailHardwareStation.md" target="_blank">Miscellaneous/RetailHardwareStation</a>|
|[MergedSelfServicePackageReference](#MergedSelfServicePackageReference)||<a href="RetailHardwareStation.md" target="_blank">Miscellaneous/RetailHardwareStation</a>|
|[Relationship_RetailSelfServicePackageInfoRelationshipId](#Relationship_RetailSelfServicePackageInfoRelationshipId)||<a href="RetailHardwareStation.md" target="_blank">Miscellaneous/RetailHardwareStation</a>|
|[Relationship_RetailSelfServiceMergedPackagesRelationshipId](#Relationship_RetailSelfServiceMergedPackagesRelationshipId)||<a href="RetailHardwareStation.md" target="_blank">Miscellaneous/RetailHardwareStation</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/RetailHardwareStation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailHardwareStation/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#HardwareStationId name="HardwareStationId">HardwareStationId</a>

First included in: Miscellaneous/RetailHardwareStation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HardwareStationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HardwareStationName name="HardwareStationName">HardwareStationName</a>

First included in: Miscellaneous/RetailHardwareStation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HardwareStationName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HardwareProfileId name="HardwareProfileId">HardwareProfileId</a>

First included in: Miscellaneous/RetailHardwareStation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HardwareProfileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HardwareStationPortNumber name="HardwareStationPortNumber">HardwareStationPortNumber</a>

First included in: Miscellaneous/RetailHardwareStation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HardwareStationPortNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SelfServicePackage name="SelfServicePackage">SelfServicePackage</a>

First included in: Miscellaneous/RetailHardwareStation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SelfServicePackage attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#MergedSelfServicePackageReference name="MergedSelfServicePackageReference">MergedSelfServicePackageReference</a>

First included in: Miscellaneous/RetailHardwareStation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MergedSelfServicePackageReference attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_RetailSelfServicePackageInfoRelationshipId name="Relationship_RetailSelfServicePackageInfoRelationshipId">Relationship_RetailSelfServicePackageInfoRelationshipId</a>

First included in: Miscellaneous/RetailHardwareStation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailSelfServicePackageInfoRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailSelfServicePackageInfo.md" target="_blank">/core/erp/Tables/Commerce/Retail/Miscellaneous/RetailSelfServicePackageInfo.cdm.json/RetailSelfServicePackageInfo</a></td><td><a href="RetailSelfServicePackageInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailSelfServiceMergedPackagesRelationshipId name="Relationship_RetailSelfServiceMergedPackagesRelationshipId">Relationship_RetailSelfServiceMergedPackagesRelationshipId</a>

First included in: Miscellaneous/RetailHardwareStation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailSelfServiceMergedPackagesRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailSelfServiceMergedPackages.md" target="_blank">/core/erp/Tables/Commerce/Retail/Miscellaneous/RetailSelfServiceMergedPackages.cdm.json/RetailSelfServiceMergedPackages</a></td><td><a href="RetailSelfServiceMergedPackages.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
