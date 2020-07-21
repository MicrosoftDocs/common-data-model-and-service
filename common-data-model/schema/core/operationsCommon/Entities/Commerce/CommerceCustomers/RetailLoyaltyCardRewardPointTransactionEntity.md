---
title: RetailLoyaltyCardRewardPointTransactionEntity in CommerceCustomers - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/21/2020
ms.author: nebanfic
---

# Loyalty transaction in CommerceCustomers(RetailLoyaltyCardRewardPointTransactionEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Commerce/CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Loyalty transaction</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AdjustmentId](#AdjustmentId)||<a href="RetailLoyaltyCardRewardPointTransactionEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity</a>|
|[LoyaltyProgram](#LoyaltyProgram)||<a href="RetailLoyaltyCardRewardPointTransactionEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity</a>|
|[CardNumber](#CardNumber)||<a href="RetailLoyaltyCardRewardPointTransactionEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity</a>|
|[Channel](#Channel)||<a href="RetailLoyaltyCardRewardPointTransactionEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity</a>|
|[CustomerAccount](#CustomerAccount)||<a href="RetailLoyaltyCardRewardPointTransactionEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity</a>|
|[CustomerAccountCompany](#CustomerAccountCompany)||<a href="RetailLoyaltyCardRewardPointTransactionEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity</a>|
|[EntryDate](#EntryDate)||<a href="RetailLoyaltyCardRewardPointTransactionEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity</a>|
|[EntryTime](#EntryTime)||<a href="RetailLoyaltyCardRewardPointTransactionEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity</a>|
|[EntryType](#EntryType)||<a href="RetailLoyaltyCardRewardPointTransactionEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity</a>|
|[ExpirationDate](#ExpirationDate)||<a href="RetailLoyaltyCardRewardPointTransactionEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity</a>|
|[LoyaltyTier](#LoyaltyTier)||<a href="RetailLoyaltyCardRewardPointTransactionEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity</a>|
|[LoyaltyTransactionType](#LoyaltyTransactionType)||<a href="RetailLoyaltyCardRewardPointTransactionEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity</a>|
|[LoyaltyTransactionCompany](#LoyaltyTransactionCompany)||<a href="RetailLoyaltyCardRewardPointTransactionEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity</a>|
|[LoyaltyTransactionLineNumber](#LoyaltyTransactionLineNumber)||<a href="RetailLoyaltyCardRewardPointTransactionEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity</a>|
|[ReceiptId](#ReceiptId)||<a href="RetailLoyaltyCardRewardPointTransactionEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity</a>|
|[Remaining](#Remaining)||<a href="RetailLoyaltyCardRewardPointTransactionEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity</a>|
|[RewardPoint](#RewardPoint)||<a href="RetailLoyaltyCardRewardPointTransactionEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity</a>|
|[RewardPointAmountQty](#RewardPointAmountQty)||<a href="RetailLoyaltyCardRewardPointTransactionEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity</a>|
|[SalesOrderId](#SalesOrderId)||<a href="RetailLoyaltyCardRewardPointTransactionEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity</a>|
|[OperatorId](#OperatorId)||<a href="RetailLoyaltyCardRewardPointTransactionEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity</a>|
|[Terminal](#Terminal)||<a href="RetailLoyaltyCardRewardPointTransactionEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity</a>|
|[TransactionNumber](#TransactionNumber)||<a href="RetailLoyaltyCardRewardPointTransactionEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity</a>|
|[LoyaltyProgramName](#LoyaltyProgramName)||<a href="RetailLoyaltyCardRewardPointTransactionEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity</a>|
|[ChannelOperatingUnitId](#ChannelOperatingUnitId)||<a href="RetailLoyaltyCardRewardPointTransactionEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity</a>|
|[OperatingUnitNumber](#OperatingUnitNumber)||<a href="RetailLoyaltyCardRewardPointTransactionEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity</a>|
|[RewardPointId](#RewardPointId)||<a href="RetailLoyaltyCardRewardPointTransactionEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity</a>|
|[LoyaltyTierLoyaltyProgram](#LoyaltyTierLoyaltyProgram)||<a href="RetailLoyaltyCardRewardPointTransactionEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity</a>|
|[LoyaltyTierId](#LoyaltyTierId)||<a href="RetailLoyaltyCardRewardPointTransactionEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity</a>|
|[LoyaltyTierLoyaltyProgramName](#LoyaltyTierLoyaltyProgramName)||<a href="RetailLoyaltyCardRewardPointTransactionEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity</a>|
|[RetailTransactionSalesTransLineNum](#RetailTransactionSalesTransLineNum)||<a href="RetailLoyaltyCardRewardPointTransactionEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity</a>|
|[SalesLineLineNum](#SalesLineLineNum)||<a href="RetailLoyaltyCardRewardPointTransactionEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity</a>|
|[StartDate](#StartDate)||<a href="RetailLoyaltyCardRewardPointTransactionEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity</a>|
|[CardTenderType](#CardTenderType)||<a href="RetailLoyaltyCardRewardPointTransactionEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity</a>|
|[NonTransactionalActivityId](#NonTransactionalActivityId)||<a href="RetailLoyaltyCardRewardPointTransactionEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity</a>|
|[LoyaltyOtherActivityTypeId](#LoyaltyOtherActivityTypeId)||<a href="RetailLoyaltyCardRewardPointTransactionEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity</a>|
|[LoyaltyOtherActivityTypeName](#LoyaltyOtherActivityTypeName)||<a href="RetailLoyaltyCardRewardPointTransactionEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity</a>|
|[BackingTable_RetailLoyaltyCardRewardPointTransRelationshipId](#BackingTable_RetailLoyaltyCardRewardPointTransRelationshipId)||<a href="RetailLoyaltyCardRewardPointTransactionEntity.md" target="_blank">CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity</a>|

### <a href=#AdjustmentId name="AdjustmentId">AdjustmentId</a>

First included in: CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AdjustmentId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LoyaltyProgram name="LoyaltyProgram">LoyaltyProgram</a>

First included in: CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoyaltyProgram attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CardNumber name="CardNumber">CardNumber</a>

First included in: CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CardNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Channel name="Channel">Channel</a>

First included in: CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity (this entity)  

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

### <a href=#CustomerAccount name="CustomerAccount">CustomerAccount</a>

First included in: CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerAccountCompany name="CustomerAccountCompany">CustomerAccountCompany</a>

First included in: CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerAccountCompany attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EntryDate name="EntryDate">EntryDate</a>

First included in: CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EntryDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EntryTime name="EntryTime">EntryTime</a>

First included in: CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EntryTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EntryType name="EntryType">EntryType</a>

First included in: CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EntryType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExpirationDate name="ExpirationDate">ExpirationDate</a>

First included in: CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpirationDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LoyaltyTier name="LoyaltyTier">LoyaltyTier</a>

First included in: CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoyaltyTier attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LoyaltyTransactionType name="LoyaltyTransactionType">LoyaltyTransactionType</a>

First included in: CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoyaltyTransactionType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LoyaltyTransactionCompany name="LoyaltyTransactionCompany">LoyaltyTransactionCompany</a>

First included in: CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoyaltyTransactionCompany attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LoyaltyTransactionLineNumber name="LoyaltyTransactionLineNumber">LoyaltyTransactionLineNumber</a>

First included in: CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoyaltyTransactionLineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReceiptId name="ReceiptId">ReceiptId</a>

First included in: CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceiptId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Remaining name="Remaining">Remaining</a>

First included in: CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Remaining attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RewardPoint name="RewardPoint">RewardPoint</a>

First included in: CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RewardPoint attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RewardPointAmountQty name="RewardPointAmountQty">RewardPointAmountQty</a>

First included in: CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RewardPointAmountQty attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesOrderId name="SalesOrderId">SalesOrderId</a>

First included in: CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesOrderId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperatorId name="OperatorId">OperatorId</a>

First included in: CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperatorId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Terminal name="Terminal">Terminal</a>

First included in: CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Terminal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionNumber name="TransactionNumber">TransactionNumber</a>

First included in: CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LoyaltyProgramName name="LoyaltyProgramName">LoyaltyProgramName</a>

First included in: CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoyaltyProgramName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChannelOperatingUnitId name="ChannelOperatingUnitId">ChannelOperatingUnitId</a>

First included in: CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChannelOperatingUnitId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperatingUnitNumber name="OperatingUnitNumber">OperatingUnitNumber</a>

First included in: CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperatingUnitNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RewardPointId name="RewardPointId">RewardPointId</a>

First included in: CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RewardPointId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LoyaltyTierLoyaltyProgram name="LoyaltyTierLoyaltyProgram">LoyaltyTierLoyaltyProgram</a>

First included in: CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoyaltyTierLoyaltyProgram attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LoyaltyTierId name="LoyaltyTierId">LoyaltyTierId</a>

First included in: CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoyaltyTierId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LoyaltyTierLoyaltyProgramName name="LoyaltyTierLoyaltyProgramName">LoyaltyTierLoyaltyProgramName</a>

First included in: CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoyaltyTierLoyaltyProgramName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailTransactionSalesTransLineNum name="RetailTransactionSalesTransLineNum">RetailTransactionSalesTransLineNum</a>

First included in: CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailTransactionSalesTransLineNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesLineLineNum name="SalesLineLineNum">SalesLineLineNum</a>

First included in: CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesLineLineNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StartDate name="StartDate">StartDate</a>

First included in: CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CardTenderType name="CardTenderType">CardTenderType</a>

First included in: CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CardTenderType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NonTransactionalActivityId name="NonTransactionalActivityId">NonTransactionalActivityId</a>

First included in: CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NonTransactionalActivityId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LoyaltyOtherActivityTypeId name="LoyaltyOtherActivityTypeId">LoyaltyOtherActivityTypeId</a>

First included in: CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoyaltyOtherActivityTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LoyaltyOtherActivityTypeName name="LoyaltyOtherActivityTypeName">LoyaltyOtherActivityTypeName</a>

First included in: CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoyaltyOtherActivityTypeName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_RetailLoyaltyCardRewardPointTransRelationshipId name="BackingTable_RetailLoyaltyCardRewardPointTransRelationshipId">BackingTable_RetailLoyaltyCardRewardPointTransRelationshipId</a>

First included in: CommerceCustomers/RetailLoyaltyCardRewardPointTransactionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailLoyaltyCardRewardPointTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Commerce/CommerceCustomers/Transaction/RetailLoyaltyCardRewardPointTrans.md" target="_blank">/core/operationsCommon/Tables/Commerce/CommerceCustomers/Transaction/RetailLoyaltyCardRewardPointTrans.cdm.json/RetailLoyaltyCardRewardPointTrans</a></td><td><a href="../../../Tables/Commerce/CommerceCustomers/Transaction/RetailLoyaltyCardRewardPointTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
