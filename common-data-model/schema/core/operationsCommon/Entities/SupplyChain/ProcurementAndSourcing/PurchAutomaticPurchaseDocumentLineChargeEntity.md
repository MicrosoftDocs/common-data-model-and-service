---
title: PurchAutomaticPurchaseDocumentLineChargeEntity in ProcurementAndSourcing - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/13/2020
ms.author: nebanfic
---

# Automatic purchase document line charges in ProcurementAndSourcing(PurchAutomaticPurchaseDocumentLineChargeEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/PurchAutomaticPurchaseDocumentLineChargeEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Automatic purchase document line charges</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ChargingVendorAccountNumber](#ChargingVendorAccountNumber)||<a href="PurchAutomaticPurchaseDocumentLineChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchAutomaticPurchaseDocumentLineChargeEntity</a>|
|[ChargingChargeVendorGroupId](#ChargingChargeVendorGroupId)||<a href="PurchAutomaticPurchaseDocumentLineChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchAutomaticPurchaseDocumentLineChargeEntity</a>|
|[ChargingItemNumber](#ChargingItemNumber)||<a href="PurchAutomaticPurchaseDocumentLineChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchAutomaticPurchaseDocumentLineChargeEntity</a>|
|[ChargingChargeProductGroupId](#ChargingChargeProductGroupId)||<a href="PurchAutomaticPurchaseDocumentLineChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchAutomaticPurchaseDocumentLineChargeEntity</a>|
|[LineNumber](#LineNumber)||<a href="PurchAutomaticPurchaseDocumentLineChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchAutomaticPurchaseDocumentLineChargeEntity</a>|
|[PurchaseDocumentCurrencyCode](#PurchaseDocumentCurrencyCode)||<a href="PurchAutomaticPurchaseDocumentLineChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchAutomaticPurchaseDocumentLineChargeEntity</a>|
|[PurchaseChargeCode](#PurchaseChargeCode)||<a href="PurchAutomaticPurchaseDocumentLineChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchAutomaticPurchaseDocumentLineChargeEntity</a>|
|[ChargeCategory](#ChargeCategory)||<a href="PurchAutomaticPurchaseDocumentLineChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchAutomaticPurchaseDocumentLineChargeEntity</a>|
|[ChargePercentage](#ChargePercentage)||<a href="PurchAutomaticPurchaseDocumentLineChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchAutomaticPurchaseDocumentLineChargeEntity</a>|
|[FixedChargeAmount](#FixedChargeAmount)||<a href="PurchAutomaticPurchaseDocumentLineChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchAutomaticPurchaseDocumentLineChargeEntity</a>|
|[ProportionalChargeAmount](#ProportionalChargeAmount)||<a href="PurchAutomaticPurchaseDocumentLineChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchAutomaticPurchaseDocumentLineChargeEntity</a>|
|[UnitChargeAmount](#UnitChargeAmount)||<a href="PurchAutomaticPurchaseDocumentLineChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchAutomaticPurchaseDocumentLineChargeEntity</a>|
|[IntercompanyChargePercentage](#IntercompanyChargePercentage)||<a href="PurchAutomaticPurchaseDocumentLineChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchAutomaticPurchaseDocumentLineChargeEntity</a>|
|[Value](#Value)||<a href="PurchAutomaticPurchaseDocumentLineChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchAutomaticPurchaseDocumentLineChargeEntity</a>|
|[ChargeAccountingCurrencyCode](#ChargeAccountingCurrencyCode)||<a href="PurchAutomaticPurchaseDocumentLineChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchAutomaticPurchaseDocumentLineChargeEntity</a>|
|[SalesTaxGroupCode](#SalesTaxGroupCode)||<a href="PurchAutomaticPurchaseDocumentLineChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchAutomaticPurchaseDocumentLineChargeEntity</a>|
|[AccountCode](#AccountCode)||<a href="PurchAutomaticPurchaseDocumentLineChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchAutomaticPurchaseDocumentLineChargeEntity</a>|
|[AccountRelation](#AccountRelation)||<a href="PurchAutomaticPurchaseDocumentLineChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchAutomaticPurchaseDocumentLineChargeEntity</a>|
|[ItemCode](#ItemCode)||<a href="PurchAutomaticPurchaseDocumentLineChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchAutomaticPurchaseDocumentLineChargeEntity</a>|
|[ItemRelation](#ItemRelation)||<a href="PurchAutomaticPurchaseDocumentLineChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchAutomaticPurchaseDocumentLineChargeEntity</a>|
|[BackingTable_MarkupAutoLineRelationshipId](#BackingTable_MarkupAutoLineRelationshipId)||<a href="PurchAutomaticPurchaseDocumentLineChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchAutomaticPurchaseDocumentLineChargeEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="PurchAutomaticPurchaseDocumentLineChargeEntity.md" target="_blank">ProcurementAndSourcing/PurchAutomaticPurchaseDocumentLineChargeEntity</a>|

### <a href=#ChargingVendorAccountNumber name="ChargingVendorAccountNumber">ChargingVendorAccountNumber</a>

First included in: ProcurementAndSourcing/PurchAutomaticPurchaseDocumentLineChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargingVendorAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChargingChargeVendorGroupId name="ChargingChargeVendorGroupId">ChargingChargeVendorGroupId</a>

First included in: ProcurementAndSourcing/PurchAutomaticPurchaseDocumentLineChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargingChargeVendorGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChargingItemNumber name="ChargingItemNumber">ChargingItemNumber</a>

First included in: ProcurementAndSourcing/PurchAutomaticPurchaseDocumentLineChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargingItemNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChargingChargeProductGroupId name="ChargingChargeProductGroupId">ChargingChargeProductGroupId</a>

First included in: ProcurementAndSourcing/PurchAutomaticPurchaseDocumentLineChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargingChargeProductGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: ProcurementAndSourcing/PurchAutomaticPurchaseDocumentLineChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseDocumentCurrencyCode name="PurchaseDocumentCurrencyCode">PurchaseDocumentCurrencyCode</a>

First included in: ProcurementAndSourcing/PurchAutomaticPurchaseDocumentLineChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseDocumentCurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseChargeCode name="PurchaseChargeCode">PurchaseChargeCode</a>

First included in: ProcurementAndSourcing/PurchAutomaticPurchaseDocumentLineChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseChargeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChargeCategory name="ChargeCategory">ChargeCategory</a>

First included in: ProcurementAndSourcing/PurchAutomaticPurchaseDocumentLineChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargeCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChargePercentage name="ChargePercentage">ChargePercentage</a>

First included in: ProcurementAndSourcing/PurchAutomaticPurchaseDocumentLineChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargePercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FixedChargeAmount name="FixedChargeAmount">FixedChargeAmount</a>

First included in: ProcurementAndSourcing/PurchAutomaticPurchaseDocumentLineChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedChargeAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProportionalChargeAmount name="ProportionalChargeAmount">ProportionalChargeAmount</a>

First included in: ProcurementAndSourcing/PurchAutomaticPurchaseDocumentLineChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProportionalChargeAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnitChargeAmount name="UnitChargeAmount">UnitChargeAmount</a>

First included in: ProcurementAndSourcing/PurchAutomaticPurchaseDocumentLineChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitChargeAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntercompanyChargePercentage name="IntercompanyChargePercentage">IntercompanyChargePercentage</a>

First included in: ProcurementAndSourcing/PurchAutomaticPurchaseDocumentLineChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntercompanyChargePercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Value name="Value">Value</a>

First included in: ProcurementAndSourcing/PurchAutomaticPurchaseDocumentLineChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Value attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChargeAccountingCurrencyCode name="ChargeAccountingCurrencyCode">ChargeAccountingCurrencyCode</a>

First included in: ProcurementAndSourcing/PurchAutomaticPurchaseDocumentLineChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargeAccountingCurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxGroupCode name="SalesTaxGroupCode">SalesTaxGroupCode</a>

First included in: ProcurementAndSourcing/PurchAutomaticPurchaseDocumentLineChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountCode name="AccountCode">AccountCode</a>

First included in: ProcurementAndSourcing/PurchAutomaticPurchaseDocumentLineChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountRelation name="AccountRelation">AccountRelation</a>

First included in: ProcurementAndSourcing/PurchAutomaticPurchaseDocumentLineChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountRelation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemCode name="ItemCode">ItemCode</a>

First included in: ProcurementAndSourcing/PurchAutomaticPurchaseDocumentLineChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemRelation name="ItemRelation">ItemRelation</a>

First included in: ProcurementAndSourcing/PurchAutomaticPurchaseDocumentLineChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemRelation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_MarkupAutoLineRelationshipId name="BackingTable_MarkupAutoLineRelationshipId">BackingTable_MarkupAutoLineRelationshipId</a>

First included in: ProcurementAndSourcing/PurchAutomaticPurchaseDocumentLineChargeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_MarkupAutoLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Group/MarkupAutoLine.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Group/MarkupAutoLine.cdm.json/MarkupAutoLine</a></td><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Group/MarkupAutoLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProcurementAndSourcing/PurchAutomaticPurchaseDocumentLineChargeEntity (this entity)  

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
