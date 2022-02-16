---
title: RetailBuyersPushEntity in InventoryAndAdvancedWarehouse - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Buyers push in InventoryAndAdvancedWarehouse(RetailBuyersPushEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Commerce/InventoryAndAdvancedWarehouse/RetailBuyersPushEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Buyers push</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[BuyersPushId](#BuyersPushId)||<a href="RetailBuyersPushEntity.md" target="_blank">InventoryAndAdvancedWarehouse/RetailBuyersPushEntity</a>|
|[Description](#Description)||<a href="RetailBuyersPushEntity.md" target="_blank">InventoryAndAdvancedWarehouse/RetailBuyersPushEntity</a>|
|[DistributionType](#DistributionType)||<a href="RetailBuyersPushEntity.md" target="_blank">InventoryAndAdvancedWarehouse/RetailBuyersPushEntity</a>|
|[Warehouse](#Warehouse)||<a href="RetailBuyersPushEntity.md" target="_blank">InventoryAndAdvancedWarehouse/RetailBuyersPushEntity</a>|
|[Site](#Site)||<a href="RetailBuyersPushEntity.md" target="_blank">InventoryAndAdvancedWarehouse/RetailBuyersPushEntity</a>|
|[ItemId](#ItemId)||<a href="RetailBuyersPushEntity.md" target="_blank">InventoryAndAdvancedWarehouse/RetailBuyersPushEntity</a>|
|[JournalCreated](#JournalCreated)||<a href="RetailBuyersPushEntity.md" target="_blank">InventoryAndAdvancedWarehouse/RetailBuyersPushEntity</a>|
|[LocationRecId](#LocationRecId)||<a href="RetailBuyersPushEntity.md" target="_blank">InventoryAndAdvancedWarehouse/RetailBuyersPushEntity</a>|
|[ReplenishmentHierarchyNode](#ReplenishmentHierarchyNode)||<a href="RetailBuyersPushEntity.md" target="_blank">InventoryAndAdvancedWarehouse/RetailBuyersPushEntity</a>|
|[RespectAssortments](#RespectAssortments)||<a href="RetailBuyersPushEntity.md" target="_blank">InventoryAndAdvancedWarehouse/RetailBuyersPushEntity</a>|
|[TransferOrderCreated](#TransferOrderCreated)||<a href="RetailBuyersPushEntity.md" target="_blank">InventoryAndAdvancedWarehouse/RetailBuyersPushEntity</a>|
|[OMHierarchyRelationship_ChildOrganization](#OMHierarchyRelationship_ChildOrganization)||<a href="RetailBuyersPushEntity.md" target="_blank">InventoryAndAdvancedWarehouse/RetailBuyersPushEntity</a>|
|[OMHierarchyRelationship_HierarchyType](#OMHierarchyRelationship_HierarchyType)||<a href="RetailBuyersPushEntity.md" target="_blank">InventoryAndAdvancedWarehouse/RetailBuyersPushEntity</a>|
|[ReplenishmentHierarchyValidFrom](#ReplenishmentHierarchyValidFrom)||<a href="RetailBuyersPushEntity.md" target="_blank">InventoryAndAdvancedWarehouse/RetailBuyersPushEntity</a>|
|[ReplenishmentHierarchyValidTo](#ReplenishmentHierarchyValidTo)||<a href="RetailBuyersPushEntity.md" target="_blank">InventoryAndAdvancedWarehouse/RetailBuyersPushEntity</a>|
|[ReplenishmentHierarchyTypeName](#ReplenishmentHierarchyTypeName)||<a href="RetailBuyersPushEntity.md" target="_blank">InventoryAndAdvancedWarehouse/RetailBuyersPushEntity</a>|
|[ReplenishmentOrganizationPartyNumber](#ReplenishmentOrganizationPartyNumber)||<a href="RetailBuyersPushEntity.md" target="_blank">InventoryAndAdvancedWarehouse/RetailBuyersPushEntity</a>|
|[BackingTable_RetailBuyersPushTableRelationshipId](#BackingTable_RetailBuyersPushTableRelationshipId)||<a href="RetailBuyersPushEntity.md" target="_blank">InventoryAndAdvancedWarehouse/RetailBuyersPushEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="RetailBuyersPushEntity.md" target="_blank">InventoryAndAdvancedWarehouse/RetailBuyersPushEntity</a>|

### <a href=#BuyersPushId name="BuyersPushId">BuyersPushId</a>

First included in: InventoryAndAdvancedWarehouse/RetailBuyersPushEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BuyersPushId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: InventoryAndAdvancedWarehouse/RetailBuyersPushEntity (this entity)  

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

### <a href=#DistributionType name="DistributionType">DistributionType</a>

First included in: InventoryAndAdvancedWarehouse/RetailBuyersPushEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DistributionType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Warehouse name="Warehouse">Warehouse</a>

First included in: InventoryAndAdvancedWarehouse/RetailBuyersPushEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Warehouse attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Site name="Site">Site</a>

First included in: InventoryAndAdvancedWarehouse/RetailBuyersPushEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Site attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemId name="ItemId">ItemId</a>

First included in: InventoryAndAdvancedWarehouse/RetailBuyersPushEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JournalCreated name="JournalCreated">JournalCreated</a>

First included in: InventoryAndAdvancedWarehouse/RetailBuyersPushEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalCreated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LocationRecId name="LocationRecId">LocationRecId</a>

First included in: InventoryAndAdvancedWarehouse/RetailBuyersPushEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LocationRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReplenishmentHierarchyNode name="ReplenishmentHierarchyNode">ReplenishmentHierarchyNode</a>

First included in: InventoryAndAdvancedWarehouse/RetailBuyersPushEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplenishmentHierarchyNode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RespectAssortments name="RespectAssortments">RespectAssortments</a>

First included in: InventoryAndAdvancedWarehouse/RetailBuyersPushEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RespectAssortments attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransferOrderCreated name="TransferOrderCreated">TransferOrderCreated</a>

First included in: InventoryAndAdvancedWarehouse/RetailBuyersPushEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferOrderCreated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OMHierarchyRelationship_ChildOrganization name="OMHierarchyRelationship_ChildOrganization">OMHierarchyRelationship_ChildOrganization</a>

First included in: InventoryAndAdvancedWarehouse/RetailBuyersPushEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OMHierarchyRelationship_ChildOrganization attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OMHierarchyRelationship_HierarchyType name="OMHierarchyRelationship_HierarchyType">OMHierarchyRelationship_HierarchyType</a>

First included in: InventoryAndAdvancedWarehouse/RetailBuyersPushEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OMHierarchyRelationship_HierarchyType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReplenishmentHierarchyValidFrom name="ReplenishmentHierarchyValidFrom">ReplenishmentHierarchyValidFrom</a>

First included in: InventoryAndAdvancedWarehouse/RetailBuyersPushEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplenishmentHierarchyValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReplenishmentHierarchyValidTo name="ReplenishmentHierarchyValidTo">ReplenishmentHierarchyValidTo</a>

First included in: InventoryAndAdvancedWarehouse/RetailBuyersPushEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplenishmentHierarchyValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReplenishmentHierarchyTypeName name="ReplenishmentHierarchyTypeName">ReplenishmentHierarchyTypeName</a>

First included in: InventoryAndAdvancedWarehouse/RetailBuyersPushEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplenishmentHierarchyTypeName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReplenishmentOrganizationPartyNumber name="ReplenishmentOrganizationPartyNumber">ReplenishmentOrganizationPartyNumber</a>

First included in: InventoryAndAdvancedWarehouse/RetailBuyersPushEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplenishmentOrganizationPartyNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_RetailBuyersPushTableRelationshipId name="BackingTable_RetailBuyersPushTableRelationshipId">BackingTable_RetailBuyersPushTableRelationshipId</a>

First included in: InventoryAndAdvancedWarehouse/RetailBuyersPushEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailBuyersPushTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Commerce/InventoryAndAdvancedWarehouse/WorksheetHeader/RetailBuyersPushTable.md" target="_blank">/core/operationsCommon/Tables/Commerce/InventoryAndAdvancedWarehouse/WorksheetHeader/RetailBuyersPushTable.cdm.json/RetailBuyersPushTable</a></td><td><a href="../../../Tables/Commerce/InventoryAndAdvancedWarehouse/WorksheetHeader/RetailBuyersPushTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndAdvancedWarehouse/RetailBuyersPushEntity (this entity)  

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
