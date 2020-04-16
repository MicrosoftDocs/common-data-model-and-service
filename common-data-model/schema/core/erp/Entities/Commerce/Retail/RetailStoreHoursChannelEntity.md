---
title: RetailStoreHoursChannelEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/16/2020
ms.author: nebanfic
---

# RetailStoreHoursChannelEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Entities/Commerce/Retail/RetailStoreHoursChannelEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.Application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Entity|
|---|---|---|
|[StoreHoursTemplateId](#StoreHoursTemplateId)||<a href="RetailStoreHoursChannelEntity.md" target="_blank">Retail/RetailStoreHoursChannelEntity</a>|
|[OMInternalOrganizationId](#OMInternalOrganizationId)||<a href="RetailStoreHoursChannelEntity.md" target="_blank">Retail/RetailStoreHoursChannelEntity</a>|
|[OMOperatingUnitPartyNumber](#OMOperatingUnitPartyNumber)||<a href="RetailStoreHoursChannelEntity.md" target="_blank">Retail/RetailStoreHoursChannelEntity</a>|
|[OMInternalOrganizationPartyNumber](#OMInternalOrganizationPartyNumber)||<a href="RetailStoreHoursChannelEntity.md" target="_blank">Retail/RetailStoreHoursChannelEntity</a>|
|[BackingTable_RetailStoreHoursChannelRelationshipId](#BackingTable_RetailStoreHoursChannelRelationshipId)||<a href="RetailStoreHoursChannelEntity.md" target="_blank">Retail/RetailStoreHoursChannelEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="RetailStoreHoursChannelEntity.md" target="_blank">Retail/RetailStoreHoursChannelEntity</a>|

### <a href=#StoreHoursTemplateId name="StoreHoursTemplateId">StoreHoursTemplateId</a>

First included in: Retail/RetailStoreHoursChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StoreHoursTemplateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OMInternalOrganizationId name="OMInternalOrganizationId">OMInternalOrganizationId</a>

First included in: Retail/RetailStoreHoursChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OMInternalOrganizationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OMOperatingUnitPartyNumber name="OMOperatingUnitPartyNumber">OMOperatingUnitPartyNumber</a>

First included in: Retail/RetailStoreHoursChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OMOperatingUnitPartyNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OMInternalOrganizationPartyNumber name="OMInternalOrganizationPartyNumber">OMInternalOrganizationPartyNumber</a>

First included in: Retail/RetailStoreHoursChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OMInternalOrganizationPartyNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_RetailStoreHoursChannelRelationshipId name="BackingTable_RetailStoreHoursChannelRelationshipId">BackingTable_RetailStoreHoursChannelRelationshipId</a>

First included in: Retail/RetailStoreHoursChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>6</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailStoreHoursChannelRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: Retail/RetailStoreHoursChannelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>6</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PrimaryCompanyContextRelationshipId attribute are listed below.</summary>

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
