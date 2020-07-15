---
title: SalesOpenSalesTotalDiscountJournalLineEntity in SalesAndMarketing - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/15/2020
ms.author: nebanfic
---

# Open sales total discount journal lines in SalesAndMarketing(SalesOpenSalesTotalDiscountJournalLineEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/SalesAndMarketing/SalesOpenSalesTotalDiscountJournalLineEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Open sales total discount journal lines</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[TradeAgreementJournalNumber](#TradeAgreementJournalNumber)||<a href="SalesOpenSalesTotalDiscountJournalLineEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesTotalDiscountJournalLineEntity</a>|
|[LineNumber](#LineNumber)||<a href="SalesOpenSalesTotalDiscountJournalLineEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesTotalDiscountJournalLineEntity</a>|
|[TotalDiscountCustomerGroupCode](#TotalDiscountCustomerGroupCode)||<a href="SalesOpenSalesTotalDiscountJournalLineEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesTotalDiscountJournalLineEntity</a>|
|[CustomerAccountNumber](#CustomerAccountNumber)||<a href="SalesOpenSalesTotalDiscountJournalLineEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesTotalDiscountJournalLineEntity</a>|
|[FromOrderSubtotalAmount](#FromOrderSubtotalAmount)||<a href="SalesOpenSalesTotalDiscountJournalLineEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesTotalDiscountJournalLineEntity</a>|
|[ToOrderSubtotalAmount](#ToOrderSubtotalAmount)||<a href="SalesOpenSalesTotalDiscountJournalLineEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesTotalDiscountJournalLineEntity</a>|
|[DiscountApplicableFromDate](#DiscountApplicableFromDate)||<a href="SalesOpenSalesTotalDiscountJournalLineEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesTotalDiscountJournalLineEntity</a>|
|[DiscountApplicableToDate](#DiscountApplicableToDate)||<a href="SalesOpenSalesTotalDiscountJournalLineEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesTotalDiscountJournalLineEntity</a>|
|[DiscountAmount](#DiscountAmount)||<a href="SalesOpenSalesTotalDiscountJournalLineEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesTotalDiscountJournalLineEntity</a>|
|[DiscountCurrencyCode](#DiscountCurrencyCode)||<a href="SalesOpenSalesTotalDiscountJournalLineEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesTotalDiscountJournalLineEntity</a>|
|[DiscountPercentage1](#DiscountPercentage1)||<a href="SalesOpenSalesTotalDiscountJournalLineEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesTotalDiscountJournalLineEntity</a>|
|[DiscountPercentage2](#DiscountPercentage2)||<a href="SalesOpenSalesTotalDiscountJournalLineEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesTotalDiscountJournalLineEntity</a>|
|[WillSearchContinue](#WillSearchContinue)||<a href="SalesOpenSalesTotalDiscountJournalLineEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesTotalDiscountJournalLineEntity</a>|
|[ProcessingLog](#ProcessingLog)||<a href="SalesOpenSalesTotalDiscountJournalLineEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesTotalDiscountJournalLineEntity</a>|
|[AccountRelation](#AccountRelation)||<a href="SalesOpenSalesTotalDiscountJournalLineEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesTotalDiscountJournalLineEntity</a>|
|[AccountCode](#AccountCode)||<a href="SalesOpenSalesTotalDiscountJournalLineEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesTotalDiscountJournalLineEntity</a>|
|[ItemCode](#ItemCode)||<a href="SalesOpenSalesTotalDiscountJournalLineEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesTotalDiscountJournalLineEntity</a>|
|[ItemRelation](#ItemRelation)||<a href="SalesOpenSalesTotalDiscountJournalLineEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesTotalDiscountJournalLineEntity</a>|
|[JournalNum](#JournalNum)||<a href="SalesOpenSalesTotalDiscountJournalLineEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesTotalDiscountJournalLineEntity</a>|
|[Relationship_TotalDiscountCustomerGroupRelationshipId](#Relationship_TotalDiscountCustomerGroupRelationshipId)||<a href="SalesOpenSalesTotalDiscountJournalLineEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesTotalDiscountJournalLineEntity</a>|
|[Relationship_CustTableRelationshipId](#Relationship_CustTableRelationshipId)||<a href="SalesOpenSalesTotalDiscountJournalLineEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesTotalDiscountJournalLineEntity</a>|
|[BackingTable_PriceDiscAdmTransRelationshipId](#BackingTable_PriceDiscAdmTransRelationshipId)||<a href="SalesOpenSalesTotalDiscountJournalLineEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesTotalDiscountJournalLineEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="SalesOpenSalesTotalDiscountJournalLineEntity.md" target="_blank">SalesAndMarketing/SalesOpenSalesTotalDiscountJournalLineEntity</a>|

### <a href=#TradeAgreementJournalNumber name="TradeAgreementJournalNumber">TradeAgreementJournalNumber</a>

First included in: SalesAndMarketing/SalesOpenSalesTotalDiscountJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TradeAgreementJournalNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: SalesAndMarketing/SalesOpenSalesTotalDiscountJournalLineEntity (this entity)  

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

### <a href=#TotalDiscountCustomerGroupCode name="TotalDiscountCustomerGroupCode">TotalDiscountCustomerGroupCode</a>

First included in: SalesAndMarketing/SalesOpenSalesTotalDiscountJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalDiscountCustomerGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerAccountNumber name="CustomerAccountNumber">CustomerAccountNumber</a>

First included in: SalesAndMarketing/SalesOpenSalesTotalDiscountJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FromOrderSubtotalAmount name="FromOrderSubtotalAmount">FromOrderSubtotalAmount</a>

First included in: SalesAndMarketing/SalesOpenSalesTotalDiscountJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromOrderSubtotalAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ToOrderSubtotalAmount name="ToOrderSubtotalAmount">ToOrderSubtotalAmount</a>

First included in: SalesAndMarketing/SalesOpenSalesTotalDiscountJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToOrderSubtotalAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscountApplicableFromDate name="DiscountApplicableFromDate">DiscountApplicableFromDate</a>

First included in: SalesAndMarketing/SalesOpenSalesTotalDiscountJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountApplicableFromDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscountApplicableToDate name="DiscountApplicableToDate">DiscountApplicableToDate</a>

First included in: SalesAndMarketing/SalesOpenSalesTotalDiscountJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountApplicableToDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscountAmount name="DiscountAmount">DiscountAmount</a>

First included in: SalesAndMarketing/SalesOpenSalesTotalDiscountJournalLineEntity (this entity)  

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

### <a href=#DiscountCurrencyCode name="DiscountCurrencyCode">DiscountCurrencyCode</a>

First included in: SalesAndMarketing/SalesOpenSalesTotalDiscountJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountCurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscountPercentage1 name="DiscountPercentage1">DiscountPercentage1</a>

First included in: SalesAndMarketing/SalesOpenSalesTotalDiscountJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountPercentage1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscountPercentage2 name="DiscountPercentage2">DiscountPercentage2</a>

First included in: SalesAndMarketing/SalesOpenSalesTotalDiscountJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountPercentage2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillSearchContinue name="WillSearchContinue">WillSearchContinue</a>

First included in: SalesAndMarketing/SalesOpenSalesTotalDiscountJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillSearchContinue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProcessingLog name="ProcessingLog">ProcessingLog</a>

First included in: SalesAndMarketing/SalesOpenSalesTotalDiscountJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcessingLog attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountRelation name="AccountRelation">AccountRelation</a>

First included in: SalesAndMarketing/SalesOpenSalesTotalDiscountJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountRelation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountCode name="AccountCode">AccountCode</a>

First included in: SalesAndMarketing/SalesOpenSalesTotalDiscountJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemCode name="ItemCode">ItemCode</a>

First included in: SalesAndMarketing/SalesOpenSalesTotalDiscountJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemRelation name="ItemRelation">ItemRelation</a>

First included in: SalesAndMarketing/SalesOpenSalesTotalDiscountJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemRelation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JournalNum name="JournalNum">JournalNum</a>

First included in: SalesAndMarketing/SalesOpenSalesTotalDiscountJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TotalDiscountCustomerGroupRelationshipId name="Relationship_TotalDiscountCustomerGroupRelationshipId">Relationship_TotalDiscountCustomerGroupRelationshipId</a>

First included in: SalesAndMarketing/SalesOpenSalesTotalDiscountJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TotalDiscountCustomerGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_CustTableRelationshipId name="Relationship_CustTableRelationshipId">Relationship_CustTableRelationshipId</a>

First included in: SalesAndMarketing/SalesOpenSalesTotalDiscountJournalLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustTableRelationshipId attribute are listed below.</summary>

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

First included in: SalesAndMarketing/SalesOpenSalesTotalDiscountJournalLineEntity (this entity)  

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

First included in: SalesAndMarketing/SalesOpenSalesTotalDiscountJournalLineEntity (this entity)  

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
