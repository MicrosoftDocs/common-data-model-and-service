---
title: CustFormletterDocument - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# CustFormletterDocument

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Parameter/CustFormletterDocument.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[CustFormletterDocument/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="CustFormletterDocument.md" target="_blank">Parameter/CustFormletterDocument</a>|
|[DocuOnAgreement](#DocuOnAgreement)||<a href="CustFormletterDocument.md" target="_blank">Parameter/CustFormletterDocument</a>|
|[DocuOnConfirm](#DocuOnConfirm)||<a href="CustFormletterDocument.md" target="_blank">Parameter/CustFormletterDocument</a>|
|[DocuOnFreeTextInvoice](#DocuOnFreeTextInvoice)||<a href="CustFormletterDocument.md" target="_blank">Parameter/CustFormletterDocument</a>|
|[DocuOnInvoice](#DocuOnInvoice)||<a href="CustFormletterDocument.md" target="_blank">Parameter/CustFormletterDocument</a>|
|[DocuOnInvoice4Paym_RU](#DocuOnInvoice4Paym_RU)||<a href="CustFormletterDocument.md" target="_blank">Parameter/CustFormletterDocument</a>|
|[DocuOnPackingSlip](#DocuOnPackingSlip)||<a href="CustFormletterDocument.md" target="_blank">Parameter/CustFormletterDocument</a>|
|[DocuOnPickingList](#DocuOnPickingList)||<a href="CustFormletterDocument.md" target="_blank">Parameter/CustFormletterDocument</a>|
|[DocuOnQuotation](#DocuOnQuotation)||<a href="CustFormletterDocument.md" target="_blank">Parameter/CustFormletterDocument</a>|
|[DocuOverdueFineNumOfDaysInvoice_FR](#DocuOverdueFineNumOfDaysInvoice_FR)||<a href="CustFormletterDocument.md" target="_blank">Parameter/CustFormletterDocument</a>|
|[DocuOverdueFineTxtInvoice_FR](#DocuOverdueFineTxtInvoice_FR)||<a href="CustFormletterDocument.md" target="_blank">Parameter/CustFormletterDocument</a>|
|[DocuTypeAgreement](#DocuTypeAgreement)||<a href="CustFormletterDocument.md" target="_blank">Parameter/CustFormletterDocument</a>|
|[DocuTypeConfirm](#DocuTypeConfirm)||<a href="CustFormletterDocument.md" target="_blank">Parameter/CustFormletterDocument</a>|
|[DocuTypeFreeTextInvoice](#DocuTypeFreeTextInvoice)||<a href="CustFormletterDocument.md" target="_blank">Parameter/CustFormletterDocument</a>|
|[DocuTypeInvoice](#DocuTypeInvoice)||<a href="CustFormletterDocument.md" target="_blank">Parameter/CustFormletterDocument</a>|
|[DocuTypeInvoice4Paym_RU](#DocuTypeInvoice4Paym_RU)||<a href="CustFormletterDocument.md" target="_blank">Parameter/CustFormletterDocument</a>|
|[DocuTypePackingSlip](#DocuTypePackingSlip)||<a href="CustFormletterDocument.md" target="_blank">Parameter/CustFormletterDocument</a>|
|[DocuTypePickingList](#DocuTypePickingList)||<a href="CustFormletterDocument.md" target="_blank">Parameter/CustFormletterDocument</a>|
|[DocuTypeQuotation](#DocuTypeQuotation)||<a href="CustFormletterDocument.md" target="_blank">Parameter/CustFormletterDocument</a>|
|[Key](#Key)||<a href="CustFormletterDocument.md" target="_blank">Parameter/CustFormletterDocument</a>|
|[DocuTypePrepaymentRequest_IT](#DocuTypePrepaymentRequest_IT)||<a href="CustFormletterDocument.md" target="_blank">Parameter/CustFormletterDocument</a>|
|[DocuOnPrepaymentRequest_IT](#DocuOnPrepaymentRequest_IT)||<a href="CustFormletterDocument.md" target="_blank">Parameter/CustFormletterDocument</a>|
|[DataAreaId](#DataAreaId)||<a href="CustFormletterDocument.md" target="_blank">Parameter/CustFormletterDocument</a>|
|[Relationship_AgreementDocuTypeRelationshipId](#Relationship_AgreementDocuTypeRelationshipId)||<a href="CustFormletterDocument.md" target="_blank">Parameter/CustFormletterDocument</a>|
|[Relationship_ConfirmationDocuTypeRelationshipId](#Relationship_ConfirmationDocuTypeRelationshipId)||<a href="CustFormletterDocument.md" target="_blank">Parameter/CustFormletterDocument</a>|
|[Relationship_DocuTypeRelationshipId](#Relationship_DocuTypeRelationshipId)||<a href="CustFormletterDocument.md" target="_blank">Parameter/CustFormletterDocument</a>|
|[Relationship_FreeTextInvoiceDocuTypeRelationshipId](#Relationship_FreeTextInvoiceDocuTypeRelationshipId)||<a href="CustFormletterDocument.md" target="_blank">Parameter/CustFormletterDocument</a>|
|[Relationship_InvoiceDocuTypeRelationshipId](#Relationship_InvoiceDocuTypeRelationshipId)||<a href="CustFormletterDocument.md" target="_blank">Parameter/CustFormletterDocument</a>|
|[Relationship_PackingSlipDocuTypeRelationshipId](#Relationship_PackingSlipDocuTypeRelationshipId)||<a href="CustFormletterDocument.md" target="_blank">Parameter/CustFormletterDocument</a>|
|[Relationship_PickingListDocuTypeRelationshipId](#Relationship_PickingListDocuTypeRelationshipId)||<a href="CustFormletterDocument.md" target="_blank">Parameter/CustFormletterDocument</a>|
|[Relationship_QuotationDocuTypeRelationshipId](#Relationship_QuotationDocuTypeRelationshipId)||<a href="CustFormletterDocument.md" target="_blank">Parameter/CustFormletterDocument</a>|
|[Relationship_PrepaymReqDocuType_ITRelationshipId](#Relationship_PrepaymReqDocuType_ITRelationshipId)||<a href="CustFormletterDocument.md" target="_blank">Parameter/CustFormletterDocument</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="CustFormletterDocument.md" target="_blank">Parameter/CustFormletterDocument</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Parameter/CustFormletterDocument (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[CustFormletterDocument/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DocuOnAgreement name="DocuOnAgreement">DocuOnAgreement</a>

First included in: Parameter/CustFormletterDocument (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocuOnAgreement attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DocuOnConfirm name="DocuOnConfirm">DocuOnConfirm</a>

First included in: Parameter/CustFormletterDocument (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocuOnConfirm attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DocuOnFreeTextInvoice name="DocuOnFreeTextInvoice">DocuOnFreeTextInvoice</a>

First included in: Parameter/CustFormletterDocument (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocuOnFreeTextInvoice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DocuOnInvoice name="DocuOnInvoice">DocuOnInvoice</a>

First included in: Parameter/CustFormletterDocument (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocuOnInvoice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DocuOnInvoice4Paym_RU name="DocuOnInvoice4Paym_RU">DocuOnInvoice4Paym_RU</a>

First included in: Parameter/CustFormletterDocument (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocuOnInvoice4Paym_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DocuOnPackingSlip name="DocuOnPackingSlip">DocuOnPackingSlip</a>

First included in: Parameter/CustFormletterDocument (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocuOnPackingSlip attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DocuOnPickingList name="DocuOnPickingList">DocuOnPickingList</a>

First included in: Parameter/CustFormletterDocument (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocuOnPickingList attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DocuOnQuotation name="DocuOnQuotation">DocuOnQuotation</a>

First included in: Parameter/CustFormletterDocument (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocuOnQuotation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DocuOverdueFineNumOfDaysInvoice_FR name="DocuOverdueFineNumOfDaysInvoice_FR">DocuOverdueFineNumOfDaysInvoice_FR</a>

First included in: Parameter/CustFormletterDocument (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocuOverdueFineNumOfDaysInvoice_FR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DocuOverdueFineTxtInvoice_FR name="DocuOverdueFineTxtInvoice_FR">DocuOverdueFineTxtInvoice_FR</a>

First included in: Parameter/CustFormletterDocument (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocuOverdueFineTxtInvoice_FR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocuTypeAgreement name="DocuTypeAgreement">DocuTypeAgreement</a>

First included in: Parameter/CustFormletterDocument (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocuTypeAgreement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocuTypeConfirm name="DocuTypeConfirm">DocuTypeConfirm</a>

First included in: Parameter/CustFormletterDocument (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocuTypeConfirm attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocuTypeFreeTextInvoice name="DocuTypeFreeTextInvoice">DocuTypeFreeTextInvoice</a>

First included in: Parameter/CustFormletterDocument (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocuTypeFreeTextInvoice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocuTypeInvoice name="DocuTypeInvoice">DocuTypeInvoice</a>

First included in: Parameter/CustFormletterDocument (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocuTypeInvoice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocuTypeInvoice4Paym_RU name="DocuTypeInvoice4Paym_RU">DocuTypeInvoice4Paym_RU</a>

First included in: Parameter/CustFormletterDocument (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocuTypeInvoice4Paym_RU attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocuTypePackingSlip name="DocuTypePackingSlip">DocuTypePackingSlip</a>

First included in: Parameter/CustFormletterDocument (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocuTypePackingSlip attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocuTypePickingList name="DocuTypePickingList">DocuTypePickingList</a>

First included in: Parameter/CustFormletterDocument (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocuTypePickingList attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocuTypeQuotation name="DocuTypeQuotation">DocuTypeQuotation</a>

First included in: Parameter/CustFormletterDocument (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocuTypeQuotation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Key name="Key">Key</a>

First included in: Parameter/CustFormletterDocument (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Key attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#DocuTypePrepaymentRequest_IT name="DocuTypePrepaymentRequest_IT">DocuTypePrepaymentRequest_IT</a>

First included in: Parameter/CustFormletterDocument (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocuTypePrepaymentRequest_IT attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocuOnPrepaymentRequest_IT name="DocuOnPrepaymentRequest_IT">DocuOnPrepaymentRequest_IT</a>

First included in: Parameter/CustFormletterDocument (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocuOnPrepaymentRequest_IT attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Parameter/CustFormletterDocument (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AgreementDocuTypeRelationshipId name="Relationship_AgreementDocuTypeRelationshipId">Relationship_AgreementDocuTypeRelationshipId</a>

First included in: Parameter/CustFormletterDocument (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AgreementDocuTypeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Group/DocuType.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Group/DocuType.cdm.json/DocuType</a></td><td><a href="../../../System/SystemAdministration/Group/DocuType.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ConfirmationDocuTypeRelationshipId name="Relationship_ConfirmationDocuTypeRelationshipId">Relationship_ConfirmationDocuTypeRelationshipId</a>

First included in: Parameter/CustFormletterDocument (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ConfirmationDocuTypeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Group/DocuType.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Group/DocuType.cdm.json/DocuType</a></td><td><a href="../../../System/SystemAdministration/Group/DocuType.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DocuTypeRelationshipId name="Relationship_DocuTypeRelationshipId">Relationship_DocuTypeRelationshipId</a>

First included in: Parameter/CustFormletterDocument (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DocuTypeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Group/DocuType.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Group/DocuType.cdm.json/DocuType</a></td><td><a href="../../../System/SystemAdministration/Group/DocuType.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FreeTextInvoiceDocuTypeRelationshipId name="Relationship_FreeTextInvoiceDocuTypeRelationshipId">Relationship_FreeTextInvoiceDocuTypeRelationshipId</a>

First included in: Parameter/CustFormletterDocument (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FreeTextInvoiceDocuTypeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Group/DocuType.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Group/DocuType.cdm.json/DocuType</a></td><td><a href="../../../System/SystemAdministration/Group/DocuType.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InvoiceDocuTypeRelationshipId name="Relationship_InvoiceDocuTypeRelationshipId">Relationship_InvoiceDocuTypeRelationshipId</a>

First included in: Parameter/CustFormletterDocument (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InvoiceDocuTypeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Group/DocuType.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Group/DocuType.cdm.json/DocuType</a></td><td><a href="../../../System/SystemAdministration/Group/DocuType.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PackingSlipDocuTypeRelationshipId name="Relationship_PackingSlipDocuTypeRelationshipId">Relationship_PackingSlipDocuTypeRelationshipId</a>

First included in: Parameter/CustFormletterDocument (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PackingSlipDocuTypeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Group/DocuType.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Group/DocuType.cdm.json/DocuType</a></td><td><a href="../../../System/SystemAdministration/Group/DocuType.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PickingListDocuTypeRelationshipId name="Relationship_PickingListDocuTypeRelationshipId">Relationship_PickingListDocuTypeRelationshipId</a>

First included in: Parameter/CustFormletterDocument (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PickingListDocuTypeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Group/DocuType.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Group/DocuType.cdm.json/DocuType</a></td><td><a href="../../../System/SystemAdministration/Group/DocuType.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_QuotationDocuTypeRelationshipId name="Relationship_QuotationDocuTypeRelationshipId">Relationship_QuotationDocuTypeRelationshipId</a>

First included in: Parameter/CustFormletterDocument (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_QuotationDocuTypeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Group/DocuType.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Group/DocuType.cdm.json/DocuType</a></td><td><a href="../../../System/SystemAdministration/Group/DocuType.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrepaymReqDocuType_ITRelationshipId name="Relationship_PrepaymReqDocuType_ITRelationshipId">Relationship_PrepaymReqDocuType_ITRelationshipId</a>

First included in: Parameter/CustFormletterDocument (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PrepaymReqDocuType_ITRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Group/DocuType.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Group/DocuType.cdm.json/DocuType</a></td><td><a href="../../../System/SystemAdministration/Group/DocuType.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Parameter/CustFormletterDocument (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CompanyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
