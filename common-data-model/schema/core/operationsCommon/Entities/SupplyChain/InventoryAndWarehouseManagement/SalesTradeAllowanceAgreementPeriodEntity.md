---
title: SalesTradeAllowanceAgreementPeriodEntity in InventoryAndWarehouseManagement - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Trade allowance agreement periods in InventoryAndWarehouseManagement(SalesTradeAllowanceAgreementPeriodEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/InventoryAndWarehouseManagement/SalesTradeAllowanceAgreementPeriodEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Trade allowance agreement periods</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ToOrderDate](#ToOrderDate)||<a href="SalesTradeAllowanceAgreementPeriodEntity.md" target="_blank">InventoryAndWarehouseManagement/SalesTradeAllowanceAgreementPeriodEntity</a>|
|[FromOrderDate](#FromOrderDate)||<a href="SalesTradeAllowanceAgreementPeriodEntity.md" target="_blank">InventoryAndWarehouseManagement/SalesTradeAllowanceAgreementPeriodEntity</a>|
|[ToLumpSumPayoutDate](#ToLumpSumPayoutDate)||<a href="SalesTradeAllowanceAgreementPeriodEntity.md" target="_blank">InventoryAndWarehouseManagement/SalesTradeAllowanceAgreementPeriodEntity</a>|
|[FromLumpSumPayoutDate](#FromLumpSumPayoutDate)||<a href="SalesTradeAllowanceAgreementPeriodEntity.md" target="_blank">InventoryAndWarehouseManagement/SalesTradeAllowanceAgreementPeriodEntity</a>|
|[PeriodName](#PeriodName)||<a href="SalesTradeAllowanceAgreementPeriodEntity.md" target="_blank">InventoryAndWarehouseManagement/SalesTradeAllowanceAgreementPeriodEntity</a>|
|[ToRequestedShipDate](#ToRequestedShipDate)||<a href="SalesTradeAllowanceAgreementPeriodEntity.md" target="_blank">InventoryAndWarehouseManagement/SalesTradeAllowanceAgreementPeriodEntity</a>|
|[FromRequestedShipDate](#FromRequestedShipDate)||<a href="SalesTradeAllowanceAgreementPeriodEntity.md" target="_blank">InventoryAndWarehouseManagement/SalesTradeAllowanceAgreementPeriodEntity</a>|
|[ToRequestedReceiptDate](#ToRequestedReceiptDate)||<a href="SalesTradeAllowanceAgreementPeriodEntity.md" target="_blank">InventoryAndWarehouseManagement/SalesTradeAllowanceAgreementPeriodEntity</a>|
|[FromRequestedReceiptDate](#FromRequestedReceiptDate)||<a href="SalesTradeAllowanceAgreementPeriodEntity.md" target="_blank">InventoryAndWarehouseManagement/SalesTradeAllowanceAgreementPeriodEntity</a>|
|[BackingTable_TAMPromotionPeriodRelationshipId](#BackingTable_TAMPromotionPeriodRelationshipId)||<a href="SalesTradeAllowanceAgreementPeriodEntity.md" target="_blank">InventoryAndWarehouseManagement/SalesTradeAllowanceAgreementPeriodEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="SalesTradeAllowanceAgreementPeriodEntity.md" target="_blank">InventoryAndWarehouseManagement/SalesTradeAllowanceAgreementPeriodEntity</a>|

### <a href=#ToOrderDate name="ToOrderDate">ToOrderDate</a>

First included in: InventoryAndWarehouseManagement/SalesTradeAllowanceAgreementPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToOrderDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FromOrderDate name="FromOrderDate">FromOrderDate</a>

First included in: InventoryAndWarehouseManagement/SalesTradeAllowanceAgreementPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromOrderDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ToLumpSumPayoutDate name="ToLumpSumPayoutDate">ToLumpSumPayoutDate</a>

First included in: InventoryAndWarehouseManagement/SalesTradeAllowanceAgreementPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToLumpSumPayoutDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FromLumpSumPayoutDate name="FromLumpSumPayoutDate">FromLumpSumPayoutDate</a>

First included in: InventoryAndWarehouseManagement/SalesTradeAllowanceAgreementPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromLumpSumPayoutDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PeriodName name="PeriodName">PeriodName</a>

First included in: InventoryAndWarehouseManagement/SalesTradeAllowanceAgreementPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ToRequestedShipDate name="ToRequestedShipDate">ToRequestedShipDate</a>

First included in: InventoryAndWarehouseManagement/SalesTradeAllowanceAgreementPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToRequestedShipDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FromRequestedShipDate name="FromRequestedShipDate">FromRequestedShipDate</a>

First included in: InventoryAndWarehouseManagement/SalesTradeAllowanceAgreementPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromRequestedShipDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ToRequestedReceiptDate name="ToRequestedReceiptDate">ToRequestedReceiptDate</a>

First included in: InventoryAndWarehouseManagement/SalesTradeAllowanceAgreementPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToRequestedReceiptDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FromRequestedReceiptDate name="FromRequestedReceiptDate">FromRequestedReceiptDate</a>

First included in: InventoryAndWarehouseManagement/SalesTradeAllowanceAgreementPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromRequestedReceiptDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_TAMPromotionPeriodRelationshipId name="BackingTable_TAMPromotionPeriodRelationshipId">BackingTable_TAMPromotionPeriodRelationshipId</a>

First included in: InventoryAndWarehouseManagement/SalesTradeAllowanceAgreementPeriodEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_TAMPromotionPeriodRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Main/TAMPromotionPeriod.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Main/TAMPromotionPeriod.cdm.json/TAMPromotionPeriod</a></td><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Main/TAMPromotionPeriod.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: InventoryAndWarehouseManagement/SalesTradeAllowanceAgreementPeriodEntity (this entity)  

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
