---
title: TaxPostingGroupEntityV2 in Tax - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/20/2020
ms.author: nebanfic
---

# Sales tax ledger posting groups V2 in Tax(TaxPostingGroupEntityV2)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/Tax/TaxPostingGroupEntityV2.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales tax ledger posting groups V2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[TaxPostingGroupCode](#TaxPostingGroupCode)||<a href="TaxPostingGroupEntityV2.md" target="_blank">Tax/TaxPostingGroupEntityV2</a>|
|[Description](#Description)||<a href="TaxPostingGroupEntityV2.md" target="_blank">Tax/TaxPostingGroupEntityV2</a>|
|[TaxFromCustomerCashDiscountMainAccountId](#TaxFromCustomerCashDiscountMainAccountId)||<a href="TaxPostingGroupEntityV2.md" target="_blank">Tax/TaxPostingGroupEntityV2</a>|
|[TaxFromCustomerCashDiscountMainAccountIdDisplayValue](#TaxFromCustomerCashDiscountMainAccountIdDisplayValue)||<a href="TaxPostingGroupEntityV2.md" target="_blank">Tax/TaxPostingGroupEntityV2</a>|
|[TaxFromVendorCashDiscountMainAccountId](#TaxFromVendorCashDiscountMainAccountId)||<a href="TaxPostingGroupEntityV2.md" target="_blank">Tax/TaxPostingGroupEntityV2</a>|
|[TaxFromVendorCashDiscountMainAccountIdDisplayValue](#TaxFromVendorCashDiscountMainAccountIdDisplayValue)||<a href="TaxPostingGroupEntityV2.md" target="_blank">Tax/TaxPostingGroupEntityV2</a>|
|[TaxPayableMainAccountId](#TaxPayableMainAccountId)||<a href="TaxPostingGroupEntityV2.md" target="_blank">Tax/TaxPostingGroupEntityV2</a>|
|[TaxPayableMainAccountIdDisplayValue](#TaxPayableMainAccountIdDisplayValue)||<a href="TaxPostingGroupEntityV2.md" target="_blank">Tax/TaxPostingGroupEntityV2</a>|
|[UseTaxPayableMainAccountId](#UseTaxPayableMainAccountId)||<a href="TaxPostingGroupEntityV2.md" target="_blank">Tax/TaxPostingGroupEntityV2</a>|
|[UseTaxPayableMainAccountIdDisplayValue](#UseTaxPayableMainAccountIdDisplayValue)||<a href="TaxPostingGroupEntityV2.md" target="_blank">Tax/TaxPostingGroupEntityV2</a>|
|[TaxReceivableMainAccountId](#TaxReceivableMainAccountId)||<a href="TaxPostingGroupEntityV2.md" target="_blank">Tax/TaxPostingGroupEntityV2</a>|
|[TaxReceivableMainAccountIdDisplayValue](#TaxReceivableMainAccountIdDisplayValue)||<a href="TaxPostingGroupEntityV2.md" target="_blank">Tax/TaxPostingGroupEntityV2</a>|
|[TaxSettlementMainAccountId](#TaxSettlementMainAccountId)||<a href="TaxPostingGroupEntityV2.md" target="_blank">Tax/TaxPostingGroupEntityV2</a>|
|[TaxSettlementMainAccountIdDisplayValue](#TaxSettlementMainAccountIdDisplayValue)||<a href="TaxPostingGroupEntityV2.md" target="_blank">Tax/TaxPostingGroupEntityV2</a>|
|[UseTaxMainAccountId](#UseTaxMainAccountId)||<a href="TaxPostingGroupEntityV2.md" target="_blank">Tax/TaxPostingGroupEntityV2</a>|
|[UseTaxMainAccountIdDisplayValue](#UseTaxMainAccountIdDisplayValue)||<a href="TaxPostingGroupEntityV2.md" target="_blank">Tax/TaxPostingGroupEntityV2</a>|
|[TaxReceivableLongTermMainAccountId](#TaxReceivableLongTermMainAccountId)||<a href="TaxPostingGroupEntityV2.md" target="_blank">Tax/TaxPostingGroupEntityV2</a>|
|[TaxReceivableLongTermMainAccountIdDisplayValue](#TaxReceivableLongTermMainAccountIdDisplayValue)||<a href="TaxPostingGroupEntityV2.md" target="_blank">Tax/TaxPostingGroupEntityV2</a>|
|[TaxReceivableShortTermMainAccountId](#TaxReceivableShortTermMainAccountId)||<a href="TaxPostingGroupEntityV2.md" target="_blank">Tax/TaxPostingGroupEntityV2</a>|
|[TaxReceivableShortTermMainAccountIdDisplayValue](#TaxReceivableShortTermMainAccountIdDisplayValue)||<a href="TaxPostingGroupEntityV2.md" target="_blank">Tax/TaxPostingGroupEntityV2</a>|
|[TaxSalesExpenseMainAccountId](#TaxSalesExpenseMainAccountId)||<a href="TaxPostingGroupEntityV2.md" target="_blank">Tax/TaxPostingGroupEntityV2</a>|
|[TaxSalesExpenseMainAccountIdDisplayValue](#TaxSalesExpenseMainAccountIdDisplayValue)||<a href="TaxPostingGroupEntityV2.md" target="_blank">Tax/TaxPostingGroupEntityV2</a>|
|[TaxUnrealizedPayablesMainAccountId](#TaxUnrealizedPayablesMainAccountId)||<a href="TaxPostingGroupEntityV2.md" target="_blank">Tax/TaxPostingGroupEntityV2</a>|
|[TaxUnrealizedPayablesMainAccountIdDisplayValue](#TaxUnrealizedPayablesMainAccountIdDisplayValue)||<a href="TaxPostingGroupEntityV2.md" target="_blank">Tax/TaxPostingGroupEntityV2</a>|
|[TaxUnrealizedReceivablesMainAccountId](#TaxUnrealizedReceivablesMainAccountId)||<a href="TaxPostingGroupEntityV2.md" target="_blank">Tax/TaxPostingGroupEntityV2</a>|
|[TaxUnrealizedReceivablesMainAccountIdDisplayValue](#TaxUnrealizedReceivablesMainAccountIdDisplayValue)||<a href="TaxPostingGroupEntityV2.md" target="_blank">Tax/TaxPostingGroupEntityV2</a>|
|[TaxIncomingDifferenceMainAccountId](#TaxIncomingDifferenceMainAccountId)||<a href="TaxPostingGroupEntityV2.md" target="_blank">Tax/TaxPostingGroupEntityV2</a>|
|[TaxIncomingDifferenceMainAccountIdDisplayValue](#TaxIncomingDifferenceMainAccountIdDisplayValue)||<a href="TaxPostingGroupEntityV2.md" target="_blank">Tax/TaxPostingGroupEntityV2</a>|
|[TaxIncomingDiffOffsetMainAccountId](#TaxIncomingDiffOffsetMainAccountId)||<a href="TaxPostingGroupEntityV2.md" target="_blank">Tax/TaxPostingGroupEntityV2</a>|
|[TaxIncomingDiffOffsetMainAccountIdDisplayValue](#TaxIncomingDiffOffsetMainAccountIdDisplayValue)||<a href="TaxPostingGroupEntityV2.md" target="_blank">Tax/TaxPostingGroupEntityV2</a>|
|[TaxOutgoingDifferenceMainAccountId](#TaxOutgoingDifferenceMainAccountId)||<a href="TaxPostingGroupEntityV2.md" target="_blank">Tax/TaxPostingGroupEntityV2</a>|
|[TaxOutgoingDifferenceMainAccountIdDisplayValue](#TaxOutgoingDifferenceMainAccountIdDisplayValue)||<a href="TaxPostingGroupEntityV2.md" target="_blank">Tax/TaxPostingGroupEntityV2</a>|
|[TaxOutgoingDiffOffsetMainAccountId](#TaxOutgoingDiffOffsetMainAccountId)||<a href="TaxPostingGroupEntityV2.md" target="_blank">Tax/TaxPostingGroupEntityV2</a>|
|[TaxOutgoingDiffOffsetMainAccountIdDisplayValue](#TaxOutgoingDiffOffsetMainAccountIdDisplayValue)||<a href="TaxPostingGroupEntityV2.md" target="_blank">Tax/TaxPostingGroupEntityV2</a>|
|[TaxOutgoingOffsetLedgerMainAccountId](#TaxOutgoingOffsetLedgerMainAccountId)||<a href="TaxPostingGroupEntityV2.md" target="_blank">Tax/TaxPostingGroupEntityV2</a>|
|[TaxOutgoingOffsetLedgerMainAccountIdDisplayValue](#TaxOutgoingOffsetLedgerMainAccountIdDisplayValue)||<a href="TaxPostingGroupEntityV2.md" target="_blank">Tax/TaxPostingGroupEntityV2</a>|
|[Relationship_TaxFromCustomerCashDiscountMainAccountDimensionCombinationRelationshipId](#Relationship_TaxFromCustomerCashDiscountMainAccountDimensionCombinationRelationshipId)||<a href="TaxPostingGroupEntityV2.md" target="_blank">Tax/TaxPostingGroupEntityV2</a>|
|[Relationship_TaxFromVendorCashDiscountMainAccountDimensionCombinationRelationshipId](#Relationship_TaxFromVendorCashDiscountMainAccountDimensionCombinationRelationshipId)||<a href="TaxPostingGroupEntityV2.md" target="_blank">Tax/TaxPostingGroupEntityV2</a>|
|[Relationship_TaxPayableMainAccountDimensionCombinationRelationshipId](#Relationship_TaxPayableMainAccountDimensionCombinationRelationshipId)||<a href="TaxPostingGroupEntityV2.md" target="_blank">Tax/TaxPostingGroupEntityV2</a>|
|[Relationship_UseTaxPayableMainAccountDimensionCombinationRelationshipId](#Relationship_UseTaxPayableMainAccountDimensionCombinationRelationshipId)||<a href="TaxPostingGroupEntityV2.md" target="_blank">Tax/TaxPostingGroupEntityV2</a>|
|[Relationship_TaxReceivableMainAccountDimensionCombinationRelationshipId](#Relationship_TaxReceivableMainAccountDimensionCombinationRelationshipId)||<a href="TaxPostingGroupEntityV2.md" target="_blank">Tax/TaxPostingGroupEntityV2</a>|
|[Relationship_TaxSettlementMainAccountDimensionCombinationRelationshipId](#Relationship_TaxSettlementMainAccountDimensionCombinationRelationshipId)||<a href="TaxPostingGroupEntityV2.md" target="_blank">Tax/TaxPostingGroupEntityV2</a>|
|[Relationship_UseTaxMainAccountDimensionCombinationRelationshipId](#Relationship_UseTaxMainAccountDimensionCombinationRelationshipId)||<a href="TaxPostingGroupEntityV2.md" target="_blank">Tax/TaxPostingGroupEntityV2</a>|
|[Relationship_TaxUnrealizedPayablesDimensionCombinationRelationshipId](#Relationship_TaxUnrealizedPayablesDimensionCombinationRelationshipId)||<a href="TaxPostingGroupEntityV2.md" target="_blank">Tax/TaxPostingGroupEntityV2</a>|
|[Relationship_TaxUnrealizedReceivablesDimensionCombinationRelationshipId](#Relationship_TaxUnrealizedReceivablesDimensionCombinationRelationshipId)||<a href="TaxPostingGroupEntityV2.md" target="_blank">Tax/TaxPostingGroupEntityV2</a>|
|[Relationship_TaxIncomingDifferenceMainAccountDimensionCombinationRelationshipId](#Relationship_TaxIncomingDifferenceMainAccountDimensionCombinationRelationshipId)||<a href="TaxPostingGroupEntityV2.md" target="_blank">Tax/TaxPostingGroupEntityV2</a>|
|[Relationship_TaxIncomingDiffOffsetMainAccountDimensionCombinationRelationshipId](#Relationship_TaxIncomingDiffOffsetMainAccountDimensionCombinationRelationshipId)||<a href="TaxPostingGroupEntityV2.md" target="_blank">Tax/TaxPostingGroupEntityV2</a>|
|[Relationship_TaxOutgoingDifferenceMainAccountDimensionCombinationRelationshipId](#Relationship_TaxOutgoingDifferenceMainAccountDimensionCombinationRelationshipId)||<a href="TaxPostingGroupEntityV2.md" target="_blank">Tax/TaxPostingGroupEntityV2</a>|
|[Relationship_TaxOutgoingDiffOffsetMainAccountDimensionCombinationRelationshipId](#Relationship_TaxOutgoingDiffOffsetMainAccountDimensionCombinationRelationshipId)||<a href="TaxPostingGroupEntityV2.md" target="_blank">Tax/TaxPostingGroupEntityV2</a>|
|[BackingTable_TaxLedgerAccountGroupRelationshipId](#BackingTable_TaxLedgerAccountGroupRelationshipId)||<a href="TaxPostingGroupEntityV2.md" target="_blank">Tax/TaxPostingGroupEntityV2</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="TaxPostingGroupEntityV2.md" target="_blank">Tax/TaxPostingGroupEntityV2</a>|

### <a href=#TaxPostingGroupCode name="TaxPostingGroupCode">TaxPostingGroupCode</a>

First included in: Tax/TaxPostingGroupEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxPostingGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: Tax/TaxPostingGroupEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxFromCustomerCashDiscountMainAccountId name="TaxFromCustomerCashDiscountMainAccountId">TaxFromCustomerCashDiscountMainAccountId</a>

First included in: Tax/TaxPostingGroupEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Vendor cash discount</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxFromCustomerCashDiscountMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Vendor cash discount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxFromCustomerCashDiscountMainAccountIdDisplayValue name="TaxFromCustomerCashDiscountMainAccountIdDisplayValue">TaxFromCustomerCashDiscountMainAccountIdDisplayValue</a>

First included in: Tax/TaxPostingGroupEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Vendor cash discount</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxFromCustomerCashDiscountMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Vendor cash discount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxFromVendorCashDiscountMainAccountId name="TaxFromVendorCashDiscountMainAccountId">TaxFromVendorCashDiscountMainAccountId</a>

First included in: Tax/TaxPostingGroupEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer cash discount</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxFromVendorCashDiscountMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Customer cash discount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxFromVendorCashDiscountMainAccountIdDisplayValue name="TaxFromVendorCashDiscountMainAccountIdDisplayValue">TaxFromVendorCashDiscountMainAccountIdDisplayValue</a>

First included in: Tax/TaxPostingGroupEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customer cash discount</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxFromVendorCashDiscountMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Customer cash discount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxPayableMainAccountId name="TaxPayableMainAccountId">TaxPayableMainAccountId</a>

First included in: Tax/TaxPostingGroupEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales tax payable</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxPayableMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales tax payable</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxPayableMainAccountIdDisplayValue name="TaxPayableMainAccountIdDisplayValue">TaxPayableMainAccountIdDisplayValue</a>

First included in: Tax/TaxPostingGroupEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales tax payable</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxPayableMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales tax payable</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseTaxPayableMainAccountId name="UseTaxPayableMainAccountId">UseTaxPayableMainAccountId</a>

First included in: Tax/TaxPostingGroupEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Use tax payable</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseTaxPayableMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Use tax payable</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseTaxPayableMainAccountIdDisplayValue name="UseTaxPayableMainAccountIdDisplayValue">UseTaxPayableMainAccountIdDisplayValue</a>

First included in: Tax/TaxPostingGroupEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Use tax payable</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseTaxPayableMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Use tax payable</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxReceivableMainAccountId name="TaxReceivableMainAccountId">TaxReceivableMainAccountId</a>

First included in: Tax/TaxPostingGroupEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxReceivableMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxReceivableMainAccountIdDisplayValue name="TaxReceivableMainAccountIdDisplayValue">TaxReceivableMainAccountIdDisplayValue</a>

First included in: Tax/TaxPostingGroupEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales tax receivable</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxReceivableMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales tax receivable</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxSettlementMainAccountId name="TaxSettlementMainAccountId">TaxSettlementMainAccountId</a>

First included in: Tax/TaxPostingGroupEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Settlement account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxSettlementMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Settlement account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxSettlementMainAccountIdDisplayValue name="TaxSettlementMainAccountIdDisplayValue">TaxSettlementMainAccountIdDisplayValue</a>

First included in: Tax/TaxPostingGroupEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Settlement account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxSettlementMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Settlement account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseTaxMainAccountId name="UseTaxMainAccountId">UseTaxMainAccountId</a>

First included in: Tax/TaxPostingGroupEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Use tax expense</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseTaxMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Use tax expense</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseTaxMainAccountIdDisplayValue name="UseTaxMainAccountIdDisplayValue">UseTaxMainAccountIdDisplayValue</a>

First included in: Tax/TaxPostingGroupEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Use tax expense</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseTaxMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Use tax expense</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxReceivableLongTermMainAccountId name="TaxReceivableLongTermMainAccountId">TaxReceivableLongTermMainAccountId</a>

First included in: Tax/TaxPostingGroupEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales tax receivable long term</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxReceivableLongTermMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales tax receivable long term</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxReceivableLongTermMainAccountIdDisplayValue name="TaxReceivableLongTermMainAccountIdDisplayValue">TaxReceivableLongTermMainAccountIdDisplayValue</a>

First included in: Tax/TaxPostingGroupEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales tax receivable long term</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxReceivableLongTermMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales tax receivable long term</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxReceivableShortTermMainAccountId name="TaxReceivableShortTermMainAccountId">TaxReceivableShortTermMainAccountId</a>

First included in: Tax/TaxPostingGroupEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales tax receivable short term</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxReceivableShortTermMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales tax receivable short term</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxReceivableShortTermMainAccountIdDisplayValue name="TaxReceivableShortTermMainAccountIdDisplayValue">TaxReceivableShortTermMainAccountIdDisplayValue</a>

First included in: Tax/TaxPostingGroupEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales tax receivable short term</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxReceivableShortTermMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales tax receivable short term</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxSalesExpenseMainAccountId name="TaxSalesExpenseMainAccountId">TaxSalesExpenseMainAccountId</a>

First included in: Tax/TaxPostingGroupEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales tax expense</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxSalesExpenseMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales tax expense</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxSalesExpenseMainAccountIdDisplayValue name="TaxSalesExpenseMainAccountIdDisplayValue">TaxSalesExpenseMainAccountIdDisplayValue</a>

First included in: Tax/TaxPostingGroupEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales tax expense</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxSalesExpenseMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales tax expense</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxUnrealizedPayablesMainAccountId name="TaxUnrealizedPayablesMainAccountId">TaxUnrealizedPayablesMainAccountId</a>

First included in: Tax/TaxPostingGroupEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Unrealized tax payable</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxUnrealizedPayablesMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unrealized tax payable</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxUnrealizedPayablesMainAccountIdDisplayValue name="TaxUnrealizedPayablesMainAccountIdDisplayValue">TaxUnrealizedPayablesMainAccountIdDisplayValue</a>

First included in: Tax/TaxPostingGroupEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Unrealized tax payable</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxUnrealizedPayablesMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unrealized tax payable</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxUnrealizedReceivablesMainAccountId name="TaxUnrealizedReceivablesMainAccountId">TaxUnrealizedReceivablesMainAccountId</a>

First included in: Tax/TaxPostingGroupEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Unrealized tax receivable</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxUnrealizedReceivablesMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unrealized tax receivable</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxUnrealizedReceivablesMainAccountIdDisplayValue name="TaxUnrealizedReceivablesMainAccountIdDisplayValue">TaxUnrealizedReceivablesMainAccountIdDisplayValue</a>

First included in: Tax/TaxPostingGroupEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Unrealized tax receivable</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxUnrealizedReceivablesMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unrealized tax receivable</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxIncomingDifferenceMainAccountId name="TaxIncomingDifferenceMainAccountId">TaxIncomingDifferenceMainAccountId</a>

First included in: Tax/TaxPostingGroupEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales tax receivable difference</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxIncomingDifferenceMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales tax receivable difference</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxIncomingDifferenceMainAccountIdDisplayValue name="TaxIncomingDifferenceMainAccountIdDisplayValue">TaxIncomingDifferenceMainAccountIdDisplayValue</a>

First included in: Tax/TaxPostingGroupEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales tax receivable difference</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxIncomingDifferenceMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales tax receivable difference</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxIncomingDiffOffsetMainAccountId name="TaxIncomingDiffOffsetMainAccountId">TaxIncomingDiffOffsetMainAccountId</a>

First included in: Tax/TaxPostingGroupEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales tax receivable difference offset</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxIncomingDiffOffsetMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales tax receivable difference offset</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxIncomingDiffOffsetMainAccountIdDisplayValue name="TaxIncomingDiffOffsetMainAccountIdDisplayValue">TaxIncomingDiffOffsetMainAccountIdDisplayValue</a>

First included in: Tax/TaxPostingGroupEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales tax receivable difference offset</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxIncomingDiffOffsetMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales tax receivable difference offset</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxOutgoingDifferenceMainAccountId name="TaxOutgoingDifferenceMainAccountId">TaxOutgoingDifferenceMainAccountId</a>

First included in: Tax/TaxPostingGroupEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales tax payable difference</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxOutgoingDifferenceMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales tax payable difference</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxOutgoingDifferenceMainAccountIdDisplayValue name="TaxOutgoingDifferenceMainAccountIdDisplayValue">TaxOutgoingDifferenceMainAccountIdDisplayValue</a>

First included in: Tax/TaxPostingGroupEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales tax payable difference</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxOutgoingDifferenceMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales tax payable difference</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxOutgoingDiffOffsetMainAccountId name="TaxOutgoingDiffOffsetMainAccountId">TaxOutgoingDiffOffsetMainAccountId</a>

First included in: Tax/TaxPostingGroupEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales tax payable difference offset</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxOutgoingDiffOffsetMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales tax payable difference offset</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxOutgoingDiffOffsetMainAccountIdDisplayValue name="TaxOutgoingDiffOffsetMainAccountIdDisplayValue">TaxOutgoingDiffOffsetMainAccountIdDisplayValue</a>

First included in: Tax/TaxPostingGroupEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales tax payable difference offset</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxOutgoingDiffOffsetMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales tax payable difference offset</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxOutgoingOffsetLedgerMainAccountId name="TaxOutgoingOffsetLedgerMainAccountId">TaxOutgoingOffsetLedgerMainAccountId</a>

First included in: Tax/TaxPostingGroupEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxOutgoingOffsetLedgerMainAccountId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxOutgoingOffsetLedgerMainAccountIdDisplayValue name="TaxOutgoingOffsetLedgerMainAccountIdDisplayValue">TaxOutgoingOffsetLedgerMainAccountIdDisplayValue</a>

First included in: Tax/TaxPostingGroupEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Payment offset account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxOutgoingOffsetLedgerMainAccountIdDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Payment offset account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxFromCustomerCashDiscountMainAccountDimensionCombinationRelationshipId name="Relationship_TaxFromCustomerCashDiscountMainAccountDimensionCombinationRelationshipId">Relationship_TaxFromCustomerCashDiscountMainAccountDimensionCombinationRelationshipId</a>

First included in: Tax/TaxPostingGroupEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxFromCustomerCashDiscountMainAccountDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_TaxFromVendorCashDiscountMainAccountDimensionCombinationRelationshipId name="Relationship_TaxFromVendorCashDiscountMainAccountDimensionCombinationRelationshipId">Relationship_TaxFromVendorCashDiscountMainAccountDimensionCombinationRelationshipId</a>

First included in: Tax/TaxPostingGroupEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxFromVendorCashDiscountMainAccountDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_TaxPayableMainAccountDimensionCombinationRelationshipId name="Relationship_TaxPayableMainAccountDimensionCombinationRelationshipId">Relationship_TaxPayableMainAccountDimensionCombinationRelationshipId</a>

First included in: Tax/TaxPostingGroupEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxPayableMainAccountDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_UseTaxPayableMainAccountDimensionCombinationRelationshipId name="Relationship_UseTaxPayableMainAccountDimensionCombinationRelationshipId">Relationship_UseTaxPayableMainAccountDimensionCombinationRelationshipId</a>

First included in: Tax/TaxPostingGroupEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_UseTaxPayableMainAccountDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_TaxReceivableMainAccountDimensionCombinationRelationshipId name="Relationship_TaxReceivableMainAccountDimensionCombinationRelationshipId">Relationship_TaxReceivableMainAccountDimensionCombinationRelationshipId</a>

First included in: Tax/TaxPostingGroupEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxReceivableMainAccountDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_TaxSettlementMainAccountDimensionCombinationRelationshipId name="Relationship_TaxSettlementMainAccountDimensionCombinationRelationshipId">Relationship_TaxSettlementMainAccountDimensionCombinationRelationshipId</a>

First included in: Tax/TaxPostingGroupEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxSettlementMainAccountDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_UseTaxMainAccountDimensionCombinationRelationshipId name="Relationship_UseTaxMainAccountDimensionCombinationRelationshipId">Relationship_UseTaxMainAccountDimensionCombinationRelationshipId</a>

First included in: Tax/TaxPostingGroupEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_UseTaxMainAccountDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_TaxUnrealizedPayablesDimensionCombinationRelationshipId name="Relationship_TaxUnrealizedPayablesDimensionCombinationRelationshipId">Relationship_TaxUnrealizedPayablesDimensionCombinationRelationshipId</a>

First included in: Tax/TaxPostingGroupEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxUnrealizedPayablesDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_TaxUnrealizedReceivablesDimensionCombinationRelationshipId name="Relationship_TaxUnrealizedReceivablesDimensionCombinationRelationshipId">Relationship_TaxUnrealizedReceivablesDimensionCombinationRelationshipId</a>

First included in: Tax/TaxPostingGroupEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxUnrealizedReceivablesDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_TaxIncomingDifferenceMainAccountDimensionCombinationRelationshipId name="Relationship_TaxIncomingDifferenceMainAccountDimensionCombinationRelationshipId">Relationship_TaxIncomingDifferenceMainAccountDimensionCombinationRelationshipId</a>

First included in: Tax/TaxPostingGroupEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxIncomingDifferenceMainAccountDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_TaxIncomingDiffOffsetMainAccountDimensionCombinationRelationshipId name="Relationship_TaxIncomingDiffOffsetMainAccountDimensionCombinationRelationshipId">Relationship_TaxIncomingDiffOffsetMainAccountDimensionCombinationRelationshipId</a>

First included in: Tax/TaxPostingGroupEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxIncomingDiffOffsetMainAccountDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_TaxOutgoingDifferenceMainAccountDimensionCombinationRelationshipId name="Relationship_TaxOutgoingDifferenceMainAccountDimensionCombinationRelationshipId">Relationship_TaxOutgoingDifferenceMainAccountDimensionCombinationRelationshipId</a>

First included in: Tax/TaxPostingGroupEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxOutgoingDifferenceMainAccountDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_TaxOutgoingDiffOffsetMainAccountDimensionCombinationRelationshipId name="Relationship_TaxOutgoingDiffOffsetMainAccountDimensionCombinationRelationshipId">Relationship_TaxOutgoingDiffOffsetMainAccountDimensionCombinationRelationshipId</a>

First included in: Tax/TaxPostingGroupEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxOutgoingDiffOffsetMainAccountDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_TaxLedgerAccountGroupRelationshipId name="BackingTable_TaxLedgerAccountGroupRelationshipId">BackingTable_TaxLedgerAccountGroupRelationshipId</a>

First included in: Tax/TaxPostingGroupEntityV2 (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_TaxLedgerAccountGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Tax/Group/TaxLedgerAccountGroup.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxLedgerAccountGroup.cdm.json/TaxLedgerAccountGroup</a></td><td><a href="../../../Tables/Finance/Tax/Group/TaxLedgerAccountGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: Tax/TaxPostingGroupEntityV2 (this entity)  

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
