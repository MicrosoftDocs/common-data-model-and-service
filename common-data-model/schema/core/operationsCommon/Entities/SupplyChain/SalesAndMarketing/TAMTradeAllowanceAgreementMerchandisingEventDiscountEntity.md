---
title: TAMTradeAllowanceAgreementMerchandisingEventDiscountEntity in SalesAndMarketing - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Trade allowance agreement merchandising event discounts in SalesAndMarketing(TAMTradeAllowanceAgreementMerchandisingEventDiscountEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventDiscountEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Trade allowance agreement merchandising event discounts</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[LIneDiscountAmount](#LIneDiscountAmount)||<a href="TAMTradeAllowanceAgreementMerchandisingEventDiscountEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventDiscountEntity</a>|
|[LineDiscountPercentage](#LineDiscountPercentage)||<a href="TAMTradeAllowanceAgreementMerchandisingEventDiscountEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventDiscountEntity</a>|
|[FromQuantity](#FromQuantity)||<a href="TAMTradeAllowanceAgreementMerchandisingEventDiscountEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventDiscountEntity</a>|
|[ToQuantity](#ToQuantity)||<a href="TAMTradeAllowanceAgreementMerchandisingEventDiscountEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventDiscountEntity</a>|
|[WillAnalyticsIncludeDiscount](#WillAnalyticsIncludeDiscount)||<a href="TAMTradeAllowanceAgreementMerchandisingEventDiscountEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventDiscountEntity</a>|
|[DiscountLineNumber](#DiscountLineNumber)||<a href="TAMTradeAllowanceAgreementMerchandisingEventDiscountEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventDiscountEntity</a>|
|[CustomerAccountNumber](#CustomerAccountNumber)||<a href="TAMTradeAllowanceAgreementMerchandisingEventDiscountEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventDiscountEntity</a>|
|[TradeAllowanceAgreementMerchandisingEventId](#TradeAllowanceAgreementMerchandisingEventId)||<a href="TAMTradeAllowanceAgreementMerchandisingEventDiscountEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventDiscountEntity</a>|
|[TradeAllowanceAgreementId](#TradeAllowanceAgreementId)||<a href="TAMTradeAllowanceAgreementMerchandisingEventDiscountEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventDiscountEntity</a>|
|[Relationship_TradeAllowanceAgreementMerchandisingEventRelationshipId](#Relationship_TradeAllowanceAgreementMerchandisingEventRelationshipId)||<a href="TAMTradeAllowanceAgreementMerchandisingEventDiscountEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventDiscountEntity</a>|
|[Relationship_TradeAllowanceAgreementHeaderRelationshipId](#Relationship_TradeAllowanceAgreementHeaderRelationshipId)||<a href="TAMTradeAllowanceAgreementMerchandisingEventDiscountEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventDiscountEntity</a>|
|[BackingTable_TAMMerchEventPricingRelationshipId](#BackingTable_TAMMerchEventPricingRelationshipId)||<a href="TAMTradeAllowanceAgreementMerchandisingEventDiscountEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventDiscountEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="TAMTradeAllowanceAgreementMerchandisingEventDiscountEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventDiscountEntity</a>|

### <a href=#LIneDiscountAmount name="LIneDiscountAmount">LIneDiscountAmount</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LIneDiscountAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineDiscountPercentage name="LineDiscountPercentage">LineDiscountPercentage</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineDiscountPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FromQuantity name="FromQuantity">FromQuantity</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ToQuantity name="ToQuantity">ToQuantity</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillAnalyticsIncludeDiscount name="WillAnalyticsIncludeDiscount">WillAnalyticsIncludeDiscount</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillAnalyticsIncludeDiscount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscountLineNumber name="DiscountLineNumber">DiscountLineNumber</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountLineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerAccountNumber name="CustomerAccountNumber">CustomerAccountNumber</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TradeAllowanceAgreementMerchandisingEventId name="TradeAllowanceAgreementMerchandisingEventId">TradeAllowanceAgreementMerchandisingEventId</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TradeAllowanceAgreementMerchandisingEventId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TradeAllowanceAgreementId name="TradeAllowanceAgreementId">TradeAllowanceAgreementId</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TradeAllowanceAgreementId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TradeAllowanceAgreementMerchandisingEventRelationshipId name="Relationship_TradeAllowanceAgreementMerchandisingEventRelationshipId">Relationship_TradeAllowanceAgreementMerchandisingEventRelationshipId</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TradeAllowanceAgreementMerchandisingEventRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_TradeAllowanceAgreementHeaderRelationshipId name="Relationship_TradeAllowanceAgreementHeaderRelationshipId">Relationship_TradeAllowanceAgreementHeaderRelationshipId</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TradeAllowanceAgreementHeaderRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_TAMMerchEventPricingRelationshipId name="BackingTable_TAMMerchEventPricingRelationshipId">BackingTable_TAMMerchEventPricingRelationshipId</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_TAMMerchEventPricingRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Main/TAMMerchEventPricing.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Main/TAMMerchEventPricing.cdm.json/TAMMerchEventPricing</a></td><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Main/TAMMerchEventPricing.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementMerchandisingEventDiscountEntity (this entity)  

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
