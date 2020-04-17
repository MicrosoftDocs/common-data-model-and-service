---
title: RetailTransactionAuditableDiscountLineEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/16/2020
ms.author: nebanfic
---

# @RetailAudit:RetailTransactionAuditableDiscountLineEntityLabel

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Entities/Commerce/Retail/RetailTransactionAuditableDiscountLineEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.Application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>@RetailAudit:RetailTransactionAuditableDiscountLineEntityLabel</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[Amount](#Amount)||<a href="RetailTransactionAuditableDiscountLineEntity.md" target="_blank">Retail/RetailTransactionAuditableDiscountLineEntity</a>|
|[Channel](#Channel)||<a href="RetailTransactionAuditableDiscountLineEntity.md" target="_blank">Retail/RetailTransactionAuditableDiscountLineEntity</a>|
|[CustomerDiscountType](#CustomerDiscountType)||<a href="RetailTransactionAuditableDiscountLineEntity.md" target="_blank">Retail/RetailTransactionAuditableDiscountLineEntity</a>|
|[DealPrice](#DealPrice)||<a href="RetailTransactionAuditableDiscountLineEntity.md" target="_blank">Retail/RetailTransactionAuditableDiscountLineEntity</a>|
|[DiscountAmount](#DiscountAmount)||<a href="RetailTransactionAuditableDiscountLineEntity.md" target="_blank">Retail/RetailTransactionAuditableDiscountLineEntity</a>|
|[DiscountCost](#DiscountCost)||<a href="RetailTransactionAuditableDiscountLineEntity.md" target="_blank">Retail/RetailTransactionAuditableDiscountLineEntity</a>|
|[DiscountOriginType](#DiscountOriginType)||<a href="RetailTransactionAuditableDiscountLineEntity.md" target="_blank">Retail/RetailTransactionAuditableDiscountLineEntity</a>|
|[LineNumber](#LineNumber)||<a href="RetailTransactionAuditableDiscountLineEntity.md" target="_blank">Retail/RetailTransactionAuditableDiscountLineEntity</a>|
|[ManualDiscountType](#ManualDiscountType)||<a href="RetailTransactionAuditableDiscountLineEntity.md" target="_blank">Retail/RetailTransactionAuditableDiscountLineEntity</a>|
|[Percentage](#Percentage)||<a href="RetailTransactionAuditableDiscountLineEntity.md" target="_blank">Retail/RetailTransactionAuditableDiscountLineEntity</a>|
|[PeriodicDiscountOfferId](#PeriodicDiscountOfferId)||<a href="RetailTransactionAuditableDiscountLineEntity.md" target="_blank">Retail/RetailTransactionAuditableDiscountLineEntity</a>|
|[SalesLineNumber](#SalesLineNumber)||<a href="RetailTransactionAuditableDiscountLineEntity.md" target="_blank">Retail/RetailTransactionAuditableDiscountLineEntity</a>|
|[StoreNumber](#StoreNumber)||<a href="RetailTransactionAuditableDiscountLineEntity.md" target="_blank">Retail/RetailTransactionAuditableDiscountLineEntity</a>|
|[RegisterNumber](#RegisterNumber)||<a href="RetailTransactionAuditableDiscountLineEntity.md" target="_blank">Retail/RetailTransactionAuditableDiscountLineEntity</a>|
|[TransactionId](#TransactionId)||<a href="RetailTransactionAuditableDiscountLineEntity.md" target="_blank">Retail/RetailTransactionAuditableDiscountLineEntity</a>|
|[BundleId](#BundleId)||<a href="RetailTransactionAuditableDiscountLineEntity.md" target="_blank">Retail/RetailTransactionAuditableDiscountLineEntity</a>|
|[OperatingUnitRecId](#OperatingUnitRecId)||<a href="RetailTransactionAuditableDiscountLineEntity.md" target="_blank">Retail/RetailTransactionAuditableDiscountLineEntity</a>|
|[OperatingUnitNumber](#OperatingUnitNumber)||<a href="RetailTransactionAuditableDiscountLineEntity.md" target="_blank">Retail/RetailTransactionAuditableDiscountLineEntity</a>|
|[HeaderStoreNumber](#HeaderStoreNumber)||<a href="RetailTransactionAuditableDiscountLineEntity.md" target="_blank">Retail/RetailTransactionAuditableDiscountLineEntity</a>|
|[HeaderStatementNumber](#HeaderStatementNumber)||<a href="RetailTransactionAuditableDiscountLineEntity.md" target="_blank">Retail/RetailTransactionAuditableDiscountLineEntity</a>|
|[HeaderTransactionType](#HeaderTransactionType)||<a href="RetailTransactionAuditableDiscountLineEntity.md" target="_blank">Retail/RetailTransactionAuditableDiscountLineEntity</a>|
|[HeaderValidationStatus](#HeaderValidationStatus)||<a href="RetailTransactionAuditableDiscountLineEntity.md" target="_blank">Retail/RetailTransactionAuditableDiscountLineEntity</a>|
|[HeaderAsynchronousOrderStatus](#HeaderAsynchronousOrderStatus)||<a href="RetailTransactionAuditableDiscountLineEntity.md" target="_blank">Retail/RetailTransactionAuditableDiscountLineEntity</a>|
|[Relationship_RetailTransactionRelationshipId](#Relationship_RetailTransactionRelationshipId)||<a href="RetailTransactionAuditableDiscountLineEntity.md" target="_blank">Retail/RetailTransactionAuditableDiscountLineEntity</a>|
|[Relationship_RetailTransactionSalesTransRelationshipId](#Relationship_RetailTransactionSalesTransRelationshipId)||<a href="RetailTransactionAuditableDiscountLineEntity.md" target="_blank">Retail/RetailTransactionAuditableDiscountLineEntity</a>|
|[BackingTable_RetailTransactionDiscountTransRelationshipId](#BackingTable_RetailTransactionDiscountTransRelationshipId)||<a href="RetailTransactionAuditableDiscountLineEntity.md" target="_blank">Retail/RetailTransactionAuditableDiscountLineEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="RetailTransactionAuditableDiscountLineEntity.md" target="_blank">Retail/RetailTransactionAuditableDiscountLineEntity</a>|

### <a href=#Amount name="Amount">Amount</a>

First included in: Retail/RetailTransactionAuditableDiscountLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Amount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Channel name="Channel">Channel</a>

First included in: Retail/RetailTransactionAuditableDiscountLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Channel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerDiscountType name="CustomerDiscountType">CustomerDiscountType</a>

First included in: Retail/RetailTransactionAuditableDiscountLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerDiscountType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DealPrice name="DealPrice">DealPrice</a>

First included in: Retail/RetailTransactionAuditableDiscountLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DealPrice attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscountAmount name="DiscountAmount">DiscountAmount</a>

First included in: Retail/RetailTransactionAuditableDiscountLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscountCost name="DiscountCost">DiscountCost</a>

First included in: Retail/RetailTransactionAuditableDiscountLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountCost attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DiscountOriginType name="DiscountOriginType">DiscountOriginType</a>

First included in: Retail/RetailTransactionAuditableDiscountLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscountOriginType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: Retail/RetailTransactionAuditableDiscountLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ManualDiscountType name="ManualDiscountType">ManualDiscountType</a>

First included in: Retail/RetailTransactionAuditableDiscountLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ManualDiscountType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Percentage name="Percentage">Percentage</a>

First included in: Retail/RetailTransactionAuditableDiscountLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Percentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PeriodicDiscountOfferId name="PeriodicDiscountOfferId">PeriodicDiscountOfferId</a>

First included in: Retail/RetailTransactionAuditableDiscountLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PeriodicDiscountOfferId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesLineNumber name="SalesLineNumber">SalesLineNumber</a>

First included in: Retail/RetailTransactionAuditableDiscountLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesLineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StoreNumber name="StoreNumber">StoreNumber</a>

First included in: Retail/RetailTransactionAuditableDiscountLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StoreNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RegisterNumber name="RegisterNumber">RegisterNumber</a>

First included in: Retail/RetailTransactionAuditableDiscountLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RegisterNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionId name="TransactionId">TransactionId</a>

First included in: Retail/RetailTransactionAuditableDiscountLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BundleId name="BundleId">BundleId</a>

First included in: Retail/RetailTransactionAuditableDiscountLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BundleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperatingUnitRecId name="OperatingUnitRecId">OperatingUnitRecId</a>

First included in: Retail/RetailTransactionAuditableDiscountLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperatingUnitRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperatingUnitNumber name="OperatingUnitNumber">OperatingUnitNumber</a>

First included in: Retail/RetailTransactionAuditableDiscountLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperatingUnitNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HeaderStoreNumber name="HeaderStoreNumber">HeaderStoreNumber</a>

First included in: Retail/RetailTransactionAuditableDiscountLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HeaderStoreNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HeaderStatementNumber name="HeaderStatementNumber">HeaderStatementNumber</a>

First included in: Retail/RetailTransactionAuditableDiscountLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HeaderStatementNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HeaderTransactionType name="HeaderTransactionType">HeaderTransactionType</a>

First included in: Retail/RetailTransactionAuditableDiscountLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HeaderTransactionType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HeaderValidationStatus name="HeaderValidationStatus">HeaderValidationStatus</a>

First included in: Retail/RetailTransactionAuditableDiscountLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HeaderValidationStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HeaderAsynchronousOrderStatus name="HeaderAsynchronousOrderStatus">HeaderAsynchronousOrderStatus</a>

First included in: Retail/RetailTransactionAuditableDiscountLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HeaderAsynchronousOrderStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailTransactionRelationshipId name="Relationship_RetailTransactionRelationshipId">Relationship_RetailTransactionRelationshipId</a>

First included in: Retail/RetailTransactionAuditableDiscountLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailTransactionRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_RetailTransactionSalesTransRelationshipId name="Relationship_RetailTransactionSalesTransRelationshipId">Relationship_RetailTransactionSalesTransRelationshipId</a>

First included in: Retail/RetailTransactionAuditableDiscountLineEntity (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_RetailTransactionDiscountTransRelationshipId name="BackingTable_RetailTransactionDiscountTransRelationshipId">BackingTable_RetailTransactionDiscountTransRelationshipId</a>

First included in: Retail/RetailTransactionAuditableDiscountLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailTransactionDiscountTransRelationshipId attribute are listed below.</summary>

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

First included in: Retail/RetailTransactionAuditableDiscountLineEntity (this entity)  

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
