---
title: PurchProcurementDocumentDefaultsEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# PurchProcurementDocumentDefaultsEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ArePurchaseOrderAmountsPrintedByDefault](#ArePurchaseOrderAmountsPrintedByDefault)||<a href="PurchProcurementDocumentDefaultsEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity</a>|
|[DefaultPurchaseOrderPoolId](#DefaultPurchaseOrderPoolId)||<a href="PurchProcurementDocumentDefaultsEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity</a>|
|[DefaultPurchaseOrderType](#DefaultPurchaseOrderType)||<a href="PurchProcurementDocumentDefaultsEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity</a>|
|[DefaultRFQDeliveryModeCode](#DefaultRFQDeliveryModeCode)||<a href="PurchProcurementDocumentDefaultsEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity</a>|
|[DefaultRFQDeliveryTermsCode](#DefaultRFQDeliveryTermsCode)||<a href="PurchProcurementDocumentDefaultsEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity</a>|
|[DefaultRFQExpirationTime](#DefaultRFQExpirationTime)||<a href="PurchProcurementDocumentDefaultsEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity</a>|
|[DefaultRFQPaymentTermsName](#DefaultRFQPaymentTermsName)||<a href="PurchProcurementDocumentDefaultsEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity</a>|
|[DefaultRFQPurchaseDocumentType](#DefaultRFQPurchaseDocumentType)||<a href="PurchProcurementDocumentDefaultsEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity</a>|
|[DefaultRFQSolicitationTypeRecId](#DefaultRFQSolicitationTypeRecId)||<a href="PurchProcurementDocumentDefaultsEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity</a>|
|[DefaultRFQSolicitationTypeName](#DefaultRFQSolicitationTypeName)||<a href="PurchProcurementDocumentDefaultsEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity</a>|
|[DefaultRFQValidityPeriodDays](#DefaultRFQValidityPeriodDays)||<a href="PurchProcurementDocumentDefaultsEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity</a>|
|[DefaultReturnOrderReturnActionId](#DefaultReturnOrderReturnActionId)||<a href="PurchProcurementDocumentDefaultsEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity</a>|
|[IsQuotationReplyHeaderCurrencyCodeDisplayedByDefault](#IsQuotationReplyHeaderCurrencyCodeDisplayedByDefault)||<a href="PurchProcurementDocumentDefaultsEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity</a>|
|[IsQuotationReplyHeaderDeliveryDateDisplayedByDefault](#IsQuotationReplyHeaderDeliveryDateDisplayedByDefault)||<a href="PurchProcurementDocumentDefaultsEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity</a>|
|[IsQuotationReplyHeaderDeliveryTermsDisplayedByDefault](#IsQuotationReplyHeaderDeliveryTermsDisplayedByDefault)||<a href="PurchProcurementDocumentDefaultsEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity</a>|
|[IsQuotationReplyHeaderDocumentationDisplayedByDefault](#IsQuotationReplyHeaderDocumentationDisplayedByDefault)||<a href="PurchProcurementDocumentDefaultsEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity</a>|
|[IsQuotationReplyHeaderTotalDiscountPercentageDisplayedByDefault](#IsQuotationReplyHeaderTotalDiscountPercentageDisplayedByDefault)||<a href="PurchProcurementDocumentDefaultsEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity</a>|
|[IsQuotationReplyHeaderPurchaseChargeDisplayedByDefault](#IsQuotationReplyHeaderPurchaseChargeDisplayedByDefault)||<a href="PurchProcurementDocumentDefaultsEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity</a>|
|[IsQuotationReplyHeaderPaymentTermsDisplayedByDefault](#IsQuotationReplyHeaderPaymentTermsDisplayedByDefault)||<a href="PurchProcurementDocumentDefaultsEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity</a>|
|[IsQuotationReplyHeaderValidFromDateDisplayedByDefault](#IsQuotationReplyHeaderValidFromDateDisplayedByDefault)||<a href="PurchProcurementDocumentDefaultsEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity</a>|
|[IsQuotationReplyHeaderValidToDateDisplayedByDefault](#IsQuotationReplyHeaderValidToDateDisplayedByDefault)||<a href="PurchProcurementDocumentDefaultsEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity</a>|
|[IsQuotationReplyHeaderVendReferenceDisplayedByDefault](#IsQuotationReplyHeaderVendReferenceDisplayedByDefault)||<a href="PurchProcurementDocumentDefaultsEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity</a>|
|[IsQuotationReplyLineDeliveryDateDisplayedByDefault](#IsQuotationReplyLineDeliveryDateDisplayedByDefault)||<a href="PurchProcurementDocumentDefaultsEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity</a>|
|[IsQuotationReplyLineDocumentationDisplayedByDefault](#IsQuotationReplyLineDocumentationDisplayedByDefault)||<a href="PurchProcurementDocumentDefaultsEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity</a>|
|[IsQuotationReplyLineExternalItemDescriptionDisplayedByDefault](#IsQuotationReplyLineExternalItemDescriptionDisplayedByDefault)||<a href="PurchProcurementDocumentDefaultsEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity</a>|
|[IsQuotationReplyLineExternalItemNumberDisplayedByDefault](#IsQuotationReplyLineExternalItemNumberDisplayedByDefault)||<a href="PurchProcurementDocumentDefaultsEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity</a>|
|[IsQuotationReplyLineLeadTimeDisplayedByDefault](#IsQuotationReplyLineLeadTimeDisplayedByDefault)||<a href="PurchProcurementDocumentDefaultsEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity</a>|
|[IsQuotationReplyLineLineDiscountAmountDisplayedByDefault](#IsQuotationReplyLineLineDiscountAmountDisplayedByDefault)||<a href="PurchProcurementDocumentDefaultsEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity</a>|
|[IsQuotationReplyLinePurchaseChargeDisplayedByDefault](#IsQuotationReplyLinePurchaseChargeDisplayedByDefault)||<a href="PurchProcurementDocumentDefaultsEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity</a>|
|[IsQuotationReplyLineMultilineDiscountAmountDisplayedByDefault](#IsQuotationReplyLineMultilineDiscountAmountDisplayedByDefault)||<a href="PurchProcurementDocumentDefaultsEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity</a>|
|[IsQuotationReplyLineMultilineDiscountPercentageDisplayedByDefault](#IsQuotationReplyLineMultilineDiscountPercentageDisplayedByDefault)||<a href="PurchProcurementDocumentDefaultsEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity</a>|
|[IsQuotationReplyLineLineDiscountPercentDisplayedByDefault](#IsQuotationReplyLineLineDiscountPercentDisplayedByDefault)||<a href="PurchProcurementDocumentDefaultsEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity</a>|
|[IsQuotationReplyLinePriceQuantityDisplayedByDefault](#IsQuotationReplyLinePriceQuantityDisplayedByDefault)||<a href="PurchProcurementDocumentDefaultsEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity</a>|
|[IsQuotationReplyLineQuantityDisplayedByDefault](#IsQuotationReplyLineQuantityDisplayedByDefault)||<a href="PurchProcurementDocumentDefaultsEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity</a>|
|[IsQuotationReplyLineUnitSymbolDisplayedByDefault](#IsQuotationReplyLineUnitSymbolDisplayedByDefault)||<a href="PurchProcurementDocumentDefaultsEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity</a>|
|[IsQuotationReplyLineValidFromDateDisplayedByDefault](#IsQuotationReplyLineValidFromDateDisplayedByDefault)||<a href="PurchProcurementDocumentDefaultsEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity</a>|
|[IsQuotationReplyLineValidToDateDisplayedByDefault](#IsQuotationReplyLineValidToDateDisplayedByDefault)||<a href="PurchProcurementDocumentDefaultsEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity</a>|
|[IsQuotationReplyLineWorkingDaysDisplayedByDefault](#IsQuotationReplyLineWorkingDaysDisplayedByDefault)||<a href="PurchProcurementDocumentDefaultsEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity</a>|
|[IsRFQValidityPeriodUsingWorkingDays](#IsRFQValidityPeriodUsingWorkingDays)||<a href="PurchProcurementDocumentDefaultsEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity</a>|
|[ExchangeRateDate](#ExchangeRateDate)||<a href="PurchProcurementDocumentDefaultsEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity</a>|
|[BackingTable_PurchParametersRelationshipId](#BackingTable_PurchParametersRelationshipId)||<a href="PurchProcurementDocumentDefaultsEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="PurchProcurementDocumentDefaultsEntity.md" target="_blank">ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity</a>|

### <a href=#ArePurchaseOrderAmountsPrintedByDefault name="ArePurchaseOrderAmountsPrintedByDefault">ArePurchaseOrderAmountsPrintedByDefault</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ArePurchaseOrderAmountsPrintedByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultPurchaseOrderPoolId name="DefaultPurchaseOrderPoolId">DefaultPurchaseOrderPoolId</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultPurchaseOrderPoolId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultPurchaseOrderType name="DefaultPurchaseOrderType">DefaultPurchaseOrderType</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultPurchaseOrderType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultRFQDeliveryModeCode name="DefaultRFQDeliveryModeCode">DefaultRFQDeliveryModeCode</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultRFQDeliveryModeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultRFQDeliveryTermsCode name="DefaultRFQDeliveryTermsCode">DefaultRFQDeliveryTermsCode</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultRFQDeliveryTermsCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultRFQExpirationTime name="DefaultRFQExpirationTime">DefaultRFQExpirationTime</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultRFQExpirationTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultRFQPaymentTermsName name="DefaultRFQPaymentTermsName">DefaultRFQPaymentTermsName</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultRFQPaymentTermsName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultRFQPurchaseDocumentType name="DefaultRFQPurchaseDocumentType">DefaultRFQPurchaseDocumentType</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultRFQPurchaseDocumentType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultRFQSolicitationTypeRecId name="DefaultRFQSolicitationTypeRecId">DefaultRFQSolicitationTypeRecId</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultRFQSolicitationTypeRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultRFQSolicitationTypeName name="DefaultRFQSolicitationTypeName">DefaultRFQSolicitationTypeName</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultRFQSolicitationTypeName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultRFQValidityPeriodDays name="DefaultRFQValidityPeriodDays">DefaultRFQValidityPeriodDays</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultRFQValidityPeriodDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultReturnOrderReturnActionId name="DefaultReturnOrderReturnActionId">DefaultReturnOrderReturnActionId</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultReturnOrderReturnActionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuotationReplyHeaderCurrencyCodeDisplayedByDefault name="IsQuotationReplyHeaderCurrencyCodeDisplayedByDefault">IsQuotationReplyHeaderCurrencyCodeDisplayedByDefault</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuotationReplyHeaderCurrencyCodeDisplayedByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuotationReplyHeaderDeliveryDateDisplayedByDefault name="IsQuotationReplyHeaderDeliveryDateDisplayedByDefault">IsQuotationReplyHeaderDeliveryDateDisplayedByDefault</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuotationReplyHeaderDeliveryDateDisplayedByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuotationReplyHeaderDeliveryTermsDisplayedByDefault name="IsQuotationReplyHeaderDeliveryTermsDisplayedByDefault">IsQuotationReplyHeaderDeliveryTermsDisplayedByDefault</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuotationReplyHeaderDeliveryTermsDisplayedByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuotationReplyHeaderDocumentationDisplayedByDefault name="IsQuotationReplyHeaderDocumentationDisplayedByDefault">IsQuotationReplyHeaderDocumentationDisplayedByDefault</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuotationReplyHeaderDocumentationDisplayedByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuotationReplyHeaderTotalDiscountPercentageDisplayedByDefault name="IsQuotationReplyHeaderTotalDiscountPercentageDisplayedByDefault">IsQuotationReplyHeaderTotalDiscountPercentageDisplayedByDefault</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuotationReplyHeaderTotalDiscountPercentageDisplayedByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuotationReplyHeaderPurchaseChargeDisplayedByDefault name="IsQuotationReplyHeaderPurchaseChargeDisplayedByDefault">IsQuotationReplyHeaderPurchaseChargeDisplayedByDefault</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuotationReplyHeaderPurchaseChargeDisplayedByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuotationReplyHeaderPaymentTermsDisplayedByDefault name="IsQuotationReplyHeaderPaymentTermsDisplayedByDefault">IsQuotationReplyHeaderPaymentTermsDisplayedByDefault</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuotationReplyHeaderPaymentTermsDisplayedByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuotationReplyHeaderValidFromDateDisplayedByDefault name="IsQuotationReplyHeaderValidFromDateDisplayedByDefault">IsQuotationReplyHeaderValidFromDateDisplayedByDefault</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuotationReplyHeaderValidFromDateDisplayedByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuotationReplyHeaderValidToDateDisplayedByDefault name="IsQuotationReplyHeaderValidToDateDisplayedByDefault">IsQuotationReplyHeaderValidToDateDisplayedByDefault</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuotationReplyHeaderValidToDateDisplayedByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuotationReplyHeaderVendReferenceDisplayedByDefault name="IsQuotationReplyHeaderVendReferenceDisplayedByDefault">IsQuotationReplyHeaderVendReferenceDisplayedByDefault</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuotationReplyHeaderVendReferenceDisplayedByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuotationReplyLineDeliveryDateDisplayedByDefault name="IsQuotationReplyLineDeliveryDateDisplayedByDefault">IsQuotationReplyLineDeliveryDateDisplayedByDefault</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuotationReplyLineDeliveryDateDisplayedByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuotationReplyLineDocumentationDisplayedByDefault name="IsQuotationReplyLineDocumentationDisplayedByDefault">IsQuotationReplyLineDocumentationDisplayedByDefault</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuotationReplyLineDocumentationDisplayedByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuotationReplyLineExternalItemDescriptionDisplayedByDefault name="IsQuotationReplyLineExternalItemDescriptionDisplayedByDefault">IsQuotationReplyLineExternalItemDescriptionDisplayedByDefault</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuotationReplyLineExternalItemDescriptionDisplayedByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuotationReplyLineExternalItemNumberDisplayedByDefault name="IsQuotationReplyLineExternalItemNumberDisplayedByDefault">IsQuotationReplyLineExternalItemNumberDisplayedByDefault</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuotationReplyLineExternalItemNumberDisplayedByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuotationReplyLineLeadTimeDisplayedByDefault name="IsQuotationReplyLineLeadTimeDisplayedByDefault">IsQuotationReplyLineLeadTimeDisplayedByDefault</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuotationReplyLineLeadTimeDisplayedByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuotationReplyLineLineDiscountAmountDisplayedByDefault name="IsQuotationReplyLineLineDiscountAmountDisplayedByDefault">IsQuotationReplyLineLineDiscountAmountDisplayedByDefault</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuotationReplyLineLineDiscountAmountDisplayedByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuotationReplyLinePurchaseChargeDisplayedByDefault name="IsQuotationReplyLinePurchaseChargeDisplayedByDefault">IsQuotationReplyLinePurchaseChargeDisplayedByDefault</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuotationReplyLinePurchaseChargeDisplayedByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuotationReplyLineMultilineDiscountAmountDisplayedByDefault name="IsQuotationReplyLineMultilineDiscountAmountDisplayedByDefault">IsQuotationReplyLineMultilineDiscountAmountDisplayedByDefault</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuotationReplyLineMultilineDiscountAmountDisplayedByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuotationReplyLineMultilineDiscountPercentageDisplayedByDefault name="IsQuotationReplyLineMultilineDiscountPercentageDisplayedByDefault">IsQuotationReplyLineMultilineDiscountPercentageDisplayedByDefault</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuotationReplyLineMultilineDiscountPercentageDisplayedByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuotationReplyLineLineDiscountPercentDisplayedByDefault name="IsQuotationReplyLineLineDiscountPercentDisplayedByDefault">IsQuotationReplyLineLineDiscountPercentDisplayedByDefault</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuotationReplyLineLineDiscountPercentDisplayedByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuotationReplyLinePriceQuantityDisplayedByDefault name="IsQuotationReplyLinePriceQuantityDisplayedByDefault">IsQuotationReplyLinePriceQuantityDisplayedByDefault</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuotationReplyLinePriceQuantityDisplayedByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuotationReplyLineQuantityDisplayedByDefault name="IsQuotationReplyLineQuantityDisplayedByDefault">IsQuotationReplyLineQuantityDisplayedByDefault</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuotationReplyLineQuantityDisplayedByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuotationReplyLineUnitSymbolDisplayedByDefault name="IsQuotationReplyLineUnitSymbolDisplayedByDefault">IsQuotationReplyLineUnitSymbolDisplayedByDefault</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuotationReplyLineUnitSymbolDisplayedByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuotationReplyLineValidFromDateDisplayedByDefault name="IsQuotationReplyLineValidFromDateDisplayedByDefault">IsQuotationReplyLineValidFromDateDisplayedByDefault</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuotationReplyLineValidFromDateDisplayedByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuotationReplyLineValidToDateDisplayedByDefault name="IsQuotationReplyLineValidToDateDisplayedByDefault">IsQuotationReplyLineValidToDateDisplayedByDefault</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuotationReplyLineValidToDateDisplayedByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuotationReplyLineWorkingDaysDisplayedByDefault name="IsQuotationReplyLineWorkingDaysDisplayedByDefault">IsQuotationReplyLineWorkingDaysDisplayedByDefault</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuotationReplyLineWorkingDaysDisplayedByDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsRFQValidityPeriodUsingWorkingDays name="IsRFQValidityPeriodUsingWorkingDays">IsRFQValidityPeriodUsingWorkingDays</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsRFQValidityPeriodUsingWorkingDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExchangeRateDate name="ExchangeRateDate">ExchangeRateDate</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchangeRateDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_PurchParametersRelationshipId name="BackingTable_PurchParametersRelationshipId">BackingTable_PurchParametersRelationshipId</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PurchParametersRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Parameter/PurchParameters.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Parameter/PurchParameters.cdm.json/PurchParameters</a></td><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Parameter/PurchParameters.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProcurementAndSourcing/PurchProcurementDocumentDefaultsEntity (this entity)  

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
