---
title: SalesFormletterSalesInvoiceFormPrintingConfigurationEntity in SalesAndMarketing - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Sales invoice form printing configurations in SalesAndMarketing(SalesFormletterSalesInvoiceFormPrintingConfigurationEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/SalesAndMarketing/SalesFormletterSalesInvoiceFormPrintingConfigurationEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales invoice form printing configurations</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[IsInventoryStatusIdDisplayed](#IsInventoryStatusIdDisplayed)||<a href="SalesFormletterSalesInvoiceFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesInvoiceFormPrintingConfigurationEntity</a>|
|[IsItemBatchNumberDisplayed](#IsItemBatchNumberDisplayed)||<a href="SalesFormletterSalesInvoiceFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesInvoiceFormPrintingConfigurationEntity</a>|
|[IsItemSerialNumberDisplayed](#IsItemSerialNumberDisplayed)||<a href="SalesFormletterSalesInvoiceFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesInvoiceFormPrintingConfigurationEntity</a>|
|[IsLicensePlateNumberDisplayed](#IsLicensePlateNumberDisplayed)||<a href="SalesFormletterSalesInvoiceFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesInvoiceFormPrintingConfigurationEntity</a>|
|[IsProductColorIdDisplayed](#IsProductColorIdDisplayed)||<a href="SalesFormletterSalesInvoiceFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesInvoiceFormPrintingConfigurationEntity</a>|
|[IsProductConfigurationIdDisplayed](#IsProductConfigurationIdDisplayed)||<a href="SalesFormletterSalesInvoiceFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesInvoiceFormPrintingConfigurationEntity</a>|
|[IsProductSizeIdDisplayed](#IsProductSizeIdDisplayed)||<a href="SalesFormletterSalesInvoiceFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesInvoiceFormPrintingConfigurationEntity</a>|
|[IsProductStyleIdDisplayed](#IsProductStyleIdDisplayed)||<a href="SalesFormletterSalesInvoiceFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesInvoiceFormPrintingConfigurationEntity</a>|
|[IsProductVersionIdDisplayed](#IsProductVersionIdDisplayed)||<a href="SalesFormletterSalesInvoiceFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesInvoiceFormPrintingConfigurationEntity</a>|
|[IsShippingSiteIdDisplayed](#IsShippingSiteIdDisplayed)||<a href="SalesFormletterSalesInvoiceFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesInvoiceFormPrintingConfigurationEntity</a>|
|[IsShippingWarehouseIdDisplayed](#IsShippingWarehouseIdDisplayed)||<a href="SalesFormletterSalesInvoiceFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesInvoiceFormPrintingConfigurationEntity</a>|
|[IsShippingWarehouseLocationIdDisplayed](#IsShippingWarehouseLocationIdDisplayed)||<a href="SalesFormletterSalesInvoiceFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesInvoiceFormPrintingConfigurationEntity</a>|
|[InventDimInvoice](#InventDimInvoice)||<a href="SalesFormletterSalesInvoiceFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesInvoiceFormPrintingConfigurationEntity</a>|
|[PaperFormat](#PaperFormat)||<a href="SalesFormletterSalesInvoiceFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesInvoiceFormPrintingConfigurationEntity</a>|
|[DocumentAttachmentDisplayRule](#DocumentAttachmentDisplayRule)||<a href="SalesFormletterSalesInvoiceFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesInvoiceFormPrintingConfigurationEntity</a>|
|[DisplayedDocumentAttachmentTypeCode](#DisplayedDocumentAttachmentTypeCode)||<a href="SalesFormletterSalesInvoiceFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesInvoiceFormPrintingConfigurationEntity</a>|
|[BackorderTrackingDisplayRule](#BackorderTrackingDisplayRule)||<a href="SalesFormletterSalesInvoiceFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesInvoiceFormPrintingConfigurationEntity</a>|
|[IsPackingSlipSpecificationDisplayed](#IsPackingSlipSpecificationDisplayed)||<a href="SalesFormletterSalesInvoiceFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesInvoiceFormPrintingConfigurationEntity</a>|
|[IsTaxExemptNumberDisplayed](#IsTaxExemptNumberDisplayed)||<a href="SalesFormletterSalesInvoiceFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesInvoiceFormPrintingConfigurationEntity</a>|
|[CreditNoteLineDisplayRule](#CreditNoteLineDisplayRule)||<a href="SalesFormletterSalesInvoiceFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesInvoiceFormPrintingConfigurationEntity</a>|
|[DisplayedPaymentAttachmentType](#DisplayedPaymentAttachmentType)||<a href="SalesFormletterSalesInvoiceFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesInvoiceFormPrintingConfigurationEntity</a>|
|[LumpSumRecoveryGracePeriodDays](#LumpSumRecoveryGracePeriodDays)||<a href="SalesFormletterSalesInvoiceFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesInvoiceFormPrintingConfigurationEntity</a>|
|[LumpSumRecoveryText](#LumpSumRecoveryText)||<a href="SalesFormletterSalesInvoiceFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesInvoiceFormPrintingConfigurationEntity</a>|
|[BackingTable_CustFormletterParametersRelationshipId](#BackingTable_CustFormletterParametersRelationshipId)||<a href="SalesFormletterSalesInvoiceFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesInvoiceFormPrintingConfigurationEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="SalesFormletterSalesInvoiceFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesInvoiceFormPrintingConfigurationEntity</a>|

### <a href=#IsInventoryStatusIdDisplayed name="IsInventoryStatusIdDisplayed">IsInventoryStatusIdDisplayed</a>

First included in: SalesAndMarketing/SalesFormletterSalesInvoiceFormPrintingConfigurationEntity (this entity)  

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

First included in: SalesAndMarketing/SalesFormletterSalesInvoiceFormPrintingConfigurationEntity (this entity)  

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

First included in: SalesAndMarketing/SalesFormletterSalesInvoiceFormPrintingConfigurationEntity (this entity)  

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

First included in: SalesAndMarketing/SalesFormletterSalesInvoiceFormPrintingConfigurationEntity (this entity)  

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

First included in: SalesAndMarketing/SalesFormletterSalesInvoiceFormPrintingConfigurationEntity (this entity)  

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

First included in: SalesAndMarketing/SalesFormletterSalesInvoiceFormPrintingConfigurationEntity (this entity)  

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

First included in: SalesAndMarketing/SalesFormletterSalesInvoiceFormPrintingConfigurationEntity (this entity)  

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

First included in: SalesAndMarketing/SalesFormletterSalesInvoiceFormPrintingConfigurationEntity (this entity)  

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

First included in: SalesAndMarketing/SalesFormletterSalesInvoiceFormPrintingConfigurationEntity (this entity)  

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

First included in: SalesAndMarketing/SalesFormletterSalesInvoiceFormPrintingConfigurationEntity (this entity)  

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

First included in: SalesAndMarketing/SalesFormletterSalesInvoiceFormPrintingConfigurationEntity (this entity)  

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

First included in: SalesAndMarketing/SalesFormletterSalesInvoiceFormPrintingConfigurationEntity (this entity)  

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

### <a href=#InventDimInvoice name="InventDimInvoice">InventDimInvoice</a>

First included in: SalesAndMarketing/SalesFormletterSalesInvoiceFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventDimInvoice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaperFormat name="PaperFormat">PaperFormat</a>

First included in: SalesAndMarketing/SalesFormletterSalesInvoiceFormPrintingConfigurationEntity (this entity)  

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

First included in: SalesAndMarketing/SalesFormletterSalesInvoiceFormPrintingConfigurationEntity (this entity)  

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

First included in: SalesAndMarketing/SalesFormletterSalesInvoiceFormPrintingConfigurationEntity (this entity)  

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

### <a href=#BackorderTrackingDisplayRule name="BackorderTrackingDisplayRule">BackorderTrackingDisplayRule</a>

First included in: SalesAndMarketing/SalesFormletterSalesInvoiceFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackorderTrackingDisplayRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPackingSlipSpecificationDisplayed name="IsPackingSlipSpecificationDisplayed">IsPackingSlipSpecificationDisplayed</a>

First included in: SalesAndMarketing/SalesFormletterSalesInvoiceFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPackingSlipSpecificationDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsTaxExemptNumberDisplayed name="IsTaxExemptNumberDisplayed">IsTaxExemptNumberDisplayed</a>

First included in: SalesAndMarketing/SalesFormletterSalesInvoiceFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsTaxExemptNumberDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditNoteLineDisplayRule name="CreditNoteLineDisplayRule">CreditNoteLineDisplayRule</a>

First included in: SalesAndMarketing/SalesFormletterSalesInvoiceFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditNoteLineDisplayRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DisplayedPaymentAttachmentType name="DisplayedPaymentAttachmentType">DisplayedPaymentAttachmentType</a>

First included in: SalesAndMarketing/SalesFormletterSalesInvoiceFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisplayedPaymentAttachmentType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LumpSumRecoveryGracePeriodDays name="LumpSumRecoveryGracePeriodDays">LumpSumRecoveryGracePeriodDays</a>

First included in: SalesAndMarketing/SalesFormletterSalesInvoiceFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LumpSumRecoveryGracePeriodDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LumpSumRecoveryText name="LumpSumRecoveryText">LumpSumRecoveryText</a>

First included in: SalesAndMarketing/SalesFormletterSalesInvoiceFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LumpSumRecoveryText attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_CustFormletterParametersRelationshipId name="BackingTable_CustFormletterParametersRelationshipId">BackingTable_CustFormletterParametersRelationshipId</a>

First included in: SalesAndMarketing/SalesFormletterSalesInvoiceFormPrintingConfigurationEntity (this entity)  

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

First included in: SalesAndMarketing/SalesFormletterSalesInvoiceFormPrintingConfigurationEntity (this entity)  

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
