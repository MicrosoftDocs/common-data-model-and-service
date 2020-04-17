---
title: TMSTransportationTransferLoadBuildingTemplateSequenceEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# TMSTransportationTransferLoadBuildingTemplateSequenceEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Entities/SupplyChain/Transportation/TMSTransportationTransferLoadBuildingTemplateSequenceEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[LoadTemplateId](#LoadTemplateId)||<a href="TMSTransportationTransferLoadBuildingTemplateSequenceEntity.md" target="_blank">Transportation/TMSTransportationTransferLoadBuildingTemplateSequenceEntity</a>|
|[SequenceNumber](#SequenceNumber)||<a href="TMSTransportationTransferLoadBuildingTemplateSequenceEntity.md" target="_blank">Transportation/TMSTransportationTransferLoadBuildingTemplateSequenceEntity</a>|
|[TransportationTransferLoadBuildingTemplateName](#TransportationTransferLoadBuildingTemplateName)||<a href="TMSTransportationTransferLoadBuildingTemplateSequenceEntity.md" target="_blank">Transportation/TMSTransportationTransferLoadBuildingTemplateSequenceEntity</a>|
|[Relationship_TransportationTransferLoadBuildingTemplateRelationshipId](#Relationship_TransportationTransferLoadBuildingTemplateRelationshipId)||<a href="TMSTransportationTransferLoadBuildingTemplateSequenceEntity.md" target="_blank">Transportation/TMSTransportationTransferLoadBuildingTemplateSequenceEntity</a>|
|[Relationship_LoadTemplateRelationshipId](#Relationship_LoadTemplateRelationshipId)||<a href="TMSTransportationTransferLoadBuildingTemplateSequenceEntity.md" target="_blank">Transportation/TMSTransportationTransferLoadBuildingTemplateSequenceEntity</a>|
|[BackingTable_TMSLoadBuildTemplateLoadTemplateRelationshipId](#BackingTable_TMSLoadBuildTemplateLoadTemplateRelationshipId)||<a href="TMSTransportationTransferLoadBuildingTemplateSequenceEntity.md" target="_blank">Transportation/TMSTransportationTransferLoadBuildingTemplateSequenceEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="TMSTransportationTransferLoadBuildingTemplateSequenceEntity.md" target="_blank">Transportation/TMSTransportationTransferLoadBuildingTemplateSequenceEntity</a>|

### <a href=#LoadTemplateId name="LoadTemplateId">LoadTemplateId</a>

First included in: Transportation/TMSTransportationTransferLoadBuildingTemplateSequenceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoadTemplateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SequenceNumber name="SequenceNumber">SequenceNumber</a>

First included in: Transportation/TMSTransportationTransferLoadBuildingTemplateSequenceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SequenceNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationTransferLoadBuildingTemplateName name="TransportationTransferLoadBuildingTemplateName">TransportationTransferLoadBuildingTemplateName</a>

First included in: Transportation/TMSTransportationTransferLoadBuildingTemplateSequenceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationTransferLoadBuildingTemplateName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TransportationTransferLoadBuildingTemplateRelationshipId name="Relationship_TransportationTransferLoadBuildingTemplateRelationshipId">Relationship_TransportationTransferLoadBuildingTemplateRelationshipId</a>

First included in: Transportation/TMSTransportationTransferLoadBuildingTemplateSequenceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TransportationTransferLoadBuildingTemplateRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_LoadTemplateRelationshipId name="Relationship_LoadTemplateRelationshipId">Relationship_LoadTemplateRelationshipId</a>

First included in: Transportation/TMSTransportationTransferLoadBuildingTemplateSequenceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LoadTemplateRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_TMSLoadBuildTemplateLoadTemplateRelationshipId name="BackingTable_TMSLoadBuildTemplateLoadTemplateRelationshipId">BackingTable_TMSLoadBuildTemplateLoadTemplateRelationshipId</a>

First included in: Transportation/TMSTransportationTransferLoadBuildingTemplateSequenceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_TMSLoadBuildTemplateLoadTemplateRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Transportation/Miscellaneous/TMSLoadBuildTemplateLoadTemplate.md" target="_blank">/core/erp/Tables/SupplyChain/Transportation/Miscellaneous/TMSLoadBuildTemplateLoadTemplate.cdm.json/TMSLoadBuildTemplateLoadTemplate</a></td><td><a href="../../../Tables/SupplyChain/Transportation/Miscellaneous/TMSLoadBuildTemplateLoadTemplate.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: Transportation/TMSTransportationTransferLoadBuildingTemplateSequenceEntity (this entity)  

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
