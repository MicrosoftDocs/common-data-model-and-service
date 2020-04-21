---
title: SalesPackingSlipTrackingInformationEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# SalesPackingSlipTrackingInformationEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/SalesAndMarketing/SalesPackingSlipTrackingInformationEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[SalesOrderNumber](#SalesOrderNumber)||<a href="SalesPackingSlipTrackingInformationEntity.md" target="_blank">SalesAndMarketing/SalesPackingSlipTrackingInformationEntity</a>|
|[PackingSlipNumber](#PackingSlipNumber)||<a href="SalesPackingSlipTrackingInformationEntity.md" target="_blank">SalesAndMarketing/SalesPackingSlipTrackingInformationEntity</a>|
|[DeliveryDate](#DeliveryDate)||<a href="SalesPackingSlipTrackingInformationEntity.md" target="_blank">SalesAndMarketing/SalesPackingSlipTrackingInformationEntity</a>|
|[TrackingNumber](#TrackingNumber)||<a href="SalesPackingSlipTrackingInformationEntity.md" target="_blank">SalesAndMarketing/SalesPackingSlipTrackingInformationEntity</a>|
|[TrackingURL](#TrackingURL)||<a href="SalesPackingSlipTrackingInformationEntity.md" target="_blank">SalesAndMarketing/SalesPackingSlipTrackingInformationEntity</a>|
|[BackingTable_SalesPackingSlipTrackingInformationRelationshipId](#BackingTable_SalesPackingSlipTrackingInformationRelationshipId)||<a href="SalesPackingSlipTrackingInformationEntity.md" target="_blank">SalesAndMarketing/SalesPackingSlipTrackingInformationEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="SalesPackingSlipTrackingInformationEntity.md" target="_blank">SalesAndMarketing/SalesPackingSlipTrackingInformationEntity</a>|

### <a href=#SalesOrderNumber name="SalesOrderNumber">SalesOrderNumber</a>

First included in: SalesAndMarketing/SalesPackingSlipTrackingInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PackingSlipNumber name="PackingSlipNumber">PackingSlipNumber</a>

First included in: SalesAndMarketing/SalesPackingSlipTrackingInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackingSlipNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryDate name="DeliveryDate">DeliveryDate</a>

First included in: SalesAndMarketing/SalesPackingSlipTrackingInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TrackingNumber name="TrackingNumber">TrackingNumber</a>

First included in: SalesAndMarketing/SalesPackingSlipTrackingInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TrackingNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TrackingURL name="TrackingURL">TrackingURL</a>

First included in: SalesAndMarketing/SalesPackingSlipTrackingInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TrackingURL attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_SalesPackingSlipTrackingInformationRelationshipId name="BackingTable_SalesPackingSlipTrackingInformationRelationshipId">BackingTable_SalesPackingSlipTrackingInformationRelationshipId</a>

First included in: SalesAndMarketing/SalesPackingSlipTrackingInformationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_SalesPackingSlipTrackingInformationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Worksheet/SalesPackingSlipTrackingInformation.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Worksheet/SalesPackingSlipTrackingInformation.cdm.json/SalesPackingSlipTrackingInformation</a></td><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Worksheet/SalesPackingSlipTrackingInformation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: SalesAndMarketing/SalesPackingSlipTrackingInformationEntity (this entity)  

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
