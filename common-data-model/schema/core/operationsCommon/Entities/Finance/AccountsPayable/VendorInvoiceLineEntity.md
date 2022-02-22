---
title: VendorInvoiceLineEntity in AccountsPayable - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Vendor invoice line in AccountsPayable(VendorInvoiceLineEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/AccountsPayable/VendorInvoiceLineEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Vendor invoice line</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[VendorAccount](#VendorAccount)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[TemplateId](#TemplateId)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[AdvanceApplicationReference](#AdvanceApplicationReference)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[ChangeQuantityManually](#ChangeQuantityManually)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[CloseForReceipt](#CloseForReceipt)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[CountyOrigDest](#CountyOrigDest)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[Currency](#Currency)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[Dimension](#Dimension)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[DeliveryName](#DeliveryName)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[LineDescription](#LineDescription)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[DimensionNumber](#DimensionNumber)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[InventNow](#InventNow)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[InvoiceAccount](#InvoiceAccount)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[ItemNumber](#ItemNumber)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[NetAmount](#NetAmount)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[Discount](#Discount)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[LineNumber](#LineNumber)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[DiscountPercent](#DiscountPercent)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[LineType](#LineType)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[MultilineDiscount](#MultilineDiscount)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[MultilineDiscountPercentage](#MultilineDiscountPercentage)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[Ordering](#Ordering)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[PackedExtensions](#PackedExtensions)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[MainAccount](#MainAccount)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[AdjustedUnitPrice](#AdjustedUnitPrice)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[PDSCalculationId](#PDSCalculationId)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[CWUpdate](#CWUpdate)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[CWDeliveryRemainder](#CWDeliveryRemainder)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[CWRemainingQuantity](#CWRemainingQuantity)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[Port](#Port)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[PriceUnit](#PriceUnit)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[ProcurementCategory](#ProcurementCategory)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[ReleaseAllRetainedAmount](#ReleaseAllRetainedAmount)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[Amount](#Amount)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[Percentage](#Percentage)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[RetainageAmount](#RetainageAmount)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[TotalRetainedAmount](#TotalRetainedAmount)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[RetainPercentage](#RetainPercentage)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[ChargesOnPurchases](#ChargesOnPurchases)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[UnitPrice](#UnitPrice)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[Unit](#Unit)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[ReasonTableReference](#ReasonTableReference)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[ReceiveNow](#ReceiveNow)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[RemainAfter](#RemainAfter)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[RemainAfterInvent](#RemainAfterInvent)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[RemainBefore](#RemainBefore)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[RemainBeforeInvent](#RemainBeforeInvent)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[OriginalDeliverRemainder](#OriginalDeliverRemainder)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[VendorInvoiceLineReviewStatus](#VendorInvoiceLineReviewStatus)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[SourceDocumentLine](#SourceDocumentLine)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[StatisticsProcedure](#StatisticsProcedure)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[PurchaseOrder](#PurchaseOrder)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[Tax1099Amount](#Tax1099Amount)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[Tax1099BoxDetailReference](#Tax1099BoxDetailReference)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[Tax1099Fields](#Tax1099Fields)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[DeliveryState](#DeliveryState)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[Tax1099StateAmount](#Tax1099StateAmount)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[SalesTaxGroup](#SalesTaxGroup)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[ItemSalesTax](#ItemSalesTax)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[WithholdingTaxGroup](#WithholdingTaxGroup)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[TransactionCode](#TransactionCode)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[Transport](#Transport)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[Commodity](#Commodity)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[OrigCountryRegionId](#OrigCountryRegionId)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[StateOfOrigin](#StateOfOrigin)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[AccountingDistributionTemplateId](#AccountingDistributionTemplateId)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[LegalEntity](#LegalEntity)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[PartyID](#PartyID)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[DataAreaCompany](#DataAreaCompany)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[ProcurementCategoryHierarchy](#ProcurementCategoryHierarchy)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[ProcurementCategoryName](#ProcurementCategoryName)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[ProcurementCategoryHierarchyName](#ProcurementCategoryHierarchyName)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[Tax1099Box](#Tax1099Box)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[Tax1099Type](#Tax1099Type)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[DimensionDisplayValue](#DimensionDisplayValue)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[MainAccountDisplayValue](#MainAccountDisplayValue)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[HeaderReference](#HeaderReference)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[PurchLineNumber](#PurchLineNumber)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[CFOPCodeRecId](#CFOPCodeRecId)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[TaxServiceCode](#TaxServiceCode)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[TaxWithholdGroup](#TaxWithholdGroup)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[TaxWithholdItemGroup](#TaxWithholdItemGroup)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[CFOPCode](#CFOPCode)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[TaxWithholdItemGroupName](#TaxWithholdItemGroupName)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[DiotOperationType](#DiotOperationType)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[ItemName](#ItemName)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[InvoiceLineNumber](#InvoiceLineNumber)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[InventorySiteId](#InventorySiteId)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[InventoryWarehouseId](#InventoryWarehouseId)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[ProductSizeId](#ProductSizeId)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[ProductColorId](#ProductColorId)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[ProductConfigurationId](#ProductConfigurationId)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[ProductStyleId](#ProductStyleId)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[ProductVersionId](#ProductVersionId)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[ItemBatchNumber](#ItemBatchNumber)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[OrderedInventoryStatusId](#OrderedInventoryStatusId)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[BudgetReservationLineRecId](#BudgetReservationLineRecId)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[BudgetReservationLineNumber](#BudgetReservationLineNumber)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[BudgetReservationDocumentNumber](#BudgetReservationDocumentNumber)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[InvoiceTransactionDate](#InvoiceTransactionDate)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[ProductFlavor](#ProductFlavor)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[Relationship_DimensionDimensionSetRelationshipId](#Relationship_DimensionDimensionSetRelationshipId)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[Relationship_MainAccountCombinationRelationshipId](#Relationship_MainAccountCombinationRelationshipId)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[Relationship_VendorInvoiceHeaderEntityRelationshipId](#Relationship_VendorInvoiceHeaderEntityRelationshipId)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[BackingTable_VendInvoiceInfoLineRelationshipId](#BackingTable_VendInvoiceInfoLineRelationshipId)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="VendorInvoiceLineEntity.md" target="_blank">AccountsPayable/VendorInvoiceLineEntity</a>|

### <a href=#VendorAccount name="VendorAccount">VendorAccount</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TemplateId name="TemplateId">TemplateId</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TemplateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AdvanceApplicationReference name="AdvanceApplicationReference">AdvanceApplicationReference</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AdvanceApplicationReference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChangeQuantityManually name="ChangeQuantityManually">ChangeQuantityManually</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChangeQuantityManually attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CloseForReceipt name="CloseForReceipt">CloseForReceipt</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CloseForReceipt attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CountyOrigDest name="CountyOrigDest">CountyOrigDest</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CountyOrigDest attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Currency name="Currency">Currency</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Currency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Dimension name="Dimension">Dimension</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Dimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryName name="DeliveryName">DeliveryName</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineDescription name="LineDescription">LineDescription</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

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

### <a href=#DimensionNumber name="DimensionNumber">DimensionNumber</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventNow name="InventNow">InventNow</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventNow attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAccount name="InvoiceAccount">InvoiceAccount</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemNumber name="ItemNumber">ItemNumber</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

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

### <a href=#NetAmount name="NetAmount">NetAmount</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NetAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Discount name="Discount">Discount</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Discount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscountPercent name="DiscountPercent">DiscountPercent</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountPercent attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineType name="LineType">LineType</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

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

### <a href=#MultilineDiscount name="MultilineDiscount">MultilineDiscount</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MultilineDiscount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MultilineDiscountPercentage name="MultilineDiscountPercentage">MultilineDiscountPercentage</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MultilineDiscountPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Ordering name="Ordering">Ordering</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Ordering attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PackedExtensions name="PackedExtensions">PackedExtensions</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackedExtensions attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MainAccount name="MainAccount">MainAccount</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AdjustedUnitPrice name="AdjustedUnitPrice">AdjustedUnitPrice</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AdjustedUnitPrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PDSCalculationId name="PDSCalculationId">PDSCalculationId</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PDSCalculationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CWUpdate name="CWUpdate">CWUpdate</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CWUpdate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CWDeliveryRemainder name="CWDeliveryRemainder">CWDeliveryRemainder</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CWDeliveryRemainder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CWRemainingQuantity name="CWRemainingQuantity">CWRemainingQuantity</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CWRemainingQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Port name="Port">Port</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Port attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PriceUnit name="PriceUnit">PriceUnit</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProcurementCategory name="ProcurementCategory">ProcurementCategory</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcurementCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReleaseAllRetainedAmount name="ReleaseAllRetainedAmount">ReleaseAllRetainedAmount</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReleaseAllRetainedAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Amount name="Amount">Amount</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Amount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Percentage name="Percentage">Percentage</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Percentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetainageAmount name="RetainageAmount">RetainageAmount</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetainageAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalRetainedAmount name="TotalRetainedAmount">TotalRetainedAmount</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalRetainedAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetainPercentage name="RetainPercentage">RetainPercentage</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetainPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChargesOnPurchases name="ChargesOnPurchases">ChargesOnPurchases</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargesOnPurchases attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UnitPrice name="UnitPrice">UnitPrice</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitPrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Unit name="Unit">Unit</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Unit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReasonTableReference name="ReasonTableReference">ReasonTableReference</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReasonTableReference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceiveNow name="ReceiveNow">ReceiveNow</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quantity</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceiveNow attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Quantity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RemainAfter name="RemainAfter">RemainAfter</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemainAfter attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RemainAfterInvent name="RemainAfterInvent">RemainAfterInvent</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemainAfterInvent attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RemainBefore name="RemainBefore">RemainBefore</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemainBefore attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RemainBeforeInvent name="RemainBeforeInvent">RemainBeforeInvent</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RemainBeforeInvent attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OriginalDeliverRemainder name="OriginalDeliverRemainder">OriginalDeliverRemainder</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginalDeliverRemainder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorInvoiceLineReviewStatus name="VendorInvoiceLineReviewStatus">VendorInvoiceLineReviewStatus</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorInvoiceLineReviewStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SourceDocumentLine name="SourceDocumentLine">SourceDocumentLine</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SourceDocumentLine attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StatisticsProcedure name="StatisticsProcedure">StatisticsProcedure</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StatisticsProcedure attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchaseOrder name="PurchaseOrder">PurchaseOrder</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseOrder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Tax1099Amount name="Tax1099Amount">Tax1099Amount</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Tax1099Amount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Tax1099BoxDetailReference name="Tax1099BoxDetailReference">Tax1099BoxDetailReference</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Tax1099BoxDetailReference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Tax1099Fields name="Tax1099Fields">Tax1099Fields</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Tax1099Fields attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryState name="DeliveryState">DeliveryState</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryState attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Tax1099StateAmount name="Tax1099StateAmount">Tax1099StateAmount</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Tax1099StateAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTaxGroup name="SalesTaxGroup">SalesTaxGroup</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTaxGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemSalesTax name="ItemSalesTax">ItemSalesTax</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemSalesTax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WithholdingTaxGroup name="WithholdingTaxGroup">WithholdingTaxGroup</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WithholdingTaxGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionCode name="TransactionCode">TransactionCode</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Transport name="Transport">Transport</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Transport attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Commodity name="Commodity">Commodity</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Commodity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrigCountryRegionId name="OrigCountryRegionId">OrigCountryRegionId</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrigCountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StateOfOrigin name="StateOfOrigin">StateOfOrigin</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StateOfOrigin attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountingDistributionTemplateId name="AccountingDistributionTemplateId">AccountingDistributionTemplateId</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountingDistributionTemplateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LegalEntity name="LegalEntity">LegalEntity</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LegalEntity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PartyID name="PartyID">PartyID</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PartyID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaCompany name="DataAreaCompany">DataAreaCompany</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataAreaCompany attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProcurementCategoryHierarchy name="ProcurementCategoryHierarchy">ProcurementCategoryHierarchy</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcurementCategoryHierarchy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProcurementCategoryName name="ProcurementCategoryName">ProcurementCategoryName</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Procurement category</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcurementCategoryName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Procurement category</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProcurementCategoryHierarchyName name="ProcurementCategoryHierarchyName">ProcurementCategoryHierarchyName</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcurementCategoryHierarchyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Tax1099Box name="Tax1099Box">Tax1099Box</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Tax1099Box attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Tax1099Type name="Tax1099Type">Tax1099Type</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Tax1099Type attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DimensionDisplayValue name="DimensionDisplayValue">DimensionDisplayValue</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MainAccountDisplayValue name="MainAccountDisplayValue">MainAccountDisplayValue</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainAccountDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HeaderReference name="HeaderReference">HeaderReference</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Invoice header</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HeaderReference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Invoice header</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchLineNumber name="PurchLineNumber">PurchLineNumber</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchLineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CFOPCodeRecId name="CFOPCodeRecId">CFOPCodeRecId</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFOPCodeRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxServiceCode name="TaxServiceCode">TaxServiceCode</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxServiceCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxWithholdGroup name="TaxWithholdGroup">TaxWithholdGroup</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxWithholdItemGroup name="TaxWithholdItemGroup">TaxWithholdItemGroup</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdItemGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CFOPCode name="CFOPCode">CFOPCode</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CFOPCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxWithholdItemGroupName name="TaxWithholdItemGroupName">TaxWithholdItemGroupName</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdItemGroupName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiotOperationType name="DiotOperationType">DiotOperationType</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiotOperationType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemName name="ItemName">ItemName</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Item name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Item name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceLineNumber name="InvoiceLineNumber">InvoiceLineNumber</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceLineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventorySiteId name="InventorySiteId">InventorySiteId</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventorySiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventoryWarehouseId name="InventoryWarehouseId">InventoryWarehouseId</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventoryWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductSizeId name="ProductSizeId">ProductSizeId</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

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

### <a href=#ProductColorId name="ProductColorId">ProductColorId</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

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

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

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

### <a href=#ProductStyleId name="ProductStyleId">ProductStyleId</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

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

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

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

### <a href=#ItemBatchNumber name="ItemBatchNumber">ItemBatchNumber</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

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

### <a href=#OrderedInventoryStatusId name="OrderedInventoryStatusId">OrderedInventoryStatusId</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderedInventoryStatusId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BudgetReservationLineRecId name="BudgetReservationLineRecId">BudgetReservationLineRecId</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetReservationLineRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BudgetReservationLineNumber name="BudgetReservationLineNumber">BudgetReservationLineNumber</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

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

### <a href=#BudgetReservationDocumentNumber name="BudgetReservationDocumentNumber">BudgetReservationDocumentNumber</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

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

### <a href=#InvoiceTransactionDate name="InvoiceTransactionDate">InvoiceTransactionDate</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceTransactionDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductFlavor name="ProductFlavor">ProductFlavor</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductFlavor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DimensionDimensionSetRelationshipId name="Relationship_DimensionDimensionSetRelationshipId">Relationship_DimensionDimensionSetRelationshipId</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DimensionDimensionSetRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_MainAccountCombinationRelationshipId name="Relationship_MainAccountCombinationRelationshipId">Relationship_MainAccountCombinationRelationshipId</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MainAccountCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_VendorInvoiceHeaderEntityRelationshipId name="Relationship_VendorInvoiceHeaderEntityRelationshipId">Relationship_VendorInvoiceHeaderEntityRelationshipId</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendorInvoiceHeaderEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_VendInvoiceInfoLineRelationshipId name="BackingTable_VendInvoiceInfoLineRelationshipId">BackingTable_VendInvoiceInfoLineRelationshipId</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_VendInvoiceInfoLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/AccountsPayable/TransactionLine/VendInvoiceInfoLine.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsPayable/TransactionLine/VendInvoiceInfoLine.cdm.json/VendInvoiceInfoLine</a></td><td><a href="../../../Tables/Finance/AccountsPayable/TransactionLine/VendInvoiceInfoLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: AccountsPayable/VendorInvoiceLineEntity (this entity)  

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
