---
title: TMSFreightBillMatchingAuditToleranceLevelEntity in Transportation - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/7/2020
ms.author: nebanfic
---

# Freight bill matching audit tolerance levels in Transportation

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/Transportation/TMSFreightBillMatchingAuditToleranceLevelEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Freight bill matching audit tolerance levels</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[UnderpaymentFreightBillReconcilliationReasonCode](#UnderpaymentFreightBillReconcilliationReasonCode)||<a href="TMSFreightBillMatchingAuditToleranceLevelEntity.md" target="_blank">Transportation/TMSFreightBillMatchingAuditToleranceLevelEntity</a>|
|[ToleranceLevelId](#ToleranceLevelId)||<a href="TMSFreightBillMatchingAuditToleranceLevelEntity.md" target="_blank">Transportation/TMSFreightBillMatchingAuditToleranceLevelEntity</a>|
|[MaximumAuditToleranceUnitType](#MaximumAuditToleranceUnitType)||<a href="TMSFreightBillMatchingAuditToleranceLevelEntity.md" target="_blank">Transportation/TMSFreightBillMatchingAuditToleranceLevelEntity</a>|
|[MinimumAuditToleranceUnitType](#MinimumAuditToleranceUnitType)||<a href="TMSFreightBillMatchingAuditToleranceLevelEntity.md" target="_blank">Transportation/TMSFreightBillMatchingAuditToleranceLevelEntity</a>|
|[ShippingCarrierId](#ShippingCarrierId)||<a href="TMSFreightBillMatchingAuditToleranceLevelEntity.md" target="_blank">Transportation/TMSFreightBillMatchingAuditToleranceLevelEntity</a>|
|[FreightBillTypeId](#FreightBillTypeId)||<a href="TMSFreightBillMatchingAuditToleranceLevelEntity.md" target="_blank">Transportation/TMSFreightBillMatchingAuditToleranceLevelEntity</a>|
|[WarehouseId](#WarehouseId)||<a href="TMSFreightBillMatchingAuditToleranceLevelEntity.md" target="_blank">Transportation/TMSFreightBillMatchingAuditToleranceLevelEntity</a>|
|[OperationalSiteId](#OperationalSiteId)||<a href="TMSFreightBillMatchingAuditToleranceLevelEntity.md" target="_blank">Transportation/TMSFreightBillMatchingAuditToleranceLevelEntity</a>|
|[OverpaymentFreightBillReconcilliationReasonCode](#OverpaymentFreightBillReconcilliationReasonCode)||<a href="TMSFreightBillMatchingAuditToleranceLevelEntity.md" target="_blank">Transportation/TMSFreightBillMatchingAuditToleranceLevelEntity</a>|
|[ToleranceSequenceNumber](#ToleranceSequenceNumber)||<a href="TMSFreightBillMatchingAuditToleranceLevelEntity.md" target="_blank">Transportation/TMSFreightBillMatchingAuditToleranceLevelEntity</a>|
|[MinimumAuditToleranceAmount](#MinimumAuditToleranceAmount)||<a href="TMSFreightBillMatchingAuditToleranceLevelEntity.md" target="_blank">Transportation/TMSFreightBillMatchingAuditToleranceLevelEntity</a>|
|[MinimumAuditTolerancePercentage](#MinimumAuditTolerancePercentage)||<a href="TMSFreightBillMatchingAuditToleranceLevelEntity.md" target="_blank">Transportation/TMSFreightBillMatchingAuditToleranceLevelEntity</a>|
|[MaximumAuditToleranceAmount](#MaximumAuditToleranceAmount)||<a href="TMSFreightBillMatchingAuditToleranceLevelEntity.md" target="_blank">Transportation/TMSFreightBillMatchingAuditToleranceLevelEntity</a>|
|[MaximumAuditTolerancePercentage](#MaximumAuditTolerancePercentage)||<a href="TMSFreightBillMatchingAuditToleranceLevelEntity.md" target="_blank">Transportation/TMSFreightBillMatchingAuditToleranceLevelEntity</a>|
|[BackingTable_TMSAuditMasterRelationshipId](#BackingTable_TMSAuditMasterRelationshipId)||<a href="TMSFreightBillMatchingAuditToleranceLevelEntity.md" target="_blank">Transportation/TMSFreightBillMatchingAuditToleranceLevelEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="TMSFreightBillMatchingAuditToleranceLevelEntity.md" target="_blank">Transportation/TMSFreightBillMatchingAuditToleranceLevelEntity</a>|

### <a href=#UnderpaymentFreightBillReconcilliationReasonCode name="UnderpaymentFreightBillReconcilliationReasonCode">UnderpaymentFreightBillReconcilliationReasonCode</a>

First included in: Transportation/TMSFreightBillMatchingAuditToleranceLevelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnderpaymentFreightBillReconcilliationReasonCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ToleranceLevelId name="ToleranceLevelId">ToleranceLevelId</a>

First included in: Transportation/TMSFreightBillMatchingAuditToleranceLevelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToleranceLevelId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumAuditToleranceUnitType name="MaximumAuditToleranceUnitType">MaximumAuditToleranceUnitType</a>

First included in: Transportation/TMSFreightBillMatchingAuditToleranceLevelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumAuditToleranceUnitType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinimumAuditToleranceUnitType name="MinimumAuditToleranceUnitType">MinimumAuditToleranceUnitType</a>

First included in: Transportation/TMSFreightBillMatchingAuditToleranceLevelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumAuditToleranceUnitType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingCarrierId name="ShippingCarrierId">ShippingCarrierId</a>

First included in: Transportation/TMSFreightBillMatchingAuditToleranceLevelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingCarrierId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FreightBillTypeId name="FreightBillTypeId">FreightBillTypeId</a>

First included in: Transportation/TMSFreightBillMatchingAuditToleranceLevelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FreightBillTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseId name="WarehouseId">WarehouseId</a>

First included in: Transportation/TMSFreightBillMatchingAuditToleranceLevelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperationalSiteId name="OperationalSiteId">OperationalSiteId</a>

First included in: Transportation/TMSFreightBillMatchingAuditToleranceLevelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperationalSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OverpaymentFreightBillReconcilliationReasonCode name="OverpaymentFreightBillReconcilliationReasonCode">OverpaymentFreightBillReconcilliationReasonCode</a>

First included in: Transportation/TMSFreightBillMatchingAuditToleranceLevelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OverpaymentFreightBillReconcilliationReasonCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ToleranceSequenceNumber name="ToleranceSequenceNumber">ToleranceSequenceNumber</a>

First included in: Transportation/TMSFreightBillMatchingAuditToleranceLevelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToleranceSequenceNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinimumAuditToleranceAmount name="MinimumAuditToleranceAmount">MinimumAuditToleranceAmount</a>

First included in: Transportation/TMSFreightBillMatchingAuditToleranceLevelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumAuditToleranceAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinimumAuditTolerancePercentage name="MinimumAuditTolerancePercentage">MinimumAuditTolerancePercentage</a>

First included in: Transportation/TMSFreightBillMatchingAuditToleranceLevelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumAuditTolerancePercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumAuditToleranceAmount name="MaximumAuditToleranceAmount">MaximumAuditToleranceAmount</a>

First included in: Transportation/TMSFreightBillMatchingAuditToleranceLevelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumAuditToleranceAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumAuditTolerancePercentage name="MaximumAuditTolerancePercentage">MaximumAuditTolerancePercentage</a>

First included in: Transportation/TMSFreightBillMatchingAuditToleranceLevelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumAuditTolerancePercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_TMSAuditMasterRelationshipId name="BackingTable_TMSAuditMasterRelationshipId">BackingTable_TMSAuditMasterRelationshipId</a>

First included in: Transportation/TMSFreightBillMatchingAuditToleranceLevelEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_TMSAuditMasterRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Transportation/Group/TMSAuditMaster.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Transportation/Group/TMSAuditMaster.cdm.json/TMSAuditMaster</a></td><td><a href="../../../Tables/SupplyChain/Transportation/Group/TMSAuditMaster.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: Transportation/TMSFreightBillMatchingAuditToleranceLevelEntity (this entity)  

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
