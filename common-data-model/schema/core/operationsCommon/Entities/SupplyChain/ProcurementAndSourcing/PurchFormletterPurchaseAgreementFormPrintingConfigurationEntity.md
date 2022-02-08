---
title: PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity in ProcurementAndSourcing - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Purchase agreement form printing configurations in ProcurementAndSourcing(PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchase agreement form printing configurations</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[IsProductColorIdDisplayed](#IsProductColorIdDisplayed)||<a href="PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity.md" target="_blank">ProcurementAndSourcing/PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity</a>|
|[IsProductConfigurationIdDisplayed](#IsProductConfigurationIdDisplayed)||<a href="PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity.md" target="_blank">ProcurementAndSourcing/PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity</a>|
|[IsProductSizeIdDisplayed](#IsProductSizeIdDisplayed)||<a href="PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity.md" target="_blank">ProcurementAndSourcing/PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity</a>|
|[IsProductStyleIdDisplayed](#IsProductStyleIdDisplayed)||<a href="PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity.md" target="_blank">ProcurementAndSourcing/PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity</a>|
|[IsProductVersionIdDisplayed](#IsProductVersionIdDisplayed)||<a href="PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity.md" target="_blank">ProcurementAndSourcing/PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity</a>|
|[IsReceivingSiteIdDisplayed](#IsReceivingSiteIdDisplayed)||<a href="PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity.md" target="_blank">ProcurementAndSourcing/PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity</a>|
|[IsReceivingWarehouseIdDisplayed](#IsReceivingWarehouseIdDisplayed)||<a href="PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity.md" target="_blank">ProcurementAndSourcing/PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity</a>|
|[InventDimPurchaseAgreement](#InventDimPurchaseAgreement)||<a href="PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity.md" target="_blank">ProcurementAndSourcing/PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity</a>|
|[DocumentAttachmentDisplayRule](#DocumentAttachmentDisplayRule)||<a href="PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity.md" target="_blank">ProcurementAndSourcing/PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity</a>|
|[DisplayedDocumentAttachmentTypeCode](#DisplayedDocumentAttachmentTypeCode)||<a href="PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity.md" target="_blank">ProcurementAndSourcing/PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity</a>|
|[PaperFormat](#PaperFormat)||<a href="PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity.md" target="_blank">ProcurementAndSourcing/PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity</a>|
|[IsDeliveryTermsDisplayed](#IsDeliveryTermsDisplayed)||<a href="PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity.md" target="_blank">ProcurementAndSourcing/PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity</a>|
|[IsDeliveryModeDisplayed](#IsDeliveryModeDisplayed)||<a href="PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity.md" target="_blank">ProcurementAndSourcing/PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity</a>|
|[IsMaxEnforcedDisplayed](#IsMaxEnforcedDisplayed)||<a href="PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity.md" target="_blank">ProcurementAndSourcing/PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity</a>|
|[IsCashDiscountDisplayed](#IsCashDiscountDisplayed)||<a href="PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity.md" target="_blank">ProcurementAndSourcing/PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity</a>|
|[IsPaymentTermsDisplayed](#IsPaymentTermsDisplayed)||<a href="PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity.md" target="_blank">ProcurementAndSourcing/PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity</a>|
|[IsAgreementClassificationDisplayed](#IsAgreementClassificationDisplayed)||<a href="PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity.md" target="_blank">ProcurementAndSourcing/PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity</a>|
|[IsContractReferenceDisplayed](#IsContractReferenceDisplayed)||<a href="PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity.md" target="_blank">ProcurementAndSourcing/PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity</a>|
|[BackingTable_VendFormletterParametersRelationshipId](#BackingTable_VendFormletterParametersRelationshipId)||<a href="PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity.md" target="_blank">ProcurementAndSourcing/PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity.md" target="_blank">ProcurementAndSourcing/PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity</a>|

### <a href=#IsProductColorIdDisplayed name="IsProductColorIdDisplayed">IsProductColorIdDisplayed</a>

First included in: ProcurementAndSourcing/PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity (this entity)  

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

### <a href=#IsReceivingSiteIdDisplayed name="IsReceivingSiteIdDisplayed">IsReceivingSiteIdDisplayed</a>

First included in: ProcurementAndSourcing/PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsReceivingSiteIdDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsReceivingWarehouseIdDisplayed name="IsReceivingWarehouseIdDisplayed">IsReceivingWarehouseIdDisplayed</a>

First included in: ProcurementAndSourcing/PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsReceivingWarehouseIdDisplayed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventDimPurchaseAgreement name="InventDimPurchaseAgreement">InventDimPurchaseAgreement</a>

First included in: ProcurementAndSourcing/PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventDimPurchaseAgreement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentAttachmentDisplayRule name="DocumentAttachmentDisplayRule">DocumentAttachmentDisplayRule</a>

First included in: ProcurementAndSourcing/PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity (this entity)  

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

### <a href=#PaperFormat name="PaperFormat">PaperFormat</a>

First included in: ProcurementAndSourcing/PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity (this entity)  

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

### <a href=#IsDeliveryTermsDisplayed name="IsDeliveryTermsDisplayed">IsDeliveryTermsDisplayed</a>

First included in: ProcurementAndSourcing/PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity (this entity)  

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

### <a href=#IsDeliveryModeDisplayed name="IsDeliveryModeDisplayed">IsDeliveryModeDisplayed</a>

First included in: ProcurementAndSourcing/PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity (this entity)  

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

### <a href=#IsMaxEnforcedDisplayed name="IsMaxEnforcedDisplayed">IsMaxEnforcedDisplayed</a>

First included in: ProcurementAndSourcing/PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity (this entity)  

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

### <a href=#IsCashDiscountDisplayed name="IsCashDiscountDisplayed">IsCashDiscountDisplayed</a>

First included in: ProcurementAndSourcing/PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity (this entity)  

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

### <a href=#IsPaymentTermsDisplayed name="IsPaymentTermsDisplayed">IsPaymentTermsDisplayed</a>

First included in: ProcurementAndSourcing/PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity (this entity)  

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

### <a href=#IsAgreementClassificationDisplayed name="IsAgreementClassificationDisplayed">IsAgreementClassificationDisplayed</a>

First included in: ProcurementAndSourcing/PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity (this entity)  

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

### <a href=#IsContractReferenceDisplayed name="IsContractReferenceDisplayed">IsContractReferenceDisplayed</a>

First included in: ProcurementAndSourcing/PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity (this entity)  

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

### <a href=#BackingTable_VendFormletterParametersRelationshipId name="BackingTable_VendFormletterParametersRelationshipId">BackingTable_VendFormletterParametersRelationshipId</a>

First included in: ProcurementAndSourcing/PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_VendFormletterParametersRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/AccountsPayable/Parameter/VendFormletterParameters.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsPayable/Parameter/VendFormletterParameters.cdm.json/VendFormletterParameters</a></td><td><a href="../../../Tables/Finance/AccountsPayable/Parameter/VendFormletterParameters.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProcurementAndSourcing/PurchFormletterPurchaseAgreementFormPrintingConfigurationEntity (this entity)  

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
