---
title: PurchOpenPurchaseTotalDiscountJournalLineEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Open purchase total discount journal lines

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/PurchOpenPurchaseTotalDiscountJournalLineEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Open purchase total discount journal lines</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[TradeAgreementJournalNumber](#TradeAgreementJournalNumber)||<a href="PurchOpenPurchaseTotalDiscountJournalLineEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchaseTotalDiscountJournalLineEntity</a>|
|[LineNumber](#LineNumber)||<a href="PurchOpenPurchaseTotalDiscountJournalLineEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchaseTotalDiscountJournalLineEntity</a>|
|[TotalDiscountVendorGroupCode](#TotalDiscountVendorGroupCode)||<a href="PurchOpenPurchaseTotalDiscountJournalLineEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchaseTotalDiscountJournalLineEntity</a>|
|[VendorAccountNumber](#VendorAccountNumber)||<a href="PurchOpenPurchaseTotalDiscountJournalLineEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchaseTotalDiscountJournalLineEntity</a>|
|[FromOrderSubtotalAmount](#FromOrderSubtotalAmount)||<a href="PurchOpenPurchaseTotalDiscountJournalLineEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchaseTotalDiscountJournalLineEntity</a>|
|[ToOrderSubtotalAmount](#ToOrderSubtotalAmount)||<a href="PurchOpenPurchaseTotalDiscountJournalLineEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchaseTotalDiscountJournalLineEntity</a>|
|[DiscountApplicableFromDate](#DiscountApplicableFromDate)||<a href="PurchOpenPurchaseTotalDiscountJournalLineEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchaseTotalDiscountJournalLineEntity</a>|
|[DiscountApplicableToDate](#DiscountApplicableToDate)||<a href="PurchOpenPurchaseTotalDiscountJournalLineEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchaseTotalDiscountJournalLineEntity</a>|
|[DiscountAmount](#DiscountAmount)||<a href="PurchOpenPurchaseTotalDiscountJournalLineEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchaseTotalDiscountJournalLineEntity</a>|
|[DiscountCurrencyCode](#DiscountCurrencyCode)||<a href="PurchOpenPurchaseTotalDiscountJournalLineEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchaseTotalDiscountJournalLineEntity</a>|
|[DiscountPercentage1](#DiscountPercentage1)||<a href="PurchOpenPurchaseTotalDiscountJournalLineEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchaseTotalDiscountJournalLineEntity</a>|
|[DiscountPercentage2](#DiscountPercentage2)||<a href="PurchOpenPurchaseTotalDiscountJournalLineEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchaseTotalDiscountJournalLineEntity</a>|
|[WillSearchContinue](#WillSearchContinue)||<a href="PurchOpenPurchaseTotalDiscountJournalLineEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchaseTotalDiscountJournalLineEntity</a>|
|[ProcessingLog](#ProcessingLog)||<a href="PurchOpenPurchaseTotalDiscountJournalLineEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchaseTotalDiscountJournalLineEntity</a>|
|[AccountRelation](#AccountRelation)||<a href="PurchOpenPurchaseTotalDiscountJournalLineEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchaseTotalDiscountJournalLineEntity</a>|
|[AccountCode](#AccountCode)||<a href="PurchOpenPurchaseTotalDiscountJournalLineEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchaseTotalDiscountJournalLineEntity</a>|
|[ItemCode](#ItemCode)||<a href="PurchOpenPurchaseTotalDiscountJournalLineEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchaseTotalDiscountJournalLineEntity</a>|
|[ItemRelation](#ItemRelation)||<a href="PurchOpenPurchaseTotalDiscountJournalLineEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchaseTotalDiscountJournalLineEntity</a>|
|[JournalNum](#JournalNum)||<a href="PurchOpenPurchaseTotalDiscountJournalLineEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchaseTotalDiscountJournalLineEntity</a>|
|[Relationship_TotalDiscountVendorGroupRelationshipId](#Relationship_TotalDiscountVendorGroupRelationshipId)||<a href="PurchOpenPurchaseTotalDiscountJournalLineEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchaseTotalDiscountJournalLineEntity</a>|
|[Relationship_VendTableRelationshipId](#Relationship_VendTableRelationshipId)||<a href="PurchOpenPurchaseTotalDiscountJournalLineEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchaseTotalDiscountJournalLineEntity</a>|
|[BackingTable_PriceDiscAdmTransRelationshipId](#BackingTable_PriceDiscAdmTransRelationshipId)||<a href="PurchOpenPurchaseTotalDiscountJournalLineEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchaseTotalDiscountJournalLineEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="PurchOpenPurchaseTotalDiscountJournalLineEntity.md" target="_blank">ProcurementAndSourcing/PurchOpenPurchaseTotalDiscountJournalLineEntity</a>|

### <a href=#TradeAgreementJournalNumber name="TradeAgreementJournalNumber">TradeAgreementJournalNumber</a>

First included in: ProcurementAndSourcing/PurchOpenPurchaseTotalDiscountJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TradeAgreementJournalNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: ProcurementAndSourcing/PurchOpenPurchaseTotalDiscountJournalLineEntity (this entity)  

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

### <a href=#TotalDiscountVendorGroupCode name="TotalDiscountVendorGroupCode">TotalDiscountVendorGroupCode</a>

First included in: ProcurementAndSourcing/PurchOpenPurchaseTotalDiscountJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalDiscountVendorGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorAccountNumber name="VendorAccountNumber">VendorAccountNumber</a>

First included in: ProcurementAndSourcing/PurchOpenPurchaseTotalDiscountJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FromOrderSubtotalAmount name="FromOrderSubtotalAmount">FromOrderSubtotalAmount</a>

First included in: ProcurementAndSourcing/PurchOpenPurchaseTotalDiscountJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromOrderSubtotalAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ToOrderSubtotalAmount name="ToOrderSubtotalAmount">ToOrderSubtotalAmount</a>

First included in: ProcurementAndSourcing/PurchOpenPurchaseTotalDiscountJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToOrderSubtotalAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscountApplicableFromDate name="DiscountApplicableFromDate">DiscountApplicableFromDate</a>

First included in: ProcurementAndSourcing/PurchOpenPurchaseTotalDiscountJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountApplicableFromDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscountApplicableToDate name="DiscountApplicableToDate">DiscountApplicableToDate</a>

First included in: ProcurementAndSourcing/PurchOpenPurchaseTotalDiscountJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountApplicableToDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscountAmount name="DiscountAmount">DiscountAmount</a>

First included in: ProcurementAndSourcing/PurchOpenPurchaseTotalDiscountJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscountCurrencyCode name="DiscountCurrencyCode">DiscountCurrencyCode</a>

First included in: ProcurementAndSourcing/PurchOpenPurchaseTotalDiscountJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountCurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscountPercentage1 name="DiscountPercentage1">DiscountPercentage1</a>

First included in: ProcurementAndSourcing/PurchOpenPurchaseTotalDiscountJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountPercentage1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscountPercentage2 name="DiscountPercentage2">DiscountPercentage2</a>

First included in: ProcurementAndSourcing/PurchOpenPurchaseTotalDiscountJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountPercentage2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillSearchContinue name="WillSearchContinue">WillSearchContinue</a>

First included in: ProcurementAndSourcing/PurchOpenPurchaseTotalDiscountJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillSearchContinue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProcessingLog name="ProcessingLog">ProcessingLog</a>

First included in: ProcurementAndSourcing/PurchOpenPurchaseTotalDiscountJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcessingLog attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountRelation name="AccountRelation">AccountRelation</a>

First included in: ProcurementAndSourcing/PurchOpenPurchaseTotalDiscountJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountRelation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountCode name="AccountCode">AccountCode</a>

First included in: ProcurementAndSourcing/PurchOpenPurchaseTotalDiscountJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemCode name="ItemCode">ItemCode</a>

First included in: ProcurementAndSourcing/PurchOpenPurchaseTotalDiscountJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemRelation name="ItemRelation">ItemRelation</a>

First included in: ProcurementAndSourcing/PurchOpenPurchaseTotalDiscountJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemRelation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JournalNum name="JournalNum">JournalNum</a>

First included in: ProcurementAndSourcing/PurchOpenPurchaseTotalDiscountJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TotalDiscountVendorGroupRelationshipId name="Relationship_TotalDiscountVendorGroupRelationshipId">Relationship_TotalDiscountVendorGroupRelationshipId</a>

First included in: ProcurementAndSourcing/PurchOpenPurchaseTotalDiscountJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TotalDiscountVendorGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_VendTableRelationshipId name="Relationship_VendTableRelationshipId">Relationship_VendTableRelationshipId</a>

First included in: ProcurementAndSourcing/PurchOpenPurchaseTotalDiscountJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendTableRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_PriceDiscAdmTransRelationshipId name="BackingTable_PriceDiscAdmTransRelationshipId">BackingTable_PriceDiscAdmTransRelationshipId</a>

First included in: ProcurementAndSourcing/PurchOpenPurchaseTotalDiscountJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PriceDiscAdmTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/WorksheetLine/PriceDiscAdmTrans.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/WorksheetLine/PriceDiscAdmTrans.cdm.json/PriceDiscAdmTrans</a></td><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/WorksheetLine/PriceDiscAdmTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProcurementAndSourcing/PurchOpenPurchaseTotalDiscountJournalLineEntity (this entity)  

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
