---
title: CashDiscountEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Cash discount

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/APARShared/CashDiscountEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Cash discount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[CashDiscountCode](#CashDiscountCode)||<a href="CashDiscountEntity.md" target="_blank">APARShared/CashDiscountEntity</a>|
|[NextCashDiscountCode](#NextCashDiscountCode)||<a href="CashDiscountEntity.md" target="_blank">APARShared/CashDiscountEntity</a>|
|[Description](#Description)||<a href="CashDiscountEntity.md" target="_blank">APARShared/CashDiscountEntity</a>|
|[DiscountMethod](#DiscountMethod)||<a href="CashDiscountEntity.md" target="_blank">APARShared/CashDiscountEntity</a>|
|[OffsetMethodForVendorDiscounts](#OffsetMethodForVendorDiscounts)||<a href="CashDiscountEntity.md" target="_blank">APARShared/CashDiscountEntity</a>|
|[NumberOfDays](#NumberOfDays)||<a href="CashDiscountEntity.md" target="_blank">APARShared/CashDiscountEntity</a>|
|[NumberOfMonths](#NumberOfMonths)||<a href="CashDiscountEntity.md" target="_blank">APARShared/CashDiscountEntity</a>|
|[MainAccountIdForCustomerDiscounts](#MainAccountIdForCustomerDiscounts)||<a href="CashDiscountEntity.md" target="_blank">APARShared/CashDiscountEntity</a>|
|[Percent](#Percent)||<a href="CashDiscountEntity.md" target="_blank">APARShared/CashDiscountEntity</a>|
|[MainAccountIdForVendorDiscounts](#MainAccountIdForVendorDiscounts)||<a href="CashDiscountEntity.md" target="_blank">APARShared/CashDiscountEntity</a>|
|[MainAccountIdForCustomerDiscountsDisplayValue](#MainAccountIdForCustomerDiscountsDisplayValue)||<a href="CashDiscountEntity.md" target="_blank">APARShared/CashDiscountEntity</a>|
|[MainAccountIdForVendorDiscountsDisplayValue](#MainAccountIdForVendorDiscountsDisplayValue)||<a href="CashDiscountEntity.md" target="_blank">APARShared/CashDiscountEntity</a>|
|[DescriptionQRBill](#DescriptionQRBill)||<a href="CashDiscountEntity.md" target="_blank">APARShared/CashDiscountEntity</a>|
|[Relationship_MainAccountIdForCustomerDiscountsCombinationRelationshipId](#Relationship_MainAccountIdForCustomerDiscountsCombinationRelationshipId)||<a href="CashDiscountEntity.md" target="_blank">APARShared/CashDiscountEntity</a>|
|[Relationship_MainAccountIdForVendorDiscountsCombinationRelationshipId](#Relationship_MainAccountIdForVendorDiscountsCombinationRelationshipId)||<a href="CashDiscountEntity.md" target="_blank">APARShared/CashDiscountEntity</a>|
|[BackingTable_CashDiscRelationshipId](#BackingTable_CashDiscRelationshipId)||<a href="CashDiscountEntity.md" target="_blank">APARShared/CashDiscountEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="CashDiscountEntity.md" target="_blank">APARShared/CashDiscountEntity</a>|

### <a href=#CashDiscountCode name="CashDiscountCode">CashDiscountCode</a>

First included in: APARShared/CashDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDiscountCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NextCashDiscountCode name="NextCashDiscountCode">NextCashDiscountCode</a>

First included in: APARShared/CashDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NextCashDiscountCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: APARShared/CashDiscountEntity (this entity)  

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

### <a href=#DiscountMethod name="DiscountMethod">DiscountMethod</a>

First included in: APARShared/CashDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OffsetMethodForVendorDiscounts name="OffsetMethodForVendorDiscounts">OffsetMethodForVendorDiscounts</a>

First included in: APARShared/CashDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OffsetMethodForVendorDiscounts attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NumberOfDays name="NumberOfDays">NumberOfDays</a>

First included in: APARShared/CashDiscountEntity (this entity)  

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

First included in: APARShared/CashDiscountEntity (this entity)  

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

### <a href=#MainAccountIdForCustomerDiscounts name="MainAccountIdForCustomerDiscounts">MainAccountIdForCustomerDiscounts</a>

First included in: APARShared/CashDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainAccountIdForCustomerDiscounts attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Percent name="Percent">Percent</a>

First included in: APARShared/CashDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Percent attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MainAccountIdForVendorDiscounts name="MainAccountIdForVendorDiscounts">MainAccountIdForVendorDiscounts</a>

First included in: APARShared/CashDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainAccountIdForVendorDiscounts attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MainAccountIdForCustomerDiscountsDisplayValue name="MainAccountIdForCustomerDiscountsDisplayValue">MainAccountIdForCustomerDiscountsDisplayValue</a>

First included in: APARShared/CashDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Main account for customer discounts</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainAccountIdForCustomerDiscountsDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Main account for customer discounts</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MainAccountIdForVendorDiscountsDisplayValue name="MainAccountIdForVendorDiscountsDisplayValue">MainAccountIdForVendorDiscountsDisplayValue</a>

First included in: APARShared/CashDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Main account for vendor discounts</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainAccountIdForVendorDiscountsDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Main account for vendor discounts</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DescriptionQRBill name="DescriptionQRBill">DescriptionQRBill</a>

First included in: APARShared/CashDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DescriptionQRBill attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_MainAccountIdForCustomerDiscountsCombinationRelationshipId name="Relationship_MainAccountIdForCustomerDiscountsCombinationRelationshipId">Relationship_MainAccountIdForCustomerDiscountsCombinationRelationshipId</a>

First included in: APARShared/CashDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MainAccountIdForCustomerDiscountsCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_MainAccountIdForVendorDiscountsCombinationRelationshipId name="Relationship_MainAccountIdForVendorDiscountsCombinationRelationshipId">Relationship_MainAccountIdForVendorDiscountsCombinationRelationshipId</a>

First included in: APARShared/CashDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MainAccountIdForVendorDiscountsCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_CashDiscRelationshipId name="BackingTable_CashDiscRelationshipId">BackingTable_CashDiscRelationshipId</a>

First included in: APARShared/CashDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_CashDiscRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Bank/Group/CashDisc.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Group/CashDisc.cdm.json/CashDisc</a></td><td><a href="../../../Tables/Finance/Bank/Group/CashDisc.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: APARShared/CashDiscountEntity (this entity)  

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
