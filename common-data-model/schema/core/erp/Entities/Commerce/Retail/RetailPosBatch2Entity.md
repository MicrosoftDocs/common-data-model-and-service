---
title: RetailPosBatch2Entity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/16/2020
ms.author: nebanfic
---

# @RET5070

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Entities/Commerce/Retail/RetailPosBatch2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.Application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>@RET5070</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Entity|
|---|---|---|
|[Terminal](#Terminal)||<a href="RetailPosBatch2Entity.md" target="_blank">Retail/RetailPosBatch2Entity</a>|
|[BatchShiftId](#BatchShiftId)||<a href="RetailPosBatch2Entity.md" target="_blank">Retail/RetailPosBatch2Entity</a>|
|[Channel](#Channel)||<a href="RetailPosBatch2Entity.md" target="_blank">Retail/RetailPosBatch2Entity</a>|
|[CloseDate](#CloseDate)||<a href="RetailPosBatch2Entity.md" target="_blank">Retail/RetailPosBatch2Entity</a>|
|[CloseDateTimeUtc](#CloseDateTimeUtc)||<a href="RetailPosBatch2Entity.md" target="_blank">Retail/RetailPosBatch2Entity</a>|
|[ClosedAtRegisterNumber](#ClosedAtRegisterNumber)||<a href="RetailPosBatch2Entity.md" target="_blank">Retail/RetailPosBatch2Entity</a>|
|[CloseTime](#CloseTime)||<a href="RetailPosBatch2Entity.md" target="_blank">Retail/RetailPosBatch2Entity</a>|
|[CustomerSalesCount](#CustomerSalesCount)||<a href="RetailPosBatch2Entity.md" target="_blank">Retail/RetailPosBatch2Entity</a>|
|[DiscountTotalAmount](#DiscountTotalAmount)||<a href="RetailPosBatch2Entity.md" target="_blank">Retail/RetailPosBatch2Entity</a>|
|[LogonsCount](#LogonsCount)||<a href="RetailPosBatch2Entity.md" target="_blank">Retail/RetailPosBatch2Entity</a>|
|[NoSaleCount](#NoSaleCount)||<a href="RetailPosBatch2Entity.md" target="_blank">Retail/RetailPosBatch2Entity</a>|
|[LocationNumber](#LocationNumber)||<a href="RetailPosBatch2Entity.md" target="_blank">Retail/RetailPosBatch2Entity</a>|
|[PaidToAccountTotal](#PaidToAccountTotal)||<a href="RetailPosBatch2Entity.md" target="_blank">Retail/RetailPosBatch2Entity</a>|
|[Posted](#Posted)||<a href="RetailPosBatch2Entity.md" target="_blank">Retail/RetailPosBatch2Entity</a>|
|[ReplicationCounter](#ReplicationCounter)||<a href="RetailPosBatch2Entity.md" target="_blank">Retail/RetailPosBatch2Entity</a>|
|[ReturnsTotal](#ReturnsTotal)||<a href="RetailPosBatch2Entity.md" target="_blank">Retail/RetailPosBatch2Entity</a>|
|[RoundedAmountTotal](#RoundedAmountTotal)||<a href="RetailPosBatch2Entity.md" target="_blank">Retail/RetailPosBatch2Entity</a>|
|[SalesCount](#SalesCount)||<a href="RetailPosBatch2Entity.md" target="_blank">Retail/RetailPosBatch2Entity</a>|
|[SalesTotal](#SalesTotal)||<a href="RetailPosBatch2Entity.md" target="_blank">Retail/RetailPosBatch2Entity</a>|
|[OperatorId](#OperatorId)||<a href="RetailPosBatch2Entity.md" target="_blank">Retail/RetailPosBatch2Entity</a>|
|[StartDate](#StartDate)||<a href="RetailPosBatch2Entity.md" target="_blank">Retail/RetailPosBatch2Entity</a>|
|[StartDateTimeUtc](#StartDateTimeUtc)||<a href="RetailPosBatch2Entity.md" target="_blank">Retail/RetailPosBatch2Entity</a>|
|[StartTime](#StartTime)||<a href="RetailPosBatch2Entity.md" target="_blank">Retail/RetailPosBatch2Entity</a>|
|[StatementId](#StatementId)||<a href="RetailPosBatch2Entity.md" target="_blank">Retail/RetailPosBatch2Entity</a>|
|[Status](#Status)||<a href="RetailPosBatch2Entity.md" target="_blank">Retail/RetailPosBatch2Entity</a>|
|[OperationUnitNumber](#OperationUnitNumber)||<a href="RetailPosBatch2Entity.md" target="_blank">Retail/RetailPosBatch2Entity</a>|
|[TaxTotal](#TaxTotal)||<a href="RetailPosBatch2Entity.md" target="_blank">Retail/RetailPosBatch2Entity</a>|
|[TransactionsCount](#TransactionsCount)||<a href="RetailPosBatch2Entity.md" target="_blank">Retail/RetailPosBatch2Entity</a>|
|[VoidsCount](#VoidsCount)||<a href="RetailPosBatch2Entity.md" target="_blank">Retail/RetailPosBatch2Entity</a>|
|[ItemsSold](#ItemsSold)||<a href="RetailPosBatch2Entity.md" target="_blank">Retail/RetailPosBatch2Entity</a>|
|[PriceOverrideTotal](#PriceOverrideTotal)||<a href="RetailPosBatch2Entity.md" target="_blank">Retail/RetailPosBatch2Entity</a>|
|[ReceiptCopiesCount](#ReceiptCopiesCount)||<a href="RetailPosBatch2Entity.md" target="_blank">Retail/RetailPosBatch2Entity</a>|
|[ReceiptCopiesTotal](#ReceiptCopiesTotal)||<a href="RetailPosBatch2Entity.md" target="_blank">Retail/RetailPosBatch2Entity</a>|
|[ReturnsCount](#ReturnsCount)||<a href="RetailPosBatch2Entity.md" target="_blank">Retail/RetailPosBatch2Entity</a>|
|[ReturnsGrandTotal](#ReturnsGrandTotal)||<a href="RetailPosBatch2Entity.md" target="_blank">Retail/RetailPosBatch2Entity</a>|
|[SalesGrandTotal](#SalesGrandTotal)||<a href="RetailPosBatch2Entity.md" target="_blank">Retail/RetailPosBatch2Entity</a>|
|[ServicesSoldQuantity](#ServicesSoldQuantity)||<a href="RetailPosBatch2Entity.md" target="_blank">Retail/RetailPosBatch2Entity</a>|
|[SuspendedCount](#SuspendedCount)||<a href="RetailPosBatch2Entity.md" target="_blank">Retail/RetailPosBatch2Entity</a>|
|[SuspendedTotal](#SuspendedTotal)||<a href="RetailPosBatch2Entity.md" target="_blank">Retail/RetailPosBatch2Entity</a>|
|[TrainingCount](#TrainingCount)||<a href="RetailPosBatch2Entity.md" target="_blank">Retail/RetailPosBatch2Entity</a>|
|[TrainingTotal](#TrainingTotal)||<a href="RetailPosBatch2Entity.md" target="_blank">Retail/RetailPosBatch2Entity</a>|
|[RetailChannelTable_OMOperatingUnitID](#RetailChannelTable_OMOperatingUnitID)||<a href="RetailPosBatch2Entity.md" target="_blank">Retail/RetailPosBatch2Entity</a>|
|[OrganizationPartyNumber](#OrganizationPartyNumber)||<a href="RetailPosBatch2Entity.md" target="_blank">Retail/RetailPosBatch2Entity</a>|
|[StoreNumber](#StoreNumber)||<a href="RetailPosBatch2Entity.md" target="_blank">Retail/RetailPosBatch2Entity</a>|
|[GiftCardsTotal](#GiftCardsTotal)||<a href="RetailPosBatch2Entity.md" target="_blank">Retail/RetailPosBatch2Entity</a>|
|[VoidedSalesTotal](#VoidedSalesTotal)||<a href="RetailPosBatch2Entity.md" target="_blank">Retail/RetailPosBatch2Entity</a>|
|[ShiftReturnsTotal](#ShiftReturnsTotal)||<a href="RetailPosBatch2Entity.md" target="_blank">Retail/RetailPosBatch2Entity</a>|
|[ShiftSalesTotal](#ShiftSalesTotal)||<a href="RetailPosBatch2Entity.md" target="_blank">Retail/RetailPosBatch2Entity</a>|
|[GiftCardCashOutTotal](#GiftCardCashOutTotal)||<a href="RetailPosBatch2Entity.md" target="_blank">Retail/RetailPosBatch2Entity</a>|
|[ChargeTotal](#ChargeTotal)||<a href="RetailPosBatch2Entity.md" target="_blank">Retail/RetailPosBatch2Entity</a>|
|[ZeroSalesCount](#ZeroSalesCount)||<a href="RetailPosBatch2Entity.md" target="_blank">Retail/RetailPosBatch2Entity</a>|
|[BackingTable_RetailPosBatchTableRelationshipId](#BackingTable_RetailPosBatchTableRelationshipId)||<a href="RetailPosBatch2Entity.md" target="_blank">Retail/RetailPosBatch2Entity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="RetailPosBatch2Entity.md" target="_blank">Retail/RetailPosBatch2Entity</a>|

### <a href=#Terminal name="Terminal">Terminal</a>

First included in: Retail/RetailPosBatch2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Terminal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BatchShiftId name="BatchShiftId">BatchShiftId</a>

First included in: Retail/RetailPosBatch2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BatchShiftId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Channel name="Channel">Channel</a>

First included in: Retail/RetailPosBatch2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Channel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CloseDate name="CloseDate">CloseDate</a>

First included in: Retail/RetailPosBatch2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CloseDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CloseDateTimeUtc name="CloseDateTimeUtc">CloseDateTimeUtc</a>

First included in: Retail/RetailPosBatch2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CloseDateTimeUtc attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ClosedAtRegisterNumber name="ClosedAtRegisterNumber">ClosedAtRegisterNumber</a>

First included in: Retail/RetailPosBatch2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClosedAtRegisterNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CloseTime name="CloseTime">CloseTime</a>

First included in: Retail/RetailPosBatch2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CloseTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerSalesCount name="CustomerSalesCount">CustomerSalesCount</a>

First included in: Retail/RetailPosBatch2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerSalesCount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscountTotalAmount name="DiscountTotalAmount">DiscountTotalAmount</a>

First included in: Retail/RetailPosBatch2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountTotalAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LogonsCount name="LogonsCount">LogonsCount</a>

First included in: Retail/RetailPosBatch2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogonsCount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NoSaleCount name="NoSaleCount">NoSaleCount</a>

First included in: Retail/RetailPosBatch2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NoSaleCount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LocationNumber name="LocationNumber">LocationNumber</a>

First included in: Retail/RetailPosBatch2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LocationNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaidToAccountTotal name="PaidToAccountTotal">PaidToAccountTotal</a>

First included in: Retail/RetailPosBatch2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaidToAccountTotal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Posted name="Posted">Posted</a>

First included in: Retail/RetailPosBatch2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Posted attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReplicationCounter name="ReplicationCounter">ReplicationCounter</a>

First included in: Retail/RetailPosBatch2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplicationCounter attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnsTotal name="ReturnsTotal">ReturnsTotal</a>

First included in: Retail/RetailPosBatch2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnsTotal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RoundedAmountTotal name="RoundedAmountTotal">RoundedAmountTotal</a>

First included in: Retail/RetailPosBatch2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RoundedAmountTotal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesCount name="SalesCount">SalesCount</a>

First included in: Retail/RetailPosBatch2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesCount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesTotal name="SalesTotal">SalesTotal</a>

First included in: Retail/RetailPosBatch2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesTotal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperatorId name="OperatorId">OperatorId</a>

First included in: Retail/RetailPosBatch2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperatorId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StartDate name="StartDate">StartDate</a>

First included in: Retail/RetailPosBatch2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StartDateTimeUtc name="StartDateTimeUtc">StartDateTimeUtc</a>

First included in: Retail/RetailPosBatch2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartDateTimeUtc attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StartTime name="StartTime">StartTime</a>

First included in: Retail/RetailPosBatch2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StatementId name="StatementId">StatementId</a>

First included in: Retail/RetailPosBatch2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StatementId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Status name="Status">Status</a>

First included in: Retail/RetailPosBatch2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Status attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperationUnitNumber name="OperationUnitNumber">OperationUnitNumber</a>

First included in: Retail/RetailPosBatch2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperationUnitNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxTotal name="TaxTotal">TaxTotal</a>

First included in: Retail/RetailPosBatch2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxTotal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionsCount name="TransactionsCount">TransactionsCount</a>

First included in: Retail/RetailPosBatch2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionsCount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VoidsCount name="VoidsCount">VoidsCount</a>

First included in: Retail/RetailPosBatch2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VoidsCount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemsSold name="ItemsSold">ItemsSold</a>

First included in: Retail/RetailPosBatch2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemsSold attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PriceOverrideTotal name="PriceOverrideTotal">PriceOverrideTotal</a>

First included in: Retail/RetailPosBatch2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriceOverrideTotal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceiptCopiesCount name="ReceiptCopiesCount">ReceiptCopiesCount</a>

First included in: Retail/RetailPosBatch2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceiptCopiesCount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceiptCopiesTotal name="ReceiptCopiesTotal">ReceiptCopiesTotal</a>

First included in: Retail/RetailPosBatch2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceiptCopiesTotal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnsCount name="ReturnsCount">ReturnsCount</a>

First included in: Retail/RetailPosBatch2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnsCount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnsGrandTotal name="ReturnsGrandTotal">ReturnsGrandTotal</a>

First included in: Retail/RetailPosBatch2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnsGrandTotal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesGrandTotal name="SalesGrandTotal">SalesGrandTotal</a>

First included in: Retail/RetailPosBatch2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesGrandTotal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ServicesSoldQuantity name="ServicesSoldQuantity">ServicesSoldQuantity</a>

First included in: Retail/RetailPosBatch2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServicesSoldQuantity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SuspendedCount name="SuspendedCount">SuspendedCount</a>

First included in: Retail/RetailPosBatch2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SuspendedCount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SuspendedTotal name="SuspendedTotal">SuspendedTotal</a>

First included in: Retail/RetailPosBatch2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SuspendedTotal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TrainingCount name="TrainingCount">TrainingCount</a>

First included in: Retail/RetailPosBatch2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TrainingCount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TrainingTotal name="TrainingTotal">TrainingTotal</a>

First included in: Retail/RetailPosBatch2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TrainingTotal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailChannelTable_OMOperatingUnitID name="RetailChannelTable_OMOperatingUnitID">RetailChannelTable_OMOperatingUnitID</a>

First included in: Retail/RetailPosBatch2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailChannelTable_OMOperatingUnitID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrganizationPartyNumber name="OrganizationPartyNumber">OrganizationPartyNumber</a>

First included in: Retail/RetailPosBatch2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrganizationPartyNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StoreNumber name="StoreNumber">StoreNumber</a>

First included in: Retail/RetailPosBatch2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StoreNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GiftCardsTotal name="GiftCardsTotal">GiftCardsTotal</a>

First included in: Retail/RetailPosBatch2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiftCardsTotal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VoidedSalesTotal name="VoidedSalesTotal">VoidedSalesTotal</a>

First included in: Retail/RetailPosBatch2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VoidedSalesTotal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShiftReturnsTotal name="ShiftReturnsTotal">ShiftReturnsTotal</a>

First included in: Retail/RetailPosBatch2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShiftReturnsTotal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShiftSalesTotal name="ShiftSalesTotal">ShiftSalesTotal</a>

First included in: Retail/RetailPosBatch2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShiftSalesTotal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GiftCardCashOutTotal name="GiftCardCashOutTotal">GiftCardCashOutTotal</a>

First included in: Retail/RetailPosBatch2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiftCardCashOutTotal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChargeTotal name="ChargeTotal">ChargeTotal</a>

First included in: Retail/RetailPosBatch2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChargeTotal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ZeroSalesCount name="ZeroSalesCount">ZeroSalesCount</a>

First included in: Retail/RetailPosBatch2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ZeroSalesCount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_RetailPosBatchTableRelationshipId name="BackingTable_RetailPosBatchTableRelationshipId">BackingTable_RetailPosBatchTableRelationshipId</a>

First included in: Retail/RetailPosBatch2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>6</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailPosBatchTableRelationshipId attribute are listed below.</summary>

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

First included in: Retail/RetailPosBatch2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>6</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PrimaryCompanyContextRelationshipId attribute are listed below.</summary>

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
