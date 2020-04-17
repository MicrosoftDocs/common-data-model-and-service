---
title: PurchReqLine - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# PurchReqLine

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/SupplyChain/ProcurementAndSourcing/WorksheetLine/PurchReqLine.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PurchReqLine/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[AccountingDistributionTemplate](#AccountingDistributionTemplate)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[ActivityNumber](#ActivityNumber)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[ActivityNumberDataArea](#ActivityNumberDataArea)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[AddressRefRecId](#AddressRefRecId)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[AddressRefTableId](#AddressRefTableId)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[AssetGroup](#AssetGroup)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[AssetGroupDataArea](#AssetGroupDataArea)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[AssetRuleQualifierOption](#AssetRuleQualifierOption)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[AssetRuleQualifierOptionLocal](#AssetRuleQualifierOptionLocal)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[AssetRuleQualifierOptionName](#AssetRuleQualifierOptionName)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[Attention](#Attention)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[BusinessJustification](#BusinessJustification)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[BuyingLegalEntity](#BuyingLegalEntity)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[CFOPTable_BR](#CFOPTable_BR)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[CFPSTable_BR](#CFPSTable_BR)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[CurrencyCode](#CurrencyCode)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[DefaultDimension](#DefaultDimension)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[DeliveryName](#DeliveryName)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[DeliveryPostalAddress](#DeliveryPostalAddress)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[ExternalItemId](#ExternalItemId)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[InventDimId](#InventDimId)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[InventDimIdDataArea](#InventDimIdDataArea)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[InventLocationId](#InventLocationId)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[InventLocationIdDataArea](#InventLocationIdDataArea)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[IsModified](#IsModified)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[IsPreEncumbranceRequired](#IsPreEncumbranceRequired)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[IsPrepayment](#IsPrepayment)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[IsPurchaseOrderGenerationManual](#IsPurchaseOrderGenerationManual)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[IsSaved](#IsSaved)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[ItemId](#ItemId)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[ItemIdDataArea](#ItemIdDataArea)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[ItemIdNonCatalog](#ItemIdNonCatalog)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[LineAmount](#LineAmount)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[LineComplete](#LineComplete)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[LineDisc](#LineDisc)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[LineNum](#LineNum)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[LinePercent](#LinePercent)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[LineRefId](#LineRefId)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[LineType](#LineType)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[Name](#Name)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[PrePaymentDetails](#PrePaymentDetails)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[PriceDiscountTransfer](#PriceDiscountTransfer)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[PriceUnit](#PriceUnit)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[ProcurementCategory](#ProcurementCategory)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[ProjCategoryId](#ProjCategoryId)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[ProjCategoryIdDataArea](#ProjCategoryIdDataArea)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[ProjId](#ProjId)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[ProjIdDataArea](#ProjIdDataArea)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[ProjLinePropertyId](#ProjLinePropertyId)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[ProjLinePropertyIdDataArea](#ProjLinePropertyIdDataArea)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[ProjSalesCurrencyId](#ProjSalesCurrencyId)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[ProjSalesPrice](#ProjSalesPrice)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[ProjSalesUnitOfMeasure](#ProjSalesUnitOfMeasure)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[ProjTaxGroupId](#ProjTaxGroupId)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[ProjTaxGroupIdDataArea](#ProjTaxGroupIdDataArea)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[ProjTaxItemGroupId](#ProjTaxItemGroupId)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[ProjTaxItemGroupIdDataArea](#ProjTaxItemGroupIdDataArea)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[ProjTransId](#ProjTransId)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[ProjTransIdDataArea](#ProjTransIdDataArea)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[PurchAgreement](#PurchAgreement)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[PurchId](#PurchId)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[PurchIdDataArea](#PurchIdDataArea)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[PurchLineCreated](#PurchLineCreated)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[PurchMarkup](#PurchMarkup)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[PurchPrice](#PurchPrice)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[PurchQty](#PurchQty)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[PurchReqConsolidationStatus](#PurchReqConsolidationStatus)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[PurchReqTable](#PurchReqTable)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[PurchRFQCaseId](#PurchRFQCaseId)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[PurchRFQCaseIdDataArea](#PurchRFQCaseIdDataArea)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[PurchUnitOfMeasure](#PurchUnitOfMeasure)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[ReasonRefRecId](#ReasonRefRecId)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[ReceivingOperatingUnit](#ReceivingOperatingUnit)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[RequiredDate](#RequiredDate)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[Requisitioner](#Requisitioner)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[RequisitionPurpose](#RequisitionPurpose)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[RequisitionStatus](#RequisitionStatus)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[RFQRequirement](#RFQRequirement)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[SalesPurchOperationType_BR](#SalesPurchOperationType_BR)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[SequenceNumber](#SequenceNumber)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[SourceDocumentLine](#SourceDocumentLine)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[TaxGroup](#TaxGroup)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[TaxGroupDataArea](#TaxGroupDataArea)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[TaxItemGroup](#TaxItemGroup)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[TaxItemGroupDataArea](#TaxItemGroupDataArea)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[TaxServiceCode_BR](#TaxServiceCode_BR)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[TransDate](#TransDate)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[URL](#URL)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[VendAccount](#VendAccount)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[VendAccountDataArea](#VendAccountDataArea)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[VendQuoteNumber](#VendQuoteNumber)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[PackedExtensions](#PackedExtensions)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[IsPriceDiscCalculated](#IsPriceDiscCalculated)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[BudgetReservationLine_PSN](#BudgetReservationLine_PSN)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[CompanyLocation_IN](#CompanyLocation_IN)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[ExciseRecordType_IN](#ExciseRecordType_IN)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[ExciseTariffCodes_IN](#ExciseTariffCodes_IN)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[ExciseType_IN](#ExciseType_IN)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[Exempt_IN](#Exempt_IN)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[HSNCodeTable_IN](#HSNCodeTable_IN)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[ITCCategory_IN](#ITCCategory_IN)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[NonBusinessUsagePercentage_IN](#NonBusinessUsagePercentage_IN)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[SalesTaxFormTypes_IN](#SalesTaxFormTypes_IN)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[ServiceAccountingCodeTable_IN](#ServiceAccountingCodeTable_IN)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[ServiceCodeTable_IN](#ServiceCodeTable_IN)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[ServiceCategory_IN](#ServiceCategory_IN)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[GTAServiceCategory_IN](#GTAServiceCategory_IN)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[VATGoodsType_IN](#VATGoodsType_IN)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[NonRecoverablePercent_IN](#NonRecoverablePercent_IN)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[VendorLocation_IN](#VendorLocation_IN)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[VendorTaxInformation_IN](#VendorTaxInformation_IN)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[DSA_IN](#DSA_IN)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[CustomsTariffCodeTable_IN](#CustomsTariffCodeTable_IN)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[MaximumRetailPrice_IN](#MaximumRetailPrice_IN)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[PurchSupplierAuxId](#PurchSupplierAuxId)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[PSNCalendarDays](#PSNCalendarDays)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[PSNLeadTime](#PSNLeadTime)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[Relationship_AccountingDistributionTemplateRelationshipId](#Relationship_AccountingDistributionTemplateRelationshipId)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[Relationship_AssetGroupRelationshipId](#Relationship_AssetGroupRelationshipId)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[Relationship_AssetRuleQualifierOptionRelationshipId](#Relationship_AssetRuleQualifierOptionRelationshipId)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[Relationship_AssetRuleQualifierOptionLocalRelationshipId](#Relationship_AssetRuleQualifierOptionLocalRelationshipId)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[Relationship_CFOPTable_BRRelationshipId](#Relationship_CFOPTable_BRRelationshipId)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[Relationship_CFPSTable_BRRelationshipId](#Relationship_CFPSTable_BRRelationshipId)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[Relationship_CompanyInfoRelationshipId](#Relationship_CompanyInfoRelationshipId)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[Relationship_CurrencyRelationshipId](#Relationship_CurrencyRelationshipId)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[Relationship_CurrencyCodeRelationshipId](#Relationship_CurrencyCodeRelationshipId)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[Relationship_DefaultDimensionRelationshipId](#Relationship_DefaultDimensionRelationshipId)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[Relationship_DeliveryPostalAddressRelationshipId](#Relationship_DeliveryPostalAddressRelationshipId)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[Relationship_EcoResCategoryRelationshipId](#Relationship_EcoResCategoryRelationshipId)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[Relationship_InventDimRelationshipId](#Relationship_InventDimRelationshipId)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[Relationship_InventLocationRelationshipId](#Relationship_InventLocationRelationshipId)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[Relationship_InventTableRelationshipId](#Relationship_InventTableRelationshipId)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[Relationship_OMOperatingUnitRelationshipId](#Relationship_OMOperatingUnitRelationshipId)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[Relationship_ProjCategoryRelationshipId](#Relationship_ProjCategoryRelationshipId)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[Relationship_ProjItemTransRelationshipId](#Relationship_ProjItemTransRelationshipId)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[Relationship_ProjLinePropertyRelationshipId](#Relationship_ProjLinePropertyRelationshipId)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[Relationship_ProjTableRelationshipId](#Relationship_ProjTableRelationshipId)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[Relationship_ProjTaxGroupHeadingRelationshipId](#Relationship_ProjTaxGroupHeadingRelationshipId)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[Relationship_ProjTaxItemGroupHeadingRelationshipId](#Relationship_ProjTaxItemGroupHeadingRelationshipId)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[Relationship_PurchaseAgreementRelationshipId](#Relationship_PurchaseAgreementRelationshipId)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[Relationship_PurchReqBusinessJustificationCodesRelationshipId](#Relationship_PurchReqBusinessJustificationCodesRelationshipId)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[Relationship_PurchReqTableRelationshipId](#Relationship_PurchReqTableRelationshipId)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[Relationship_PurchRFQCaseTableRelationshipId](#Relationship_PurchRFQCaseTableRelationshipId)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[Relationship_PurchTableRelationshipId](#Relationship_PurchTableRelationshipId)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[Relationship_ReasonRefRelationshipId](#Relationship_ReasonRefRelationshipId)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[Relationship_SalesPurchOperationType_BRRelationshipId](#Relationship_SalesPurchOperationType_BRRelationshipId)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[Relationship_smmActivitiesRelationshipId](#Relationship_smmActivitiesRelationshipId)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[Relationship_SourceDocumentLineRelationshipId](#Relationship_SourceDocumentLineRelationshipId)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[Relationship_TaxGroupHeadingRelationshipId](#Relationship_TaxGroupHeadingRelationshipId)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[Relationship_TaxItemGroupHeadingRelationshipId](#Relationship_TaxItemGroupHeadingRelationshipId)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[Relationship_TaxServiceCode_BRRelationshipId](#Relationship_TaxServiceCode_BRRelationshipId)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[Relationship_VendTableRelationshipId](#Relationship_VendTableRelationshipId)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|
|[Relationship_BudgetReservationLine_PSNRelationshipId](#Relationship_BudgetReservationLine_PSNRelationshipId)||<a href="PurchReqLine.md" target="_blank">WorksheetLine/PurchReqLine</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PurchReqLine/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AccountingDistributionTemplate name="AccountingDistributionTemplate">AccountingDistributionTemplate</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

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

First included in: WorksheetLine/PurchReqLine (this entity)  

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

### <a href=#ActivityNumberDataArea name="ActivityNumberDataArea">ActivityNumberDataArea</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActivityNumberDataArea attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AddressRefRecId name="AddressRefRecId">AddressRefRecId</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

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

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressRefTableId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#AssetGroup name="AssetGroup">AssetGroup</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

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

### <a href=#AssetGroupDataArea name="AssetGroupDataArea">AssetGroupDataArea</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetGroupDataArea attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AssetRuleQualifierOption name="AssetRuleQualifierOption">AssetRuleQualifierOption</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetRuleQualifierOption attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AssetRuleQualifierOptionLocal name="AssetRuleQualifierOptionLocal">AssetRuleQualifierOptionLocal</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetRuleQualifierOptionLocal attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AssetRuleQualifierOptionName name="AssetRuleQualifierOptionName">AssetRuleQualifierOptionName</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AssetRuleQualifierOptionName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Attention name="Attention">Attention</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Attention attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BusinessJustification name="BusinessJustification">BusinessJustification</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BusinessJustification attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BuyingLegalEntity name="BuyingLegalEntity">BuyingLegalEntity</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BuyingLegalEntity attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CFOPTable_BR name="CFOPTable_BR">CFOPTable_BR</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

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

### <a href=#CFPSTable_BR name="CFPSTable_BR">CFPSTable_BR</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFPSTable_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

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

### <a href=#DefaultDimension name="DefaultDimension">DefaultDimension</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

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

### <a href=#DeliveryName name="DeliveryName">DeliveryName</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

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

First included in: WorksheetLine/PurchReqLine (this entity)  

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

### <a href=#ExternalItemId name="ExternalItemId">ExternalItemId</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

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

### <a href=#InventDimId name="InventDimId">InventDimId</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

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

### <a href=#InventDimIdDataArea name="InventDimIdDataArea">InventDimIdDataArea</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventDimIdDataArea attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventLocationId name="InventLocationId">InventLocationId</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventLocationIdDataArea name="InventLocationIdDataArea">InventLocationIdDataArea</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventLocationIdDataArea attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsModified name="IsModified">IsModified</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsModified attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsPreEncumbranceRequired name="IsPreEncumbranceRequired">IsPreEncumbranceRequired</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPreEncumbranceRequired attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsPrepayment name="IsPrepayment">IsPrepayment</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPrepayment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsPurchaseOrderGenerationManual name="IsPurchaseOrderGenerationManual">IsPurchaseOrderGenerationManual</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPurchaseOrderGenerationManual attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#IsSaved name="IsSaved">IsSaved</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSaved attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ItemId name="ItemId">ItemId</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

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

### <a href=#ItemIdDataArea name="ItemIdDataArea">ItemIdDataArea</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemIdDataArea attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemIdNonCatalog name="ItemIdNonCatalog">ItemIdNonCatalog</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemIdNonCatalog attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineAmount name="LineAmount">LineAmount</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

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

### <a href=#LineComplete name="LineComplete">LineComplete</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineComplete attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LineDisc name="LineDisc">LineDisc</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

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

### <a href=#LineNum name="LineNum">LineNum</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNum attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#LinePercent name="LinePercent">LinePercent</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

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

### <a href=#LineRefId name="LineRefId">LineRefId</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineRefId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**is.readOnly**  
**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineType name="LineType">LineType</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

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

### <a href=#PrePaymentDetails name="PrePaymentDetails">PrePaymentDetails</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrePaymentDetails attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PriceDiscountTransfer name="PriceDiscountTransfer">PriceDiscountTransfer</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceDiscountTransfer attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PriceUnit name="PriceUnit">PriceUnit</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

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

First included in: WorksheetLine/PurchReqLine (this entity)  

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

First included in: WorksheetLine/PurchReqLine (this entity)  

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

### <a href=#ProjCategoryIdDataArea name="ProjCategoryIdDataArea">ProjCategoryIdDataArea</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjCategoryIdDataArea attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjId name="ProjId">ProjId</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

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

### <a href=#ProjIdDataArea name="ProjIdDataArea">ProjIdDataArea</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjIdDataArea attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjLinePropertyId name="ProjLinePropertyId">ProjLinePropertyId</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

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

### <a href=#ProjLinePropertyIdDataArea name="ProjLinePropertyIdDataArea">ProjLinePropertyIdDataArea</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjLinePropertyIdDataArea attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjSalesCurrencyId name="ProjSalesCurrencyId">ProjSalesCurrencyId</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjSalesCurrencyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjSalesPrice name="ProjSalesPrice">ProjSalesPrice</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

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

### <a href=#ProjSalesUnitOfMeasure name="ProjSalesUnitOfMeasure">ProjSalesUnitOfMeasure</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjSalesUnitOfMeasure attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ProjTaxGroupId name="ProjTaxGroupId">ProjTaxGroupId</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

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

### <a href=#ProjTaxGroupIdDataArea name="ProjTaxGroupIdDataArea">ProjTaxGroupIdDataArea</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjTaxGroupIdDataArea attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjTaxItemGroupId name="ProjTaxItemGroupId">ProjTaxItemGroupId</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

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

### <a href=#ProjTaxItemGroupIdDataArea name="ProjTaxItemGroupIdDataArea">ProjTaxItemGroupIdDataArea</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjTaxItemGroupIdDataArea attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjTransId name="ProjTransId">ProjTransId</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

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

### <a href=#ProjTransIdDataArea name="ProjTransIdDataArea">ProjTransIdDataArea</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjTransIdDataArea attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchAgreement name="PurchAgreement">PurchAgreement</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchAgreement attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PurchId name="PurchId">PurchId</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

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

### <a href=#PurchIdDataArea name="PurchIdDataArea">PurchIdDataArea</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchIdDataArea attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchLineCreated name="PurchLineCreated">PurchLineCreated</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchLineCreated attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PurchMarkup name="PurchMarkup">PurchMarkup</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

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

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchPrice attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PurchQty name="PurchQty">PurchQty</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

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

### <a href=#PurchReqConsolidationStatus name="PurchReqConsolidationStatus">PurchReqConsolidationStatus</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchReqConsolidationStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PurchReqTable name="PurchReqTable">PurchReqTable</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchReqTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PurchRFQCaseId name="PurchRFQCaseId">PurchRFQCaseId</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchRFQCaseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchRFQCaseIdDataArea name="PurchRFQCaseIdDataArea">PurchRFQCaseIdDataArea</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchRFQCaseIdDataArea attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchUnitOfMeasure name="PurchUnitOfMeasure">PurchUnitOfMeasure</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchUnitOfMeasure attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ReasonRefRecId name="ReasonRefRecId">ReasonRefRecId</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReasonRefRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ReceivingOperatingUnit name="ReceivingOperatingUnit">ReceivingOperatingUnit</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivingOperatingUnit attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RequiredDate name="RequiredDate">RequiredDate</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequiredDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#Requisitioner name="Requisitioner">Requisitioner</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Requisitioner attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RequisitionPurpose name="RequisitionPurpose">RequisitionPurpose</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequisitionPurpose attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#RequisitionStatus name="RequisitionStatus">RequisitionStatus</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequisitionStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#RFQRequirement name="RFQRequirement">RFQRequirement</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQRequirement attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#SalesPurchOperationType_BR name="SalesPurchOperationType_BR">SalesPurchOperationType_BR</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPurchOperationType_BR attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SequenceNumber name="SequenceNumber">SequenceNumber</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SequenceNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SourceDocumentLine name="SourceDocumentLine">SourceDocumentLine</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceDocumentLine attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxGroup name="TaxGroup">TaxGroup</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

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

### <a href=#TaxGroupDataArea name="TaxGroupDataArea">TaxGroupDataArea</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxGroupDataArea attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxItemGroup name="TaxItemGroup">TaxItemGroup</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

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

### <a href=#TaxItemGroupDataArea name="TaxItemGroupDataArea">TaxItemGroupDataArea</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxItemGroupDataArea attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxServiceCode_BR name="TaxServiceCode_BR">TaxServiceCode_BR</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

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

### <a href=#TransDate name="TransDate">TransDate</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#URL name="URL">URL</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the URL attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendAccount name="VendAccount">VendAccount</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

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

### <a href=#VendAccountDataArea name="VendAccountDataArea">VendAccountDataArea</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendAccountDataArea attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendQuoteNumber name="VendQuoteNumber">VendQuoteNumber</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendQuoteNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PackedExtensions name="PackedExtensions">PackedExtensions</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

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

### <a href=#IsPriceDiscCalculated name="IsPriceDiscCalculated">IsPriceDiscCalculated</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPriceDiscCalculated attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#BudgetReservationLine_PSN name="BudgetReservationLine_PSN">BudgetReservationLine_PSN</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetReservationLine_PSN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CompanyLocation_IN name="CompanyLocation_IN">CompanyLocation_IN</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyLocation_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ExciseRecordType_IN name="ExciseRecordType_IN">ExciseRecordType_IN</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExciseRecordType_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ExciseTariffCodes_IN name="ExciseTariffCodes_IN">ExciseTariffCodes_IN</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExciseTariffCodes_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ExciseType_IN name="ExciseType_IN">ExciseType_IN</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExciseType_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Exempt_IN name="Exempt_IN">Exempt_IN</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Exempt_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#HSNCodeTable_IN name="HSNCodeTable_IN">HSNCodeTable_IN</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HSNCodeTable_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ITCCategory_IN name="ITCCategory_IN">ITCCategory_IN</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ITCCategory_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#NonBusinessUsagePercentage_IN name="NonBusinessUsagePercentage_IN">NonBusinessUsagePercentage_IN</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NonBusinessUsagePercentage_IN attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SalesTaxFormTypes_IN name="SalesTaxFormTypes_IN">SalesTaxFormTypes_IN</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxFormTypes_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ServiceAccountingCodeTable_IN name="ServiceAccountingCodeTable_IN">ServiceAccountingCodeTable_IN</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceAccountingCodeTable_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ServiceCodeTable_IN name="ServiceCodeTable_IN">ServiceCodeTable_IN</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceCodeTable_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ServiceCategory_IN name="ServiceCategory_IN">ServiceCategory_IN</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceCategory_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#GTAServiceCategory_IN name="GTAServiceCategory_IN">GTAServiceCategory_IN</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GTAServiceCategory_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#VATGoodsType_IN name="VATGoodsType_IN">VATGoodsType_IN</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VATGoodsType_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#NonRecoverablePercent_IN name="NonRecoverablePercent_IN">NonRecoverablePercent_IN</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NonRecoverablePercent_IN attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#VendorLocation_IN name="VendorLocation_IN">VendorLocation_IN</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorLocation_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#VendorTaxInformation_IN name="VendorTaxInformation_IN">VendorTaxInformation_IN</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorTaxInformation_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DSA_IN name="DSA_IN">DSA_IN</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DSA_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CustomsTariffCodeTable_IN name="CustomsTariffCodeTable_IN">CustomsTariffCodeTable_IN</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomsTariffCodeTable_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#MaximumRetailPrice_IN name="MaximumRetailPrice_IN">MaximumRetailPrice_IN</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumRetailPrice_IN attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PurchSupplierAuxId name="PurchSupplierAuxId">PurchSupplierAuxId</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchSupplierAuxId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PSNCalendarDays name="PSNCalendarDays">PSNCalendarDays</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PSNCalendarDays attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PSNLeadTime name="PSNLeadTime">PSNLeadTime</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PSNLeadTime attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Relationship_AccountingDistributionTemplateRelationshipId name="Relationship_AccountingDistributionTemplateRelationshipId">Relationship_AccountingDistributionTemplateRelationshipId</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/AccountingFoundation/Group/AccountingDistributionTemplate.md" target="_blank">/core/erp/Tables/Finance/AccountingFoundation/Group/AccountingDistributionTemplate.cdm.json/AccountingDistributionTemplate</a></td><td><a href="../../../Finance/AccountingFoundation/Group/AccountingDistributionTemplate.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AssetGroupRelationshipId name="Relationship_AssetGroupRelationshipId">Relationship_AssetGroupRelationshipId</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/FixedAssets/Group/AssetGroup.md" target="_blank">/core/erp/Tables/Finance/FixedAssets/Group/AssetGroup.cdm.json/AssetGroup</a></td><td><a href="../../../Finance/FixedAssets/Group/AssetGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AssetRuleQualifierOptionRelationshipId name="Relationship_AssetRuleQualifierOptionRelationshipId">Relationship_AssetRuleQualifierOptionRelationshipId</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetRuleQualifierOptionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/FixedAssets/Reference/AssetRuleQualifierOption.md" target="_blank">/core/erp/Tables/Finance/FixedAssets/Reference/AssetRuleQualifierOption.cdm.json/AssetRuleQualifierOption</a></td><td><a href="../../../Finance/FixedAssets/Reference/AssetRuleQualifierOption.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AssetRuleQualifierOptionLocalRelationshipId name="Relationship_AssetRuleQualifierOptionLocalRelationshipId">Relationship_AssetRuleQualifierOptionLocalRelationshipId</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetRuleQualifierOptionLocalRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/FixedAssets/Reference/AssetRuleQualifierOptionLocal.md" target="_blank">/core/erp/Tables/Finance/FixedAssets/Reference/AssetRuleQualifierOptionLocal.cdm.json/AssetRuleQualifierOptionLocal</a></td><td><a href="../../../Finance/FixedAssets/Reference/AssetRuleQualifierOptionLocal.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CFOPTable_BRRelationshipId name="Relationship_CFOPTable_BRRelationshipId">Relationship_CFOPTable_BRRelationshipId</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Bank/Group/CFOPTable_BR.md" target="_blank">/core/erp/Tables/Finance/Bank/Group/CFOPTable_BR.cdm.json/CFOPTable_BR</a></td><td><a href="../../../Finance/Bank/Group/CFOPTable_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CFPSTable_BRRelationshipId name="Relationship_CFPSTable_BRRelationshipId">Relationship_CFPSTable_BRRelationshipId</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CFPSTable_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/APARShared/Group/CFPSTable_BR.md" target="_blank">/core/erp/Tables/Finance/APARShared/Group/CFPSTable_BR.cdm.json/CFPSTable_BR</a></td><td><a href="../../../Finance/APARShared/Group/CFPSTable_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyInfoRelationshipId name="Relationship_CompanyInfoRelationshipId">Relationship_CompanyInfoRelationshipId</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CompanyInfoRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_CurrencyRelationshipId name="Relationship_CurrencyRelationshipId">Relationship_CurrencyRelationshipId</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Currency/Group/Currency.md" target="_blank">/core/erp/Tables/Common/Currency/Group/Currency.cdm.json/Currency</a></td><td><a href="../../../Common/Currency/Group/Currency.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CurrencyCodeRelationshipId name="Relationship_CurrencyCodeRelationshipId">Relationship_CurrencyCodeRelationshipId</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CurrencyCodeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Currency/Group/Currency.md" target="_blank">/core/erp/Tables/Common/Currency/Group/Currency.cdm.json/Currency</a></td><td><a href="../../../Common/Currency/Group/Currency.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultDimensionRelationshipId name="Relationship_DefaultDimensionRelationshipId">Relationship_DefaultDimensionRelationshipId</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/FinancialDimensions/Main/DimensionAttributeValueSet.md" target="_blank">/core/erp/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueSet.cdm.json/DimensionAttributeValueSet</a></td><td><a href="../../../Finance/FinancialDimensions/Main/DimensionAttributeValueSet.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DeliveryPostalAddressRelationshipId name="Relationship_DeliveryPostalAddressRelationshipId">Relationship_DeliveryPostalAddressRelationshipId</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Main/LogisticsPostalAddress.md" target="_blank">/core/erp/Tables/Common/GAB/Main/LogisticsPostalAddress.cdm.json/LogisticsPostalAddress</a></td><td><a href="../../../Common/GAB/Main/LogisticsPostalAddress.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_EcoResCategoryRelationshipId name="Relationship_EcoResCategoryRelationshipId">Relationship_EcoResCategoryRelationshipId</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProductInformationManagement/Main/EcoResCategory.md" target="_blank">/core/erp/Tables/SupplyChain/ProductInformationManagement/Main/EcoResCategory.cdm.json/EcoResCategory</a></td><td><a href="../../ProductInformationManagement/Main/EcoResCategory.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventDimRelationshipId name="Relationship_InventDimRelationshipId">Relationship_InventDimRelationshipId</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Inventory/Main/InventDim.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/Main/InventDim.cdm.json/InventDim</a></td><td><a href="../../Inventory/Main/InventDim.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventLocationRelationshipId name="Relationship_InventLocationRelationshipId">Relationship_InventLocationRelationshipId</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventLocationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Inventory/Group/InventLocation.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/Group/InventLocation.cdm.json/InventLocation</a></td><td><a href="../../Inventory/Group/InventLocation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventTableRelationshipId name="Relationship_InventTableRelationshipId">Relationship_InventTableRelationshipId</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ProductInformationManagement/Main/InventTable.md" target="_blank">/core/erp/Tables/SupplyChain/ProductInformationManagement/Main/InventTable.cdm.json/InventTable</a></td><td><a href="../../ProductInformationManagement/Main/InventTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_OMOperatingUnitRelationshipId name="Relationship_OMOperatingUnitRelationshipId">Relationship_OMOperatingUnitRelationshipId</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OMOperatingUnitRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Main/OMOperatingUnit.md" target="_blank">/core/erp/Tables/Common/GAB/Main/OMOperatingUnit.cdm.json/OMOperatingUnit</a></td><td><a href="../../../Common/GAB/Main/OMOperatingUnit.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProjCategoryRelationshipId name="Relationship_ProjCategoryRelationshipId">Relationship_ProjCategoryRelationshipId</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../ProfessionalServices/ProjectManagementAndAccounting/Group/ProjCategory.md" target="_blank">/core/erp/Tables/ProfessionalServices/ProjectManagementAndAccounting/Group/ProjCategory.cdm.json/ProjCategory</a></td><td><a href="../../../ProfessionalServices/ProjectManagementAndAccounting/Group/ProjCategory.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProjItemTransRelationshipId name="Relationship_ProjItemTransRelationshipId">Relationship_ProjItemTransRelationshipId</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../ProfessionalServices/ProjectManagementAndAccounting/Transaction/ProjItemTrans.md" target="_blank">/core/erp/Tables/ProfessionalServices/ProjectManagementAndAccounting/Transaction/ProjItemTrans.cdm.json/ProjItemTrans</a></td><td><a href="../../../ProfessionalServices/ProjectManagementAndAccounting/Transaction/ProjItemTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProjLinePropertyRelationshipId name="Relationship_ProjLinePropertyRelationshipId">Relationship_ProjLinePropertyRelationshipId</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../ProfessionalServices/ProjectManagementAndAccounting/Group/ProjLineProperty.md" target="_blank">/core/erp/Tables/ProfessionalServices/ProjectManagementAndAccounting/Group/ProjLineProperty.cdm.json/ProjLineProperty</a></td><td><a href="../../../ProfessionalServices/ProjectManagementAndAccounting/Group/ProjLineProperty.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProjTableRelationshipId name="Relationship_ProjTableRelationshipId">Relationship_ProjTableRelationshipId</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../ProfessionalServices/ProjectManagementAndAccounting/Main/ProjTable.md" target="_blank">/core/erp/Tables/ProfessionalServices/ProjectManagementAndAccounting/Main/ProjTable.cdm.json/ProjTable</a></td><td><a href="../../../ProfessionalServices/ProjectManagementAndAccounting/Main/ProjTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProjTaxGroupHeadingRelationshipId name="Relationship_ProjTaxGroupHeadingRelationshipId">Relationship_ProjTaxGroupHeadingRelationshipId</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProjTaxGroupHeadingRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Tax/Group/TaxGroupHeading.md" target="_blank">/core/erp/Tables/Finance/Tax/Group/TaxGroupHeading.cdm.json/TaxGroupHeading</a></td><td><a href="../../../Finance/Tax/Group/TaxGroupHeading.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProjTaxItemGroupHeadingRelationshipId name="Relationship_ProjTaxItemGroupHeadingRelationshipId">Relationship_ProjTaxItemGroupHeadingRelationshipId</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProjTaxItemGroupHeadingRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PurchaseAgreementRelationshipId name="Relationship_PurchaseAgreementRelationshipId">Relationship_PurchaseAgreementRelationshipId</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchaseAgreementRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="AgreementLine.md" target="_blank">/core/erp/Tables/SupplyChain/ProcurementAndSourcing/WorksheetLine/AgreementLine.cdm.json/AgreementLine</a></td><td><a href="AgreementLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PurchReqBusinessJustificationCodesRelationshipId name="Relationship_PurchReqBusinessJustificationCodesRelationshipId">Relationship_PurchReqBusinessJustificationCodesRelationshipId</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchReqBusinessJustificationCodesRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Reference/PurchReqBusinessJustificationCodes.md" target="_blank">/core/erp/Tables/SupplyChain/ProcurementAndSourcing/Reference/PurchReqBusinessJustificationCodes.cdm.json/PurchReqBusinessJustificationCodes</a></td><td><a href="../Reference/PurchReqBusinessJustificationCodes.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PurchReqTableRelationshipId name="Relationship_PurchReqTableRelationshipId">Relationship_PurchReqTableRelationshipId</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchReqTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/PurchReqTable.md" target="_blank">/core/erp/Tables/SupplyChain/ProcurementAndSourcing/WorksheetHeader/PurchReqTable.cdm.json/PurchReqTable</a></td><td><a href="../WorksheetHeader/PurchReqTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PurchRFQCaseTableRelationshipId name="Relationship_PurchRFQCaseTableRelationshipId">Relationship_PurchRFQCaseTableRelationshipId</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchRFQCaseTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/PurchRFQCaseTable.md" target="_blank">/core/erp/Tables/SupplyChain/ProcurementAndSourcing/WorksheetHeader/PurchRFQCaseTable.cdm.json/PurchRFQCaseTable</a></td><td><a href="../WorksheetHeader/PurchRFQCaseTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PurchTableRelationshipId name="Relationship_PurchTableRelationshipId">Relationship_PurchTableRelationshipId</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/PurchTable.md" target="_blank">/core/erp/Tables/SupplyChain/ProcurementAndSourcing/WorksheetHeader/PurchTable.cdm.json/PurchTable</a></td><td><a href="../WorksheetHeader/PurchTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ReasonRefRelationshipId name="Relationship_ReasonRefRelationshipId">Relationship_ReasonRefRelationshipId</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReasonRefRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Ledger/Transaction/ReasonTableRef.md" target="_blank">/core/erp/Tables/Finance/Ledger/Transaction/ReasonTableRef.cdm.json/ReasonTableRef</a></td><td><a href="../../../Finance/Ledger/Transaction/ReasonTableRef.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SalesPurchOperationType_BRRelationshipId name="Relationship_SalesPurchOperationType_BRRelationshipId">Relationship_SalesPurchOperationType_BRRelationshipId</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SalesPurchOperationType_BRRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/AccountsReceivable/Main/SalesPurchOperationType_BR.md" target="_blank">/core/erp/Tables/Finance/AccountsReceivable/Main/SalesPurchOperationType_BR.cdm.json/SalesPurchOperationType_BR</a></td><td><a href="../../../Finance/AccountsReceivable/Main/SalesPurchOperationType_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_smmActivitiesRelationshipId name="Relationship_smmActivitiesRelationshipId">Relationship_smmActivitiesRelationshipId</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_smmActivitiesRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../ProfessionalServices/ProjectManagementAndAccounting/Main/ProjActivity.md" target="_blank">/core/erp/Tables/ProfessionalServices/ProjectManagementAndAccounting/Main/ProjActivity.cdm.json/ProjActivity</a></td><td><a href="../../../ProfessionalServices/ProjectManagementAndAccounting/Main/ProjActivity.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SourceDocumentLineRelationshipId name="Relationship_SourceDocumentLineRelationshipId">Relationship_SourceDocumentLineRelationshipId</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/AccountingFoundation/TransactionLine/SourceDocumentLine.md" target="_blank">/core/erp/Tables/Finance/AccountingFoundation/TransactionLine/SourceDocumentLine.cdm.json/SourceDocumentLine</a></td><td><a href="../../../Finance/AccountingFoundation/TransactionLine/SourceDocumentLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxGroupHeadingRelationshipId name="Relationship_TaxGroupHeadingRelationshipId">Relationship_TaxGroupHeadingRelationshipId</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Tax/Group/TaxGroupHeading.md" target="_blank">/core/erp/Tables/Finance/Tax/Group/TaxGroupHeading.cdm.json/TaxGroupHeading</a></td><td><a href="../../../Finance/Tax/Group/TaxGroupHeading.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxItemGroupHeadingRelationshipId name="Relationship_TaxItemGroupHeadingRelationshipId">Relationship_TaxItemGroupHeadingRelationshipId</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Tax/Group/TaxItemGroupHeading.md" target="_blank">/core/erp/Tables/Finance/Tax/Group/TaxItemGroupHeading.cdm.json/TaxItemGroupHeading</a></td><td><a href="../../../Finance/Tax/Group/TaxItemGroupHeading.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxServiceCode_BRRelationshipId name="Relationship_TaxServiceCode_BRRelationshipId">Relationship_TaxServiceCode_BRRelationshipId</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

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

First included in: WorksheetLine/PurchReqLine (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Vendor/Main/VendTable.md" target="_blank">/core/erp/Tables/SupplyChain/Vendor/Main/VendTable.cdm.json/VendTable</a></td><td><a href="../../Vendor/Main/VendTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BudgetReservationLine_PSNRelationshipId name="Relationship_BudgetReservationLine_PSNRelationshipId">Relationship_BudgetReservationLine_PSNRelationshipId</a>

First included in: WorksheetLine/PurchReqLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BudgetReservationLine_PSNRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Budget/WorksheetLine/BudgetReservationLine_PSN.md" target="_blank">/core/erp/Tables/Finance/Budget/WorksheetLine/BudgetReservationLine_PSN.cdm.json/BudgetReservationLine_PSN</a></td><td><a href="../../../Finance/Budget/WorksheetLine/BudgetReservationLine_PSN.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
