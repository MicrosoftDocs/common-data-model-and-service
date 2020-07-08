---
title: TAMVendorRebateAgreementProductSelectionV2Entity in ProcurementAndSourcing - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/8/2020
ms.author: nebanfic
---

# Vendor rebate agreement product selections V2 in ProcurementAndSourcing(TAMVendorRebateAgreementProductSelectionV2Entity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/TAMVendorRebateAgreementProductSelectionV2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Vendor rebate agreement product selections V2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[InventDimID](#InventDimID)||<a href="TAMVendorRebateAgreementProductSelectionV2Entity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementProductSelectionV2Entity</a>|
|[ItemNumber](#ItemNumber)||<a href="TAMVendorRebateAgreementProductSelectionV2Entity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementProductSelectionV2Entity</a>|
|[RebateAgreementRefRecId](#RebateAgreementRefRecId)||<a href="TAMVendorRebateAgreementProductSelectionV2Entity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementProductSelectionV2Entity</a>|
|[ProductConfigurationId](#ProductConfigurationId)||<a href="TAMVendorRebateAgreementProductSelectionV2Entity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementProductSelectionV2Entity</a>|
|[ProductColorId](#ProductColorId)||<a href="TAMVendorRebateAgreementProductSelectionV2Entity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementProductSelectionV2Entity</a>|
|[QualifyingWarehouseId](#QualifyingWarehouseId)||<a href="TAMVendorRebateAgreementProductSelectionV2Entity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementProductSelectionV2Entity</a>|
|[QualifyingSiteId](#QualifyingSiteId)||<a href="TAMVendorRebateAgreementProductSelectionV2Entity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementProductSelectionV2Entity</a>|
|[ProductSizeId](#ProductSizeId)||<a href="TAMVendorRebateAgreementProductSelectionV2Entity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementProductSelectionV2Entity</a>|
|[ProductStyleId](#ProductStyleId)||<a href="TAMVendorRebateAgreementProductSelectionV2Entity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementProductSelectionV2Entity</a>|
|[ProductVersionId](#ProductVersionId)||<a href="TAMVendorRebateAgreementProductSelectionV2Entity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementProductSelectionV2Entity</a>|
|[ProductUnitSymbol](#ProductUnitSymbol)||<a href="TAMVendorRebateAgreementProductSelectionV2Entity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementProductSelectionV2Entity</a>|
|[VendorAccountNumber](#VendorAccountNumber)||<a href="TAMVendorRebateAgreementProductSelectionV2Entity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementProductSelectionV2Entity</a>|
|[RebateAgreementId](#RebateAgreementId)||<a href="TAMVendorRebateAgreementProductSelectionV2Entity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementProductSelectionV2Entity</a>|
|[BackingTable_TAMVendRebateItemRelationshipId](#BackingTable_TAMVendRebateItemRelationshipId)||<a href="TAMVendorRebateAgreementProductSelectionV2Entity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementProductSelectionV2Entity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="TAMVendorRebateAgreementProductSelectionV2Entity.md" target="_blank">ProcurementAndSourcing/TAMVendorRebateAgreementProductSelectionV2Entity</a>|

### <a href=#InventDimID name="InventDimID">InventDimID</a>

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementProductSelectionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventDimID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemNumber name="ItemNumber">ItemNumber</a>

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementProductSelectionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RebateAgreementRefRecId name="RebateAgreementRefRecId">RebateAgreementRefRecId</a>

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementProductSelectionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RebateAgreementRefRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductConfigurationId name="ProductConfigurationId">ProductConfigurationId</a>

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementProductSelectionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductConfigurationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductColorId name="ProductColorId">ProductColorId</a>

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementProductSelectionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductColorId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QualifyingWarehouseId name="QualifyingWarehouseId">QualifyingWarehouseId</a>

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementProductSelectionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QualifyingWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QualifyingSiteId name="QualifyingSiteId">QualifyingSiteId</a>

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementProductSelectionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QualifyingSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductSizeId name="ProductSizeId">ProductSizeId</a>

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementProductSelectionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductSizeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductStyleId name="ProductStyleId">ProductStyleId</a>

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementProductSelectionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductStyleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductVersionId name="ProductVersionId">ProductVersionId</a>

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementProductSelectionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductVersionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductUnitSymbol name="ProductUnitSymbol">ProductUnitSymbol</a>

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementProductSelectionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorAccountNumber name="VendorAccountNumber">VendorAccountNumber</a>

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementProductSelectionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Vendor account number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Vendor account number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RebateAgreementId name="RebateAgreementId">RebateAgreementId</a>

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementProductSelectionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rebate agreement id</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RebateAgreementId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Rebate agreement id</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_TAMVendRebateItemRelationshipId name="BackingTable_TAMVendRebateItemRelationshipId">BackingTable_TAMVendRebateItemRelationshipId</a>

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementProductSelectionV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_TAMVendRebateItemRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Main/TAMVendRebateItem.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Main/TAMVendRebateItem.cdm.json/TAMVendRebateItem</a></td><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Main/TAMVendRebateItem.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProcurementAndSourcing/TAMVendorRebateAgreementProductSelectionV2Entity (this entity)  

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
