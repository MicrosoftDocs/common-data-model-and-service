---
title: TMSTransportationTransitTimeEngineDetailMetadataEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# TMSTransportationTransitTimeEngineDetailMetadataEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/Transportation/TMSTransportationTransitTimeEngineDetailMetadataEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[FieldLookupType](#FieldLookupType)||<a href="TMSTransportationTransitTimeEngineDetailMetadataEntity.md" target="_blank">Transportation/TMSTransportationTransitTimeEngineDetailMetadataEntity</a>|
|[IsMandatoryField](#IsMandatoryField)||<a href="TMSTransportationTransitTimeEngineDetailMetadataEntity.md" target="_blank">Transportation/TMSTransportationTransitTimeEngineDetailMetadataEntity</a>|
|[FieldName](#FieldName)||<a href="TMSTransportationTransitTimeEngineDetailMetadataEntity.md" target="_blank">Transportation/TMSTransportationTransitTimeEngineDetailMetadataEntity</a>|
|[FieldSequenceNumber](#FieldSequenceNumber)||<a href="TMSTransportationTransitTimeEngineDetailMetadataEntity.md" target="_blank">Transportation/TMSTransportationTransitTimeEngineDetailMetadataEntity</a>|
|[TransportationTransitTimeEngineId](#TransportationTransitTimeEngineId)||<a href="TMSTransportationTransitTimeEngineDetailMetadataEntity.md" target="_blank">Transportation/TMSTransportationTransitTimeEngineDetailMetadataEntity</a>|
|[BackingTable_TMSTransitTimeFieldRelationshipId](#BackingTable_TMSTransitTimeFieldRelationshipId)||<a href="TMSTransportationTransitTimeEngineDetailMetadataEntity.md" target="_blank">Transportation/TMSTransportationTransitTimeEngineDetailMetadataEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="TMSTransportationTransitTimeEngineDetailMetadataEntity.md" target="_blank">Transportation/TMSTransportationTransitTimeEngineDetailMetadataEntity</a>|

### <a href=#FieldLookupType name="FieldLookupType">FieldLookupType</a>

First included in: Transportation/TMSTransportationTransitTimeEngineDetailMetadataEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FieldLookupType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsMandatoryField name="IsMandatoryField">IsMandatoryField</a>

First included in: Transportation/TMSTransportationTransitTimeEngineDetailMetadataEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsMandatoryField attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FieldName name="FieldName">FieldName</a>

First included in: Transportation/TMSTransportationTransitTimeEngineDetailMetadataEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FieldName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FieldSequenceNumber name="FieldSequenceNumber">FieldSequenceNumber</a>

First included in: Transportation/TMSTransportationTransitTimeEngineDetailMetadataEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FieldSequenceNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationTransitTimeEngineId name="TransportationTransitTimeEngineId">TransportationTransitTimeEngineId</a>

First included in: Transportation/TMSTransportationTransitTimeEngineDetailMetadataEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationTransitTimeEngineId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_TMSTransitTimeFieldRelationshipId name="BackingTable_TMSTransitTimeFieldRelationshipId">BackingTable_TMSTransitTimeFieldRelationshipId</a>

First included in: Transportation/TMSTransportationTransitTimeEngineDetailMetadataEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_TMSTransitTimeFieldRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Transportation/Group/TMSTransitTimeField.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Transportation/Group/TMSTransitTimeField.cdm.json/TMSTransitTimeField</a></td><td><a href="../../../Tables/SupplyChain/Transportation/Group/TMSTransitTimeField.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: Transportation/TMSTransportationTransitTimeEngineDetailMetadataEntity (this entity)  

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
