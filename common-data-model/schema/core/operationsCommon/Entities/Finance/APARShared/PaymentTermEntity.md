---
title: PaymentTermEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# PaymentTermEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/APARShared/PaymentTermEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[AdditionalMonthsForCutoffDate](#AdditionalMonthsForCutoffDate)||<a href="PaymentTermEntity.md" target="_blank">APARShared/PaymentTermEntity</a>|
|[IsCashPayment](#IsCashPayment)||<a href="PaymentTermEntity.md" target="_blank">APARShared/PaymentTermEntity</a>|
|[CashPaymentMainAccountId](#CashPaymentMainAccountId)||<a href="PaymentTermEntity.md" target="_blank">APARShared/PaymentTermEntity</a>|
|[CreditCardCreditCheckType](#CreditCardCreditCheckType)||<a href="PaymentTermEntity.md" target="_blank">APARShared/PaymentTermEntity</a>|
|[CreditCardPaymentType](#CreditCardPaymentType)||<a href="PaymentTermEntity.md" target="_blank">APARShared/PaymentTermEntity</a>|
|[CustomerDueDateUpdatePolicy](#CustomerDueDateUpdatePolicy)||<a href="PaymentTermEntity.md" target="_blank">APARShared/PaymentTermEntity</a>|
|[CutoffDayOfMonth](#CutoffDayOfMonth)||<a href="PaymentTermEntity.md" target="_blank">APARShared/PaymentTermEntity</a>|
|[IsDefaultPaymentTerm](#IsDefaultPaymentTerm)||<a href="PaymentTermEntity.md" target="_blank">APARShared/PaymentTermEntity</a>|
|[Description](#Description)||<a href="PaymentTermEntity.md" target="_blank">APARShared/PaymentTermEntity</a>|
|[NumberOfDays](#NumberOfDays)||<a href="PaymentTermEntity.md" target="_blank">APARShared/PaymentTermEntity</a>|
|[NumberOfMonths](#NumberOfMonths)||<a href="PaymentTermEntity.md" target="_blank">APARShared/PaymentTermEntity</a>|
|[PaymentDayName](#PaymentDayName)||<a href="PaymentTermEntity.md" target="_blank">APARShared/PaymentTermEntity</a>|
|[PaymentMethodType](#PaymentMethodType)||<a href="PaymentTermEntity.md" target="_blank">APARShared/PaymentTermEntity</a>|
|[PaymentScheduleName](#PaymentScheduleName)||<a href="PaymentTermEntity.md" target="_blank">APARShared/PaymentTermEntity</a>|
|[Name](#Name)||<a href="PaymentTermEntity.md" target="_blank">APARShared/PaymentTermEntity</a>|
|[IsCertifiedCompanyCheck](#IsCertifiedCompanyCheck)||<a href="PaymentTermEntity.md" target="_blank">APARShared/PaymentTermEntity</a>|
|[VendorDueDateUpdatePolicy](#VendorDueDateUpdatePolicy)||<a href="PaymentTermEntity.md" target="_blank">APARShared/PaymentTermEntity</a>|
|[CashPaymentMainAccountIdDisplayValue](#CashPaymentMainAccountIdDisplayValue)||<a href="PaymentTermEntity.md" target="_blank">APARShared/PaymentTermEntity</a>|
|[PostOffsettingAR](#PostOffsettingAR)||<a href="PaymentTermEntity.md" target="_blank">APARShared/PaymentTermEntity</a>|
|[Relationship_CashPaymentMainAccountIdCombinationRelationshipId](#Relationship_CashPaymentMainAccountIdCombinationRelationshipId)||<a href="PaymentTermEntity.md" target="_blank">APARShared/PaymentTermEntity</a>|
|[Relationship_PaymentDayRelationshipId](#Relationship_PaymentDayRelationshipId)||<a href="PaymentTermEntity.md" target="_blank">APARShared/PaymentTermEntity</a>|
|[Relationship_PaymentScheduleRelationshipId](#Relationship_PaymentScheduleRelationshipId)||<a href="PaymentTermEntity.md" target="_blank">APARShared/PaymentTermEntity</a>|
|[BackingTable_PaymTermRelationshipId](#BackingTable_PaymTermRelationshipId)||<a href="PaymentTermEntity.md" target="_blank">APARShared/PaymentTermEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="PaymentTermEntity.md" target="_blank">APARShared/PaymentTermEntity</a>|

### <a href=#AdditionalMonthsForCutoffDate name="AdditionalMonthsForCutoffDate">AdditionalMonthsForCutoffDate</a>

First included in: APARShared/PaymentTermEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AdditionalMonthsForCutoffDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCashPayment name="IsCashPayment">IsCashPayment</a>

First included in: APARShared/PaymentTermEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCashPayment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashPaymentMainAccountId name="CashPaymentMainAccountId">CashPaymentMainAccountId</a>

First included in: APARShared/PaymentTermEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashPaymentMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditCardCreditCheckType name="CreditCardCreditCheckType">CreditCardCreditCheckType</a>

First included in: APARShared/PaymentTermEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditCardCreditCheckType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreditCardPaymentType name="CreditCardPaymentType">CreditCardPaymentType</a>

First included in: APARShared/PaymentTermEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditCardPaymentType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerDueDateUpdatePolicy name="CustomerDueDateUpdatePolicy">CustomerDueDateUpdatePolicy</a>

First included in: APARShared/PaymentTermEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerDueDateUpdatePolicy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CutoffDayOfMonth name="CutoffDayOfMonth">CutoffDayOfMonth</a>

First included in: APARShared/PaymentTermEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CutoffDayOfMonth attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDefaultPaymentTerm name="IsDefaultPaymentTerm">IsDefaultPaymentTerm</a>

First included in: APARShared/PaymentTermEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDefaultPaymentTerm attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: APARShared/PaymentTermEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberOfDays name="NumberOfDays">NumberOfDays</a>

First included in: APARShared/PaymentTermEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberOfDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberOfMonths name="NumberOfMonths">NumberOfMonths</a>

First included in: APARShared/PaymentTermEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberOfMonths attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentDayName name="PaymentDayName">PaymentDayName</a>

First included in: APARShared/PaymentTermEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentDayName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentMethodType name="PaymentMethodType">PaymentMethodType</a>

First included in: APARShared/PaymentTermEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentMethodType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentScheduleName name="PaymentScheduleName">PaymentScheduleName</a>

First included in: APARShared/PaymentTermEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentScheduleName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: APARShared/PaymentTermEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCertifiedCompanyCheck name="IsCertifiedCompanyCheck">IsCertifiedCompanyCheck</a>

First included in: APARShared/PaymentTermEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCertifiedCompanyCheck attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorDueDateUpdatePolicy name="VendorDueDateUpdatePolicy">VendorDueDateUpdatePolicy</a>

First included in: APARShared/PaymentTermEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorDueDateUpdatePolicy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashPaymentMainAccountIdDisplayValue name="CashPaymentMainAccountIdDisplayValue">CashPaymentMainAccountIdDisplayValue</a>

First included in: APARShared/PaymentTermEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashPaymentMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostOffsettingAR name="PostOffsettingAR">PostOffsettingAR</a>

First included in: APARShared/PaymentTermEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostOffsettingAR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CashPaymentMainAccountIdCombinationRelationshipId name="Relationship_CashPaymentMainAccountIdCombinationRelationshipId">Relationship_CashPaymentMainAccountIdCombinationRelationshipId</a>

First included in: APARShared/PaymentTermEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CashPaymentMainAccountIdCombinationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PaymentDayRelationshipId name="Relationship_PaymentDayRelationshipId">Relationship_PaymentDayRelationshipId</a>

First included in: APARShared/PaymentTermEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PaymentDayRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PaymentScheduleRelationshipId name="Relationship_PaymentScheduleRelationshipId">Relationship_PaymentScheduleRelationshipId</a>

First included in: APARShared/PaymentTermEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PaymentScheduleRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_PaymTermRelationshipId name="BackingTable_PaymTermRelationshipId">BackingTable_PaymTermRelationshipId</a>

First included in: APARShared/PaymentTermEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PaymTermRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Bank/Group/PaymTerm.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Group/PaymTerm.cdm.json/PaymTerm</a></td><td><a href="../../../Tables/Finance/Bank/Group/PaymTerm.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: APARShared/PaymentTermEntity (this entity)  

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
