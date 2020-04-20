---
title: SalesDocumentEventTrackingSetupEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# SalesDocumentEventTrackingSetupEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/SalesAndMarketing/SalesDocumentEventTrackingSetupEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[AreFraudHoldAdditionsLogged](#AreFraudHoldAdditionsLogged)||<a href="SalesDocumentEventTrackingSetupEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEventTrackingSetupEntity</a>|
|[AreSalesOrderHoldAdditionsLogged](#AreSalesOrderHoldAdditionsLogged)||<a href="SalesDocumentEventTrackingSetupEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEventTrackingSetupEntity</a>|
|[IsAlternateItemUsageLogged](#IsAlternateItemUsageLogged)||<a href="SalesDocumentEventTrackingSetupEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEventTrackingSetupEntity</a>|
|[AreDropShipmentOrderCancellationsLogged](#AreDropShipmentOrderCancellationsLogged)||<a href="SalesDocumentEventTrackingSetupEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEventTrackingSetupEntity</a>|
|[AreSalesOrderHeaderCancellationsLogged](#AreSalesOrderHeaderCancellationsLogged)||<a href="SalesDocumentEventTrackingSetupEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEventTrackingSetupEntity</a>|
|[AreSalesOrderLineCancellationsLogged](#AreSalesOrderLineCancellationsLogged)||<a href="SalesDocumentEventTrackingSetupEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEventTrackingSetupEntity</a>|
|[IsCheckHoldOnCustomerThresholdAmountLogged](#IsCheckHoldOnCustomerThresholdAmountLogged)||<a href="SalesDocumentEventTrackingSetupEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEventTrackingSetupEntity</a>|
|[AreDropShipmentOrderCreationsLogged](#AreDropShipmentOrderCreationsLogged)||<a href="SalesDocumentEventTrackingSetupEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEventTrackingSetupEntity</a>|
|[AreSalesOrderCreationsLogged](#AreSalesOrderCreationsLogged)||<a href="SalesDocumentEventTrackingSetupEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEventTrackingSetupEntity</a>|
|[AreSalesOrderDeletionsLogged](#AreSalesOrderDeletionsLogged)||<a href="SalesDocumentEventTrackingSetupEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEventTrackingSetupEntity</a>|
|[IsDropShipmentOrderDeliveryLogged](#IsDropShipmentOrderDeliveryLogged)||<a href="SalesDocumentEventTrackingSetupEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEventTrackingSetupEntity</a>|
|[AreSalesOrderLineExpeditionsLogged](#AreSalesOrderLineExpeditionsLogged)||<a href="SalesDocumentEventTrackingSetupEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEventTrackingSetupEntity</a>|
|[AreSalesOrderHeaderExpeditionsLogged](#AreSalesOrderHeaderExpeditionsLogged)||<a href="SalesDocumentEventTrackingSetupEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEventTrackingSetupEntity</a>|
|[SalesDocumentEventTrackingStartDate](#SalesDocumentEventTrackingStartDate)||<a href="SalesDocumentEventTrackingSetupEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEventTrackingSetupEntity</a>|
|[AreExemptionsLogged](#AreExemptionsLogged)||<a href="SalesDocumentEventTrackingSetupEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEventTrackingSetupEntity</a>|
|[AreSalesOrderHeaderChargeOverridesLogged](#AreSalesOrderHeaderChargeOverridesLogged)||<a href="SalesDocumentEventTrackingSetupEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEventTrackingSetupEntity</a>|
|[AreSalesOrderLineChargeOverridesLogged](#AreSalesOrderLineChargeOverridesLogged)||<a href="SalesDocumentEventTrackingSetupEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEventTrackingSetupEntity</a>|
|[AreReturnOrderModificationsLogged](#AreReturnOrderModificationsLogged)||<a href="SalesDocumentEventTrackingSetupEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEventTrackingSetupEntity</a>|
|[AreSalesOrderModificationsLogged](#AreSalesOrderModificationsLogged)||<a href="SalesDocumentEventTrackingSetupEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEventTrackingSetupEntity</a>|
|[AreSalesLineDeliveryAddressModificationsLogged](#AreSalesLineDeliveryAddressModificationsLogged)||<a href="SalesDocumentEventTrackingSetupEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEventTrackingSetupEntity</a>|
|[AreSalesOrderHoldModificationsLogged](#AreSalesOrderHoldModificationsLogged)||<a href="SalesDocumentEventTrackingSetupEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEventTrackingSetupEntity</a>|
|[AreSalesOrderCreditTracksLogged](#AreSalesOrderCreditTracksLogged)||<a href="SalesDocumentEventTrackingSetupEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEventTrackingSetupEntity</a>|
|[IsSalesOrderExceededCreditLimitLogged](#IsSalesOrderExceededCreditLimitLogged)||<a href="SalesDocumentEventTrackingSetupEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEventTrackingSetupEntity</a>|
|[IsSalesOrderOverpaidOrUnderpaidLogged](#IsSalesOrderOverpaidOrUnderpaidLogged)||<a href="SalesDocumentEventTrackingSetupEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEventTrackingSetupEntity</a>|
|[AreSalesLinesPriceMatchLogged](#AreSalesLinesPriceMatchLogged)||<a href="SalesDocumentEventTrackingSetupEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEventTrackingSetupEntity</a>|
|[AreSalesLinePriceOverridesLogged](#AreSalesLinePriceOverridesLogged)||<a href="SalesDocumentEventTrackingSetupEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEventTrackingSetupEntity</a>|
|[AreDropShipmentOrderReleasesLogged](#AreDropShipmentOrderReleasesLogged)||<a href="SalesDocumentEventTrackingSetupEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEventTrackingSetupEntity</a>|
|[AreFraudHoldRemovalsLogged](#AreFraudHoldRemovalsLogged)||<a href="SalesDocumentEventTrackingSetupEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEventTrackingSetupEntity</a>|
|[AreSalesOrderHoldRemovalsLogged](#AreSalesOrderHoldRemovalsLogged)||<a href="SalesDocumentEventTrackingSetupEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEventTrackingSetupEntity</a>|
|[AreReturnOrderCreationsLogged](#AreReturnOrderCreationsLogged)||<a href="SalesDocumentEventTrackingSetupEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEventTrackingSetupEntity</a>|
|[AreSalesQuotationLinePriceOverridesLogged](#AreSalesQuotationLinePriceOverridesLogged)||<a href="SalesDocumentEventTrackingSetupEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEventTrackingSetupEntity</a>|
|[AreSalesQuotationHeaderPriceOverridesLogged](#AreSalesQuotationHeaderPriceOverridesLogged)||<a href="SalesDocumentEventTrackingSetupEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEventTrackingSetupEntity</a>|
|[AreSalesHeaderPriceOverridesLogged](#AreSalesHeaderPriceOverridesLogged)||<a href="SalesDocumentEventTrackingSetupEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEventTrackingSetupEntity</a>|
|[SalesDocumentEventTrackingEndDate](#SalesDocumentEventTrackingEndDate)||<a href="SalesDocumentEventTrackingSetupEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEventTrackingSetupEntity</a>|
|[UserCode](#UserCode)||<a href="SalesDocumentEventTrackingSetupEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEventTrackingSetupEntity</a>|
|[UserRelation](#UserRelation)||<a href="SalesDocumentEventTrackingSetupEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEventTrackingSetupEntity</a>|
|[AreRequestedReceiptOrShipDateModificationsLogged](#AreRequestedReceiptOrShipDateModificationsLogged)||<a href="SalesDocumentEventTrackingSetupEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEventTrackingSetupEntity</a>|
|[AreConfirmedReceiptOrShipDateModificationsLogged](#AreConfirmedReceiptOrShipDateModificationsLogged)||<a href="SalesDocumentEventTrackingSetupEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEventTrackingSetupEntity</a>|
|[UserId](#UserId)||<a href="SalesDocumentEventTrackingSetupEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEventTrackingSetupEntity</a>|
|[UserGroupId](#UserGroupId)||<a href="SalesDocumentEventTrackingSetupEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEventTrackingSetupEntity</a>|
|[BackingTable_MCROrderEventSetupRelationshipId](#BackingTable_MCROrderEventSetupRelationshipId)||<a href="SalesDocumentEventTrackingSetupEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEventTrackingSetupEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="SalesDocumentEventTrackingSetupEntity.md" target="_blank">SalesAndMarketing/SalesDocumentEventTrackingSetupEntity</a>|

### <a href=#AreFraudHoldAdditionsLogged name="AreFraudHoldAdditionsLogged">AreFraudHoldAdditionsLogged</a>

First included in: SalesAndMarketing/SalesDocumentEventTrackingSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreFraudHoldAdditionsLogged attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreSalesOrderHoldAdditionsLogged name="AreSalesOrderHoldAdditionsLogged">AreSalesOrderHoldAdditionsLogged</a>

First included in: SalesAndMarketing/SalesDocumentEventTrackingSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreSalesOrderHoldAdditionsLogged attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsAlternateItemUsageLogged name="IsAlternateItemUsageLogged">IsAlternateItemUsageLogged</a>

First included in: SalesAndMarketing/SalesDocumentEventTrackingSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsAlternateItemUsageLogged attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreDropShipmentOrderCancellationsLogged name="AreDropShipmentOrderCancellationsLogged">AreDropShipmentOrderCancellationsLogged</a>

First included in: SalesAndMarketing/SalesDocumentEventTrackingSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreDropShipmentOrderCancellationsLogged attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreSalesOrderHeaderCancellationsLogged name="AreSalesOrderHeaderCancellationsLogged">AreSalesOrderHeaderCancellationsLogged</a>

First included in: SalesAndMarketing/SalesDocumentEventTrackingSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreSalesOrderHeaderCancellationsLogged attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreSalesOrderLineCancellationsLogged name="AreSalesOrderLineCancellationsLogged">AreSalesOrderLineCancellationsLogged</a>

First included in: SalesAndMarketing/SalesDocumentEventTrackingSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreSalesOrderLineCancellationsLogged attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCheckHoldOnCustomerThresholdAmountLogged name="IsCheckHoldOnCustomerThresholdAmountLogged">IsCheckHoldOnCustomerThresholdAmountLogged</a>

First included in: SalesAndMarketing/SalesDocumentEventTrackingSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCheckHoldOnCustomerThresholdAmountLogged attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreDropShipmentOrderCreationsLogged name="AreDropShipmentOrderCreationsLogged">AreDropShipmentOrderCreationsLogged</a>

First included in: SalesAndMarketing/SalesDocumentEventTrackingSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreDropShipmentOrderCreationsLogged attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreSalesOrderCreationsLogged name="AreSalesOrderCreationsLogged">AreSalesOrderCreationsLogged</a>

First included in: SalesAndMarketing/SalesDocumentEventTrackingSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreSalesOrderCreationsLogged attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreSalesOrderDeletionsLogged name="AreSalesOrderDeletionsLogged">AreSalesOrderDeletionsLogged</a>

First included in: SalesAndMarketing/SalesDocumentEventTrackingSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreSalesOrderDeletionsLogged attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDropShipmentOrderDeliveryLogged name="IsDropShipmentOrderDeliveryLogged">IsDropShipmentOrderDeliveryLogged</a>

First included in: SalesAndMarketing/SalesDocumentEventTrackingSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDropShipmentOrderDeliveryLogged attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreSalesOrderLineExpeditionsLogged name="AreSalesOrderLineExpeditionsLogged">AreSalesOrderLineExpeditionsLogged</a>

First included in: SalesAndMarketing/SalesDocumentEventTrackingSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreSalesOrderLineExpeditionsLogged attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreSalesOrderHeaderExpeditionsLogged name="AreSalesOrderHeaderExpeditionsLogged">AreSalesOrderHeaderExpeditionsLogged</a>

First included in: SalesAndMarketing/SalesDocumentEventTrackingSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreSalesOrderHeaderExpeditionsLogged attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesDocumentEventTrackingStartDate name="SalesDocumentEventTrackingStartDate">SalesDocumentEventTrackingStartDate</a>

First included in: SalesAndMarketing/SalesDocumentEventTrackingSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesDocumentEventTrackingStartDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreExemptionsLogged name="AreExemptionsLogged">AreExemptionsLogged</a>

First included in: SalesAndMarketing/SalesDocumentEventTrackingSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreExemptionsLogged attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreSalesOrderHeaderChargeOverridesLogged name="AreSalesOrderHeaderChargeOverridesLogged">AreSalesOrderHeaderChargeOverridesLogged</a>

First included in: SalesAndMarketing/SalesDocumentEventTrackingSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreSalesOrderHeaderChargeOverridesLogged attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreSalesOrderLineChargeOverridesLogged name="AreSalesOrderLineChargeOverridesLogged">AreSalesOrderLineChargeOverridesLogged</a>

First included in: SalesAndMarketing/SalesDocumentEventTrackingSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreSalesOrderLineChargeOverridesLogged attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreReturnOrderModificationsLogged name="AreReturnOrderModificationsLogged">AreReturnOrderModificationsLogged</a>

First included in: SalesAndMarketing/SalesDocumentEventTrackingSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreReturnOrderModificationsLogged attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreSalesOrderModificationsLogged name="AreSalesOrderModificationsLogged">AreSalesOrderModificationsLogged</a>

First included in: SalesAndMarketing/SalesDocumentEventTrackingSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreSalesOrderModificationsLogged attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreSalesLineDeliveryAddressModificationsLogged name="AreSalesLineDeliveryAddressModificationsLogged">AreSalesLineDeliveryAddressModificationsLogged</a>

First included in: SalesAndMarketing/SalesDocumentEventTrackingSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreSalesLineDeliveryAddressModificationsLogged attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreSalesOrderHoldModificationsLogged name="AreSalesOrderHoldModificationsLogged">AreSalesOrderHoldModificationsLogged</a>

First included in: SalesAndMarketing/SalesDocumentEventTrackingSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreSalesOrderHoldModificationsLogged attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreSalesOrderCreditTracksLogged name="AreSalesOrderCreditTracksLogged">AreSalesOrderCreditTracksLogged</a>

First included in: SalesAndMarketing/SalesDocumentEventTrackingSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreSalesOrderCreditTracksLogged attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSalesOrderExceededCreditLimitLogged name="IsSalesOrderExceededCreditLimitLogged">IsSalesOrderExceededCreditLimitLogged</a>

First included in: SalesAndMarketing/SalesDocumentEventTrackingSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSalesOrderExceededCreditLimitLogged attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsSalesOrderOverpaidOrUnderpaidLogged name="IsSalesOrderOverpaidOrUnderpaidLogged">IsSalesOrderOverpaidOrUnderpaidLogged</a>

First included in: SalesAndMarketing/SalesDocumentEventTrackingSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSalesOrderOverpaidOrUnderpaidLogged attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreSalesLinesPriceMatchLogged name="AreSalesLinesPriceMatchLogged">AreSalesLinesPriceMatchLogged</a>

First included in: SalesAndMarketing/SalesDocumentEventTrackingSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreSalesLinesPriceMatchLogged attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreSalesLinePriceOverridesLogged name="AreSalesLinePriceOverridesLogged">AreSalesLinePriceOverridesLogged</a>

First included in: SalesAndMarketing/SalesDocumentEventTrackingSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreSalesLinePriceOverridesLogged attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreDropShipmentOrderReleasesLogged name="AreDropShipmentOrderReleasesLogged">AreDropShipmentOrderReleasesLogged</a>

First included in: SalesAndMarketing/SalesDocumentEventTrackingSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreDropShipmentOrderReleasesLogged attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreFraudHoldRemovalsLogged name="AreFraudHoldRemovalsLogged">AreFraudHoldRemovalsLogged</a>

First included in: SalesAndMarketing/SalesDocumentEventTrackingSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreFraudHoldRemovalsLogged attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreSalesOrderHoldRemovalsLogged name="AreSalesOrderHoldRemovalsLogged">AreSalesOrderHoldRemovalsLogged</a>

First included in: SalesAndMarketing/SalesDocumentEventTrackingSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreSalesOrderHoldRemovalsLogged attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreReturnOrderCreationsLogged name="AreReturnOrderCreationsLogged">AreReturnOrderCreationsLogged</a>

First included in: SalesAndMarketing/SalesDocumentEventTrackingSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreReturnOrderCreationsLogged attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreSalesQuotationLinePriceOverridesLogged name="AreSalesQuotationLinePriceOverridesLogged">AreSalesQuotationLinePriceOverridesLogged</a>

First included in: SalesAndMarketing/SalesDocumentEventTrackingSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreSalesQuotationLinePriceOverridesLogged attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreSalesQuotationHeaderPriceOverridesLogged name="AreSalesQuotationHeaderPriceOverridesLogged">AreSalesQuotationHeaderPriceOverridesLogged</a>

First included in: SalesAndMarketing/SalesDocumentEventTrackingSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreSalesQuotationHeaderPriceOverridesLogged attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreSalesHeaderPriceOverridesLogged name="AreSalesHeaderPriceOverridesLogged">AreSalesHeaderPriceOverridesLogged</a>

First included in: SalesAndMarketing/SalesDocumentEventTrackingSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreSalesHeaderPriceOverridesLogged attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesDocumentEventTrackingEndDate name="SalesDocumentEventTrackingEndDate">SalesDocumentEventTrackingEndDate</a>

First included in: SalesAndMarketing/SalesDocumentEventTrackingSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesDocumentEventTrackingEndDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UserCode name="UserCode">UserCode</a>

First included in: SalesAndMarketing/SalesDocumentEventTrackingSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UserCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UserRelation name="UserRelation">UserRelation</a>

First included in: SalesAndMarketing/SalesDocumentEventTrackingSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UserRelation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreRequestedReceiptOrShipDateModificationsLogged name="AreRequestedReceiptOrShipDateModificationsLogged">AreRequestedReceiptOrShipDateModificationsLogged</a>

First included in: SalesAndMarketing/SalesDocumentEventTrackingSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreRequestedReceiptOrShipDateModificationsLogged attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreConfirmedReceiptOrShipDateModificationsLogged name="AreConfirmedReceiptOrShipDateModificationsLogged">AreConfirmedReceiptOrShipDateModificationsLogged</a>

First included in: SalesAndMarketing/SalesDocumentEventTrackingSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreConfirmedReceiptOrShipDateModificationsLogged attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UserId name="UserId">UserId</a>

First included in: SalesAndMarketing/SalesDocumentEventTrackingSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UserId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UserGroupId name="UserGroupId">UserGroupId</a>

First included in: SalesAndMarketing/SalesDocumentEventTrackingSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UserGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_MCROrderEventSetupRelationshipId name="BackingTable_MCROrderEventSetupRelationshipId">BackingTable_MCROrderEventSetupRelationshipId</a>

First included in: SalesAndMarketing/SalesDocumentEventTrackingSetupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_MCROrderEventSetupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Transaction/MCROrderEventSetup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Transaction/MCROrderEventSetup.cdm.json/MCROrderEventSetup</a></td><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Transaction/MCROrderEventSetup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: SalesAndMarketing/SalesDocumentEventTrackingSetupEntity (this entity)  

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
