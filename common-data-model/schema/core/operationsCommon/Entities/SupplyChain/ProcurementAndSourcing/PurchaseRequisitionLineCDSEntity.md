---
title: PurchaseRequisitionLineCDSEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 6/30/2020
ms.author: nebanfic
---

# CDS purchase requisition lines

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>CDS purchase requisition lines</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ProductNumber](#ProductNumber)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[AccountingDate](#AccountingDate)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[AccountingDistributionTemplateName](#AccountingDistributionTemplateName)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[BudgetReservationDocumentNumber](#BudgetReservationDocumentNumber)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[BudgetReservationLineNumber](#BudgetReservationLineNumber)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[BusinessJustificationCode](#BusinessJustificationCode)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[BusinessJustificationDetails](#BusinessJustificationDetails)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[BuyingLegalEntityId](#BuyingLegalEntityId)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[CurrencyCode](#CurrencyCode)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[DefaultLedgerDimensionDisplayValue](#DefaultLedgerDimensionDisplayValue)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[DeliveryAddressBuildingCompliment](#DeliveryAddressBuildingCompliment)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[DeliveryAddressCity](#DeliveryAddressCity)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[DeliveryAddressCountryRegionId](#DeliveryAddressCountryRegionId)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[DeliveryAddressCountryRegionISOCode](#DeliveryAddressCountryRegionISOCode)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[DeliveryAddressCountyId](#DeliveryAddressCountyId)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[DeliveryAddressDescription](#DeliveryAddressDescription)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[DeliveryAddressDistrictName](#DeliveryAddressDistrictName)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[DeliveryAddressDunsNumber](#DeliveryAddressDunsNumber)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[DeliveryAddressLatitude](#DeliveryAddressLatitude)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[DeliveryAddressLocationId](#DeliveryAddressLocationId)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[DeliveryAddressLongitude](#DeliveryAddressLongitude)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[DeliveryAddressName](#DeliveryAddressName)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[DeliveryAddressPostBox](#DeliveryAddressPostBox)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[DeliveryAddressStateId](#DeliveryAddressStateId)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[DeliveryAddressStreet](#DeliveryAddressStreet)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[DeliveryAddressStreetNumber](#DeliveryAddressStreetNumber)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[DeliveryAddressTimeZone](#DeliveryAddressTimeZone)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[DeliveryAddressZipCode](#DeliveryAddressZipCode)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[DeliveryAttentionInformation](#DeliveryAttentionInformation)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[DeliveryCityInKana](#DeliveryCityInKana)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[DeliveryStreetInKana](#DeliveryStreetInKana)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[ExternalItemNumber](#ExternalItemNumber)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[FixedAssetGroupId](#FixedAssetGroupId)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[FixedAssetReasonCode](#FixedAssetReasonCode)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[FixedAssetRuleQualifierOptionName](#FixedAssetRuleQualifierOptionName)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[FixedPriceCharges](#FixedPriceCharges)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[FormattedDeliveryAddress](#FormattedDeliveryAddress)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[IsDeliveryAddressOrderSpecific](#IsDeliveryAddressOrderSpecific)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[IsDeliveryAddressPrivate](#IsDeliveryAddressPrivate)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[IsPartialDeliveryPrevented](#IsPartialDeliveryPrevented)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[IsPrepaymentRequired](#IsPrepaymentRequired)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[ItemBatchNumber](#ItemBatchNumber)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[ItemNumber](#ItemNumber)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[LineAmount](#LineAmount)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[LineDescription](#LineDescription)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[LineDiscountAmount](#LineDiscountAmount)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[LineDiscountPercentage](#LineDiscountPercentage)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[LineStatus](#LineStatus)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[LineType](#LineType)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[PrePaymentDetails](#PrePaymentDetails)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[ProcurementProductCategoryName](#ProcurementProductCategoryName)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[ProductColorId](#ProductColorId)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[ProductConfigurationId](#ProductConfigurationId)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[ProductName](#ProductName)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[ProductSizeId](#ProductSizeId)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[ProductStyleId](#ProductStyleId)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[ProductVersionId](#ProductVersionId)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[ProjectActivityNumber](#ProjectActivityNumber)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[ProjectCategoryId](#ProjectCategoryId)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[ProjectId](#ProjectId)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[ProjectLinePropertyId](#ProjectLinePropertyId)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[ProjectSalesCurrencyCode](#ProjectSalesCurrencyCode)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[ProjectSalesPrice](#ProjectSalesPrice)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[ProjectSalesUnitSymbol](#ProjectSalesUnitSymbol)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[ProjectTaxGroupCode](#ProjectTaxGroupCode)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[ProjectTaxItemGroupCode](#ProjectTaxItemGroupCode)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[PurchasePrice](#PurchasePrice)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[PurchasePriceQuantity](#PurchasePriceQuantity)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[PurchaseUnitSymbol](#PurchaseUnitSymbol)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[ReceivingSiteId](#ReceivingSiteId)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[ReceivingWarehouseId](#ReceivingWarehouseId)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[RequestedDate](#RequestedDate)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[RequestedPurchaseQuantity](#RequestedPurchaseQuantity)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[RequisitionerPersonnelNumber](#RequisitionerPersonnelNumber)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[RequisitionLineNumber](#RequisitionLineNumber)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[RequisitionNumber](#RequisitionNumber)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[RFQRequirementLevel](#RFQRequirementLevel)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[SalesTaxGroupCode](#SalesTaxGroupCode)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[SalesTaxItemGroupCode](#SalesTaxItemGroupCode)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[URL](#URL)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[VendorAccountNumber](#VendorAccountNumber)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[ProcurementProductCategoryHierarchyName](#ProcurementProductCategoryHierarchyName)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[ReceivingOperatingUnitPartyNumber](#ReceivingOperatingUnitPartyNumber)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|
|[BackingTable_PurchaseRequisitionLineEntityRelationshipId](#BackingTable_PurchaseRequisitionLineEntityRelationshipId)||<a href="PurchaseRequisitionLineCDSEntity.md" target="_blank">ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity</a>|

### <a href=#ProductNumber name="ProductNumber">ProductNumber</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountingDate name="AccountingDate">AccountingDate</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountingDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountingDistributionTemplateName name="AccountingDistributionTemplateName">AccountingDistributionTemplateName</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountingDistributionTemplateName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BudgetReservationDocumentNumber name="BudgetReservationDocumentNumber">BudgetReservationDocumentNumber</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetReservationDocumentNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BudgetReservationLineNumber name="BudgetReservationLineNumber">BudgetReservationLineNumber</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetReservationLineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BusinessJustificationCode name="BusinessJustificationCode">BusinessJustificationCode</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BusinessJustificationCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BusinessJustificationDetails name="BusinessJustificationDetails">BusinessJustificationDetails</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BusinessJustificationDetails attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BuyingLegalEntityId name="BuyingLegalEntityId">BuyingLegalEntityId</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BuyingLegalEntityId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultLedgerDimensionDisplayValue name="DefaultLedgerDimensionDisplayValue">DefaultLedgerDimensionDisplayValue</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressBuildingCompliment name="DeliveryAddressBuildingCompliment">DeliveryAddressBuildingCompliment</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressBuildingCompliment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressCity name="DeliveryAddressCity">DeliveryAddressCity</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressCity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressCountryRegionId name="DeliveryAddressCountryRegionId">DeliveryAddressCountryRegionId</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressCountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressCountryRegionISOCode name="DeliveryAddressCountryRegionISOCode">DeliveryAddressCountryRegionISOCode</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressCountryRegionISOCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressCountyId name="DeliveryAddressCountyId">DeliveryAddressCountyId</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressCountyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressDescription name="DeliveryAddressDescription">DeliveryAddressDescription</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressDistrictName name="DeliveryAddressDistrictName">DeliveryAddressDistrictName</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressDistrictName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressDunsNumber name="DeliveryAddressDunsNumber">DeliveryAddressDunsNumber</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressDunsNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressLatitude name="DeliveryAddressLatitude">DeliveryAddressLatitude</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressLatitude attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressLocationId name="DeliveryAddressLocationId">DeliveryAddressLocationId</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressLongitude name="DeliveryAddressLongitude">DeliveryAddressLongitude</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressLongitude attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressName name="DeliveryAddressName">DeliveryAddressName</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressPostBox name="DeliveryAddressPostBox">DeliveryAddressPostBox</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressPostBox attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressStateId name="DeliveryAddressStateId">DeliveryAddressStateId</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressStateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressStreet name="DeliveryAddressStreet">DeliveryAddressStreet</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressStreet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressStreetNumber name="DeliveryAddressStreetNumber">DeliveryAddressStreetNumber</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressStreetNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressTimeZone name="DeliveryAddressTimeZone">DeliveryAddressTimeZone</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressTimeZone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressZipCode name="DeliveryAddressZipCode">DeliveryAddressZipCode</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAddressZipCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAttentionInformation name="DeliveryAttentionInformation">DeliveryAttentionInformation</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryAttentionInformation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryCityInKana name="DeliveryCityInKana">DeliveryCityInKana</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryCityInKana attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryStreetInKana name="DeliveryStreetInKana">DeliveryStreetInKana</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryStreetInKana attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExternalItemNumber name="ExternalItemNumber">ExternalItemNumber</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>External item number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExternalItemNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>External item number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FixedAssetGroupId name="FixedAssetGroupId">FixedAssetGroupId</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedAssetGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FixedAssetReasonCode name="FixedAssetReasonCode">FixedAssetReasonCode</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedAssetReasonCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FixedAssetRuleQualifierOptionName name="FixedAssetRuleQualifierOptionName">FixedAssetRuleQualifierOptionName</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedAssetRuleQualifierOptionName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FixedPriceCharges name="FixedPriceCharges">FixedPriceCharges</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedPriceCharges attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FormattedDeliveryAddress name="FormattedDeliveryAddress">FormattedDeliveryAddress</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormattedDeliveryAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDeliveryAddressOrderSpecific name="IsDeliveryAddressOrderSpecific">IsDeliveryAddressOrderSpecific</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDeliveryAddressOrderSpecific attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDeliveryAddressPrivate name="IsDeliveryAddressPrivate">IsDeliveryAddressPrivate</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDeliveryAddressPrivate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPartialDeliveryPrevented name="IsPartialDeliveryPrevented">IsPartialDeliveryPrevented</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPartialDeliveryPrevented attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPrepaymentRequired name="IsPrepaymentRequired">IsPrepaymentRequired</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPrepaymentRequired attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemBatchNumber name="ItemBatchNumber">ItemBatchNumber</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemBatchNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemNumber name="ItemNumber">ItemNumber</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineAmount name="LineAmount">LineAmount</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineDescription name="LineDescription">LineDescription</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineDiscountAmount name="LineDiscountAmount">LineDiscountAmount</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineDiscountAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineDiscountPercentage name="LineDiscountPercentage">LineDiscountPercentage</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineDiscountPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineStatus name="LineStatus">LineStatus</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineType name="LineType">LineType</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrePaymentDetails name="PrePaymentDetails">PrePaymentDetails</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrePaymentDetails attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProcurementProductCategoryName name="ProcurementProductCategoryName">ProcurementProductCategoryName</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcurementProductCategoryName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductColorId name="ProductColorId">ProductColorId</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductColorId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductConfigurationId name="ProductConfigurationId">ProductConfigurationId</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductConfigurationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductName name="ProductName">ProductName</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductSizeId name="ProductSizeId">ProductSizeId</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductSizeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductStyleId name="ProductStyleId">ProductStyleId</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductStyleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductVersionId name="ProductVersionId">ProductVersionId</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductVersionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectActivityNumber name="ProjectActivityNumber">ProjectActivityNumber</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectActivityNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectCategoryId name="ProjectCategoryId">ProjectCategoryId</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectCategoryId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectId name="ProjectId">ProjectId</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectLinePropertyId name="ProjectLinePropertyId">ProjectLinePropertyId</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectLinePropertyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectSalesCurrencyCode name="ProjectSalesCurrencyCode">ProjectSalesCurrencyCode</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectSalesCurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectSalesPrice name="ProjectSalesPrice">ProjectSalesPrice</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectSalesPrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectSalesUnitSymbol name="ProjectSalesUnitSymbol">ProjectSalesUnitSymbol</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectSalesUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectTaxGroupCode name="ProjectTaxGroupCode">ProjectTaxGroupCode</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectTaxGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectTaxItemGroupCode name="ProjectTaxItemGroupCode">ProjectTaxItemGroupCode</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectTaxItemGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchasePrice name="PurchasePrice">PurchasePrice</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

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

### <a href=#PurchasePriceQuantity name="PurchasePriceQuantity">PurchasePriceQuantity</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchasePriceQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseUnitSymbol name="PurchaseUnitSymbol">PurchaseUnitSymbol</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseUnitSymbol attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceivingSiteId name="ReceivingSiteId">ReceivingSiteId</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivingSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceivingWarehouseId name="ReceivingWarehouseId">ReceivingWarehouseId</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivingWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequestedDate name="RequestedDate">RequestedDate</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestedDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequestedPurchaseQuantity name="RequestedPurchaseQuantity">RequestedPurchaseQuantity</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestedPurchaseQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequisitionerPersonnelNumber name="RequisitionerPersonnelNumber">RequisitionerPersonnelNumber</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequisitionerPersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequisitionLineNumber name="RequisitionLineNumber">RequisitionLineNumber</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequisitionLineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequisitionNumber name="RequisitionNumber">RequisitionNumber</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequisitionNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RFQRequirementLevel name="RFQRequirementLevel">RFQRequirementLevel</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQRequirementLevel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxGroupCode name="SalesTaxGroupCode">SalesTaxGroupCode</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxItemGroupCode name="SalesTaxItemGroupCode">SalesTaxItemGroupCode</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxItemGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#URL name="URL">URL</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the URL attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorAccountNumber name="VendorAccountNumber">VendorAccountNumber</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProcurementProductCategoryHierarchyName name="ProcurementProductCategoryHierarchyName">ProcurementProductCategoryHierarchyName</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcurementProductCategoryHierarchyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceivingOperatingUnitPartyNumber name="ReceivingOperatingUnitPartyNumber">ReceivingOperatingUnitPartyNumber</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceivingOperatingUnitPartyNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_PurchaseRequisitionLineEntityRelationshipId name="BackingTable_PurchaseRequisitionLineEntityRelationshipId">BackingTable_PurchaseRequisitionLineEntityRelationshipId</a>

First included in: ProcurementAndSourcing/PurchaseRequisitionLineCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PurchaseRequisitionLineEntityRelationshipId attribute are listed below.</summary>

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
