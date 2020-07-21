---
title: RetailStoreTenderTypeTableEntity in Payments - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/21/2020
ms.author: nebanfic
---

# Store payment methods for POS designer in Payments(RetailStoreTenderTypeTableEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Commerce/Payments/RetailStoreTenderTypeTableEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Store payment methods for POS designer</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ChangeTenderId](#ChangeTenderId)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[AboveMinimumTenderId](#AboveMinimumTenderId)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[AccountType](#AccountType)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[AccountTypeGiftCardCompany](#AccountTypeGiftCardCompany)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[ActiveAccount](#ActiveAccount)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[AllowFloat](#AllowFloat)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[AllowOvertender](#AllowOvertender)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[AllowReturnNegative](#AllowReturnNegative)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[AllowUndertender](#AllowUndertender)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[AskForDate](#AskForDate)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[BankBagAccountType](#BankBagAccountType)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[BankBagLedgerDimension](#BankBagLedgerDimension)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[BankBagLedgerDimensionDisplayValue](#BankBagLedgerDimensionDisplayValue)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[ChangeLineOnReceipt](#ChangeLineOnReceipt)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[Channel](#Channel)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[CheckPayee](#CheckPayee)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[CompressPaymentEntries](#CompressPaymentEntries)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[CountingRequired](#CountingRequired)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[DefaultDimension](#DefaultDimension)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[DefaultDimensionDisplayValue](#DefaultDimensionDisplayValue)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[DiffAccBigDiffLedgerDimension](#DiffAccBigDiffLedgerDimension)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[DiffAccBigDiffLedgerDimensionDisplayValue](#DiffAccBigDiffLedgerDimensionDisplayValue)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[DifferenceAccLedgerDimension](#DifferenceAccLedgerDimension)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[DifferenceAccLedgerDimensionDisplayValue](#DifferenceAccLedgerDimensionDisplayValue)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[EndorseCheck](#EndorseCheck)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[EndorsmentLine1](#EndorsmentLine1)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[EndorsmentLine2](#EndorsmentLine2)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[FiscalPrinterTenderType_BR](#FiscalPrinterTenderType_BR)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[FrontOfCheck](#FrontOfCheck)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[Function](#Function)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[GiftCardCompany](#GiftCardCompany)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[LedgerDimension](#LedgerDimension)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[LedgerDimensionDisplayValue](#LedgerDimensionDisplayValue)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[LedgerDimensionGiftCardCompany](#LedgerDimensionGiftCardCompany)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[LedgerDimensionGiftCardCompanyDisplayValue](#LedgerDimensionGiftCardCompanyDisplayValue)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[LineNumInTransaction](#LineNumInTransaction)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[MaximumCountingDifference](#MaximumCountingDifference)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[MaximumAmountAllowed](#MaximumAmountAllowed)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[MaximumAmountEntered](#MaximumAmountEntered)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[MaximumOvertenderAmount](#MaximumOvertenderAmount)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[MaximumNormalDifferenceAmount](#MaximumNormalDifferenceAmount)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[MaximumRecount](#MaximumRecount)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[MinimumAmountAllowed](#MinimumAmountAllowed)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[MinimumAmountEntered](#MinimumAmountEntered)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[MinimumChangeAmount](#MinimumChangeAmount)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[MultiplyInTenderOperations](#MultiplyInTenderOperations)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[Name](#Name)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[OpenDrawer](#OpenDrawer)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[PayAccountBill](#PayAccountBill)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[PaymentTerminalId](#PaymentTerminalId)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[PosCountEntries](#PosCountEntries)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[PosOperation](#PosOperation)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[Rounding](#Rounding)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[RoundingMethod](#RoundingMethod)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[SafeAccLedgerDimension](#SafeAccLedgerDimension)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[SafeAccLedgerDimensionDisplayValue](#SafeAccLedgerDimensionDisplayValue)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[SafeAccountType](#SafeAccountType)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[SafeActiveAccount](#SafeActiveAccount)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[SeekAuthorization](#SeekAuthorization)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[SigCapEnabled](#SigCapEnabled)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[SigCapMinAmount](#SigCapMinAmount)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[SlipBackInPrinter](#SlipBackInPrinter)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[SlipFrontInPrinter](#SlipFrontInPrinter)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[TakenToBank](#TakenToBank)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[TakenToSafe](#TakenToSafe)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[TenderTypeId](#TenderTypeId)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[UndertenderAmount](#UndertenderAmount)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[RetailChannelTable_OMOperatingUnitID](#RetailChannelTable_OMOperatingUnitID)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[OMOperatingUnit_PartyNumber](#OMOperatingUnit_PartyNumber)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[OMOperatingUnitNumber](#OMOperatingUnitNumber)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[GiftCardItemId](#GiftCardItemId)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[ConnectorName](#ConnectorName)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[HideCardInputDetailsInPOS](#HideCardInputDetailsInPOS)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[CashDrawerLimit](#CashDrawerLimit)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[CashDrawerLimitEnabled](#CashDrawerLimitEnabled)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[TenderFlowLedgerDimension](#TenderFlowLedgerDimension)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[TenderFlowLedgerDimensionDisplayValue](#TenderFlowLedgerDimensionDisplayValue)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[GiftCardCashOutThreshold](#GiftCardCashOutThreshold)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[RestrictReturnsWithoutReceipt](#RestrictReturnsWithoutReceipt)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[Relationship_DefaultDimensionDimensionSetRelationshipId](#Relationship_DefaultDimensionDimensionSetRelationshipId)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[Relationship_RetailCallCenterEntityRelationshipId](#Relationship_RetailCallCenterEntityRelationshipId)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[BackingTable_RetailStoreTenderTypeTableRelationshipId](#BackingTable_RetailStoreTenderTypeTableRelationshipId)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="RetailStoreTenderTypeTableEntity.md" target="_blank">Payments/RetailStoreTenderTypeTableEntity</a>|

### <a href=#ChangeTenderId name="ChangeTenderId">ChangeTenderId</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Change tender</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChangeTenderId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Change tender</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AboveMinimumTenderId name="AboveMinimumTenderId">AboveMinimumTenderId</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Above minimum change tender</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AboveMinimumTenderId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Above minimum change tender</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountType name="AccountType">AccountType</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountTypeGiftCardCompany name="AccountTypeGiftCardCompany">AccountTypeGiftCardCompany</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountTypeGiftCardCompany attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActiveAccount name="ActiveAccount">ActiveAccount</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Use bank account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActiveAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Use bank account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowFloat name="AllowFloat">AllowFloat</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowFloat attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowOvertender name="AllowOvertender">AllowOvertender</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowOvertender attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowReturnNegative name="AllowReturnNegative">AllowReturnNegative</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowReturnNegative attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowUndertender name="AllowUndertender">AllowUndertender</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowUndertender attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AskForDate name="AskForDate">AskForDate</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AskForDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankBagAccountType name="BankBagAccountType">BankBagAccountType</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankBagAccountType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankBagLedgerDimension name="BankBagLedgerDimension">BankBagLedgerDimension</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Account number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankBagLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Account number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BankBagLedgerDimensionDisplayValue name="BankBagLedgerDimensionDisplayValue">BankBagLedgerDimensionDisplayValue</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BankBagLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChangeLineOnReceipt name="ChangeLineOnReceipt">ChangeLineOnReceipt</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChangeLineOnReceipt attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Channel name="Channel">Channel</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Channel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CheckPayee name="CheckPayee">CheckPayee</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CheckPayee attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompressPaymentEntries name="CompressPaymentEntries">CompressPaymentEntries</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompressPaymentEntries attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CountingRequired name="CountingRequired">CountingRequired</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CountingRequired attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimension name="DefaultDimension">DefaultDimension</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultDimensionDisplayValue name="DefaultDimensionDisplayValue">DefaultDimensionDisplayValue</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiffAccBigDiffLedgerDimension name="DiffAccBigDiffLedgerDimension">DiffAccBigDiffLedgerDimension</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Big difference account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiffAccBigDiffLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Big difference account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiffAccBigDiffLedgerDimensionDisplayValue name="DiffAccBigDiffLedgerDimensionDisplayValue">DiffAccBigDiffLedgerDimensionDisplayValue</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiffAccBigDiffLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DifferenceAccLedgerDimension name="DifferenceAccLedgerDimension">DifferenceAccLedgerDimension</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Difference account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DifferenceAccLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Difference account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DifferenceAccLedgerDimensionDisplayValue name="DifferenceAccLedgerDimensionDisplayValue">DifferenceAccLedgerDimensionDisplayValue</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DifferenceAccLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EndorseCheck name="EndorseCheck">EndorseCheck</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Endorse check</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndorseCheck attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Endorse check</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EndorsmentLine1 name="EndorsmentLine1">EndorsmentLine1</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Endorsement line 1</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndorsmentLine1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Endorsement line 1</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EndorsmentLine2 name="EndorsmentLine2">EndorsmentLine2</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Endorsement line 2</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndorsmentLine2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Endorsement line 2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FiscalPrinterTenderType_BR name="FiscalPrinterTenderType_BR">FiscalPrinterTenderType_BR</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalPrinterTenderType_BR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FrontOfCheck name="FrontOfCheck">FrontOfCheck</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FrontOfCheck attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Function name="Function">Function</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Function attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GiftCardCompany name="GiftCardCompany">GiftCardCompany</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Gift card company</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiftCardCompany attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Gift card company</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerDimension name="LedgerDimension">LedgerDimension</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Account number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Account number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerDimensionDisplayValue name="LedgerDimensionDisplayValue">LedgerDimensionDisplayValue</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerDimensionGiftCardCompany name="LedgerDimensionGiftCardCompany">LedgerDimensionGiftCardCompany</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Account number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerDimensionGiftCardCompany attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Account number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerDimensionGiftCardCompanyDisplayValue name="LedgerDimensionGiftCardCompanyDisplayValue">LedgerDimensionGiftCardCompanyDisplayValue</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerDimensionGiftCardCompanyDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumInTransaction name="LineNumInTransaction">LineNumInTransaction</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNumInTransaction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumCountingDifference name="MaximumCountingDifference">MaximumCountingDifference</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumCountingDifference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumAmountAllowed name="MaximumAmountAllowed">MaximumAmountAllowed</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Maximum amount allowed</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumAmountAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Maximum amount allowed</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumAmountEntered name="MaximumAmountEntered">MaximumAmountEntered</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumAmountEntered attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumOvertenderAmount name="MaximumOvertenderAmount">MaximumOvertenderAmount</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumOvertenderAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumNormalDifferenceAmount name="MaximumNormalDifferenceAmount">MaximumNormalDifferenceAmount</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumNormalDifferenceAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumRecount name="MaximumRecount">MaximumRecount</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumRecount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinimumAmountAllowed name="MinimumAmountAllowed">MinimumAmountAllowed</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Minimum amount allowed</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumAmountAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Minimum amount allowed</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinimumAmountEntered name="MinimumAmountEntered">MinimumAmountEntered</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Minimum amount entered</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumAmountEntered attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Minimum amount entered</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinimumChangeAmount name="MinimumChangeAmount">MinimumChangeAmount</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumChangeAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MultiplyInTenderOperations name="MultiplyInTenderOperations">MultiplyInTenderOperations</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MultiplyInTenderOperations attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OpenDrawer name="OpenDrawer">OpenDrawer</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OpenDrawer attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayAccountBill name="PayAccountBill">PayAccountBill</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayAccountBill attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentTerminalId name="PaymentTerminalId">PaymentTerminalId</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentTerminalId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PosCountEntries name="PosCountEntries">PosCountEntries</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PosCountEntries attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PosOperation name="PosOperation">PosOperation</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PosOperation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Rounding name="Rounding">Rounding</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Rounding attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RoundingMethod name="RoundingMethod">RoundingMethod</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RoundingMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SafeAccLedgerDimension name="SafeAccLedgerDimension">SafeAccLedgerDimension</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Safe account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SafeAccLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Safe account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SafeAccLedgerDimensionDisplayValue name="SafeAccLedgerDimensionDisplayValue">SafeAccLedgerDimensionDisplayValue</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SafeAccLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SafeAccountType name="SafeAccountType">SafeAccountType</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SafeAccountType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SafeActiveAccount name="SafeActiveAccount">SafeActiveAccount</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Use safe account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SafeActiveAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Use safe account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SeekAuthorization name="SeekAuthorization">SeekAuthorization</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SeekAuthorization attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SigCapEnabled name="SigCapEnabled">SigCapEnabled</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SigCapEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SigCapMinAmount name="SigCapMinAmount">SigCapMinAmount</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SigCapMinAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SlipBackInPrinter name="SlipBackInPrinter">SlipBackInPrinter</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Slip back in printer</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SlipBackInPrinter attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Slip back in printer</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SlipFrontInPrinter name="SlipFrontInPrinter">SlipFrontInPrinter</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Slip front in printer</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SlipFrontInPrinter attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Slip front in printer</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TakenToBank name="TakenToBank">TakenToBank</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TakenToBank attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TakenToSafe name="TakenToSafe">TakenToSafe</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TakenToSafe attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TenderTypeId name="TenderTypeId">TenderTypeId</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TenderTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UndertenderAmount name="UndertenderAmount">UndertenderAmount</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UndertenderAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailChannelTable_OMOperatingUnitID name="RetailChannelTable_OMOperatingUnitID">RetailChannelTable_OMOperatingUnitID</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailChannelTable_OMOperatingUnitID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OMOperatingUnit_PartyNumber name="OMOperatingUnit_PartyNumber">OMOperatingUnit_PartyNumber</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OMOperatingUnit_PartyNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OMOperatingUnitNumber name="OMOperatingUnitNumber">OMOperatingUnitNumber</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OMOperatingUnitNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GiftCardItemId name="GiftCardItemId">GiftCardItemId</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiftCardItemId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ConnectorName name="ConnectorName">ConnectorName</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ConnectorName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HideCardInputDetailsInPOS name="HideCardInputDetailsInPOS">HideCardInputDetailsInPOS</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HideCardInputDetailsInPOS attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashDrawerLimit name="CashDrawerLimit">CashDrawerLimit</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDrawerLimit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CashDrawerLimitEnabled name="CashDrawerLimitEnabled">CashDrawerLimitEnabled</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CashDrawerLimitEnabled attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TenderFlowLedgerDimension name="TenderFlowLedgerDimension">TenderFlowLedgerDimension</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TenderFlowLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TenderFlowLedgerDimensionDisplayValue name="TenderFlowLedgerDimensionDisplayValue">TenderFlowLedgerDimensionDisplayValue</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Offset account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TenderFlowLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Offset account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GiftCardCashOutThreshold name="GiftCardCashOutThreshold">GiftCardCashOutThreshold</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GiftCardCashOutThreshold attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RestrictReturnsWithoutReceipt name="RestrictReturnsWithoutReceipt">RestrictReturnsWithoutReceipt</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RestrictReturnsWithoutReceipt attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultDimensionDimensionSetRelationshipId name="Relationship_DefaultDimensionDimensionSetRelationshipId">Relationship_DefaultDimensionDimensionSetRelationshipId</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

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

### <a href=#Relationship_RetailCallCenterEntityRelationshipId name="Relationship_RetailCallCenterEntityRelationshipId">Relationship_RetailCallCenterEntityRelationshipId</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

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

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailStoreTenderTypeTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Commerce/Payments/Main/RetailStoreTenderTypeTable.md" target="_blank">/core/operationsCommon/Tables/Commerce/Payments/Main/RetailStoreTenderTypeTable.cdm.json/RetailStoreTenderTypeTable</a></td><td><a href="../../../Tables/Commerce/Payments/Main/RetailStoreTenderTypeTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: Payments/RetailStoreTenderTypeTableEntity (this entity)  

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
