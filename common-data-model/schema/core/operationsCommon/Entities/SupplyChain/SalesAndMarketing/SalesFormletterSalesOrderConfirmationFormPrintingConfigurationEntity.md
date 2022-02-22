---
title: SalesFormletterSalesOrderConfirmationFormPrintingConfigurationEntity in SalesAndMarketing - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Sales order confirmation form printing configurations in SalesAndMarketing(SalesFormletterSalesOrderConfirmationFormPrintingConfigurationEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/SalesAndMarketing/SalesFormletterSalesOrderConfirmationFormPrintingConfigurationEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales order confirmation form printing configurations</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[IsInventoryStatusIdDisplayed](#IsInventoryStatusIdDisplayed)||<a href="SalesFormletterSalesOrderConfirmationFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesOrderConfirmationFormPrintingConfigurationEntity</a>|
|[IsItemBatchNumberDisplayed](#IsItemBatchNumberDisplayed)||<a href="SalesFormletterSalesOrderConfirmationFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesOrderConfirmationFormPrintingConfigurationEntity</a>|
|[IsItemSerialNumberDisplayed](#IsItemSerialNumberDisplayed)||<a href="SalesFormletterSalesOrderConfirmationFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesOrderConfirmationFormPrintingConfigurationEntity</a>|
|[IsLicensePlateNumberDisplayed](#IsLicensePlateNumberDisplayed)||<a href="SalesFormletterSalesOrderConfirmationFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesOrderConfirmationFormPrintingConfigurationEntity</a>|
|[IsProductColorIdDisplayed](#IsProductColorIdDisplayed)||<a href="SalesFormletterSalesOrderConfirmationFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesOrderConfirmationFormPrintingConfigurationEntity</a>|
|[IsProductConfigurationIdDisplayed](#IsProductConfigurationIdDisplayed)||<a href="SalesFormletterSalesOrderConfirmationFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesOrderConfirmationFormPrintingConfigurationEntity</a>|
|[IsProductSizeIdDisplayed](#IsProductSizeIdDisplayed)||<a href="SalesFormletterSalesOrderConfirmationFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesOrderConfirmationFormPrintingConfigurationEntity</a>|
|[IsProductStyleIdDisplayed](#IsProductStyleIdDisplayed)||<a href="SalesFormletterSalesOrderConfirmationFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesOrderConfirmationFormPrintingConfigurationEntity</a>|
|[IsProductVersionIdDisplayed](#IsProductVersionIdDisplayed)||<a href="SalesFormletterSalesOrderConfirmationFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesOrderConfirmationFormPrintingConfigurationEntity</a>|
|[IsShippingSiteIdDisplayed](#IsShippingSiteIdDisplayed)||<a href="SalesFormletterSalesOrderConfirmationFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesOrderConfirmationFormPrintingConfigurationEntity</a>|
|[IsShippingWarehouseIdDisplayed](#IsShippingWarehouseIdDisplayed)||<a href="SalesFormletterSalesOrderConfirmationFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesOrderConfirmationFormPrintingConfigurationEntity</a>|
|[IsShippingWarehouseLocationIdDisplayed](#IsShippingWarehouseLocationIdDisplayed)||<a href="SalesFormletterSalesOrderConfirmationFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesOrderConfirmationFormPrintingConfigurationEntity</a>|
|[InventDimConfirm](#InventDimConfirm)||<a href="SalesFormletterSalesOrderConfirmationFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesOrderConfirmationFormPrintingConfigurationEntity</a>|
|[PaperFormat](#PaperFormat)||<a href="SalesFormletterSalesOrderConfirmationFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesOrderConfirmationFormPrintingConfigurationEntity</a>|
|[DocumentAttachmentDisplayRule](#DocumentAttachmentDisplayRule)||<a href="SalesFormletterSalesOrderConfirmationFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesOrderConfirmationFormPrintingConfigurationEntity</a>|
|[DisplayedDocumentAttachmentTypeCode](#DisplayedDocumentAttachmentTypeCode)||<a href="SalesFormletterSalesOrderConfirmationFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesOrderConfirmationFormPrintingConfigurationEntity</a>|
|[BackingTable_CustFormletterParametersRelationshipId](#BackingTable_CustFormletterParametersRelationshipId)||<a href="SalesFormletterSalesOrderConfirmationFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesOrderConfirmationFormPrintingConfigurationEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="SalesFormletterSalesOrderConfirmationFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesOrderConfirmationFormPrintingConfigurationEntity</a>|

### <a href=#IsInventoryStatusIdDisplayed name="IsInventoryStatusIdDisplayed">IsInventoryStatusIdDisplayed</a>

First included in: SalesAndMarketing/SalesFormletterSalesOrderConfirmationFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsInventoryStatusIdDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsItemBatchNumberDisplayed name="IsItemBatchNumberDisplayed">IsItemBatchNumberDisplayed</a>

First included in: SalesAndMarketing/SalesFormletterSalesOrderConfirmationFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsItemBatchNumberDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsItemSerialNumberDisplayed name="IsItemSerialNumberDisplayed">IsItemSerialNumberDisplayed</a>

First included in: SalesAndMarketing/SalesFormletterSalesOrderConfirmationFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsItemSerialNumberDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsLicensePlateNumberDisplayed name="IsLicensePlateNumberDisplayed">IsLicensePlateNumberDisplayed</a>

First included in: SalesAndMarketing/SalesFormletterSalesOrderConfirmationFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsLicensePlateNumberDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProductColorIdDisplayed name="IsProductColorIdDisplayed">IsProductColorIdDisplayed</a>

First included in: SalesAndMarketing/SalesFormletterSalesOrderConfirmationFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProductColorIdDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProductConfigurationIdDisplayed name="IsProductConfigurationIdDisplayed">IsProductConfigurationIdDisplayed</a>

First included in: SalesAndMarketing/SalesFormletterSalesOrderConfirmationFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProductConfigurationIdDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProductSizeIdDisplayed name="IsProductSizeIdDisplayed">IsProductSizeIdDisplayed</a>

First included in: SalesAndMarketing/SalesFormletterSalesOrderConfirmationFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProductSizeIdDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProductStyleIdDisplayed name="IsProductStyleIdDisplayed">IsProductStyleIdDisplayed</a>

First included in: SalesAndMarketing/SalesFormletterSalesOrderConfirmationFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProductStyleIdDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProductVersionIdDisplayed name="IsProductVersionIdDisplayed">IsProductVersionIdDisplayed</a>

First included in: SalesAndMarketing/SalesFormletterSalesOrderConfirmationFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProductVersionIdDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsShippingSiteIdDisplayed name="IsShippingSiteIdDisplayed">IsShippingSiteIdDisplayed</a>

First included in: SalesAndMarketing/SalesFormletterSalesOrderConfirmationFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsShippingSiteIdDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsShippingWarehouseIdDisplayed name="IsShippingWarehouseIdDisplayed">IsShippingWarehouseIdDisplayed</a>

First included in: SalesAndMarketing/SalesFormletterSalesOrderConfirmationFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsShippingWarehouseIdDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsShippingWarehouseLocationIdDisplayed name="IsShippingWarehouseLocationIdDisplayed">IsShippingWarehouseLocationIdDisplayed</a>

First included in: SalesAndMarketing/SalesFormletterSalesOrderConfirmationFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsShippingWarehouseLocationIdDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventDimConfirm name="InventDimConfirm">InventDimConfirm</a>

First included in: SalesAndMarketing/SalesFormletterSalesOrderConfirmationFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventDimConfirm attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaperFormat name="PaperFormat">PaperFormat</a>

First included in: SalesAndMarketing/SalesFormletterSalesOrderConfirmationFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaperFormat attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentAttachmentDisplayRule name="DocumentAttachmentDisplayRule">DocumentAttachmentDisplayRule</a>

First included in: SalesAndMarketing/SalesFormletterSalesOrderConfirmationFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentAttachmentDisplayRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DisplayedDocumentAttachmentTypeCode name="DisplayedDocumentAttachmentTypeCode">DisplayedDocumentAttachmentTypeCode</a>

First included in: SalesAndMarketing/SalesFormletterSalesOrderConfirmationFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisplayedDocumentAttachmentTypeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_CustFormletterParametersRelationshipId name="BackingTable_CustFormletterParametersRelationshipId">BackingTable_CustFormletterParametersRelationshipId</a>

First included in: SalesAndMarketing/SalesFormletterSalesOrderConfirmationFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_CustFormletterParametersRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Parameter/CustFormletterParameters.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Parameter/CustFormletterParameters.cdm.json/CustFormletterParameters</a></td><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Parameter/CustFormletterParameters.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: SalesAndMarketing/SalesFormletterSalesOrderConfirmationFormPrintingConfigurationEntity (this entity)  

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
