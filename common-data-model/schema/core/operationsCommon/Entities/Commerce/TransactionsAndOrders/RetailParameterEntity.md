---
title: RetailParameterEntity in TransactionsAndOrders - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Retail Headquarters parameters in TransactionsAndOrders(RetailParameterEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Commerce/TransactionsAndOrders/RetailParameterEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Retail Headquarters parameters</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[PrePaymentLedgerJournalName](#PrePaymentLedgerJournalName)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[MixAndMatchActivityType](#MixAndMatchActivityType)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[AccountExportProfile](#AccountExportProfile)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[AggregateBeforePosting](#AggregateBeforePosting)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[AutoSettle](#AutoSettle)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[BuyersPushRespectAssortments](#BuyersPushRespectAssortments)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[CancellationCharge](#CancellationCharge)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[CancellationChargeCode](#CancellationChargeCode)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[CrossDockingRespectAssortments](#CrossDockingRespectAssortments)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[DefaultCustomerPosting](#DefaultCustomerPosting)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[DefaultInventoryJournalName](#DefaultInventoryJournalName)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[DefaultJournalName4CategoryPrice](#DefaultJournalName4CategoryPrice)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[DefaultOrdertype](#DefaultOrdertype)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[DefaultRCashJournalName](#DefaultRCashJournalName)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[DetailSummary](#DetailSummary)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[DiscountAccountLedgerDimension](#DiscountAccountLedgerDimension)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[DiscountOfferActivityType](#DiscountOfferActivityType)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[EANLicenseNo](#EANLicenseNo)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[ElectronicDeliveryModeCode](#ElectronicDeliveryModeCode)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[EventNotificationProfileId](#EventNotificationProfileId)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[ExpirationDate](#ExpirationDate)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[GiftCardCompany](#GiftCardCompany)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[GiftcardItem](#GiftcardItem)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[GiftCardLedgerJournalName](#GiftCardLedgerJournalName)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[InventoryLocationIdForInventory](#InventoryLocationIdForInventory)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[InventoryLocationIdForPurchaseOrder](#InventoryLocationIdForPurchaseOrder)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[InventoryLocationIdForSalesOrder](#InventoryLocationIdForSalesOrder)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[ItemLabelLastAction](#ItemLabelLastAction)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[ItemLabelsForNegativeStock](#ItemLabelsForNegativeStock)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[ItemSalesStatisticsOn](#ItemSalesStatisticsOn)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[JournalNameForKitPricing](#JournalNameForKitPricing)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[Key](#Key)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[LedgerAccountType](#LedgerAccountType)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[MaxSalesOrdersPerTask](#MaxSalesOrdersPerTask)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[CallCenterGiftCardVoidJournalName](#CallCenterGiftCardVoidJournalName)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[MinimumDepositForSalesOrder](#MinimumDepositForSalesOrder)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[MinimumPasswordLength](#MinimumPasswordLength)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[MixMatchLedgerDimension](#MixMatchLedgerDimension)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[MultibuyActivityType](#MultibuyActivityType)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[MultiBuyLedgerDimension](#MultiBuyLedgerDimension)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[OfferLedgerDimension](#OfferLedgerDimension)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[OverrideSystemLookup](#OverrideSystemLookup)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[ParallelSalesOrderPosting](#ParallelSalesOrderPosting)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[Payment](#Payment)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[PaymentStatistics](#PaymentStatistics)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[PaymentMode](#PaymentMode)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[PickUpDeliveryModeCode](#PickUpDeliveryModeCode)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[PostBankedSum](#PostBankedSum)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[PostCustomerDiscount](#PostCustomerDiscount)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[PostInfocodeDiscount](#PostInfocodeDiscount)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[PostLineDiscount](#PostLineDiscount)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[PostPeriodicDiscount](#PostPeriodicDiscount)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[PostSafeSum](#PostSafeSum)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[PostSalesOrderWhenPaid](#PostSalesOrderWhenPaid)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[PostTotalDiscount](#PostTotalDiscount)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[PrepaymentLedgerDimension](#PrepaymentLedgerDimension)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[ReceiptEmailFilename](#ReceiptEmailFilename)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[ReceiptEmailSubject](#ReceiptEmailSubject)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[ReceiptEmailText](#ReceiptEmailText)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[ReceiptOption](#ReceiptOption)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[ReplenishmentAssortmentsCoverageDays](#ReplenishmentAssortmentsCoverageDays)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[RequireNumericCharacter](#RequireNumericCharacter)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[RequireSpecialCharacter](#RequireSpecialCharacter)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[RequireUppercase](#RequireUppercase)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[ReturnDispositionCodeId](#ReturnDispositionCodeId)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[ShelfLabelLastAction](#ShelfLabelLastAction)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[ShippingChargeCode](#ShippingChargeCode)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[StaffStatistics](#StaffStatistics)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[SystemInUse](#SystemInUse)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[TerminalStatistics](#TerminalStatistics)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[ThresholdLedgerDimension](#ThresholdLedgerDimension)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[TotalDiscountLedgerDimension](#TotalDiscountLedgerDimension)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[UseDefaultLedgerAccount](#UseDefaultLedgerAccount)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[UseDefaultTradeDates](#UseDefaultTradeDates)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[UseRetailReturnTaxGroup](#UseRetailReturnTaxGroup)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[WishListInvitationEmailId](#WishListInvitationEmailId)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[GiftCardClosingLedgerDimension](#GiftCardClosingLedgerDimension)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[ItemLabelSetupMissingAction](#ItemLabelSetupMissingAction)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[UseGiftCardPolicies](#UseGiftCardPolicies)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[SmallBusinessAccountExportProfileName](#SmallBusinessAccountExportProfileName)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[DiscountAccountLedgerDimensionDisplayValue](#DiscountAccountLedgerDimensionDisplayValue)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[MixMatchLedgerDimensionDisplayValue](#MixMatchLedgerDimensionDisplayValue)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[MultiBuyLedgerDimensionDisplayValue](#MultiBuyLedgerDimensionDisplayValue)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[OfferLedgerDimensionDisplayValue](#OfferLedgerDimensionDisplayValue)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[PrepaymentLedgerDimensionDisplayValue](#PrepaymentLedgerDimensionDisplayValue)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[ThresholdLedgerDimensionDisplayValue](#ThresholdLedgerDimensionDisplayValue)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[TotalDiscountLedgerDimensionDisplayValue](#TotalDiscountLedgerDimensionDisplayValue)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[GiftCardClosingLedgerDimensionDisplayValue](#GiftCardClosingLedgerDimensionDisplayValue)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[PasswordExpiryInterval](#PasswordExpiryInterval)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[PasswordExpiryNotificationThreshold](#PasswordExpiryNotificationThreshold)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[LockoutDuration](#LockoutDuration)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[LockoutThreshold](#LockoutThreshold)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[LoginCounterResetDuration](#LoginCounterResetDuration)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[CustomerAttributeGroup](#CustomerAttributeGroup)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[CustomerAttributeGroupName](#CustomerAttributeGroupName)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[ApplyDiscountsToPriceKeyedIn](#ApplyDiscountsToPriceKeyedIn)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[ApplyDiscountsToPriceOverrides](#ApplyDiscountsToPriceOverrides)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[CouponBarcodeSetupId](#CouponBarcodeSetupId)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[AllowExchangeOnReturnOrders](#AllowExchangeOnReturnOrders)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[AllowConcludeGiftCardTransactionsWhenOffline](#AllowConcludeGiftCardTransactionsWhenOffline)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[DefaultCustomerPaymentJournalName](#DefaultCustomerPaymentJournalName)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[DefaultLedgerJournalName](#DefaultLedgerJournalName)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[AggregateCustomerPayments](#AggregateCustomerPayments)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[AggregateIncomeExpenseTransactions](#AggregateIncomeExpenseTransactions)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[AggregateSalesAndReturns](#AggregateSalesAndReturns)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[AggregateTenderRemoveAndFloat](#AggregateTenderRemoveAndFloat)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[TaxOnGiftCards](#TaxOnGiftCards)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[UseAdvanceInvoice](#UseAdvanceInvoice)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[TaxCalculationBehavior](#TaxCalculationBehavior)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[MaxNumberOfStatementsPostInParallel](#MaxNumberOfStatementsPostInParallel)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[MaxNumberOfThreadsCustomerOrder](#MaxNumberOfThreadsCustomerOrder)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[AggregatedTransactionsBundleSize](#AggregatedTransactionsBundleSize)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[UseAdvancedAutoCharges](#UseAdvancedAutoCharges)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[GiftCardInquiryPrintHistoryCount](#GiftCardInquiryPrintHistoryCount)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[EnableReturnsForMultipleOrderInvoices](#EnableReturnsForMultipleOrderInvoices)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[RecalculateDimensionsOnPostingError](#RecalculateDimensionsOnPostingError)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[ChargeOverrideReasonCode](#ChargeOverrideReasonCode)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[PostPeriodicDiscountForOrders](#PostPeriodicDiscountForOrders)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[DoNotAggregateReturns](#DoNotAggregateReturns)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[UseRTSForOnlineOrderCreation](#UseRTSForOnlineOrderCreation)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[UseFinancialDimensionFromReturnStore](#UseFinancialDimensionFromReturnStore)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[UseSessionDateForCalculatingPricesAndDiscounts](#UseSessionDateForCalculatingPricesAndDiscounts)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[DefaultBatchIdOnSaleForCashAndCarrySales](#DefaultBatchIdOnSaleForCashAndCarrySales)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[DefaultBatchIdOnSaleForCustomerOrder](#DefaultBatchIdOnSaleForCustomerOrder)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[UseDefaultBatchIdOnSaleForCashAndCarrySales](#UseDefaultBatchIdOnSaleForCashAndCarrySales)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[UseDefaultBatchIdOnSaleForCustomerOrder](#UseDefaultBatchIdOnSaleForCustomerOrder)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[IgnoreReturnLink](#IgnoreReturnLink)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[ClientBookAttributeGroup](#ClientBookAttributeGroup)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[DisablePostRoundingDifference](#DisablePostRoundingDifference)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[ShowOnlyCarrierOptionsForShipOrders](#ShowOnlyCarrierOptionsForShipOrders)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[AsyncOrdersEditHoldCode](#AsyncOrdersEditHoldCode)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[EnableChannelReturnPolicies](#EnableChannelReturnPolicies)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[StmtAutoSettleCustomerDeposit](#StmtAutoSettleCustomerDeposit)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[CustomerOrderTaxCalculationBehavior](#CustomerOrderTaxCalculationBehavior)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[AllowConcludeCreditMemoTransactionsWhenOffline](#AllowConcludeCreditMemoTransactionsWhenOffline)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[InventoryAvailabilityQuantityReturnType](#InventoryAvailabilityQuantityReturnType)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[InventoryEnableAutomaticValidation](#InventoryEnableAutomaticValidation)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[Relationship_DiscountAccountLedgerDimensionCombinationRelationshipId](#Relationship_DiscountAccountLedgerDimensionCombinationRelationshipId)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[Relationship_MixMatchLedgerDimensionCombinationRelationshipId](#Relationship_MixMatchLedgerDimensionCombinationRelationshipId)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[Relationship_MultiBuyLedgerDimensionCombinationRelationshipId](#Relationship_MultiBuyLedgerDimensionCombinationRelationshipId)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[Relationship_OfferLedgerDimensionCombinationRelationshipId](#Relationship_OfferLedgerDimensionCombinationRelationshipId)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[Relationship_PrepaymentLedgerDimensionCombinationRelationshipId](#Relationship_PrepaymentLedgerDimensionCombinationRelationshipId)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[Relationship_ThresholdLedgerDimensionCombinationRelationshipId](#Relationship_ThresholdLedgerDimensionCombinationRelationshipId)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[Relationship_TotalDiscountLedgerDimensionCombinationRelationshipId](#Relationship_TotalDiscountLedgerDimensionCombinationRelationshipId)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[Relationship_GiftCardClosingLedgerDimensionCombinationRelationshipId](#Relationship_GiftCardClosingLedgerDimensionCombinationRelationshipId)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[BackingTable_RetailParametersRelationshipId](#BackingTable_RetailParametersRelationshipId)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="RetailParameterEntity.md" target="_blank">TransactionsAndOrders/RetailParameterEntity</a>|

### <a href=#PrePaymentLedgerJournalName name="PrePaymentLedgerJournalName">PrePaymentLedgerJournalName</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrePaymentLedgerJournalName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MixAndMatchActivityType name="MixAndMatchActivityType">MixAndMatchActivityType</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Mix and match activity type</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MixAndMatchActivityType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Mix and match activity type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountExportProfile name="AccountExportProfile">AccountExportProfile</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountExportProfile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AggregateBeforePosting name="AggregateBeforePosting">AggregateBeforePosting</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AggregateBeforePosting attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AutoSettle name="AutoSettle">AutoSettle</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AutoSettle attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BuyersPushRespectAssortments name="BuyersPushRespectAssortments">BuyersPushRespectAssortments</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Buyer's push</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BuyersPushRespectAssortments attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Buyer's push</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CancellationCharge name="CancellationCharge">CancellationCharge</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CancellationCharge attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CancellationChargeCode name="CancellationChargeCode">CancellationChargeCode</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cancellation charge code</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CancellationChargeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Cancellation charge code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CrossDockingRespectAssortments name="CrossDockingRespectAssortments">CrossDockingRespectAssortments</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cross docking</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CrossDockingRespectAssortments attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Cross docking</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultCustomerPosting name="DefaultCustomerPosting">DefaultCustomerPosting</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultCustomerPosting attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultInventoryJournalName name="DefaultInventoryJournalName">DefaultInventoryJournalName</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default inventory journal</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultInventoryJournalName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Default inventory journal</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultJournalName4CategoryPrice name="DefaultJournalName4CategoryPrice">DefaultJournalName4CategoryPrice</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Category journal name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultJournalName4CategoryPrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Category journal name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultOrdertype name="DefaultOrdertype">DefaultOrdertype</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default order type</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultOrdertype attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Default order type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultRCashJournalName name="DefaultRCashJournalName">DefaultRCashJournalName</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cash payment journal</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultRCashJournalName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Cash payment journal</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DetailSummary name="DetailSummary">DetailSummary</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DetailSummary attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscountAccountLedgerDimension name="DiscountAccountLedgerDimension">DiscountAccountLedgerDimension</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Discount account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountAccountLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Discount account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscountOfferActivityType name="DiscountOfferActivityType">DiscountOfferActivityType</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Discount activity type</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountOfferActivityType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Discount activity type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EANLicenseNo name="EANLicenseNo">EANLicenseNo</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EANLicenseNo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ElectronicDeliveryModeCode name="ElectronicDeliveryModeCode">ElectronicDeliveryModeCode</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Electronic mode of delivery</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ElectronicDeliveryModeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Electronic mode of delivery</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EventNotificationProfileId name="EventNotificationProfileId">EventNotificationProfileId</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EventNotificationProfileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExpirationDate name="ExpirationDate">ExpirationDate</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpirationDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GiftCardCompany name="GiftCardCompany">GiftCardCompany</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Gift card company</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiftCardCompany attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Gift card company</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GiftcardItem name="GiftcardItem">GiftcardItem</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Gift card product</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiftcardItem attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Gift card product</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GiftCardLedgerJournalName name="GiftCardLedgerJournalName">GiftCardLedgerJournalName</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Journal</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiftCardLedgerJournalName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Journal</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryLocationIdForInventory name="InventoryLocationIdForInventory">InventoryLocationIdForInventory</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Inventory</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryLocationIdForInventory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Inventory</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryLocationIdForPurchaseOrder name="InventoryLocationIdForPurchaseOrder">InventoryLocationIdForPurchaseOrder</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purchase order</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryLocationIdForPurchaseOrder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchase order</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryLocationIdForSalesOrder name="InventoryLocationIdForSalesOrder">InventoryLocationIdForSalesOrder</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales order</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryLocationIdForSalesOrder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales order</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemLabelLastAction name="ItemLabelLastAction">ItemLabelLastAction</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last action for product label</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemLabelLastAction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Last action for product label</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemLabelsForNegativeStock name="ItemLabelsForNegativeStock">ItemLabelsForNegativeStock</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemLabelsForNegativeStock attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemSalesStatisticsOn name="ItemSalesStatisticsOn">ItemSalesStatisticsOn</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales statistics on</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemSalesStatisticsOn attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales statistics on</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JournalNameForKitPricing name="JournalNameForKitPricing">JournalNameForKitPricing</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Kit journal name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalNameForKitPricing attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Kit journal name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Key name="Key">Key</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Key attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerAccountType name="LedgerAccountType">LedgerAccountType</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerAccountType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaxSalesOrdersPerTask name="MaxSalesOrdersPerTask">MaxSalesOrdersPerTask</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxSalesOrdersPerTask attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CallCenterGiftCardVoidJournalName name="CallCenterGiftCardVoidJournalName">CallCenterGiftCardVoidJournalName</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Void journal name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CallCenterGiftCardVoidJournalName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Void journal name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinimumDepositForSalesOrder name="MinimumDepositForSalesOrder">MinimumDepositForSalesOrder</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumDepositForSalesOrder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinimumPasswordLength name="MinimumPasswordLength">MinimumPasswordLength</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumPasswordLength attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MixMatchLedgerDimension name="MixMatchLedgerDimension">MixMatchLedgerDimension</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Mix and match number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MixMatchLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Mix and match number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MultibuyActivityType name="MultibuyActivityType">MultibuyActivityType</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quantity discount activity type</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MultibuyActivityType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Quantity discount activity type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MultiBuyLedgerDimension name="MultiBuyLedgerDimension">MultiBuyLedgerDimension</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quantity discount</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MultiBuyLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Quantity discount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OfferLedgerDimension name="OfferLedgerDimension">OfferLedgerDimension</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Discount</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OfferLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Discount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OverrideSystemLookup name="OverrideSystemLookup">OverrideSystemLookup</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OverrideSystemLookup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ParallelSalesOrderPosting name="ParallelSalesOrderPosting">ParallelSalesOrderPosting</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process requests in parallel</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ParallelSalesOrderPosting attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Process requests in parallel</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Payment name="Payment">Payment</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Payment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentStatistics name="PaymentStatistics">PaymentStatistics</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Payment statistics</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentStatistics attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Payment statistics</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentMode name="PaymentMode">PaymentMode</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentMode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PickUpDeliveryModeCode name="PickUpDeliveryModeCode">PickUpDeliveryModeCode</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Pickup mode of delivery</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PickUpDeliveryModeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Pickup mode of delivery</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostBankedSum name="PostBankedSum">PostBankedSum</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bank drop</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostBankedSum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Bank drop</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostCustomerDiscount name="PostCustomerDiscount">PostCustomerDiscount</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostCustomerDiscount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostInfocodeDiscount name="PostInfocodeDiscount">PostInfocodeDiscount</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostInfocodeDiscount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostLineDiscount name="PostLineDiscount">PostLineDiscount</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostLineDiscount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostPeriodicDiscount name="PostPeriodicDiscount">PostPeriodicDiscount</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostPeriodicDiscount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostSafeSum name="PostSafeSum">PostSafeSum</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Safe drop</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostSafeSum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Safe drop</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostSalesOrderWhenPaid name="PostSalesOrderWhenPaid">PostSalesOrderWhenPaid</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Post sales order when paid</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostSalesOrderWhenPaid attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Post sales order when paid</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostTotalDiscount name="PostTotalDiscount">PostTotalDiscount</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostTotalDiscount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrepaymentLedgerDimension name="PrepaymentLedgerDimension">PrepaymentLedgerDimension</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ledger account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrepaymentLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Ledger account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceiptEmailFilename name="ReceiptEmailFilename">ReceiptEmailFilename</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceiptEmailFilename attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceiptEmailSubject name="ReceiptEmailSubject">ReceiptEmailSubject</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceiptEmailSubject attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceiptEmailText name="ReceiptEmailText">ReceiptEmailText</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceiptEmailText attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceiptOption name="ReceiptOption">ReceiptOption</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceiptOption attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReplenishmentAssortmentsCoverageDays name="ReplenishmentAssortmentsCoverageDays">ReplenishmentAssortmentsCoverageDays</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplenishmentAssortmentsCoverageDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequireNumericCharacter name="RequireNumericCharacter">RequireNumericCharacter</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequireNumericCharacter attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequireSpecialCharacter name="RequireSpecialCharacter">RequireSpecialCharacter</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequireSpecialCharacter attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequireUppercase name="RequireUppercase">RequireUppercase</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequireUppercase attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnDispositionCodeId name="ReturnDispositionCodeId">ReturnDispositionCodeId</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnDispositionCodeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShelfLabelLastAction name="ShelfLabelLastAction">ShelfLabelLastAction</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last action for shelf label</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShelfLabelLastAction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Last action for shelf label</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingChargeCode name="ShippingChargeCode">ShippingChargeCode</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Shipping charge code</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingChargeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shipping charge code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StaffStatistics name="StaffStatistics">StaffStatistics</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Staff statistics</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StaffStatistics attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Staff statistics</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SystemInUse name="SystemInUse">SystemInUse</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>System in use</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SystemInUse attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>System in use</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TerminalStatistics name="TerminalStatistics">TerminalStatistics</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Terminal statistics</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TerminalStatistics attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Terminal statistics</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThresholdLedgerDimension name="ThresholdLedgerDimension">ThresholdLedgerDimension</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Threshold discount number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThresholdLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Threshold discount number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalDiscountLedgerDimension name="TotalDiscountLedgerDimension">TotalDiscountLedgerDimension</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total discount account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalDiscountLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Total discount account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseDefaultLedgerAccount name="UseDefaultLedgerAccount">UseDefaultLedgerAccount</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Use default ledger accounts</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseDefaultLedgerAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Use default ledger accounts</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseDefaultTradeDates name="UseDefaultTradeDates">UseDefaultTradeDates</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Use posting date as sales date</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseDefaultTradeDates attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Use posting date as sales date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseRetailReturnTaxGroup name="UseRetailReturnTaxGroup">UseRetailReturnTaxGroup</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Use sales tax group for returns</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseRetailReturnTaxGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Use sales tax group for returns</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WishListInvitationEmailId name="WishListInvitationEmailId">WishListInvitationEmailId</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WishListInvitationEmailId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GiftCardClosingLedgerDimension name="GiftCardClosingLedgerDimension">GiftCardClosingLedgerDimension</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Nonoperating income account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiftCardClosingLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Nonoperating income account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemLabelSetupMissingAction name="ItemLabelSetupMissingAction">ItemLabelSetupMissingAction</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemLabelSetupMissingAction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseGiftCardPolicies name="UseGiftCardPolicies">UseGiftCardPolicies</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Use gift card policies</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseGiftCardPolicies attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Use gift card policies</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SmallBusinessAccountExportProfileName name="SmallBusinessAccountExportProfileName">SmallBusinessAccountExportProfileName</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SmallBusinessAccountExportProfileName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscountAccountLedgerDimensionDisplayValue name="DiscountAccountLedgerDimensionDisplayValue">DiscountAccountLedgerDimensionDisplayValue</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Discount account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountAccountLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Discount account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MixMatchLedgerDimensionDisplayValue name="MixMatchLedgerDimensionDisplayValue">MixMatchLedgerDimensionDisplayValue</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Mix and match number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MixMatchLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Mix and match number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MultiBuyLedgerDimensionDisplayValue name="MultiBuyLedgerDimensionDisplayValue">MultiBuyLedgerDimensionDisplayValue</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quantity discount</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MultiBuyLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Quantity discount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OfferLedgerDimensionDisplayValue name="OfferLedgerDimensionDisplayValue">OfferLedgerDimensionDisplayValue</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Discount</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OfferLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Discount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrepaymentLedgerDimensionDisplayValue name="PrepaymentLedgerDimensionDisplayValue">PrepaymentLedgerDimensionDisplayValue</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ledger account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrepaymentLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Ledger account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThresholdLedgerDimensionDisplayValue name="ThresholdLedgerDimensionDisplayValue">ThresholdLedgerDimensionDisplayValue</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Threshold discount number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThresholdLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Threshold discount number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalDiscountLedgerDimensionDisplayValue name="TotalDiscountLedgerDimensionDisplayValue">TotalDiscountLedgerDimensionDisplayValue</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total discount account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalDiscountLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Total discount account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GiftCardClosingLedgerDimensionDisplayValue name="GiftCardClosingLedgerDimensionDisplayValue">GiftCardClosingLedgerDimensionDisplayValue</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Nonoperating income account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiftCardClosingLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Nonoperating income account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PasswordExpiryInterval name="PasswordExpiryInterval">PasswordExpiryInterval</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Password expiry interval (in days)</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PasswordExpiryInterval attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Password expiry interval (in days)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PasswordExpiryNotificationThreshold name="PasswordExpiryNotificationThreshold">PasswordExpiryNotificationThreshold</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Password expiry notification threshold (in days)</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PasswordExpiryNotificationThreshold attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Password expiry notification threshold (in days)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LockoutDuration name="LockoutDuration">LockoutDuration</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Lockout duration (in minutes)</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LockoutDuration attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Lockout duration (in minutes)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LockoutThreshold name="LockoutThreshold">LockoutThreshold</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Lockout threshold</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LockoutThreshold attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Lockout threshold</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LoginCounterResetDuration name="LoginCounterResetDuration">LoginCounterResetDuration</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reset login counter after (in minutes)</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoginCounterResetDuration attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reset login counter after (in minutes)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerAttributeGroup name="CustomerAttributeGroup">CustomerAttributeGroup</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerAttributeGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerAttributeGroupName name="CustomerAttributeGroupName">CustomerAttributeGroupName</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerAttributeGroupName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ApplyDiscountsToPriceKeyedIn name="ApplyDiscountsToPriceKeyedIn">ApplyDiscountsToPriceKeyedIn</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ApplyDiscountsToPriceKeyedIn attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ApplyDiscountsToPriceOverrides name="ApplyDiscountsToPriceOverrides">ApplyDiscountsToPriceOverrides</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ApplyDiscountsToPriceOverrides attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CouponBarcodeSetupId name="CouponBarcodeSetupId">CouponBarcodeSetupId</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CouponBarcodeSetupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowExchangeOnReturnOrders name="AllowExchangeOnReturnOrders">AllowExchangeOnReturnOrders</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowExchangeOnReturnOrders attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowConcludeGiftCardTransactionsWhenOffline name="AllowConcludeGiftCardTransactionsWhenOffline">AllowConcludeGiftCardTransactionsWhenOffline</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow concluding gift card transactions in offline mode</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowConcludeGiftCardTransactionsWhenOffline attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow concluding gift card transactions in offline mode</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultCustomerPaymentJournalName name="DefaultCustomerPaymentJournalName">DefaultCustomerPaymentJournalName</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultCustomerPaymentJournalName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultLedgerJournalName name="DefaultLedgerJournalName">DefaultLedgerJournalName</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultLedgerJournalName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AggregateCustomerPayments name="AggregateCustomerPayments">AggregateCustomerPayments</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AggregateCustomerPayments attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AggregateIncomeExpenseTransactions name="AggregateIncomeExpenseTransactions">AggregateIncomeExpenseTransactions</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AggregateIncomeExpenseTransactions attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AggregateSalesAndReturns name="AggregateSalesAndReturns">AggregateSalesAndReturns</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AggregateSalesAndReturns attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AggregateTenderRemoveAndFloat name="AggregateTenderRemoveAndFloat">AggregateTenderRemoveAndFloat</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AggregateTenderRemoveAndFloat attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxOnGiftCards name="TaxOnGiftCards">TaxOnGiftCards</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxOnGiftCards attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseAdvanceInvoice name="UseAdvanceInvoice">UseAdvanceInvoice</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseAdvanceInvoice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxCalculationBehavior name="TaxCalculationBehavior">TaxCalculationBehavior</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxCalculationBehavior attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaxNumberOfStatementsPostInParallel name="MaxNumberOfStatementsPostInParallel">MaxNumberOfStatementsPostInParallel</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxNumberOfStatementsPostInParallel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaxNumberOfThreadsCustomerOrder name="MaxNumberOfThreadsCustomerOrder">MaxNumberOfThreadsCustomerOrder</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxNumberOfThreadsCustomerOrder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AggregatedTransactionsBundleSize name="AggregatedTransactionsBundleSize">AggregatedTransactionsBundleSize</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AggregatedTransactionsBundleSize attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseAdvancedAutoCharges name="UseAdvancedAutoCharges">UseAdvancedAutoCharges</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseAdvancedAutoCharges attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GiftCardInquiryPrintHistoryCount name="GiftCardInquiryPrintHistoryCount">GiftCardInquiryPrintHistoryCount</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiftCardInquiryPrintHistoryCount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnableReturnsForMultipleOrderInvoices name="EnableReturnsForMultipleOrderInvoices">EnableReturnsForMultipleOrderInvoices</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableReturnsForMultipleOrderInvoices attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RecalculateDimensionsOnPostingError name="RecalculateDimensionsOnPostingError">RecalculateDimensionsOnPostingError</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecalculateDimensionsOnPostingError attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChargeOverrideReasonCode name="ChargeOverrideReasonCode">ChargeOverrideReasonCode</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargeOverrideReasonCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostPeriodicDiscountForOrders name="PostPeriodicDiscountForOrders">PostPeriodicDiscountForOrders</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostPeriodicDiscountForOrders attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DoNotAggregateReturns name="DoNotAggregateReturns">DoNotAggregateReturns</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DoNotAggregateReturns attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseRTSForOnlineOrderCreation name="UseRTSForOnlineOrderCreation">UseRTSForOnlineOrderCreation</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseRTSForOnlineOrderCreation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseFinancialDimensionFromReturnStore name="UseFinancialDimensionFromReturnStore">UseFinancialDimensionFromReturnStore</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseFinancialDimensionFromReturnStore attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseSessionDateForCalculatingPricesAndDiscounts name="UseSessionDateForCalculatingPricesAndDiscounts">UseSessionDateForCalculatingPricesAndDiscounts</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseSessionDateForCalculatingPricesAndDiscounts attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultBatchIdOnSaleForCashAndCarrySales name="DefaultBatchIdOnSaleForCashAndCarrySales">DefaultBatchIdOnSaleForCashAndCarrySales</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultBatchIdOnSaleForCashAndCarrySales attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultBatchIdOnSaleForCustomerOrder name="DefaultBatchIdOnSaleForCustomerOrder">DefaultBatchIdOnSaleForCustomerOrder</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultBatchIdOnSaleForCustomerOrder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseDefaultBatchIdOnSaleForCashAndCarrySales name="UseDefaultBatchIdOnSaleForCashAndCarrySales">UseDefaultBatchIdOnSaleForCashAndCarrySales</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseDefaultBatchIdOnSaleForCashAndCarrySales attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UseDefaultBatchIdOnSaleForCustomerOrder name="UseDefaultBatchIdOnSaleForCustomerOrder">UseDefaultBatchIdOnSaleForCustomerOrder</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UseDefaultBatchIdOnSaleForCustomerOrder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IgnoreReturnLink name="IgnoreReturnLink">IgnoreReturnLink</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IgnoreReturnLink attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ClientBookAttributeGroup name="ClientBookAttributeGroup">ClientBookAttributeGroup</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClientBookAttributeGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DisablePostRoundingDifference name="DisablePostRoundingDifference">DisablePostRoundingDifference</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisablePostRoundingDifference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShowOnlyCarrierOptionsForShipOrders name="ShowOnlyCarrierOptionsForShipOrders">ShowOnlyCarrierOptionsForShipOrders</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShowOnlyCarrierOptionsForShipOrders attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AsyncOrdersEditHoldCode name="AsyncOrdersEditHoldCode">AsyncOrdersEditHoldCode</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AsyncOrdersEditHoldCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnableChannelReturnPolicies name="EnableChannelReturnPolicies">EnableChannelReturnPolicies</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableChannelReturnPolicies attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StmtAutoSettleCustomerDeposit name="StmtAutoSettleCustomerDeposit">StmtAutoSettleCustomerDeposit</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StmtAutoSettleCustomerDeposit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerOrderTaxCalculationBehavior name="CustomerOrderTaxCalculationBehavior">CustomerOrderTaxCalculationBehavior</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerOrderTaxCalculationBehavior attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowConcludeCreditMemoTransactionsWhenOffline name="AllowConcludeCreditMemoTransactionsWhenOffline">AllowConcludeCreditMemoTransactionsWhenOffline</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowConcludeCreditMemoTransactionsWhenOffline attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryAvailabilityQuantityReturnType name="InventoryAvailabilityQuantityReturnType">InventoryAvailabilityQuantityReturnType</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryAvailabilityQuantityReturnType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryEnableAutomaticValidation name="InventoryEnableAutomaticValidation">InventoryEnableAutomaticValidation</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Enable automatic validation</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryEnableAutomaticValidation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Enable automatic validation</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DiscountAccountLedgerDimensionCombinationRelationshipId name="Relationship_DiscountAccountLedgerDimensionCombinationRelationshipId">Relationship_DiscountAccountLedgerDimensionCombinationRelationshipId</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DiscountAccountLedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_MixMatchLedgerDimensionCombinationRelationshipId name="Relationship_MixMatchLedgerDimensionCombinationRelationshipId">Relationship_MixMatchLedgerDimensionCombinationRelationshipId</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MixMatchLedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_MultiBuyLedgerDimensionCombinationRelationshipId name="Relationship_MultiBuyLedgerDimensionCombinationRelationshipId">Relationship_MultiBuyLedgerDimensionCombinationRelationshipId</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MultiBuyLedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_OfferLedgerDimensionCombinationRelationshipId name="Relationship_OfferLedgerDimensionCombinationRelationshipId">Relationship_OfferLedgerDimensionCombinationRelationshipId</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OfferLedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PrepaymentLedgerDimensionCombinationRelationshipId name="Relationship_PrepaymentLedgerDimensionCombinationRelationshipId">Relationship_PrepaymentLedgerDimensionCombinationRelationshipId</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PrepaymentLedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ThresholdLedgerDimensionCombinationRelationshipId name="Relationship_ThresholdLedgerDimensionCombinationRelationshipId">Relationship_ThresholdLedgerDimensionCombinationRelationshipId</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ThresholdLedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_TotalDiscountLedgerDimensionCombinationRelationshipId name="Relationship_TotalDiscountLedgerDimensionCombinationRelationshipId">Relationship_TotalDiscountLedgerDimensionCombinationRelationshipId</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TotalDiscountLedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_GiftCardClosingLedgerDimensionCombinationRelationshipId name="Relationship_GiftCardClosingLedgerDimensionCombinationRelationshipId">Relationship_GiftCardClosingLedgerDimensionCombinationRelationshipId</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_GiftCardClosingLedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_RetailParametersRelationshipId name="BackingTable_RetailParametersRelationshipId">BackingTable_RetailParametersRelationshipId</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailParametersRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Commerce/ChannelManagement/Parameter/RetailParameters.md" target="_blank">/core/operationsCommon/Tables/Commerce/ChannelManagement/Parameter/RetailParameters.cdm.json/RetailParameters</a></td><td><a href="../../../Tables/Commerce/ChannelManagement/Parameter/RetailParameters.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: TransactionsAndOrders/RetailParameterEntity (this entity)  

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
