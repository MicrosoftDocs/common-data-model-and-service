---
title: CustDirectDebitMandateEntity in AccountsReceivable - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/8/2020
ms.author: nebanfic
---

# Customer direct debit mandates in AccountsReceivable(CustDirectDebitMandateEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/AccountsReceivable/CustDirectDebitMandateEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Customer direct debit mandates</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[CustomerAccount](#CustomerAccount)||<a href="CustDirectDebitMandateEntity.md" target="_blank">AccountsReceivable/CustDirectDebitMandateEntity</a>|
|[MandateId](#MandateId)||<a href="CustDirectDebitMandateEntity.md" target="_blank">AccountsReceivable/CustDirectDebitMandateEntity</a>|
|[CustomerBankAccount](#CustomerBankAccount)||<a href="CustDirectDebitMandateEntity.md" target="_blank">AccountsReceivable/CustDirectDebitMandateEntity</a>|
|[CustomerAddress](#CustomerAddress)||<a href="CustDirectDebitMandateEntity.md" target="_blank">AccountsReceivable/CustDirectDebitMandateEntity</a>|
|[DaysForFirstBankSubmission](#DaysForFirstBankSubmission)||<a href="CustDirectDebitMandateEntity.md" target="_blank">AccountsReceivable/CustDirectDebitMandateEntity</a>|
|[DaysForRecurringBankSubmission](#DaysForRecurringBankSubmission)||<a href="CustDirectDebitMandateEntity.md" target="_blank">AccountsReceivable/CustDirectDebitMandateEntity</a>|
|[DaysForFirstPrenotification](#DaysForFirstPrenotification)||<a href="CustDirectDebitMandateEntity.md" target="_blank">AccountsReceivable/CustDirectDebitMandateEntity</a>|
|[DaysForRecurringPrenotification](#DaysForRecurringPrenotification)||<a href="CustDirectDebitMandateEntity.md" target="_blank">AccountsReceivable/CustDirectDebitMandateEntity</a>|
|[CancellationDate](#CancellationDate)||<a href="CustDirectDebitMandateEntity.md" target="_blank">AccountsReceivable/CustDirectDebitMandateEntity</a>|
|[ExpirationDate](#ExpirationDate)||<a href="CustDirectDebitMandateEntity.md" target="_blank">AccountsReceivable/CustDirectDebitMandateEntity</a>|
|[MandatePaymentType](#MandatePaymentType)||<a href="CustDirectDebitMandateEntity.md" target="_blank">AccountsReceivable/CustDirectDebitMandateEntity</a>|
|[MandateScheme](#MandateScheme)||<a href="CustDirectDebitMandateEntity.md" target="_blank">AccountsReceivable/CustDirectDebitMandateEntity</a>|
|[SignatureDate](#SignatureDate)||<a href="CustDirectDebitMandateEntity.md" target="_blank">AccountsReceivable/CustDirectDebitMandateEntity</a>|
|[SignatureLocation](#SignatureLocation)||<a href="CustDirectDebitMandateEntity.md" target="_blank">AccountsReceivable/CustDirectDebitMandateEntity</a>|
|[ExpectedNumberOfPayments](#ExpectedNumberOfPayments)||<a href="CustDirectDebitMandateEntity.md" target="_blank">AccountsReceivable/CustDirectDebitMandateEntity</a>|
|[UsageCount](#UsageCount)||<a href="CustDirectDebitMandateEntity.md" target="_blank">AccountsReceivable/CustDirectDebitMandateEntity</a>|
|[Status](#Status)||<a href="CustDirectDebitMandateEntity.md" target="_blank">AccountsReceivable/CustDirectDebitMandateEntity</a>|
|[IsPrivate](#IsPrivate)||<a href="CustDirectDebitMandateEntity.md" target="_blank">AccountsReceivable/CustDirectDebitMandateEntity</a>|
|[PrivateForParty](#PrivateForParty)||<a href="CustDirectDebitMandateEntity.md" target="_blank">AccountsReceivable/CustDirectDebitMandateEntity</a>|
|[CreditorBankAccount](#CreditorBankAccount)||<a href="CustDirectDebitMandateEntity.md" target="_blank">AccountsReceivable/CustDirectDebitMandateEntity</a>|
|[BackingTable_CustDirectDebitMandateRelationshipId](#BackingTable_CustDirectDebitMandateRelationshipId)||<a href="CustDirectDebitMandateEntity.md" target="_blank">AccountsReceivable/CustDirectDebitMandateEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="CustDirectDebitMandateEntity.md" target="_blank">AccountsReceivable/CustDirectDebitMandateEntity</a>|

### <a href=#CustomerAccount name="CustomerAccount">CustomerAccount</a>

First included in: AccountsReceivable/CustDirectDebitMandateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MandateId name="MandateId">MandateId</a>

First included in: AccountsReceivable/CustDirectDebitMandateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MandateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerBankAccount name="CustomerBankAccount">CustomerBankAccount</a>

First included in: AccountsReceivable/CustDirectDebitMandateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerBankAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerAddress name="CustomerAddress">CustomerAddress</a>

First included in: AccountsReceivable/CustDirectDebitMandateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DaysForFirstBankSubmission name="DaysForFirstBankSubmission">DaysForFirstBankSubmission</a>

First included in: AccountsReceivable/CustDirectDebitMandateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DaysForFirstBankSubmission attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DaysForRecurringBankSubmission name="DaysForRecurringBankSubmission">DaysForRecurringBankSubmission</a>

First included in: AccountsReceivable/CustDirectDebitMandateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DaysForRecurringBankSubmission attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DaysForFirstPrenotification name="DaysForFirstPrenotification">DaysForFirstPrenotification</a>

First included in: AccountsReceivable/CustDirectDebitMandateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DaysForFirstPrenotification attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DaysForRecurringPrenotification name="DaysForRecurringPrenotification">DaysForRecurringPrenotification</a>

First included in: AccountsReceivable/CustDirectDebitMandateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DaysForRecurringPrenotification attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CancellationDate name="CancellationDate">CancellationDate</a>

First included in: AccountsReceivable/CustDirectDebitMandateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CancellationDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExpirationDate name="ExpirationDate">ExpirationDate</a>

First included in: AccountsReceivable/CustDirectDebitMandateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpirationDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MandatePaymentType name="MandatePaymentType">MandatePaymentType</a>

First included in: AccountsReceivable/CustDirectDebitMandateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MandatePaymentType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MandateScheme name="MandateScheme">MandateScheme</a>

First included in: AccountsReceivable/CustDirectDebitMandateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MandateScheme attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SignatureDate name="SignatureDate">SignatureDate</a>

First included in: AccountsReceivable/CustDirectDebitMandateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SignatureDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SignatureLocation name="SignatureLocation">SignatureLocation</a>

First included in: AccountsReceivable/CustDirectDebitMandateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SignatureLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExpectedNumberOfPayments name="ExpectedNumberOfPayments">ExpectedNumberOfPayments</a>

First included in: AccountsReceivable/CustDirectDebitMandateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpectedNumberOfPayments attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UsageCount name="UsageCount">UsageCount</a>

First included in: AccountsReceivable/CustDirectDebitMandateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UsageCount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Status name="Status">Status</a>

First included in: AccountsReceivable/CustDirectDebitMandateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Mandate status</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Status attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Mandate status</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPrivate name="IsPrivate">IsPrivate</a>

First included in: AccountsReceivable/CustDirectDebitMandateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPrivate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrivateForParty name="PrivateForParty">PrivateForParty</a>

First included in: AccountsReceivable/CustDirectDebitMandateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrivateForParty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditorBankAccount name="CreditorBankAccount">CreditorBankAccount</a>

First included in: AccountsReceivable/CustDirectDebitMandateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditorBankAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_CustDirectDebitMandateRelationshipId name="BackingTable_CustDirectDebitMandateRelationshipId">BackingTable_CustDirectDebitMandateRelationshipId</a>

First included in: AccountsReceivable/CustDirectDebitMandateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_CustDirectDebitMandateRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/AccountsReceivable/Main/CustDirectDebitMandate.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Main/CustDirectDebitMandate.cdm.json/CustDirectDebitMandate</a></td><td><a href="../../../Tables/Finance/AccountsReceivable/Main/CustDirectDebitMandate.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: AccountsReceivable/CustDirectDebitMandateEntity (this entity)  

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
