---
title: PurchAgreementHeaderDefaultHistory in TransactionHeader - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Purchase agreement confirmation history in TransactionHeader(PurchAgreementHeaderDefaultHistory)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/TransactionHeader/PurchAgreementHeaderDefaultHistory.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PurchAgreementHeaderDefaultHistory/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchase agreement confirmation history</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="PurchAgreementHeaderDefaultHistory.md" target="_blank">TransactionHeader/PurchAgreementHeaderDefaultHistory</a>|
|[BuyerGroup](#BuyerGroup)||<a href="PurchAgreementHeaderDefaultHistory.md" target="_blank">TransactionHeader/PurchAgreementHeaderDefaultHistory</a>|
|[BuyerGroupDataAreaId](#BuyerGroupDataAreaId)||<a href="PurchAgreementHeaderDefaultHistory.md" target="_blank">TransactionHeader/PurchAgreementHeaderDefaultHistory</a>|
|[MethodOfPayment](#MethodOfPayment)||<a href="PurchAgreementHeaderDefaultHistory.md" target="_blank">TransactionHeader/PurchAgreementHeaderDefaultHistory</a>|
|[MethodOfPaymentDataAreaId](#MethodOfPaymentDataAreaId)||<a href="PurchAgreementHeaderDefaultHistory.md" target="_blank">TransactionHeader/PurchAgreementHeaderDefaultHistory</a>|
|[PaymentSpecification](#PaymentSpecification)||<a href="PurchAgreementHeaderDefaultHistory.md" target="_blank">TransactionHeader/PurchAgreementHeaderDefaultHistory</a>|
|[PaymentSpecificationDataAreaId](#PaymentSpecificationDataAreaId)||<a href="PurchAgreementHeaderDefaultHistory.md" target="_blank">TransactionHeader/PurchAgreementHeaderDefaultHistory</a>|
|[PurchaseAgreementHeaderHistory](#PurchaseAgreementHeaderHistory)||<a href="PurchAgreementHeaderDefaultHistory.md" target="_blank">TransactionHeader/PurchAgreementHeaderDefaultHistory</a>|
|[PurchasePool](#PurchasePool)||<a href="PurchAgreementHeaderDefaultHistory.md" target="_blank">TransactionHeader/PurchAgreementHeaderDefaultHistory</a>|
|[PurchasePoolDataAreaId](#PurchasePoolDataAreaId)||<a href="PurchAgreementHeaderDefaultHistory.md" target="_blank">TransactionHeader/PurchAgreementHeaderDefaultHistory</a>|
|[VendAccount_PSN](#VendAccount_PSN)||<a href="PurchAgreementHeaderDefaultHistory.md" target="_blank">TransactionHeader/PurchAgreementHeaderDefaultHistory</a>|
|[VendBankAccountDataAreaID_PSN](#VendBankAccountDataAreaID_PSN)||<a href="PurchAgreementHeaderDefaultHistory.md" target="_blank">TransactionHeader/PurchAgreementHeaderDefaultHistory</a>|
|[VendBankAccountID_PSN](#VendBankAccountID_PSN)||<a href="PurchAgreementHeaderDefaultHistory.md" target="_blank">TransactionHeader/PurchAgreementHeaderDefaultHistory</a>|
|[VendorInvoiceAccount](#VendorInvoiceAccount)||<a href="PurchAgreementHeaderDefaultHistory.md" target="_blank">TransactionHeader/PurchAgreementHeaderDefaultHistory</a>|
|[VendorInvoiceAccountDataAreaId](#VendorInvoiceAccountDataAreaId)||<a href="PurchAgreementHeaderDefaultHistory.md" target="_blank">TransactionHeader/PurchAgreementHeaderDefaultHistory</a>|
|[Relationship_InventBuyerGroupRelationshipId](#Relationship_InventBuyerGroupRelationshipId)||<a href="PurchAgreementHeaderDefaultHistory.md" target="_blank">TransactionHeader/PurchAgreementHeaderDefaultHistory</a>|
|[Relationship_PurchAgreementHeaderHistoryRelationshipId](#Relationship_PurchAgreementHeaderHistoryRelationshipId)||<a href="PurchAgreementHeaderDefaultHistory.md" target="_blank">TransactionHeader/PurchAgreementHeaderDefaultHistory</a>|
|[Relationship_PurchPoolRelationshipId](#Relationship_PurchPoolRelationshipId)||<a href="PurchAgreementHeaderDefaultHistory.md" target="_blank">TransactionHeader/PurchAgreementHeaderDefaultHistory</a>|
|[Relationship_VendBankAccountRelationshipId](#Relationship_VendBankAccountRelationshipId)||<a href="PurchAgreementHeaderDefaultHistory.md" target="_blank">TransactionHeader/PurchAgreementHeaderDefaultHistory</a>|
|[Relationship_VendInvoiceAccountRelationshipId](#Relationship_VendInvoiceAccountRelationshipId)||<a href="PurchAgreementHeaderDefaultHistory.md" target="_blank">TransactionHeader/PurchAgreementHeaderDefaultHistory</a>|
|[Relationship_VendPaymModeRelationshipId](#Relationship_VendPaymModeRelationshipId)||<a href="PurchAgreementHeaderDefaultHistory.md" target="_blank">TransactionHeader/PurchAgreementHeaderDefaultHistory</a>|
|[Relationship_VendPaymModeSpecRelationshipId](#Relationship_VendPaymModeSpecRelationshipId)||<a href="PurchAgreementHeaderDefaultHistory.md" target="_blank">TransactionHeader/PurchAgreementHeaderDefaultHistory</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: TransactionHeader/PurchAgreementHeaderDefaultHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PurchAgreementHeaderDefaultHistory/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BuyerGroup name="BuyerGroup">BuyerGroup</a>

First included in: TransactionHeader/PurchAgreementHeaderDefaultHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BuyerGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BuyerGroupDataAreaId name="BuyerGroupDataAreaId">BuyerGroupDataAreaId</a>

First included in: TransactionHeader/PurchAgreementHeaderDefaultHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BuyerGroupDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MethodOfPayment name="MethodOfPayment">MethodOfPayment</a>

First included in: TransactionHeader/PurchAgreementHeaderDefaultHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MethodOfPayment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MethodOfPaymentDataAreaId name="MethodOfPaymentDataAreaId">MethodOfPaymentDataAreaId</a>

First included in: TransactionHeader/PurchAgreementHeaderDefaultHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MethodOfPaymentDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentSpecification name="PaymentSpecification">PaymentSpecification</a>

First included in: TransactionHeader/PurchAgreementHeaderDefaultHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentSpecification attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentSpecificationDataAreaId name="PaymentSpecificationDataAreaId">PaymentSpecificationDataAreaId</a>

First included in: TransactionHeader/PurchAgreementHeaderDefaultHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentSpecificationDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseAgreementHeaderHistory name="PurchaseAgreementHeaderHistory">PurchaseAgreementHeaderHistory</a>

First included in: TransactionHeader/PurchAgreementHeaderDefaultHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purchase agreement confirmation history</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseAgreementHeaderHistory attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchase agreement confirmation history</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PurchasePool name="PurchasePool">PurchasePool</a>

First included in: TransactionHeader/PurchAgreementHeaderDefaultHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchasePool attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchasePoolDataAreaId name="PurchasePoolDataAreaId">PurchasePoolDataAreaId</a>

First included in: TransactionHeader/PurchAgreementHeaderDefaultHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchasePoolDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendAccount_PSN name="VendAccount_PSN">VendAccount_PSN</a>

First included in: TransactionHeader/PurchAgreementHeaderDefaultHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendAccount_PSN attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendBankAccountDataAreaID_PSN name="VendBankAccountDataAreaID_PSN">VendBankAccountDataAreaID_PSN</a>

First included in: TransactionHeader/PurchAgreementHeaderDefaultHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendBankAccountDataAreaID_PSN attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendBankAccountID_PSN name="VendBankAccountID_PSN">VendBankAccountID_PSN</a>

First included in: TransactionHeader/PurchAgreementHeaderDefaultHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bank</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendBankAccountID_PSN attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Bank</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorInvoiceAccount name="VendorInvoiceAccount">VendorInvoiceAccount</a>

First included in: TransactionHeader/PurchAgreementHeaderDefaultHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorInvoiceAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorInvoiceAccountDataAreaId name="VendorInvoiceAccountDataAreaId">VendorInvoiceAccountDataAreaId</a>

First included in: TransactionHeader/PurchAgreementHeaderDefaultHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorInvoiceAccountDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventBuyerGroupRelationshipId name="Relationship_InventBuyerGroupRelationshipId">Relationship_InventBuyerGroupRelationshipId</a>

First included in: TransactionHeader/PurchAgreementHeaderDefaultHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventBuyerGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Inventory/Group/InventBuyerGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/InventBuyerGroup.cdm.json/InventBuyerGroup</a></td><td><a href="../../Inventory/Group/InventBuyerGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PurchAgreementHeaderHistoryRelationshipId name="Relationship_PurchAgreementHeaderHistoryRelationshipId">Relationship_PurchAgreementHeaderHistoryRelationshipId</a>

First included in: TransactionHeader/PurchAgreementHeaderDefaultHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchAgreementHeaderHistoryRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="PurchAgreementHeaderHistory.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/TransactionHeader/PurchAgreementHeaderHistory.cdm.json/PurchAgreementHeaderHistory</a></td><td><a href="PurchAgreementHeaderHistory.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PurchPoolRelationshipId name="Relationship_PurchPoolRelationshipId">Relationship_PurchPoolRelationshipId</a>

First included in: TransactionHeader/PurchAgreementHeaderDefaultHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchPoolRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/PurchPool.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Group/PurchPool.cdm.json/PurchPool</a></td><td><a href="../Group/PurchPool.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendBankAccountRelationshipId name="Relationship_VendBankAccountRelationshipId">Relationship_VendBankAccountRelationshipId</a>

First included in: TransactionHeader/PurchAgreementHeaderDefaultHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendBankAccountRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Vendor/Main/VendBankAccount.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Vendor/Main/VendBankAccount.cdm.json/VendBankAccount</a></td><td><a href="../../Vendor/Main/VendBankAccount.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendInvoiceAccountRelationshipId name="Relationship_VendInvoiceAccountRelationshipId">Relationship_VendInvoiceAccountRelationshipId</a>

First included in: TransactionHeader/PurchAgreementHeaderDefaultHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendInvoiceAccountRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Vendor/Main/VendTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Vendor/Main/VendTable.cdm.json/VendTable</a></td><td><a href="../../Vendor/Main/VendTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendPaymModeRelationshipId name="Relationship_VendPaymModeRelationshipId">Relationship_VendPaymModeRelationshipId</a>

First included in: TransactionHeader/PurchAgreementHeaderDefaultHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendPaymModeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Bank/Group/VendPaymModeTable.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Group/VendPaymModeTable.cdm.json/VendPaymModeTable</a></td><td><a href="../../../Finance/Bank/Group/VendPaymModeTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendPaymModeSpecRelationshipId name="Relationship_VendPaymModeSpecRelationshipId">Relationship_VendPaymModeSpecRelationshipId</a>

First included in: TransactionHeader/PurchAgreementHeaderDefaultHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendPaymModeSpecRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Bank/Group/VendPaymModeSpec.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Group/VendPaymModeSpec.cdm.json/VendPaymModeSpec</a></td><td><a href="../../../Finance/Bank/Group/VendPaymModeSpec.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
