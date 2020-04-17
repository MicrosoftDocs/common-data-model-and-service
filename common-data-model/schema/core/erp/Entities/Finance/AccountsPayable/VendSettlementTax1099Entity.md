---
title: VendSettlementTax1099Entity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# VendSettlementTax1099Entity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Entities/Finance/AccountsPayable/VendSettlementTax1099Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[VendorAccount](#VendorAccount)||<a href="VendSettlementTax1099Entity.md" target="_blank">AccountsPayable/VendSettlementTax1099Entity</a>|
|[TransDate](#TransDate)||<a href="VendSettlementTax1099Entity.md" target="_blank">AccountsPayable/VendSettlementTax1099Entity</a>|
|[SettledFederal1099](#SettledFederal1099)||<a href="VendSettlementTax1099Entity.md" target="_blank">AccountsPayable/VendSettlementTax1099Entity</a>|
|[CountryRegion](#CountryRegion)||<a href="VendSettlementTax1099Entity.md" target="_blank">AccountsPayable/VendSettlementTax1099Entity</a>|
|[State](#State)||<a href="VendSettlementTax1099Entity.md" target="_blank">AccountsPayable/VendSettlementTax1099Entity</a>|
|[SettledState1099](#SettledState1099)||<a href="VendSettlementTax1099Entity.md" target="_blank">AccountsPayable/VendSettlementTax1099Entity</a>|
|[ManualEntry](#ManualEntry)||<a href="VendSettlementTax1099Entity.md" target="_blank">AccountsPayable/VendSettlementTax1099Entity</a>|
|[G10aState](#G10aState)||<a href="VendSettlementTax1099Entity.md" target="_blank">AccountsPayable/VendSettlementTax1099Entity</a>|
|[G10bStateIdNumber](#G10bStateIdNumber)||<a href="VendSettlementTax1099Entity.md" target="_blank">AccountsPayable/VendSettlementTax1099Entity</a>|
|[G11StateIncomeTaxWithheld](#G11StateIncomeTaxWithheld)||<a href="VendSettlementTax1099Entity.md" target="_blank">AccountsPayable/VendSettlementTax1099Entity</a>|
|[G3TaxYear](#G3TaxYear)||<a href="VendSettlementTax1099Entity.md" target="_blank">AccountsPayable/VendSettlementTax1099Entity</a>|
|[G8TradeOrBusinessIncome](#G8TradeOrBusinessIncome)||<a href="VendSettlementTax1099Entity.md" target="_blank">AccountsPayable/VendSettlementTax1099Entity</a>|
|[S1DateOfClosing](#S1DateOfClosing)||<a href="VendSettlementTax1099Entity.md" target="_blank">AccountsPayable/VendSettlementTax1099Entity</a>|
|[S3AddressOrLegalDescription](#S3AddressOrLegalDescription)||<a href="VendSettlementTax1099Entity.md" target="_blank">AccountsPayable/VendSettlementTax1099Entity</a>|
|[S4TransferorRecievedProperty](#S4TransferorRecievedProperty)||<a href="VendSettlementTax1099Entity.md" target="_blank">AccountsPayable/VendSettlementTax1099Entity</a>|
|[S5BuyerPartOfRealEstateTax](#S5BuyerPartOfRealEstateTax)||<a href="VendSettlementTax1099Entity.md" target="_blank">AccountsPayable/VendSettlementTax1099Entity</a>|
|[Tax1099BoxIdRef](#Tax1099BoxIdRef)||<a href="VendSettlementTax1099Entity.md" target="_blank">AccountsPayable/VendSettlementTax1099Entity</a>|
|[Tax1099BoxId](#Tax1099BoxId)||<a href="VendSettlementTax1099Entity.md" target="_blank">AccountsPayable/VendSettlementTax1099Entity</a>|
|[Tax1099Type](#Tax1099Type)||<a href="VendSettlementTax1099Entity.md" target="_blank">AccountsPayable/VendSettlementTax1099Entity</a>|
|[RecordId](#RecordId)||<a href="VendSettlementTax1099Entity.md" target="_blank">AccountsPayable/VendSettlementTax1099Entity</a>|
|[BackingTable_VendSettlementTax1099RelationshipId](#BackingTable_VendSettlementTax1099RelationshipId)||<a href="VendSettlementTax1099Entity.md" target="_blank">AccountsPayable/VendSettlementTax1099Entity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="VendSettlementTax1099Entity.md" target="_blank">AccountsPayable/VendSettlementTax1099Entity</a>|

### <a href=#VendorAccount name="VendorAccount">VendorAccount</a>

First included in: AccountsPayable/VendSettlementTax1099Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransDate name="TransDate">TransDate</a>

First included in: AccountsPayable/VendSettlementTax1099Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SettledFederal1099 name="SettledFederal1099">SettledFederal1099</a>

First included in: AccountsPayable/VendSettlementTax1099Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SettledFederal1099 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CountryRegion name="CountryRegion">CountryRegion</a>

First included in: AccountsPayable/VendSettlementTax1099Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CountryRegion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#State name="State">State</a>

First included in: AccountsPayable/VendSettlementTax1099Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the State attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SettledState1099 name="SettledState1099">SettledState1099</a>

First included in: AccountsPayable/VendSettlementTax1099Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SettledState1099 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ManualEntry name="ManualEntry">ManualEntry</a>

First included in: AccountsPayable/VendSettlementTax1099Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ManualEntry attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#G10aState name="G10aState">G10aState</a>

First included in: AccountsPayable/VendSettlementTax1099Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the G10aState attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#G10bStateIdNumber name="G10bStateIdNumber">G10bStateIdNumber</a>

First included in: AccountsPayable/VendSettlementTax1099Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the G10bStateIdNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#G11StateIncomeTaxWithheld name="G11StateIncomeTaxWithheld">G11StateIncomeTaxWithheld</a>

First included in: AccountsPayable/VendSettlementTax1099Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the G11StateIncomeTaxWithheld attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#G3TaxYear name="G3TaxYear">G3TaxYear</a>

First included in: AccountsPayable/VendSettlementTax1099Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the G3TaxYear attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#G8TradeOrBusinessIncome name="G8TradeOrBusinessIncome">G8TradeOrBusinessIncome</a>

First included in: AccountsPayable/VendSettlementTax1099Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the G8TradeOrBusinessIncome attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#S1DateOfClosing name="S1DateOfClosing">S1DateOfClosing</a>

First included in: AccountsPayable/VendSettlementTax1099Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the S1DateOfClosing attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#S3AddressOrLegalDescription name="S3AddressOrLegalDescription">S3AddressOrLegalDescription</a>

First included in: AccountsPayable/VendSettlementTax1099Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the S3AddressOrLegalDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#S4TransferorRecievedProperty name="S4TransferorRecievedProperty">S4TransferorRecievedProperty</a>

First included in: AccountsPayable/VendSettlementTax1099Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the S4TransferorRecievedProperty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#S5BuyerPartOfRealEstateTax name="S5BuyerPartOfRealEstateTax">S5BuyerPartOfRealEstateTax</a>

First included in: AccountsPayable/VendSettlementTax1099Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the S5BuyerPartOfRealEstateTax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Tax1099BoxIdRef name="Tax1099BoxIdRef">Tax1099BoxIdRef</a>

First included in: AccountsPayable/VendSettlementTax1099Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Tax1099BoxIdRef attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Tax1099BoxId name="Tax1099BoxId">Tax1099BoxId</a>

First included in: AccountsPayable/VendSettlementTax1099Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Tax1099BoxId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Tax1099Type name="Tax1099Type">Tax1099Type</a>

First included in: AccountsPayable/VendSettlementTax1099Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Tax1099Type attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RecordId name="RecordId">RecordId</a>

First included in: AccountsPayable/VendSettlementTax1099Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecordId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_VendSettlementTax1099RelationshipId name="BackingTable_VendSettlementTax1099RelationshipId">BackingTable_VendSettlementTax1099RelationshipId</a>

First included in: AccountsPayable/VendSettlementTax1099Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_VendSettlementTax1099RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/AccountsPayable/Transaction/VendSettlementTax1099.md" target="_blank">/core/erp/Tables/Finance/AccountsPayable/Transaction/VendSettlementTax1099.cdm.json/VendSettlementTax1099</a></td><td><a href="../../../Tables/Finance/AccountsPayable/Transaction/VendSettlementTax1099.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: AccountsPayable/VendSettlementTax1099Entity (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/erp/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
