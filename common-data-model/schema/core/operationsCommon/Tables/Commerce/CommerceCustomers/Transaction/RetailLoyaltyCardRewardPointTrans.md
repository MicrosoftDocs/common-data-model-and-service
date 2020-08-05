---
title: RetailLoyaltyCardRewardPointTrans in Transaction - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Loyalty transaction in Transaction(RetailLoyaltyCardRewardPointTrans)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Commerce/CommerceCustomers/Transaction/RetailLoyaltyCardRewardPointTrans.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailLoyaltyCardRewardPointTrans/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Loyalty transaction</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailLoyaltyCardRewardPointTrans.md" target="_blank">Transaction/RetailLoyaltyCardRewardPointTrans</a>|
|[AdjustmentId](#AdjustmentId)||<a href="RetailLoyaltyCardRewardPointTrans.md" target="_blank">Transaction/RetailLoyaltyCardRewardPointTrans</a>|
|[Affiliation](#Affiliation)||<a href="RetailLoyaltyCardRewardPointTrans.md" target="_blank">Transaction/RetailLoyaltyCardRewardPointTrans</a>|
|[CardNumber](#CardNumber)||<a href="RetailLoyaltyCardRewardPointTrans.md" target="_blank">Transaction/RetailLoyaltyCardRewardPointTrans</a>|
|[Channel](#Channel)||<a href="RetailLoyaltyCardRewardPointTrans.md" target="_blank">Transaction/RetailLoyaltyCardRewardPointTrans</a>|
|[CustAccount](#CustAccount)||<a href="RetailLoyaltyCardRewardPointTrans.md" target="_blank">Transaction/RetailLoyaltyCardRewardPointTrans</a>|
|[CustAccountDataAreaId](#CustAccountDataAreaId)||<a href="RetailLoyaltyCardRewardPointTrans.md" target="_blank">Transaction/RetailLoyaltyCardRewardPointTrans</a>|
|[EntryDate](#EntryDate)||<a href="RetailLoyaltyCardRewardPointTrans.md" target="_blank">Transaction/RetailLoyaltyCardRewardPointTrans</a>|
|[EntryTime](#EntryTime)||<a href="RetailLoyaltyCardRewardPointTrans.md" target="_blank">Transaction/RetailLoyaltyCardRewardPointTrans</a>|
|[EntryType](#EntryType)||<a href="RetailLoyaltyCardRewardPointTrans.md" target="_blank">Transaction/RetailLoyaltyCardRewardPointTrans</a>|
|[ExpirationDate](#ExpirationDate)||<a href="RetailLoyaltyCardRewardPointTrans.md" target="_blank">Transaction/RetailLoyaltyCardRewardPointTrans</a>|
|[LoyaltyTier](#LoyaltyTier)||<a href="RetailLoyaltyCardRewardPointTrans.md" target="_blank">Transaction/RetailLoyaltyCardRewardPointTrans</a>|
|[LoyaltyTransactionType](#LoyaltyTransactionType)||<a href="RetailLoyaltyCardRewardPointTrans.md" target="_blank">Transaction/RetailLoyaltyCardRewardPointTrans</a>|
|[loyaltyTransDataAreaId](#loyaltyTransDataAreaId)||<a href="RetailLoyaltyCardRewardPointTrans.md" target="_blank">Transaction/RetailLoyaltyCardRewardPointTrans</a>|
|[LoyaltyTransLineNum](#LoyaltyTransLineNum)||<a href="RetailLoyaltyCardRewardPointTrans.md" target="_blank">Transaction/RetailLoyaltyCardRewardPointTrans</a>|
|[ReceiptId](#ReceiptId)||<a href="RetailLoyaltyCardRewardPointTrans.md" target="_blank">Transaction/RetailLoyaltyCardRewardPointTrans</a>|
|[Remaining](#Remaining)||<a href="RetailLoyaltyCardRewardPointTrans.md" target="_blank">Transaction/RetailLoyaltyCardRewardPointTrans</a>|
|[RewardPoint](#RewardPoint)||<a href="RetailLoyaltyCardRewardPointTrans.md" target="_blank">Transaction/RetailLoyaltyCardRewardPointTrans</a>|
|[RewardPointAmountQty](#RewardPointAmountQty)||<a href="RetailLoyaltyCardRewardPointTrans.md" target="_blank">Transaction/RetailLoyaltyCardRewardPointTrans</a>|
|[SalesId](#SalesId)||<a href="RetailLoyaltyCardRewardPointTrans.md" target="_blank">Transaction/RetailLoyaltyCardRewardPointTrans</a>|
|[StaffId](#StaffId)||<a href="RetailLoyaltyCardRewardPointTrans.md" target="_blank">Transaction/RetailLoyaltyCardRewardPointTrans</a>|
|[storeId](#storeId)||<a href="RetailLoyaltyCardRewardPointTrans.md" target="_blank">Transaction/RetailLoyaltyCardRewardPointTrans</a>|
|[terminalId](#terminalId)||<a href="RetailLoyaltyCardRewardPointTrans.md" target="_blank">Transaction/RetailLoyaltyCardRewardPointTrans</a>|
|[transactionId](#transactionId)||<a href="RetailLoyaltyCardRewardPointTrans.md" target="_blank">Transaction/RetailLoyaltyCardRewardPointTrans</a>|
|[RetailTransactionSalesTransLineNum](#RetailTransactionSalesTransLineNum)||<a href="RetailLoyaltyCardRewardPointTrans.md" target="_blank">Transaction/RetailLoyaltyCardRewardPointTrans</a>|
|[SalesLineLineNum](#SalesLineLineNum)||<a href="RetailLoyaltyCardRewardPointTrans.md" target="_blank">Transaction/RetailLoyaltyCardRewardPointTrans</a>|
|[StartDate](#StartDate)||<a href="RetailLoyaltyCardRewardPointTrans.md" target="_blank">Transaction/RetailLoyaltyCardRewardPointTrans</a>|
|[CardTenderType](#CardTenderType)||<a href="RetailLoyaltyCardRewardPointTrans.md" target="_blank">Transaction/RetailLoyaltyCardRewardPointTrans</a>|
|[NonTransactionalActivityId](#NonTransactionalActivityId)||<a href="RetailLoyaltyCardRewardPointTrans.md" target="_blank">Transaction/RetailLoyaltyCardRewardPointTrans</a>|
|[LoyaltyOtherActivityTypeId](#LoyaltyOtherActivityTypeId)||<a href="RetailLoyaltyCardRewardPointTrans.md" target="_blank">Transaction/RetailLoyaltyCardRewardPointTrans</a>|
|[Relationship_CustTableRelationshipId](#Relationship_CustTableRelationshipId)||<a href="RetailLoyaltyCardRewardPointTrans.md" target="_blank">Transaction/RetailLoyaltyCardRewardPointTrans</a>|
|[Relationship_RetailAffiliationRelationshipId](#Relationship_RetailAffiliationRelationshipId)||<a href="RetailLoyaltyCardRewardPointTrans.md" target="_blank">Transaction/RetailLoyaltyCardRewardPointTrans</a>|
|[Relationship_RetailChannelTableRelationshipId](#Relationship_RetailChannelTableRelationshipId)||<a href="RetailLoyaltyCardRewardPointTrans.md" target="_blank">Transaction/RetailLoyaltyCardRewardPointTrans</a>|
|[Relationship_RetailLoyaltyCardRelationshipId](#Relationship_RetailLoyaltyCardRelationshipId)||<a href="RetailLoyaltyCardRewardPointTrans.md" target="_blank">Transaction/RetailLoyaltyCardRewardPointTrans</a>|
|[Relationship_RetailLoyaltyCardRewardPointAdjustmentRelationshipId](#Relationship_RetailLoyaltyCardRewardPointAdjustmentRelationshipId)||<a href="RetailLoyaltyCardRewardPointTrans.md" target="_blank">Transaction/RetailLoyaltyCardRewardPointTrans</a>|
|[Relationship_RetailLoyaltyRewardPointRelationshipId](#Relationship_RetailLoyaltyRewardPointRelationshipId)||<a href="RetailLoyaltyCardRewardPointTrans.md" target="_blank">Transaction/RetailLoyaltyCardRewardPointTrans</a>|
|[Relationship_RetailLoyaltyTierRelationshipId](#Relationship_RetailLoyaltyTierRelationshipId)||<a href="RetailLoyaltyCardRewardPointTrans.md" target="_blank">Transaction/RetailLoyaltyCardRewardPointTrans</a>|
|[Relationship_RetailStoreTableRelationshipId](#Relationship_RetailStoreTableRelationshipId)||<a href="RetailLoyaltyCardRewardPointTrans.md" target="_blank">Transaction/RetailLoyaltyCardRewardPointTrans</a>|
|[Relationship_RetailTerminalTableRelationshipId](#Relationship_RetailTerminalTableRelationshipId)||<a href="RetailLoyaltyCardRewardPointTrans.md" target="_blank">Transaction/RetailLoyaltyCardRewardPointTrans</a>|
|[Relationship_RetailTransactionLoyaltyRewardPointTransRelationshipId](#Relationship_RetailTransactionLoyaltyRewardPointTransRelationshipId)||<a href="RetailLoyaltyCardRewardPointTrans.md" target="_blank">Transaction/RetailLoyaltyCardRewardPointTrans</a>|
|[Relationship_RetailTransactionTableRelationshipId](#Relationship_RetailTransactionTableRelationshipId)||<a href="RetailLoyaltyCardRewardPointTrans.md" target="_blank">Transaction/RetailLoyaltyCardRewardPointTrans</a>|
|[Relationship_SalesTableRelationshipId](#Relationship_SalesTableRelationshipId)||<a href="RetailLoyaltyCardRewardPointTrans.md" target="_blank">Transaction/RetailLoyaltyCardRewardPointTrans</a>|
|[Relationship_RetailTransactionSalesTransRelationshipId](#Relationship_RetailTransactionSalesTransRelationshipId)||<a href="RetailLoyaltyCardRewardPointTrans.md" target="_blank">Transaction/RetailLoyaltyCardRewardPointTrans</a>|
|[Relationship_SalesLineRelationshipId](#Relationship_SalesLineRelationshipId)||<a href="RetailLoyaltyCardRewardPointTrans.md" target="_blank">Transaction/RetailLoyaltyCardRewardPointTrans</a>|
|[Relationship_RetailLoyaltyOtherActivityTypeRelationshipId](#Relationship_RetailLoyaltyOtherActivityTypeRelationshipId)||<a href="RetailLoyaltyCardRewardPointTrans.md" target="_blank">Transaction/RetailLoyaltyCardRewardPointTrans</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/RetailLoyaltyCardRewardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailLoyaltyCardRewardPointTrans/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AdjustmentId name="AdjustmentId">AdjustmentId</a>

First included in: Transaction/RetailLoyaltyCardRewardPointTrans (this entity)  

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

### <a href=#Affiliation name="Affiliation">Affiliation</a>

First included in: Transaction/RetailLoyaltyCardRewardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Affiliation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CardNumber name="CardNumber">CardNumber</a>

First included in: Transaction/RetailLoyaltyCardRewardPointTrans (this entity)  

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

First included in: Transaction/RetailLoyaltyCardRewardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Channel attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CustAccount name="CustAccount">CustAccount</a>

First included in: Transaction/RetailLoyaltyCardRewardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustAccountDataAreaId name="CustAccountDataAreaId">CustAccountDataAreaId</a>

First included in: Transaction/RetailLoyaltyCardRewardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustAccountDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EntryDate name="EntryDate">EntryDate</a>

First included in: Transaction/RetailLoyaltyCardRewardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EntryDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#EntryTime name="EntryTime">EntryTime</a>

First included in: Transaction/RetailLoyaltyCardRewardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EntryTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.time**  
</details>

### <a href=#EntryType name="EntryType">EntryType</a>

First included in: Transaction/RetailLoyaltyCardRewardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EntryType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ExpirationDate name="ExpirationDate">ExpirationDate</a>

First included in: Transaction/RetailLoyaltyCardRewardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpirationDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#LoyaltyTier name="LoyaltyTier">LoyaltyTier</a>

First included in: Transaction/RetailLoyaltyCardRewardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoyaltyTier attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LoyaltyTransactionType name="LoyaltyTransactionType">LoyaltyTransactionType</a>

First included in: Transaction/RetailLoyaltyCardRewardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoyaltyTransactionType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#loyaltyTransDataAreaId name="loyaltyTransDataAreaId">loyaltyTransDataAreaId</a>

First included in: Transaction/RetailLoyaltyCardRewardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the loyaltyTransDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LoyaltyTransLineNum name="LoyaltyTransLineNum">LoyaltyTransLineNum</a>

First included in: Transaction/RetailLoyaltyCardRewardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoyaltyTransLineNum attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ReceiptId name="ReceiptId">ReceiptId</a>

First included in: Transaction/RetailLoyaltyCardRewardPointTrans (this entity)  

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

First included in: Transaction/RetailLoyaltyCardRewardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Remaining attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#RewardPoint name="RewardPoint">RewardPoint</a>

First included in: Transaction/RetailLoyaltyCardRewardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reward point ID</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RewardPoint attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reward point ID</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RewardPointAmountQty name="RewardPointAmountQty">RewardPointAmountQty</a>

First included in: Transaction/RetailLoyaltyCardRewardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RewardPointAmountQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SalesId name="SalesId">SalesId</a>

First included in: Transaction/RetailLoyaltyCardRewardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StaffId name="StaffId">StaffId</a>

First included in: Transaction/RetailLoyaltyCardRewardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StaffId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#storeId name="storeId">storeId</a>

First included in: Transaction/RetailLoyaltyCardRewardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the storeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#terminalId name="terminalId">terminalId</a>

First included in: Transaction/RetailLoyaltyCardRewardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the terminalId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#transactionId name="transactionId">transactionId</a>

First included in: Transaction/RetailLoyaltyCardRewardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the transactionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailTransactionSalesTransLineNum name="RetailTransactionSalesTransLineNum">RetailTransactionSalesTransLineNum</a>

First included in: Transaction/RetailLoyaltyCardRewardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailTransactionSalesTransLineNum attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SalesLineLineNum name="SalesLineLineNum">SalesLineLineNum</a>

First included in: Transaction/RetailLoyaltyCardRewardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesLineLineNum attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#StartDate name="StartDate">StartDate</a>

First included in: Transaction/RetailLoyaltyCardRewardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#CardTenderType name="CardTenderType">CardTenderType</a>

First included in: Transaction/RetailLoyaltyCardRewardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CardTenderType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#NonTransactionalActivityId name="NonTransactionalActivityId">NonTransactionalActivityId</a>

First included in: Transaction/RetailLoyaltyCardRewardPointTrans (this entity)  

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

First included in: Transaction/RetailLoyaltyCardRewardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoyaltyOtherActivityTypeId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_CustTableRelationshipId name="Relationship_CustTableRelationshipId">Relationship_CustTableRelationshipId</a>

First included in: Transaction/RetailLoyaltyCardRewardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Customer/Main/CustTable.md" target="_blank">/core/operationsCommon/Tables/Common/Customer/Main/CustTable.cdm.json/CustTable</a></td><td><a href="../../../Common/Customer/Main/CustTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailAffiliationRelationshipId name="Relationship_RetailAffiliationRelationshipId">Relationship_RetailAffiliationRelationshipId</a>

First included in: Transaction/RetailLoyaltyCardRewardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailAffiliationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/RetailAffiliation.md" target="_blank">/core/operationsCommon/Tables/Commerce/CommerceCustomers/Miscellaneous/RetailAffiliation.cdm.json/RetailAffiliation</a></td><td><a href="../Miscellaneous/RetailAffiliation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailChannelTableRelationshipId name="Relationship_RetailChannelTableRelationshipId">Relationship_RetailChannelTableRelationshipId</a>

First included in: Transaction/RetailLoyaltyCardRewardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailChannelTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ChannelManagement/Main/RetailChannelTable.md" target="_blank">/core/operationsCommon/Tables/Commerce/ChannelManagement/Main/RetailChannelTable.cdm.json/RetailChannelTable</a></td><td><a href="../../ChannelManagement/Main/RetailChannelTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailLoyaltyCardRelationshipId name="Relationship_RetailLoyaltyCardRelationshipId">Relationship_RetailLoyaltyCardRelationshipId</a>

First included in: Transaction/RetailLoyaltyCardRewardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailLoyaltyCardRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/RetailLoyaltyCard.md" target="_blank">/core/operationsCommon/Tables/Commerce/CommerceCustomers/Miscellaneous/RetailLoyaltyCard.cdm.json/RetailLoyaltyCard</a></td><td><a href="../Miscellaneous/RetailLoyaltyCard.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailLoyaltyCardRewardPointAdjustmentRelationshipId name="Relationship_RetailLoyaltyCardRewardPointAdjustmentRelationshipId">Relationship_RetailLoyaltyCardRewardPointAdjustmentRelationshipId</a>

First included in: Transaction/RetailLoyaltyCardRewardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailLoyaltyCardRewardPointAdjustmentRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/RetailLoyaltyCardRewardPointAdjustment.md" target="_blank">/core/operationsCommon/Tables/Commerce/CommerceCustomers/Miscellaneous/RetailLoyaltyCardRewardPointAdjustment.cdm.json/RetailLoyaltyCardRewardPointAdjustment</a></td><td><a href="../Miscellaneous/RetailLoyaltyCardRewardPointAdjustment.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailLoyaltyRewardPointRelationshipId name="Relationship_RetailLoyaltyRewardPointRelationshipId">Relationship_RetailLoyaltyRewardPointRelationshipId</a>

First included in: Transaction/RetailLoyaltyCardRewardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailLoyaltyRewardPointRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/RetailLoyaltyRewardPoint.md" target="_blank">/core/operationsCommon/Tables/Commerce/CommerceCustomers/Miscellaneous/RetailLoyaltyRewardPoint.cdm.json/RetailLoyaltyRewardPoint</a></td><td><a href="../Miscellaneous/RetailLoyaltyRewardPoint.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailLoyaltyTierRelationshipId name="Relationship_RetailLoyaltyTierRelationshipId">Relationship_RetailLoyaltyTierRelationshipId</a>

First included in: Transaction/RetailLoyaltyCardRewardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailLoyaltyTierRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/RetailLoyaltyTier.md" target="_blank">/core/operationsCommon/Tables/Commerce/CommerceCustomers/Miscellaneous/RetailLoyaltyTier.cdm.json/RetailLoyaltyTier</a></td><td><a href="../Miscellaneous/RetailLoyaltyTier.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailStoreTableRelationshipId name="Relationship_RetailStoreTableRelationshipId">Relationship_RetailStoreTableRelationshipId</a>

First included in: Transaction/RetailLoyaltyCardRewardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailStoreTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ChannelManagement/BrickAndMortarStore/Main/RetailStoreTable.md" target="_blank">/core/operationsCommon/Tables/Commerce/ChannelManagement/BrickAndMortarStore/Main/RetailStoreTable.cdm.json/RetailStoreTable</a></td><td><a href="../../ChannelManagement/BrickAndMortarStore/Main/RetailStoreTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailTerminalTableRelationshipId name="Relationship_RetailTerminalTableRelationshipId">Relationship_RetailTerminalTableRelationshipId</a>

First included in: Transaction/RetailLoyaltyCardRewardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailTerminalTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../ChannelManagement/BrickAndMortarStore/Main/RetailTerminalTable.md" target="_blank">/core/operationsCommon/Tables/Commerce/ChannelManagement/BrickAndMortarStore/Main/RetailTerminalTable.cdm.json/RetailTerminalTable</a></td><td><a href="../../ChannelManagement/BrickAndMortarStore/Main/RetailTerminalTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailTransactionLoyaltyRewardPointTransRelationshipId name="Relationship_RetailTransactionLoyaltyRewardPointTransRelationshipId">Relationship_RetailTransactionLoyaltyRewardPointTransRelationshipId</a>

First included in: Transaction/RetailLoyaltyCardRewardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailTransactionLoyaltyRewardPointTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../TransactionsAndOrders/Transaction/RetailTransactionLoyaltyRewardPointTrans.md" target="_blank">/core/operationsCommon/Tables/Commerce/TransactionsAndOrders/Transaction/RetailTransactionLoyaltyRewardPointTrans.cdm.json/RetailTransactionLoyaltyRewardPointTrans</a></td><td><a href="../../TransactionsAndOrders/Transaction/RetailTransactionLoyaltyRewardPointTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailTransactionTableRelationshipId name="Relationship_RetailTransactionTableRelationshipId">Relationship_RetailTransactionTableRelationshipId</a>

First included in: Transaction/RetailLoyaltyCardRewardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailTransactionTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../TransactionsAndOrders/Transaction/RetailTransactionTable.md" target="_blank">/core/operationsCommon/Tables/Commerce/TransactionsAndOrders/Transaction/RetailTransactionTable.cdm.json/RetailTransactionTable</a></td><td><a href="../../TransactionsAndOrders/Transaction/RetailTransactionTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SalesTableRelationshipId name="Relationship_SalesTableRelationshipId">Relationship_SalesTableRelationshipId</a>

First included in: Transaction/RetailLoyaltyCardRewardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SalesTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/SalesAndMarketing/WorksheetHeader/SalesTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/WorksheetHeader/SalesTable.cdm.json/SalesTable</a></td><td><a href="../../../SupplyChain/SalesAndMarketing/WorksheetHeader/SalesTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailTransactionSalesTransRelationshipId name="Relationship_RetailTransactionSalesTransRelationshipId">Relationship_RetailTransactionSalesTransRelationshipId</a>

First included in: Transaction/RetailLoyaltyCardRewardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailTransactionSalesTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../TransactionsAndOrders/Transaction/RetailTransactionSalesTrans.md" target="_blank">/core/operationsCommon/Tables/Commerce/TransactionsAndOrders/Transaction/RetailTransactionSalesTrans.cdm.json/RetailTransactionSalesTrans</a></td><td><a href="../../TransactionsAndOrders/Transaction/RetailTransactionSalesTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SalesLineRelationshipId name="Relationship_SalesLineRelationshipId">Relationship_SalesLineRelationshipId</a>

First included in: Transaction/RetailLoyaltyCardRewardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SalesLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../SupplyChain/SalesAndMarketing/WorksheetLine/SalesLine.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/WorksheetLine/SalesLine.cdm.json/SalesLine</a></td><td><a href="../../../SupplyChain/SalesAndMarketing/WorksheetLine/SalesLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailLoyaltyOtherActivityTypeRelationshipId name="Relationship_RetailLoyaltyOtherActivityTypeRelationshipId">Relationship_RetailLoyaltyOtherActivityTypeRelationshipId</a>

First included in: Transaction/RetailLoyaltyCardRewardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailLoyaltyOtherActivityTypeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/RetailLoyaltyOtherActivityType.md" target="_blank">/core/operationsCommon/Tables/Commerce/CommerceCustomers/Miscellaneous/RetailLoyaltyOtherActivityType.cdm.json/RetailLoyaltyOtherActivityType</a></td><td><a href="../Miscellaneous/RetailLoyaltyOtherActivityType.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
