---
title: RetailTransactionDiscountLineEntity in TransactionsAndOrders - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Discount transactions in TransactionsAndOrders(RetailTransactionDiscountLineEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Commerce/TransactionsAndOrders/RetailTransactionDiscountLineEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Discount transactions</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[EffectiveAmount](#EffectiveAmount)||<a href="RetailTransactionDiscountLineEntity.md" target="_blank">TransactionsAndOrders/RetailTransactionDiscountLineEntity</a>|
|[Channel](#Channel)||<a href="RetailTransactionDiscountLineEntity.md" target="_blank">TransactionsAndOrders/RetailTransactionDiscountLineEntity</a>|
|[CustomerDiscountType](#CustomerDiscountType)||<a href="RetailTransactionDiscountLineEntity.md" target="_blank">TransactionsAndOrders/RetailTransactionDiscountLineEntity</a>|
|[DealPrice](#DealPrice)||<a href="RetailTransactionDiscountLineEntity.md" target="_blank">TransactionsAndOrders/RetailTransactionDiscountLineEntity</a>|
|[DiscountAmount](#DiscountAmount)||<a href="RetailTransactionDiscountLineEntity.md" target="_blank">TransactionsAndOrders/RetailTransactionDiscountLineEntity</a>|
|[DiscountCode](#DiscountCode)||<a href="RetailTransactionDiscountLineEntity.md" target="_blank">TransactionsAndOrders/RetailTransactionDiscountLineEntity</a>|
|[DiscountOriginType](#DiscountOriginType)||<a href="RetailTransactionDiscountLineEntity.md" target="_blank">TransactionsAndOrders/RetailTransactionDiscountLineEntity</a>|
|[LineNumber](#LineNumber)||<a href="RetailTransactionDiscountLineEntity.md" target="_blank">TransactionsAndOrders/RetailTransactionDiscountLineEntity</a>|
|[ManualDiscountType](#ManualDiscountType)||<a href="RetailTransactionDiscountLineEntity.md" target="_blank">TransactionsAndOrders/RetailTransactionDiscountLineEntity</a>|
|[DiscountPercentage](#DiscountPercentage)||<a href="RetailTransactionDiscountLineEntity.md" target="_blank">TransactionsAndOrders/RetailTransactionDiscountLineEntity</a>|
|[DiscountOfferId](#DiscountOfferId)||<a href="RetailTransactionDiscountLineEntity.md" target="_blank">TransactionsAndOrders/RetailTransactionDiscountLineEntity</a>|
|[SalesLineNumber](#SalesLineNumber)||<a href="RetailTransactionDiscountLineEntity.md" target="_blank">TransactionsAndOrders/RetailTransactionDiscountLineEntity</a>|
|[BundleId](#BundleId)||<a href="RetailTransactionDiscountLineEntity.md" target="_blank">TransactionsAndOrders/RetailTransactionDiscountLineEntity</a>|
|[Terminal](#Terminal)||<a href="RetailTransactionDiscountLineEntity.md" target="_blank">TransactionsAndOrders/RetailTransactionDiscountLineEntity</a>|
|[TransactionNumber](#TransactionNumber)||<a href="RetailTransactionDiscountLineEntity.md" target="_blank">TransactionsAndOrders/RetailTransactionDiscountLineEntity</a>|
|[RetailChannelTableOMOperatingUnitID](#RetailChannelTableOMOperatingUnitID)||<a href="RetailTransactionDiscountLineEntity.md" target="_blank">TransactionsAndOrders/RetailTransactionDiscountLineEntity</a>|
|[OperatingUnitNumber](#OperatingUnitNumber)||<a href="RetailTransactionDiscountLineEntity.md" target="_blank">TransactionsAndOrders/RetailTransactionDiscountLineEntity</a>|
|[BackingTable_RetailTransactionDiscountTransRelationshipId](#BackingTable_RetailTransactionDiscountTransRelationshipId)||<a href="RetailTransactionDiscountLineEntity.md" target="_blank">TransactionsAndOrders/RetailTransactionDiscountLineEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="RetailTransactionDiscountLineEntity.md" target="_blank">TransactionsAndOrders/RetailTransactionDiscountLineEntity</a>|

### <a href=#EffectiveAmount name="EffectiveAmount">EffectiveAmount</a>

First included in: TransactionsAndOrders/RetailTransactionDiscountLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EffectiveAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Channel name="Channel">Channel</a>

First included in: TransactionsAndOrders/RetailTransactionDiscountLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Channel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerDiscountType name="CustomerDiscountType">CustomerDiscountType</a>

First included in: TransactionsAndOrders/RetailTransactionDiscountLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerDiscountType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DealPrice name="DealPrice">DealPrice</a>

First included in: TransactionsAndOrders/RetailTransactionDiscountLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DealPrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscountAmount name="DiscountAmount">DiscountAmount</a>

First included in: TransactionsAndOrders/RetailTransactionDiscountLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscountCode name="DiscountCode">DiscountCode</a>

First included in: TransactionsAndOrders/RetailTransactionDiscountLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscountOriginType name="DiscountOriginType">DiscountOriginType</a>

First included in: TransactionsAndOrders/RetailTransactionDiscountLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountOriginType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: TransactionsAndOrders/RetailTransactionDiscountLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ManualDiscountType name="ManualDiscountType">ManualDiscountType</a>

First included in: TransactionsAndOrders/RetailTransactionDiscountLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ManualDiscountType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscountPercentage name="DiscountPercentage">DiscountPercentage</a>

First included in: TransactionsAndOrders/RetailTransactionDiscountLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscountOfferId name="DiscountOfferId">DiscountOfferId</a>

First included in: TransactionsAndOrders/RetailTransactionDiscountLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountOfferId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesLineNumber name="SalesLineNumber">SalesLineNumber</a>

First included in: TransactionsAndOrders/RetailTransactionDiscountLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesLineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BundleId name="BundleId">BundleId</a>

First included in: TransactionsAndOrders/RetailTransactionDiscountLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BundleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Terminal name="Terminal">Terminal</a>

First included in: TransactionsAndOrders/RetailTransactionDiscountLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Terminal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionNumber name="TransactionNumber">TransactionNumber</a>

First included in: TransactionsAndOrders/RetailTransactionDiscountLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailChannelTableOMOperatingUnitID name="RetailChannelTableOMOperatingUnitID">RetailChannelTableOMOperatingUnitID</a>

First included in: TransactionsAndOrders/RetailTransactionDiscountLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailChannelTableOMOperatingUnitID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperatingUnitNumber name="OperatingUnitNumber">OperatingUnitNumber</a>

First included in: TransactionsAndOrders/RetailTransactionDiscountLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperatingUnitNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_RetailTransactionDiscountTransRelationshipId name="BackingTable_RetailTransactionDiscountTransRelationshipId">BackingTable_RetailTransactionDiscountTransRelationshipId</a>

First included in: TransactionsAndOrders/RetailTransactionDiscountLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailTransactionDiscountTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Commerce/TransactionsAndOrders/Transaction/RetailTransactionDiscountTrans.md" target="_blank">/core/operationsCommon/Tables/Commerce/TransactionsAndOrders/Transaction/RetailTransactionDiscountTrans.cdm.json/RetailTransactionDiscountTrans</a></td><td><a href="../../../Tables/Commerce/TransactionsAndOrders/Transaction/RetailTransactionDiscountTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: TransactionsAndOrders/RetailTransactionDiscountLineEntity (this entity)  

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
