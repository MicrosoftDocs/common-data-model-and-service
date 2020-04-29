---
title: CFMPaymentRequestPaymentOrder - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# Payment order

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/RCashFlowManagement/WorksheetHeader/CFMPaymentRequestPaymentOrder.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[CFMPaymentRequestPaymentOrder/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Payment order</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="CFMPaymentRequestPaymentOrder.md" target="_blank">WorksheetHeader/CFMPaymentRequestPaymentOrder</a>|
|[BaseCode](#BaseCode)||<a href="CFMPaymentRequestPaymentOrder.md" target="_blank">WorksheetHeader/CFMPaymentRequestPaymentOrder</a>|
|[BudgetReceiptClassCode](#BudgetReceiptClassCode)||<a href="CFMPaymentRequestPaymentOrder.md" target="_blank">WorksheetHeader/CFMPaymentRequestPaymentOrder</a>|
|[DocDate](#DocDate)||<a href="CFMPaymentRequestPaymentOrder.md" target="_blank">WorksheetHeader/CFMPaymentRequestPaymentOrder</a>|
|[DocNum](#DocNum)||<a href="CFMPaymentRequestPaymentOrder.md" target="_blank">WorksheetHeader/CFMPaymentRequestPaymentOrder</a>|
|[OrderOfPayment](#OrderOfPayment)||<a href="CFMPaymentRequestPaymentOrder.md" target="_blank">WorksheetHeader/CFMPaymentRequestPaymentOrder</a>|
|[PeriodCode](#PeriodCode)||<a href="CFMPaymentRequestPaymentOrder.md" target="_blank">WorksheetHeader/CFMPaymentRequestPaymentOrder</a>|
|[PeriodNumber](#PeriodNumber)||<a href="CFMPaymentRequestPaymentOrder.md" target="_blank">WorksheetHeader/CFMPaymentRequestPaymentOrder</a>|
|[PrintKPP](#PrintKPP)||<a href="CFMPaymentRequestPaymentOrder.md" target="_blank">WorksheetHeader/CFMPaymentRequestPaymentOrder</a>|
|[RecipientRCOAD](#RecipientRCOAD)||<a href="CFMPaymentRequestPaymentOrder.md" target="_blank">WorksheetHeader/CFMPaymentRequestPaymentOrder</a>|
|[RequisitesDataAreaId](#RequisitesDataAreaId)||<a href="CFMPaymentRequestPaymentOrder.md" target="_blank">WorksheetHeader/CFMPaymentRequestPaymentOrder</a>|
|[StatusCode](#StatusCode)||<a href="CFMPaymentRequestPaymentOrder.md" target="_blank">WorksheetHeader/CFMPaymentRequestPaymentOrder</a>|
|[TaxPeriodDate](#TaxPeriodDate)||<a href="CFMPaymentRequestPaymentOrder.md" target="_blank">WorksheetHeader/CFMPaymentRequestPaymentOrder</a>|
|[TypeCode](#TypeCode)||<a href="CFMPaymentRequestPaymentOrder.md" target="_blank">WorksheetHeader/CFMPaymentRequestPaymentOrder</a>|
|[UIN](#UIN)||<a href="CFMPaymentRequestPaymentOrder.md" target="_blank">WorksheetHeader/CFMPaymentRequestPaymentOrder</a>|
|[year](#year)||<a href="CFMPaymentRequestPaymentOrder.md" target="_blank">WorksheetHeader/CFMPaymentRequestPaymentOrder</a>|
|[Hash](#Hash)||<a href="CFMPaymentRequestPaymentOrder.md" target="_blank">WorksheetHeader/CFMPaymentRequestPaymentOrder</a>|
|[Relationship_PaymentOrderBudgetReceiptClassTable_RURelationshipId](#Relationship_PaymentOrderBudgetReceiptClassTable_RURelationshipId)||<a href="CFMPaymentRequestPaymentOrder.md" target="_blank">WorksheetHeader/CFMPaymentRequestPaymentOrder</a>|
|[Relationship_PaymentOrderPaymBaseCodeTable_RURelationshipId](#Relationship_PaymentOrderPaymBaseCodeTable_RURelationshipId)||<a href="CFMPaymentRequestPaymentOrder.md" target="_blank">WorksheetHeader/CFMPaymentRequestPaymentOrder</a>|
|[Relationship_PaymentOrderStatusTable_RURelationshipId](#Relationship_PaymentOrderStatusTable_RURelationshipId)||<a href="CFMPaymentRequestPaymentOrder.md" target="_blank">WorksheetHeader/CFMPaymentRequestPaymentOrder</a>|
|[Relationship_PaymentOrderTypeTable_RURelationshipId](#Relationship_PaymentOrderTypeTable_RURelationshipId)||<a href="CFMPaymentRequestPaymentOrder.md" target="_blank">WorksheetHeader/CFMPaymentRequestPaymentOrder</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetHeader/CFMPaymentRequestPaymentOrder (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[CFMPaymentRequestPaymentOrder/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BaseCode name="BaseCode">BaseCode</a>

First included in: WorksheetHeader/CFMPaymentRequestPaymentOrder (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BaseCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BudgetReceiptClassCode name="BudgetReceiptClassCode">BudgetReceiptClassCode</a>

First included in: WorksheetHeader/CFMPaymentRequestPaymentOrder (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetReceiptClassCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DocDate name="DocDate">DocDate</a>

First included in: WorksheetHeader/CFMPaymentRequestPaymentOrder (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#DocNum name="DocNum">DocNum</a>

First included in: WorksheetHeader/CFMPaymentRequestPaymentOrder (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DocNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrderOfPayment name="OrderOfPayment">OrderOfPayment</a>

First included in: WorksheetHeader/CFMPaymentRequestPaymentOrder (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderOfPayment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PeriodCode name="PeriodCode">PeriodCode</a>

First included in: WorksheetHeader/CFMPaymentRequestPaymentOrder (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodCode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PeriodNumber name="PeriodNumber">PeriodNumber</a>

First included in: WorksheetHeader/CFMPaymentRequestPaymentOrder (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PrintKPP name="PrintKPP">PrintKPP</a>

First included in: WorksheetHeader/CFMPaymentRequestPaymentOrder (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>RRC printing</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintKPP attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>RRC printing</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#RecipientRCOAD name="RecipientRCOAD">RecipientRCOAD</a>

First included in: WorksheetHeader/CFMPaymentRequestPaymentOrder (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>RCOAD</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecipientRCOAD attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>RCOAD</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#RequisitesDataAreaId name="RequisitesDataAreaId">RequisitesDataAreaId</a>

First included in: WorksheetHeader/CFMPaymentRequestPaymentOrder (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequisitesDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StatusCode name="StatusCode">StatusCode</a>

First included in: WorksheetHeader/CFMPaymentRequestPaymentOrder (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StatusCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxPeriodDate name="TaxPeriodDate">TaxPeriodDate</a>

First included in: WorksheetHeader/CFMPaymentRequestPaymentOrder (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxPeriodDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#TypeCode name="TypeCode">TypeCode</a>

First included in: WorksheetHeader/CFMPaymentRequestPaymentOrder (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TypeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UIN name="UIN">UIN</a>

First included in: WorksheetHeader/CFMPaymentRequestPaymentOrder (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UIN attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#year name="year">year</a>

First included in: WorksheetHeader/CFMPaymentRequestPaymentOrder (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the year attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Hash name="Hash">Hash</a>

First included in: WorksheetHeader/CFMPaymentRequestPaymentOrder (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Hash attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PaymentOrderBudgetReceiptClassTable_RURelationshipId name="Relationship_PaymentOrderBudgetReceiptClassTable_RURelationshipId">Relationship_PaymentOrderBudgetReceiptClassTable_RURelationshipId</a>

First included in: WorksheetHeader/CFMPaymentRequestPaymentOrder (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PaymentOrderBudgetReceiptClassTable_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Bank/Main/PaymentOrderBudgetReceiptClassTable_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Main/PaymentOrderBudgetReceiptClassTable_RU.cdm.json/PaymentOrderBudgetReceiptClassTable_RU</a></td><td><a href="../../Bank/Main/PaymentOrderBudgetReceiptClassTable_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PaymentOrderPaymBaseCodeTable_RURelationshipId name="Relationship_PaymentOrderPaymBaseCodeTable_RURelationshipId">Relationship_PaymentOrderPaymBaseCodeTable_RURelationshipId</a>

First included in: WorksheetHeader/CFMPaymentRequestPaymentOrder (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PaymentOrderPaymBaseCodeTable_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Bank/Main/PaymentOrderPaymBaseCodeTable_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Main/PaymentOrderPaymBaseCodeTable_RU.cdm.json/PaymentOrderPaymBaseCodeTable_RU</a></td><td><a href="../../Bank/Main/PaymentOrderPaymBaseCodeTable_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PaymentOrderStatusTable_RURelationshipId name="Relationship_PaymentOrderStatusTable_RURelationshipId">Relationship_PaymentOrderStatusTable_RURelationshipId</a>

First included in: WorksheetHeader/CFMPaymentRequestPaymentOrder (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PaymentOrderStatusTable_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Bank/Main/PaymentOrderStatusTable_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Main/PaymentOrderStatusTable_RU.cdm.json/PaymentOrderStatusTable_RU</a></td><td><a href="../../Bank/Main/PaymentOrderStatusTable_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PaymentOrderTypeTable_RURelationshipId name="Relationship_PaymentOrderTypeTable_RURelationshipId">Relationship_PaymentOrderTypeTable_RURelationshipId</a>

First included in: WorksheetHeader/CFMPaymentRequestPaymentOrder (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PaymentOrderTypeTable_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Bank/Main/PaymentOrderTypeTable_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Main/PaymentOrderTypeTable_RU.cdm.json/PaymentOrderTypeTable_RU</a></td><td><a href="../../Bank/Main/PaymentOrderTypeTable_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
