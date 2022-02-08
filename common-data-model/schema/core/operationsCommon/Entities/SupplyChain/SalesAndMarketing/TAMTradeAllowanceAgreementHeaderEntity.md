---
title: TAMTradeAllowanceAgreementHeaderEntity in SalesAndMarketing - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Trade allowance agreement headers in SalesAndMarketing(TAMTradeAllowanceAgreementHeaderEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Trade allowance agreement headers</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[BaseQuantity](#BaseQuantity)||<a href="TAMTradeAllowanceAgreementHeaderEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity</a>|
|[AgreementCurrencyCode](#AgreementCurrencyCode)||<a href="TAMTradeAllowanceAgreementHeaderEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity</a>|
|[PromotionLiftPercentage](#PromotionLiftPercentage)||<a href="TAMTradeAllowanceAgreementHeaderEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity</a>|
|[MarketingObjectiveCode](#MarketingObjectiveCode)||<a href="TAMTradeAllowanceAgreementHeaderEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity</a>|
|[PromotionCostAmount](#PromotionCostAmount)||<a href="TAMTradeAllowanceAgreementHeaderEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity</a>|
|[ToOrderDate](#ToOrderDate)||<a href="TAMTradeAllowanceAgreementHeaderEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity</a>|
|[FromOrderDate](#FromOrderDate)||<a href="TAMTradeAllowanceAgreementHeaderEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity</a>|
|[ExpectedPromotionalQuantity](#ExpectedPromotionalQuantity)||<a href="TAMTradeAllowanceAgreementHeaderEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity</a>|
|[ToLumpSumPayoutDate](#ToLumpSumPayoutDate)||<a href="TAMTradeAllowanceAgreementHeaderEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity</a>|
|[FromLumpSumPayoutDate](#FromLumpSumPayoutDate)||<a href="TAMTradeAllowanceAgreementHeaderEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity</a>|
|[AgreementDescription](#AgreementDescription)||<a href="TAMTradeAllowanceAgreementHeaderEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity</a>|
|[AgreementDetails](#AgreementDetails)||<a href="TAMTradeAllowanceAgreementHeaderEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity</a>|
|[AgreementId](#AgreementId)||<a href="TAMTradeAllowanceAgreementHeaderEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity</a>|
|[TradeAllowanceAgreementPeriodName](#TradeAllowanceAgreementPeriodName)||<a href="TAMTradeAllowanceAgreementHeaderEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity</a>|
|[AgreementStatus](#AgreementStatus)||<a href="TAMTradeAllowanceAgreementHeaderEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity</a>|
|[IsBaseQuantityOverridden](#IsBaseQuantityOverridden)||<a href="TAMTradeAllowanceAgreementHeaderEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity</a>|
|[ToRequestedShipDate](#ToRequestedShipDate)||<a href="TAMTradeAllowanceAgreementHeaderEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity</a>|
|[FromRequestedShipDate](#FromRequestedShipDate)||<a href="TAMTradeAllowanceAgreementHeaderEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity</a>|
|[ToRequestedReceiptDate](#ToRequestedReceiptDate)||<a href="TAMTradeAllowanceAgreementHeaderEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity</a>|
|[FromRequestedReceiptDate](#FromRequestedReceiptDate)||<a href="TAMTradeAllowanceAgreementHeaderEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity</a>|
|[BaseQuantityUnitSymbol](#BaseQuantityUnitSymbol)||<a href="TAMTradeAllowanceAgreementHeaderEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity</a>|
|[WorkflowApprovalStatus](#WorkflowApprovalStatus)||<a href="TAMTradeAllowanceAgreementHeaderEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity</a>|
|[OwningWorkerPersonnelNumber](#OwningWorkerPersonnelNumber)||<a href="TAMTradeAllowanceAgreementHeaderEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity</a>|
|[CustomerAccountNumber](#CustomerAccountNumber)||<a href="TAMTradeAllowanceAgreementHeaderEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity</a>|
|[Relationship_CurrencyRelationshipId](#Relationship_CurrencyRelationshipId)||<a href="TAMTradeAllowanceAgreementHeaderEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity</a>|
|[Relationship_MarketingObjectiveRelationshipId](#Relationship_MarketingObjectiveRelationshipId)||<a href="TAMTradeAllowanceAgreementHeaderEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity</a>|
|[Relationship_WorkerRelationshipId](#Relationship_WorkerRelationshipId)||<a href="TAMTradeAllowanceAgreementHeaderEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity</a>|
|[Relationship_UnitOfMeasureRelationshipId](#Relationship_UnitOfMeasureRelationshipId)||<a href="TAMTradeAllowanceAgreementHeaderEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity</a>|
|[Relationship_TradeAllowanceAgreementPeriodRelationshipId](#Relationship_TradeAllowanceAgreementPeriodRelationshipId)||<a href="TAMTradeAllowanceAgreementHeaderEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity</a>|
|[Relationship_CustomerRelationshipId](#Relationship_CustomerRelationshipId)||<a href="TAMTradeAllowanceAgreementHeaderEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity</a>|
|[BackingTable_TAMTradePromotionRelationshipId](#BackingTable_TAMTradePromotionRelationshipId)||<a href="TAMTradeAllowanceAgreementHeaderEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="TAMTradeAllowanceAgreementHeaderEntity.md" target="_blank">SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity</a>|

### <a href=#BaseQuantity name="BaseQuantity">BaseQuantity</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BaseQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgreementCurrencyCode name="AgreementCurrencyCode">AgreementCurrencyCode</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgreementCurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PromotionLiftPercentage name="PromotionLiftPercentage">PromotionLiftPercentage</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PromotionLiftPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MarketingObjectiveCode name="MarketingObjectiveCode">MarketingObjectiveCode</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MarketingObjectiveCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PromotionCostAmount name="PromotionCostAmount">PromotionCostAmount</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PromotionCostAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ToOrderDate name="ToOrderDate">ToOrderDate</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToOrderDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FromOrderDate name="FromOrderDate">FromOrderDate</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromOrderDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExpectedPromotionalQuantity name="ExpectedPromotionalQuantity">ExpectedPromotionalQuantity</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpectedPromotionalQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ToLumpSumPayoutDate name="ToLumpSumPayoutDate">ToLumpSumPayoutDate</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToLumpSumPayoutDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FromLumpSumPayoutDate name="FromLumpSumPayoutDate">FromLumpSumPayoutDate</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromLumpSumPayoutDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgreementDescription name="AgreementDescription">AgreementDescription</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgreementDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgreementDetails name="AgreementDetails">AgreementDetails</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgreementDetails attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgreementId name="AgreementId">AgreementId</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgreementId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TradeAllowanceAgreementPeriodName name="TradeAllowanceAgreementPeriodName">TradeAllowanceAgreementPeriodName</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TradeAllowanceAgreementPeriodName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgreementStatus name="AgreementStatus">AgreementStatus</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgreementStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsBaseQuantityOverridden name="IsBaseQuantityOverridden">IsBaseQuantityOverridden</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsBaseQuantityOverridden attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ToRequestedShipDate name="ToRequestedShipDate">ToRequestedShipDate</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToRequestedShipDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FromRequestedShipDate name="FromRequestedShipDate">FromRequestedShipDate</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromRequestedShipDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ToRequestedReceiptDate name="ToRequestedReceiptDate">ToRequestedReceiptDate</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ToRequestedReceiptDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FromRequestedReceiptDate name="FromRequestedReceiptDate">FromRequestedReceiptDate</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FromRequestedReceiptDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BaseQuantityUnitSymbol name="BaseQuantityUnitSymbol">BaseQuantityUnitSymbol</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BaseQuantityUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkflowApprovalStatus name="WorkflowApprovalStatus">WorkflowApprovalStatus</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkflowApprovalStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OwningWorkerPersonnelNumber name="OwningWorkerPersonnelNumber">OwningWorkerPersonnelNumber</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OwningWorkerPersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerAccountNumber name="CustomerAccountNumber">CustomerAccountNumber</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity (this entity)  

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

### <a href=#Relationship_CurrencyRelationshipId name="Relationship_CurrencyRelationshipId">Relationship_CurrencyRelationshipId</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CurrencyRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_MarketingObjectiveRelationshipId name="Relationship_MarketingObjectiveRelationshipId">Relationship_MarketingObjectiveRelationshipId</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MarketingObjectiveRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_WorkerRelationshipId name="Relationship_WorkerRelationshipId">Relationship_WorkerRelationshipId</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WorkerRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_UnitOfMeasureRelationshipId name="Relationship_UnitOfMeasureRelationshipId">Relationship_UnitOfMeasureRelationshipId</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_UnitOfMeasureRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_TradeAllowanceAgreementPeriodRelationshipId name="Relationship_TradeAllowanceAgreementPeriodRelationshipId">Relationship_TradeAllowanceAgreementPeriodRelationshipId</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TradeAllowanceAgreementPeriodRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_CustomerRelationshipId name="Relationship_CustomerRelationshipId">Relationship_CustomerRelationshipId</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustomerRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_TAMTradePromotionRelationshipId name="BackingTable_TAMTradePromotionRelationshipId">BackingTable_TAMTradePromotionRelationshipId</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_TAMTradePromotionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Main/TAMTradePromotion.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Main/TAMTradePromotion.cdm.json/TAMTradePromotion</a></td><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Main/TAMTradePromotion.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: SalesAndMarketing/TAMTradeAllowanceAgreementHeaderEntity (this entity)  

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
