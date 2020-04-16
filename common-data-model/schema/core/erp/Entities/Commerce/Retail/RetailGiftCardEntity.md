---
title: RetailGiftCardEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/16/2020
ms.author: nebanfic
---

# @RET4435

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Entities/Commerce/Retail/RetailGiftCardEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.Application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>@RET4435</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Entity|
|---|---|---|
|[CurrencyCode](#CurrencyCode)||<a href="RetailGiftCardEntity.md" target="_blank">Retail/RetailGiftCardEntity</a>|
|[EntryId](#EntryId)||<a href="RetailGiftCardEntity.md" target="_blank">Retail/RetailGiftCardEntity</a>|
|[CallCenterGiftCardType](#CallCenterGiftCardType)||<a href="RetailGiftCardEntity.md" target="_blank">Retail/RetailGiftCardEntity</a>|
|[ActiveFrom](#ActiveFrom)||<a href="RetailGiftCardEntity.md" target="_blank">Retail/RetailGiftCardEntity</a>|
|[ExpiryDate](#ExpiryDate)||<a href="RetailGiftCardEntity.md" target="_blank">Retail/RetailGiftCardEntity</a>|
|[FaceValue](#FaceValue)||<a href="RetailGiftCardEntity.md" target="_blank">Retail/RetailGiftCardEntity</a>|
|[MaximumBalanceInAccountingCurrency](#MaximumBalanceInAccountingCurrency)||<a href="RetailGiftCardEntity.md" target="_blank">Retail/RetailGiftCardEntity</a>|
|[MinimumReloadInAccountingCurrency](#MinimumReloadInAccountingCurrency)||<a href="RetailGiftCardEntity.md" target="_blank">Retail/RetailGiftCardEntity</a>|
|[NonReloadable](#NonReloadable)||<a href="RetailGiftCardEntity.md" target="_blank">Retail/RetailGiftCardEntity</a>|
|[OneTimeRedemption](#OneTimeRedemption)||<a href="RetailGiftCardEntity.md" target="_blank">Retail/RetailGiftCardEntity</a>|
|[Status](#Status)||<a href="RetailGiftCardEntity.md" target="_blank">Retail/RetailGiftCardEntity</a>|
|[IsReserved](#IsReserved)||<a href="RetailGiftCardEntity.md" target="_blank">Retail/RetailGiftCardEntity</a>|
|[ReservedByRetailChannel](#ReservedByRetailChannel)||<a href="RetailGiftCardEntity.md" target="_blank">Retail/RetailGiftCardEntity</a>|
|[ReservedByRetailTerminal](#ReservedByRetailTerminal)||<a href="RetailGiftCardEntity.md" target="_blank">Retail/RetailGiftCardEntity</a>|
|[ReservedByTransactionId](#ReservedByTransactionId)||<a href="RetailGiftCardEntity.md" target="_blank">Retail/RetailGiftCardEntity</a>|
|[BackingTable_RetailGiftCardTableRelationshipId](#BackingTable_RetailGiftCardTableRelationshipId)||<a href="RetailGiftCardEntity.md" target="_blank">Retail/RetailGiftCardEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="RetailGiftCardEntity.md" target="_blank">Retail/RetailGiftCardEntity</a>|

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: Retail/RetailGiftCardEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EntryId name="EntryId">EntryId</a>

First included in: Retail/RetailGiftCardEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EntryId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CallCenterGiftCardType name="CallCenterGiftCardType">CallCenterGiftCardType</a>

First included in: Retail/RetailGiftCardEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CallCenterGiftCardType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActiveFrom name="ActiveFrom">ActiveFrom</a>

First included in: Retail/RetailGiftCardEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActiveFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExpiryDate name="ExpiryDate">ExpiryDate</a>

First included in: Retail/RetailGiftCardEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpiryDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FaceValue name="FaceValue">FaceValue</a>

First included in: Retail/RetailGiftCardEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FaceValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumBalanceInAccountingCurrency name="MaximumBalanceInAccountingCurrency">MaximumBalanceInAccountingCurrency</a>

First included in: Retail/RetailGiftCardEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumBalanceInAccountingCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinimumReloadInAccountingCurrency name="MinimumReloadInAccountingCurrency">MinimumReloadInAccountingCurrency</a>

First included in: Retail/RetailGiftCardEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumReloadInAccountingCurrency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#NonReloadable name="NonReloadable">NonReloadable</a>

First included in: Retail/RetailGiftCardEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the NonReloadable attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OneTimeRedemption name="OneTimeRedemption">OneTimeRedemption</a>

First included in: Retail/RetailGiftCardEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OneTimeRedemption attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Status name="Status">Status</a>

First included in: Retail/RetailGiftCardEntity (this entity)  

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

### <a href=#IsReserved name="IsReserved">IsReserved</a>

First included in: Retail/RetailGiftCardEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsReserved attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReservedByRetailChannel name="ReservedByRetailChannel">ReservedByRetailChannel</a>

First included in: Retail/RetailGiftCardEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReservedByRetailChannel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReservedByRetailTerminal name="ReservedByRetailTerminal">ReservedByRetailTerminal</a>

First included in: Retail/RetailGiftCardEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReservedByRetailTerminal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReservedByTransactionId name="ReservedByTransactionId">ReservedByTransactionId</a>

First included in: Retail/RetailGiftCardEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReservedByTransactionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_RetailGiftCardTableRelationshipId name="BackingTable_RetailGiftCardTableRelationshipId">BackingTable_RetailGiftCardTableRelationshipId</a>

First included in: Retail/RetailGiftCardEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>6</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailGiftCardTableRelationshipId attribute are listed below.</summary>

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

First included in: Retail/RetailGiftCardEntity (this entity)  

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
