---
title: SalesQuotationHeaderCDSEntity in SalesAndMarketing - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/15/2020
ms.author: nebanfic
---

# CDS sales quotation header in SalesAndMarketing(SalesQuotationHeaderCDSEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/SalesAndMarketing/SalesQuotationHeaderCDSEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>CDS sales quotation header</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ArePricesIncludingSalesTax](#ArePricesIncludingSalesTax)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[AreTotalsCalculated](#AreTotalsCalculated)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[CashDiscountCode](#CashDiscountCode)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[CashDiscountPercentage](#CashDiscountPercentage)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[ContactPersonId](#ContactPersonId)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[CurrencyCode](#CurrencyCode)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[CustomersReference](#CustomersReference)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[CustomerRequisitionNumber](#CustomerRequisitionNumber)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[DefaultShippingSiteId](#DefaultShippingSiteId)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[DefaultShippingWarehouseId](#DefaultShippingWarehouseId)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[DeliveryAddressCity](#DeliveryAddressCity)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[DeliveryAddressCountryRegionId](#DeliveryAddressCountryRegionId)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[DeliveryAddressCountryRegionISOCode](#DeliveryAddressCountryRegionISOCode)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[DeliveryAddressCountyId](#DeliveryAddressCountyId)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[DeliveryAddressDescription](#DeliveryAddressDescription)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[DeliveryAddressDistrictName](#DeliveryAddressDistrictName)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[DeliveryAddressDunsNumber](#DeliveryAddressDunsNumber)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[DeliveryAddressLatitude](#DeliveryAddressLatitude)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[DeliveryAddressLocationId](#DeliveryAddressLocationId)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[DeliveryAddressLongitude](#DeliveryAddressLongitude)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[DeliveryAddressName](#DeliveryAddressName)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[DeliveryAddressPostBox](#DeliveryAddressPostBox)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[DeliveryAddressStateId](#DeliveryAddressStateId)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[DeliveryAddressStreet](#DeliveryAddressStreet)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[DeliveryAddressStreetNumber](#DeliveryAddressStreetNumber)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[DeliveryAddressTimeZone](#DeliveryAddressTimeZone)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[DeliveryAddressZipCode](#DeliveryAddressZipCode)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[DeliveryBuildingCompliment](#DeliveryBuildingCompliment)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[DeliveryValidFrom](#DeliveryValidFrom)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[DeliveryValidTo](#DeliveryValidTo)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[DeliveryTermsCode](#DeliveryTermsCode)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[DeliveryPostalAddressRecId](#DeliveryPostalAddressRecId)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[DeliveryModeCode](#DeliveryModeCode)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[Email](#Email)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[FormattedDeliveryAddress](#FormattedDeliveryAddress)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[FormattedInvoiceAddress](#FormattedInvoiceAddress)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[GeneratedSalesOrderNumber](#GeneratedSalesOrderNumber)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[InvoiceAddressCity](#InvoiceAddressCity)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[InvoiceAddressCountryRegionId](#InvoiceAddressCountryRegionId)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[InvoiceAddressCountryRegionISOCode](#InvoiceAddressCountryRegionISOCode)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[InvoiceAddressCountyId](#InvoiceAddressCountyId)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[InvoiceAddressDistrictName](#InvoiceAddressDistrictName)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[InvoiceAddressLatitude](#InvoiceAddressLatitude)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[InvoiceAddressLongitude](#InvoiceAddressLongitude)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[InvoiceAddressPostBox](#InvoiceAddressPostBox)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[InvoiceAddressStateId](#InvoiceAddressStateId)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[InvoiceAddressTimeZone](#InvoiceAddressTimeZone)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[InvoiceAddressStreetNumber](#InvoiceAddressStreetNumber)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[InvoiceAddressStreet](#InvoiceAddressStreet)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[InvoiceAddressZipCode](#InvoiceAddressZipCode)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[InvoiceBuildingCompliment](#InvoiceBuildingCompliment)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[InvoiceCustomerAccountNumber](#InvoiceCustomerAccountNumber)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[InvoiceValidFrom](#InvoiceValidFrom)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[InvoiceValidTo](#InvoiceValidTo)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[IsDeliveryAddressOrderSpecific](#IsDeliveryAddressOrderSpecific)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[IsDeliveryAddressPrivate](#IsDeliveryAddressPrivate)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[IsInvoiceAddressPrivate](#IsInvoiceAddressPrivate)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[LanguageId](#LanguageId)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[OpportunityId](#OpportunityId)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[PaymentTermsName](#PaymentTermsName)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[PriceCustomerGroupCode](#PriceCustomerGroupCode)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[ProspectId](#ProspectId)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[QuotationResponsiblePersonnelNumber](#QuotationResponsiblePersonnelNumber)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[QuotationTakerPersonnelNumber](#QuotationTakerPersonnelNumber)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[QuotationTotalAmount](#QuotationTotalAmount)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[QuotationTotalChargesAmount](#QuotationTotalChargesAmount)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[QuotationTotalDiscountAmount](#QuotationTotalDiscountAmount)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[QuotationTotalTaxAmount](#QuotationTotalTaxAmount)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[QuotationHeaderTaxAmount](#QuotationHeaderTaxAmount)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[ReceiptDateRequested](#ReceiptDateRequested)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[RequestedShippingDate](#RequestedShippingDate)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[RequestingCustomerAccountNumber](#RequestingCustomerAccountNumber)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[SalesOrderOriginCode](#SalesOrderOriginCode)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[SalesOrderPromisingMethod](#SalesOrderPromisingMethod)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[SalesQuotationName](#SalesQuotationName)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[SalesQuotationNumber](#SalesQuotationNumber)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[SalesQuotationStatus](#SalesQuotationStatus)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[SalesQuotationExpiryDate](#SalesQuotationExpiryDate)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[SalesQuotationConfirmationDate](#SalesQuotationConfirmationDate)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[SalesQuotationFollowUpDate](#SalesQuotationFollowUpDate)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[TotalDiscountAmount](#TotalDiscountAmount)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[TotalDiscountPercentage](#TotalDiscountPercentage)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[URL](#URL)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[SalesQuotationCalculatedTotalsRecId](#SalesQuotationCalculatedTotalsRecId)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[Relationship_SalesOrderHeaderCDSRelationshipId](#Relationship_SalesOrderHeaderCDSRelationshipId)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[BackingTable_SalesQuotationHeaderV2EntityRelationshipId](#BackingTable_SalesQuotationHeaderV2EntityRelationshipId)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="SalesQuotationHeaderCDSEntity.md" target="_blank">SalesAndMarketing/SalesQuotationHeaderCDSEntity</a>|

### <a href=#ArePricesIncludingSalesTax name="ArePricesIncludingSalesTax">ArePricesIncludingSalesTax</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ArePricesIncludingSalesTax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreTotalsCalculated name="AreTotalsCalculated">AreTotalsCalculated</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreTotalsCalculated attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashDiscountCode name="CashDiscountCode">CashDiscountCode</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDiscountCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashDiscountPercentage name="CashDiscountPercentage">CashDiscountPercentage</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDiscountPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContactPersonId name="ContactPersonId">ContactPersonId</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContactPersonId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

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

### <a href=#CustomersReference name="CustomersReference">CustomersReference</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomersReference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerRequisitionNumber name="CustomerRequisitionNumber">CustomerRequisitionNumber</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerRequisitionNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultShippingSiteId name="DefaultShippingSiteId">DefaultShippingSiteId</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultShippingSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultShippingWarehouseId name="DefaultShippingWarehouseId">DefaultShippingWarehouseId</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultShippingWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryAddressCity name="DeliveryAddressCity">DeliveryAddressCity</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

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

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

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

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

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

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

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

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

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

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

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

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

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

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

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

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

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

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

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

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

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

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

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

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

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

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

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

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

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

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

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

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

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

### <a href=#DeliveryBuildingCompliment name="DeliveryBuildingCompliment">DeliveryBuildingCompliment</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryBuildingCompliment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryValidFrom name="DeliveryValidFrom">DeliveryValidFrom</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryValidTo name="DeliveryValidTo">DeliveryValidTo</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryTermsCode name="DeliveryTermsCode">DeliveryTermsCode</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryTermsCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryPostalAddressRecId name="DeliveryPostalAddressRecId">DeliveryPostalAddressRecId</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryPostalAddressRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryModeCode name="DeliveryModeCode">DeliveryModeCode</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryModeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Email name="Email">Email</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Email attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FormattedDeliveryAddress name="FormattedDeliveryAddress">FormattedDeliveryAddress</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

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

### <a href=#FormattedInvoiceAddress name="FormattedInvoiceAddress">FormattedInvoiceAddress</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormattedInvoiceAddress attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GeneratedSalesOrderNumber name="GeneratedSalesOrderNumber">GeneratedSalesOrderNumber</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GeneratedSalesOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddressCity name="InvoiceAddressCity">InvoiceAddressCity</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddressCity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddressCountryRegionId name="InvoiceAddressCountryRegionId">InvoiceAddressCountryRegionId</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddressCountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddressCountryRegionISOCode name="InvoiceAddressCountryRegionISOCode">InvoiceAddressCountryRegionISOCode</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddressCountryRegionISOCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddressCountyId name="InvoiceAddressCountyId">InvoiceAddressCountyId</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddressCountyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddressDistrictName name="InvoiceAddressDistrictName">InvoiceAddressDistrictName</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddressDistrictName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddressLatitude name="InvoiceAddressLatitude">InvoiceAddressLatitude</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddressLatitude attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddressLongitude name="InvoiceAddressLongitude">InvoiceAddressLongitude</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddressLongitude attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddressPostBox name="InvoiceAddressPostBox">InvoiceAddressPostBox</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddressPostBox attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddressStateId name="InvoiceAddressStateId">InvoiceAddressStateId</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddressStateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddressTimeZone name="InvoiceAddressTimeZone">InvoiceAddressTimeZone</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddressTimeZone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddressStreetNumber name="InvoiceAddressStreetNumber">InvoiceAddressStreetNumber</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddressStreetNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddressStreet name="InvoiceAddressStreet">InvoiceAddressStreet</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddressStreet attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddressZipCode name="InvoiceAddressZipCode">InvoiceAddressZipCode</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddressZipCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceBuildingCompliment name="InvoiceBuildingCompliment">InvoiceBuildingCompliment</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceBuildingCompliment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceCustomerAccountNumber name="InvoiceCustomerAccountNumber">InvoiceCustomerAccountNumber</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceCustomerAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceValidFrom name="InvoiceValidFrom">InvoiceValidFrom</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceValidTo name="InvoiceValidTo">InvoiceValidTo</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDeliveryAddressOrderSpecific name="IsDeliveryAddressOrderSpecific">IsDeliveryAddressOrderSpecific</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

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

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

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

### <a href=#IsInvoiceAddressPrivate name="IsInvoiceAddressPrivate">IsInvoiceAddressPrivate</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsInvoiceAddressPrivate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LanguageId name="LanguageId">LanguageId</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LanguageId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OpportunityId name="OpportunityId">OpportunityId</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OpportunityId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentTermsName name="PaymentTermsName">PaymentTermsName</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentTermsName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PriceCustomerGroupCode name="PriceCustomerGroupCode">PriceCustomerGroupCode</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceCustomerGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProspectId name="ProspectId">ProspectId</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProspectId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuotationResponsiblePersonnelNumber name="QuotationResponsiblePersonnelNumber">QuotationResponsiblePersonnelNumber</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuotationResponsiblePersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuotationTakerPersonnelNumber name="QuotationTakerPersonnelNumber">QuotationTakerPersonnelNumber</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuotationTakerPersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuotationTotalAmount name="QuotationTotalAmount">QuotationTotalAmount</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuotationTotalAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuotationTotalChargesAmount name="QuotationTotalChargesAmount">QuotationTotalChargesAmount</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuotationTotalChargesAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuotationTotalDiscountAmount name="QuotationTotalDiscountAmount">QuotationTotalDiscountAmount</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuotationTotalDiscountAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuotationTotalTaxAmount name="QuotationTotalTaxAmount">QuotationTotalTaxAmount</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuotationTotalTaxAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuotationHeaderTaxAmount name="QuotationHeaderTaxAmount">QuotationHeaderTaxAmount</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuotationHeaderTaxAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceiptDateRequested name="ReceiptDateRequested">ReceiptDateRequested</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceiptDateRequested attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequestedShippingDate name="RequestedShippingDate">RequestedShippingDate</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestedShippingDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequestingCustomerAccountNumber name="RequestingCustomerAccountNumber">RequestingCustomerAccountNumber</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestingCustomerAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesOrderOriginCode name="SalesOrderOriginCode">SalesOrderOriginCode</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesOrderOriginCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesOrderPromisingMethod name="SalesOrderPromisingMethod">SalesOrderPromisingMethod</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesOrderPromisingMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesQuotationName name="SalesQuotationName">SalesQuotationName</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesQuotationName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesQuotationNumber name="SalesQuotationNumber">SalesQuotationNumber</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesQuotationNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesQuotationStatus name="SalesQuotationStatus">SalesQuotationStatus</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesQuotationStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesQuotationExpiryDate name="SalesQuotationExpiryDate">SalesQuotationExpiryDate</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesQuotationExpiryDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesQuotationConfirmationDate name="SalesQuotationConfirmationDate">SalesQuotationConfirmationDate</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesQuotationConfirmationDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesQuotationFollowUpDate name="SalesQuotationFollowUpDate">SalesQuotationFollowUpDate</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesQuotationFollowUpDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalDiscountAmount name="TotalDiscountAmount">TotalDiscountAmount</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalDiscountAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalDiscountPercentage name="TotalDiscountPercentage">TotalDiscountPercentage</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalDiscountPercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#URL name="URL">URL</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

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

### <a href=#SalesQuotationCalculatedTotalsRecId name="SalesQuotationCalculatedTotalsRecId">SalesQuotationCalculatedTotalsRecId</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesQuotationCalculatedTotalsRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SalesOrderHeaderCDSRelationshipId name="Relationship_SalesOrderHeaderCDSRelationshipId">Relationship_SalesOrderHeaderCDSRelationshipId</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SalesOrderHeaderCDSRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_SalesQuotationHeaderV2EntityRelationshipId name="BackingTable_SalesQuotationHeaderV2EntityRelationshipId">BackingTable_SalesQuotationHeaderV2EntityRelationshipId</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_SalesQuotationHeaderV2EntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: SalesAndMarketing/SalesQuotationHeaderCDSEntity (this entity)  

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
