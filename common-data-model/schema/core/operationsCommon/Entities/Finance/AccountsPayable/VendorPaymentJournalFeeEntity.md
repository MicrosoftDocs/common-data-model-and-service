---
title: VendorPaymentJournalFeeEntity in AccountsPayable - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Vendor payment journal fee in AccountsPayable(VendorPaymentJournalFeeEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/AccountsPayable/VendorPaymentJournalFeeEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Vendor payment journal fee</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[SourceJournalLineRefRecId](#SourceJournalLineRefRecId)||<a href="VendorPaymentJournalFeeEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalFeeEntity</a>|
|[DefaultDimension](#DefaultDimension)||<a href="VendorPaymentJournalFeeEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalFeeEntity</a>|
|[CurrencyCode](#CurrencyCode)||<a href="VendorPaymentJournalFeeEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalFeeEntity</a>|
|[PaymentFeeId](#PaymentFeeId)||<a href="VendorPaymentJournalFeeEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalFeeEntity</a>|
|[Amount](#Amount)||<a href="VendorPaymentJournalFeeEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalFeeEntity</a>|
|[Account](#Account)||<a href="VendorPaymentJournalFeeEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalFeeEntity</a>|
|[AccountType](#AccountType)||<a href="VendorPaymentJournalFeeEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalFeeEntity</a>|
|[SalesTaxDirection](#SalesTaxDirection)||<a href="VendorPaymentJournalFeeEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalFeeEntity</a>|
|[SalesTaxGroup](#SalesTaxGroup)||<a href="VendorPaymentJournalFeeEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalFeeEntity</a>|
|[ItemSalesTaxGroup](#ItemSalesTaxGroup)||<a href="VendorPaymentJournalFeeEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalFeeEntity</a>|
|[DefaultDimensionDisplayValue](#DefaultDimensionDisplayValue)||<a href="VendorPaymentJournalFeeEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalFeeEntity</a>|
|[AccountDisplayValue](#AccountDisplayValue)||<a href="VendorPaymentJournalFeeEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalFeeEntity</a>|
|[SourceJournalLineNumber](#SourceJournalLineNumber)||<a href="VendorPaymentJournalFeeEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalFeeEntity</a>|
|[SourceJournalBatchNumber](#SourceJournalBatchNumber)||<a href="VendorPaymentJournalFeeEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalFeeEntity</a>|
|[ItemWithholdingTaxGroupCode](#ItemWithholdingTaxGroupCode)||<a href="VendorPaymentJournalFeeEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalFeeEntity</a>|
|[IsPaymFeeCoveredByVendor](#IsPaymFeeCoveredByVendor)||<a href="VendorPaymentJournalFeeEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalFeeEntity</a>|
|[Relationship_DefaultDimensionDimensionSetRelationshipId](#Relationship_DefaultDimensionDimensionSetRelationshipId)||<a href="VendorPaymentJournalFeeEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalFeeEntity</a>|
|[Relationship_AccountCombinationRelationshipId](#Relationship_AccountCombinationRelationshipId)||<a href="VendorPaymentJournalFeeEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalFeeEntity</a>|
|[Relationship_SourceVendorPaymentJournalLineRelationshipId](#Relationship_SourceVendorPaymentJournalLineRelationshipId)||<a href="VendorPaymentJournalFeeEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalFeeEntity</a>|
|[Relationship_CurrencyCodeRelationshipId](#Relationship_CurrencyCodeRelationshipId)||<a href="VendorPaymentJournalFeeEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalFeeEntity</a>|
|[Relationship_SalesTaxGroupRelationshipId](#Relationship_SalesTaxGroupRelationshipId)||<a href="VendorPaymentJournalFeeEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalFeeEntity</a>|
|[Relationship_ItemSalesTaxGroupRelationshipId](#Relationship_ItemSalesTaxGroupRelationshipId)||<a href="VendorPaymentJournalFeeEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalFeeEntity</a>|
|[Relationship_PaymentFeeRelationshipId](#Relationship_PaymentFeeRelationshipId)||<a href="VendorPaymentJournalFeeEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalFeeEntity</a>|
|[BackingTable_CustVendPaymJournalFeeRelationshipId](#BackingTable_CustVendPaymJournalFeeRelationshipId)||<a href="VendorPaymentJournalFeeEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalFeeEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="VendorPaymentJournalFeeEntity.md" target="_blank">AccountsPayable/VendorPaymentJournalFeeEntity</a>|

### <a href=#SourceJournalLineRefRecId name="SourceJournalLineRefRecId">SourceJournalLineRefRecId</a>

First included in: AccountsPayable/VendorPaymentJournalFeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceJournalLineRefRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimension name="DefaultDimension">DefaultDimension</a>

First included in: AccountsPayable/VendorPaymentJournalFeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: AccountsPayable/VendorPaymentJournalFeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentFeeId name="PaymentFeeId">PaymentFeeId</a>

First included in: AccountsPayable/VendorPaymentJournalFeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentFeeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Amount name="Amount">Amount</a>

First included in: AccountsPayable/VendorPaymentJournalFeeEntity (this entity)  

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

### <a href=#Account name="Account">Account</a>

First included in: AccountsPayable/VendorPaymentJournalFeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Account attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountType name="AccountType">AccountType</a>

First included in: AccountsPayable/VendorPaymentJournalFeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxDirection name="SalesTaxDirection">SalesTaxDirection</a>

First included in: AccountsPayable/VendorPaymentJournalFeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxDirection attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxGroup name="SalesTaxGroup">SalesTaxGroup</a>

First included in: AccountsPayable/VendorPaymentJournalFeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemSalesTaxGroup name="ItemSalesTaxGroup">ItemSalesTaxGroup</a>

First included in: AccountsPayable/VendorPaymentJournalFeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemSalesTaxGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimensionDisplayValue name="DefaultDimensionDisplayValue">DefaultDimensionDisplayValue</a>

First included in: AccountsPayable/VendorPaymentJournalFeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountDisplayValue name="AccountDisplayValue">AccountDisplayValue</a>

First included in: AccountsPayable/VendorPaymentJournalFeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SourceJournalLineNumber name="SourceJournalLineNumber">SourceJournalLineNumber</a>

First included in: AccountsPayable/VendorPaymentJournalFeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceJournalLineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SourceJournalBatchNumber name="SourceJournalBatchNumber">SourceJournalBatchNumber</a>

First included in: AccountsPayable/VendorPaymentJournalFeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceJournalBatchNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemWithholdingTaxGroupCode name="ItemWithholdingTaxGroupCode">ItemWithholdingTaxGroupCode</a>

First included in: AccountsPayable/VendorPaymentJournalFeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemWithholdingTaxGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPaymFeeCoveredByVendor name="IsPaymFeeCoveredByVendor">IsPaymFeeCoveredByVendor</a>

First included in: AccountsPayable/VendorPaymentJournalFeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPaymFeeCoveredByVendor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultDimensionDimensionSetRelationshipId name="Relationship_DefaultDimensionDimensionSetRelationshipId">Relationship_DefaultDimensionDimensionSetRelationshipId</a>

First included in: AccountsPayable/VendorPaymentJournalFeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultDimensionDimensionSetRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_AccountCombinationRelationshipId name="Relationship_AccountCombinationRelationshipId">Relationship_AccountCombinationRelationshipId</a>

First included in: AccountsPayable/VendorPaymentJournalFeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AccountCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_SourceVendorPaymentJournalLineRelationshipId name="Relationship_SourceVendorPaymentJournalLineRelationshipId">Relationship_SourceVendorPaymentJournalLineRelationshipId</a>

First included in: AccountsPayable/VendorPaymentJournalFeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SourceVendorPaymentJournalLineRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_CurrencyCodeRelationshipId name="Relationship_CurrencyCodeRelationshipId">Relationship_CurrencyCodeRelationshipId</a>

First included in: AccountsPayable/VendorPaymentJournalFeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CurrencyCodeRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_SalesTaxGroupRelationshipId name="Relationship_SalesTaxGroupRelationshipId">Relationship_SalesTaxGroupRelationshipId</a>

First included in: AccountsPayable/VendorPaymentJournalFeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SalesTaxGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ItemSalesTaxGroupRelationshipId name="Relationship_ItemSalesTaxGroupRelationshipId">Relationship_ItemSalesTaxGroupRelationshipId</a>

First included in: AccountsPayable/VendorPaymentJournalFeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ItemSalesTaxGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PaymentFeeRelationshipId name="Relationship_PaymentFeeRelationshipId">Relationship_PaymentFeeRelationshipId</a>

First included in: AccountsPayable/VendorPaymentJournalFeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PaymentFeeRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_CustVendPaymJournalFeeRelationshipId name="BackingTable_CustVendPaymJournalFeeRelationshipId">BackingTable_CustVendPaymJournalFeeRelationshipId</a>

First included in: AccountsPayable/VendorPaymentJournalFeeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_CustVendPaymJournalFeeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Bank/WorksheetLine/CustVendPaymJournalFee.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/WorksheetLine/CustVendPaymJournalFee.cdm.json/CustVendPaymJournalFee</a></td><td><a href="../../../Tables/Finance/Bank/WorksheetLine/CustVendPaymJournalFee.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: AccountsPayable/VendorPaymentJournalFeeEntity (this entity)  

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
