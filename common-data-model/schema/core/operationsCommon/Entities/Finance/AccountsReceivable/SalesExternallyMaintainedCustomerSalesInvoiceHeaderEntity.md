---
title: SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity in AccountsReceivable - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Externally maintained customer sales invoice headers in AccountsReceivable(SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Externally maintained customer sales invoice headers</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ContactPersonId](#ContactPersonId)||<a href="SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity</a>|
|[CurrencyCode](#CurrencyCode)||<a href="SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity</a>|
|[CustomersOrderReference](#CustomersOrderReference)||<a href="SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity</a>|
|[DeliveryModeCode](#DeliveryModeCode)||<a href="SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity</a>|
|[DeliveryTermsCode](#DeliveryTermsCode)||<a href="SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity</a>|
|[InvoiceAddressCity](#InvoiceAddressCity)||<a href="SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity</a>|
|[InvoiceAddressCountryRegionId](#InvoiceAddressCountryRegionId)||<a href="SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity</a>|
|[InvoiceAddressCountryRegionISOCode](#InvoiceAddressCountryRegionISOCode)||<a href="SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity</a>|
|[InvoiceAddressState](#InvoiceAddressState)||<a href="SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity</a>|
|[InvoiceAddressStreet](#InvoiceAddressStreet)||<a href="SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity</a>|
|[InvoiceAddressStreetNumber](#InvoiceAddressStreetNumber)||<a href="SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity</a>|
|[InvoiceAddressZipCode](#InvoiceAddressZipCode)||<a href="SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity</a>|
|[InvoiceCustomerAccountNumber](#InvoiceCustomerAccountNumber)||<a href="SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity</a>|
|[InvoiceDate](#InvoiceDate)||<a href="SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity</a>|
|[InvoiceNumber](#InvoiceNumber)||<a href="SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity</a>|
|[PaymentTermsName](#PaymentTermsName)||<a href="SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity</a>|
|[SalesOrderNumber](#SalesOrderNumber)||<a href="SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity</a>|
|[SalesOrderResponsiblePersonnelNumber](#SalesOrderResponsiblePersonnelNumber)||<a href="SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity</a>|
|[TotalChargeAmount](#TotalChargeAmount)||<a href="SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity</a>|
|[TotalDiscountAmount](#TotalDiscountAmount)||<a href="SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity</a>|
|[TotalDiscountCustomerGroupCode](#TotalDiscountCustomerGroupCode)||<a href="SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity</a>|
|[TotalInvoiceAmount](#TotalInvoiceAmount)||<a href="SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity</a>|
|[TotalTaxAmount](#TotalTaxAmount)||<a href="SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity</a>|
|[InvoiceHeaderTaxAmount](#InvoiceHeaderTaxAmount)||<a href="SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity</a>|
|[SalesOrderOriginType](#SalesOrderOriginType)||<a href="SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity</a>|
|[LedgerVoucher](#LedgerVoucher)||<a href="SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity</a>|
|[BackingTable_SalesInvoiceHeaderV2EntityRelationshipId](#BackingTable_SalesInvoiceHeaderV2EntityRelationshipId)||<a href="SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity.md" target="_blank">AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity</a>|

### <a href=#ContactPersonId name="ContactPersonId">ContactPersonId</a>

First included in: AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity (this entity)  

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

First included in: AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity (this entity)  

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

### <a href=#CustomersOrderReference name="CustomersOrderReference">CustomersOrderReference</a>

First included in: AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomersOrderReference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryModeCode name="DeliveryModeCode">DeliveryModeCode</a>

First included in: AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity (this entity)  

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

### <a href=#DeliveryTermsCode name="DeliveryTermsCode">DeliveryTermsCode</a>

First included in: AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity (this entity)  

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

### <a href=#InvoiceAddressCity name="InvoiceAddressCity">InvoiceAddressCity</a>

First included in: AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity (this entity)  

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

First included in: AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity (this entity)  

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

First included in: AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity (this entity)  

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

### <a href=#InvoiceAddressState name="InvoiceAddressState">InvoiceAddressState</a>

First included in: AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAddressState attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAddressStreet name="InvoiceAddressStreet">InvoiceAddressStreet</a>

First included in: AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity (this entity)  

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

### <a href=#InvoiceAddressStreetNumber name="InvoiceAddressStreetNumber">InvoiceAddressStreetNumber</a>

First included in: AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity (this entity)  

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

### <a href=#InvoiceAddressZipCode name="InvoiceAddressZipCode">InvoiceAddressZipCode</a>

First included in: AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity (this entity)  

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

### <a href=#InvoiceCustomerAccountNumber name="InvoiceCustomerAccountNumber">InvoiceCustomerAccountNumber</a>

First included in: AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity (this entity)  

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

### <a href=#InvoiceDate name="InvoiceDate">InvoiceDate</a>

First included in: AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceNumber name="InvoiceNumber">InvoiceNumber</a>

First included in: AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentTermsName name="PaymentTermsName">PaymentTermsName</a>

First included in: AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity (this entity)  

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

### <a href=#SalesOrderNumber name="SalesOrderNumber">SalesOrderNumber</a>

First included in: AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesOrderNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesOrderResponsiblePersonnelNumber name="SalesOrderResponsiblePersonnelNumber">SalesOrderResponsiblePersonnelNumber</a>

First included in: AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesOrderResponsiblePersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalChargeAmount name="TotalChargeAmount">TotalChargeAmount</a>

First included in: AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalChargeAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalDiscountAmount name="TotalDiscountAmount">TotalDiscountAmount</a>

First included in: AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity (this entity)  

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

### <a href=#TotalDiscountCustomerGroupCode name="TotalDiscountCustomerGroupCode">TotalDiscountCustomerGroupCode</a>

First included in: AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalDiscountCustomerGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalInvoiceAmount name="TotalInvoiceAmount">TotalInvoiceAmount</a>

First included in: AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalInvoiceAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalTaxAmount name="TotalTaxAmount">TotalTaxAmount</a>

First included in: AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalTaxAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceHeaderTaxAmount name="InvoiceHeaderTaxAmount">InvoiceHeaderTaxAmount</a>

First included in: AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceHeaderTaxAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesOrderOriginType name="SalesOrderOriginType">SalesOrderOriginType</a>

First included in: AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesOrderOriginType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerVoucher name="LedgerVoucher">LedgerVoucher</a>

First included in: AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerVoucher attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_SalesInvoiceHeaderV2EntityRelationshipId name="BackingTable_SalesInvoiceHeaderV2EntityRelationshipId">BackingTable_SalesInvoiceHeaderV2EntityRelationshipId</a>

First included in: AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_SalesInvoiceHeaderV2EntityRelationshipId attribute are listed below.</summary>

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

First included in: AccountsReceivable/SalesExternallyMaintainedCustomerSalesInvoiceHeaderEntity (this entity)  

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
