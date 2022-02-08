---
title: RetailFunctionalityProfile in Group - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# POS functionality profile in Group(RetailFunctionalityProfile)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Commerce/ChannelManagement/BrickAndMortarStore/Group/RetailFunctionalityProfile.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailFunctionalityProfile/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

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
|[RecId](#RecId)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[profileId](#profileId)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[addTaxOnPrices](#addTaxOnPrices)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[aggregateItems](#aggregateItems)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[aggregateItemsForPrinting](#aggregateItemsForPrinting)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[aggregatePayments](#aggregatePayments)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[AmountDecimalPlaces](#AmountDecimalPlaces)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[amountRoundingTo](#amountRoundingTo)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[ApplyDiscountOnUnitPrices](#ApplyDiscountOnUnitPrices)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[AuditEnabled](#AuditEnabled)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[backupTrainingTransactions](#backupTrainingTransactions)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[blockedClosedAccount](#blockedClosedAccount)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[centralTableServer](#centralTableServer)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[centralTableServerPort](#centralTableServerPort)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[currencySymbol](#currencySymbol)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[DaysCustomerHistory](#DaysCustomerHistory)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[daysTransactionsExists](#daysTransactionsExists)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[DecimalNotRequiredForMinorCurrencyUnit](#DecimalNotRequiredForMinorCurrencyUnit)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[discountAtTotal](#discountAtTotal)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[displaySecondaryTotalCurrency](#displaySecondaryTotalCurrency)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[endOfTransaction](#endOfTransaction)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[EODBankTotalsVerification](#EODBankTotalsVerification)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[includeKitComponents](#includeKitComponents)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[itemNotOnFile](#itemNotOnFile)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[limitStaffListToStore](#limitStaffListToStore)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[lineItemTaxChange](#lineItemTaxChange)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[ManualCalculateDiscounts](#ManualCalculateDiscounts)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[markDown](#markDown)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[markUp](#markUp)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[maximumPrice](#maximumPrice)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[maximumQty](#maximumQty)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[maximumStoreTransLog](#maximumStoreTransLog)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[maxTransactionSearchResults](#maxTransactionSearchResults)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[minimumPasswordLength](#minimumPasswordLength)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[multibleItemSymbol](#multibleItemSymbol)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[mustKeyInPriceIfZero](#mustKeyInPriceIfZero)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[name](#name)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[negativeAdjustment](#negativeAdjustment)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[negativeSalesLine](#negativeSalesLine)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[noSale](#noSale)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[noTaxUsed](#noTaxUsed)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[overridePrice](#overridePrice)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[PriceDecimalPlaces](#PriceDecimalPlaces)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[priceRoundingTo](#priceRoundingTo)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[printXReportOnTerminal](#printXReportOnTerminal)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[refundSale](#refundSale)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[RequireAmountDeclaration](#RequireAmountDeclaration)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[RetailReceiptProfile](#RetailReceiptProfile)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[salesPerson](#salesPerson)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[salesPersonMode](#salesPersonMode)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[secondaryTotalCurrency](#secondaryTotalCurrency)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[serialNumber](#serialNumber)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[showStaffListAtLogOn](#showStaffListAtLogOn)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[skipTaxOnReceipt](#skipTaxOnReceipt)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[staffBarcodeLogon](#staffBarcodeLogon)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[StaffBarcodeLogonRequiresPassword](#StaffBarcodeLogonRequiresPassword)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[staffCardLogon](#staffCardLogon)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[StaffCardLogonRequiresPassword](#StaffCardLogonRequiresPassword)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[startOfTransaction](#startOfTransaction)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[supportedCountryRegionISOCode](#supportedCountryRegionISOCode)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[taEnableRegistration](#taEnableRegistration)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[taxRegistrationNumberOnReceipt](#taxRegistrationNumberOnReceipt)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[tenderDeclaration](#tenderDeclaration)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[transactionDeleteReminder](#transactionDeleteReminder)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[transactionTaxChange](#transactionTaxChange)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[TSCentralTableServer](#TSCentralTableServer)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[TSCustomer](#TSCustomer)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[TSDataEntries](#TSDataEntries)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[TSFloatingCashier](#TSFloatingCashier)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[TSInventoryLookup](#TSInventoryLookup)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[TSResendDelay](#TSResendDelay)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[TSSendTransactions](#TSSendTransactions)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[TSSendVoidTransactions](#TSSendVoidTransactions)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[TSStaff](#TSStaff)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[TSSuspendRetrieveTransactions](#TSSuspendRetrieveTransactions)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[TSTransactionResendLimit](#TSTransactionResendLimit)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[TSUpdateReplicationCounter](#TSUpdateReplicationCounter)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[voidIsPressed](#voidIsPressed)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[voidPayment](#voidPayment)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[voidTransaction](#voidTransaction)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[cancelReason](#cancelReason)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[contingencyReason](#contingencyReason)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[CreateOfflineCustomerOrders](#CreateOfflineCustomerOrders)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[CreateAsyncCustomers](#CreateAsyncCustomers)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[SearchCustomersInAx](#SearchCustomersInAx)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[PrintTenderDetailsOnXReport](#PrintTenderDetailsOnXReport)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[PromptForSalesRep](#PromptForSalesRep)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[RequireSalesRep](#RequireSalesRep)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[DefaultSalesRep](#DefaultSalesRep)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[SalesModeDefaultAsCustomerOrder](#SalesModeDefaultAsCustomerOrder)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[AlwaysExpandTransactionScreenLineDetails](#AlwaysExpandTransactionScreenLineDetails)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[ProhibitMixingSalesAndReturns](#ProhibitMixingSalesAndReturns)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[IsProductSuggestionsEnabled](#IsProductSuggestionsEnabled)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[ProductSearchType](#ProductSearchType)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[DenominationsToDisplay](#DenominationsToDisplay)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[RejectOrderFulfillment](#RejectOrderFulfillment)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[EmployeeLogonType](#EmployeeLogonType)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[notificationRefreshInterval](#notificationRefreshInterval)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[CustomerSearchDefault](#CustomerSearchDefault)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[CustomerSearchMode](#CustomerSearchMode)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[ShiftClosingCheck](#ShiftClosingCheck)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[ShiftClosingTime](#ShiftClosingTime)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[ShiftClosingInterval](#ShiftClosingInterval)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[ManualTaxCalculation](#ManualTaxCalculation)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[ExcludeSalesOrderInvoices](#ExcludeSalesOrderInvoices)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[IncludeFreeTextInvoices](#IncludeFreeTextInvoices)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[IncludeProjectInvoices](#IncludeProjectInvoices)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[IncludeCreditNoteInvoices](#IncludeCreditNoteInvoices)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[RegistrationProcessId](#RegistrationProcessId)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[GenerateLoyaltyCardNumber](#GenerateLoyaltyCardNumber)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[PrintVoidTransactionReceipts](#PrintVoidTransactionReceipts)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[ManualChargeCalculation](#ManualChargeCalculation)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[VoidSuspendedTransactionsOnCloseShift](#VoidSuspendedTransactionsOnCloseShift)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[CustomerAccountFloorLimit](#CustomerAccountFloorLimit)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[DisplayTaxExemptInLineDetails](#DisplayTaxExemptInLineDetails)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[TaxExemptReceiptIndicator](#TaxExemptReceiptIndicator)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[UseAdvancedCashManagement](#UseAdvancedCashManagement)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[PrintReceiptsOnCardDecline](#PrintReceiptsOnCardDecline)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[DefaultCustomerSearchMode](#DefaultCustomerSearchMode)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[IsFiscalCustomerRequiredForTransaction](#IsFiscalCustomerRequiredForTransaction)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[InventAvailabilityCalculationMode](#InventAvailabilityCalculationMode)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[UseFinancialReconcialiationInStore](#UseFinancialReconcialiationInStore)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[RequirePaymentForFulfillment](#RequirePaymentForFulfillment)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[Relationship_CurrencyRelationshipId](#Relationship_CurrencyRelationshipId)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[Relationship_RetailInfocodeTableRelationshipId](#Relationship_RetailInfocodeTableRelationshipId)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[Relationship_RetailInfocodeTable1RelationshipId](#Relationship_RetailInfocodeTable1RelationshipId)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[Relationship_RetailInfocodeTable10RelationshipId](#Relationship_RetailInfocodeTable10RelationshipId)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[Relationship_RetailInfocodeTable11RelationshipId](#Relationship_RetailInfocodeTable11RelationshipId)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[Relationship_RetailInfocodeTable12RelationshipId](#Relationship_RetailInfocodeTable12RelationshipId)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[Relationship_RetailInfocodeTable13RelationshipId](#Relationship_RetailInfocodeTable13RelationshipId)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[Relationship_RetailInfocodeTable14RelationshipId](#Relationship_RetailInfocodeTable14RelationshipId)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[Relationship_RetailInfocodeTable15RelationshipId](#Relationship_RetailInfocodeTable15RelationshipId)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[Relationship_RetailInfocodeTable16RelationshipId](#Relationship_RetailInfocodeTable16RelationshipId)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[Relationship_RetailInfocodeTable17RelationshipId](#Relationship_RetailInfocodeTable17RelationshipId)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[Relationship_RetailInfocodeTable18RelationshipId](#Relationship_RetailInfocodeTable18RelationshipId)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[Relationship_RetailInfocodeTable2RelationshipId](#Relationship_RetailInfocodeTable2RelationshipId)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[Relationship_RetailInfocodeTable3RelationshipId](#Relationship_RetailInfocodeTable3RelationshipId)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[Relationship_RetailInfocodeTable4RelationshipId](#Relationship_RetailInfocodeTable4RelationshipId)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[Relationship_RetailInfocodeTable5RelationshipId](#Relationship_RetailInfocodeTable5RelationshipId)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[Relationship_RetailInfocodeTable6RelationshipId](#Relationship_RetailInfocodeTable6RelationshipId)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[Relationship_RetailInfocodeTable7RelationshipId](#Relationship_RetailInfocodeTable7RelationshipId)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[Relationship_RetailInfocodeTable8RelationshipId](#Relationship_RetailInfocodeTable8RelationshipId)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[Relationship_RetailInfocodeTable9RelationshipId](#Relationship_RetailInfocodeTable9RelationshipId)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[Relationship_RetailReceiptProfileRelationshipId](#Relationship_RetailReceiptProfileRelationshipId)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[Relationship_RetailInfocodeTable19RelationshipId](#Relationship_RetailInfocodeTable19RelationshipId)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[Relationship_RetailInfocodeTable20RelationshipId](#Relationship_RetailInfocodeTable20RelationshipId)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[Relationship_RetailInfocodeTable21RelationshipId](#Relationship_RetailInfocodeTable21RelationshipId)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|
|[Relationship_RetailInfocodeTable22RelationshipId](#Relationship_RetailInfocodeTable22RelationshipId)||<a href="RetailFunctionalityProfile.md" target="_blank">Group/RetailFunctionalityProfile</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailFunctionalityProfile/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#profileId name="profileId">profileId</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the profileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#addTaxOnPrices name="addTaxOnPrices">addTaxOnPrices</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the addTaxOnPrices attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#aggregateItems name="aggregateItems">aggregateItems</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the aggregateItems attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#aggregateItemsForPrinting name="aggregateItemsForPrinting">aggregateItemsForPrinting</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the aggregateItemsForPrinting attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#aggregatePayments name="aggregatePayments">aggregatePayments</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the aggregatePayments attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#AmountDecimalPlaces name="AmountDecimalPlaces">AmountDecimalPlaces</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

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

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the amountRoundingTo attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ApplyDiscountOnUnitPrices name="ApplyDiscountOnUnitPrices">ApplyDiscountOnUnitPrices</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Apply discounts to unit price</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ApplyDiscountOnUnitPrices attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Apply discounts to unit price</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#AuditEnabled name="AuditEnabled">AuditEnabled</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AuditEnabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#backupTrainingTransactions name="backupTrainingTransactions">backupTrainingTransactions</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the backupTrainingTransactions attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#blockedClosedAccount name="blockedClosedAccount">blockedClosedAccount</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the blockedClosedAccount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#centralTableServer name="centralTableServer">centralTableServer</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

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

First included in: Group/RetailFunctionalityProfile (this entity)  

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

First included in: Group/RetailFunctionalityProfile (this entity)  

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

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DaysCustomerHistory attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#daysTransactionsExists name="daysTransactionsExists">daysTransactionsExists</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the daysTransactionsExists attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DecimalNotRequiredForMinorCurrencyUnit name="DecimalNotRequiredForMinorCurrencyUnit">DecimalNotRequiredForMinorCurrencyUnit</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DecimalNotRequiredForMinorCurrencyUnit attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#discountAtTotal name="discountAtTotal">discountAtTotal</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

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

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the displaySecondaryTotalCurrency attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#endOfTransaction name="endOfTransaction">endOfTransaction</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

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

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Verify bank totals</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EODBankTotalsVerification attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Verify bank totals</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#includeKitComponents name="includeKitComponents">includeKitComponents</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Show product kit details on receipt</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the includeKitComponents attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Show product kit details on receipt</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#itemNotOnFile name="itemNotOnFile">itemNotOnFile</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

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

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the limitStaffListToStore attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#lineItemTaxChange name="lineItemTaxChange">lineItemTaxChange</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

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

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Manually calculate multiple item discounts</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ManualCalculateDiscounts attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Manually calculate multiple item discounts</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#markDown name="markDown">markDown</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

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

First included in: Group/RetailFunctionalityProfile (this entity)  

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

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Maximum price</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the maximumPrice attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Maximum price</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#maximumQty name="maximumQty">maximumQty</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Maximum quantity</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the maximumQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Maximum quantity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#maximumStoreTransLog name="maximumStoreTransLog">maximumStoreTransLog</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the maximumStoreTransLog attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#maxTransactionSearchResults name="maxTransactionSearchResults">maxTransactionSearchResults</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the maxTransactionSearchResults attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#minimumPasswordLength name="minimumPasswordLength">minimumPasswordLength</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the minimumPasswordLength attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#multibleItemSymbol name="multibleItemSymbol">multibleItemSymbol</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

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

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the mustKeyInPriceIfZero attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#name name="name">name</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

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

First included in: Group/RetailFunctionalityProfile (this entity)  

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

First included in: Group/RetailFunctionalityProfile (this entity)  

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

First included in: Group/RetailFunctionalityProfile (this entity)  

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

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the noTaxUsed attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#overridePrice name="overridePrice">overridePrice</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

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

First included in: Group/RetailFunctionalityProfile (this entity)  

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

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the priceRoundingTo attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#printXReportOnTerminal name="printXReportOnTerminal">printXReportOnTerminal</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the printXReportOnTerminal attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#refundSale name="refundSale">refundSale</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

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

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequireAmountDeclaration attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RetailReceiptProfile name="RetailReceiptProfile">RetailReceiptProfile</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

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

First included in: Group/RetailFunctionalityProfile (this entity)  

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

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the salesPersonMode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#secondaryTotalCurrency name="secondaryTotalCurrency">secondaryTotalCurrency</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

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

First included in: Group/RetailFunctionalityProfile (this entity)  

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

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the showStaffListAtLogOn attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#skipTaxOnReceipt name="skipTaxOnReceipt">skipTaxOnReceipt</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the skipTaxOnReceipt attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#staffBarcodeLogon name="staffBarcodeLogon">staffBarcodeLogon</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the staffBarcodeLogon attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#StaffBarcodeLogonRequiresPassword name="StaffBarcodeLogonRequiresPassword">StaffBarcodeLogonRequiresPassword</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StaffBarcodeLogonRequiresPassword attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#staffCardLogon name="staffCardLogon">staffCardLogon</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the staffCardLogon attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#StaffCardLogonRequiresPassword name="StaffCardLogonRequiresPassword">StaffCardLogonRequiresPassword</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StaffCardLogonRequiresPassword attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#startOfTransaction name="startOfTransaction">startOfTransaction</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

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

First included in: Group/RetailFunctionalityProfile (this entity)  

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

### <a href=#taEnableRegistration name="taEnableRegistration">taEnableRegistration</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Enable time registrations</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the taEnableRegistration attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Enable time registrations</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#taxRegistrationNumberOnReceipt name="taxRegistrationNumberOnReceipt">taxRegistrationNumberOnReceipt</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the taxRegistrationNumberOnReceipt attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#tenderDeclaration name="tenderDeclaration">tenderDeclaration</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

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

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the transactionDeleteReminder attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#transactionTaxChange name="transactionTaxChange">transactionTaxChange</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

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

### <a href=#TSCentralTableServer name="TSCentralTableServer">TSCentralTableServer</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Commerce Data Exchange: Real-time Service central table server</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TSCentralTableServer attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Commerce Data Exchange: Real-time Service central table server</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#TSCustomer name="TSCustomer">TSCustomer</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Commerce Data Exchange: Real-time Service customer</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TSCustomer attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Commerce Data Exchange: Real-time Service customer</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#TSDataEntries name="TSDataEntries">TSDataEntries</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Commerce Data Exchange: Real-time Service data entries</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TSDataEntries attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Commerce Data Exchange: Real-time Service data entries</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#TSFloatingCashier name="TSFloatingCashier">TSFloatingCashier</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Commerce Data Exchange: Real-time Service floating cashier</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TSFloatingCashier attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Commerce Data Exchange: Real-time Service floating cashier</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#TSInventoryLookup name="TSInventoryLookup">TSInventoryLookup</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Commerce Data Exchange: Real-time Service inventory lookup</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TSInventoryLookup attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Commerce Data Exchange: Real-time Service inventory lookup</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#TSResendDelay name="TSResendDelay">TSResendDelay</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Commerce Data Exchange: Real-time Service resend delay</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TSResendDelay attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Commerce Data Exchange: Real-time Service resend delay</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#TSSendTransactions name="TSSendTransactions">TSSendTransactions</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Commerce Data Exchange: Real-time Service send transactions</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TSSendTransactions attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Commerce Data Exchange: Real-time Service send transactions</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#TSSendVoidTransactions name="TSSendVoidTransactions">TSSendVoidTransactions</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Commerce Data Exchange: Real-time Service send void transactions</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TSSendVoidTransactions attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Commerce Data Exchange: Real-time Service send void transactions</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#TSStaff name="TSStaff">TSStaff</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Commerce Data Exchange: Real-time Service staff</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TSStaff attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Commerce Data Exchange: Real-time Service staff</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#TSSuspendRetrieveTransactions name="TSSuspendRetrieveTransactions">TSSuspendRetrieveTransactions</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Commerce Data Exchange: Real-time Service suspend retrieve transactions</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TSSuspendRetrieveTransactions attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Commerce Data Exchange: Real-time Service suspend retrieve transactions</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#TSTransactionResendLimit name="TSTransactionResendLimit">TSTransactionResendLimit</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Commerce Data Exchange: Real-time Service transaction resend limit</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TSTransactionResendLimit attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Commerce Data Exchange: Real-time Service transaction resend limit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#TSUpdateReplicationCounter name="TSUpdateReplicationCounter">TSUpdateReplicationCounter</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Commerce Data Exchange: Real-time Service update replication counter</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TSUpdateReplicationCounter attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Commerce Data Exchange: Real-time Service update replication counter</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#voidIsPressed name="voidIsPressed">voidIsPressed</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

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

First included in: Group/RetailFunctionalityProfile (this entity)  

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

First included in: Group/RetailFunctionalityProfile (this entity)  

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

First included in: Group/RetailFunctionalityProfile (this entity)  

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

First included in: Group/RetailFunctionalityProfile (this entity)  

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

### <a href=#CreateOfflineCustomerOrders name="CreateOfflineCustomerOrders">CreateOfflineCustomerOrders</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Create customer order in async mode</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreateOfflineCustomerOrders attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Create customer order in async mode</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#CreateAsyncCustomers name="CreateAsyncCustomers">CreateAsyncCustomers</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreateAsyncCustomers attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#SearchCustomersInAx name="SearchCustomersInAx">SearchCustomersInAx</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SearchCustomersInAx attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PrintTenderDetailsOnXReport name="PrintTenderDetailsOnXReport">PrintTenderDetailsOnXReport</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintTenderDetailsOnXReport attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PromptForSalesRep name="PromptForSalesRep">PromptForSalesRep</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Prompt for sales representative</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PromptForSalesRep attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Prompt for sales representative</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#RequireSalesRep name="RequireSalesRep">RequireSalesRep</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Require sales representative</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequireSalesRep attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Require sales representative</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#DefaultSalesRep name="DefaultSalesRep">DefaultSalesRep</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default to cashier when available</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultSalesRep attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Default to cashier when available</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#SalesModeDefaultAsCustomerOrder name="SalesModeDefaultAsCustomerOrder">SalesModeDefaultAsCustomerOrder</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesModeDefaultAsCustomerOrder attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#AlwaysExpandTransactionScreenLineDetails name="AlwaysExpandTransactionScreenLineDetails">AlwaysExpandTransactionScreenLineDetails</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AlwaysExpandTransactionScreenLineDetails attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ProhibitMixingSalesAndReturns name="ProhibitMixingSalesAndReturns">ProhibitMixingSalesAndReturns</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProhibitMixingSalesAndReturns attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#IsProductSuggestionsEnabled name="IsProductSuggestionsEnabled">IsProductSuggestionsEnabled</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProductSuggestionsEnabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ProductSearchType name="ProductSearchType">ProductSearchType</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Match search terms</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductSearchType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Match search terms</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#DenominationsToDisplay name="DenominationsToDisplay">DenominationsToDisplay</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Denominations to display</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DenominationsToDisplay attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Denominations to display</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#RejectOrderFulfillment name="RejectOrderFulfillment">RejectOrderFulfillment</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

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

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Logon Authentication Method</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmployeeLogonType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Logon Authentication Method</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#notificationRefreshInterval name="notificationRefreshInterval">notificationRefreshInterval</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Refresh interval (in minutes)</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the notificationRefreshInterval attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Refresh interval (in minutes)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#CustomerSearchDefault name="CustomerSearchDefault">CustomerSearchDefault</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerSearchDefault attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CustomerSearchMode name="CustomerSearchMode">CustomerSearchMode</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerSearchMode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShiftClosingCheck name="ShiftClosingCheck">ShiftClosingCheck</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShiftClosingCheck attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShiftClosingTime name="ShiftClosingTime">ShiftClosingTime</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShiftClosingTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
</details>

### <a href=#ShiftClosingInterval name="ShiftClosingInterval">ShiftClosingInterval</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShiftClosingInterval attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ManualTaxCalculation name="ManualTaxCalculation">ManualTaxCalculation</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Manual tax calculation</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ManualTaxCalculation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Manual tax calculation</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ExcludeSalesOrderInvoices name="ExcludeSalesOrderInvoices">ExcludeSalesOrderInvoices</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExcludeSalesOrderInvoices attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#IncludeFreeTextInvoices name="IncludeFreeTextInvoices">IncludeFreeTextInvoices</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IncludeFreeTextInvoices attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#IncludeProjectInvoices name="IncludeProjectInvoices">IncludeProjectInvoices</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IncludeProjectInvoices attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#IncludeCreditNoteInvoices name="IncludeCreditNoteInvoices">IncludeCreditNoteInvoices</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IncludeCreditNoteInvoices attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RegistrationProcessId name="RegistrationProcessId">RegistrationProcessId</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RegistrationProcessId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GenerateLoyaltyCardNumber name="GenerateLoyaltyCardNumber">GenerateLoyaltyCardNumber</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GenerateLoyaltyCardNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PrintVoidTransactionReceipts name="PrintVoidTransactionReceipts">PrintVoidTransactionReceipts</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintVoidTransactionReceipts attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ManualChargeCalculation name="ManualChargeCalculation">ManualChargeCalculation</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ManualChargeCalculation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#VoidSuspendedTransactionsOnCloseShift name="VoidSuspendedTransactionsOnCloseShift">VoidSuspendedTransactionsOnCloseShift</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VoidSuspendedTransactionsOnCloseShift attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CustomerAccountFloorLimit name="CustomerAccountFloorLimit">CustomerAccountFloorLimit</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerAccountFloorLimit attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DisplayTaxExemptInLineDetails name="DisplayTaxExemptInLineDetails">DisplayTaxExemptInLineDetails</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisplayTaxExemptInLineDetails attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TaxExemptReceiptIndicator name="TaxExemptReceiptIndicator">TaxExemptReceiptIndicator</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

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

### <a href=#UseAdvancedCashManagement name="UseAdvancedCashManagement">UseAdvancedCashManagement</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseAdvancedCashManagement attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PrintReceiptsOnCardDecline name="PrintReceiptsOnCardDecline">PrintReceiptsOnCardDecline</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Print card decline receipt</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintReceiptsOnCardDecline attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Print card decline receipt</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#DefaultCustomerSearchMode name="DefaultCustomerSearchMode">DefaultCustomerSearchMode</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultCustomerSearchMode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#IsFiscalCustomerRequiredForTransaction name="IsFiscalCustomerRequiredForTransaction">IsFiscalCustomerRequiredForTransaction</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsFiscalCustomerRequiredForTransaction attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#InventAvailabilityCalculationMode name="InventAvailabilityCalculationMode">InventAvailabilityCalculationMode</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Inventory availability calculation mode</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventAvailabilityCalculationMode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Inventory availability calculation mode</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#UseFinancialReconcialiationInStore name="UseFinancialReconcialiationInStore">UseFinancialReconcialiationInStore</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseFinancialReconcialiationInStore attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RequirePaymentForFulfillment name="RequirePaymentForFulfillment">RequirePaymentForFulfillment</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequirePaymentForFulfillment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Relationship_CurrencyRelationshipId name="Relationship_CurrencyRelationshipId">Relationship_CurrencyRelationshipId</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../../Common/Currency/Group/Currency.md" target="_blank">/core/operationsCommon/Tables/Common/Currency/Group/Currency.cdm.json/Currency</a></td><td><a href="../../../../Common/Currency/Group/Currency.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailInfocodeTableRelationshipId name="Relationship_RetailInfocodeTableRelationshipId">Relationship_RetailInfocodeTableRelationshipId</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailInfocodeTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../TransactionsAndOrders/Main/RetailInfocode.md" target="_blank">/core/operationsCommon/Tables/Commerce/TransactionsAndOrders/Main/RetailInfocode.cdm.json/RetailInfocode</a></td><td><a href="../../../TransactionsAndOrders/Main/RetailInfocode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailInfocodeTable1RelationshipId name="Relationship_RetailInfocodeTable1RelationshipId">Relationship_RetailInfocodeTable1RelationshipId</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailInfocodeTable1RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../TransactionsAndOrders/Main/RetailInfocode.md" target="_blank">/core/operationsCommon/Tables/Commerce/TransactionsAndOrders/Main/RetailInfocode.cdm.json/RetailInfocode</a></td><td><a href="../../../TransactionsAndOrders/Main/RetailInfocode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailInfocodeTable10RelationshipId name="Relationship_RetailInfocodeTable10RelationshipId">Relationship_RetailInfocodeTable10RelationshipId</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailInfocodeTable10RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../TransactionsAndOrders/Main/RetailInfocode.md" target="_blank">/core/operationsCommon/Tables/Commerce/TransactionsAndOrders/Main/RetailInfocode.cdm.json/RetailInfocode</a></td><td><a href="../../../TransactionsAndOrders/Main/RetailInfocode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailInfocodeTable11RelationshipId name="Relationship_RetailInfocodeTable11RelationshipId">Relationship_RetailInfocodeTable11RelationshipId</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailInfocodeTable11RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../TransactionsAndOrders/Main/RetailInfocode.md" target="_blank">/core/operationsCommon/Tables/Commerce/TransactionsAndOrders/Main/RetailInfocode.cdm.json/RetailInfocode</a></td><td><a href="../../../TransactionsAndOrders/Main/RetailInfocode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailInfocodeTable12RelationshipId name="Relationship_RetailInfocodeTable12RelationshipId">Relationship_RetailInfocodeTable12RelationshipId</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailInfocodeTable12RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../TransactionsAndOrders/Main/RetailInfocode.md" target="_blank">/core/operationsCommon/Tables/Commerce/TransactionsAndOrders/Main/RetailInfocode.cdm.json/RetailInfocode</a></td><td><a href="../../../TransactionsAndOrders/Main/RetailInfocode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailInfocodeTable13RelationshipId name="Relationship_RetailInfocodeTable13RelationshipId">Relationship_RetailInfocodeTable13RelationshipId</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailInfocodeTable13RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../TransactionsAndOrders/Main/RetailInfocode.md" target="_blank">/core/operationsCommon/Tables/Commerce/TransactionsAndOrders/Main/RetailInfocode.cdm.json/RetailInfocode</a></td><td><a href="../../../TransactionsAndOrders/Main/RetailInfocode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailInfocodeTable14RelationshipId name="Relationship_RetailInfocodeTable14RelationshipId">Relationship_RetailInfocodeTable14RelationshipId</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailInfocodeTable14RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../TransactionsAndOrders/Main/RetailInfocode.md" target="_blank">/core/operationsCommon/Tables/Commerce/TransactionsAndOrders/Main/RetailInfocode.cdm.json/RetailInfocode</a></td><td><a href="../../../TransactionsAndOrders/Main/RetailInfocode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailInfocodeTable15RelationshipId name="Relationship_RetailInfocodeTable15RelationshipId">Relationship_RetailInfocodeTable15RelationshipId</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailInfocodeTable15RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../TransactionsAndOrders/Main/RetailInfocode.md" target="_blank">/core/operationsCommon/Tables/Commerce/TransactionsAndOrders/Main/RetailInfocode.cdm.json/RetailInfocode</a></td><td><a href="../../../TransactionsAndOrders/Main/RetailInfocode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailInfocodeTable16RelationshipId name="Relationship_RetailInfocodeTable16RelationshipId">Relationship_RetailInfocodeTable16RelationshipId</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailInfocodeTable16RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../TransactionsAndOrders/Main/RetailInfocode.md" target="_blank">/core/operationsCommon/Tables/Commerce/TransactionsAndOrders/Main/RetailInfocode.cdm.json/RetailInfocode</a></td><td><a href="../../../TransactionsAndOrders/Main/RetailInfocode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailInfocodeTable17RelationshipId name="Relationship_RetailInfocodeTable17RelationshipId">Relationship_RetailInfocodeTable17RelationshipId</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailInfocodeTable17RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../TransactionsAndOrders/Main/RetailInfocode.md" target="_blank">/core/operationsCommon/Tables/Commerce/TransactionsAndOrders/Main/RetailInfocode.cdm.json/RetailInfocode</a></td><td><a href="../../../TransactionsAndOrders/Main/RetailInfocode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailInfocodeTable18RelationshipId name="Relationship_RetailInfocodeTable18RelationshipId">Relationship_RetailInfocodeTable18RelationshipId</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailInfocodeTable18RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../TransactionsAndOrders/Main/RetailInfocode.md" target="_blank">/core/operationsCommon/Tables/Commerce/TransactionsAndOrders/Main/RetailInfocode.cdm.json/RetailInfocode</a></td><td><a href="../../../TransactionsAndOrders/Main/RetailInfocode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailInfocodeTable2RelationshipId name="Relationship_RetailInfocodeTable2RelationshipId">Relationship_RetailInfocodeTable2RelationshipId</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailInfocodeTable2RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../TransactionsAndOrders/Main/RetailInfocode.md" target="_blank">/core/operationsCommon/Tables/Commerce/TransactionsAndOrders/Main/RetailInfocode.cdm.json/RetailInfocode</a></td><td><a href="../../../TransactionsAndOrders/Main/RetailInfocode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailInfocodeTable3RelationshipId name="Relationship_RetailInfocodeTable3RelationshipId">Relationship_RetailInfocodeTable3RelationshipId</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailInfocodeTable3RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../TransactionsAndOrders/Main/RetailInfocode.md" target="_blank">/core/operationsCommon/Tables/Commerce/TransactionsAndOrders/Main/RetailInfocode.cdm.json/RetailInfocode</a></td><td><a href="../../../TransactionsAndOrders/Main/RetailInfocode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailInfocodeTable4RelationshipId name="Relationship_RetailInfocodeTable4RelationshipId">Relationship_RetailInfocodeTable4RelationshipId</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailInfocodeTable4RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../TransactionsAndOrders/Main/RetailInfocode.md" target="_blank">/core/operationsCommon/Tables/Commerce/TransactionsAndOrders/Main/RetailInfocode.cdm.json/RetailInfocode</a></td><td><a href="../../../TransactionsAndOrders/Main/RetailInfocode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailInfocodeTable5RelationshipId name="Relationship_RetailInfocodeTable5RelationshipId">Relationship_RetailInfocodeTable5RelationshipId</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailInfocodeTable5RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../TransactionsAndOrders/Main/RetailInfocode.md" target="_blank">/core/operationsCommon/Tables/Commerce/TransactionsAndOrders/Main/RetailInfocode.cdm.json/RetailInfocode</a></td><td><a href="../../../TransactionsAndOrders/Main/RetailInfocode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailInfocodeTable6RelationshipId name="Relationship_RetailInfocodeTable6RelationshipId">Relationship_RetailInfocodeTable6RelationshipId</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailInfocodeTable6RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../TransactionsAndOrders/Main/RetailInfocode.md" target="_blank">/core/operationsCommon/Tables/Commerce/TransactionsAndOrders/Main/RetailInfocode.cdm.json/RetailInfocode</a></td><td><a href="../../../TransactionsAndOrders/Main/RetailInfocode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailInfocodeTable7RelationshipId name="Relationship_RetailInfocodeTable7RelationshipId">Relationship_RetailInfocodeTable7RelationshipId</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailInfocodeTable7RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../TransactionsAndOrders/Main/RetailInfocode.md" target="_blank">/core/operationsCommon/Tables/Commerce/TransactionsAndOrders/Main/RetailInfocode.cdm.json/RetailInfocode</a></td><td><a href="../../../TransactionsAndOrders/Main/RetailInfocode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailInfocodeTable8RelationshipId name="Relationship_RetailInfocodeTable8RelationshipId">Relationship_RetailInfocodeTable8RelationshipId</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailInfocodeTable8RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../TransactionsAndOrders/Main/RetailInfocode.md" target="_blank">/core/operationsCommon/Tables/Commerce/TransactionsAndOrders/Main/RetailInfocode.cdm.json/RetailInfocode</a></td><td><a href="../../../TransactionsAndOrders/Main/RetailInfocode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailInfocodeTable9RelationshipId name="Relationship_RetailInfocodeTable9RelationshipId">Relationship_RetailInfocodeTable9RelationshipId</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailInfocodeTable9RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../TransactionsAndOrders/Main/RetailInfocode.md" target="_blank">/core/operationsCommon/Tables/Commerce/TransactionsAndOrders/Main/RetailInfocode.cdm.json/RetailInfocode</a></td><td><a href="../../../TransactionsAndOrders/Main/RetailInfocode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailReceiptProfileRelationshipId name="Relationship_RetailReceiptProfileRelationshipId">Relationship_RetailReceiptProfileRelationshipId</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailReceiptProfileRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/RetailReceiptProfile.md" target="_blank">/core/operationsCommon/Tables/Commerce/ChannelManagement/BrickAndMortarStore/Miscellaneous/RetailReceiptProfile.cdm.json/RetailReceiptProfile</a></td><td><a href="../Miscellaneous/RetailReceiptProfile.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailInfocodeTable19RelationshipId name="Relationship_RetailInfocodeTable19RelationshipId">Relationship_RetailInfocodeTable19RelationshipId</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailInfocodeTable19RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../TransactionsAndOrders/Main/RetailInfocode.md" target="_blank">/core/operationsCommon/Tables/Commerce/TransactionsAndOrders/Main/RetailInfocode.cdm.json/RetailInfocode</a></td><td><a href="../../../TransactionsAndOrders/Main/RetailInfocode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailInfocodeTable20RelationshipId name="Relationship_RetailInfocodeTable20RelationshipId">Relationship_RetailInfocodeTable20RelationshipId</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailInfocodeTable20RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../TransactionsAndOrders/Main/RetailInfocode.md" target="_blank">/core/operationsCommon/Tables/Commerce/TransactionsAndOrders/Main/RetailInfocode.cdm.json/RetailInfocode</a></td><td><a href="../../../TransactionsAndOrders/Main/RetailInfocode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailInfocodeTable21RelationshipId name="Relationship_RetailInfocodeTable21RelationshipId">Relationship_RetailInfocodeTable21RelationshipId</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailInfocodeTable21RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../TransactionsAndOrders/Main/RetailInfocode.md" target="_blank">/core/operationsCommon/Tables/Commerce/TransactionsAndOrders/Main/RetailInfocode.cdm.json/RetailInfocode</a></td><td><a href="../../../TransactionsAndOrders/Main/RetailInfocode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailInfocodeTable22RelationshipId name="Relationship_RetailInfocodeTable22RelationshipId">Relationship_RetailInfocodeTable22RelationshipId</a>

First included in: Group/RetailFunctionalityProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailInfocodeTable22RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../TransactionsAndOrders/Main/RetailInfocode.md" target="_blank">/core/operationsCommon/Tables/Commerce/TransactionsAndOrders/Main/RetailInfocode.cdm.json/RetailInfocode</a></td><td><a href="../../../TransactionsAndOrders/Main/RetailInfocode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
