---
title: MCRCustomerInvoicePaymentEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# Customer payments

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/AccountsReceivable/MCRCustomerInvoicePaymentEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Customer payments</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[Amount](#Amount)||<a href="MCRCustomerInvoicePaymentEntity.md" target="_blank">AccountsReceivable/MCRCustomerInvoicePaymentEntity</a>|
|[IsCheckAuthorized](#IsCheckAuthorized)||<a href="MCRCustomerInvoicePaymentEntity.md" target="_blank">AccountsReceivable/MCRCustomerInvoicePaymentEntity</a>|
|[CheckNumber](#CheckNumber)||<a href="MCRCustomerInvoicePaymentEntity.md" target="_blank">AccountsReceivable/MCRCustomerInvoicePaymentEntity</a>|
|[CurrencyCode](#CurrencyCode)||<a href="MCRCustomerInvoicePaymentEntity.md" target="_blank">AccountsReceivable/MCRCustomerInvoicePaymentEntity</a>|
|[CustomerAccount](#CustomerAccount)||<a href="MCRCustomerInvoicePaymentEntity.md" target="_blank">AccountsReceivable/MCRCustomerInvoicePaymentEntity</a>|
|[CustomerPaymentType](#CustomerPaymentType)||<a href="MCRCustomerInvoicePaymentEntity.md" target="_blank">AccountsReceivable/MCRCustomerInvoicePaymentEntity</a>|
|[IsPlanRefund](#IsPlanRefund)||<a href="MCRCustomerInvoicePaymentEntity.md" target="_blank">AccountsReceivable/MCRCustomerInvoicePaymentEntity</a>|
|[IsPrepay](#IsPrepay)||<a href="MCRCustomerInvoicePaymentEntity.md" target="_blank">AccountsReceivable/MCRCustomerInvoicePaymentEntity</a>|
|[AuthorizationRetryNumber](#AuthorizationRetryNumber)||<a href="MCRCustomerInvoicePaymentEntity.md" target="_blank">AccountsReceivable/MCRCustomerInvoicePaymentEntity</a>|
|[IsOnAccountAuthorized](#IsOnAccountAuthorized)||<a href="MCRCustomerInvoicePaymentEntity.md" target="_blank">AccountsReceivable/MCRCustomerInvoicePaymentEntity</a>|
|[PaymentSchedId](#PaymentSchedId)||<a href="MCRCustomerInvoicePaymentEntity.md" target="_blank">AccountsReceivable/MCRCustomerInvoicePaymentEntity</a>|
|[PercentAmount](#PercentAmount)||<a href="MCRCustomerInvoicePaymentEntity.md" target="_blank">AccountsReceivable/MCRCustomerInvoicePaymentEntity</a>|
|[PostedAmount](#PostedAmount)||<a href="MCRCustomerInvoicePaymentEntity.md" target="_blank">AccountsReceivable/MCRCustomerInvoicePaymentEntity</a>|
|[UniqueCreditCardId](#UniqueCreditCardId)||<a href="MCRCustomerInvoicePaymentEntity.md" target="_blank">AccountsReceivable/MCRCustomerInvoicePaymentEntity</a>|
|[IsCreditCardProcessed](#IsCreditCardProcessed)||<a href="MCRCustomerInvoicePaymentEntity.md" target="_blank">AccountsReceivable/MCRCustomerInvoicePaymentEntity</a>|
|[RetailGiftCardId](#RetailGiftCardId)||<a href="MCRCustomerInvoicePaymentEntity.md" target="_blank">AccountsReceivable/MCRCustomerInvoicePaymentEntity</a>|
|[Status](#Status)||<a href="MCRCustomerInvoicePaymentEntity.md" target="_blank">AccountsReceivable/MCRCustomerInvoicePaymentEntity</a>|
|[RetailStoreCardTypeId](#RetailStoreCardTypeId)||<a href="MCRCustomerInvoicePaymentEntity.md" target="_blank">AccountsReceivable/MCRCustomerInvoicePaymentEntity</a>|
|[RetailStoreTenderTypeId](#RetailStoreTenderTypeId)||<a href="MCRCustomerInvoicePaymentEntity.md" target="_blank">AccountsReceivable/MCRCustomerInvoicePaymentEntity</a>|
|[RetailChannelId](#RetailChannelId)||<a href="MCRCustomerInvoicePaymentEntity.md" target="_blank">AccountsReceivable/MCRCustomerInvoicePaymentEntity</a>|
|[InvoiceId](#InvoiceId)||<a href="MCRCustomerInvoicePaymentEntity.md" target="_blank">AccountsReceivable/MCRCustomerInvoicePaymentEntity</a>|
|[LineNumber](#LineNumber)||<a href="MCRCustomerInvoicePaymentEntity.md" target="_blank">AccountsReceivable/MCRCustomerInvoicePaymentEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="MCRCustomerInvoicePaymentEntity.md" target="_blank">AccountsReceivable/MCRCustomerInvoicePaymentEntity</a>|

### <a href=#Amount name="Amount">Amount</a>

First included in: AccountsReceivable/MCRCustomerInvoicePaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Amount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCheckAuthorized name="IsCheckAuthorized">IsCheckAuthorized</a>

First included in: AccountsReceivable/MCRCustomerInvoicePaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCheckAuthorized attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CheckNumber name="CheckNumber">CheckNumber</a>

First included in: AccountsReceivable/MCRCustomerInvoicePaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CheckNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: AccountsReceivable/MCRCustomerInvoicePaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerAccount name="CustomerAccount">CustomerAccount</a>

First included in: AccountsReceivable/MCRCustomerInvoicePaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerPaymentType name="CustomerPaymentType">CustomerPaymentType</a>

First included in: AccountsReceivable/MCRCustomerInvoicePaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerPaymentType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPlanRefund name="IsPlanRefund">IsPlanRefund</a>

First included in: AccountsReceivable/MCRCustomerInvoicePaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPlanRefund attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPrepay name="IsPrepay">IsPrepay</a>

First included in: AccountsReceivable/MCRCustomerInvoicePaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPrepay attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AuthorizationRetryNumber name="AuthorizationRetryNumber">AuthorizationRetryNumber</a>

First included in: AccountsReceivable/MCRCustomerInvoicePaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AuthorizationRetryNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsOnAccountAuthorized name="IsOnAccountAuthorized">IsOnAccountAuthorized</a>

First included in: AccountsReceivable/MCRCustomerInvoicePaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsOnAccountAuthorized attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentSchedId name="PaymentSchedId">PaymentSchedId</a>

First included in: AccountsReceivable/MCRCustomerInvoicePaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentSchedId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PercentAmount name="PercentAmount">PercentAmount</a>

First included in: AccountsReceivable/MCRCustomerInvoicePaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PercentAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostedAmount name="PostedAmount">PostedAmount</a>

First included in: AccountsReceivable/MCRCustomerInvoicePaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostedAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UniqueCreditCardId name="UniqueCreditCardId">UniqueCreditCardId</a>

First included in: AccountsReceivable/MCRCustomerInvoicePaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UniqueCreditCardId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCreditCardProcessed name="IsCreditCardProcessed">IsCreditCardProcessed</a>

First included in: AccountsReceivable/MCRCustomerInvoicePaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCreditCardProcessed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailGiftCardId name="RetailGiftCardId">RetailGiftCardId</a>

First included in: AccountsReceivable/MCRCustomerInvoicePaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailGiftCardId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Status name="Status">Status</a>

First included in: AccountsReceivable/MCRCustomerInvoicePaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Status attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailStoreCardTypeId name="RetailStoreCardTypeId">RetailStoreCardTypeId</a>

First included in: AccountsReceivable/MCRCustomerInvoicePaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailStoreCardTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailStoreTenderTypeId name="RetailStoreTenderTypeId">RetailStoreTenderTypeId</a>

First included in: AccountsReceivable/MCRCustomerInvoicePaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailStoreTenderTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailChannelId name="RetailChannelId">RetailChannelId</a>

First included in: AccountsReceivable/MCRCustomerInvoicePaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailChannelId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceId name="InvoiceId">InvoiceId</a>

First included in: AccountsReceivable/MCRCustomerInvoicePaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: AccountsReceivable/MCRCustomerInvoicePaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: AccountsReceivable/MCRCustomerInvoicePaymentEntity (this entity)  

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
