---
title: PurchLineHistory - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Purchase lines history

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Transaction/PurchLineHistory.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PurchLineHistory/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchase lines history</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[TaxItemGroup](#TaxItemGroup)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[TaxGroup](#TaxGroup)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[AccountingDistributionTemplate](#AccountingDistributionTemplate)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[ActivityNumber](#ActivityNumber)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[AddressRefRecId](#AddressRefRecId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[AddressRefTableId](#AddressRefTableId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[AgreementSkipAutoLink](#AgreementSkipAutoLink)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[AssetBookId](#AssetBookId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[AssetGroup](#AssetGroup)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[AssetId](#AssetId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[AssetTransTypePurch](#AssetTransTypePurch)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[BarCode](#BarCode)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[BarCodeType](#BarCodeType)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Blocked](#Blocked)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[CFOPTable_BR](#CFOPTable_BR)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Complete](#Complete)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[ConfirmedDlv](#ConfirmedDlv)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[ConfirmedTaxAmount](#ConfirmedTaxAmount)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[ConfirmedTaxWriteCode](#ConfirmedTaxWriteCode)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[CountyOrigDest](#CountyOrigDest)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[CovRef](#CovRef)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[CreateFixedAsset](#CreateFixedAsset)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[CurrencyCode](#CurrencyCode)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[CustomerRef](#CustomerRef)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[CustPurchaseOrderFormNum](#CustPurchaseOrderFormNum)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[DefaultDimension](#DefaultDimension)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[DeliveryDate](#DeliveryDate)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[DeliveryName](#DeliveryName)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[DeliveryPostalAddress](#DeliveryPostalAddress)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[DeliveryType](#DeliveryType)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[DepreciationStartDate](#DepreciationStartDate)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[DiscAmount](#DiscAmount)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[DiscPercent](#DiscPercent)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[ExternalItemId](#ExternalItemId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[GSTHSTTaxType_CA](#GSTHSTTaxType_CA)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[InterCompanyInventTransId](#InterCompanyInventTransId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[InterCompanyOrigin](#InterCompanyOrigin)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[InventDimId](#InventDimId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[InventReceivedNow](#InventReceivedNow)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[InventRefId](#InventRefId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[InventRefTransId](#InventRefTransId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[InventTransId](#InventTransId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[IsFinalized](#IsFinalized)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[ItemBOMId](#ItemBOMId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[ItemId](#ItemId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[ItemRefType](#ItemRefType)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[ItemRouteId](#ItemRouteId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[LedgerDimension](#LedgerDimension)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[LineAmount](#LineAmount)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[LineDeliveryType](#LineDeliveryType)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[LineDisc](#LineDisc)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[LineHeader](#LineHeader)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[LineNumber](#LineNumber)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[LinePercent](#LinePercent)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[MatchingAgreementLine](#MatchingAgreementLine)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[MatchingPolicy](#MatchingPolicy)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[MCRDropShipComment](#MCRDropShipComment)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[MCRDropShipment](#MCRDropShipment)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[MCRDropShipStatus](#MCRDropShipStatus)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[MultiLnDisc](#MultiLnDisc)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[MultiLnPercent](#MultiLnPercent)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Name](#Name)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[OverDeliveryPct](#OverDeliveryPct)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[PackedExtensions](#PackedExtensions)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[PdsCWInventReceivedNow](#PdsCWInventReceivedNow)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[PdsCWQty](#PdsCWQty)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[PdsCWRemainInventFinancial](#PdsCWRemainInventFinancial)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[PdsCWRemainInventPhysical](#PdsCWRemainInventPhysical)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Port](#Port)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[PriceUnit](#PriceUnit)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[ProcurementCategory](#ProcurementCategory)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[ProjCategoryId](#ProjCategoryId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[ProjId](#ProjId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[ProjLinePropertyId](#ProjLinePropertyId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[ProjSalesCurrencyId](#ProjSalesCurrencyId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[ProjSalesPrice](#ProjSalesPrice)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[ProjSalesUnitId](#ProjSalesUnitId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[ProjTaxGroupId](#ProjTaxGroupId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[ProjTaxItemGroupId](#ProjTaxItemGroupId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[ProjTransId](#ProjTransId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[ProjWorker](#ProjWorker)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[PurchaseType](#PurchaseType)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[PurchCommitmentLine_PSN](#PurchCommitmentLine_PSN)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[PurchId](#PurchId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[PurchMarkup](#PurchMarkup)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[PurchPrice](#PurchPrice)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[PurchQty](#PurchQty)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[PurchReceivedNow](#PurchReceivedNow)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[PurchReqId](#PurchReqId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[PurchReqLineRefId](#PurchReqLineRefId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[PurchStatus](#PurchStatus)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[PurchUnit](#PurchUnit)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[QtyOrdered](#QtyOrdered)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[RemainInventFinancial](#RemainInventFinancial)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[RemainInventPhysical](#RemainInventPhysical)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[RemainPurchFinancial](#RemainPurchFinancial)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[RemainPurchPhysical](#RemainPurchPhysical)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[ReqAttention](#ReqAttention)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[ReqPlanIdSched](#ReqPlanIdSched)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[ReqPOId](#ReqPOId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Requester](#Requester)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[ReturnActionId](#ReturnActionId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[ReturnDispositionCodeId](#ReturnDispositionCodeId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[ReturnStatus](#ReturnStatus)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Scrap](#Scrap)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[ShippingDateConfirmed](#ShippingDateConfirmed)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[ShippingDateRequested](#ShippingDateRequested)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[SkipUpdate](#SkipUpdate)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[SourceDocumentLine](#SourceDocumentLine)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[StatProcId](#StatProcId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[StatTriangularDeal](#StatTriangularDeal)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[StockedProduct](#StockedProduct)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Tax1099Amount](#Tax1099Amount)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Tax1099Fields](#Tax1099Fields)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Tax1099RecId](#Tax1099RecId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Tax1099State](#Tax1099State)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Tax1099StateAmount](#Tax1099StateAmount)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[TaxAutogenerated](#TaxAutogenerated)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[TaxServiceCode_BR](#TaxServiceCode_BR)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[TaxWithholdBaseCur_TH](#TaxWithholdBaseCur_TH)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[TaxWithholdGroup_TH](#TaxWithholdGroup_TH)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[TaxWithholdItemGroupHeading_TH](#TaxWithholdItemGroupHeading_TH)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[TransactionCode](#TransactionCode)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Transport](#Transport)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[UnderDeliveryPct](#UnderDeliveryPct)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[ValidFrom](#ValidFrom)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[ValidTo](#ValidTo)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[VendAccount](#VendAccount)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[VendGroup](#VendGroup)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[IntrastatCommodity](#IntrastatCommodity)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[OrigCountryRegionId](#OrigCountryRegionId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[OrigStateId](#OrigStateId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[PurchaseOrderLineCreationMethod](#PurchaseOrderLineCreationMethod)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[DataAreaId](#DataAreaId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Relationship_AccountingDistributionTemplateRelationshipId](#Relationship_AccountingDistributionTemplateRelationshipId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Relationship_AgreementLineRelationshipId](#Relationship_AgreementLineRelationshipId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Relationship_AssetBookRelationshipId](#Relationship_AssetBookRelationshipId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Relationship_AssetBookTableRelationshipId](#Relationship_AssetBookTableRelationshipId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Relationship_AssetGroupRelationshipId](#Relationship_AssetGroupRelationshipId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Relationship_AssetTableRelationshipId](#Relationship_AssetTableRelationshipId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Relationship_BarcodeSetupRelationshipId](#Relationship_BarcodeSetupRelationshipId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Relationship_BOMTableRelationshipId](#Relationship_BOMTableRelationshipId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Relationship_CFOPTable_BRRelationshipId](#Relationship_CFOPTable_BRRelationshipId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Relationship_CountyOrigDestRelationshipId](#Relationship_CountyOrigDestRelationshipId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Relationship_CurrencyRelationshipId](#Relationship_CurrencyRelationshipId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Relationship_DefaultDimensionRelationshipId](#Relationship_DefaultDimensionRelationshipId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Relationship_DeliveryPostalAddressRelationshipId](#Relationship_DeliveryPostalAddressRelationshipId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Relationship_IntrastatPortRelationshipId](#Relationship_IntrastatPortRelationshipId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Relationship_IntrastatStatProcRelationshipId](#Relationship_IntrastatStatProcRelationshipId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Relationship_IntrastatTransactionCodeRelationshipId](#Relationship_IntrastatTransactionCodeRelationshipId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Relationship_IntrastatTransportModeRelationshipId](#Relationship_IntrastatTransportModeRelationshipId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Relationship_InventDimRelationshipId](#Relationship_InventDimRelationshipId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Relationship_InventItemBarcodeRelationshipId](#Relationship_InventItemBarcodeRelationshipId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Relationship_InventJournalTableRefRelationshipId](#Relationship_InventJournalTableRefRelationshipId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Relationship_InventTableRelationshipId](#Relationship_InventTableRelationshipId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Relationship_InventTransOriginRelationshipId](#Relationship_InventTransOriginRelationshipId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Relationship_LedgerDimensionRelationshipId](#Relationship_LedgerDimensionRelationshipId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Relationship_ProcurementCategoryRelationshipId](#Relationship_ProcurementCategoryRelationshipId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Relationship_ProdLineRefRelationshipId](#Relationship_ProdLineRefRelationshipId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Relationship_ProdTableRefRelationshipId](#Relationship_ProdTableRefRelationshipId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Relationship_ProjCategoryRelationshipId](#Relationship_ProjCategoryRelationshipId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Relationship_ProjectSalesCurrencyRelationshipId](#Relationship_ProjectSalesCurrencyRelationshipId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Relationship_ProjectTaxGroupHeadingRelationshipId](#Relationship_ProjectTaxGroupHeadingRelationshipId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Relationship_ProjectTaxItemGroupHeadingRelationshipId](#Relationship_ProjectTaxItemGroupHeadingRelationshipId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Relationship_ProjItemTransRelationshipId](#Relationship_ProjItemTransRelationshipId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Relationship_ProjLinePropertyRelationshipId](#Relationship_ProjLinePropertyRelationshipId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Relationship_ProjTableRelationshipId](#Relationship_ProjTableRelationshipId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Relationship_PurchCommitmentLine_PSNRelationshipId](#Relationship_PurchCommitmentLine_PSNRelationshipId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Relationship_PurchLineRelationshipId](#Relationship_PurchLineRelationshipId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Relationship_PurchReqLineRelationshipId](#Relationship_PurchReqLineRelationshipId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Relationship_PurchReturnActionDefaultsRelationshipId](#Relationship_PurchReturnActionDefaultsRelationshipId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Relationship_PurchTableHistoryRelationshipId](#Relationship_PurchTableHistoryRelationshipId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Relationship_ReqPlanSchedRelationshipId](#Relationship_ReqPlanSchedRelationshipId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Relationship_ReturnDispositionCodeRelationshipId](#Relationship_ReturnDispositionCodeRelationshipId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Relationship_RouteTableRelationshipId](#Relationship_RouteTableRelationshipId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Relationship_SalesTableRefRelationshipId](#Relationship_SalesTableRefRelationshipId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Relationship_SourceDocumentLineRelationshipId](#Relationship_SourceDocumentLineRelationshipId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Relationship_StateRelationshipId](#Relationship_StateRelationshipId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Relationship_Tax1099BoxDetailRelationshipId](#Relationship_Tax1099BoxDetailRelationshipId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Relationship_Tax1099FieldsRelationshipId](#Relationship_Tax1099FieldsRelationshipId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Relationship_TaxGroupHeadingRelationshipId](#Relationship_TaxGroupHeadingRelationshipId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Relationship_TaxItemGroupHeadingRelationshipId](#Relationship_TaxItemGroupHeadingRelationshipId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Relationship_TaxWithholdGroupHeadingRelationshipId](#Relationship_TaxWithholdGroupHeadingRelationshipId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Relationship_TaxWithholdItemGroupHeading_THRelationshipId](#Relationship_TaxWithholdItemGroupHeading_THRelationshipId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Relationship_VendGroupRelationshipId](#Relationship_VendGroupRelationshipId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Relationship_VendTableRelationshipId](#Relationship_VendTableRelationshipId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Relationship_OrigStateRelationshipId](#Relationship_OrigStateRelationshipId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Relationship_IntrastatCommodityRelationshipId](#Relationship_IntrastatCommodityRelationshipId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="PurchLineHistory.md" target="_blank">Transaction/PurchLineHistory</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PurchLineHistory/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxItemGroup name="TaxItemGroup">TaxItemGroup</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxItemGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxGroup name="TaxGroup">TaxGroup</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountingDistributionTemplate name="AccountingDistributionTemplate">AccountingDistributionTemplate</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountingDistributionTemplate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ActivityNumber name="ActivityNumber">ActivityNumber</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActivityNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressRefRecId name="AddressRefRecId">AddressRefRecId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressRefRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AddressRefTableId name="AddressRefTableId">AddressRefTableId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressRefTableId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#AgreementSkipAutoLink name="AgreementSkipAutoLink">AgreementSkipAutoLink</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgreementSkipAutoLink attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AssetBookId name="AssetBookId">AssetBookId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetBookId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AssetGroup name="AssetGroup">AssetGroup</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AssetId name="AssetId">AssetId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AssetTransTypePurch name="AssetTransTypePurch">AssetTransTypePurch</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetTransTypePurch attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#BarCode name="BarCode">BarCode</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BarCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BarCodeType name="BarCodeType">BarCodeType</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BarCodeType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Blocked name="Blocked">Blocked</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Blocked attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CFOPTable_BR name="CFOPTable_BR">CFOPTable_BR</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFOPTable_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Complete name="Complete">Complete</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Complete attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ConfirmedDlv name="ConfirmedDlv">ConfirmedDlv</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Confirmed</td></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConfirmedDlv attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Confirmed</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.date**  
</details>

### <a href=#ConfirmedTaxAmount name="ConfirmedTaxAmount">ConfirmedTaxAmount</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConfirmedTaxAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ConfirmedTaxWriteCode name="ConfirmedTaxWriteCode">ConfirmedTaxWriteCode</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConfirmedTaxWriteCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CountyOrigDest name="CountyOrigDest">CountyOrigDest</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CountyOrigDest attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CovRef name="CovRef">CovRef</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CovRef attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#CreateFixedAsset name="CreateFixedAsset">CreateFixedAsset</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>New fixed asset?</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreateFixedAsset attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>New fixed asset?</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerRef name="CustomerRef">CustomerRef</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerRef attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustPurchaseOrderFormNum name="CustPurchaseOrderFormNum">CustPurchaseOrderFormNum</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustPurchaseOrderFormNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimension name="DefaultDimension">DefaultDimension</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DeliveryDate name="DeliveryDate">DeliveryDate</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#DeliveryName name="DeliveryName">DeliveryName</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryPostalAddress name="DeliveryPostalAddress">DeliveryPostalAddress</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryPostalAddress attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DeliveryType name="DeliveryType">DeliveryType</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#DepreciationStartDate name="DepreciationStartDate">DepreciationStartDate</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepreciationStartDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#DiscAmount name="DiscAmount">DiscAmount</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DiscPercent name="DiscPercent">DiscPercent</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscPercent attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ExternalItemId name="ExternalItemId">ExternalItemId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExternalItemId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GSTHSTTaxType_CA name="GSTHSTTaxType_CA">GSTHSTTaxType_CA</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GSTHSTTaxType_CA attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InterCompanyInventTransId name="InterCompanyInventTransId">InterCompanyInventTransId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InterCompanyInventTransId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InterCompanyOrigin name="InterCompanyOrigin">InterCompanyOrigin</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InterCompanyOrigin attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#InventDimId name="InventDimId">InventDimId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventDimId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventReceivedNow name="InventReceivedNow">InventReceivedNow</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Receive now</td></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventReceivedNow attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Receive now</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InventRefId name="InventRefId">InventRefId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventRefId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventRefTransId name="InventRefTransId">InventRefTransId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventRefTransId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventTransId name="InventTransId">InventTransId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventTransId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsFinalized name="IsFinalized">IsFinalized</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsFinalized attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#ItemBOMId name="ItemBOMId">ItemBOMId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemBOMId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemId name="ItemId">ItemId</a>

First included in: Transaction/PurchLineHistory (this entity)  

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

### <a href=#ItemRefType name="ItemRefType">ItemRefType</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemRefType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ItemRouteId name="ItemRouteId">ItemRouteId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemRouteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerDimension name="LedgerDimension">LedgerDimension</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ledger account</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Ledger account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LineAmount name="LineAmount">LineAmount</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#LineDeliveryType name="LineDeliveryType">LineDeliveryType</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineDeliveryType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#LineDisc name="LineDisc">LineDisc</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineDisc attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#LineHeader name="LineHeader">LineHeader</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineHeader attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LinePercent name="LinePercent">LinePercent</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LinePercent attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#MatchingAgreementLine name="MatchingAgreementLine">MatchingAgreementLine</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MatchingAgreementLine attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#MatchingPolicy name="MatchingPolicy">MatchingPolicy</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Matching policy</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MatchingPolicy attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Matching policy</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#MCRDropShipComment name="MCRDropShipComment">MCRDropShipComment</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRDropShipComment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MCRDropShipment name="MCRDropShipment">MCRDropShipment</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRDropShipment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MCRDropShipStatus name="MCRDropShipStatus">MCRDropShipStatus</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRDropShipStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MultiLnDisc name="MultiLnDisc">MultiLnDisc</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MultiLnDisc attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#MultiLnPercent name="MultiLnPercent">MultiLnPercent</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MultiLnPercent attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Name name="Name">Name</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OverDeliveryPct name="OverDeliveryPct">OverDeliveryPct</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OverDeliveryPct attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PackedExtensions name="PackedExtensions">PackedExtensions</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackedExtensions attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#PdsCWInventReceivedNow name="PdsCWInventReceivedNow">PdsCWInventReceivedNow</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PdsCWInventReceivedNow attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PdsCWQty name="PdsCWQty">PdsCWQty</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PdsCWQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PdsCWRemainInventFinancial name="PdsCWRemainInventFinancial">PdsCWRemainInventFinancial</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>CW invoice remainder</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PdsCWRemainInventFinancial attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>CW invoice remainder</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PdsCWRemainInventPhysical name="PdsCWRemainInventPhysical">PdsCWRemainInventPhysical</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>CW deliver remainder</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PdsCWRemainInventPhysical attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>CW deliver remainder</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Port name="Port">Port</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Port attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PriceUnit name="PriceUnit">PriceUnit</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceUnit attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ProcurementCategory name="ProcurementCategory">ProcurementCategory</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcurementCategory attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ProjCategoryId name="ProjCategoryId">ProjCategoryId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjCategoryId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjId name="ProjId">ProjId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjLinePropertyId name="ProjLinePropertyId">ProjLinePropertyId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjLinePropertyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjSalesCurrencyId name="ProjSalesCurrencyId">ProjSalesCurrencyId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales currency</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjSalesCurrencyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales currency</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjSalesPrice name="ProjSalesPrice">ProjSalesPrice</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjSalesPrice attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ProjSalesUnitId name="ProjSalesUnitId">ProjSalesUnitId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjSalesUnitId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjTaxGroupId name="ProjTaxGroupId">ProjTaxGroupId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjTaxGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjTaxItemGroupId name="ProjTaxItemGroupId">ProjTaxItemGroupId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjTaxItemGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjTransId name="ProjTransId">ProjTransId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjTransId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjWorker name="ProjWorker">ProjWorker</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjWorker attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PurchaseType name="PurchaseType">PurchaseType</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Type</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#PurchCommitmentLine_PSN name="PurchCommitmentLine_PSN">PurchCommitmentLine_PSN</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Commitment</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchCommitmentLine_PSN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Commitment</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PurchId name="PurchId">PurchId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchMarkup name="PurchMarkup">PurchMarkup</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchMarkup attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PurchPrice name="PurchPrice">PurchPrice</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Unit price</td></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchPrice attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unit price</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PurchQty name="PurchQty">PurchQty</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PurchReceivedNow name="PurchReceivedNow">PurchReceivedNow</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Receive now</td></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchReceivedNow attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Receive now</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PurchReqId name="PurchReqId">PurchReqId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchReqId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchReqLineRefId name="PurchReqLineRefId">PurchReqLineRefId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchReqLineRefId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchStatus name="PurchStatus">PurchStatus</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Line status</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Line status</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#PurchUnit name="PurchUnit">PurchUnit</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QtyOrdered name="QtyOrdered">QtyOrdered</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QtyOrdered attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#RemainInventFinancial name="RemainInventFinancial">RemainInventFinancial</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Invoice remainder</td></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemainInventFinancial attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Invoice remainder</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#RemainInventPhysical name="RemainInventPhysical">RemainInventPhysical</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Deliver remainder</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemainInventPhysical attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Deliver remainder</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#RemainPurchFinancial name="RemainPurchFinancial">RemainPurchFinancial</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Invoice remainder</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemainPurchFinancial attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Invoice remainder</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#RemainPurchPhysical name="RemainPurchPhysical">RemainPurchPhysical</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Deliver remainder</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemainPurchPhysical attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Deliver remainder</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ReqAttention name="ReqAttention">ReqAttention</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReqAttention attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReqPlanIdSched name="ReqPlanIdSched">ReqPlanIdSched</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReqPlanIdSched attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReqPOId name="ReqPOId">ReqPOId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReqPOId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Requester name="Requester">Requester</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Requester attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ReturnActionId name="ReturnActionId">ReturnActionId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnActionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnDispositionCodeId name="ReturnDispositionCodeId">ReturnDispositionCodeId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnDispositionCodeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnStatus name="ReturnStatus">ReturnStatus</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#Scrap name="Scrap">Scrap</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Scrap</td></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Scrap attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Scrap</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#ShippingDateConfirmed name="ShippingDateConfirmed">ShippingDateConfirmed</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingDateConfirmed attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#ShippingDateRequested name="ShippingDateRequested">ShippingDateRequested</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingDateRequested attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#SkipUpdate name="SkipUpdate">SkipUpdate</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SkipUpdate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SourceDocumentLine name="SourceDocumentLine">SourceDocumentLine</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Source document line</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceDocumentLine attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Source document line</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#StatProcId name="StatProcId">StatProcId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StatProcId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StatTriangularDeal name="StatTriangularDeal">StatTriangularDeal</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StatTriangularDeal attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#StockedProduct name="StockedProduct">StockedProduct</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StockedProduct attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#Tax1099Amount name="Tax1099Amount">Tax1099Amount</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Tax1099Amount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Tax1099Fields name="Tax1099Fields">Tax1099Fields</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Tax1099Fields attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Tax1099RecId name="Tax1099RecId">Tax1099RecId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Tax1099RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Tax1099State name="Tax1099State">Tax1099State</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Tax1099State attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Tax1099StateAmount name="Tax1099StateAmount">Tax1099StateAmount</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Tax1099StateAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxAutogenerated name="TaxAutogenerated">TaxAutogenerated</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAutogenerated attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxServiceCode_BR name="TaxServiceCode_BR">TaxServiceCode_BR</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxServiceCode_BR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxWithholdBaseCur_TH name="TaxWithholdBaseCur_TH">TaxWithholdBaseCur_TH</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Adjusted withholding tax</td></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdBaseCur_TH attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Adjusted withholding tax</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TaxWithholdGroup_TH name="TaxWithholdGroup_TH">TaxWithholdGroup_TH</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdGroup_TH attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxWithholdItemGroupHeading_TH name="TaxWithholdItemGroupHeading_TH">TaxWithholdItemGroupHeading_TH</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdItemGroupHeading_TH attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TransactionCode name="TransactionCode">TransactionCode</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Transport name="Transport">Transport</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Transport attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnderDeliveryPct name="UnderDeliveryPct">UnderDeliveryPct</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnderDeliveryPct attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ValidFrom name="ValidFrom">ValidFrom</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidFrom attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#ValidTo name="ValidTo">ValidTo</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidTo attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#VendAccount name="VendAccount">VendAccount</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendGroup name="VendGroup">VendGroup</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Group</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Group</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IntrastatCommodity name="IntrastatCommodity">IntrastatCommodity</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IntrastatCommodity attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#OrigCountryRegionId name="OrigCountryRegionId">OrigCountryRegionId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Country/region of origin</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrigCountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Country/region of origin</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrigStateId name="OrigStateId">OrigStateId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>State of origin</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrigStateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>State of origin</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseOrderLineCreationMethod name="PurchaseOrderLineCreationMethod">PurchaseOrderLineCreationMethod</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseOrderLineCreationMethod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/PurchLineHistory (this entity)  

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

### <a href=#Relationship_AccountingDistributionTemplateRelationshipId name="Relationship_AccountingDistributionTemplateRelationshipId">Relationship_AccountingDistributionTemplateRelationshipId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AccountingDistributionTemplateRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/AccountingFoundation/Group/AccountingDistributionTemplate.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountingFoundation/Group/AccountingDistributionTemplate.cdm.json/AccountingDistributionTemplate</a></td><td><a href="../../../Finance/AccountingFoundation/Group/AccountingDistributionTemplate.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AgreementLineRelationshipId name="Relationship_AgreementLineRelationshipId">Relationship_AgreementLineRelationshipId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AgreementLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetLine/AgreementLine.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/WorksheetLine/AgreementLine.cdm.json/AgreementLine</a></td><td><a href="../WorksheetLine/AgreementLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AssetBookRelationshipId name="Relationship_AssetBookRelationshipId">Relationship_AssetBookRelationshipId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetBookRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/FixedAssets/Main/AssetBook.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Main/AssetBook.cdm.json/AssetBook</a></td><td><a href="../../../Finance/FixedAssets/Main/AssetBook.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AssetBookTableRelationshipId name="Relationship_AssetBookTableRelationshipId">Relationship_AssetBookTableRelationshipId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetBookTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/FixedAssets/Main/AssetBookTable.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Main/AssetBookTable.cdm.json/AssetBookTable</a></td><td><a href="../../../Finance/FixedAssets/Main/AssetBookTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AssetGroupRelationshipId name="Relationship_AssetGroupRelationshipId">Relationship_AssetGroupRelationshipId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/FixedAssets/Group/AssetGroup.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Group/AssetGroup.cdm.json/AssetGroup</a></td><td><a href="../../../Finance/FixedAssets/Group/AssetGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AssetTableRelationshipId name="Relationship_AssetTableRelationshipId">Relationship_AssetTableRelationshipId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/FixedAssets/Main/AssetTable.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Main/AssetTable.cdm.json/AssetTable</a></td><td><a href="../../../Finance/FixedAssets/Main/AssetTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BarcodeSetupRelationshipId name="Relationship_BarcodeSetupRelationshipId">Relationship_BarcodeSetupRelationshipId</a>

First included in: Transaction/PurchLineHistory (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Inventory/Group/BarcodeSetup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/BarcodeSetup.cdm.json/BarcodeSetup</a></td><td><a href="../../Inventory/Group/BarcodeSetup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BOMTableRelationshipId name="Relationship_BOMTableRelationshipId">Relationship_BOMTableRelationshipId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BOMTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProductInformationManagement/Main/BOMTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/BOMTable.cdm.json/BOMTable</a></td><td><a href="../../ProductInformationManagement/Main/BOMTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CFOPTable_BRRelationshipId name="Relationship_CFOPTable_BRRelationshipId">Relationship_CFOPTable_BRRelationshipId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CFOPTable_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Bank/Group/CFOPTable_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Group/CFOPTable_BR.cdm.json/CFOPTable_BR</a></td><td><a href="../../../Finance/Bank/Group/CFOPTable_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CountyOrigDestRelationshipId name="Relationship_CountyOrigDestRelationshipId">Relationship_CountyOrigDestRelationshipId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CountyOrigDestRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Group/LogisticsAddressCounty.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Group/LogisticsAddressCounty.cdm.json/LogisticsAddressCounty</a></td><td><a href="../../../Common/GAB/Group/LogisticsAddressCounty.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CurrencyRelationshipId name="Relationship_CurrencyRelationshipId">Relationship_CurrencyRelationshipId</a>

First included in: Transaction/PurchLineHistory (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Currency/Group/Currency.md" target="_blank">/core/operationsCommon/Tables/Common/Currency/Group/Currency.cdm.json/Currency</a></td><td><a href="../../../Common/Currency/Group/Currency.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultDimensionRelationshipId name="Relationship_DefaultDimensionRelationshipId">Relationship_DefaultDimensionRelationshipId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/FinancialDimensions/Main/DimensionAttributeValueSet.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueSet.cdm.json/DimensionAttributeValueSet</a></td><td><a href="../../../Finance/FinancialDimensions/Main/DimensionAttributeValueSet.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DeliveryPostalAddressRelationshipId name="Relationship_DeliveryPostalAddressRelationshipId">Relationship_DeliveryPostalAddressRelationshipId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DeliveryPostalAddressRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Main/LogisticsPostalAddress.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Main/LogisticsPostalAddress.cdm.json/LogisticsPostalAddress</a></td><td><a href="../../../Common/GAB/Main/LogisticsPostalAddress.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_IntrastatPortRelationshipId name="Relationship_IntrastatPortRelationshipId">Relationship_IntrastatPortRelationshipId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_IntrastatPortRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Intrastat/Group/IntrastatPort.md" target="_blank">/core/operationsCommon/Tables/Common/Intrastat/Group/IntrastatPort.cdm.json/IntrastatPort</a></td><td><a href="../../../Common/Intrastat/Group/IntrastatPort.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_IntrastatStatProcRelationshipId name="Relationship_IntrastatStatProcRelationshipId">Relationship_IntrastatStatProcRelationshipId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_IntrastatStatProcRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Intrastat/Group/IntrastatStatProc.md" target="_blank">/core/operationsCommon/Tables/Common/Intrastat/Group/IntrastatStatProc.cdm.json/IntrastatStatProc</a></td><td><a href="../../../Common/Intrastat/Group/IntrastatStatProc.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_IntrastatTransactionCodeRelationshipId name="Relationship_IntrastatTransactionCodeRelationshipId">Relationship_IntrastatTransactionCodeRelationshipId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_IntrastatTransactionCodeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Intrastat/Group/IntrastatTransactionCode.md" target="_blank">/core/operationsCommon/Tables/Common/Intrastat/Group/IntrastatTransactionCode.cdm.json/IntrastatTransactionCode</a></td><td><a href="../../../Common/Intrastat/Group/IntrastatTransactionCode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_IntrastatTransportModeRelationshipId name="Relationship_IntrastatTransportModeRelationshipId">Relationship_IntrastatTransportModeRelationshipId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_IntrastatTransportModeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Intrastat/Group/IntrastatTransportMode.md" target="_blank">/core/operationsCommon/Tables/Common/Intrastat/Group/IntrastatTransportMode.cdm.json/IntrastatTransportMode</a></td><td><a href="../../../Common/Intrastat/Group/IntrastatTransportMode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventDimRelationshipId name="Relationship_InventDimRelationshipId">Relationship_InventDimRelationshipId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventDimRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Inventory/Main/InventDim.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/InventDim.cdm.json/InventDim</a></td><td><a href="../../Inventory/Main/InventDim.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventItemBarcodeRelationshipId name="Relationship_InventItemBarcodeRelationshipId">Relationship_InventItemBarcodeRelationshipId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventItemBarcodeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Inventory/Main/InventItemBarcode.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/InventItemBarcode.cdm.json/InventItemBarcode</a></td><td><a href="../../Inventory/Main/InventItemBarcode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventJournalTableRefRelationshipId name="Relationship_InventJournalTableRefRelationshipId">Relationship_InventJournalTableRefRelationshipId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventJournalTableRefRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Inventory/WorksheetHeader/InventJournalTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/WorksheetHeader/InventJournalTable.cdm.json/InventJournalTable</a></td><td><a href="../../Inventory/WorksheetHeader/InventJournalTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventTableRelationshipId name="Relationship_InventTableRelationshipId">Relationship_InventTableRelationshipId</a>

First included in: Transaction/PurchLineHistory (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProductInformationManagement/Main/InventTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/InventTable.cdm.json/InventTable</a></td><td><a href="../../ProductInformationManagement/Main/InventTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventTransOriginRelationshipId name="Relationship_InventTransOriginRelationshipId">Relationship_InventTransOriginRelationshipId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventTransOriginRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Inventory/Transaction/InventTransOrigin.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Transaction/InventTransOrigin.cdm.json/InventTransOrigin</a></td><td><a href="../../Inventory/Transaction/InventTransOrigin.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerDimensionRelationshipId name="Relationship_LedgerDimensionRelationshipId">Relationship_LedgerDimensionRelationshipId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../../Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProcurementCategoryRelationshipId name="Relationship_ProcurementCategoryRelationshipId">Relationship_ProcurementCategoryRelationshipId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProcurementCategoryRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProductInformationManagement/Main/EcoResCategory.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/EcoResCategory.cdm.json/EcoResCategory</a></td><td><a href="../../ProductInformationManagement/Main/EcoResCategory.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProdLineRefRelationshipId name="Relationship_ProdLineRefRelationshipId">Relationship_ProdLineRefRelationshipId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProdLineRefRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProductionControl/WorksheetHeader/ProdTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/WorksheetHeader/ProdTable.cdm.json/ProdTable</a></td><td><a href="../../ProductionControl/WorksheetHeader/ProdTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProdTableRefRelationshipId name="Relationship_ProdTableRefRelationshipId">Relationship_ProdTableRefRelationshipId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProdTableRefRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProductionControl/WorksheetHeader/ProdTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/WorksheetHeader/ProdTable.cdm.json/ProdTable</a></td><td><a href="../../ProductionControl/WorksheetHeader/ProdTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProjCategoryRelationshipId name="Relationship_ProjCategoryRelationshipId">Relationship_ProjCategoryRelationshipId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProjCategoryRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../ProfessionalServices/ProjectManagementAndAccounting/Group/ProjCategory.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Group/ProjCategory.cdm.json/ProjCategory</a></td><td><a href="../../../ProfessionalServices/ProjectManagementAndAccounting/Group/ProjCategory.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProjectSalesCurrencyRelationshipId name="Relationship_ProjectSalesCurrencyRelationshipId">Relationship_ProjectSalesCurrencyRelationshipId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProjectSalesCurrencyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Currency/Group/Currency.md" target="_blank">/core/operationsCommon/Tables/Common/Currency/Group/Currency.cdm.json/Currency</a></td><td><a href="../../../Common/Currency/Group/Currency.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProjectTaxGroupHeadingRelationshipId name="Relationship_ProjectTaxGroupHeadingRelationshipId">Relationship_ProjectTaxGroupHeadingRelationshipId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProjectTaxGroupHeadingRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Tax/Group/TaxGroupHeading.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxGroupHeading.cdm.json/TaxGroupHeading</a></td><td><a href="../../../Finance/Tax/Group/TaxGroupHeading.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProjectTaxItemGroupHeadingRelationshipId name="Relationship_ProjectTaxItemGroupHeadingRelationshipId">Relationship_ProjectTaxItemGroupHeadingRelationshipId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProjectTaxItemGroupHeadingRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_ProjItemTransRelationshipId name="Relationship_ProjItemTransRelationshipId">Relationship_ProjItemTransRelationshipId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProjItemTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../ProfessionalServices/ProjectManagementAndAccounting/Transaction/ProjItemTrans.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Transaction/ProjItemTrans.cdm.json/ProjItemTrans</a></td><td><a href="../../../ProfessionalServices/ProjectManagementAndAccounting/Transaction/ProjItemTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProjLinePropertyRelationshipId name="Relationship_ProjLinePropertyRelationshipId">Relationship_ProjLinePropertyRelationshipId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProjLinePropertyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../ProfessionalServices/ProjectManagementAndAccounting/Group/ProjLineProperty.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Group/ProjLineProperty.cdm.json/ProjLineProperty</a></td><td><a href="../../../ProfessionalServices/ProjectManagementAndAccounting/Group/ProjLineProperty.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProjTableRelationshipId name="Relationship_ProjTableRelationshipId">Relationship_ProjTableRelationshipId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProjTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../ProfessionalServices/ProjectManagementAndAccounting/Main/ProjTable.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Main/ProjTable.cdm.json/ProjTable</a></td><td><a href="../../../ProfessionalServices/ProjectManagementAndAccounting/Main/ProjTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PurchCommitmentLine_PSNRelationshipId name="Relationship_PurchCommitmentLine_PSNRelationshipId">Relationship_PurchCommitmentLine_PSNRelationshipId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchCommitmentLine_PSNRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Budget/Miscellaneous/PurchCommitmentLine_PSN.md" target="_blank">/core/operationsCommon/Tables/Finance/Budget/Miscellaneous/PurchCommitmentLine_PSN.cdm.json/PurchCommitmentLine_PSN</a></td><td><a href="../../../Finance/Budget/Miscellaneous/PurchCommitmentLine_PSN.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PurchLineRelationshipId name="Relationship_PurchLineRelationshipId">Relationship_PurchLineRelationshipId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetLine/PurchLine.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/WorksheetLine/PurchLine.cdm.json/PurchLine</a></td><td><a href="../WorksheetLine/PurchLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PurchReqLineRelationshipId name="Relationship_PurchReqLineRelationshipId">Relationship_PurchReqLineRelationshipId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchReqLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetLine/PurchReqLine.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/WorksheetLine/PurchReqLine.cdm.json/PurchReqLine</a></td><td><a href="../WorksheetLine/PurchReqLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PurchReturnActionDefaultsRelationshipId name="Relationship_PurchReturnActionDefaultsRelationshipId">Relationship_PurchReturnActionDefaultsRelationshipId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchReturnActionDefaultsRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../SalesAndMarketing/Group/ReturnActionDefaults.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Group/ReturnActionDefaults.cdm.json/ReturnActionDefaults</a></td><td><a href="../../SalesAndMarketing/Group/ReturnActionDefaults.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PurchTableHistoryRelationshipId name="Relationship_PurchTableHistoryRelationshipId">Relationship_PurchTableHistoryRelationshipId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchTableHistoryRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="PurchTableHistory.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Transaction/PurchTableHistory.cdm.json/PurchTableHistory</a></td><td><a href="PurchTableHistory.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ReqPlanSchedRelationshipId name="Relationship_ReqPlanSchedRelationshipId">Relationship_ReqPlanSchedRelationshipId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReqPlanSchedRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../MasterPlanning/Group/ReqPlanSched.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/MasterPlanning/Group/ReqPlanSched.cdm.json/ReqPlanSched</a></td><td><a href="../../MasterPlanning/Group/ReqPlanSched.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ReturnDispositionCodeRelationshipId name="Relationship_ReturnDispositionCodeRelationshipId">Relationship_ReturnDispositionCodeRelationshipId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReturnDispositionCodeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../SalesAndMarketing/Reference/ReturnDispositionCode.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Reference/ReturnDispositionCode.cdm.json/ReturnDispositionCode</a></td><td><a href="../../SalesAndMarketing/Reference/ReturnDispositionCode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RouteTableRelationshipId name="Relationship_RouteTableRelationshipId">Relationship_RouteTableRelationshipId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RouteTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProductionControl/Main/RouteTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/Main/RouteTable.cdm.json/RouteTable</a></td><td><a href="../../ProductionControl/Main/RouteTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SalesTableRefRelationshipId name="Relationship_SalesTableRefRelationshipId">Relationship_SalesTableRefRelationshipId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SalesTableRefRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../SalesAndMarketing/WorksheetHeader/SalesTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/WorksheetHeader/SalesTable.cdm.json/SalesTable</a></td><td><a href="../../SalesAndMarketing/WorksheetHeader/SalesTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SourceDocumentLineRelationshipId name="Relationship_SourceDocumentLineRelationshipId">Relationship_SourceDocumentLineRelationshipId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SourceDocumentLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/AccountingFoundation/TransactionLine/SourceDocumentLine.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountingFoundation/TransactionLine/SourceDocumentLine.cdm.json/SourceDocumentLine</a></td><td><a href="../../../Finance/AccountingFoundation/TransactionLine/SourceDocumentLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_StateRelationshipId name="Relationship_StateRelationshipId">Relationship_StateRelationshipId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_StateRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Group/LogisticsAddressState.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Group/LogisticsAddressState.cdm.json/LogisticsAddressState</a></td><td><a href="../../../Common/GAB/Group/LogisticsAddressState.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_Tax1099BoxDetailRelationshipId name="Relationship_Tax1099BoxDetailRelationshipId">Relationship_Tax1099BoxDetailRelationshipId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_Tax1099BoxDetailRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/AccountsPayable/Miscellaneous/Tax1099BoxDetail.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsPayable/Miscellaneous/Tax1099BoxDetail.cdm.json/Tax1099BoxDetail</a></td><td><a href="../../../Finance/AccountsPayable/Miscellaneous/Tax1099BoxDetail.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_Tax1099FieldsRelationshipId name="Relationship_Tax1099FieldsRelationshipId">Relationship_Tax1099FieldsRelationshipId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_Tax1099FieldsRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/AccountsPayable/Group/Tax1099Fields.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsPayable/Group/Tax1099Fields.cdm.json/Tax1099Fields</a></td><td><a href="../../../Finance/AccountsPayable/Group/Tax1099Fields.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxGroupHeadingRelationshipId name="Relationship_TaxGroupHeadingRelationshipId">Relationship_TaxGroupHeadingRelationshipId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxGroupHeadingRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Tax/Group/TaxGroupHeading.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxGroupHeading.cdm.json/TaxGroupHeading</a></td><td><a href="../../../Finance/Tax/Group/TaxGroupHeading.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxItemGroupHeadingRelationshipId name="Relationship_TaxItemGroupHeadingRelationshipId">Relationship_TaxItemGroupHeadingRelationshipId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxItemGroupHeadingRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_TaxWithholdGroupHeadingRelationshipId name="Relationship_TaxWithholdGroupHeadingRelationshipId">Relationship_TaxWithholdGroupHeadingRelationshipId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxWithholdGroupHeadingRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Tax/Group/TaxWithholdGroupHeading.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxWithholdGroupHeading.cdm.json/TaxWithholdGroupHeading</a></td><td><a href="../../../Finance/Tax/Group/TaxWithholdGroupHeading.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxWithholdItemGroupHeading_THRelationshipId name="Relationship_TaxWithholdItemGroupHeading_THRelationshipId">Relationship_TaxWithholdItemGroupHeading_THRelationshipId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxWithholdItemGroupHeading_THRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Tax/Group/TaxWithholdItemGroupHeading_TH.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxWithholdItemGroupHeading_TH.cdm.json/TaxWithholdItemGroupHeading_TH</a></td><td><a href="../../../Finance/Tax/Group/TaxWithholdItemGroupHeading_TH.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendGroupRelationshipId name="Relationship_VendGroupRelationshipId">Relationship_VendGroupRelationshipId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Vendor/Group/VendGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Vendor/Group/VendGroup.cdm.json/VendGroup</a></td><td><a href="../../Vendor/Group/VendGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendTableRelationshipId name="Relationship_VendTableRelationshipId">Relationship_VendTableRelationshipId</a>

First included in: Transaction/PurchLineHistory (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Vendor/Main/VendTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Vendor/Main/VendTable.cdm.json/VendTable</a></td><td><a href="../../Vendor/Main/VendTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_OrigStateRelationshipId name="Relationship_OrigStateRelationshipId">Relationship_OrigStateRelationshipId</a>

First included in: Transaction/PurchLineHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OrigStateRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Group/LogisticsAddressState.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Group/LogisticsAddressState.cdm.json/LogisticsAddressState</a></td><td><a href="../../../Common/GAB/Group/LogisticsAddressState.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_IntrastatCommodityRelationshipId name="Relationship_IntrastatCommodityRelationshipId">Relationship_IntrastatCommodityRelationshipId</a>

First included in: Transaction/PurchLineHistory (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProductInformationManagement/Main/EcoResCategory.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/EcoResCategory.cdm.json/EcoResCategory</a></td><td><a href="../../ProductInformationManagement/Main/EcoResCategory.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Transaction/PurchLineHistory (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
