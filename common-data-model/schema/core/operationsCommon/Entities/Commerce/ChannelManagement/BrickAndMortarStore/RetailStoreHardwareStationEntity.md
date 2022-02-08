---
title: RetailStoreHardwareStationEntity in BrickAndMortarStore - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Store hardware stations in BrickAndMortarStore(RetailStoreHardwareStationEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Commerce/ChannelManagement/BrickAndMortarStore/RetailStoreHardwareStationEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Store hardware stations</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[HardwareStationId](#HardwareStationId)||<a href="RetailStoreHardwareStationEntity.md" target="_blank">BrickAndMortarStore/RetailStoreHardwareStationEntity</a>|
|[HostName](#HostName)||<a href="RetailStoreHardwareStationEntity.md" target="_blank">BrickAndMortarStore/RetailStoreHardwareStationEntity</a>|
|[EftTerminalId](#EftTerminalId)||<a href="RetailStoreHardwareStationEntity.md" target="_blank">BrickAndMortarStore/RetailStoreHardwareStationEntity</a>|
|[Description](#Description)||<a href="RetailStoreHardwareStationEntity.md" target="_blank">BrickAndMortarStore/RetailStoreHardwareStationEntity</a>|
|[StoreNumber](#StoreNumber)||<a href="RetailStoreHardwareStationEntity.md" target="_blank">BrickAndMortarStore/RetailStoreHardwareStationEntity</a>|
|[HardwareProfileId](#HardwareProfileId)||<a href="RetailStoreHardwareStationEntity.md" target="_blank">BrickAndMortarStore/RetailStoreHardwareStationEntity</a>|
|[HardwareStationType](#HardwareStationType)||<a href="RetailStoreHardwareStationEntity.md" target="_blank">BrickAndMortarStore/RetailStoreHardwareStationEntity</a>|
|[SelfServicePackage](#SelfServicePackage)||<a href="RetailStoreHardwareStationEntity.md" target="_blank">BrickAndMortarStore/RetailStoreHardwareStationEntity</a>|
|[Port](#Port)||<a href="RetailStoreHardwareStationEntity.md" target="_blank">BrickAndMortarStore/RetailStoreHardwareStationEntity</a>|
|[CertificateThumbprint](#CertificateThumbprint)||<a href="RetailStoreHardwareStationEntity.md" target="_blank">BrickAndMortarStore/RetailStoreHardwareStationEntity</a>|
|[MergedSelfServicePackageReference](#MergedSelfServicePackageReference)||<a href="RetailStoreHardwareStationEntity.md" target="_blank">BrickAndMortarStore/RetailStoreHardwareStationEntity</a>|
|[Relationship_RetailStoreEntityRelationshipId](#Relationship_RetailStoreEntityRelationshipId)||<a href="RetailStoreHardwareStationEntity.md" target="_blank">BrickAndMortarStore/RetailStoreHardwareStationEntity</a>|
|[Relationship_RetailHardwareStationEntityRelationshipId](#Relationship_RetailHardwareStationEntityRelationshipId)||<a href="RetailStoreHardwareStationEntity.md" target="_blank">BrickAndMortarStore/RetailStoreHardwareStationEntity</a>|
|[BackingTable_RetailStoreHardwareStationTableRelationshipId](#BackingTable_RetailStoreHardwareStationTableRelationshipId)||<a href="RetailStoreHardwareStationEntity.md" target="_blank">BrickAndMortarStore/RetailStoreHardwareStationEntity</a>|

### <a href=#HardwareStationId name="HardwareStationId">HardwareStationId</a>

First included in: BrickAndMortarStore/RetailStoreHardwareStationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HardwareStationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HostName name="HostName">HostName</a>

First included in: BrickAndMortarStore/RetailStoreHardwareStationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HostName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EftTerminalId name="EftTerminalId">EftTerminalId</a>

First included in: BrickAndMortarStore/RetailStoreHardwareStationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EftTerminalId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: BrickAndMortarStore/RetailStoreHardwareStationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StoreNumber name="StoreNumber">StoreNumber</a>

First included in: BrickAndMortarStore/RetailStoreHardwareStationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StoreNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HardwareProfileId name="HardwareProfileId">HardwareProfileId</a>

First included in: BrickAndMortarStore/RetailStoreHardwareStationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HardwareProfileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HardwareStationType name="HardwareStationType">HardwareStationType</a>

First included in: BrickAndMortarStore/RetailStoreHardwareStationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HardwareStationType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SelfServicePackage name="SelfServicePackage">SelfServicePackage</a>

First included in: BrickAndMortarStore/RetailStoreHardwareStationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SelfServicePackage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Port name="Port">Port</a>

First included in: BrickAndMortarStore/RetailStoreHardwareStationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Port attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CertificateThumbprint name="CertificateThumbprint">CertificateThumbprint</a>

First included in: BrickAndMortarStore/RetailStoreHardwareStationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CertificateThumbprint attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MergedSelfServicePackageReference name="MergedSelfServicePackageReference">MergedSelfServicePackageReference</a>

First included in: BrickAndMortarStore/RetailStoreHardwareStationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MergedSelfServicePackageReference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailStoreEntityRelationshipId name="Relationship_RetailStoreEntityRelationshipId">Relationship_RetailStoreEntityRelationshipId</a>

First included in: BrickAndMortarStore/RetailStoreHardwareStationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailStoreEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_RetailHardwareStationEntityRelationshipId name="Relationship_RetailHardwareStationEntityRelationshipId">Relationship_RetailHardwareStationEntityRelationshipId</a>

First included in: BrickAndMortarStore/RetailStoreHardwareStationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailHardwareStationEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_RetailStoreHardwareStationTableRelationshipId name="BackingTable_RetailStoreHardwareStationTableRelationshipId">BackingTable_RetailStoreHardwareStationTableRelationshipId</a>

First included in: BrickAndMortarStore/RetailStoreHardwareStationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailStoreHardwareStationTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../Tables/Commerce/Payments/Miscellaneous/RetailStoreHardwareStationTable.md" target="_blank">/core/operationsCommon/Tables/Commerce/Payments/Miscellaneous/RetailStoreHardwareStationTable.cdm.json/RetailStoreHardwareStationTable</a></td><td><a href="../../../../Tables/Commerce/Payments/Miscellaneous/RetailStoreHardwareStationTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
