---
title: RetailLoyaltyConflictCardPointTrans - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# RetailLoyaltyConflictCardPointTrans

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Commerce/Retail/Transaction/RetailLoyaltyConflictCardPointTrans.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailLoyaltyConflictCardPointTrans/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailLoyaltyConflictCardPointTrans.md" target="_blank">Transaction/RetailLoyaltyConflictCardPointTrans</a>|
|[Affiliation](#Affiliation)||<a href="RetailLoyaltyConflictCardPointTrans.md" target="_blank">Transaction/RetailLoyaltyConflictCardPointTrans</a>|
|[CardNumber](#CardNumber)||<a href="RetailLoyaltyConflictCardPointTrans.md" target="_blank">Transaction/RetailLoyaltyConflictCardPointTrans</a>|
|[Channel](#Channel)||<a href="RetailLoyaltyConflictCardPointTrans.md" target="_blank">Transaction/RetailLoyaltyConflictCardPointTrans</a>|
|[Comment](#Comment)||<a href="RetailLoyaltyConflictCardPointTrans.md" target="_blank">Transaction/RetailLoyaltyConflictCardPointTrans</a>|
|[CustAccount](#CustAccount)||<a href="RetailLoyaltyConflictCardPointTrans.md" target="_blank">Transaction/RetailLoyaltyConflictCardPointTrans</a>|
|[CustAccountDataAreaId](#CustAccountDataAreaId)||<a href="RetailLoyaltyConflictCardPointTrans.md" target="_blank">Transaction/RetailLoyaltyConflictCardPointTrans</a>|
|[EntryDate](#EntryDate)||<a href="RetailLoyaltyConflictCardPointTrans.md" target="_blank">Transaction/RetailLoyaltyConflictCardPointTrans</a>|
|[EntryTime](#EntryTime)||<a href="RetailLoyaltyConflictCardPointTrans.md" target="_blank">Transaction/RetailLoyaltyConflictCardPointTrans</a>|
|[EntryType](#EntryType)||<a href="RetailLoyaltyConflictCardPointTrans.md" target="_blank">Transaction/RetailLoyaltyConflictCardPointTrans</a>|
|[ExpirationDate](#ExpirationDate)||<a href="RetailLoyaltyConflictCardPointTrans.md" target="_blank">Transaction/RetailLoyaltyConflictCardPointTrans</a>|
|[IsMigrated](#IsMigrated)||<a href="RetailLoyaltyConflictCardPointTrans.md" target="_blank">Transaction/RetailLoyaltyConflictCardPointTrans</a>|
|[LoyaltyTier](#LoyaltyTier)||<a href="RetailLoyaltyConflictCardPointTrans.md" target="_blank">Transaction/RetailLoyaltyConflictCardPointTrans</a>|
|[loyaltyTransDataAreaId](#loyaltyTransDataAreaId)||<a href="RetailLoyaltyConflictCardPointTrans.md" target="_blank">Transaction/RetailLoyaltyConflictCardPointTrans</a>|
|[LoyaltyTransLineNum](#LoyaltyTransLineNum)||<a href="RetailLoyaltyConflictCardPointTrans.md" target="_blank">Transaction/RetailLoyaltyConflictCardPointTrans</a>|
|[ReceiptId](#ReceiptId)||<a href="RetailLoyaltyConflictCardPointTrans.md" target="_blank">Transaction/RetailLoyaltyConflictCardPointTrans</a>|
|[RewardPoint](#RewardPoint)||<a href="RetailLoyaltyConflictCardPointTrans.md" target="_blank">Transaction/RetailLoyaltyConflictCardPointTrans</a>|
|[RewardPointAmountQty](#RewardPointAmountQty)||<a href="RetailLoyaltyConflictCardPointTrans.md" target="_blank">Transaction/RetailLoyaltyConflictCardPointTrans</a>|
|[StaffId](#StaffId)||<a href="RetailLoyaltyConflictCardPointTrans.md" target="_blank">Transaction/RetailLoyaltyConflictCardPointTrans</a>|
|[storeId](#storeId)||<a href="RetailLoyaltyConflictCardPointTrans.md" target="_blank">Transaction/RetailLoyaltyConflictCardPointTrans</a>|
|[terminalId](#terminalId)||<a href="RetailLoyaltyConflictCardPointTrans.md" target="_blank">Transaction/RetailLoyaltyConflictCardPointTrans</a>|
|[transactionId](#transactionId)||<a href="RetailLoyaltyConflictCardPointTrans.md" target="_blank">Transaction/RetailLoyaltyConflictCardPointTrans</a>|
|[Relationship_CustTableRelationshipId](#Relationship_CustTableRelationshipId)||<a href="RetailLoyaltyConflictCardPointTrans.md" target="_blank">Transaction/RetailLoyaltyConflictCardPointTrans</a>|
|[Relationship_RetailAffiliationRelationshipId](#Relationship_RetailAffiliationRelationshipId)||<a href="RetailLoyaltyConflictCardPointTrans.md" target="_blank">Transaction/RetailLoyaltyConflictCardPointTrans</a>|
|[Relationship_RetailChannelTableRelationshipId](#Relationship_RetailChannelTableRelationshipId)||<a href="RetailLoyaltyConflictCardPointTrans.md" target="_blank">Transaction/RetailLoyaltyConflictCardPointTrans</a>|
|[Relationship_RetailLoyaltyCardRelationshipId](#Relationship_RetailLoyaltyCardRelationshipId)||<a href="RetailLoyaltyConflictCardPointTrans.md" target="_blank">Transaction/RetailLoyaltyConflictCardPointTrans</a>|
|[Relationship_RetailLoyaltyRewardPointRelationshipId](#Relationship_RetailLoyaltyRewardPointRelationshipId)||<a href="RetailLoyaltyConflictCardPointTrans.md" target="_blank">Transaction/RetailLoyaltyConflictCardPointTrans</a>|
|[Relationship_RetailLoyaltyTierRelationshipId](#Relationship_RetailLoyaltyTierRelationshipId)||<a href="RetailLoyaltyConflictCardPointTrans.md" target="_blank">Transaction/RetailLoyaltyConflictCardPointTrans</a>|
|[Relationship_RetailStoreTableRelationshipId](#Relationship_RetailStoreTableRelationshipId)||<a href="RetailLoyaltyConflictCardPointTrans.md" target="_blank">Transaction/RetailLoyaltyConflictCardPointTrans</a>|
|[Relationship_RetailTerminalTableRelationshipId](#Relationship_RetailTerminalTableRelationshipId)||<a href="RetailLoyaltyConflictCardPointTrans.md" target="_blank">Transaction/RetailLoyaltyConflictCardPointTrans</a>|
|[Relationship_RetailTransactionLoyaltyRewardPointTransRelationshipId](#Relationship_RetailTransactionLoyaltyRewardPointTransRelationshipId)||<a href="RetailLoyaltyConflictCardPointTrans.md" target="_blank">Transaction/RetailLoyaltyConflictCardPointTrans</a>|
|[Relationship_RetailTransactionTableRelationshipId](#Relationship_RetailTransactionTableRelationshipId)||<a href="RetailLoyaltyConflictCardPointTrans.md" target="_blank">Transaction/RetailLoyaltyConflictCardPointTrans</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/RetailLoyaltyConflictCardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailLoyaltyConflictCardPointTrans/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Affiliation name="Affiliation">Affiliation</a>

First included in: Transaction/RetailLoyaltyConflictCardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Affiliation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CardNumber name="CardNumber">CardNumber</a>

First included in: Transaction/RetailLoyaltyConflictCardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CardNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Channel name="Channel">Channel</a>

First included in: Transaction/RetailLoyaltyConflictCardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Channel attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Comment name="Comment">Comment</a>

First included in: Transaction/RetailLoyaltyConflictCardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Comment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustAccount name="CustAccount">CustAccount</a>

First included in: Transaction/RetailLoyaltyConflictCardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustAccountDataAreaId name="CustAccountDataAreaId">CustAccountDataAreaId</a>

First included in: Transaction/RetailLoyaltyConflictCardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustAccountDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EntryDate name="EntryDate">EntryDate</a>

First included in: Transaction/RetailLoyaltyConflictCardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EntryDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.dataFormat.date**  
</details>

### <a href=#EntryTime name="EntryTime">EntryTime</a>

First included in: Transaction/RetailLoyaltyConflictCardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>time</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EntryTime attribute are listed below.</summary>

**is.dataFormat.time**  
**means.measurement.time**  
**is.dataFormat.time**  
</details>

### <a href=#EntryType name="EntryType">EntryType</a>

First included in: Transaction/RetailLoyaltyConflictCardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EntryType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#ExpirationDate name="ExpirationDate">ExpirationDate</a>

First included in: Transaction/RetailLoyaltyConflictCardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpirationDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#IsMigrated name="IsMigrated">IsMigrated</a>

First included in: Transaction/RetailLoyaltyConflictCardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsMigrated attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LoyaltyTier name="LoyaltyTier">LoyaltyTier</a>

First included in: Transaction/RetailLoyaltyConflictCardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoyaltyTier attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#loyaltyTransDataAreaId name="loyaltyTransDataAreaId">loyaltyTransDataAreaId</a>

First included in: Transaction/RetailLoyaltyConflictCardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the loyaltyTransDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LoyaltyTransLineNum name="LoyaltyTransLineNum">LoyaltyTransLineNum</a>

First included in: Transaction/RetailLoyaltyConflictCardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoyaltyTransLineNum attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ReceiptId name="ReceiptId">ReceiptId</a>

First included in: Transaction/RetailLoyaltyConflictCardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceiptId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RewardPoint name="RewardPoint">RewardPoint</a>

First included in: Transaction/RetailLoyaltyConflictCardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RewardPoint attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RewardPointAmountQty name="RewardPointAmountQty">RewardPointAmountQty</a>

First included in: Transaction/RetailLoyaltyConflictCardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RewardPointAmountQty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#StaffId name="StaffId">StaffId</a>

First included in: Transaction/RetailLoyaltyConflictCardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StaffId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#storeId name="storeId">storeId</a>

First included in: Transaction/RetailLoyaltyConflictCardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the storeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#terminalId name="terminalId">terminalId</a>

First included in: Transaction/RetailLoyaltyConflictCardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the terminalId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#transactionId name="transactionId">transactionId</a>

First included in: Transaction/RetailLoyaltyConflictCardPointTrans (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the transactionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustTableRelationshipId name="Relationship_CustTableRelationshipId">Relationship_CustTableRelationshipId</a>

First included in: Transaction/RetailLoyaltyConflictCardPointTrans (this entity)  

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

First included in: Transaction/RetailLoyaltyConflictCardPointTrans (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/RetailAffiliation.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Miscellaneous/RetailAffiliation.cdm.json/RetailAffiliation</a></td><td><a href="../Miscellaneous/RetailAffiliation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailChannelTableRelationshipId name="Relationship_RetailChannelTableRelationshipId">Relationship_RetailChannelTableRelationshipId</a>

First included in: Transaction/RetailLoyaltyConflictCardPointTrans (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/RetailChannelTable.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Main/RetailChannelTable.cdm.json/RetailChannelTable</a></td><td><a href="../Main/RetailChannelTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailLoyaltyCardRelationshipId name="Relationship_RetailLoyaltyCardRelationshipId">Relationship_RetailLoyaltyCardRelationshipId</a>

First included in: Transaction/RetailLoyaltyConflictCardPointTrans (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/RetailLoyaltyCard.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Miscellaneous/RetailLoyaltyCard.cdm.json/RetailLoyaltyCard</a></td><td><a href="../Miscellaneous/RetailLoyaltyCard.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailLoyaltyRewardPointRelationshipId name="Relationship_RetailLoyaltyRewardPointRelationshipId">Relationship_RetailLoyaltyRewardPointRelationshipId</a>

First included in: Transaction/RetailLoyaltyConflictCardPointTrans (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/RetailLoyaltyRewardPoint.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Miscellaneous/RetailLoyaltyRewardPoint.cdm.json/RetailLoyaltyRewardPoint</a></td><td><a href="../Miscellaneous/RetailLoyaltyRewardPoint.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailLoyaltyTierRelationshipId name="Relationship_RetailLoyaltyTierRelationshipId">Relationship_RetailLoyaltyTierRelationshipId</a>

First included in: Transaction/RetailLoyaltyConflictCardPointTrans (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/RetailLoyaltyTier.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Miscellaneous/RetailLoyaltyTier.cdm.json/RetailLoyaltyTier</a></td><td><a href="../Miscellaneous/RetailLoyaltyTier.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailStoreTableRelationshipId name="Relationship_RetailStoreTableRelationshipId">Relationship_RetailStoreTableRelationshipId</a>

First included in: Transaction/RetailLoyaltyConflictCardPointTrans (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/RetailStoreTable.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Main/RetailStoreTable.cdm.json/RetailStoreTable</a></td><td><a href="../Main/RetailStoreTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailTerminalTableRelationshipId name="Relationship_RetailTerminalTableRelationshipId">Relationship_RetailTerminalTableRelationshipId</a>

First included in: Transaction/RetailLoyaltyConflictCardPointTrans (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/RetailTerminalTable.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Main/RetailTerminalTable.cdm.json/RetailTerminalTable</a></td><td><a href="../Main/RetailTerminalTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailTransactionLoyaltyRewardPointTransRelationshipId name="Relationship_RetailTransactionLoyaltyRewardPointTransRelationshipId">Relationship_RetailTransactionLoyaltyRewardPointTransRelationshipId</a>

First included in: Transaction/RetailLoyaltyConflictCardPointTrans (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailTransactionLoyaltyRewardPointTrans.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Transaction/RetailTransactionLoyaltyRewardPointTrans.cdm.json/RetailTransactionLoyaltyRewardPointTrans</a></td><td><a href="RetailTransactionLoyaltyRewardPointTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailTransactionTableRelationshipId name="Relationship_RetailTransactionTableRelationshipId">Relationship_RetailTransactionTableRelationshipId</a>

First included in: Transaction/RetailLoyaltyConflictCardPointTrans (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailTransactionTable.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Transaction/RetailTransactionTable.cdm.json/RetailTransactionTable</a></td><td><a href="RetailTransactionTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
