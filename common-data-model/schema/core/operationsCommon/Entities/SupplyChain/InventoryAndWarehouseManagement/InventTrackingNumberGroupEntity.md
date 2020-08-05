---
title: InventTrackingNumberGroupEntity in InventoryAndWarehouseManagement - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Tracking number groups in InventoryAndWarehouseManagement(InventTrackingNumberGroupEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/InventTrackingNumberGroupEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tracking number groups</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[IsExpectedDateIncluded](#IsExpectedDateIncluded)||<a href="InventTrackingNumberGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTrackingNumberGroupEntity</a>|
|[IsLotIdIncluded](#IsLotIdIncluded)||<a href="InventTrackingNumberGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTrackingNumberGroupEntity</a>|
|[IsNumberSequenceNumberIncluded](#IsNumberSequenceNumberIncluded)||<a href="InventTrackingNumberGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTrackingNumberGroupEntity</a>|
|[IsReferenceNumberIncluded](#IsReferenceNumberIncluded)||<a href="InventTrackingNumberGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTrackingNumberGroupEntity</a>|
|[IsActivatedForInventory](#IsActivatedForInventory)||<a href="InventTrackingNumberGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTrackingNumberGroupEntity</a>|
|[IsActivatedForKanban](#IsActivatedForKanban)||<a href="InventTrackingNumberGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTrackingNumberGroupEntity</a>|
|[IsNumberManuallyAllocated](#IsNumberManuallyAllocated)||<a href="InventTrackingNumberGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTrackingNumberGroupEntity</a>|
|[GroupName](#GroupName)||<a href="InventTrackingNumberGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTrackingNumberGroupEntity</a>|
|[NumberSequenceRecId](#NumberSequenceRecId)||<a href="InventTrackingNumberGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTrackingNumberGroupEntity</a>|
|[GroupCode](#GroupCode)||<a href="InventTrackingNumberGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTrackingNumberGroupEntity</a>|
|[IsOnlyForInventoryTransactions](#IsOnlyForInventoryTransactions)||<a href="InventTrackingNumberGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTrackingNumberGroupEntity</a>|
|[InventoryQuantityTreshold](#InventoryQuantityTreshold)||<a href="InventTrackingNumberGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTrackingNumberGroupEntity</a>|
|[WillPhysicalUpdateAssignNumber](#WillPhysicalUpdateAssignNumber)||<a href="InventTrackingNumberGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTrackingNumberGroupEntity</a>|
|[IsActivatedForProduction](#IsActivatedForProduction)||<a href="InventTrackingNumberGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTrackingNumberGroupEntity</a>|
|[IsActivatedForPurchase](#IsActivatedForPurchase)||<a href="InventTrackingNumberGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTrackingNumberGroupEntity</a>|
|[IsActivatedForSales](#IsActivatedForSales)||<a href="InventTrackingNumberGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTrackingNumberGroupEntity</a>|
|[NumberSequenceCode](#NumberSequenceCode)||<a href="InventTrackingNumberGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTrackingNumberGroupEntity</a>|
|[NumberSequenceTable_NumberSequenceScope](#NumberSequenceTable_NumberSequenceScope)||<a href="InventTrackingNumberGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTrackingNumberGroupEntity</a>|
|[NumberSequenceScopeDataArea](#NumberSequenceScopeDataArea)||<a href="InventTrackingNumberGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTrackingNumberGroupEntity</a>|
|[BackingTable_InventNumGroupRelationshipId](#BackingTable_InventNumGroupRelationshipId)||<a href="InventTrackingNumberGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTrackingNumberGroupEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="InventTrackingNumberGroupEntity.md" target="_blank">InventoryAndWarehouseManagement/InventTrackingNumberGroupEntity</a>|

### <a href=#IsExpectedDateIncluded name="IsExpectedDateIncluded">IsExpectedDateIncluded</a>

First included in: InventoryAndWarehouseManagement/InventTrackingNumberGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsExpectedDateIncluded attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsLotIdIncluded name="IsLotIdIncluded">IsLotIdIncluded</a>

First included in: InventoryAndWarehouseManagement/InventTrackingNumberGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsLotIdIncluded attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsNumberSequenceNumberIncluded name="IsNumberSequenceNumberIncluded">IsNumberSequenceNumberIncluded</a>

First included in: InventoryAndWarehouseManagement/InventTrackingNumberGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsNumberSequenceNumberIncluded attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsReferenceNumberIncluded name="IsReferenceNumberIncluded">IsReferenceNumberIncluded</a>

First included in: InventoryAndWarehouseManagement/InventTrackingNumberGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsReferenceNumberIncluded attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsActivatedForInventory name="IsActivatedForInventory">IsActivatedForInventory</a>

First included in: InventoryAndWarehouseManagement/InventTrackingNumberGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsActivatedForInventory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsActivatedForKanban name="IsActivatedForKanban">IsActivatedForKanban</a>

First included in: InventoryAndWarehouseManagement/InventTrackingNumberGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsActivatedForKanban attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsNumberManuallyAllocated name="IsNumberManuallyAllocated">IsNumberManuallyAllocated</a>

First included in: InventoryAndWarehouseManagement/InventTrackingNumberGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsNumberManuallyAllocated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GroupName name="GroupName">GroupName</a>

First included in: InventoryAndWarehouseManagement/InventTrackingNumberGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GroupName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberSequenceRecId name="NumberSequenceRecId">NumberSequenceRecId</a>

First included in: InventoryAndWarehouseManagement/InventTrackingNumberGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberSequenceRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GroupCode name="GroupCode">GroupCode</a>

First included in: InventoryAndWarehouseManagement/InventTrackingNumberGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsOnlyForInventoryTransactions name="IsOnlyForInventoryTransactions">IsOnlyForInventoryTransactions</a>

First included in: InventoryAndWarehouseManagement/InventTrackingNumberGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsOnlyForInventoryTransactions attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryQuantityTreshold name="InventoryQuantityTreshold">InventoryQuantityTreshold</a>

First included in: InventoryAndWarehouseManagement/InventTrackingNumberGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryQuantityTreshold attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillPhysicalUpdateAssignNumber name="WillPhysicalUpdateAssignNumber">WillPhysicalUpdateAssignNumber</a>

First included in: InventoryAndWarehouseManagement/InventTrackingNumberGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillPhysicalUpdateAssignNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsActivatedForProduction name="IsActivatedForProduction">IsActivatedForProduction</a>

First included in: InventoryAndWarehouseManagement/InventTrackingNumberGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsActivatedForProduction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsActivatedForPurchase name="IsActivatedForPurchase">IsActivatedForPurchase</a>

First included in: InventoryAndWarehouseManagement/InventTrackingNumberGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsActivatedForPurchase attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsActivatedForSales name="IsActivatedForSales">IsActivatedForSales</a>

First included in: InventoryAndWarehouseManagement/InventTrackingNumberGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsActivatedForSales attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberSequenceCode name="NumberSequenceCode">NumberSequenceCode</a>

First included in: InventoryAndWarehouseManagement/InventTrackingNumberGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberSequenceCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberSequenceTable_NumberSequenceScope name="NumberSequenceTable_NumberSequenceScope">NumberSequenceTable_NumberSequenceScope</a>

First included in: InventoryAndWarehouseManagement/InventTrackingNumberGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberSequenceTable_NumberSequenceScope attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberSequenceScopeDataArea name="NumberSequenceScopeDataArea">NumberSequenceScopeDataArea</a>

First included in: InventoryAndWarehouseManagement/InventTrackingNumberGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberSequenceScopeDataArea attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_InventNumGroupRelationshipId name="BackingTable_InventNumGroupRelationshipId">BackingTable_InventNumGroupRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventTrackingNumberGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_InventNumGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Group/InventNumGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/InventNumGroup.cdm.json/InventNumGroup</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Group/InventNumGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/InventTrackingNumberGroupEntity (this entity)  

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
