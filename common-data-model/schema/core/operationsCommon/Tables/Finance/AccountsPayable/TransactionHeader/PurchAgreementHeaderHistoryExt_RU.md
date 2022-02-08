---
title: PurchAgreementHeaderHistoryExt_RU in TransactionHeader - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Purchase agreement confirmation history in TransactionHeader(PurchAgreementHeaderHistoryExt_RU)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/AccountsPayable/TransactionHeader/PurchAgreementHeaderHistoryExt_RU.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PurchAgreementHeaderHistoryExt_RU/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Agreement history</td></tr><tr><td>en</td><td>Purchase agreement confirmation history</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="PurchAgreementHeaderHistoryExt_RU.md" target="_blank">TransactionHeader/PurchAgreementHeaderHistoryExt_RU</a>|
|[AgreementAmount](#AgreementAmount)||<a href="PurchAgreementHeaderHistoryExt_RU.md" target="_blank">TransactionHeader/PurchAgreementHeaderHistoryExt_RU</a>|
|[AgreementDate](#AgreementDate)||<a href="PurchAgreementHeaderHistoryExt_RU.md" target="_blank">TransactionHeader/PurchAgreementHeaderHistoryExt_RU</a>|
|[AgreementHeaderHistory](#AgreementHeaderHistory)||<a href="PurchAgreementHeaderHistoryExt_RU.md" target="_blank">TransactionHeader/PurchAgreementHeaderHistoryExt_RU</a>|
|[AgreementId](#AgreementId)||<a href="PurchAgreementHeaderHistoryExt_RU.md" target="_blank">TransactionHeader/PurchAgreementHeaderHistoryExt_RU</a>|
|[AgreementSubject](#AgreementSubject)||<a href="PurchAgreementHeaderHistoryExt_RU.md" target="_blank">TransactionHeader/PurchAgreementHeaderHistoryExt_RU</a>|
|[AgreementVatAmount](#AgreementVatAmount)||<a href="PurchAgreementHeaderHistoryExt_RU.md" target="_blank">TransactionHeader/PurchAgreementHeaderHistoryExt_RU</a>|
|[CellularPhone](#CellularPhone)||<a href="PurchAgreementHeaderHistoryExt_RU.md" target="_blank">TransactionHeader/PurchAgreementHeaderHistoryExt_RU</a>|
|[CreditMax](#CreditMax)||<a href="PurchAgreementHeaderHistoryExt_RU.md" target="_blank">TransactionHeader/PurchAgreementHeaderHistoryExt_RU</a>|
|[DefaultDimension](#DefaultDimension)||<a href="PurchAgreementHeaderHistoryExt_RU.md" target="_blank">TransactionHeader/PurchAgreementHeaderHistoryExt_RU</a>|
|[Email](#Email)||<a href="PurchAgreementHeaderHistoryExt_RU.md" target="_blank">TransactionHeader/PurchAgreementHeaderHistoryExt_RU</a>|
|[InstanceRelationType](#InstanceRelationType)||<a href="PurchAgreementHeaderHistoryExt_RU.md" target="_blank">TransactionHeader/PurchAgreementHeaderHistoryExt_RU</a>|
|[InventProfileId](#InventProfileId)||<a href="PurchAgreementHeaderHistoryExt_RU.md" target="_blank">TransactionHeader/PurchAgreementHeaderHistoryExt_RU</a>|
|[InventProfileType](#InventProfileType)||<a href="PurchAgreementHeaderHistoryExt_RU.md" target="_blank">TransactionHeader/PurchAgreementHeaderHistoryExt_RU</a>|
|[LineOfBusinessId](#LineOfBusinessId)||<a href="PurchAgreementHeaderHistoryExt_RU.md" target="_blank">TransactionHeader/PurchAgreementHeaderHistoryExt_RU</a>|
|[PaymDayId](#PaymDayId)||<a href="PurchAgreementHeaderHistoryExt_RU.md" target="_blank">TransactionHeader/PurchAgreementHeaderHistoryExt_RU</a>|
|[Phone](#Phone)||<a href="PurchAgreementHeaderHistoryExt_RU.md" target="_blank">TransactionHeader/PurchAgreementHeaderHistoryExt_RU</a>|
|[PhoneLocal](#PhoneLocal)||<a href="PurchAgreementHeaderHistoryExt_RU.md" target="_blank">TransactionHeader/PurchAgreementHeaderHistoryExt_RU</a>|
|[TaxAmountDifference](#TaxAmountDifference)||<a href="PurchAgreementHeaderHistoryExt_RU.md" target="_blank">TransactionHeader/PurchAgreementHeaderHistoryExt_RU</a>|
|[TeleFax](#TeleFax)||<a href="PurchAgreementHeaderHistoryExt_RU.md" target="_blank">TransactionHeader/PurchAgreementHeaderHistoryExt_RU</a>|
|[Telex](#Telex)||<a href="PurchAgreementHeaderHistoryExt_RU.md" target="_blank">TransactionHeader/PurchAgreementHeaderHistoryExt_RU</a>|
|[Url](#Url)||<a href="PurchAgreementHeaderHistoryExt_RU.md" target="_blank">TransactionHeader/PurchAgreementHeaderHistoryExt_RU</a>|
|[DataAreaId](#DataAreaId)||<a href="PurchAgreementHeaderHistoryExt_RU.md" target="_blank">TransactionHeader/PurchAgreementHeaderHistoryExt_RU</a>|
|[Relationship_AgreementHeaderHistoryRelationshipId](#Relationship_AgreementHeaderHistoryRelationshipId)||<a href="PurchAgreementHeaderHistoryExt_RU.md" target="_blank">TransactionHeader/PurchAgreementHeaderHistoryExt_RU</a>|
|[Relationship_DefaultDimensionRelationshipId](#Relationship_DefaultDimensionRelationshipId)||<a href="PurchAgreementHeaderHistoryExt_RU.md" target="_blank">TransactionHeader/PurchAgreementHeaderHistoryExt_RU</a>|
|[Relationship_InventProfileRelationshipId](#Relationship_InventProfileRelationshipId)||<a href="PurchAgreementHeaderHistoryExt_RU.md" target="_blank">TransactionHeader/PurchAgreementHeaderHistoryExt_RU</a>|
|[Relationship_LineOfBusinessRelationshipId](#Relationship_LineOfBusinessRelationshipId)||<a href="PurchAgreementHeaderHistoryExt_RU.md" target="_blank">TransactionHeader/PurchAgreementHeaderHistoryExt_RU</a>|
|[Relationship_PaymDayRelationshipId](#Relationship_PaymDayRelationshipId)||<a href="PurchAgreementHeaderHistoryExt_RU.md" target="_blank">TransactionHeader/PurchAgreementHeaderHistoryExt_RU</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="PurchAgreementHeaderHistoryExt_RU.md" target="_blank">TransactionHeader/PurchAgreementHeaderHistoryExt_RU</a>|
|[VATChargeSource](#VATChargeSource)||<a href="PurchAgreementHeaderHistoryExt_RU.md" target="_blank">TransactionHeader/PurchAgreementHeaderHistoryExt_RU</a>|
|[VATOperationCode](#VATOperationCode)||<a href="PurchAgreementHeaderHistoryExt_RU.md" target="_blank">TransactionHeader/PurchAgreementHeaderHistoryExt_RU</a>|
|[VendPostingProfile](#VendPostingProfile)||<a href="PurchAgreementHeaderHistoryExt_RU.md" target="_blank">TransactionHeader/PurchAgreementHeaderHistoryExt_RU</a>|
|[VendPrepaymentPostingProfile](#VendPrepaymentPostingProfile)||<a href="PurchAgreementHeaderHistoryExt_RU.md" target="_blank">TransactionHeader/PurchAgreementHeaderHistoryExt_RU</a>|
|[WorkerPurchResponsible](#WorkerPurchResponsible)||<a href="PurchAgreementHeaderHistoryExt_RU.md" target="_blank">TransactionHeader/PurchAgreementHeaderHistoryExt_RU</a>|
|[Relationship_VATOperationCodeTableRelationshipId](#Relationship_VATOperationCodeTableRelationshipId)||<a href="PurchAgreementHeaderHistoryExt_RU.md" target="_blank">TransactionHeader/PurchAgreementHeaderHistoryExt_RU</a>|
|[Relationship_VendLedgerPostingProfileRelationshipId](#Relationship_VendLedgerPostingProfileRelationshipId)||<a href="PurchAgreementHeaderHistoryExt_RU.md" target="_blank">TransactionHeader/PurchAgreementHeaderHistoryExt_RU</a>|
|[Relationship_VendLedgerPrepaymentProfileRelationshipId](#Relationship_VendLedgerPrepaymentProfileRelationshipId)||<a href="PurchAgreementHeaderHistoryExt_RU.md" target="_blank">TransactionHeader/PurchAgreementHeaderHistoryExt_RU</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: TransactionHeader/PurchAgreementHeaderHistoryExt_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PurchAgreementHeaderHistoryExt_RU/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AgreementAmount name="AgreementAmount">AgreementAmount</a>

First included in: TransactionHeader/PurchAgreementHeaderHistoryExt_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgreementAmount attribute are listed below.</summary>

**is.nullable**  
The attribute value may be set to NULL.  

</details>

### <a href=#AgreementDate name="AgreementDate">AgreementDate</a>

First included in: TransactionHeader/PurchAgreementHeaderHistoryExt_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgreementDate attribute are listed below.</summary>

**is.nullable**  
The attribute value may be set to NULL.  

</details>

### <a href=#AgreementHeaderHistory name="AgreementHeaderHistory">AgreementHeaderHistory</a>

First included in: TransactionHeader/PurchAgreementHeaderHistoryExt_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgreementHeaderHistory attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AgreementId name="AgreementId">AgreementId</a>

First included in: TransactionHeader/PurchAgreementHeaderHistoryExt_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgreementId attribute are listed below.</summary>

**is.readOnly**  
</details>

### <a href=#AgreementSubject name="AgreementSubject">AgreementSubject</a>

First included in: TransactionHeader/PurchAgreementHeaderHistoryExt_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgreementSubject attribute are listed below.</summary>

**is.nullable**  
The attribute value may be set to NULL.  

</details>

### <a href=#AgreementVatAmount name="AgreementVatAmount">AgreementVatAmount</a>

First included in: TransactionHeader/PurchAgreementHeaderHistoryExt_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgreementVatAmount attribute are listed below.</summary>

**is.nullable**  
The attribute value may be set to NULL.  

</details>

### <a href=#CellularPhone name="CellularPhone">CellularPhone</a>

First included in: TransactionHeader/PurchAgreementHeaderHistoryExt_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CellularPhone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditMax name="CreditMax">CreditMax</a>

First included in: TransactionHeader/PurchAgreementHeaderHistoryExt_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditMax attribute are listed below.</summary>

**is.nullable**  
The attribute value may be set to NULL.  

</details>

### <a href=#DefaultDimension name="DefaultDimension">DefaultDimension</a>

First included in: TransactionHeader/PurchAgreementHeaderHistoryExt_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimension attribute are listed below.</summary>

**is.nullable**  
The attribute value may be set to NULL.  

</details>

### <a href=#Email name="Email">Email</a>

First included in: TransactionHeader/PurchAgreementHeaderHistoryExt_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Email attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InstanceRelationType name="InstanceRelationType">InstanceRelationType</a>

First included in: TransactionHeader/PurchAgreementHeaderHistoryExt_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InstanceRelationType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#InventProfileId name="InventProfileId">InventProfileId</a>

First included in: TransactionHeader/PurchAgreementHeaderHistoryExt_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventProfileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventProfileType name="InventProfileType">InventProfileType</a>

First included in: TransactionHeader/PurchAgreementHeaderHistoryExt_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventProfileType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#LineOfBusinessId name="LineOfBusinessId">LineOfBusinessId</a>

First included in: TransactionHeader/PurchAgreementHeaderHistoryExt_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineOfBusinessId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymDayId name="PaymDayId">PaymDayId</a>

First included in: TransactionHeader/PurchAgreementHeaderHistoryExt_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymDayId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Phone name="Phone">Phone</a>

First included in: TransactionHeader/PurchAgreementHeaderHistoryExt_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Phone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PhoneLocal name="PhoneLocal">PhoneLocal</a>

First included in: TransactionHeader/PurchAgreementHeaderHistoryExt_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PhoneLocal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxAmountDifference name="TaxAmountDifference">TaxAmountDifference</a>

First included in: TransactionHeader/PurchAgreementHeaderHistoryExt_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAmountDifference attribute are listed below.</summary>

**is.nullable**  
The attribute value may be set to NULL.  

</details>

### <a href=#TeleFax name="TeleFax">TeleFax</a>

First included in: TransactionHeader/PurchAgreementHeaderHistoryExt_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TeleFax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Telex name="Telex">Telex</a>

First included in: TransactionHeader/PurchAgreementHeaderHistoryExt_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Telex attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Url name="Url">Url</a>

First included in: TransactionHeader/PurchAgreementHeaderHistoryExt_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Url attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: TransactionHeader/PurchAgreementHeaderHistoryExt_RU (this entity)  

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

### <a href=#Relationship_AgreementHeaderHistoryRelationshipId name="Relationship_AgreementHeaderHistoryRelationshipId">Relationship_AgreementHeaderHistoryRelationshipId</a>

First included in: TransactionHeader/PurchAgreementHeaderHistoryExt_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AgreementHeaderHistoryRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProcurementAndSourcing/TransactionHeader/AgreementHeaderHistory.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/TransactionHeader/AgreementHeaderHistory.cdm.json/AgreementHeaderHistory</a></td><td><a href="../../../SupplyChain/ProcurementAndSourcing/TransactionHeader/AgreementHeaderHistory.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultDimensionRelationshipId name="Relationship_DefaultDimensionRelationshipId">Relationship_DefaultDimensionRelationshipId</a>

First included in: TransactionHeader/PurchAgreementHeaderHistoryExt_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueSet.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueSet.cdm.json/DimensionAttributeValueSet</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueSet.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventProfileRelationshipId name="Relationship_InventProfileRelationshipId">Relationship_InventProfileRelationshipId</a>

First included in: TransactionHeader/PurchAgreementHeaderHistoryExt_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventProfileRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Inventory/Group/InventProfile_RU.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/InventProfile_RU.cdm.json/InventProfile_RU</a></td><td><a href="../../../SupplyChain/Inventory/Group/InventProfile_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LineOfBusinessRelationshipId name="Relationship_LineOfBusinessRelationshipId">Relationship_LineOfBusinessRelationshipId</a>

First included in: TransactionHeader/PurchAgreementHeaderHistoryExt_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LineOfBusinessRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/LineOfBusiness.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsPayable/Group/LineOfBusiness.cdm.json/LineOfBusiness</a></td><td><a href="../Group/LineOfBusiness.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PaymDayRelationshipId name="Relationship_PaymDayRelationshipId">Relationship_PaymDayRelationshipId</a>

First included in: TransactionHeader/PurchAgreementHeaderHistoryExt_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PaymDayRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Bank/Group/PaymDay.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Group/PaymDay.cdm.json/PaymDay</a></td><td><a href="../../Bank/Group/PaymDay.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: TransactionHeader/PurchAgreementHeaderHistoryExt_RU (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VATChargeSource name="VATChargeSource">VATChargeSource</a>

First included in: TransactionHeader/PurchAgreementHeaderHistoryExt_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VATChargeSource attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#VATOperationCode name="VATOperationCode">VATOperationCode</a>

First included in: TransactionHeader/PurchAgreementHeaderHistoryExt_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VATOperationCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendPostingProfile name="VendPostingProfile">VendPostingProfile</a>

First included in: TransactionHeader/PurchAgreementHeaderHistoryExt_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendPostingProfile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendPrepaymentPostingProfile name="VendPrepaymentPostingProfile">VendPrepaymentPostingProfile</a>

First included in: TransactionHeader/PurchAgreementHeaderHistoryExt_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Posting profile with prepayment journal voucher</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendPrepaymentPostingProfile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Posting profile with prepayment journal voucher</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkerPurchResponsible name="WorkerPurchResponsible">WorkerPurchResponsible</a>

First included in: TransactionHeader/PurchAgreementHeaderHistoryExt_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerPurchResponsible attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_VATOperationCodeTableRelationshipId name="Relationship_VATOperationCodeTableRelationshipId">Relationship_VATOperationCodeTableRelationshipId</a>

First included in: TransactionHeader/PurchAgreementHeaderHistoryExt_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VATOperationCodeTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../RSalesPurchBooks/Group/VATOperationCodeTable_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/RSalesPurchBooks/Group/VATOperationCodeTable_RU.cdm.json/VATOperationCodeTable_RU</a></td><td><a href="../../RSalesPurchBooks/Group/VATOperationCodeTable_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendLedgerPostingProfileRelationshipId name="Relationship_VendLedgerPostingProfileRelationshipId">Relationship_VendLedgerPostingProfileRelationshipId</a>

First included in: TransactionHeader/PurchAgreementHeaderHistoryExt_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendLedgerPostingProfileRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/VendLedger.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsPayable/Group/VendLedger.cdm.json/VendLedger</a></td><td><a href="../Group/VendLedger.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendLedgerPrepaymentProfileRelationshipId name="Relationship_VendLedgerPrepaymentProfileRelationshipId">Relationship_VendLedgerPrepaymentProfileRelationshipId</a>

First included in: TransactionHeader/PurchAgreementHeaderHistoryExt_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendLedgerPrepaymentProfileRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/VendLedger.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsPayable/Group/VendLedger.cdm.json/VendLedger</a></td><td><a href="../Group/VendLedger.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
