---
title: RetailAttributesLegalEntityLookup in Miscellaneous - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Retail product legal entity properties in Miscellaneous(RetailAttributesLegalEntityLookup)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Commerce/Merchandising/Miscellaneous/RetailAttributesLegalEntityLookup.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailAttributesLegalEntityLookup/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Retail product category attributes</td></tr><tr><td>en</td><td>Retail product legal entity properties</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[Category](#Category)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[EcoResInstanceValue](#EcoResInstanceValue)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[InstanceRelationType](#InstanceRelationType)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[isSynchronized](#isSynchronized)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[LegalEntity](#LegalEntity)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[Relationship_CategoryInstanceRelationshipId](#Relationship_CategoryInstanceRelationshipId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[Relationship_EcoResCategoryRelationshipId](#Relationship_EcoResCategoryRelationshipId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[Relationship_LegalEntityRelationshipId](#Relationship_LegalEntityRelationshipId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[BarCodeSetup](#BarCodeSetup)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[ExceptionCode_BR](#ExceptionCode_BR)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[GroupCounting](#GroupCounting)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[GroupCoverage](#GroupCoverage)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[GroupInventoryModel](#GroupInventoryModel)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[GroupItemGroup](#GroupItemGroup)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[ICMSOnService_BR](#ICMSOnService_BR)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[InventProductType_BR](#InventProductType_BR)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[ItemDataAreaId](#ItemDataAreaId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[ItemSalesTaxGroupPurch](#ItemSalesTaxGroupPurch)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[ItemSalesTaxGroupSales](#ItemSalesTaxGroupSales)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[ReplenishmentRule](#ReplenishmentRule)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[ReportItemLabel](#ReportItemLabel)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[ReportShelfLabel](#ReportShelfLabel)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[ReturnPolicy](#ReturnPolicy)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[SiteId](#SiteId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[TaxationOrigin_BR](#TaxationOrigin_BR)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[TaxFiscalClassification_BR](#TaxFiscalClassification_BR)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[TaxServiceCode_BR](#TaxServiceCode_BR)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[UnitBaseComparison](#UnitBaseComparison)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[UnitBOM](#UnitBOM)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[UnitInvent](#UnitInvent)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[UnitPrice](#UnitPrice)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[UnitPriceSales](#UnitPriceSales)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[UnitPurchase](#UnitPurchase)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[UnitSales](#UnitSales)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[WarehouseInvent](#WarehouseInvent)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[WarehousePurch](#WarehousePurch)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[WarehouseSales](#WarehouseSales)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[LabelAttribute1](#LabelAttribute1)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[LabelAttribute2](#LabelAttribute2)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[LabelAttribute3](#LabelAttribute3)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[LabelAttribute4](#LabelAttribute4)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[LabelAttribute5](#LabelAttribute5)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[Infocode](#Infocode)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[ReservationHierarchy](#ReservationHierarchy)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[UOMSeqGroupId](#UOMSeqGroupId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[PurchaseOverdeliveryPct](#PurchaseOverdeliveryPct)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[PurchaseUnderdeliveryPct](#PurchaseUnderdeliveryPct)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[SalesOverdeliveryPct](#SalesOverdeliveryPct)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[SalesUnderdeliveryPct](#SalesUnderdeliveryPct)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[InventoryOverdeliveryPct](#InventoryOverdeliveryPct)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[InventoryUnderdeliveryPct](#InventoryUnderdeliveryPct)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[PurchModel](#PurchModel)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[CostModel](#CostModel)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[ItemBuyerGroupId](#ItemBuyerGroupId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[PurchaseInterCompanyBlocked](#PurchaseInterCompanyBlocked)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[ItemPriceToleranceGroupId](#ItemPriceToleranceGroupId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[PrimaryVendorId](#PrimaryVendorId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[PurchasePriceDate](#PurchasePriceDate)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[PurchasePrice](#PurchasePrice)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[PurchaseMarkup](#PurchaseMarkup)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[PurchasePriceQty](#PurchasePriceQty)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[PurchaseMarkupGroupId](#PurchaseMarkupGroupId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[PurchaseAllocateMarkup](#PurchaseAllocateMarkup)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[PurchaseLineDisc](#PurchaseLineDisc)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[PurchaseMultiLineDisc](#PurchaseMultiLineDisc)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[PurchaseEndDisc](#PurchaseEndDisc)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[PurchaseSuppItemGroupId](#PurchaseSuppItemGroupId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[PurchasePDSPricingPrecision](#PurchasePDSPricingPrecision)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[ItemVendRebateGroupId](#ItemVendRebateGroupId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[PdsVendorCheckItem](#PdsVendorCheckItem)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[NetWeight](#NetWeight)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[TaraWeight](#TaraWeight)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[GrossDepth](#GrossDepth)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[GrossWidth](#GrossWidth)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[GrossHeight](#GrossHeight)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[UnitVolume](#UnitVolume)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[BatchNumGroupId](#BatchNumGroupId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[SerialNumGroupId](#SerialNumGroupId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[WMSArrivalHandlingTime](#WMSArrivalHandlingTime)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[SortCode](#SortCode)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[PackagingGroupId](#PackagingGroupId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[TaxPackagingQty](#TaxPackagingQty)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[CostGroupId](#CostGroupId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[InventoryPriceDate](#InventoryPriceDate)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[InventoryPrice](#InventoryPrice)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[InventoryPriceUnit](#InventoryPriceUnit)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[InventoryMarkup](#InventoryMarkup)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[InventoryPriceQty](#InventoryPriceQty)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[InventoryAllocateMarkup](#InventoryAllocateMarkup)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[ABCValue](#ABCValue)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[ABCContributionMargin](#ABCContributionMargin)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[ABCRevenue](#ABCRevenue)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[ABCTieUp](#ABCTieUp)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[SalesInterCompanyBlocked](#SalesInterCompanyBlocked)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[SalesCommisionGroupId](#SalesCommisionGroupId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[SalesPriceModel](#SalesPriceModel)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[SalesBasePriceModel](#SalesBasePriceModel)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[SalesContributionRatio](#SalesContributionRatio)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[SalesPercentMarkup](#SalesPercentMarkup)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[SalesPriceDate](#SalesPriceDate)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[SalesPrice](#SalesPrice)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[SalesPriceMarkup](#SalesPriceMarkup)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[SalesPriceMarkupQuantity](#SalesPriceMarkupQuantity)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[SalesMarkupGroupId](#SalesMarkupGroupId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[SalesAllocateMarkup](#SalesAllocateMarkup)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[SalesLineDiscount](#SalesLineDiscount)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[SalesMultiLineDiscount](#SalesMultiLineDiscount)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[SalesTotalDiscount](#SalesTotalDiscount)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[SalesSuppItemGroupId](#SalesSuppItemGroupId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[SalesUseAltItemId](#SalesUseAltItemId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[SalesAltItemId](#SalesAltItemId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[SalesAltConfigId](#SalesAltConfigId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[SalesAltInventSizeId](#SalesAltInventSizeId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[SalesAltInventColorId](#SalesAltInventColorId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[SalesAltInventStyleId](#SalesAltInventStyleId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[SalesInstallmentEligible](#SalesInstallmentEligible)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[SalesPDSPricingPrecision](#SalesPDSPricingPrecision)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[SalesFTCExempt](#SalesFTCExempt)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[SalesAllowPriceAdjust](#SalesAllowPriceAdjust)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[SalesContinuityScheduleId](#SalesContinuityScheduleId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[SalesStartDate](#SalesStartDate)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[SalesEndDate](#SalesEndDate)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[SalesPdsItemRebateGroupId](#SalesPdsItemRebateGroupId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[SalesPdsFreightAllocationGroupId](#SalesPdsFreightAllocationGroupId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[RetailBarCodeUseEANStandard](#RetailBarCodeUseEANStandard)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[RetailBlockedAtRegister](#RetailBlockedAtRegister)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[RetailDateBlocked](#RetailDateBlocked)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[RetailDateToActivateItem](#RetailDateToActivateItem)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[RetailDateToBeBlocked](#RetailDateToBeBlocked)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[RetailPOSAllowNegativeQuantity](#RetailPOSAllowNegativeQuantity)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[RetailPOSDisallowDiscount](#RetailPOSDisallowDiscount)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[RetailPOSIsScaleItem](#RetailPOSIsScaleItem)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[RetailPOSIsZeroPriceValid](#RetailPOSIsZeroPriceValid)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[RetailPOSKeyingInPrice](#RetailPOSKeyingInPrice)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[RetailPOSKeyingInQuantity](#RetailPOSKeyingInQuantity)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[RetailPOSMustKeyInComment](#RetailPOSMustKeyInComment)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[RetailProhibitReturn_RU](#RetailProhibitReturn_RU)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[RetailPOSDisallowManualDiscount](#RetailPOSDisallowManualDiscount)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[RetailPrintVariantsShelfLabels](#RetailPrintVariantsShelfLabels)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[RetailSeasonCode](#RetailSeasonCode)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[RetailLifeFrom](#RetailLifeFrom)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[RetailLifeTo](#RetailLifeTo)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[SalesRetailInventoryAvailabilityBuffer](#SalesRetailInventoryAvailabilityBuffer)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[SalesRetailInventoryAvailabilityLevelProfile](#SalesRetailInventoryAvailabilityLevelProfile)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[SalesAltInventVersionId](#SalesAltInventVersionId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[Relationship_BarcodeSetupRelationshipId](#Relationship_BarcodeSetupRelationshipId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[Relationship_ExceptionCode_BRRelationshipId](#Relationship_ExceptionCode_BRRelationshipId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[Relationship_GroupCountingRelationshipId](#Relationship_GroupCountingRelationshipId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[Relationship_GroupCoverageRelationshipId](#Relationship_GroupCoverageRelationshipId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[Relationship_GroupInventoryModelRelationshipId](#Relationship_GroupInventoryModelRelationshipId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[Relationship_GroupItemGroupRelationshipId](#Relationship_GroupItemGroupRelationshipId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[Relationship_InventProductType_BRRelationshipId](#Relationship_InventProductType_BRRelationshipId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[Relationship_ItemSalesTaxGroupPurchRelationshipId](#Relationship_ItemSalesTaxGroupPurchRelationshipId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[Relationship_ItemSalesTaxGroupSalesRelationshipId](#Relationship_ItemSalesTaxGroupSalesRelationshipId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[Relationship_ReplenishmentRuleRelationshipId](#Relationship_ReplenishmentRuleRelationshipId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[Relationship_ReportItemLabelRelationshipId](#Relationship_ReportItemLabelRelationshipId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[Relationship_ReportShelfLabelRelationshipId](#Relationship_ReportShelfLabelRelationshipId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[Relationship_RetailReturnPolicyRelationshipId](#Relationship_RetailReturnPolicyRelationshipId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[Relationship_SiteIdRelationshipId](#Relationship_SiteIdRelationshipId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[Relationship_TaxFiscalClassification_BRRelationshipId](#Relationship_TaxFiscalClassification_BRRelationshipId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[Relationship_TaxServiceCode_BRRelationshipId](#Relationship_TaxServiceCode_BRRelationshipId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[Relationship_WarehouseInventRelationshipId](#Relationship_WarehouseInventRelationshipId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[Relationship_WarehousePurchRelationshipId](#Relationship_WarehousePurchRelationshipId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[Relationship_WarehouseSalesRelationshipId](#Relationship_WarehouseSalesRelationshipId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[Relationship_LabelAttribute1RelationshipId](#Relationship_LabelAttribute1RelationshipId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[Relationship_LabelAttribute2RelationshipId](#Relationship_LabelAttribute2RelationshipId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[Relationship_LabelAttribute3RelationshipId](#Relationship_LabelAttribute3RelationshipId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[Relationship_LabelAttribute4RelationshipId](#Relationship_LabelAttribute4RelationshipId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[Relationship_LabelAttribute5RelationshipId](#Relationship_LabelAttribute5RelationshipId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[Relationship_RetailInfoCodeRelationshipId](#Relationship_RetailInfoCodeRelationshipId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[Relationship_WHSReservationHierarchyRelationshipId](#Relationship_WHSReservationHierarchyRelationshipId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[Relationship_WHSUOMSeqGroupTableRelationshipId](#Relationship_WHSUOMSeqGroupTableRelationshipId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[Relationship_InventItemPriceToleranceGroupRelationshipId](#Relationship_InventItemPriceToleranceGroupRelationshipId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[Relationship_InventPackagingGroupRelationshipId](#Relationship_InventPackagingGroupRelationshipId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[Relationship_BOMCostGroupRelationshipId](#Relationship_BOMCostGroupRelationshipId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[Relationship_TAMItemVendRebateGroupRelationshipId](#Relationship_TAMItemVendRebateGroupRelationshipId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[Relationship_CommissionItemGroupRelationshipId](#Relationship_CommissionItemGroupRelationshipId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[Relationship_MCRContinuityScheduleHeaderRelationshipId](#Relationship_MCRContinuityScheduleHeaderRelationshipId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[Relationship_PdsItemRebateGroupRelationshipId](#Relationship_PdsItemRebateGroupRelationshipId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|
|[Relationship_PdsFreightGroupRelationshipId](#Relationship_PdsFreightGroupRelationshipId)||<a href="RetailAttributesLegalEntityLookup.md" target="_blank">Miscellaneous/RetailAttributesLegalEntityLookup</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailAttributesLegalEntityLookup/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Category name="Category">Category</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Category attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#EcoResInstanceValue name="EcoResInstanceValue">EcoResInstanceValue</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EcoResInstanceValue attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#InstanceRelationType name="InstanceRelationType">InstanceRelationType</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InstanceRelationType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#isSynchronized name="isSynchronized">isSynchronized</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the isSynchronized attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#LegalEntity name="LegalEntity">LegalEntity</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LegalEntity attribute are listed below.</summary>

</details>

### <a href=#Relationship_CategoryInstanceRelationshipId name="Relationship_CategoryInstanceRelationshipId">Relationship_CategoryInstanceRelationshipId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CategoryInstanceRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResCategoryInstanceValue.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/EcoResCategoryInstanceValue.cdm.json/EcoResCategoryInstanceValue</a></td><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResCategoryInstanceValue.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_EcoResCategoryRelationshipId name="Relationship_EcoResCategoryRelationshipId">Relationship_EcoResCategoryRelationshipId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EcoResCategoryRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResCategory.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/EcoResCategory.cdm.json/EcoResCategory</a></td><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResCategory.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LegalEntityRelationshipId name="Relationship_LegalEntityRelationshipId">Relationship_LegalEntityRelationshipId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LegalEntityRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BarCodeSetup name="BarCodeSetup">BarCodeSetup</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

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

### <a href=#ExceptionCode_BR name="ExceptionCode_BR">ExceptionCode_BR</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExceptionCode_BR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GroupCounting name="GroupCounting">GroupCounting</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

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

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

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

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

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

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

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

### <a href=#ICMSOnService_BR name="ICMSOnService_BR">ICMSOnService_BR</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ICMSOnService_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#InventProductType_BR name="InventProductType_BR">InventProductType_BR</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventProductType_BR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemDataAreaId name="ItemDataAreaId">ItemDataAreaId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemSalesTaxGroupPurch name="ItemSalesTaxGroupPurch">ItemSalesTaxGroupPurch</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purchase order sales tax group</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemSalesTaxGroupPurch attribute are listed below.</summary>

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

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

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

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

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

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

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

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

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

### <a href=#ReturnPolicy name="ReturnPolicy">ReturnPolicy</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Return location</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnPolicy attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Return location</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SiteId name="SiteId">SiteId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

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

### <a href=#TaxationOrigin_BR name="TaxationOrigin_BR">TaxationOrigin_BR</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxationOrigin_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TaxFiscalClassification_BR name="TaxFiscalClassification_BR">TaxFiscalClassification_BR</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxFiscalClassification_BR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxServiceCode_BR name="TaxServiceCode_BR">TaxServiceCode_BR</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxServiceCode_BR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnitBaseComparison name="UnitBaseComparison">UnitBaseComparison</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Base comparison unit</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitBaseComparison attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Base comparison unit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#UnitBOM name="UnitBOM">UnitBOM</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>BOM unit</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitBOM attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>BOM unit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#UnitInvent name="UnitInvent">UnitInvent</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Inventory unit</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitInvent attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Inventory unit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#UnitPrice name="UnitPrice">UnitPrice</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purchase price unit</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitPrice attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchase price unit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#UnitPriceSales name="UnitPriceSales">UnitPriceSales</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales price unit</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitPriceSales attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales price unit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#UnitPurchase name="UnitPurchase">UnitPurchase</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purchase unit</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitPurchase attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchase unit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#UnitSales name="UnitSales">UnitSales</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales unit</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitSales attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales unit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#WarehouseInvent name="WarehouseInvent">WarehouseInvent</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Inventory warehouse</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseInvent attribute are listed below.</summary>

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

### <a href=#WarehousePurch name="WarehousePurch">WarehousePurch</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purchase warehouse</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehousePurch attribute are listed below.</summary>

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

### <a href=#WarehouseSales name="WarehouseSales">WarehouseSales</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales warehouse</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseSales attribute are listed below.</summary>

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

### <a href=#LabelAttribute1 name="LabelAttribute1">LabelAttribute1</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Label attribute 1</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LabelAttribute1 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Label attribute 1</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LabelAttribute2 name="LabelAttribute2">LabelAttribute2</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Label attribute 2</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LabelAttribute2 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Label attribute 2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LabelAttribute3 name="LabelAttribute3">LabelAttribute3</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Label attribute 3</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LabelAttribute3 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Label attribute 3</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LabelAttribute4 name="LabelAttribute4">LabelAttribute4</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Label attribute 4</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LabelAttribute4 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Label attribute 4</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LabelAttribute5 name="LabelAttribute5">LabelAttribute5</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Label attribute 5</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LabelAttribute5 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Label attribute 5</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Infocode name="Infocode">Infocode</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Infocode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReservationHierarchy name="ReservationHierarchy">ReservationHierarchy</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReservationHierarchy attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#UOMSeqGroupId name="UOMSeqGroupId">UOMSeqGroupId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UOMSeqGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseOverdeliveryPct name="PurchaseOverdeliveryPct">PurchaseOverdeliveryPct</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purchase overdelivery</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseOverdeliveryPct attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchase overdelivery</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PurchaseUnderdeliveryPct name="PurchaseUnderdeliveryPct">PurchaseUnderdeliveryPct</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Purchase underdelivery</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseUnderdeliveryPct attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchase underdelivery</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SalesOverdeliveryPct name="SalesOverdeliveryPct">SalesOverdeliveryPct</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales overdelivery</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesOverdeliveryPct attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales overdelivery</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SalesUnderdeliveryPct name="SalesUnderdeliveryPct">SalesUnderdeliveryPct</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales underdelivery</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesUnderdeliveryPct attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales underdelivery</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InventoryOverdeliveryPct name="InventoryOverdeliveryPct">InventoryOverdeliveryPct</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Inventory overdelivery</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryOverdeliveryPct attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Inventory overdelivery</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InventoryUnderdeliveryPct name="InventoryUnderdeliveryPct">InventoryUnderdeliveryPct</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Inventory underdelivery</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryUnderdeliveryPct attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Inventory underdelivery</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PurchModel name="PurchModel">PurchModel</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Latest purchase price</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchModel attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Latest purchase price</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#CostModel name="CostModel">CostModel</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Latest cost price</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CostModel attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Latest cost price</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ItemBuyerGroupId name="ItemBuyerGroupId">ItemBuyerGroupId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Buyer group</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemBuyerGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Buyer group</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseInterCompanyBlocked name="PurchaseInterCompanyBlocked">PurchaseInterCompanyBlocked</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseInterCompanyBlocked attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ItemPriceToleranceGroupId name="ItemPriceToleranceGroupId">ItemPriceToleranceGroupId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

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

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

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

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchasePriceDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#PurchasePrice name="PurchasePrice">PurchasePrice</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchasePrice attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PurchaseMarkup name="PurchaseMarkup">PurchaseMarkup</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseMarkup attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PurchasePriceQty name="PurchasePriceQty">PurchasePriceQty</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchasePriceQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PurchaseMarkupGroupId name="PurchaseMarkupGroupId">PurchaseMarkupGroupId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

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

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseAllocateMarkup attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PurchaseLineDisc name="PurchaseLineDisc">PurchaseLineDisc</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

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

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Multiline discount</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseMultiLineDisc attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Multiline discount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseEndDisc name="PurchaseEndDisc">PurchaseEndDisc</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total discount</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseEndDisc attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Total discount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#PurchaseSuppItemGroupId name="PurchaseSuppItemGroupId">PurchaseSuppItemGroupId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

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

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchasePDSPricingPrecision attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ItemVendRebateGroupId name="ItemVendRebateGroupId">ItemVendRebateGroupId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

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

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PdsVendorCheckItem attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#NetWeight name="NetWeight">NetWeight</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NetWeight attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaraWeight name="TaraWeight">TaraWeight</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaraWeight attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#GrossDepth name="GrossDepth">GrossDepth</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Gross depth</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GrossDepth attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Gross depth</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#GrossWidth name="GrossWidth">GrossWidth</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Gross width</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GrossWidth attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Gross width</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#GrossHeight name="GrossHeight">GrossHeight</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Gross height</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GrossHeight attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Gross height</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#UnitVolume name="UnitVolume">UnitVolume</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitVolume attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#BatchNumGroupId name="BatchNumGroupId">BatchNumGroupId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Batch number group</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BatchNumGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Batch number group</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SerialNumGroupId name="SerialNumGroupId">SerialNumGroupId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Serial number group</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SerialNumGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Serial number group</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WMSArrivalHandlingTime name="WMSArrivalHandlingTime">WMSArrivalHandlingTime</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WMSArrivalHandlingTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
</details>

### <a href=#SortCode name="SortCode">SortCode</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SortCode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PackagingGroupId name="PackagingGroupId">PackagingGroupId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

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

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxPackagingQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CostGroupId name="CostGroupId">CostGroupId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

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

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryPriceDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#InventoryPrice name="InventoryPrice">InventoryPrice</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryPrice attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InventoryPriceUnit name="InventoryPriceUnit">InventoryPriceUnit</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryPriceUnit attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InventoryMarkup name="InventoryMarkup">InventoryMarkup</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryMarkup attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InventoryPriceQty name="InventoryPriceQty">InventoryPriceQty</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryPriceQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InventoryAllocateMarkup name="InventoryAllocateMarkup">InventoryAllocateMarkup</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryAllocateMarkup attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ABCValue name="ABCValue">ABCValue</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>ABC-code value</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ABCValue attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>ABC-code value</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ABCContributionMargin name="ABCContributionMargin">ABCContributionMargin</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>ABC-code margin</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ABCContributionMargin attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>ABC-code margin</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ABCRevenue name="ABCRevenue">ABCRevenue</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>ABC-code revenue</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ABCRevenue attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>ABC-code revenue</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ABCTieUp name="ABCTieUp">ABCTieUp</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>ABC-code carrying cost</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ABCTieUp attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>ABC-code carrying cost</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#SalesInterCompanyBlocked name="SalesInterCompanyBlocked">SalesInterCompanyBlocked</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesInterCompanyBlocked attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#SalesCommisionGroupId name="SalesCommisionGroupId">SalesCommisionGroupId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Commission group</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesCommisionGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Commission group</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesPriceModel name="SalesPriceModel">SalesPriceModel</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPriceModel attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#SalesBasePriceModel name="SalesBasePriceModel">SalesBasePriceModel</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesBasePriceModel attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#SalesContributionRatio name="SalesContributionRatio">SalesContributionRatio</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesContributionRatio attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SalesPercentMarkup name="SalesPercentMarkup">SalesPercentMarkup</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPercentMarkup attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SalesPriceDate name="SalesPriceDate">SalesPriceDate</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPriceDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#SalesPrice name="SalesPrice">SalesPrice</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPrice attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SalesPriceMarkup name="SalesPriceMarkup">SalesPriceMarkup</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPriceMarkup attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SalesPriceMarkupQuantity name="SalesPriceMarkupQuantity">SalesPriceMarkupQuantity</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPriceMarkupQuantity attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SalesMarkupGroupId name="SalesMarkupGroupId">SalesMarkupGroupId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

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

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesAllocateMarkup attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#SalesLineDiscount name="SalesLineDiscount">SalesLineDiscount</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

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

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Multiline discount</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesMultiLineDiscount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Multiline discount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTotalDiscount name="SalesTotalDiscount">SalesTotalDiscount</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total discount</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTotalDiscount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Total discount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#SalesSuppItemGroupId name="SalesSuppItemGroupId">SalesSuppItemGroupId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

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

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>When to use</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesUseAltItemId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>When to use</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#SalesAltItemId name="SalesAltItemId">SalesAltItemId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

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

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

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

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Alternative size</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesAltInventSizeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Alternative size</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesAltInventColorId name="SalesAltInventColorId">SalesAltInventColorId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Alternative color</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesAltInventColorId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Alternative color</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesAltInventStyleId name="SalesAltInventStyleId">SalesAltInventStyleId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Alternative style</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesAltInventStyleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Alternative style</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesInstallmentEligible name="SalesInstallmentEligible">SalesInstallmentEligible</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesInstallmentEligible attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#SalesPDSPricingPrecision name="SalesPDSPricingPrecision">SalesPDSPricingPrecision</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPDSPricingPrecision attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#SalesFTCExempt name="SalesFTCExempt">SalesFTCExempt</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesFTCExempt attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#SalesAllowPriceAdjust name="SalesAllowPriceAdjust">SalesAllowPriceAdjust</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow price adjust</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesAllowPriceAdjust attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Allow price adjust</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#SalesContinuityScheduleId name="SalesContinuityScheduleId">SalesContinuityScheduleId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Continuity schedule ID</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesContinuityScheduleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Continuity schedule ID</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesStartDate name="SalesStartDate">SalesStartDate</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesStartDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#SalesEndDate name="SalesEndDate">SalesEndDate</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesEndDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#SalesPdsItemRebateGroupId name="SalesPdsItemRebateGroupId">SalesPdsItemRebateGroupId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

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

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

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

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Use EAN standard bar code</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailBarCodeUseEANStandard attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Use EAN standard bar code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#RetailBlockedAtRegister name="RetailBlockedAtRegister">RetailBlockedAtRegister</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Blocked at register</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailBlockedAtRegister attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Blocked at register</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#RetailDateBlocked name="RetailDateBlocked">RetailDateBlocked</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailDateBlocked attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#RetailDateToActivateItem name="RetailDateToActivateItem">RetailDateToActivateItem</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailDateToActivateItem attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#RetailDateToBeBlocked name="RetailDateToBeBlocked">RetailDateToBeBlocked</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailDateToBeBlocked attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#RetailPOSAllowNegativeQuantity name="RetailPOSAllowNegativeQuantity">RetailPOSAllowNegativeQuantity</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailPOSAllowNegativeQuantity attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RetailPOSDisallowDiscount name="RetailPOSDisallowDiscount">RetailPOSDisallowDiscount</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailPOSDisallowDiscount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RetailPOSIsScaleItem name="RetailPOSIsScaleItem">RetailPOSIsScaleItem</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailPOSIsScaleItem attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RetailPOSIsZeroPriceValid name="RetailPOSIsZeroPriceValid">RetailPOSIsZeroPriceValid</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailPOSIsZeroPriceValid attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RetailPOSKeyingInPrice name="RetailPOSKeyingInPrice">RetailPOSKeyingInPrice</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailPOSKeyingInPrice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RetailPOSKeyingInQuantity name="RetailPOSKeyingInQuantity">RetailPOSKeyingInQuantity</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailPOSKeyingInQuantity attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RetailPOSMustKeyInComment name="RetailPOSMustKeyInComment">RetailPOSMustKeyInComment</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailPOSMustKeyInComment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RetailProhibitReturn_RU name="RetailProhibitReturn_RU">RetailProhibitReturn_RU</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailProhibitReturn_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RetailPOSDisallowManualDiscount name="RetailPOSDisallowManualDiscount">RetailPOSDisallowManualDiscount</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailPOSDisallowManualDiscount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RetailPrintVariantsShelfLabels name="RetailPrintVariantsShelfLabels">RetailPrintVariantsShelfLabels</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailPrintVariantsShelfLabels attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RetailSeasonCode name="RetailSeasonCode">RetailSeasonCode</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

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

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailLifeFrom attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#RetailLifeTo name="RetailLifeTo">RetailLifeTo</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailLifeTo attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#SalesRetailInventoryAvailabilityBuffer name="SalesRetailInventoryAvailabilityBuffer">SalesRetailInventoryAvailabilityBuffer</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesRetailInventoryAvailabilityBuffer attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SalesRetailInventoryAvailabilityLevelProfile name="SalesRetailInventoryAvailabilityLevelProfile">SalesRetailInventoryAvailabilityLevelProfile</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Inventory level profile</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesRetailInventoryAvailabilityLevelProfile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Inventory level profile</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesAltInventVersionId name="SalesAltInventVersionId">SalesAltInventVersionId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Alternative version</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesAltInventVersionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Alternative version</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BarcodeSetupRelationshipId name="Relationship_BarcodeSetupRelationshipId">Relationship_BarcodeSetupRelationshipId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BarcodeSetupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Inventory/Group/BarcodeSetup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/BarcodeSetup.cdm.json/BarcodeSetup</a></td><td><a href="../../../SupplyChain/Inventory/Group/BarcodeSetup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ExceptionCode_BRRelationshipId name="Relationship_ExceptionCode_BRRelationshipId">Relationship_ExceptionCode_BRRelationshipId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ExceptionCode_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/APARShared/Miscellaneous/ExceptionCodeTable_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/APARShared/Miscellaneous/ExceptionCodeTable_BR.cdm.json/ExceptionCodeTable_BR</a></td><td><a href="../../../Finance/APARShared/Miscellaneous/ExceptionCodeTable_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_GroupCountingRelationshipId name="Relationship_GroupCountingRelationshipId">Relationship_GroupCountingRelationshipId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_GroupCountingRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Inventory/Group/InventCountGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/InventCountGroup.cdm.json/InventCountGroup</a></td><td><a href="../../../SupplyChain/Inventory/Group/InventCountGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_GroupCoverageRelationshipId name="Relationship_GroupCoverageRelationshipId">Relationship_GroupCoverageRelationshipId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_GroupCoverageRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/MasterPlanning/Group/ReqGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/MasterPlanning/Group/ReqGroup.cdm.json/ReqGroup</a></td><td><a href="../../../SupplyChain/MasterPlanning/Group/ReqGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_GroupInventoryModelRelationshipId name="Relationship_GroupInventoryModelRelationshipId">Relationship_GroupInventoryModelRelationshipId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_GroupInventoryModelRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Inventory/Group/InventModelGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/InventModelGroup.cdm.json/InventModelGroup</a></td><td><a href="../../../SupplyChain/Inventory/Group/InventModelGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_GroupItemGroupRelationshipId name="Relationship_GroupItemGroupRelationshipId">Relationship_GroupItemGroupRelationshipId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_GroupItemGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Inventory/Group/InventItemGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/InventItemGroup.cdm.json/InventItemGroup</a></td><td><a href="../../../SupplyChain/Inventory/Group/InventItemGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventProductType_BRRelationshipId name="Relationship_InventProductType_BRRelationshipId">Relationship_InventProductType_BRRelationshipId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventProductType_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Inventory/Main/InventProductTypeTable_BR.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/InventProductTypeTable_BR.cdm.json/InventProductTypeTable_BR</a></td><td><a href="../../../SupplyChain/Inventory/Main/InventProductTypeTable_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ItemSalesTaxGroupPurchRelationshipId name="Relationship_ItemSalesTaxGroupPurchRelationshipId">Relationship_ItemSalesTaxGroupPurchRelationshipId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ItemSalesTaxGroupPurchRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Tax/Group/TaxItemGroupHeading.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxItemGroupHeading.cdm.json/TaxItemGroupHeading</a></td><td><a href="../../../Finance/Tax/Group/TaxItemGroupHeading.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ItemSalesTaxGroupSalesRelationshipId name="Relationship_ItemSalesTaxGroupSalesRelationshipId">Relationship_ItemSalesTaxGroupSalesRelationshipId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ItemSalesTaxGroupSalesRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Tax/Group/TaxItemGroupHeading.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxItemGroupHeading.cdm.json/TaxItemGroupHeading</a></td><td><a href="../../../Finance/Tax/Group/TaxItemGroupHeading.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ReplenishmentRuleRelationshipId name="Relationship_ReplenishmentRuleRelationshipId">Relationship_ReplenishmentRuleRelationshipId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReplenishmentRuleRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../InventoryAndAdvancedWarehouse/Main/RetailReplenishmentRuleTable.md" target="_blank">/core/operationsCommon/Tables/Commerce/InventoryAndAdvancedWarehouse/Main/RetailReplenishmentRuleTable.cdm.json/RetailReplenishmentRuleTable</a></td><td><a href="../../InventoryAndAdvancedWarehouse/Main/RetailReplenishmentRuleTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ReportItemLabelRelationshipId name="Relationship_ReportItemLabelRelationshipId">Relationship_ReportItemLabelRelationshipId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReportItemLabelRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../InventoryAndAdvancedWarehouse/Group/RetailInventItemLabelReportSetup.md" target="_blank">/core/operationsCommon/Tables/Commerce/InventoryAndAdvancedWarehouse/Group/RetailInventItemLabelReportSetup.cdm.json/RetailInventItemLabelReportSetup</a></td><td><a href="../../InventoryAndAdvancedWarehouse/Group/RetailInventItemLabelReportSetup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ReportShelfLabelRelationshipId name="Relationship_ReportShelfLabelRelationshipId">Relationship_ReportShelfLabelRelationshipId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReportShelfLabelRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../InventoryAndAdvancedWarehouse/Group/RetailInventItemLabelReportSetup.md" target="_blank">/core/operationsCommon/Tables/Commerce/InventoryAndAdvancedWarehouse/Group/RetailInventItemLabelReportSetup.cdm.json/RetailInventItemLabelReportSetup</a></td><td><a href="../../InventoryAndAdvancedWarehouse/Group/RetailInventItemLabelReportSetup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailReturnPolicyRelationshipId name="Relationship_RetailReturnPolicyRelationshipId">Relationship_RetailReturnPolicyRelationshipId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailReturnPolicyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../TransactionsAndOrders/Miscellaneous/RetailReturnPolicy.md" target="_blank">/core/operationsCommon/Tables/Commerce/TransactionsAndOrders/Miscellaneous/RetailReturnPolicy.cdm.json/RetailReturnPolicy</a></td><td><a href="../../TransactionsAndOrders/Miscellaneous/RetailReturnPolicy.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SiteIdRelationshipId name="Relationship_SiteIdRelationshipId">Relationship_SiteIdRelationshipId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SiteIdRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Inventory/Group/InventSite.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/InventSite.cdm.json/InventSite</a></td><td><a href="../../../SupplyChain/Inventory/Group/InventSite.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxFiscalClassification_BRRelationshipId name="Relationship_TaxFiscalClassification_BRRelationshipId">Relationship_TaxFiscalClassification_BRRelationshipId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxFiscalClassification_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Tax/Parameter/TaxFiscalClassification_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Parameter/TaxFiscalClassification_BR.cdm.json/TaxFiscalClassification_BR</a></td><td><a href="../../../Finance/Tax/Parameter/TaxFiscalClassification_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxServiceCode_BRRelationshipId name="Relationship_TaxServiceCode_BRRelationshipId">Relationship_TaxServiceCode_BRRelationshipId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxServiceCode_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Tax/Group/TaxServiceCode_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxServiceCode_BR.cdm.json/TaxServiceCode_BR</a></td><td><a href="../../../Finance/Tax/Group/TaxServiceCode_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WarehouseInventRelationshipId name="Relationship_WarehouseInventRelationshipId">Relationship_WarehouseInventRelationshipId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WarehouseInventRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Inventory/Group/InventLocation.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/InventLocation.cdm.json/InventLocation</a></td><td><a href="../../../SupplyChain/Inventory/Group/InventLocation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WarehousePurchRelationshipId name="Relationship_WarehousePurchRelationshipId">Relationship_WarehousePurchRelationshipId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WarehousePurchRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Inventory/Group/InventLocation.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/InventLocation.cdm.json/InventLocation</a></td><td><a href="../../../SupplyChain/Inventory/Group/InventLocation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WarehouseSalesRelationshipId name="Relationship_WarehouseSalesRelationshipId">Relationship_WarehouseSalesRelationshipId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WarehouseSalesRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Inventory/Group/InventLocation.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/InventLocation.cdm.json/InventLocation</a></td><td><a href="../../../SupplyChain/Inventory/Group/InventLocation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LabelAttribute1RelationshipId name="Relationship_LabelAttribute1RelationshipId">Relationship_LabelAttribute1RelationshipId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LabelAttribute1RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResAttribute.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/EcoResAttribute.cdm.json/EcoResAttribute</a></td><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResAttribute.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LabelAttribute2RelationshipId name="Relationship_LabelAttribute2RelationshipId">Relationship_LabelAttribute2RelationshipId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LabelAttribute2RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResAttribute.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/EcoResAttribute.cdm.json/EcoResAttribute</a></td><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResAttribute.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LabelAttribute3RelationshipId name="Relationship_LabelAttribute3RelationshipId">Relationship_LabelAttribute3RelationshipId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LabelAttribute3RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResAttribute.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/EcoResAttribute.cdm.json/EcoResAttribute</a></td><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResAttribute.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LabelAttribute4RelationshipId name="Relationship_LabelAttribute4RelationshipId">Relationship_LabelAttribute4RelationshipId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LabelAttribute4RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResAttribute.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/EcoResAttribute.cdm.json/EcoResAttribute</a></td><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResAttribute.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LabelAttribute5RelationshipId name="Relationship_LabelAttribute5RelationshipId">Relationship_LabelAttribute5RelationshipId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LabelAttribute5RelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResAttribute.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/EcoResAttribute.cdm.json/EcoResAttribute</a></td><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResAttribute.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailInfoCodeRelationshipId name="Relationship_RetailInfoCodeRelationshipId">Relationship_RetailInfoCodeRelationshipId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailInfoCodeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../TransactionsAndOrders/Main/RetailInfocode.md" target="_blank">/core/operationsCommon/Tables/Commerce/TransactionsAndOrders/Main/RetailInfocode.cdm.json/RetailInfocode</a></td><td><a href="../../TransactionsAndOrders/Main/RetailInfocode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WHSReservationHierarchyRelationshipId name="Relationship_WHSReservationHierarchyRelationshipId">Relationship_WHSReservationHierarchyRelationshipId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WHSReservationHierarchyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Inventory/Group/WHSReservationHierarchy.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/WHSReservationHierarchy.cdm.json/WHSReservationHierarchy</a></td><td><a href="../../../SupplyChain/Inventory/Group/WHSReservationHierarchy.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WHSUOMSeqGroupTableRelationshipId name="Relationship_WHSUOMSeqGroupTableRelationshipId">Relationship_WHSUOMSeqGroupTableRelationshipId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WHSUOMSeqGroupTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Inventory/Group/WHSUOMSeqGroupTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/WHSUOMSeqGroupTable.cdm.json/WHSUOMSeqGroupTable</a></td><td><a href="../../../SupplyChain/Inventory/Group/WHSUOMSeqGroupTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventItemPriceToleranceGroupRelationshipId name="Relationship_InventItemPriceToleranceGroupRelationshipId">Relationship_InventItemPriceToleranceGroupRelationshipId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventItemPriceToleranceGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/AccountsPayable/Group/InventItemPriceToleranceGroup.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsPayable/Group/InventItemPriceToleranceGroup.cdm.json/InventItemPriceToleranceGroup</a></td><td><a href="../../../Finance/AccountsPayable/Group/InventItemPriceToleranceGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventPackagingGroupRelationshipId name="Relationship_InventPackagingGroupRelationshipId">Relationship_InventPackagingGroupRelationshipId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventPackagingGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Inventory/Group/InventPackagingGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/InventPackagingGroup.cdm.json/InventPackagingGroup</a></td><td><a href="../../../SupplyChain/Inventory/Group/InventPackagingGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BOMCostGroupRelationshipId name="Relationship_BOMCostGroupRelationshipId">Relationship_BOMCostGroupRelationshipId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BOMCostGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Inventory/Group/BOMCostGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/BOMCostGroup.cdm.json/BOMCostGroup</a></td><td><a href="../../../SupplyChain/Inventory/Group/BOMCostGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TAMItemVendRebateGroupRelationshipId name="Relationship_TAMItemVendRebateGroupRelationshipId">Relationship_TAMItemVendRebateGroupRelationshipId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TAMItemVendRebateGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/SalesAndMarketing/Group/TAMItemVendRebateGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Group/TAMItemVendRebateGroup.cdm.json/TAMItemVendRebateGroup</a></td><td><a href="../../../SupplyChain/SalesAndMarketing/Group/TAMItemVendRebateGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CommissionItemGroupRelationshipId name="Relationship_CommissionItemGroupRelationshipId">Relationship_CommissionItemGroupRelationshipId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CommissionItemGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/SalesAndMarketing/Group/CommissionItemGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Group/CommissionItemGroup.cdm.json/CommissionItemGroup</a></td><td><a href="../../../SupplyChain/SalesAndMarketing/Group/CommissionItemGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_MCRContinuityScheduleHeaderRelationshipId name="Relationship_MCRContinuityScheduleHeaderRelationshipId">Relationship_MCRContinuityScheduleHeaderRelationshipId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MCRContinuityScheduleHeaderRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../TransactionsAndOrders/WorksheetHeader/MCRContinuityScheduleHeader.md" target="_blank">/core/operationsCommon/Tables/Commerce/TransactionsAndOrders/WorksheetHeader/MCRContinuityScheduleHeader.cdm.json/MCRContinuityScheduleHeader</a></td><td><a href="../../TransactionsAndOrders/WorksheetHeader/MCRContinuityScheduleHeader.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PdsItemRebateGroupRelationshipId name="Relationship_PdsItemRebateGroupRelationshipId">Relationship_PdsItemRebateGroupRelationshipId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PdsItemRebateGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/SalesAndMarketing/Group/PdsItemRebateGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Group/PdsItemRebateGroup.cdm.json/PdsItemRebateGroup</a></td><td><a href="../../../SupplyChain/SalesAndMarketing/Group/PdsItemRebateGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PdsFreightGroupRelationshipId name="Relationship_PdsFreightGroupRelationshipId">Relationship_PdsFreightGroupRelationshipId</a>

First included in: Miscellaneous/RetailAttributesLegalEntityLookup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PdsFreightGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Inventory/Group/PdsFreightGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/PdsFreightGroup.cdm.json/PdsFreightGroup</a></td><td><a href="../../../SupplyChain/Inventory/Group/PdsFreightGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
