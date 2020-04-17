---
title: RetailDiscountEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/16/2020
ms.author: nebanfic
---

# @RET2911

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Entities/Commerce/Retail/RetailDiscountEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.Application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>@RET2911</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ConcurrencyMode](#ConcurrencyMode)||<a href="RetailDiscountEntity.md" target="_blank">Retail/RetailDiscountEntity</a>|
|[CurrencyCode](#CurrencyCode)||<a href="RetailDiscountEntity.md" target="_blank">Retail/RetailDiscountEntity</a>|
|[DateValidationType](#DateValidationType)||<a href="RetailDiscountEntity.md" target="_blank">Retail/RetailDiscountEntity</a>|
|[Description](#Description)||<a href="RetailDiscountEntity.md" target="_blank">Retail/RetailDiscountEntity</a>|
|[Disclaimer](#Disclaimer)||<a href="RetailDiscountEntity.md" target="_blank">Retail/RetailDiscountEntity</a>|
|[DiscountPercentValue](#DiscountPercentValue)||<a href="RetailDiscountEntity.md" target="_blank">Retail/RetailDiscountEntity</a>|
|[IsDiscountCodeRequired](#IsDiscountCodeRequired)||<a href="RetailDiscountEntity.md" target="_blank">Retail/RetailDiscountEntity</a>|
|[Name](#Name)||<a href="RetailDiscountEntity.md" target="_blank">Retail/RetailDiscountEntity</a>|
|[OfferId](#OfferId)||<a href="RetailDiscountEntity.md" target="_blank">Retail/RetailDiscountEntity</a>|
|[PeriodicDiscountType](#PeriodicDiscountType)||<a href="RetailDiscountEntity.md" target="_blank">Retail/RetailDiscountEntity</a>|
|[Status](#Status)||<a href="RetailDiscountEntity.md" target="_blank">Retail/RetailDiscountEntity</a>|
|[ValidationPeriodId](#ValidationPeriodId)||<a href="RetailDiscountEntity.md" target="_blank">Retail/RetailDiscountEntity</a>|
|[ValidFrom](#ValidFrom)||<a href="RetailDiscountEntity.md" target="_blank">Retail/RetailDiscountEntity</a>|
|[ValidTo](#ValidTo)||<a href="RetailDiscountEntity.md" target="_blank">Retail/RetailDiscountEntity</a>|
|[MultibuyDiscountType](#MultibuyDiscountType)||<a href="RetailDiscountEntity.md" target="_blank">Retail/RetailDiscountEntity</a>|
|[ThresholdCountNonDiscountItems](#ThresholdCountNonDiscountItems)||<a href="RetailDiscountEntity.md" target="_blank">Retail/RetailDiscountEntity</a>|
|[MixAndMatchDealPrice](#MixAndMatchDealPrice)||<a href="RetailDiscountEntity.md" target="_blank">Retail/RetailDiscountEntity</a>|
|[MixAndMatchDiscountAmount](#MixAndMatchDiscountAmount)||<a href="RetailDiscountEntity.md" target="_blank">Retail/RetailDiscountEntity</a>|
|[MixAndMatchDiscountType](#MixAndMatchDiscountType)||<a href="RetailDiscountEntity.md" target="_blank">Retail/RetailDiscountEntity</a>|
|[MixAndMatchNoOfLeastExpensiveLines](#MixAndMatchNoOfLeastExpensiveLines)||<a href="RetailDiscountEntity.md" target="_blank">Retail/RetailDiscountEntity</a>|
|[MixAndMatchNumberOfTimesApplicable](#MixAndMatchNumberOfTimesApplicable)||<a href="RetailDiscountEntity.md" target="_blank">Retail/RetailDiscountEntity</a>|
|[MixAndMatchLeastExpensiveMode](#MixAndMatchLeastExpensiveMode)||<a href="RetailDiscountEntity.md" target="_blank">Retail/RetailDiscountEntity</a>|
|[DiscountCode](#DiscountCode)||<a href="RetailDiscountEntity.md" target="_blank">Retail/RetailDiscountEntity</a>|
|[BarCode](#BarCode)||<a href="RetailDiscountEntity.md" target="_blank">Retail/RetailDiscountEntity</a>|
|[DiscountCodeId](#DiscountCodeId)||<a href="RetailDiscountEntity.md" target="_blank">Retail/RetailDiscountEntity</a>|
|[DiscountLedgerDimensionDisplayValue](#DiscountLedgerDimensionDisplayValue)||<a href="RetailDiscountEntity.md" target="_blank">Retail/RetailDiscountEntity</a>|
|[DiscountLedgerDimension](#DiscountLedgerDimension)||<a href="RetailDiscountEntity.md" target="_blank">Retail/RetailDiscountEntity</a>|
|[DiscountRecordId](#DiscountRecordId)||<a href="RetailDiscountEntity.md" target="_blank">Retail/RetailDiscountEntity</a>|
|[OfferQuantityLimit](#OfferQuantityLimit)||<a href="RetailDiscountEntity.md" target="_blank">Retail/RetailDiscountEntity</a>|
|[PrintDescriptionOnFiscalReceipt](#PrintDescriptionOnFiscalReceipt)||<a href="RetailDiscountEntity.md" target="_blank">Retail/RetailDiscountEntity</a>|
|[PricingPriorityNumber](#PricingPriorityNumber)||<a href="RetailDiscountEntity.md" target="_blank">Retail/RetailDiscountEntity</a>|
|[BackingTable_RetailPeriodicDiscountRelationshipId](#BackingTable_RetailPeriodicDiscountRelationshipId)||<a href="RetailDiscountEntity.md" target="_blank">Retail/RetailDiscountEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="RetailDiscountEntity.md" target="_blank">Retail/RetailDiscountEntity</a>|

### <a href=#ConcurrencyMode name="ConcurrencyMode">ConcurrencyMode</a>

First included in: Retail/RetailDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConcurrencyMode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: Retail/RetailDiscountEntity (this entity)  

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

### <a href=#DateValidationType name="DateValidationType">DateValidationType</a>

First included in: Retail/RetailDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DateValidationType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: Retail/RetailDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Disclaimer name="Disclaimer">Disclaimer</a>

First included in: Retail/RetailDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Disclaimer attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscountPercentValue name="DiscountPercentValue">DiscountPercentValue</a>

First included in: Retail/RetailDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountPercentValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsDiscountCodeRequired name="IsDiscountCodeRequired">IsDiscountCodeRequired</a>

First included in: Retail/RetailDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDiscountCodeRequired attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: Retail/RetailDiscountEntity (this entity)  

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

### <a href=#OfferId name="OfferId">OfferId</a>

First included in: Retail/RetailDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OfferId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PeriodicDiscountType name="PeriodicDiscountType">PeriodicDiscountType</a>

First included in: Retail/RetailDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodicDiscountType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Status name="Status">Status</a>

First included in: Retail/RetailDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Status attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidationPeriodId name="ValidationPeriodId">ValidationPeriodId</a>

First included in: Retail/RetailDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidationPeriodId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidFrom name="ValidFrom">ValidFrom</a>

First included in: Retail/RetailDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidTo name="ValidTo">ValidTo</a>

First included in: Retail/RetailDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MultibuyDiscountType name="MultibuyDiscountType">MultibuyDiscountType</a>

First included in: Retail/RetailDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MultibuyDiscountType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThresholdCountNonDiscountItems name="ThresholdCountNonDiscountItems">ThresholdCountNonDiscountItems</a>

First included in: Retail/RetailDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThresholdCountNonDiscountItems attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MixAndMatchDealPrice name="MixAndMatchDealPrice">MixAndMatchDealPrice</a>

First included in: Retail/RetailDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MixAndMatchDealPrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MixAndMatchDiscountAmount name="MixAndMatchDiscountAmount">MixAndMatchDiscountAmount</a>

First included in: Retail/RetailDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MixAndMatchDiscountAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MixAndMatchDiscountType name="MixAndMatchDiscountType">MixAndMatchDiscountType</a>

First included in: Retail/RetailDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MixAndMatchDiscountType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MixAndMatchNoOfLeastExpensiveLines name="MixAndMatchNoOfLeastExpensiveLines">MixAndMatchNoOfLeastExpensiveLines</a>

First included in: Retail/RetailDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MixAndMatchNoOfLeastExpensiveLines attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MixAndMatchNumberOfTimesApplicable name="MixAndMatchNumberOfTimesApplicable">MixAndMatchNumberOfTimesApplicable</a>

First included in: Retail/RetailDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MixAndMatchNumberOfTimesApplicable attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MixAndMatchLeastExpensiveMode name="MixAndMatchLeastExpensiveMode">MixAndMatchLeastExpensiveMode</a>

First included in: Retail/RetailDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MixAndMatchLeastExpensiveMode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscountCode name="DiscountCode">DiscountCode</a>

First included in: Retail/RetailDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BarCode name="BarCode">BarCode</a>

First included in: Retail/RetailDiscountEntity (this entity)  

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

### <a href=#DiscountCodeId name="DiscountCodeId">DiscountCodeId</a>

First included in: Retail/RetailDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountCodeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscountLedgerDimensionDisplayValue name="DiscountLedgerDimensionDisplayValue">DiscountLedgerDimensionDisplayValue</a>

First included in: Retail/RetailDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscountLedgerDimension name="DiscountLedgerDimension">DiscountLedgerDimension</a>

First included in: Retail/RetailDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscountRecordId name="DiscountRecordId">DiscountRecordId</a>

First included in: Retail/RetailDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountRecordId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OfferQuantityLimit name="OfferQuantityLimit">OfferQuantityLimit</a>

First included in: Retail/RetailDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OfferQuantityLimit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PrintDescriptionOnFiscalReceipt name="PrintDescriptionOnFiscalReceipt">PrintDescriptionOnFiscalReceipt</a>

First included in: Retail/RetailDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrintDescriptionOnFiscalReceipt attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PricingPriorityNumber name="PricingPriorityNumber">PricingPriorityNumber</a>

First included in: Retail/RetailDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PricingPriorityNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_RetailPeriodicDiscountRelationshipId name="BackingTable_RetailPeriodicDiscountRelationshipId">BackingTable_RetailPeriodicDiscountRelationshipId</a>

First included in: Retail/RetailDiscountEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailPeriodicDiscountRelationshipId attribute are listed below.</summary>

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

First included in: Retail/RetailDiscountEntity (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
