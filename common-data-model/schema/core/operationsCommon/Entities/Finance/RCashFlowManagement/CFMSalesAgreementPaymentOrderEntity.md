---
title: CFMSalesAgreementPaymentOrderEntity in RCashFlowManagement - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/20/2020
ms.author: nebanfic
---

# Payment order requisites for sales agreements in RCashFlowManagement(CFMSalesAgreementPaymentOrderEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/RCashFlowManagement/CFMSalesAgreementPaymentOrderEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Payment order requisites for sales agreements</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[PurposeText](#PurposeText)||<a href="CFMSalesAgreementPaymentOrderEntity.md" target="_blank">RCashFlowManagement/CFMSalesAgreementPaymentOrderEntity</a>|
|[OriginPayment](#OriginPayment)||<a href="CFMSalesAgreementPaymentOrderEntity.md" target="_blank">RCashFlowManagement/CFMSalesAgreementPaymentOrderEntity</a>|
|[BudgetRevenueCode](#BudgetRevenueCode)||<a href="CFMSalesAgreementPaymentOrderEntity.md" target="_blank">RCashFlowManagement/CFMSalesAgreementPaymentOrderEntity</a>|
|[DocumentDate](#DocumentDate)||<a href="CFMSalesAgreementPaymentOrderEntity.md" target="_blank">RCashFlowManagement/CFMSalesAgreementPaymentOrderEntity</a>|
|[DocumentNumber](#DocumentNumber)||<a href="CFMSalesAgreementPaymentOrderEntity.md" target="_blank">RCashFlowManagement/CFMSalesAgreementPaymentOrderEntity</a>|
|[OrderOfPayment](#OrderOfPayment)||<a href="CFMSalesAgreementPaymentOrderEntity.md" target="_blank">RCashFlowManagement/CFMSalesAgreementPaymentOrderEntity</a>|
|[PeriodCode](#PeriodCode)||<a href="CFMSalesAgreementPaymentOrderEntity.md" target="_blank">RCashFlowManagement/CFMSalesAgreementPaymentOrderEntity</a>|
|[PeriodNumber](#PeriodNumber)||<a href="CFMSalesAgreementPaymentOrderEntity.md" target="_blank">RCashFlowManagement/CFMSalesAgreementPaymentOrderEntity</a>|
|[RRCPrinting](#RRCPrinting)||<a href="CFMSalesAgreementPaymentOrderEntity.md" target="_blank">RCashFlowManagement/CFMSalesAgreementPaymentOrderEntity</a>|
|[RCOAD](#RCOAD)||<a href="CFMSalesAgreementPaymentOrderEntity.md" target="_blank">RCashFlowManagement/CFMSalesAgreementPaymentOrderEntity</a>|
|[NumberStatus](#NumberStatus)||<a href="CFMSalesAgreementPaymentOrderEntity.md" target="_blank">RCashFlowManagement/CFMSalesAgreementPaymentOrderEntity</a>|
|[PeriodDate](#PeriodDate)||<a href="CFMSalesAgreementPaymentOrderEntity.md" target="_blank">RCashFlowManagement/CFMSalesAgreementPaymentOrderEntity</a>|
|[PaymentType](#PaymentType)||<a href="CFMSalesAgreementPaymentOrderEntity.md" target="_blank">RCashFlowManagement/CFMSalesAgreementPaymentOrderEntity</a>|
|[UCI](#UCI)||<a href="CFMSalesAgreementPaymentOrderEntity.md" target="_blank">RCashFlowManagement/CFMSalesAgreementPaymentOrderEntity</a>|
|[SalesAgreement](#SalesAgreement)||<a href="CFMSalesAgreementPaymentOrderEntity.md" target="_blank">RCashFlowManagement/CFMSalesAgreementPaymentOrderEntity</a>|
|[LegalEntity](#LegalEntity)||<a href="CFMSalesAgreementPaymentOrderEntity.md" target="_blank">RCashFlowManagement/CFMSalesAgreementPaymentOrderEntity</a>|
|[BackingTable_CFMAgreementPaymentOrderRelationshipId](#BackingTable_CFMAgreementPaymentOrderRelationshipId)||<a href="CFMSalesAgreementPaymentOrderEntity.md" target="_blank">RCashFlowManagement/CFMSalesAgreementPaymentOrderEntity</a>|

### <a href=#PurposeText name="PurposeText">PurposeText</a>

First included in: RCashFlowManagement/CFMSalesAgreementPaymentOrderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurposeText attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OriginPayment name="OriginPayment">OriginPayment</a>

First included in: RCashFlowManagement/CFMSalesAgreementPaymentOrderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginPayment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BudgetRevenueCode name="BudgetRevenueCode">BudgetRevenueCode</a>

First included in: RCashFlowManagement/CFMSalesAgreementPaymentOrderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetRevenueCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentDate name="DocumentDate">DocumentDate</a>

First included in: RCashFlowManagement/CFMSalesAgreementPaymentOrderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocumentNumber name="DocumentNumber">DocumentNumber</a>

First included in: RCashFlowManagement/CFMSalesAgreementPaymentOrderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocumentNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrderOfPayment name="OrderOfPayment">OrderOfPayment</a>

First included in: RCashFlowManagement/CFMSalesAgreementPaymentOrderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderOfPayment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PeriodCode name="PeriodCode">PeriodCode</a>

First included in: RCashFlowManagement/CFMSalesAgreementPaymentOrderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PeriodNumber name="PeriodNumber">PeriodNumber</a>

First included in: RCashFlowManagement/CFMSalesAgreementPaymentOrderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RRCPrinting name="RRCPrinting">RRCPrinting</a>

First included in: RCashFlowManagement/CFMSalesAgreementPaymentOrderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RRCPrinting attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RCOAD name="RCOAD">RCOAD</a>

First included in: RCashFlowManagement/CFMSalesAgreementPaymentOrderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RCOAD attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberStatus name="NumberStatus">NumberStatus</a>

First included in: RCashFlowManagement/CFMSalesAgreementPaymentOrderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NumberStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PeriodDate name="PeriodDate">PeriodDate</a>

First included in: RCashFlowManagement/CFMSalesAgreementPaymentOrderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentType name="PaymentType">PaymentType</a>

First included in: RCashFlowManagement/CFMSalesAgreementPaymentOrderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UCI name="UCI">UCI</a>

First included in: RCashFlowManagement/CFMSalesAgreementPaymentOrderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UCI attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesAgreement name="SalesAgreement">SalesAgreement</a>

First included in: RCashFlowManagement/CFMSalesAgreementPaymentOrderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesAgreement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LegalEntity name="LegalEntity">LegalEntity</a>

First included in: RCashFlowManagement/CFMSalesAgreementPaymentOrderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LegalEntity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_CFMAgreementPaymentOrderRelationshipId name="BackingTable_CFMAgreementPaymentOrderRelationshipId">BackingTable_CFMAgreementPaymentOrderRelationshipId</a>

First included in: RCashFlowManagement/CFMSalesAgreementPaymentOrderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_CFMAgreementPaymentOrderRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/RCashFlowManagement/WorksheetHeader/CFMAgreementPaymentOrder.md" target="_blank">/core/operationsCommon/Tables/Finance/RCashFlowManagement/WorksheetHeader/CFMAgreementPaymentOrder.cdm.json/CFMAgreementPaymentOrder</a></td><td><a href="../../../Tables/Finance/RCashFlowManagement/WorksheetHeader/CFMAgreementPaymentOrder.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
