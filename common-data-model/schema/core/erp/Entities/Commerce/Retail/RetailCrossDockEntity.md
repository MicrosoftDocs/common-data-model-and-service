---
title: RetailCrossDockEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/16/2020
ms.author: nebanfic
---

# @Retail:CrossDockEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Entities/Commerce/Retail/RetailCrossDockEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.Application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>@Retail:CrossDockEntity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Entity|
|---|---|---|
|[CrossDockId](#CrossDockId)||<a href="RetailCrossDockEntity.md" target="_blank">Retail/RetailCrossDockEntity</a>|
|[Description](#Description)||<a href="RetailCrossDockEntity.md" target="_blank">Retail/RetailCrossDockEntity</a>|
|[DistributionType](#DistributionType)||<a href="RetailCrossDockEntity.md" target="_blank">Retail/RetailCrossDockEntity</a>|
|[ItemId](#ItemId)||<a href="RetailCrossDockEntity.md" target="_blank">Retail/RetailCrossDockEntity</a>|
|[JournalCreated](#JournalCreated)||<a href="RetailCrossDockEntity.md" target="_blank">Retail/RetailCrossDockEntity</a>|
|[LocationRecId](#LocationRecId)||<a href="RetailCrossDockEntity.md" target="_blank">Retail/RetailCrossDockEntity</a>|
|[PurchaseId](#PurchaseId)||<a href="RetailCrossDockEntity.md" target="_blank">Retail/RetailCrossDockEntity</a>|
|[ReplenishmentHierarchyNode](#ReplenishmentHierarchyNode)||<a href="RetailCrossDockEntity.md" target="_blank">Retail/RetailCrossDockEntity</a>|
|[RespectAssortments](#RespectAssortments)||<a href="RetailCrossDockEntity.md" target="_blank">Retail/RetailCrossDockEntity</a>|
|[TransferOrderCreated](#TransferOrderCreated)||<a href="RetailCrossDockEntity.md" target="_blank">Retail/RetailCrossDockEntity</a>|
|[OMHierarchyRelationship_ChildOrganization](#OMHierarchyRelationship_ChildOrganization)||<a href="RetailCrossDockEntity.md" target="_blank">Retail/RetailCrossDockEntity</a>|
|[OMHierarchyRelationship_HierarchyType](#OMHierarchyRelationship_HierarchyType)||<a href="RetailCrossDockEntity.md" target="_blank">Retail/RetailCrossDockEntity</a>|
|[ReplenishmentHierarchyValidFrom](#ReplenishmentHierarchyValidFrom)||<a href="RetailCrossDockEntity.md" target="_blank">Retail/RetailCrossDockEntity</a>|
|[ReplenishmentHierarchyValidTo](#ReplenishmentHierarchyValidTo)||<a href="RetailCrossDockEntity.md" target="_blank">Retail/RetailCrossDockEntity</a>|
|[ReplenishmentHierarchyTypeName](#ReplenishmentHierarchyTypeName)||<a href="RetailCrossDockEntity.md" target="_blank">Retail/RetailCrossDockEntity</a>|
|[ReplenishmentOrganizationPartyNumber](#ReplenishmentOrganizationPartyNumber)||<a href="RetailCrossDockEntity.md" target="_blank">Retail/RetailCrossDockEntity</a>|
|[BackingTable_RetailBuyersPushTableRelationshipId](#BackingTable_RetailBuyersPushTableRelationshipId)||<a href="RetailCrossDockEntity.md" target="_blank">Retail/RetailCrossDockEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="RetailCrossDockEntity.md" target="_blank">Retail/RetailCrossDockEntity</a>|

### <a href=#CrossDockId name="CrossDockId">CrossDockId</a>

First included in: Retail/RetailCrossDockEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CrossDockId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: Retail/RetailCrossDockEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DistributionType name="DistributionType">DistributionType</a>

First included in: Retail/RetailCrossDockEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DistributionType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemId name="ItemId">ItemId</a>

First included in: Retail/RetailCrossDockEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JournalCreated name="JournalCreated">JournalCreated</a>

First included in: Retail/RetailCrossDockEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalCreated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LocationRecId name="LocationRecId">LocationRecId</a>

First included in: Retail/RetailCrossDockEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LocationRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseId name="PurchaseId">PurchaseId</a>

First included in: Retail/RetailCrossDockEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReplenishmentHierarchyNode name="ReplenishmentHierarchyNode">ReplenishmentHierarchyNode</a>

First included in: Retail/RetailCrossDockEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplenishmentHierarchyNode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RespectAssortments name="RespectAssortments">RespectAssortments</a>

First included in: Retail/RetailCrossDockEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RespectAssortments attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransferOrderCreated name="TransferOrderCreated">TransferOrderCreated</a>

First included in: Retail/RetailCrossDockEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferOrderCreated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OMHierarchyRelationship_ChildOrganization name="OMHierarchyRelationship_ChildOrganization">OMHierarchyRelationship_ChildOrganization</a>

First included in: Retail/RetailCrossDockEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OMHierarchyRelationship_ChildOrganization attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OMHierarchyRelationship_HierarchyType name="OMHierarchyRelationship_HierarchyType">OMHierarchyRelationship_HierarchyType</a>

First included in: Retail/RetailCrossDockEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OMHierarchyRelationship_HierarchyType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReplenishmentHierarchyValidFrom name="ReplenishmentHierarchyValidFrom">ReplenishmentHierarchyValidFrom</a>

First included in: Retail/RetailCrossDockEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplenishmentHierarchyValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReplenishmentHierarchyValidTo name="ReplenishmentHierarchyValidTo">ReplenishmentHierarchyValidTo</a>

First included in: Retail/RetailCrossDockEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplenishmentHierarchyValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReplenishmentHierarchyTypeName name="ReplenishmentHierarchyTypeName">ReplenishmentHierarchyTypeName</a>

First included in: Retail/RetailCrossDockEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplenishmentHierarchyTypeName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReplenishmentOrganizationPartyNumber name="ReplenishmentOrganizationPartyNumber">ReplenishmentOrganizationPartyNumber</a>

First included in: Retail/RetailCrossDockEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplenishmentOrganizationPartyNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_RetailBuyersPushTableRelationshipId name="BackingTable_RetailBuyersPushTableRelationshipId">BackingTable_RetailBuyersPushTableRelationshipId</a>

First included in: Retail/RetailCrossDockEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>6</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailBuyersPushTableRelationshipId attribute are listed below.</summary>

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

First included in: Retail/RetailCrossDockEntity (this entity)  

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
