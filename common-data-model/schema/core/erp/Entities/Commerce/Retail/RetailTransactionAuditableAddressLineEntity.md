---
title: RetailTransactionAuditableAddressLineEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/16/2020
ms.author: nebanfic
---

# @RetailAudit:RetailTransactionAuditableAddressLineLabel

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Entities/Commerce/Retail/RetailTransactionAuditableAddressLineEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.Application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>@RetailAudit:RetailTransactionAuditableAddressLineLabel</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Entity|
|---|---|---|
|[OperatingUnitNumber](#OperatingUnitNumber)||<a href="RetailTransactionAuditableAddressLineEntity.md" target="_blank">Retail/RetailTransactionAuditableAddressLineEntity</a>|
|[Channel](#Channel)||<a href="RetailTransactionAuditableAddressLineEntity.md" target="_blank">Retail/RetailTransactionAuditableAddressLineEntity</a>|
|[StoreNumber](#StoreNumber)||<a href="RetailTransactionAuditableAddressLineEntity.md" target="_blank">Retail/RetailTransactionAuditableAddressLineEntity</a>|
|[RegisterNumber](#RegisterNumber)||<a href="RetailTransactionAuditableAddressLineEntity.md" target="_blank">Retail/RetailTransactionAuditableAddressLineEntity</a>|
|[TransactionId](#TransactionId)||<a href="RetailTransactionAuditableAddressLineEntity.md" target="_blank">Retail/RetailTransactionAuditableAddressLineEntity</a>|
|[CountryRegionId](#CountryRegionId)||<a href="RetailTransactionAuditableAddressLineEntity.md" target="_blank">Retail/RetailTransactionAuditableAddressLineEntity</a>|
|[State](#State)||<a href="RetailTransactionAuditableAddressLineEntity.md" target="_blank">Retail/RetailTransactionAuditableAddressLineEntity</a>|
|[County](#County)||<a href="RetailTransactionAuditableAddressLineEntity.md" target="_blank">Retail/RetailTransactionAuditableAddressLineEntity</a>|
|[District](#District)||<a href="RetailTransactionAuditableAddressLineEntity.md" target="_blank">Retail/RetailTransactionAuditableAddressLineEntity</a>|
|[City](#City)||<a href="RetailTransactionAuditableAddressLineEntity.md" target="_blank">Retail/RetailTransactionAuditableAddressLineEntity</a>|
|[Street](#Street)||<a href="RetailTransactionAuditableAddressLineEntity.md" target="_blank">Retail/RetailTransactionAuditableAddressLineEntity</a>|
|[StreetNumber](#StreetNumber)||<a href="RetailTransactionAuditableAddressLineEntity.md" target="_blank">Retail/RetailTransactionAuditableAddressLineEntity</a>|
|[ZipCode](#ZipCode)||<a href="RetailTransactionAuditableAddressLineEntity.md" target="_blank">Retail/RetailTransactionAuditableAddressLineEntity</a>|
|[Attention](#Attention)||<a href="RetailTransactionAuditableAddressLineEntity.md" target="_blank">Retail/RetailTransactionAuditableAddressLineEntity</a>|
|[DeliveryName](#DeliveryName)||<a href="RetailTransactionAuditableAddressLineEntity.md" target="_blank">Retail/RetailTransactionAuditableAddressLineEntity</a>|
|[Email](#Email)||<a href="RetailTransactionAuditableAddressLineEntity.md" target="_blank">Retail/RetailTransactionAuditableAddressLineEntity</a>|
|[Telephone](#Telephone)||<a href="RetailTransactionAuditableAddressLineEntity.md" target="_blank">Retail/RetailTransactionAuditableAddressLineEntity</a>|
|[SalesLineNumber](#SalesLineNumber)||<a href="RetailTransactionAuditableAddressLineEntity.md" target="_blank">Retail/RetailTransactionAuditableAddressLineEntity</a>|
|[SalesName](#SalesName)||<a href="RetailTransactionAuditableAddressLineEntity.md" target="_blank">Retail/RetailTransactionAuditableAddressLineEntity</a>|
|[OperatingUnitRecId](#OperatingUnitRecId)||<a href="RetailTransactionAuditableAddressLineEntity.md" target="_blank">Retail/RetailTransactionAuditableAddressLineEntity</a>|
|[HeaderTransactionType](#HeaderTransactionType)||<a href="RetailTransactionAuditableAddressLineEntity.md" target="_blank">Retail/RetailTransactionAuditableAddressLineEntity</a>|
|[HeaderValidationStatus](#HeaderValidationStatus)||<a href="RetailTransactionAuditableAddressLineEntity.md" target="_blank">Retail/RetailTransactionAuditableAddressLineEntity</a>|
|[HeaderAsynchronousOrderStatus](#HeaderAsynchronousOrderStatus)||<a href="RetailTransactionAuditableAddressLineEntity.md" target="_blank">Retail/RetailTransactionAuditableAddressLineEntity</a>|
|[Relationship_RetailTransactionRelationshipId](#Relationship_RetailTransactionRelationshipId)||<a href="RetailTransactionAuditableAddressLineEntity.md" target="_blank">Retail/RetailTransactionAuditableAddressLineEntity</a>|
|[Relationship_RetailTransactionSalesTransRelationshipId](#Relationship_RetailTransactionSalesTransRelationshipId)||<a href="RetailTransactionAuditableAddressLineEntity.md" target="_blank">Retail/RetailTransactionAuditableAddressLineEntity</a>|
|[BackingTable_RetailTransactionAddressTransRelationshipId](#BackingTable_RetailTransactionAddressTransRelationshipId)||<a href="RetailTransactionAuditableAddressLineEntity.md" target="_blank">Retail/RetailTransactionAuditableAddressLineEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="RetailTransactionAuditableAddressLineEntity.md" target="_blank">Retail/RetailTransactionAuditableAddressLineEntity</a>|

### <a href=#OperatingUnitNumber name="OperatingUnitNumber">OperatingUnitNumber</a>

First included in: Retail/RetailTransactionAuditableAddressLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperatingUnitNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Channel name="Channel">Channel</a>

First included in: Retail/RetailTransactionAuditableAddressLineEntity (this entity)  

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

### <a href=#StoreNumber name="StoreNumber">StoreNumber</a>

First included in: Retail/RetailTransactionAuditableAddressLineEntity (this entity)  

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

### <a href=#RegisterNumber name="RegisterNumber">RegisterNumber</a>

First included in: Retail/RetailTransactionAuditableAddressLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

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

First included in: Retail/RetailTransactionAuditableAddressLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CountryRegionId name="CountryRegionId">CountryRegionId</a>

First included in: Retail/RetailTransactionAuditableAddressLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#State name="State">State</a>

First included in: Retail/RetailTransactionAuditableAddressLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the State attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#County name="County">County</a>

First included in: Retail/RetailTransactionAuditableAddressLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the County attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#District name="District">District</a>

First included in: Retail/RetailTransactionAuditableAddressLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the District attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#City name="City">City</a>

First included in: Retail/RetailTransactionAuditableAddressLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the City attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Street name="Street">Street</a>

First included in: Retail/RetailTransactionAuditableAddressLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Street attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StreetNumber name="StreetNumber">StreetNumber</a>

First included in: Retail/RetailTransactionAuditableAddressLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StreetNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ZipCode name="ZipCode">ZipCode</a>

First included in: Retail/RetailTransactionAuditableAddressLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ZipCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Attention name="Attention">Attention</a>

First included in: Retail/RetailTransactionAuditableAddressLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Attention attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryName name="DeliveryName">DeliveryName</a>

First included in: Retail/RetailTransactionAuditableAddressLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Email name="Email">Email</a>

First included in: Retail/RetailTransactionAuditableAddressLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Email attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Telephone name="Telephone">Telephone</a>

First included in: Retail/RetailTransactionAuditableAddressLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Telephone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesLineNumber name="SalesLineNumber">SalesLineNumber</a>

First included in: Retail/RetailTransactionAuditableAddressLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesLineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesName name="SalesName">SalesName</a>

First included in: Retail/RetailTransactionAuditableAddressLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperatingUnitRecId name="OperatingUnitRecId">OperatingUnitRecId</a>

First included in: Retail/RetailTransactionAuditableAddressLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperatingUnitRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HeaderTransactionType name="HeaderTransactionType">HeaderTransactionType</a>

First included in: Retail/RetailTransactionAuditableAddressLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

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

First included in: Retail/RetailTransactionAuditableAddressLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

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

First included in: Retail/RetailTransactionAuditableAddressLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>7</td></tr></table>

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

First included in: Retail/RetailTransactionAuditableAddressLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>6</td></tr></table>

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

First included in: Retail/RetailTransactionAuditableAddressLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>6</td></tr></table>

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

### <a href=#BackingTable_RetailTransactionAddressTransRelationshipId name="BackingTable_RetailTransactionAddressTransRelationshipId">BackingTable_RetailTransactionAddressTransRelationshipId</a>

First included in: Retail/RetailTransactionAuditableAddressLineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>6</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailTransactionAddressTransRelationshipId attribute are listed below.</summary>

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

First included in: Retail/RetailTransactionAuditableAddressLineEntity (this entity)  

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
