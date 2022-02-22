---
title: RetailAttributesLegalEntityLookupEntity in Merchandising - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Category basic product properties in Merchandising(RetailAttributesLegalEntityLookupEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Commerce/Merchandising/RetailAttributesLegalEntityLookupEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Category basic product properties</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[CategoryHierarchyName](#CategoryHierarchyName)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[CategoryName](#CategoryName)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[LegalEntity](#LegalEntity)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[BarCodeSetup](#BarCodeSetup)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[GroupCounting](#GroupCounting)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[GroupCoverage](#GroupCoverage)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[GroupInventoryModel](#GroupInventoryModel)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[GroupItemGroup](#GroupItemGroup)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[ItemLegalEntity](#ItemLegalEntity)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[ItemSalesTaxGroupPurchase](#ItemSalesTaxGroupPurchase)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[ItemSalesTaxGroupSales](#ItemSalesTaxGroupSales)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[ReplenishmentRule](#ReplenishmentRule)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[ReportItemLabel](#ReportItemLabel)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[ReportShelfLabel](#ReportShelfLabel)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[SiteId](#SiteId)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[UnitPrice](#UnitPrice)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[UnitPriceSales](#UnitPriceSales)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[InventoryWarehouse](#InventoryWarehouse)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[PurchaseWarehouse](#PurchaseWarehouse)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[SalesWarehouse](#SalesWarehouse)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[ReturnPolicyNumber](#ReturnPolicyNumber)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[BaseComparisonUnitSymbol](#BaseComparisonUnitSymbol)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[BillOfMaterialsUnitSymbol](#BillOfMaterialsUnitSymbol)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[InventoryUnitSymbol](#InventoryUnitSymbol)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[PurchaseUnitSymbol](#PurchaseUnitSymbol)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[SalesUnitSymbol](#SalesUnitSymbol)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[PurchaseOverdeliveryPct](#PurchaseOverdeliveryPct)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[PurchaseUnderdeliveryPct](#PurchaseUnderdeliveryPct)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[SalesOverdeliveryPct](#SalesOverdeliveryPct)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[SalesUnderdeliveryPct](#SalesUnderdeliveryPct)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[InventoryOverdeliveryPct](#InventoryOverdeliveryPct)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[InventoryUnderdeliveryPct](#InventoryUnderdeliveryPct)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[PurchModel](#PurchModel)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[CostModel](#CostModel)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[ItemBuyerGroupId](#ItemBuyerGroupId)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[PurchaseInterCompanyBlocked](#PurchaseInterCompanyBlocked)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[ItemPriceToleranceGroupId](#ItemPriceToleranceGroupId)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[PrimaryVendorId](#PrimaryVendorId)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[PurchasePriceDate](#PurchasePriceDate)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[PurchasePrice](#PurchasePrice)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[PurchaseMarkup](#PurchaseMarkup)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[PurchasePriceQty](#PurchasePriceQty)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[PurchaseMarkupGroupId](#PurchaseMarkupGroupId)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[PurchaseAllocateMarkup](#PurchaseAllocateMarkup)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[PurchaseLineDisc](#PurchaseLineDisc)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[PurchaseMultiLineDisc](#PurchaseMultiLineDisc)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[PurchaseEndDisc](#PurchaseEndDisc)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[PurchaseSuppItemGroupId](#PurchaseSuppItemGroupId)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[PurchasePDSPricingPrecision](#PurchasePDSPricingPrecision)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[ItemVendRebateGroupId](#ItemVendRebateGroupId)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[PdsVendorCheckItem](#PdsVendorCheckItem)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[NetWeight](#NetWeight)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[TaraWeight](#TaraWeight)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[GrossDepth](#GrossDepth)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[GrossWidth](#GrossWidth)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[GrossHeight](#GrossHeight)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[UnitVolume](#UnitVolume)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[BatchNumGroupId](#BatchNumGroupId)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[SerialNumGroupId](#SerialNumGroupId)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[WMSArrivalHandlingTime](#WMSArrivalHandlingTime)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[SortCode](#SortCode)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[PackagingGroupId](#PackagingGroupId)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[TaxPackagingQty](#TaxPackagingQty)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[CostGroupId](#CostGroupId)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[InventoryPriceDate](#InventoryPriceDate)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[InventoryPrice](#InventoryPrice)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[InventoryPriceUnit](#InventoryPriceUnit)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[InventoryMarkup](#InventoryMarkup)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[InventoryPriceQty](#InventoryPriceQty)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[InventoryAllocateMarkup](#InventoryAllocateMarkup)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[ABCValue](#ABCValue)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[ABCContributionMargin](#ABCContributionMargin)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[ABCRevenue](#ABCRevenue)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[ABCTieUp](#ABCTieUp)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[SalesInterCompanyBlocked](#SalesInterCompanyBlocked)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[SalesCommisionGroupId](#SalesCommisionGroupId)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[SalesPriceModel](#SalesPriceModel)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[SalesBasePriceModel](#SalesBasePriceModel)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[SalesContributionRatio](#SalesContributionRatio)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[SalesPercentMarkup](#SalesPercentMarkup)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[SalesPriceDate](#SalesPriceDate)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[SalesPrice](#SalesPrice)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[SalesPriceMarkup](#SalesPriceMarkup)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[SalesPriceMarkupQuantity](#SalesPriceMarkupQuantity)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[SalesMarkupGroupId](#SalesMarkupGroupId)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[SalesAllocateMarkup](#SalesAllocateMarkup)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[SalesLineDiscount](#SalesLineDiscount)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[SalesMultiLineDiscount](#SalesMultiLineDiscount)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[SalesTotalDiscount](#SalesTotalDiscount)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[SalesSuppItemGroupId](#SalesSuppItemGroupId)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[SalesUseAltItemId](#SalesUseAltItemId)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[SalesAltItemId](#SalesAltItemId)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[SalesAltConfigId](#SalesAltConfigId)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[SalesAltInventSizeId](#SalesAltInventSizeId)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[SalesAltInventColorId](#SalesAltInventColorId)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[SalesAltInventStyleId](#SalesAltInventStyleId)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[SalesInstallmentEligible](#SalesInstallmentEligible)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[SalesPDSPricingPrecision](#SalesPDSPricingPrecision)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[SalesFTCExempt](#SalesFTCExempt)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[SalesAllowPriceAdjust](#SalesAllowPriceAdjust)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[SalesContinuityScheduleId](#SalesContinuityScheduleId)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[SalesStartDate](#SalesStartDate)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[SalesEndDate](#SalesEndDate)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[SalesPdsItemRebateGroupId](#SalesPdsItemRebateGroupId)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[SalesPdsFreightAllocationGroupId](#SalesPdsFreightAllocationGroupId)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[RetailBarCodeUseEANStandard](#RetailBarCodeUseEANStandard)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[RetailBlockedAtRegister](#RetailBlockedAtRegister)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[RetailDateBlocked](#RetailDateBlocked)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[RetailDateToActivateItem](#RetailDateToActivateItem)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[RetailDateToBeBlocked](#RetailDateToBeBlocked)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[RetailPOSAllowNegativeQuantity](#RetailPOSAllowNegativeQuantity)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[RetailPOSDisallowDiscount](#RetailPOSDisallowDiscount)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[RetailPOSIsScaleItem](#RetailPOSIsScaleItem)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[RetailPOSIsZeroPriceValid](#RetailPOSIsZeroPriceValid)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[RetailPOSKeyingInPrice](#RetailPOSKeyingInPrice)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[RetailPOSKeyingInQuantity](#RetailPOSKeyingInQuantity)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[RetailPOSMustKeyInComment](#RetailPOSMustKeyInComment)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[RetailPOSDisallowManualDiscount](#RetailPOSDisallowManualDiscount)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[RetailPrintVariantsShelfLabels](#RetailPrintVariantsShelfLabels)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[RetailSeasonCode](#RetailSeasonCode)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[RetailLifeFrom](#RetailLifeFrom)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[RetailLifeTo](#RetailLifeTo)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[SalesRetailInventoryAvailabilityBuffer](#SalesRetailInventoryAvailabilityBuffer)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[SalesRetailInventoryAvailabilityLevelProfile](#SalesRetailInventoryAvailabilityLevelProfile)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|
|[BackingTable_RetailAttributesLegalEntityLookupRelationshipId](#BackingTable_RetailAttributesLegalEntityLookupRelationshipId)||<a href="RetailAttributesLegalEntityLookupEntity.md" target="_blank">Merchandising/RetailAttributesLegalEntityLookupEntity</a>|

### <a href=#CategoryHierarchyName name="CategoryHierarchyName">CategoryHierarchyName</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Category hierarchy name</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CategoryHierarchyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Category hierarchy name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CategoryName name="CategoryName">CategoryName</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Category name</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CategoryName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Category name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LegalEntity name="LegalEntity">LegalEntity</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LegalEntity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BarCodeSetup name="BarCodeSetup">BarCodeSetup</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BarCodeSetup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GroupCounting name="GroupCounting">GroupCounting</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GroupCounting attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GroupCoverage name="GroupCoverage">GroupCoverage</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GroupCoverage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GroupInventoryModel name="GroupInventoryModel">GroupInventoryModel</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Inventory model</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GroupInventoryModel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Inventory model</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GroupItemGroup name="GroupItemGroup">GroupItemGroup</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GroupItemGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemLegalEntity name="ItemLegalEntity">ItemLegalEntity</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemLegalEntity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemSalesTaxGroupPurchase name="ItemSalesTaxGroupPurchase">ItemSalesTaxGroupPurchase</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purchase order sales tax group</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemSalesTaxGroupPurchase attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchase order sales tax group</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemSalesTaxGroupSales name="ItemSalesTaxGroupSales">ItemSalesTaxGroupSales</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales order sales tax group</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemSalesTaxGroupSales attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales order sales tax group</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReplenishmentRule name="ReplenishmentRule">ReplenishmentRule</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplenishmentRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportItemLabel name="ReportItemLabel">ReportItemLabel</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Product label report</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportItemLabel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Product label report</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReportShelfLabel name="ReportShelfLabel">ReportShelfLabel</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Shelf label report</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportShelfLabel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shelf label report</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SiteId name="SiteId">SiteId</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnitPrice name="UnitPrice">UnitPrice</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purchase price unit</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitPrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchase price unit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnitPriceSales name="UnitPriceSales">UnitPriceSales</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales price unit</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitPriceSales attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales price unit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryWarehouse name="InventoryWarehouse">InventoryWarehouse</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Inventory warehouse</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryWarehouse attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Inventory warehouse</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseWarehouse name="PurchaseWarehouse">PurchaseWarehouse</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purchase warehouse</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseWarehouse attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchase warehouse</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesWarehouse name="SalesWarehouse">SalesWarehouse</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales warehouse</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesWarehouse attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales warehouse</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnPolicyNumber name="ReturnPolicyNumber">ReturnPolicyNumber</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Return location</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnPolicyNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Return location</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BaseComparisonUnitSymbol name="BaseComparisonUnitSymbol">BaseComparisonUnitSymbol</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Base comparison unit</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BaseComparisonUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Base comparison unit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BillOfMaterialsUnitSymbol name="BillOfMaterialsUnitSymbol">BillOfMaterialsUnitSymbol</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>BOM unit</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BillOfMaterialsUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>BOM unit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryUnitSymbol name="InventoryUnitSymbol">InventoryUnitSymbol</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Inventory unit</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Inventory unit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseUnitSymbol name="PurchaseUnitSymbol">PurchaseUnitSymbol</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purchase unit</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchase unit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesUnitSymbol name="SalesUnitSymbol">SalesUnitSymbol</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales unit</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales unit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseOverdeliveryPct name="PurchaseOverdeliveryPct">PurchaseOverdeliveryPct</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseOverdeliveryPct attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseUnderdeliveryPct name="PurchaseUnderdeliveryPct">PurchaseUnderdeliveryPct</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseUnderdeliveryPct attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesOverdeliveryPct name="SalesOverdeliveryPct">SalesOverdeliveryPct</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesOverdeliveryPct attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesUnderdeliveryPct name="SalesUnderdeliveryPct">SalesUnderdeliveryPct</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesUnderdeliveryPct attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryOverdeliveryPct name="InventoryOverdeliveryPct">InventoryOverdeliveryPct</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryOverdeliveryPct attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryUnderdeliveryPct name="InventoryUnderdeliveryPct">InventoryUnderdeliveryPct</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryUnderdeliveryPct attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchModel name="PurchModel">PurchModel</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchModel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostModel name="CostModel">CostModel</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostModel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemBuyerGroupId name="ItemBuyerGroupId">ItemBuyerGroupId</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemBuyerGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseInterCompanyBlocked name="PurchaseInterCompanyBlocked">PurchaseInterCompanyBlocked</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseInterCompanyBlocked attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemPriceToleranceGroupId name="ItemPriceToleranceGroupId">ItemPriceToleranceGroupId</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemPriceToleranceGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrimaryVendorId name="PrimaryVendorId">PrimaryVendorId</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryVendorId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchasePriceDate name="PurchasePriceDate">PurchasePriceDate</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchasePriceDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchasePrice name="PurchasePrice">PurchasePrice</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchasePrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseMarkup name="PurchaseMarkup">PurchaseMarkup</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseMarkup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchasePriceQty name="PurchasePriceQty">PurchasePriceQty</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchasePriceQty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseMarkupGroupId name="PurchaseMarkupGroupId">PurchaseMarkupGroupId</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseMarkupGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseAllocateMarkup name="PurchaseAllocateMarkup">PurchaseAllocateMarkup</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseAllocateMarkup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseLineDisc name="PurchaseLineDisc">PurchaseLineDisc</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseLineDisc attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseMultiLineDisc name="PurchaseMultiLineDisc">PurchaseMultiLineDisc</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseMultiLineDisc attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseEndDisc name="PurchaseEndDisc">PurchaseEndDisc</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseEndDisc attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseSuppItemGroupId name="PurchaseSuppItemGroupId">PurchaseSuppItemGroupId</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseSuppItemGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchasePDSPricingPrecision name="PurchasePDSPricingPrecision">PurchasePDSPricingPrecision</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchasePDSPricingPrecision attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemVendRebateGroupId name="ItemVendRebateGroupId">ItemVendRebateGroupId</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemVendRebateGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PdsVendorCheckItem name="PdsVendorCheckItem">PdsVendorCheckItem</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PdsVendorCheckItem attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NetWeight name="NetWeight">NetWeight</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NetWeight attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaraWeight name="TaraWeight">TaraWeight</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaraWeight attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GrossDepth name="GrossDepth">GrossDepth</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GrossDepth attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GrossWidth name="GrossWidth">GrossWidth</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GrossWidth attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GrossHeight name="GrossHeight">GrossHeight</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GrossHeight attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnitVolume name="UnitVolume">UnitVolume</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitVolume attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BatchNumGroupId name="BatchNumGroupId">BatchNumGroupId</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BatchNumGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SerialNumGroupId name="SerialNumGroupId">SerialNumGroupId</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SerialNumGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WMSArrivalHandlingTime name="WMSArrivalHandlingTime">WMSArrivalHandlingTime</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WMSArrivalHandlingTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SortCode name="SortCode">SortCode</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SortCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PackagingGroupId name="PackagingGroupId">PackagingGroupId</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackagingGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxPackagingQty name="TaxPackagingQty">TaxPackagingQty</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxPackagingQty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CostGroupId name="CostGroupId">CostGroupId</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryPriceDate name="InventoryPriceDate">InventoryPriceDate</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryPriceDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryPrice name="InventoryPrice">InventoryPrice</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryPrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryPriceUnit name="InventoryPriceUnit">InventoryPriceUnit</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryPriceUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryMarkup name="InventoryMarkup">InventoryMarkup</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryMarkup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryPriceQty name="InventoryPriceQty">InventoryPriceQty</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryPriceQty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryAllocateMarkup name="InventoryAllocateMarkup">InventoryAllocateMarkup</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryAllocateMarkup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ABCValue name="ABCValue">ABCValue</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ABCValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ABCContributionMargin name="ABCContributionMargin">ABCContributionMargin</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ABCContributionMargin attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ABCRevenue name="ABCRevenue">ABCRevenue</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ABCRevenue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ABCTieUp name="ABCTieUp">ABCTieUp</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ABCTieUp attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesInterCompanyBlocked name="SalesInterCompanyBlocked">SalesInterCompanyBlocked</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesInterCompanyBlocked attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesCommisionGroupId name="SalesCommisionGroupId">SalesCommisionGroupId</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesCommisionGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesPriceModel name="SalesPriceModel">SalesPriceModel</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPriceModel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesBasePriceModel name="SalesBasePriceModel">SalesBasePriceModel</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesBasePriceModel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesContributionRatio name="SalesContributionRatio">SalesContributionRatio</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesContributionRatio attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesPercentMarkup name="SalesPercentMarkup">SalesPercentMarkup</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPercentMarkup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesPriceDate name="SalesPriceDate">SalesPriceDate</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPriceDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesPrice name="SalesPrice">SalesPrice</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesPriceMarkup name="SalesPriceMarkup">SalesPriceMarkup</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPriceMarkup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesPriceMarkupQuantity name="SalesPriceMarkupQuantity">SalesPriceMarkupQuantity</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPriceMarkupQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesMarkupGroupId name="SalesMarkupGroupId">SalesMarkupGroupId</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesMarkupGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesAllocateMarkup name="SalesAllocateMarkup">SalesAllocateMarkup</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesAllocateMarkup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesLineDiscount name="SalesLineDiscount">SalesLineDiscount</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesLineDiscount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesMultiLineDiscount name="SalesMultiLineDiscount">SalesMultiLineDiscount</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesMultiLineDiscount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTotalDiscount name="SalesTotalDiscount">SalesTotalDiscount</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTotalDiscount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesSuppItemGroupId name="SalesSuppItemGroupId">SalesSuppItemGroupId</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesSuppItemGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesUseAltItemId name="SalesUseAltItemId">SalesUseAltItemId</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesUseAltItemId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesAltItemId name="SalesAltItemId">SalesAltItemId</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesAltItemId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesAltConfigId name="SalesAltConfigId">SalesAltConfigId</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesAltConfigId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesAltInventSizeId name="SalesAltInventSizeId">SalesAltInventSizeId</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesAltInventSizeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesAltInventColorId name="SalesAltInventColorId">SalesAltInventColorId</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesAltInventColorId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesAltInventStyleId name="SalesAltInventStyleId">SalesAltInventStyleId</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesAltInventStyleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesInstallmentEligible name="SalesInstallmentEligible">SalesInstallmentEligible</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesInstallmentEligible attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesPDSPricingPrecision name="SalesPDSPricingPrecision">SalesPDSPricingPrecision</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPDSPricingPrecision attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesFTCExempt name="SalesFTCExempt">SalesFTCExempt</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesFTCExempt attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesAllowPriceAdjust name="SalesAllowPriceAdjust">SalesAllowPriceAdjust</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesAllowPriceAdjust attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesContinuityScheduleId name="SalesContinuityScheduleId">SalesContinuityScheduleId</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesContinuityScheduleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesStartDate name="SalesStartDate">SalesStartDate</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesStartDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesEndDate name="SalesEndDate">SalesEndDate</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesEndDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesPdsItemRebateGroupId name="SalesPdsItemRebateGroupId">SalesPdsItemRebateGroupId</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPdsItemRebateGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesPdsFreightAllocationGroupId name="SalesPdsFreightAllocationGroupId">SalesPdsFreightAllocationGroupId</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPdsFreightAllocationGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailBarCodeUseEANStandard name="RetailBarCodeUseEANStandard">RetailBarCodeUseEANStandard</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailBarCodeUseEANStandard attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailBlockedAtRegister name="RetailBlockedAtRegister">RetailBlockedAtRegister</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailBlockedAtRegister attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailDateBlocked name="RetailDateBlocked">RetailDateBlocked</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailDateBlocked attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailDateToActivateItem name="RetailDateToActivateItem">RetailDateToActivateItem</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailDateToActivateItem attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailDateToBeBlocked name="RetailDateToBeBlocked">RetailDateToBeBlocked</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailDateToBeBlocked attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailPOSAllowNegativeQuantity name="RetailPOSAllowNegativeQuantity">RetailPOSAllowNegativeQuantity</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailPOSAllowNegativeQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailPOSDisallowDiscount name="RetailPOSDisallowDiscount">RetailPOSDisallowDiscount</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailPOSDisallowDiscount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailPOSIsScaleItem name="RetailPOSIsScaleItem">RetailPOSIsScaleItem</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailPOSIsScaleItem attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailPOSIsZeroPriceValid name="RetailPOSIsZeroPriceValid">RetailPOSIsZeroPriceValid</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailPOSIsZeroPriceValid attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailPOSKeyingInPrice name="RetailPOSKeyingInPrice">RetailPOSKeyingInPrice</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailPOSKeyingInPrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailPOSKeyingInQuantity name="RetailPOSKeyingInQuantity">RetailPOSKeyingInQuantity</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailPOSKeyingInQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailPOSMustKeyInComment name="RetailPOSMustKeyInComment">RetailPOSMustKeyInComment</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailPOSMustKeyInComment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailPOSDisallowManualDiscount name="RetailPOSDisallowManualDiscount">RetailPOSDisallowManualDiscount</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailPOSDisallowManualDiscount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailPrintVariantsShelfLabels name="RetailPrintVariantsShelfLabels">RetailPrintVariantsShelfLabels</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailPrintVariantsShelfLabels attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailSeasonCode name="RetailSeasonCode">RetailSeasonCode</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailSeasonCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailLifeFrom name="RetailLifeFrom">RetailLifeFrom</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailLifeFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailLifeTo name="RetailLifeTo">RetailLifeTo</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailLifeTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesRetailInventoryAvailabilityBuffer name="SalesRetailInventoryAvailabilityBuffer">SalesRetailInventoryAvailabilityBuffer</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesRetailInventoryAvailabilityBuffer attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesRetailInventoryAvailabilityLevelProfile name="SalesRetailInventoryAvailabilityLevelProfile">SalesRetailInventoryAvailabilityLevelProfile</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesRetailInventoryAvailabilityLevelProfile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_RetailAttributesLegalEntityLookupRelationshipId name="BackingTable_RetailAttributesLegalEntityLookupRelationshipId">BackingTable_RetailAttributesLegalEntityLookupRelationshipId</a>

First included in: Merchandising/RetailAttributesLegalEntityLookupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailAttributesLegalEntityLookupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Commerce/Merchandising/Miscellaneous/RetailAttributesLegalEntityLookup.md" target="_blank">/core/operationsCommon/Tables/Commerce/Merchandising/Miscellaneous/RetailAttributesLegalEntityLookup.cdm.json/RetailAttributesLegalEntityLookup</a></td><td><a href="../../../Tables/Commerce/Merchandising/Miscellaneous/RetailAttributesLegalEntityLookup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
