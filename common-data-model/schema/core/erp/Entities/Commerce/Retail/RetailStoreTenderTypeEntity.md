---
title: RetailStoreTenderTypeEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/16/2020
ms.author: nebanfic
---

# @Retail:StoreTenderTypeEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Entities/Commerce/Retail/RetailStoreTenderTypeEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.Application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>@Retail:StoreTenderTypeEntity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Entity|
|---|---|---|
|[RetailChannelId](#RetailChannelId)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[PaymentMethodNumber](#PaymentMethodNumber)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[ChangeTenderId](#ChangeTenderId)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[AboveMinimumTenderId](#AboveMinimumTenderId)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[AccountType](#AccountType)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[AccountTypeGiftCardCompany](#AccountTypeGiftCardCompany)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[ActiveAccount](#ActiveAccount)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[AllowFloat](#AllowFloat)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[AllowOvertender](#AllowOvertender)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[AllowReturnNegative](#AllowReturnNegative)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[AllowUndertender](#AllowUndertender)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[AskForDate](#AskForDate)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[BankBagAccountType](#BankBagAccountType)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[ChangeLineOnReceipt](#ChangeLineOnReceipt)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[CheckPayee](#CheckPayee)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[CompressPaymentEntries](#CompressPaymentEntries)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[CountingRequired](#CountingRequired)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[EndorseCheck](#EndorseCheck)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[EndorsmentLine1](#EndorsmentLine1)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[EndorsmentLine2](#EndorsmentLine2)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[FrontOfCheck](#FrontOfCheck)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[Function](#Function)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[GiftCardCompany](#GiftCardCompany)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[LineNumInTransaction](#LineNumInTransaction)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[MaxCountingDifference](#MaxCountingDifference)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[MaximumAmountAllowed](#MaximumAmountAllowed)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[MaximumAmountEntered](#MaximumAmountEntered)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[MaximumOvertenderAmount](#MaximumOvertenderAmount)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[MaxNormalDifferenceAmount](#MaxNormalDifferenceAmount)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[MaxRecount](#MaxRecount)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[MinimumAmountAllowed](#MinimumAmountAllowed)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[MinimumAmountEntered](#MinimumAmountEntered)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[MinimumChangeAmount](#MinimumChangeAmount)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[MultiplyInTenderOperations](#MultiplyInTenderOperations)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[Name](#Name)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[OpenDrawer](#OpenDrawer)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[SignatureCaptureMinAmount](#SignatureCaptureMinAmount)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[PayAccountBill](#PayAccountBill)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[PaymTermId](#PaymTermId)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[PosCountEntries](#PosCountEntries)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[PosOperation](#PosOperation)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[Rounding](#Rounding)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[RoundingMethod](#RoundingMethod)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[SafeAccLedgerDimension](#SafeAccLedgerDimension)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[SafeAccountType](#SafeAccountType)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[SafeActiveAccount](#SafeActiveAccount)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[SeekAuthorization](#SeekAuthorization)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[SigCapEnabled](#SigCapEnabled)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[SlipBackInPrinter](#SlipBackInPrinter)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[SlipFrontInPrinter](#SlipFrontInPrinter)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[TakenToBank](#TakenToBank)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[TakenToSafe](#TakenToSafe)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[UndertenderAmount](#UndertenderAmount)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[DefaultDimensionDisplayValue](#DefaultDimensionDisplayValue)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[BankBagLedgerDimensionDisplayValue](#BankBagLedgerDimensionDisplayValue)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[DiffAccBigDiffLedgerDimensionDisplayValue](#DiffAccBigDiffLedgerDimensionDisplayValue)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[DifferenceAccLedgerDimensionDisplayValue](#DifferenceAccLedgerDimensionDisplayValue)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[LedgerDimensionDisplayValue](#LedgerDimensionDisplayValue)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[LedgerDimensionGiftCardCompanyDisplayValue](#LedgerDimensionGiftCardCompanyDisplayValue)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[SafeAccLedgerDimensionDisplayValue](#SafeAccLedgerDimensionDisplayValue)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[BankBagLedgerDimension](#BankBagLedgerDimension)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[DefaultDimension](#DefaultDimension)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[DiffAccBigDiffLedgerDimension](#DiffAccBigDiffLedgerDimension)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[DifferenceAccLedgerDimension](#DifferenceAccLedgerDimension)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[LedgerDimension](#LedgerDimension)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[LedgerDimensionGiftCardCompany](#LedgerDimensionGiftCardCompany)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[GiftCardItemId](#GiftCardItemId)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[ConnectorName](#ConnectorName)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[HideCardInputDetailsInPOS](#HideCardInputDetailsInPOS)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[TenderFlowLedgerDimension](#TenderFlowLedgerDimension)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[TenderFlowLedgerDimensionDisplayValue](#TenderFlowLedgerDimensionDisplayValue)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[GiftCardCashOutThreshold](#GiftCardCashOutThreshold)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[Relationship_DefaultDimensionDimensionSetRelationshipId](#Relationship_DefaultDimensionDimensionSetRelationshipId)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[Relationship_BankBagLedgerDimensionCombinationRelationshipId](#Relationship_BankBagLedgerDimensionCombinationRelationshipId)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[Relationship_DiffAccBigDiffLedgerDimensionCombinationRelationshipId](#Relationship_DiffAccBigDiffLedgerDimensionCombinationRelationshipId)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[Relationship_DifferenceAccLedgerDimensionCombinationRelationshipId](#Relationship_DifferenceAccLedgerDimensionCombinationRelationshipId)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[Relationship_LedgerDimensionCombinationRelationshipId](#Relationship_LedgerDimensionCombinationRelationshipId)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[Relationship_LedgerDimensionGiftCardCompanyCombinationRelationshipId](#Relationship_LedgerDimensionGiftCardCompanyCombinationRelationshipId)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[Relationship_SafeAccLedgerDimensionCombinationRelationshipId](#Relationship_SafeAccLedgerDimensionCombinationRelationshipId)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[Relationship_RetailStoreEntityRelationshipId](#Relationship_RetailStoreEntityRelationshipId)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[Relationship_RetailOnlineChannelEntityRelationshipId](#Relationship_RetailOnlineChannelEntityRelationshipId)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[Relationship_RetailCallCenterEntityRelationshipId](#Relationship_RetailCallCenterEntityRelationshipId)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[BackingTable_RetailStoreTenderTypeTableRelationshipId](#BackingTable_RetailStoreTenderTypeTableRelationshipId)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="RetailStoreTenderTypeEntity.md" target="_blank">Retail/RetailStoreTenderTypeEntity</a>|

### <a href=#RetailChannelId name="RetailChannelId">RetailChannelId</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailChannelId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentMethodNumber name="PaymentMethodNumber">PaymentMethodNumber</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentMethodNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChangeTenderId name="ChangeTenderId">ChangeTenderId</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChangeTenderId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AboveMinimumTenderId name="AboveMinimumTenderId">AboveMinimumTenderId</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AboveMinimumTenderId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountType name="AccountType">AccountType</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountTypeGiftCardCompany name="AccountTypeGiftCardCompany">AccountTypeGiftCardCompany</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountTypeGiftCardCompany attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActiveAccount name="ActiveAccount">ActiveAccount</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActiveAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowFloat name="AllowFloat">AllowFloat</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowFloat attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowOvertender name="AllowOvertender">AllowOvertender</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowOvertender attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowReturnNegative name="AllowReturnNegative">AllowReturnNegative</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowReturnNegative attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowUndertender name="AllowUndertender">AllowUndertender</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowUndertender attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AskForDate name="AskForDate">AskForDate</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AskForDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankBagAccountType name="BankBagAccountType">BankBagAccountType</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankBagAccountType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChangeLineOnReceipt name="ChangeLineOnReceipt">ChangeLineOnReceipt</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChangeLineOnReceipt attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CheckPayee name="CheckPayee">CheckPayee</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CheckPayee attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompressPaymentEntries name="CompressPaymentEntries">CompressPaymentEntries</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompressPaymentEntries attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CountingRequired name="CountingRequired">CountingRequired</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CountingRequired attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EndorseCheck name="EndorseCheck">EndorseCheck</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndorseCheck attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EndorsmentLine1 name="EndorsmentLine1">EndorsmentLine1</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndorsmentLine1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EndorsmentLine2 name="EndorsmentLine2">EndorsmentLine2</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndorsmentLine2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FrontOfCheck name="FrontOfCheck">FrontOfCheck</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FrontOfCheck attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Function name="Function">Function</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Function attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GiftCardCompany name="GiftCardCompany">GiftCardCompany</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiftCardCompany attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumInTransaction name="LineNumInTransaction">LineNumInTransaction</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNumInTransaction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaxCountingDifference name="MaxCountingDifference">MaxCountingDifference</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxCountingDifference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumAmountAllowed name="MaximumAmountAllowed">MaximumAmountAllowed</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumAmountAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumAmountEntered name="MaximumAmountEntered">MaximumAmountEntered</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumAmountEntered attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumOvertenderAmount name="MaximumOvertenderAmount">MaximumOvertenderAmount</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumOvertenderAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaxNormalDifferenceAmount name="MaxNormalDifferenceAmount">MaxNormalDifferenceAmount</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxNormalDifferenceAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaxRecount name="MaxRecount">MaxRecount</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxRecount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinimumAmountAllowed name="MinimumAmountAllowed">MinimumAmountAllowed</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumAmountAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinimumAmountEntered name="MinimumAmountEntered">MinimumAmountEntered</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumAmountEntered attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinimumChangeAmount name="MinimumChangeAmount">MinimumChangeAmount</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumChangeAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MultiplyInTenderOperations name="MultiplyInTenderOperations">MultiplyInTenderOperations</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MultiplyInTenderOperations attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OpenDrawer name="OpenDrawer">OpenDrawer</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OpenDrawer attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SignatureCaptureMinAmount name="SignatureCaptureMinAmount">SignatureCaptureMinAmount</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SignatureCaptureMinAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayAccountBill name="PayAccountBill">PayAccountBill</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayAccountBill attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymTermId name="PaymTermId">PaymTermId</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymTermId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PosCountEntries name="PosCountEntries">PosCountEntries</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PosCountEntries attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PosOperation name="PosOperation">PosOperation</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PosOperation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Rounding name="Rounding">Rounding</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Rounding attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RoundingMethod name="RoundingMethod">RoundingMethod</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RoundingMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SafeAccLedgerDimension name="SafeAccLedgerDimension">SafeAccLedgerDimension</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SafeAccLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SafeAccountType name="SafeAccountType">SafeAccountType</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SafeAccountType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SafeActiveAccount name="SafeActiveAccount">SafeActiveAccount</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SafeActiveAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SeekAuthorization name="SeekAuthorization">SeekAuthorization</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SeekAuthorization attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SigCapEnabled name="SigCapEnabled">SigCapEnabled</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SigCapEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SlipBackInPrinter name="SlipBackInPrinter">SlipBackInPrinter</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SlipBackInPrinter attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SlipFrontInPrinter name="SlipFrontInPrinter">SlipFrontInPrinter</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SlipFrontInPrinter attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TakenToBank name="TakenToBank">TakenToBank</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TakenToBank attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TakenToSafe name="TakenToSafe">TakenToSafe</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TakenToSafe attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UndertenderAmount name="UndertenderAmount">UndertenderAmount</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UndertenderAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimensionDisplayValue name="DefaultDimensionDisplayValue">DefaultDimensionDisplayValue</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankBagLedgerDimensionDisplayValue name="BankBagLedgerDimensionDisplayValue">BankBagLedgerDimensionDisplayValue</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankBagLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiffAccBigDiffLedgerDimensionDisplayValue name="DiffAccBigDiffLedgerDimensionDisplayValue">DiffAccBigDiffLedgerDimensionDisplayValue</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiffAccBigDiffLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DifferenceAccLedgerDimensionDisplayValue name="DifferenceAccLedgerDimensionDisplayValue">DifferenceAccLedgerDimensionDisplayValue</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DifferenceAccLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerDimensionDisplayValue name="LedgerDimensionDisplayValue">LedgerDimensionDisplayValue</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerDimensionGiftCardCompanyDisplayValue name="LedgerDimensionGiftCardCompanyDisplayValue">LedgerDimensionGiftCardCompanyDisplayValue</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerDimensionGiftCardCompanyDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SafeAccLedgerDimensionDisplayValue name="SafeAccLedgerDimensionDisplayValue">SafeAccLedgerDimensionDisplayValue</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SafeAccLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankBagLedgerDimension name="BankBagLedgerDimension">BankBagLedgerDimension</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankBagLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimension name="DefaultDimension">DefaultDimension</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiffAccBigDiffLedgerDimension name="DiffAccBigDiffLedgerDimension">DiffAccBigDiffLedgerDimension</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiffAccBigDiffLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DifferenceAccLedgerDimension name="DifferenceAccLedgerDimension">DifferenceAccLedgerDimension</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DifferenceAccLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerDimension name="LedgerDimension">LedgerDimension</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerDimensionGiftCardCompany name="LedgerDimensionGiftCardCompany">LedgerDimensionGiftCardCompany</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerDimensionGiftCardCompany attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GiftCardItemId name="GiftCardItemId">GiftCardItemId</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiftCardItemId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConnectorName name="ConnectorName">ConnectorName</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConnectorName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HideCardInputDetailsInPOS name="HideCardInputDetailsInPOS">HideCardInputDetailsInPOS</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HideCardInputDetailsInPOS attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TenderFlowLedgerDimension name="TenderFlowLedgerDimension">TenderFlowLedgerDimension</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TenderFlowLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TenderFlowLedgerDimensionDisplayValue name="TenderFlowLedgerDimensionDisplayValue">TenderFlowLedgerDimensionDisplayValue</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TenderFlowLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GiftCardCashOutThreshold name="GiftCardCashOutThreshold">GiftCardCashOutThreshold</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiftCardCashOutThreshold attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultDimensionDimensionSetRelationshipId name="Relationship_DefaultDimensionDimensionSetRelationshipId">Relationship_DefaultDimensionDimensionSetRelationshipId</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>6</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultDimensionDimensionSetRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_BankBagLedgerDimensionCombinationRelationshipId name="Relationship_BankBagLedgerDimensionCombinationRelationshipId">Relationship_BankBagLedgerDimensionCombinationRelationshipId</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>6</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BankBagLedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DiffAccBigDiffLedgerDimensionCombinationRelationshipId name="Relationship_DiffAccBigDiffLedgerDimensionCombinationRelationshipId">Relationship_DiffAccBigDiffLedgerDimensionCombinationRelationshipId</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>6</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DiffAccBigDiffLedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_DifferenceAccLedgerDimensionCombinationRelationshipId name="Relationship_DifferenceAccLedgerDimensionCombinationRelationshipId">Relationship_DifferenceAccLedgerDimensionCombinationRelationshipId</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>6</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DifferenceAccLedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_LedgerDimensionCombinationRelationshipId name="Relationship_LedgerDimensionCombinationRelationshipId">Relationship_LedgerDimensionCombinationRelationshipId</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>6</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_LedgerDimensionGiftCardCompanyCombinationRelationshipId name="Relationship_LedgerDimensionGiftCardCompanyCombinationRelationshipId">Relationship_LedgerDimensionGiftCardCompanyCombinationRelationshipId</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>6</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerDimensionGiftCardCompanyCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_SafeAccLedgerDimensionCombinationRelationshipId name="Relationship_SafeAccLedgerDimensionCombinationRelationshipId">Relationship_SafeAccLedgerDimensionCombinationRelationshipId</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>6</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SafeAccLedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_RetailStoreEntityRelationshipId name="Relationship_RetailStoreEntityRelationshipId">Relationship_RetailStoreEntityRelationshipId</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>6</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailStoreEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_RetailOnlineChannelEntityRelationshipId name="Relationship_RetailOnlineChannelEntityRelationshipId">Relationship_RetailOnlineChannelEntityRelationshipId</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>6</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailOnlineChannelEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_RetailCallCenterEntityRelationshipId name="Relationship_RetailCallCenterEntityRelationshipId">Relationship_RetailCallCenterEntityRelationshipId</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>6</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailCallCenterEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_RetailStoreTenderTypeTableRelationshipId name="BackingTable_RetailStoreTenderTypeTableRelationshipId">BackingTable_RetailStoreTenderTypeTableRelationshipId</a>

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>6</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailStoreTenderTypeTableRelationshipId attribute are listed below.</summary>

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

First included in: Retail/RetailStoreTenderTypeEntity (this entity)  

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
