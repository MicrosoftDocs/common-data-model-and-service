---
title: RetailFunctionalityProfileEntity in BrickAndMortarStore - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# POS functionality profile in BrickAndMortarStore(RetailFunctionalityProfileEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Commerce/ChannelManagement/BrickAndMortarStore/RetailFunctionalityProfileEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>POS functionality profile</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[profileId](#profileId)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[addTaxOnPrices](#addTaxOnPrices)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[aggregateItems](#aggregateItems)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[aggregateItemsForPrinting](#aggregateItemsForPrinting)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[aggregatePayments](#aggregatePayments)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[AmountDecimalPlaces](#AmountDecimalPlaces)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[amountRoundingTo](#amountRoundingTo)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[ApplyDiscountOnUnitPrices](#ApplyDiscountOnUnitPrices)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[AuditEnabled](#AuditEnabled)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[backupTrainingTransactions](#backupTrainingTransactions)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[blockedClosedAccount](#blockedClosedAccount)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[centralTableServer](#centralTableServer)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[centralTableServerPort](#centralTableServerPort)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[currencySymbol](#currencySymbol)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[DaysCustomerHistory](#DaysCustomerHistory)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[daysTransactionsExists](#daysTransactionsExists)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[DecimalNotRequiredForMinorCurrencyUnit](#DecimalNotRequiredForMinorCurrencyUnit)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[discountAtTotal](#discountAtTotal)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[displaySecondaryTotalCurrency](#displaySecondaryTotalCurrency)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[endOfTransaction](#endOfTransaction)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[EODBankTotalsVerification](#EODBankTotalsVerification)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[includeKitComponents](#includeKitComponents)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[itemNotOnFile](#itemNotOnFile)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[limitStaffListToStore](#limitStaffListToStore)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[lineItemTaxChange](#lineItemTaxChange)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[ManualCalculateDiscounts](#ManualCalculateDiscounts)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[markDown](#markDown)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[markUp](#markUp)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[maximumPrice](#maximumPrice)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[maximumQuantity](#maximumQuantity)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[maximumStoreTransLog](#maximumStoreTransLog)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[maxTransactionSearchResults](#maxTransactionSearchResults)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[minimumPasswordLength](#minimumPasswordLength)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[multibleItemSymbol](#multibleItemSymbol)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[mustKeyInPriceIfZero](#mustKeyInPriceIfZero)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[name](#name)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[negativeAdjustment](#negativeAdjustment)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[negativeSalesLine](#negativeSalesLine)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[noSale](#noSale)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[noTaxUsed](#noTaxUsed)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[overridePrice](#overridePrice)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[PriceDecimalPlaces](#PriceDecimalPlaces)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[priceRoundingTo](#priceRoundingTo)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[printXReportOnTerminal](#printXReportOnTerminal)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[refundSale](#refundSale)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[RequireAmountDeclaration](#RequireAmountDeclaration)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[RetailReceiptProfile](#RetailReceiptProfile)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[salesPerson](#salesPerson)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[salesPersonMode](#salesPersonMode)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[secondaryTotalCurrency](#secondaryTotalCurrency)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[serialNumber](#serialNumber)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[showStaffListAtLogOn](#showStaffListAtLogOn)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[skipTaxOnReceipt](#skipTaxOnReceipt)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[staffBarcodeLogon](#staffBarcodeLogon)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[StaffBarcodeLogonRequiresPassword](#StaffBarcodeLogonRequiresPassword)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[staffCardLogon](#staffCardLogon)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[StaffCardLogonRequiresPassword](#StaffCardLogonRequiresPassword)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[startOfTransaction](#startOfTransaction)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[supportedCountryRegionISOCode](#supportedCountryRegionISOCode)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[TimeAttendanceEnableRegistration](#TimeAttendanceEnableRegistration)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[taxRegistrationNumberOnReceipt](#taxRegistrationNumberOnReceipt)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[tenderDeclaration](#tenderDeclaration)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[transactionDeleteReminder](#transactionDeleteReminder)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[transactionTaxChange](#transactionTaxChange)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[voidIsPressed](#voidIsPressed)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[voidPayment](#voidPayment)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[voidTransaction](#voidTransaction)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[cancelReason](#cancelReason)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[contingencyReason](#contingencyReason)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[CreateAsyncCustomers](#CreateAsyncCustomers)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[SalesModeDefaultAsCustomerOrder](#SalesModeDefaultAsCustomerOrder)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[AlwaysExpandTransactionScreenLineDetails](#AlwaysExpandTransactionScreenLineDetails)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[ProhibitMixingSalesAndReturns](#ProhibitMixingSalesAndReturns)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[IsProductSuggestionsEnabled](#IsProductSuggestionsEnabled)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[ProductSearchType](#ProductSearchType)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[DenominationsToDisplay](#DenominationsToDisplay)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[RejectOrderFulfillment](#RejectOrderFulfillment)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[EmployeeLogonType](#EmployeeLogonType)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[NotificationRefreshInterval](#NotificationRefreshInterval)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[ManualTaxCalculation](#ManualTaxCalculation)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[ExcludeSalesOrderInvoices](#ExcludeSalesOrderInvoices)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[IncludeFreeTextInvoices](#IncludeFreeTextInvoices)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[IncludeProjectInvoices](#IncludeProjectInvoices)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[IncludeCreditNoteInvoices](#IncludeCreditNoteInvoices)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[ProcessNumber](#ProcessNumber)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[GenerateLoyaltyCardNumber](#GenerateLoyaltyCardNumber)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[PrintVoidTransactionReceipts](#PrintVoidTransactionReceipts)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[ManualChargeCalculation](#ManualChargeCalculation)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[VoidSuspendedTransactionsOnCloseShift](#VoidSuspendedTransactionsOnCloseShift)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[TaxExemptReceiptIndicator](#TaxExemptReceiptIndicator)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[DisplayTaxExemptInLineDetails](#DisplayTaxExemptInLineDetails)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[UseAdvancedCashManagement](#UseAdvancedCashManagement)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[ShiftReconciliation](#ShiftReconciliation)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[PrintReceiptsOnCardDecline](#PrintReceiptsOnCardDecline)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[DefaultCustomerSearchMode](#DefaultCustomerSearchMode)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[IsFiscalCustomerRequiredForTransaction](#IsFiscalCustomerRequiredForTransaction)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[UseFinancialReconcialiationInStore](#UseFinancialReconcialiationInStore)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[CreateAsyncCustomerOrders](#CreateAsyncCustomerOrders)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[RequirePaymentForFulfillment](#RequirePaymentForFulfillment)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|
|[BackingTable_RetailFunctionalityProfileRelationshipId](#BackingTable_RetailFunctionalityProfileRelationshipId)||<a href="RetailFunctionalityProfileEntity.md" target="_blank">BrickAndMortarStore/RetailFunctionalityProfileEntity</a>|

### <a href=#profileId name="profileId">profileId</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the profileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#addTaxOnPrices name="addTaxOnPrices">addTaxOnPrices</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the addTaxOnPrices attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#aggregateItems name="aggregateItems">aggregateItems</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the aggregateItems attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#aggregateItemsForPrinting name="aggregateItemsForPrinting">aggregateItemsForPrinting</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the aggregateItemsForPrinting attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#aggregatePayments name="aggregatePayments">aggregatePayments</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the aggregatePayments attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AmountDecimalPlaces name="AmountDecimalPlaces">AmountDecimalPlaces</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountDecimalPlaces attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#amountRoundingTo name="amountRoundingTo">amountRoundingTo</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the amountRoundingTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ApplyDiscountOnUnitPrices name="ApplyDiscountOnUnitPrices">ApplyDiscountOnUnitPrices</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Apply discounts to unit price</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ApplyDiscountOnUnitPrices attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Apply discounts to unit price</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AuditEnabled name="AuditEnabled">AuditEnabled</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AuditEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#backupTrainingTransactions name="backupTrainingTransactions">backupTrainingTransactions</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the backupTrainingTransactions attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#blockedClosedAccount name="blockedClosedAccount">blockedClosedAccount</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the blockedClosedAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#centralTableServer name="centralTableServer">centralTableServer</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the centralTableServer attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#centralTableServerPort name="centralTableServerPort">centralTableServerPort</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the centralTableServerPort attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#currencySymbol name="currencySymbol">currencySymbol</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the currencySymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DaysCustomerHistory name="DaysCustomerHistory">DaysCustomerHistory</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DaysCustomerHistory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#daysTransactionsExists name="daysTransactionsExists">daysTransactionsExists</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the daysTransactionsExists attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DecimalNotRequiredForMinorCurrencyUnit name="DecimalNotRequiredForMinorCurrencyUnit">DecimalNotRequiredForMinorCurrencyUnit</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DecimalNotRequiredForMinorCurrencyUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#discountAtTotal name="discountAtTotal">discountAtTotal</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total discount</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the discountAtTotal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Total discount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#displaySecondaryTotalCurrency name="displaySecondaryTotalCurrency">displaySecondaryTotalCurrency</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the displaySecondaryTotalCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#endOfTransaction name="endOfTransaction">endOfTransaction</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>At end of transaction</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the endOfTransaction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>At end of transaction</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EODBankTotalsVerification name="EODBankTotalsVerification">EODBankTotalsVerification</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Verify bank totals</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EODBankTotalsVerification attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Verify bank totals</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#includeKitComponents name="includeKitComponents">includeKitComponents</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Show product kit details on receipt</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the includeKitComponents attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Show product kit details on receipt</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#itemNotOnFile name="itemNotOnFile">itemNotOnFile</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record not found</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the itemNotOnFile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Record not found</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#limitStaffListToStore name="limitStaffListToStore">limitStaffListToStore</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the limitStaffListToStore attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#lineItemTaxChange name="lineItemTaxChange">lineItemTaxChange</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Line product tax change</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the lineItemTaxChange attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Line product tax change</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ManualCalculateDiscounts name="ManualCalculateDiscounts">ManualCalculateDiscounts</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Manually calculate multiple item discounts</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ManualCalculateDiscounts attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Manually calculate multiple item discounts</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#markDown name="markDown">markDown</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Product discount</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the markDown attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Product discount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#markUp name="markUp">markUp</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Mark up</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the markUp attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Mark up</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#maximumPrice name="maximumPrice">maximumPrice</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Maximum price</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the maximumPrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Maximum price</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#maximumQuantity name="maximumQuantity">maximumQuantity</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Maximum quantity</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the maximumQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Maximum quantity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#maximumStoreTransLog name="maximumStoreTransLog">maximumStoreTransLog</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the maximumStoreTransLog attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#maxTransactionSearchResults name="maxTransactionSearchResults">maxTransactionSearchResults</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the maxTransactionSearchResults attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#minimumPasswordLength name="minimumPasswordLength">minimumPasswordLength</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the minimumPasswordLength attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#multibleItemSymbol name="multibleItemSymbol">multibleItemSymbol</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the multibleItemSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#mustKeyInPriceIfZero name="mustKeyInPriceIfZero">mustKeyInPriceIfZero</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the mustKeyInPriceIfZero attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#name name="name">name</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#negativeAdjustment name="negativeAdjustment">negativeAdjustment</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Negative adjustment</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the negativeAdjustment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Negative adjustment</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#negativeSalesLine name="negativeSalesLine">negativeSalesLine</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Return product</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the negativeSalesLine attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Return product</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#noSale name="noSale">noSale</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Open drawer</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the noSale attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Open drawer</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#noTaxUsed name="noTaxUsed">noTaxUsed</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the noTaxUsed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#overridePrice name="overridePrice">overridePrice</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Override price</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the overridePrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Override price</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PriceDecimalPlaces name="PriceDecimalPlaces">PriceDecimalPlaces</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Price decimal places</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceDecimalPlaces attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Price decimal places</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#priceRoundingTo name="priceRoundingTo">priceRoundingTo</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the priceRoundingTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#printXReportOnTerminal name="printXReportOnTerminal">printXReportOnTerminal</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the printXReportOnTerminal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#refundSale name="refundSale">refundSale</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Return transaction</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the refundSale attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Return transaction</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequireAmountDeclaration name="RequireAmountDeclaration">RequireAmountDeclaration</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequireAmountDeclaration attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailReceiptProfile name="RetailReceiptProfile">RetailReceiptProfile</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailReceiptProfile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#salesPerson name="salesPerson">salesPerson</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Add sales person</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the salesPerson attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Add sales person</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#salesPersonMode name="salesPersonMode">salesPersonMode</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the salesPersonMode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#secondaryTotalCurrency name="secondaryTotalCurrency">secondaryTotalCurrency</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the secondaryTotalCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#serialNumber name="serialNumber">serialNumber</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Serial number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the serialNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Serial number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#showStaffListAtLogOn name="showStaffListAtLogOn">showStaffListAtLogOn</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the showStaffListAtLogOn attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#skipTaxOnReceipt name="skipTaxOnReceipt">skipTaxOnReceipt</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the skipTaxOnReceipt attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#staffBarcodeLogon name="staffBarcodeLogon">staffBarcodeLogon</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the staffBarcodeLogon attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StaffBarcodeLogonRequiresPassword name="StaffBarcodeLogonRequiresPassword">StaffBarcodeLogonRequiresPassword</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StaffBarcodeLogonRequiresPassword attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#staffCardLogon name="staffCardLogon">staffCardLogon</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the staffCardLogon attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StaffCardLogonRequiresPassword name="StaffCardLogonRequiresPassword">StaffCardLogonRequiresPassword</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StaffCardLogonRequiresPassword attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#startOfTransaction name="startOfTransaction">startOfTransaction</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>At start of transaction</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the startOfTransaction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>At start of transaction</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#supportedCountryRegionISOCode name="supportedCountryRegionISOCode">supportedCountryRegionISOCode</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the supportedCountryRegionISOCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeAttendanceEnableRegistration name="TimeAttendanceEnableRegistration">TimeAttendanceEnableRegistration</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Enable time registrations</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeAttendanceEnableRegistration attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Enable time registrations</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#taxRegistrationNumberOnReceipt name="taxRegistrationNumberOnReceipt">taxRegistrationNumberOnReceipt</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the taxRegistrationNumberOnReceipt attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#tenderDeclaration name="tenderDeclaration">tenderDeclaration</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tender declaration</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the tenderDeclaration attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tender declaration</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#transactionDeleteReminder name="transactionDeleteReminder">transactionDeleteReminder</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the transactionDeleteReminder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#transactionTaxChange name="transactionTaxChange">transactionTaxChange</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transaction tax change</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the transactionTaxChange attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Transaction tax change</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#voidIsPressed name="voidIsPressed">voidIsPressed</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Void product</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the voidIsPressed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Void product</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#voidPayment name="voidPayment">voidPayment</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Void payment</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the voidPayment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Void payment</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#voidTransaction name="voidTransaction">voidTransaction</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Void transaction</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the voidTransaction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Void transaction</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#cancelReason name="cancelReason">cancelReason</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Voiding reason</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the cancelReason attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Voiding reason</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#contingencyReason name="contingencyReason">contingencyReason</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contingency reason</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the contingencyReason attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Contingency reason</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreateAsyncCustomers name="CreateAsyncCustomers">CreateAsyncCustomers</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreateAsyncCustomers attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesModeDefaultAsCustomerOrder name="SalesModeDefaultAsCustomerOrder">SalesModeDefaultAsCustomerOrder</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesModeDefaultAsCustomerOrder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AlwaysExpandTransactionScreenLineDetails name="AlwaysExpandTransactionScreenLineDetails">AlwaysExpandTransactionScreenLineDetails</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AlwaysExpandTransactionScreenLineDetails attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProhibitMixingSalesAndReturns name="ProhibitMixingSalesAndReturns">ProhibitMixingSalesAndReturns</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProhibitMixingSalesAndReturns attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProductSuggestionsEnabled name="IsProductSuggestionsEnabled">IsProductSuggestionsEnabled</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProductSuggestionsEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductSearchType name="ProductSearchType">ProductSearchType</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductSearchType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DenominationsToDisplay name="DenominationsToDisplay">DenominationsToDisplay</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DenominationsToDisplay attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RejectOrderFulfillment name="RejectOrderFulfillment">RejectOrderFulfillment</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reject order line</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RejectOrderFulfillment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reject order line</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EmployeeLogonType name="EmployeeLogonType">EmployeeLogonType</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Employee Logon Type</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmployeeLogonType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Employee Logon Type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NotificationRefreshInterval name="NotificationRefreshInterval">NotificationRefreshInterval</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NotificationRefreshInterval attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ManualTaxCalculation name="ManualTaxCalculation">ManualTaxCalculation</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ManualTaxCalculation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExcludeSalesOrderInvoices name="ExcludeSalesOrderInvoices">ExcludeSalesOrderInvoices</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExcludeSalesOrderInvoices attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IncludeFreeTextInvoices name="IncludeFreeTextInvoices">IncludeFreeTextInvoices</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IncludeFreeTextInvoices attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IncludeProjectInvoices name="IncludeProjectInvoices">IncludeProjectInvoices</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IncludeProjectInvoices attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IncludeCreditNoteInvoices name="IncludeCreditNoteInvoices">IncludeCreditNoteInvoices</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IncludeCreditNoteInvoices attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProcessNumber name="ProcessNumber">ProcessNumber</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcessNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GenerateLoyaltyCardNumber name="GenerateLoyaltyCardNumber">GenerateLoyaltyCardNumber</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GenerateLoyaltyCardNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrintVoidTransactionReceipts name="PrintVoidTransactionReceipts">PrintVoidTransactionReceipts</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintVoidTransactionReceipts attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ManualChargeCalculation name="ManualChargeCalculation">ManualChargeCalculation</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ManualChargeCalculation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VoidSuspendedTransactionsOnCloseShift name="VoidSuspendedTransactionsOnCloseShift">VoidSuspendedTransactionsOnCloseShift</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VoidSuspendedTransactionsOnCloseShift attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxExemptReceiptIndicator name="TaxExemptReceiptIndicator">TaxExemptReceiptIndicator</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxExemptReceiptIndicator attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DisplayTaxExemptInLineDetails name="DisplayTaxExemptInLineDetails">DisplayTaxExemptInLineDetails</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisplayTaxExemptInLineDetails attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseAdvancedCashManagement name="UseAdvancedCashManagement">UseAdvancedCashManagement</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseAdvancedCashManagement attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShiftReconciliation name="ShiftReconciliation">ShiftReconciliation</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShiftReconciliation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrintReceiptsOnCardDecline name="PrintReceiptsOnCardDecline">PrintReceiptsOnCardDecline</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintReceiptsOnCardDecline attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultCustomerSearchMode name="DefaultCustomerSearchMode">DefaultCustomerSearchMode</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultCustomerSearchMode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsFiscalCustomerRequiredForTransaction name="IsFiscalCustomerRequiredForTransaction">IsFiscalCustomerRequiredForTransaction</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsFiscalCustomerRequiredForTransaction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseFinancialReconcialiationInStore name="UseFinancialReconcialiationInStore">UseFinancialReconcialiationInStore</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseFinancialReconcialiationInStore attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CreateAsyncCustomerOrders name="CreateAsyncCustomerOrders">CreateAsyncCustomerOrders</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreateAsyncCustomerOrders attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequirePaymentForFulfillment name="RequirePaymentForFulfillment">RequirePaymentForFulfillment</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequirePaymentForFulfillment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_RetailFunctionalityProfileRelationshipId name="BackingTable_RetailFunctionalityProfileRelationshipId">BackingTable_RetailFunctionalityProfileRelationshipId</a>

First included in: BrickAndMortarStore/RetailFunctionalityProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailFunctionalityProfileRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../Tables/Commerce/ChannelManagement/BrickAndMortarStore/Group/RetailFunctionalityProfile.md" target="_blank">/core/operationsCommon/Tables/Commerce/ChannelManagement/BrickAndMortarStore/Group/RetailFunctionalityProfile.cdm.json/RetailFunctionalityProfile</a></td><td><a href="../../../../Tables/Commerce/ChannelManagement/BrickAndMortarStore/Group/RetailFunctionalityProfile.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
