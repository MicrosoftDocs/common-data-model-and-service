---
title: SalesFormletterSalesAgreementFormPrintingConfigurationEntity in SalesAndMarketing - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/13/2020
ms.author: nebanfic
---

# Sales agreement form printing configurations in SalesAndMarketing(SalesFormletterSalesAgreementFormPrintingConfigurationEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/SalesAndMarketing/SalesFormletterSalesAgreementFormPrintingConfigurationEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales agreement form printing configurations</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[IsProductColorIdDisplayed](#IsProductColorIdDisplayed)||<a href="SalesFormletterSalesAgreementFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesAgreementFormPrintingConfigurationEntity</a>|
|[IsProductConfigurationIdDisplayed](#IsProductConfigurationIdDisplayed)||<a href="SalesFormletterSalesAgreementFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesAgreementFormPrintingConfigurationEntity</a>|
|[IsProductSizeIdDisplayed](#IsProductSizeIdDisplayed)||<a href="SalesFormletterSalesAgreementFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesAgreementFormPrintingConfigurationEntity</a>|
|[IsProductStyleIdDisplayed](#IsProductStyleIdDisplayed)||<a href="SalesFormletterSalesAgreementFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesAgreementFormPrintingConfigurationEntity</a>|
|[IsProductVersionIdDisplayed](#IsProductVersionIdDisplayed)||<a href="SalesFormletterSalesAgreementFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesAgreementFormPrintingConfigurationEntity</a>|
|[IsShippingSiteIdDisplayed](#IsShippingSiteIdDisplayed)||<a href="SalesFormletterSalesAgreementFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesAgreementFormPrintingConfigurationEntity</a>|
|[IsShippingWarehouseIdDisplayed](#IsShippingWarehouseIdDisplayed)||<a href="SalesFormletterSalesAgreementFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesAgreementFormPrintingConfigurationEntity</a>|
|[InventDimSalesAgreement](#InventDimSalesAgreement)||<a href="SalesFormletterSalesAgreementFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesAgreementFormPrintingConfigurationEntity</a>|
|[PaperFormat](#PaperFormat)||<a href="SalesFormletterSalesAgreementFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesAgreementFormPrintingConfigurationEntity</a>|
|[DocumentAttachmentDisplayRule](#DocumentAttachmentDisplayRule)||<a href="SalesFormletterSalesAgreementFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesAgreementFormPrintingConfigurationEntity</a>|
|[DisplayedDocumentAttachmentTypeCode](#DisplayedDocumentAttachmentTypeCode)||<a href="SalesFormletterSalesAgreementFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesAgreementFormPrintingConfigurationEntity</a>|
|[IsAgreementClassificationDisplayed](#IsAgreementClassificationDisplayed)||<a href="SalesFormletterSalesAgreementFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesAgreementFormPrintingConfigurationEntity</a>|
|[IsCashDiscountDisplayed](#IsCashDiscountDisplayed)||<a href="SalesFormletterSalesAgreementFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesAgreementFormPrintingConfigurationEntity</a>|
|[IsContractReferenceDisplayed](#IsContractReferenceDisplayed)||<a href="SalesFormletterSalesAgreementFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesAgreementFormPrintingConfigurationEntity</a>|
|[IsDeliveryTermsDisplayed](#IsDeliveryTermsDisplayed)||<a href="SalesFormletterSalesAgreementFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesAgreementFormPrintingConfigurationEntity</a>|
|[IsMaxEnforcedDisplayed](#IsMaxEnforcedDisplayed)||<a href="SalesFormletterSalesAgreementFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesAgreementFormPrintingConfigurationEntity</a>|
|[IsDeliveryModeDisplayed](#IsDeliveryModeDisplayed)||<a href="SalesFormletterSalesAgreementFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesAgreementFormPrintingConfigurationEntity</a>|
|[IsPaymentTermsDisplayed](#IsPaymentTermsDisplayed)||<a href="SalesFormletterSalesAgreementFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesAgreementFormPrintingConfigurationEntity</a>|
|[BackingTable_CustFormletterParametersRelationshipId](#BackingTable_CustFormletterParametersRelationshipId)||<a href="SalesFormletterSalesAgreementFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesAgreementFormPrintingConfigurationEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="SalesFormletterSalesAgreementFormPrintingConfigurationEntity.md" target="_blank">SalesAndMarketing/SalesFormletterSalesAgreementFormPrintingConfigurationEntity</a>|

### <a href=#IsProductColorIdDisplayed name="IsProductColorIdDisplayed">IsProductColorIdDisplayed</a>

First included in: SalesAndMarketing/SalesFormletterSalesAgreementFormPrintingConfigurationEntity (this entity)  

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

First included in: SalesAndMarketing/SalesFormletterSalesAgreementFormPrintingConfigurationEntity (this entity)  

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

First included in: SalesAndMarketing/SalesFormletterSalesAgreementFormPrintingConfigurationEntity (this entity)  

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

First included in: SalesAndMarketing/SalesFormletterSalesAgreementFormPrintingConfigurationEntity (this entity)  

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

First included in: SalesAndMarketing/SalesFormletterSalesAgreementFormPrintingConfigurationEntity (this entity)  

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

First included in: SalesAndMarketing/SalesFormletterSalesAgreementFormPrintingConfigurationEntity (this entity)  

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

First included in: SalesAndMarketing/SalesFormletterSalesAgreementFormPrintingConfigurationEntity (this entity)  

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

### <a href=#InventDimSalesAgreement name="InventDimSalesAgreement">InventDimSalesAgreement</a>

First included in: SalesAndMarketing/SalesFormletterSalesAgreementFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventDimSalesAgreement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaperFormat name="PaperFormat">PaperFormat</a>

First included in: SalesAndMarketing/SalesFormletterSalesAgreementFormPrintingConfigurationEntity (this entity)  

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

First included in: SalesAndMarketing/SalesFormletterSalesAgreementFormPrintingConfigurationEntity (this entity)  

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

First included in: SalesAndMarketing/SalesFormletterSalesAgreementFormPrintingConfigurationEntity (this entity)  

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

### <a href=#IsAgreementClassificationDisplayed name="IsAgreementClassificationDisplayed">IsAgreementClassificationDisplayed</a>

First included in: SalesAndMarketing/SalesFormletterSalesAgreementFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsAgreementClassificationDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCashDiscountDisplayed name="IsCashDiscountDisplayed">IsCashDiscountDisplayed</a>

First included in: SalesAndMarketing/SalesFormletterSalesAgreementFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCashDiscountDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsContractReferenceDisplayed name="IsContractReferenceDisplayed">IsContractReferenceDisplayed</a>

First included in: SalesAndMarketing/SalesFormletterSalesAgreementFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsContractReferenceDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDeliveryTermsDisplayed name="IsDeliveryTermsDisplayed">IsDeliveryTermsDisplayed</a>

First included in: SalesAndMarketing/SalesFormletterSalesAgreementFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDeliveryTermsDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsMaxEnforcedDisplayed name="IsMaxEnforcedDisplayed">IsMaxEnforcedDisplayed</a>

First included in: SalesAndMarketing/SalesFormletterSalesAgreementFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsMaxEnforcedDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDeliveryModeDisplayed name="IsDeliveryModeDisplayed">IsDeliveryModeDisplayed</a>

First included in: SalesAndMarketing/SalesFormletterSalesAgreementFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDeliveryModeDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPaymentTermsDisplayed name="IsPaymentTermsDisplayed">IsPaymentTermsDisplayed</a>

First included in: SalesAndMarketing/SalesFormletterSalesAgreementFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPaymentTermsDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_CustFormletterParametersRelationshipId name="BackingTable_CustFormletterParametersRelationshipId">BackingTable_CustFormletterParametersRelationshipId</a>

First included in: SalesAndMarketing/SalesFormletterSalesAgreementFormPrintingConfigurationEntity (this entity)  

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

First included in: SalesAndMarketing/SalesFormletterSalesAgreementFormPrintingConfigurationEntity (this entity)  

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
