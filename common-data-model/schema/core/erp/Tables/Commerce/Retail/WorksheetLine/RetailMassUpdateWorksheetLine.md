---
title: RetailMassUpdateWorksheetLine - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# RetailMassUpdateWorksheetLine

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Commerce/Retail/WorksheetLine/RetailMassUpdateWorksheetLine.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailMassUpdateWorksheetLine/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[EcoResProductRecId](#EcoResProductRecId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[EcoResProductTranslation](#EcoResProductTranslation)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[EcoResProductTranslation_Description](#EcoResProductTranslation_Description)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Invent_AllocateMarkup](#Invent_AllocateMarkup)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Invent_OverDeliveryPct](#Invent_OverDeliveryPct)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Invent_Price](#Invent_Price)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Invent_PriceDate](#Invent_PriceDate)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Invent_PriceUnit](#Invent_PriceUnit)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Invent_UnderDeliveryPct](#Invent_UnderDeliveryPct)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Invent_UnitId](#Invent_UnitId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[InventItemGroupItem_ItemGroupId](#InventItemGroupItem_ItemGroupId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[InventItemLocation_CountGroupId](#InventItemLocation_CountGroupId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[InventModelGroupItem_ModelGroupId](#InventModelGroupItem_ModelGroupId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[InventTable_ABCContributionMargin](#InventTable_ABCContributionMargin)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[InventTable_ABCRevenue](#InventTable_ABCRevenue)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[InventTable_ABCTieUp](#InventTable_ABCTieUp)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[InventTable_ABCValue](#InventTable_ABCValue)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[InventTable_CommissionGroupId](#InventTable_CommissionGroupId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[InventTable_CostGroupId](#InventTable_CostGroupId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[InventTable_CostModel](#InventTable_CostModel)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[InventTable_Density](#InventTable_Density)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[InventTable_Depth](#InventTable_Depth)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[InventTable_ExceptionCode_BR](#InventTable_ExceptionCode_BR)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[InventTable_grossDepth](#InventTable_grossDepth)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[InventTable_grossHeight](#InventTable_grossHeight)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[InventTable_grossWidth](#InventTable_grossWidth)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[InventTable_Height](#InventTable_Height)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[InventTable_ICMSOnService_BR](#InventTable_ICMSOnService_BR)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[InventTable_IntrastatCommodity](#InventTable_IntrastatCommodity)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[InventTable_IntraUnit](#InventTable_IntraUnit)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[InventTable_InventProductType_BR](#InventTable_InventProductType_BR)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[InventTable_ItemBuyerGroupId](#InventTable_ItemBuyerGroupId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[InventTable_NameAlias](#InventTable_NameAlias)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[InventTable_NetWeight](#InventTable_NetWeight)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[InventTable_OrigCountryRegionId](#InventTable_OrigCountryRegionId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[InventTable_OrigStateId](#InventTable_OrigStateId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[InventTable_PackagingGroupId](#InventTable_PackagingGroupId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[InventTable_PrimaryVendorId](#InventTable_PrimaryVendorId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[InventTable_projCategoryId](#InventTable_projCategoryId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[InventTable_PurchModel](#InventTable_PurchModel)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[InventTable_ReqGroupId](#InventTable_ReqGroupId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[InventTable_SalesContributionRatio](#InventTable_SalesContributionRatio)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[InventTable_SalesPercentMarkup](#InventTable_SalesPercentMarkup)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[InventTable_SalesPriceModelBasic](#InventTable_SalesPriceModelBasic)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[InventTable_sortCode](#InventTable_sortCode)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[InventTable_StatisticsFactor](#InventTable_StatisticsFactor)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[InventTable_TaraWeight](#InventTable_TaraWeight)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[InventTable_TaxationOrigin_BR](#InventTable_TaxationOrigin_BR)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[InventTable_TaxFiscalClassification_BR](#InventTable_TaxFiscalClassification_BR)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[InventTable_TaxPackagingQty](#InventTable_TaxPackagingQty)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[InventTable_TaxServiceCode_BR](#InventTable_TaxServiceCode_BR)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[InventTable_UnitVolume](#InventTable_UnitVolume)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[InventTable_UseAltItemId](#InventTable_UseAltItemId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[InventTable_Width](#InventTable_Width)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[InventTable_WMSArrivalHandlingTime](#InventTable_WMSArrivalHandlingTime)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[IssueDate](#IssueDate)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[ItemId](#ItemId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Purch_AllocateMarkup](#Purch_AllocateMarkup)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Purch_EndDisc](#Purch_EndDisc)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Purch_InterCompanyBlocked](#Purch_InterCompanyBlocked)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Purch_LineDisc](#Purch_LineDisc)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Purch_Markup](#Purch_Markup)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Purch_MarkupGroupId](#Purch_MarkupGroupId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Purch_MultiLineDisc](#Purch_MultiLineDisc)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Purch_OverDeliveryPct](#Purch_OverDeliveryPct)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Purch_Price](#Purch_Price)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Purch_PriceDate](#Purch_PriceDate)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Purch_PriceQty](#Purch_PriceQty)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Purch_PriceUnit](#Purch_PriceUnit)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Purch_SuppItemGroupId](#Purch_SuppItemGroupId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Purch_TaxItemGroupId](#Purch_TaxItemGroupId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Purch_UnderDeliveryPct](#Purch_UnderDeliveryPct)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Purch_UnitId](#Purch_UnitId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[RetailInvent_BarcodeSetupId](#RetailInvent_BarcodeSetupId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[RetailInvent_baseComparisonUnitCode](#RetailInvent_baseComparisonUnitCode)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[RetailInvent_blockedOnPOS](#RetailInvent_blockedOnPOS)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[RetailInvent_dateToActivateItem](#RetailInvent_dateToActivateItem)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[RetailInvent_dateToBeBlocked](#RetailInvent_dateToBeBlocked)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[RetailInvent_KeyingInPrice](#RetailInvent_KeyingInPrice)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[RetailInvent_KeyingInQty](#RetailInvent_KeyingInQty)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[RetailInvent_mustKeyInComment](#RetailInvent_mustKeyInComment)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[RetailInvent_noDiscountAllowed](#RetailInvent_noDiscountAllowed)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[RetailInvent_PrintVariantsShelfLabels](#RetailInvent_PrintVariantsShelfLabels)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[RetailInvent_ProhibitReturn_RU](#RetailInvent_ProhibitReturn_RU)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[RetailInvent_qtyBecomesNegative](#RetailInvent_qtyBecomesNegative)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[RetailInvent_ScaleItem](#RetailInvent_ScaleItem)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[RetailInvent_zeroPriceValid](#RetailInvent_zeroPriceValid)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[RetailMassUpdateWorksheetTable](#RetailMassUpdateWorksheetTable)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Sales_AllocateMarkup](#Sales_AllocateMarkup)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Sales_EndDisc](#Sales_EndDisc)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Sales_InterCompanyBlocked](#Sales_InterCompanyBlocked)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Sales_LineDisc](#Sales_LineDisc)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Sales_Markup](#Sales_Markup)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Sales_MarkupGroupId](#Sales_MarkupGroupId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Sales_MultiLineDisc](#Sales_MultiLineDisc)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Sales_OverDeliveryPct](#Sales_OverDeliveryPct)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Sales_Price](#Sales_Price)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Sales_PriceDate](#Sales_PriceDate)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Sales_PriceQty](#Sales_PriceQty)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Sales_PriceUnit](#Sales_PriceUnit)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Sales_SuppItemGroupId](#Sales_SuppItemGroupId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Sales_TaxItemGroupId](#Sales_TaxItemGroupId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Sales_UnderDeliveryPct](#Sales_UnderDeliveryPct)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Sales_UnitId](#Sales_UnitId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[RetailInvent_LabelAttribute1](#RetailInvent_LabelAttribute1)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[RetailInvent_LabelAttribute2](#RetailInvent_LabelAttribute2)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[RetailInvent_LabelAttribute3](#RetailInvent_LabelAttribute3)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[RetailInvent_LabelAttribute4](#RetailInvent_LabelAttribute4)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[RetailInvent_LabelAttribute5](#RetailInvent_LabelAttribute5)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[WHSInventTable_UOMSeqGroupId](#WHSInventTable_UOMSeqGroupId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[InventTable_Intracode](#InventTable_Intracode)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[DataAreaId](#DataAreaId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Relationship_BarcodeSetupRelationshipId](#Relationship_BarcodeSetupRelationshipId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Relationship_BOMCostGroupRelationshipId](#Relationship_BOMCostGroupRelationshipId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Relationship_CommissionItemGroupRelationshipId](#Relationship_CommissionItemGroupRelationshipId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Relationship_EcoResProductRelationshipId](#Relationship_EcoResProductRelationshipId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Relationship_EcoResProductTranslationRelationshipId](#Relationship_EcoResProductTranslationRelationshipId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Relationship_ExceptionCode_BRRelationshipId](#Relationship_ExceptionCode_BRRelationshipId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Relationship_IntrastatCommodityRelationshipId](#Relationship_IntrastatCommodityRelationshipId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Relationship_InventBuyerGroupRelationshipId](#Relationship_InventBuyerGroupRelationshipId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Relationship_InventCountGroupRelationshipId](#Relationship_InventCountGroupRelationshipId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Relationship_InventItemGroupRelationshipId](#Relationship_InventItemGroupRelationshipId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Relationship_InventItemGroupItemRelationshipId](#Relationship_InventItemGroupItemRelationshipId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Relationship_InventLineDiscountGroupPurchRelationshipId](#Relationship_InventLineDiscountGroupPurchRelationshipId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Relationship_InventLineDiscountGroupSalesRelationshipId](#Relationship_InventLineDiscountGroupSalesRelationshipId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Relationship_InventModelGroupRelationshipId](#Relationship_InventModelGroupRelationshipId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Relationship_InventModelGroupItemRelationshipId](#Relationship_InventModelGroupItemRelationshipId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Relationship_InventPackagingGroupRelationshipId](#Relationship_InventPackagingGroupRelationshipId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Relationship_InventProductType_BRRelationshipId](#Relationship_InventProductType_BRRelationshipId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Relationship_InventTableRelationshipId](#Relationship_InventTableRelationshipId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Relationship_LogisticsAddressCountryRegionRelationshipId](#Relationship_LogisticsAddressCountryRegionRelationshipId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Relationship_MarkGroupPurchRelationshipId](#Relationship_MarkGroupPurchRelationshipId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Relationship_MarkGroupSalesRelationshipId](#Relationship_MarkGroupSalesRelationshipId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Relationship_MultiLineDiscGroupPurchRelationshipId](#Relationship_MultiLineDiscGroupPurchRelationshipId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Relationship_MultiLineDiscGroupSalesRelationshipId](#Relationship_MultiLineDiscGroupSalesRelationshipId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Relationship_OriginCountryRegionRelationshipId](#Relationship_OriginCountryRegionRelationshipId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Relationship_OriginStateRelationshipId](#Relationship_OriginStateRelationshipId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Relationship_ReqGroupRelationshipId](#Relationship_ReqGroupRelationshipId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Relationship_RetailInventTableRelationshipId](#Relationship_RetailInventTableRelationshipId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Relationship_RetailMassUpdateWorksheetRelationshipId](#Relationship_RetailMassUpdateWorksheetRelationshipId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Relationship_SuppItemGroupPurchRelationshipId](#Relationship_SuppItemGroupPurchRelationshipId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Relationship_SuppItemGroupSalesRelationshipId](#Relationship_SuppItemGroupSalesRelationshipId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Relationship_TaxFiscalClassification_BRRelationshipId](#Relationship_TaxFiscalClassification_BRRelationshipId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Relationship_TaxItemGroupHeadingPurchRelationshipId](#Relationship_TaxItemGroupHeadingPurchRelationshipId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Relationship_TaxItemGroupHeadingSalesRelationshipId](#Relationship_TaxItemGroupHeadingSalesRelationshipId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Relationship_TaxServiceCode_BRRelationshipId](#Relationship_TaxServiceCode_BRRelationshipId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Relationship_VendTableRelationshipId](#Relationship_VendTableRelationshipId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Relationship_LabelAttribute1RelationshipId](#Relationship_LabelAttribute1RelationshipId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Relationship_LabelAttribute2RelationshipId](#Relationship_LabelAttribute2RelationshipId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Relationship_LabelAttribute3RelationshipId](#Relationship_LabelAttribute3RelationshipId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Relationship_LabelAttribute4RelationshipId](#Relationship_LabelAttribute4RelationshipId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Relationship_LabelAttribute5RelationshipId](#Relationship_LabelAttribute5RelationshipId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Relationship_WHSInventTableRelationshipId](#Relationship_WHSInventTableRelationshipId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Relationship_WHSUOMSeqGroupTableRelationshipId](#Relationship_WHSUOMSeqGroupTableRelationshipId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="RetailMassUpdateWorksheetLine.md" target="_blank">WorksheetLine/RetailMassUpdateWorksheetLine</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailMassUpdateWorksheetLine/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#EcoResProductRecId name="EcoResProductRecId">EcoResProductRecId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EcoResProductRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#EcoResProductTranslation name="EcoResProductTranslation">EcoResProductTranslation</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EcoResProductTranslation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#EcoResProductTranslation_Description name="EcoResProductTranslation_Description">EcoResProductTranslation_Description</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EcoResProductTranslation_Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Invent_AllocateMarkup name="Invent_AllocateMarkup">Invent_AllocateMarkup</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Invent_AllocateMarkup attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Invent_OverDeliveryPct name="Invent_OverDeliveryPct">Invent_OverDeliveryPct</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Invent_OverDeliveryPct attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Invent_Price name="Invent_Price">Invent_Price</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Invent_Price attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Invent_PriceDate name="Invent_PriceDate">Invent_PriceDate</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Invent_PriceDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#Invent_PriceUnit name="Invent_PriceUnit">Invent_PriceUnit</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Invent_PriceUnit attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Invent_UnderDeliveryPct name="Invent_UnderDeliveryPct">Invent_UnderDeliveryPct</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Invent_UnderDeliveryPct attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Invent_UnitId name="Invent_UnitId">Invent_UnitId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Invent_UnitId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventItemGroupItem_ItemGroupId name="InventItemGroupItem_ItemGroupId">InventItemGroupItem_ItemGroupId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventItemGroupItem_ItemGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventItemLocation_CountGroupId name="InventItemLocation_CountGroupId">InventItemLocation_CountGroupId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventItemLocation_CountGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventModelGroupItem_ModelGroupId name="InventModelGroupItem_ModelGroupId">InventModelGroupItem_ModelGroupId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventModelGroupItem_ModelGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventTable_ABCContributionMargin name="InventTable_ABCContributionMargin">InventTable_ABCContributionMargin</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTable_ABCContributionMargin attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InventTable_ABCRevenue name="InventTable_ABCRevenue">InventTable_ABCRevenue</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTable_ABCRevenue attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InventTable_ABCTieUp name="InventTable_ABCTieUp">InventTable_ABCTieUp</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTable_ABCTieUp attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InventTable_ABCValue name="InventTable_ABCValue">InventTable_ABCValue</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTable_ABCValue attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InventTable_CommissionGroupId name="InventTable_CommissionGroupId">InventTable_CommissionGroupId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTable_CommissionGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventTable_CostGroupId name="InventTable_CostGroupId">InventTable_CostGroupId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTable_CostGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventTable_CostModel name="InventTable_CostModel">InventTable_CostModel</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTable_CostModel attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InventTable_Density name="InventTable_Density">InventTable_Density</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTable_Density attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InventTable_Depth name="InventTable_Depth">InventTable_Depth</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTable_Depth attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InventTable_ExceptionCode_BR name="InventTable_ExceptionCode_BR">InventTable_ExceptionCode_BR</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTable_ExceptionCode_BR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventTable_grossDepth name="InventTable_grossDepth">InventTable_grossDepth</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTable_grossDepth attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InventTable_grossHeight name="InventTable_grossHeight">InventTable_grossHeight</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTable_grossHeight attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InventTable_grossWidth name="InventTable_grossWidth">InventTable_grossWidth</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTable_grossWidth attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InventTable_Height name="InventTable_Height">InventTable_Height</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTable_Height attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InventTable_ICMSOnService_BR name="InventTable_ICMSOnService_BR">InventTable_ICMSOnService_BR</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTable_ICMSOnService_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InventTable_IntrastatCommodity name="InventTable_IntrastatCommodity">InventTable_IntrastatCommodity</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTable_IntrastatCommodity attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#InventTable_IntraUnit name="InventTable_IntraUnit">InventTable_IntraUnit</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTable_IntraUnit attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InventTable_InventProductType_BR name="InventTable_InventProductType_BR">InventTable_InventProductType_BR</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTable_InventProductType_BR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventTable_ItemBuyerGroupId name="InventTable_ItemBuyerGroupId">InventTable_ItemBuyerGroupId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTable_ItemBuyerGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventTable_NameAlias name="InventTable_NameAlias">InventTable_NameAlias</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTable_NameAlias attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventTable_NetWeight name="InventTable_NetWeight">InventTable_NetWeight</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTable_NetWeight attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InventTable_OrigCountryRegionId name="InventTable_OrigCountryRegionId">InventTable_OrigCountryRegionId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTable_OrigCountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventTable_OrigStateId name="InventTable_OrigStateId">InventTable_OrigStateId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTable_OrigStateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventTable_PackagingGroupId name="InventTable_PackagingGroupId">InventTable_PackagingGroupId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTable_PackagingGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventTable_PrimaryVendorId name="InventTable_PrimaryVendorId">InventTable_PrimaryVendorId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTable_PrimaryVendorId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventTable_projCategoryId name="InventTable_projCategoryId">InventTable_projCategoryId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTable_projCategoryId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventTable_PurchModel name="InventTable_PurchModel">InventTable_PurchModel</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTable_PurchModel attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InventTable_ReqGroupId name="InventTable_ReqGroupId">InventTable_ReqGroupId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTable_ReqGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventTable_SalesContributionRatio name="InventTable_SalesContributionRatio">InventTable_SalesContributionRatio</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTable_SalesContributionRatio attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InventTable_SalesPercentMarkup name="InventTable_SalesPercentMarkup">InventTable_SalesPercentMarkup</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTable_SalesPercentMarkup attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InventTable_SalesPriceModelBasic name="InventTable_SalesPriceModelBasic">InventTable_SalesPriceModelBasic</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTable_SalesPriceModelBasic attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InventTable_sortCode name="InventTable_sortCode">InventTable_sortCode</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTable_sortCode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InventTable_StatisticsFactor name="InventTable_StatisticsFactor">InventTable_StatisticsFactor</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTable_StatisticsFactor attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InventTable_TaraWeight name="InventTable_TaraWeight">InventTable_TaraWeight</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTable_TaraWeight attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InventTable_TaxationOrigin_BR name="InventTable_TaxationOrigin_BR">InventTable_TaxationOrigin_BR</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTable_TaxationOrigin_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InventTable_TaxFiscalClassification_BR name="InventTable_TaxFiscalClassification_BR">InventTable_TaxFiscalClassification_BR</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTable_TaxFiscalClassification_BR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventTable_TaxPackagingQty name="InventTable_TaxPackagingQty">InventTable_TaxPackagingQty</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTable_TaxPackagingQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InventTable_TaxServiceCode_BR name="InventTable_TaxServiceCode_BR">InventTable_TaxServiceCode_BR</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTable_TaxServiceCode_BR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventTable_UnitVolume name="InventTable_UnitVolume">InventTable_UnitVolume</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTable_UnitVolume attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InventTable_UseAltItemId name="InventTable_UseAltItemId">InventTable_UseAltItemId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTable_UseAltItemId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InventTable_Width name="InventTable_Width">InventTable_Width</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTable_Width attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InventTable_WMSArrivalHandlingTime name="InventTable_WMSArrivalHandlingTime">InventTable_WMSArrivalHandlingTime</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTable_WMSArrivalHandlingTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.dataFormat.time**  
</details>

### <a href=#IssueDate name="IssueDate">IssueDate</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IssueDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#ItemId name="ItemId">ItemId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Purch_AllocateMarkup name="Purch_AllocateMarkup">Purch_AllocateMarkup</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Purch_AllocateMarkup attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Purch_EndDisc name="Purch_EndDisc">Purch_EndDisc</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Purch_EndDisc attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Purch_InterCompanyBlocked name="Purch_InterCompanyBlocked">Purch_InterCompanyBlocked</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Purch_InterCompanyBlocked attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Purch_LineDisc name="Purch_LineDisc">Purch_LineDisc</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Purch_LineDisc attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Purch_Markup name="Purch_Markup">Purch_Markup</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Purch_Markup attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Purch_MarkupGroupId name="Purch_MarkupGroupId">Purch_MarkupGroupId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Purch_MarkupGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Purch_MultiLineDisc name="Purch_MultiLineDisc">Purch_MultiLineDisc</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Purch_MultiLineDisc attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Purch_OverDeliveryPct name="Purch_OverDeliveryPct">Purch_OverDeliveryPct</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Purch_OverDeliveryPct attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Purch_Price name="Purch_Price">Purch_Price</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Purch_Price attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Purch_PriceDate name="Purch_PriceDate">Purch_PriceDate</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Purch_PriceDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#Purch_PriceQty name="Purch_PriceQty">Purch_PriceQty</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Purch_PriceQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Purch_PriceUnit name="Purch_PriceUnit">Purch_PriceUnit</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Purch_PriceUnit attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Purch_SuppItemGroupId name="Purch_SuppItemGroupId">Purch_SuppItemGroupId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Purch_SuppItemGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Purch_TaxItemGroupId name="Purch_TaxItemGroupId">Purch_TaxItemGroupId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Purch_TaxItemGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Purch_UnderDeliveryPct name="Purch_UnderDeliveryPct">Purch_UnderDeliveryPct</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Purch_UnderDeliveryPct attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Purch_UnitId name="Purch_UnitId">Purch_UnitId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Purch_UnitId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailInvent_BarcodeSetupId name="RetailInvent_BarcodeSetupId">RetailInvent_BarcodeSetupId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailInvent_BarcodeSetupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailInvent_baseComparisonUnitCode name="RetailInvent_baseComparisonUnitCode">RetailInvent_baseComparisonUnitCode</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailInvent_baseComparisonUnitCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailInvent_blockedOnPOS name="RetailInvent_blockedOnPOS">RetailInvent_blockedOnPOS</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailInvent_blockedOnPOS attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RetailInvent_dateToActivateItem name="RetailInvent_dateToActivateItem">RetailInvent_dateToActivateItem</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailInvent_dateToActivateItem attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#RetailInvent_dateToBeBlocked name="RetailInvent_dateToBeBlocked">RetailInvent_dateToBeBlocked</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailInvent_dateToBeBlocked attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#RetailInvent_KeyingInPrice name="RetailInvent_KeyingInPrice">RetailInvent_KeyingInPrice</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailInvent_KeyingInPrice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RetailInvent_KeyingInQty name="RetailInvent_KeyingInQty">RetailInvent_KeyingInQty</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailInvent_KeyingInQty attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RetailInvent_mustKeyInComment name="RetailInvent_mustKeyInComment">RetailInvent_mustKeyInComment</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailInvent_mustKeyInComment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RetailInvent_noDiscountAllowed name="RetailInvent_noDiscountAllowed">RetailInvent_noDiscountAllowed</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailInvent_noDiscountAllowed attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RetailInvent_PrintVariantsShelfLabels name="RetailInvent_PrintVariantsShelfLabels">RetailInvent_PrintVariantsShelfLabels</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailInvent_PrintVariantsShelfLabels attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RetailInvent_ProhibitReturn_RU name="RetailInvent_ProhibitReturn_RU">RetailInvent_ProhibitReturn_RU</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailInvent_ProhibitReturn_RU attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RetailInvent_qtyBecomesNegative name="RetailInvent_qtyBecomesNegative">RetailInvent_qtyBecomesNegative</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailInvent_qtyBecomesNegative attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RetailInvent_ScaleItem name="RetailInvent_ScaleItem">RetailInvent_ScaleItem</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailInvent_ScaleItem attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RetailInvent_zeroPriceValid name="RetailInvent_zeroPriceValid">RetailInvent_zeroPriceValid</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailInvent_zeroPriceValid attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RetailMassUpdateWorksheetTable name="RetailMassUpdateWorksheetTable">RetailMassUpdateWorksheetTable</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailMassUpdateWorksheetTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Sales_AllocateMarkup name="Sales_AllocateMarkup">Sales_AllocateMarkup</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Sales_AllocateMarkup attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Sales_EndDisc name="Sales_EndDisc">Sales_EndDisc</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Sales_EndDisc attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Sales_InterCompanyBlocked name="Sales_InterCompanyBlocked">Sales_InterCompanyBlocked</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Sales_InterCompanyBlocked attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Sales_LineDisc name="Sales_LineDisc">Sales_LineDisc</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Sales_LineDisc attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Sales_Markup name="Sales_Markup">Sales_Markup</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Sales_Markup attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Sales_MarkupGroupId name="Sales_MarkupGroupId">Sales_MarkupGroupId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Sales_MarkupGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Sales_MultiLineDisc name="Sales_MultiLineDisc">Sales_MultiLineDisc</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Sales_MultiLineDisc attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Sales_OverDeliveryPct name="Sales_OverDeliveryPct">Sales_OverDeliveryPct</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Sales_OverDeliveryPct attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Sales_Price name="Sales_Price">Sales_Price</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Sales_Price attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Sales_PriceDate name="Sales_PriceDate">Sales_PriceDate</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Sales_PriceDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#Sales_PriceQty name="Sales_PriceQty">Sales_PriceQty</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Sales_PriceQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Sales_PriceUnit name="Sales_PriceUnit">Sales_PriceUnit</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Sales_PriceUnit attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Sales_SuppItemGroupId name="Sales_SuppItemGroupId">Sales_SuppItemGroupId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Sales_SuppItemGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Sales_TaxItemGroupId name="Sales_TaxItemGroupId">Sales_TaxItemGroupId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Sales_TaxItemGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Sales_UnderDeliveryPct name="Sales_UnderDeliveryPct">Sales_UnderDeliveryPct</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Sales_UnderDeliveryPct attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Sales_UnitId name="Sales_UnitId">Sales_UnitId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Sales_UnitId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailInvent_LabelAttribute1 name="RetailInvent_LabelAttribute1">RetailInvent_LabelAttribute1</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailInvent_LabelAttribute1 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RetailInvent_LabelAttribute2 name="RetailInvent_LabelAttribute2">RetailInvent_LabelAttribute2</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailInvent_LabelAttribute2 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RetailInvent_LabelAttribute3 name="RetailInvent_LabelAttribute3">RetailInvent_LabelAttribute3</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailInvent_LabelAttribute3 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RetailInvent_LabelAttribute4 name="RetailInvent_LabelAttribute4">RetailInvent_LabelAttribute4</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailInvent_LabelAttribute4 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RetailInvent_LabelAttribute5 name="RetailInvent_LabelAttribute5">RetailInvent_LabelAttribute5</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailInvent_LabelAttribute5 attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#WHSInventTable_UOMSeqGroupId name="WHSInventTable_UOMSeqGroupId">WHSInventTable_UOMSeqGroupId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WHSInventTable_UOMSeqGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventTable_Intracode name="InventTable_Intracode">InventTable_Intracode</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTable_Intracode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BarcodeSetupRelationshipId name="Relationship_BarcodeSetupRelationshipId">Relationship_BarcodeSetupRelationshipId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Inventory/Group/BarcodeSetup.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/Group/BarcodeSetup.cdm.json/BarcodeSetup</a></td><td><a href="../../../SupplyChain/Inventory/Group/BarcodeSetup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BOMCostGroupRelationshipId name="Relationship_BOMCostGroupRelationshipId">Relationship_BOMCostGroupRelationshipId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Inventory/Group/BOMCostGroup.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/Group/BOMCostGroup.cdm.json/BOMCostGroup</a></td><td><a href="../../../SupplyChain/Inventory/Group/BOMCostGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CommissionItemGroupRelationshipId name="Relationship_CommissionItemGroupRelationshipId">Relationship_CommissionItemGroupRelationshipId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/SalesAndMarketing/Group/CommissionItemGroup.md" target="_blank">/core/erp/Tables/SupplyChain/SalesAndMarketing/Group/CommissionItemGroup.cdm.json/CommissionItemGroup</a></td><td><a href="../../../SupplyChain/SalesAndMarketing/Group/CommissionItemGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_EcoResProductRelationshipId name="Relationship_EcoResProductRelationshipId">Relationship_EcoResProductRelationshipId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EcoResProductRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResProduct.md" target="_blank">/core/erp/Tables/SupplyChain/ProductInformationManagement/Main/EcoResProduct.cdm.json/EcoResProduct</a></td><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResProduct.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_EcoResProductTranslationRelationshipId name="Relationship_EcoResProductTranslationRelationshipId">Relationship_EcoResProductTranslationRelationshipId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EcoResProductTranslationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResProductTranslation.md" target="_blank">/core/erp/Tables/SupplyChain/ProductInformationManagement/Main/EcoResProductTranslation.cdm.json/EcoResProductTranslation</a></td><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResProductTranslation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ExceptionCode_BRRelationshipId name="Relationship_ExceptionCode_BRRelationshipId">Relationship_ExceptionCode_BRRelationshipId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/APARShared/Miscellaneous/ExceptionCodeTable_BR.md" target="_blank">/core/erp/Tables/Finance/APARShared/Miscellaneous/ExceptionCodeTable_BR.cdm.json/ExceptionCodeTable_BR</a></td><td><a href="../../../Finance/APARShared/Miscellaneous/ExceptionCodeTable_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_IntrastatCommodityRelationshipId name="Relationship_IntrastatCommodityRelationshipId">Relationship_IntrastatCommodityRelationshipId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_IntrastatCommodityRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResCategory.md" target="_blank">/core/erp/Tables/SupplyChain/ProductInformationManagement/Main/EcoResCategory.cdm.json/EcoResCategory</a></td><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResCategory.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventBuyerGroupRelationshipId name="Relationship_InventBuyerGroupRelationshipId">Relationship_InventBuyerGroupRelationshipId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventBuyerGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Inventory/Group/InventBuyerGroup.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/Group/InventBuyerGroup.cdm.json/InventBuyerGroup</a></td><td><a href="../../../SupplyChain/Inventory/Group/InventBuyerGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventCountGroupRelationshipId name="Relationship_InventCountGroupRelationshipId">Relationship_InventCountGroupRelationshipId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventCountGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Inventory/Group/InventCountGroup.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/Group/InventCountGroup.cdm.json/InventCountGroup</a></td><td><a href="../../../SupplyChain/Inventory/Group/InventCountGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventItemGroupRelationshipId name="Relationship_InventItemGroupRelationshipId">Relationship_InventItemGroupRelationshipId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventItemGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Inventory/Group/InventItemGroup.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/Group/InventItemGroup.cdm.json/InventItemGroup</a></td><td><a href="../../../SupplyChain/Inventory/Group/InventItemGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventItemGroupItemRelationshipId name="Relationship_InventItemGroupItemRelationshipId">Relationship_InventItemGroupItemRelationshipId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventItemGroupItemRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Inventory/Main/InventItemGroupItem.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/Main/InventItemGroupItem.cdm.json/InventItemGroupItem</a></td><td><a href="../../../SupplyChain/Inventory/Main/InventItemGroupItem.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventLineDiscountGroupPurchRelationshipId name="Relationship_InventLineDiscountGroupPurchRelationshipId">Relationship_InventLineDiscountGroupPurchRelationshipId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventLineDiscountGroupPurchRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/SalesAndMarketing/Group/PriceDiscGroup.md" target="_blank">/core/erp/Tables/SupplyChain/SalesAndMarketing/Group/PriceDiscGroup.cdm.json/PriceDiscGroup</a></td><td><a href="../../../SupplyChain/SalesAndMarketing/Group/PriceDiscGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventLineDiscountGroupSalesRelationshipId name="Relationship_InventLineDiscountGroupSalesRelationshipId">Relationship_InventLineDiscountGroupSalesRelationshipId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventLineDiscountGroupSalesRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/SalesAndMarketing/Group/PriceDiscGroup.md" target="_blank">/core/erp/Tables/SupplyChain/SalesAndMarketing/Group/PriceDiscGroup.cdm.json/PriceDiscGroup</a></td><td><a href="../../../SupplyChain/SalesAndMarketing/Group/PriceDiscGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventModelGroupRelationshipId name="Relationship_InventModelGroupRelationshipId">Relationship_InventModelGroupRelationshipId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventModelGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Inventory/Group/InventModelGroup.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/Group/InventModelGroup.cdm.json/InventModelGroup</a></td><td><a href="../../../SupplyChain/Inventory/Group/InventModelGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventModelGroupItemRelationshipId name="Relationship_InventModelGroupItemRelationshipId">Relationship_InventModelGroupItemRelationshipId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventModelGroupItemRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Inventory/Main/InventModelGroupItem.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/Main/InventModelGroupItem.cdm.json/InventModelGroupItem</a></td><td><a href="../../../SupplyChain/Inventory/Main/InventModelGroupItem.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventPackagingGroupRelationshipId name="Relationship_InventPackagingGroupRelationshipId">Relationship_InventPackagingGroupRelationshipId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Inventory/Group/InventPackagingGroup.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/Group/InventPackagingGroup.cdm.json/InventPackagingGroup</a></td><td><a href="../../../SupplyChain/Inventory/Group/InventPackagingGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventProductType_BRRelationshipId name="Relationship_InventProductType_BRRelationshipId">Relationship_InventProductType_BRRelationshipId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Inventory/Main/InventProductTypeTable_BR.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/Main/InventProductTypeTable_BR.cdm.json/InventProductTypeTable_BR</a></td><td><a href="../../../SupplyChain/Inventory/Main/InventProductTypeTable_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventTableRelationshipId name="Relationship_InventTableRelationshipId">Relationship_InventTableRelationshipId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProductInformationManagement/Main/InventTable.md" target="_blank">/core/erp/Tables/SupplyChain/ProductInformationManagement/Main/InventTable.cdm.json/InventTable</a></td><td><a href="../../../SupplyChain/ProductInformationManagement/Main/InventTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LogisticsAddressCountryRegionRelationshipId name="Relationship_LogisticsAddressCountryRegionRelationshipId">Relationship_LogisticsAddressCountryRegionRelationshipId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LogisticsAddressCountryRegionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Group/LogisticsAddressCountryRegion.md" target="_blank">/core/erp/Tables/Common/GAB/Group/LogisticsAddressCountryRegion.cdm.json/LogisticsAddressCountryRegion</a></td><td><a href="../../../Common/GAB/Group/LogisticsAddressCountryRegion.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_MarkGroupPurchRelationshipId name="Relationship_MarkGroupPurchRelationshipId">Relationship_MarkGroupPurchRelationshipId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MarkGroupPurchRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProcurementAndSourcing/Group/MarkupGroup.md" target="_blank">/core/erp/Tables/SupplyChain/ProcurementAndSourcing/Group/MarkupGroup.cdm.json/MarkupGroup</a></td><td><a href="../../../SupplyChain/ProcurementAndSourcing/Group/MarkupGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_MarkGroupSalesRelationshipId name="Relationship_MarkGroupSalesRelationshipId">Relationship_MarkGroupSalesRelationshipId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MarkGroupSalesRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProcurementAndSourcing/Group/MarkupGroup.md" target="_blank">/core/erp/Tables/SupplyChain/ProcurementAndSourcing/Group/MarkupGroup.cdm.json/MarkupGroup</a></td><td><a href="../../../SupplyChain/ProcurementAndSourcing/Group/MarkupGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_MultiLineDiscGroupPurchRelationshipId name="Relationship_MultiLineDiscGroupPurchRelationshipId">Relationship_MultiLineDiscGroupPurchRelationshipId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MultiLineDiscGroupPurchRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/SalesAndMarketing/Group/PriceDiscGroup.md" target="_blank">/core/erp/Tables/SupplyChain/SalesAndMarketing/Group/PriceDiscGroup.cdm.json/PriceDiscGroup</a></td><td><a href="../../../SupplyChain/SalesAndMarketing/Group/PriceDiscGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_MultiLineDiscGroupSalesRelationshipId name="Relationship_MultiLineDiscGroupSalesRelationshipId">Relationship_MultiLineDiscGroupSalesRelationshipId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MultiLineDiscGroupSalesRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/SalesAndMarketing/Group/PriceDiscGroup.md" target="_blank">/core/erp/Tables/SupplyChain/SalesAndMarketing/Group/PriceDiscGroup.cdm.json/PriceDiscGroup</a></td><td><a href="../../../SupplyChain/SalesAndMarketing/Group/PriceDiscGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_OriginCountryRegionRelationshipId name="Relationship_OriginCountryRegionRelationshipId">Relationship_OriginCountryRegionRelationshipId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OriginCountryRegionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Group/LogisticsAddressCountryRegion.md" target="_blank">/core/erp/Tables/Common/GAB/Group/LogisticsAddressCountryRegion.cdm.json/LogisticsAddressCountryRegion</a></td><td><a href="../../../Common/GAB/Group/LogisticsAddressCountryRegion.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_OriginStateRelationshipId name="Relationship_OriginStateRelationshipId">Relationship_OriginStateRelationshipId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OriginStateRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Group/LogisticsAddressState.md" target="_blank">/core/erp/Tables/Common/GAB/Group/LogisticsAddressState.cdm.json/LogisticsAddressState</a></td><td><a href="../../../Common/GAB/Group/LogisticsAddressState.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ReqGroupRelationshipId name="Relationship_ReqGroupRelationshipId">Relationship_ReqGroupRelationshipId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReqGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/MasterPlanning/Group/ReqGroup.md" target="_blank">/core/erp/Tables/SupplyChain/MasterPlanning/Group/ReqGroup.cdm.json/ReqGroup</a></td><td><a href="../../../SupplyChain/MasterPlanning/Group/ReqGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailInventTableRelationshipId name="Relationship_RetailInventTableRelationshipId">Relationship_RetailInventTableRelationshipId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailInventTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/RetailInventTable.md" target="_blank">/core/erp/Tables/Commerce/Retail/Main/RetailInventTable.cdm.json/RetailInventTable</a></td><td><a href="../Main/RetailInventTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailMassUpdateWorksheetRelationshipId name="Relationship_RetailMassUpdateWorksheetRelationshipId">Relationship_RetailMassUpdateWorksheetRelationshipId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailMassUpdateWorksheetRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/RetailMassUpdateWorksheetTable.md" target="_blank">/core/erp/Tables/Commerce/Retail/WorksheetHeader/RetailMassUpdateWorksheetTable.cdm.json/RetailMassUpdateWorksheetTable</a></td><td><a href="../WorksheetHeader/RetailMassUpdateWorksheetTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SuppItemGroupPurchRelationshipId name="Relationship_SuppItemGroupPurchRelationshipId">Relationship_SuppItemGroupPurchRelationshipId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SuppItemGroupPurchRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/SalesAndMarketing/Group/SuppItemGroup.md" target="_blank">/core/erp/Tables/SupplyChain/SalesAndMarketing/Group/SuppItemGroup.cdm.json/SuppItemGroup</a></td><td><a href="../../../SupplyChain/SalesAndMarketing/Group/SuppItemGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SuppItemGroupSalesRelationshipId name="Relationship_SuppItemGroupSalesRelationshipId">Relationship_SuppItemGroupSalesRelationshipId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SuppItemGroupSalesRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/SalesAndMarketing/Group/SuppItemGroup.md" target="_blank">/core/erp/Tables/SupplyChain/SalesAndMarketing/Group/SuppItemGroup.cdm.json/SuppItemGroup</a></td><td><a href="../../../SupplyChain/SalesAndMarketing/Group/SuppItemGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxFiscalClassification_BRRelationshipId name="Relationship_TaxFiscalClassification_BRRelationshipId">Relationship_TaxFiscalClassification_BRRelationshipId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Tax/Parameter/TaxFiscalClassification_BR.md" target="_blank">/core/erp/Tables/Finance/Tax/Parameter/TaxFiscalClassification_BR.cdm.json/TaxFiscalClassification_BR</a></td><td><a href="../../../Finance/Tax/Parameter/TaxFiscalClassification_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxItemGroupHeadingPurchRelationshipId name="Relationship_TaxItemGroupHeadingPurchRelationshipId">Relationship_TaxItemGroupHeadingPurchRelationshipId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxItemGroupHeadingPurchRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Tax/Group/TaxItemGroupHeading.md" target="_blank">/core/erp/Tables/Finance/Tax/Group/TaxItemGroupHeading.cdm.json/TaxItemGroupHeading</a></td><td><a href="../../../Finance/Tax/Group/TaxItemGroupHeading.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxItemGroupHeadingSalesRelationshipId name="Relationship_TaxItemGroupHeadingSalesRelationshipId">Relationship_TaxItemGroupHeadingSalesRelationshipId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxItemGroupHeadingSalesRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Tax/Group/TaxItemGroupHeading.md" target="_blank">/core/erp/Tables/Finance/Tax/Group/TaxItemGroupHeading.cdm.json/TaxItemGroupHeading</a></td><td><a href="../../../Finance/Tax/Group/TaxItemGroupHeading.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxServiceCode_BRRelationshipId name="Relationship_TaxServiceCode_BRRelationshipId">Relationship_TaxServiceCode_BRRelationshipId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Tax/Group/TaxServiceCode_BR.md" target="_blank">/core/erp/Tables/Finance/Tax/Group/TaxServiceCode_BR.cdm.json/TaxServiceCode_BR</a></td><td><a href="../../../Finance/Tax/Group/TaxServiceCode_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendTableRelationshipId name="Relationship_VendTableRelationshipId">Relationship_VendTableRelationshipId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Vendor/Main/VendTable.md" target="_blank">/core/erp/Tables/SupplyChain/Vendor/Main/VendTable.cdm.json/VendTable</a></td><td><a href="../../../SupplyChain/Vendor/Main/VendTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LabelAttribute1RelationshipId name="Relationship_LabelAttribute1RelationshipId">Relationship_LabelAttribute1RelationshipId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResAttribute.md" target="_blank">/core/erp/Tables/SupplyChain/ProductInformationManagement/Main/EcoResAttribute.cdm.json/EcoResAttribute</a></td><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResAttribute.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LabelAttribute2RelationshipId name="Relationship_LabelAttribute2RelationshipId">Relationship_LabelAttribute2RelationshipId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResAttribute.md" target="_blank">/core/erp/Tables/SupplyChain/ProductInformationManagement/Main/EcoResAttribute.cdm.json/EcoResAttribute</a></td><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResAttribute.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LabelAttribute3RelationshipId name="Relationship_LabelAttribute3RelationshipId">Relationship_LabelAttribute3RelationshipId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResAttribute.md" target="_blank">/core/erp/Tables/SupplyChain/ProductInformationManagement/Main/EcoResAttribute.cdm.json/EcoResAttribute</a></td><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResAttribute.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LabelAttribute4RelationshipId name="Relationship_LabelAttribute4RelationshipId">Relationship_LabelAttribute4RelationshipId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResAttribute.md" target="_blank">/core/erp/Tables/SupplyChain/ProductInformationManagement/Main/EcoResAttribute.cdm.json/EcoResAttribute</a></td><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResAttribute.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LabelAttribute5RelationshipId name="Relationship_LabelAttribute5RelationshipId">Relationship_LabelAttribute5RelationshipId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResAttribute.md" target="_blank">/core/erp/Tables/SupplyChain/ProductInformationManagement/Main/EcoResAttribute.cdm.json/EcoResAttribute</a></td><td><a href="../../../SupplyChain/ProductInformationManagement/Main/EcoResAttribute.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WHSInventTableRelationshipId name="Relationship_WHSInventTableRelationshipId">Relationship_WHSInventTableRelationshipId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WHSInventTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Inventory/Main/WHSInventTable.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/Main/WHSInventTable.cdm.json/WHSInventTable</a></td><td><a href="../../../SupplyChain/Inventory/Main/WHSInventTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WHSUOMSeqGroupTableRelationshipId name="Relationship_WHSUOMSeqGroupTableRelationshipId">Relationship_WHSUOMSeqGroupTableRelationshipId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/Inventory/Group/WHSUOMSeqGroupTable.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/Group/WHSUOMSeqGroupTable.cdm.json/WHSUOMSeqGroupTable</a></td><td><a href="../../../SupplyChain/Inventory/Group/WHSUOMSeqGroupTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetLine/RetailMassUpdateWorksheetLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CompanyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/erp/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
