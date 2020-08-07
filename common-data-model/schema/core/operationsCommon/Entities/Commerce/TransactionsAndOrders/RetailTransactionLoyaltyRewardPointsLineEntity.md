---
title: RetailTransactionLoyaltyRewardPointsLineEntity in TransactionsAndOrders - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Loyalty reward point transaction in TransactionsAndOrders(RetailTransactionLoyaltyRewardPointsLineEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Commerce/TransactionsAndOrders/RetailTransactionLoyaltyRewardPointsLineEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Loyalty reward point transaction</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[AffiliationId](#AffiliationId)||<a href="RetailTransactionLoyaltyRewardPointsLineEntity.md" target="_blank">TransactionsAndOrders/RetailTransactionLoyaltyRewardPointsLineEntity</a>|
|[LoyaltyCardNumber](#LoyaltyCardNumber)||<a href="RetailTransactionLoyaltyRewardPointsLineEntity.md" target="_blank">TransactionsAndOrders/RetailTransactionLoyaltyRewardPointsLineEntity</a>|
|[Channel](#Channel)||<a href="RetailTransactionLoyaltyRewardPointsLineEntity.md" target="_blank">TransactionsAndOrders/RetailTransactionLoyaltyRewardPointsLineEntity</a>|
|[CustomerAccountNumber](#CustomerAccountNumber)||<a href="RetailTransactionLoyaltyRewardPointsLineEntity.md" target="_blank">TransactionsAndOrders/RetailTransactionLoyaltyRewardPointsLineEntity</a>|
|[EntryDate](#EntryDate)||<a href="RetailTransactionLoyaltyRewardPointsLineEntity.md" target="_blank">TransactionsAndOrders/RetailTransactionLoyaltyRewardPointsLineEntity</a>|
|[EntryTime](#EntryTime)||<a href="RetailTransactionLoyaltyRewardPointsLineEntity.md" target="_blank">TransactionsAndOrders/RetailTransactionLoyaltyRewardPointsLineEntity</a>|
|[EntryType](#EntryType)||<a href="RetailTransactionLoyaltyRewardPointsLineEntity.md" target="_blank">TransactionsAndOrders/RetailTransactionLoyaltyRewardPointsLineEntity</a>|
|[ExpirationDate](#ExpirationDate)||<a href="RetailTransactionLoyaltyRewardPointsLineEntity.md" target="_blank">TransactionsAndOrders/RetailTransactionLoyaltyRewardPointsLineEntity</a>|
|[LineNumber](#LineNumber)||<a href="RetailTransactionLoyaltyRewardPointsLineEntity.md" target="_blank">TransactionsAndOrders/RetailTransactionLoyaltyRewardPointsLineEntity</a>|
|[LoyaltyTier](#LoyaltyTier)||<a href="RetailTransactionLoyaltyRewardPointsLineEntity.md" target="_blank">TransactionsAndOrders/RetailTransactionLoyaltyRewardPointsLineEntity</a>|
|[ReceiptNumber](#ReceiptNumber)||<a href="RetailTransactionLoyaltyRewardPointsLineEntity.md" target="_blank">TransactionsAndOrders/RetailTransactionLoyaltyRewardPointsLineEntity</a>|
|[RewardPoint](#RewardPoint)||<a href="RetailTransactionLoyaltyRewardPointsLineEntity.md" target="_blank">TransactionsAndOrders/RetailTransactionLoyaltyRewardPointsLineEntity</a>|
|[RewardPoints](#RewardPoints)||<a href="RetailTransactionLoyaltyRewardPointsLineEntity.md" target="_blank">TransactionsAndOrders/RetailTransactionLoyaltyRewardPointsLineEntity</a>|
|[Terminal](#Terminal)||<a href="RetailTransactionLoyaltyRewardPointsLineEntity.md" target="_blank">TransactionsAndOrders/RetailTransactionLoyaltyRewardPointsLineEntity</a>|
|[TransactionNumber](#TransactionNumber)||<a href="RetailTransactionLoyaltyRewardPointsLineEntity.md" target="_blank">TransactionsAndOrders/RetailTransactionLoyaltyRewardPointsLineEntity</a>|
|[RetailChannelTableOMOperatingUnitID](#RetailChannelTableOMOperatingUnitID)||<a href="RetailTransactionLoyaltyRewardPointsLineEntity.md" target="_blank">TransactionsAndOrders/RetailTransactionLoyaltyRewardPointsLineEntity</a>|
|[OperatingUnitNumber](#OperatingUnitNumber)||<a href="RetailTransactionLoyaltyRewardPointsLineEntity.md" target="_blank">TransactionsAndOrders/RetailTransactionLoyaltyRewardPointsLineEntity</a>|
|[RewardPointId](#RewardPointId)||<a href="RetailTransactionLoyaltyRewardPointsLineEntity.md" target="_blank">TransactionsAndOrders/RetailTransactionLoyaltyRewardPointsLineEntity</a>|
|[LoyaltyTierAffiliationId](#LoyaltyTierAffiliationId)||<a href="RetailTransactionLoyaltyRewardPointsLineEntity.md" target="_blank">TransactionsAndOrders/RetailTransactionLoyaltyRewardPointsLineEntity</a>|
|[LoyaltyTierId](#LoyaltyTierId)||<a href="RetailTransactionLoyaltyRewardPointsLineEntity.md" target="_blank">TransactionsAndOrders/RetailTransactionLoyaltyRewardPointsLineEntity</a>|
|[LoyaltyName](#LoyaltyName)||<a href="RetailTransactionLoyaltyRewardPointsLineEntity.md" target="_blank">TransactionsAndOrders/RetailTransactionLoyaltyRewardPointsLineEntity</a>|
|[RetailTransactionSalesTransLineNum](#RetailTransactionSalesTransLineNum)||<a href="RetailTransactionLoyaltyRewardPointsLineEntity.md" target="_blank">TransactionsAndOrders/RetailTransactionLoyaltyRewardPointsLineEntity</a>|
|[BackingTable_RetailTransactionLoyaltyRewardPointTransRelationshipId](#BackingTable_RetailTransactionLoyaltyRewardPointTransRelationshipId)||<a href="RetailTransactionLoyaltyRewardPointsLineEntity.md" target="_blank">TransactionsAndOrders/RetailTransactionLoyaltyRewardPointsLineEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="RetailTransactionLoyaltyRewardPointsLineEntity.md" target="_blank">TransactionsAndOrders/RetailTransactionLoyaltyRewardPointsLineEntity</a>|

### <a href=#AffiliationId name="AffiliationId">AffiliationId</a>

First included in: TransactionsAndOrders/RetailTransactionLoyaltyRewardPointsLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AffiliationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LoyaltyCardNumber name="LoyaltyCardNumber">LoyaltyCardNumber</a>

First included in: TransactionsAndOrders/RetailTransactionLoyaltyRewardPointsLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoyaltyCardNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Channel name="Channel">Channel</a>

First included in: TransactionsAndOrders/RetailTransactionLoyaltyRewardPointsLineEntity (this entity)  

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

### <a href=#CustomerAccountNumber name="CustomerAccountNumber">CustomerAccountNumber</a>

First included in: TransactionsAndOrders/RetailTransactionLoyaltyRewardPointsLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EntryDate name="EntryDate">EntryDate</a>

First included in: TransactionsAndOrders/RetailTransactionLoyaltyRewardPointsLineEntity (this entity)  

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

First included in: TransactionsAndOrders/RetailTransactionLoyaltyRewardPointsLineEntity (this entity)  

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

First included in: TransactionsAndOrders/RetailTransactionLoyaltyRewardPointsLineEntity (this entity)  

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

First included in: TransactionsAndOrders/RetailTransactionLoyaltyRewardPointsLineEntity (this entity)  

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

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: TransactionsAndOrders/RetailTransactionLoyaltyRewardPointsLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LoyaltyTier name="LoyaltyTier">LoyaltyTier</a>

First included in: TransactionsAndOrders/RetailTransactionLoyaltyRewardPointsLineEntity (this entity)  

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

### <a href=#ReceiptNumber name="ReceiptNumber">ReceiptNumber</a>

First included in: TransactionsAndOrders/RetailTransactionLoyaltyRewardPointsLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceiptNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RewardPoint name="RewardPoint">RewardPoint</a>

First included in: TransactionsAndOrders/RetailTransactionLoyaltyRewardPointsLineEntity (this entity)  

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

### <a href=#RewardPoints name="RewardPoints">RewardPoints</a>

First included in: TransactionsAndOrders/RetailTransactionLoyaltyRewardPointsLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RewardPoints attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Terminal name="Terminal">Terminal</a>

First included in: TransactionsAndOrders/RetailTransactionLoyaltyRewardPointsLineEntity (this entity)  

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

First included in: TransactionsAndOrders/RetailTransactionLoyaltyRewardPointsLineEntity (this entity)  

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

### <a href=#RetailChannelTableOMOperatingUnitID name="RetailChannelTableOMOperatingUnitID">RetailChannelTableOMOperatingUnitID</a>

First included in: TransactionsAndOrders/RetailTransactionLoyaltyRewardPointsLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailChannelTableOMOperatingUnitID attribute are listed below.</summary>

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

### <a href=#OperatingUnitNumber name="OperatingUnitNumber">OperatingUnitNumber</a>

First included in: TransactionsAndOrders/RetailTransactionLoyaltyRewardPointsLineEntity (this entity)  

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

First included in: TransactionsAndOrders/RetailTransactionLoyaltyRewardPointsLineEntity (this entity)  

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

### <a href=#LoyaltyTierAffiliationId name="LoyaltyTierAffiliationId">LoyaltyTierAffiliationId</a>

First included in: TransactionsAndOrders/RetailTransactionLoyaltyRewardPointsLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoyaltyTierAffiliationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LoyaltyTierId name="LoyaltyTierId">LoyaltyTierId</a>

First included in: TransactionsAndOrders/RetailTransactionLoyaltyRewardPointsLineEntity (this entity)  

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

### <a href=#LoyaltyName name="LoyaltyName">LoyaltyName</a>

First included in: TransactionsAndOrders/RetailTransactionLoyaltyRewardPointsLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoyaltyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailTransactionSalesTransLineNum name="RetailTransactionSalesTransLineNum">RetailTransactionSalesTransLineNum</a>

First included in: TransactionsAndOrders/RetailTransactionLoyaltyRewardPointsLineEntity (this entity)  

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

### <a href=#BackingTable_RetailTransactionLoyaltyRewardPointTransRelationshipId name="BackingTable_RetailTransactionLoyaltyRewardPointTransRelationshipId">BackingTable_RetailTransactionLoyaltyRewardPointTransRelationshipId</a>

First included in: TransactionsAndOrders/RetailTransactionLoyaltyRewardPointsLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailTransactionLoyaltyRewardPointTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Commerce/TransactionsAndOrders/Transaction/RetailTransactionLoyaltyRewardPointTrans.md" target="_blank">/core/operationsCommon/Tables/Commerce/TransactionsAndOrders/Transaction/RetailTransactionLoyaltyRewardPointTrans.cdm.json/RetailTransactionLoyaltyRewardPointTrans</a></td><td><a href="../../../Tables/Commerce/TransactionsAndOrders/Transaction/RetailTransactionLoyaltyRewardPointTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: TransactionsAndOrders/RetailTransactionLoyaltyRewardPointsLineEntity (this entity)  

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
