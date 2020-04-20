---
title: MCRCoupon - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# MCRCoupon

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Commerce/Retail/Main/MCRCoupon.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[MCRCoupon/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="MCRCoupon.md" target="_blank">Main/MCRCoupon</a>|
|[MCRCouponDesc](#MCRCouponDesc)||<a href="MCRCoupon.md" target="_blank">Main/MCRCoupon</a>|
|[MCRCouponExpDate](#MCRCouponExpDate)||<a href="MCRCoupon.md" target="_blank">Main/MCRCoupon</a>|
|[MCRCouponId](#MCRCouponId)||<a href="MCRCoupon.md" target="_blank">Main/MCRCoupon</a>|
|[MCRCouponNumber](#MCRCouponNumber)||<a href="MCRCoupon.md" target="_blank">Main/MCRCoupon</a>|
|[MCRCouponOrign](#MCRCouponOrign)||<a href="MCRCoupon.md" target="_blank">Main/MCRCoupon</a>|
|[MCRCouponParentId](#MCRCouponParentId)||<a href="MCRCoupon.md" target="_blank">Main/MCRCoupon</a>|
|[MCRCouponRedemptionRate](#MCRCouponRedemptionRate)||<a href="MCRCoupon.md" target="_blank">Main/MCRCoupon</a>|
|[MCRCouponVoided](#MCRCouponVoided)||<a href="MCRCoupon.md" target="_blank">Main/MCRCoupon</a>|
|[MCRCustomerSpecific](#MCRCustomerSpecific)||<a href="MCRCoupon.md" target="_blank">Main/MCRCoupon</a>|
|[MCREnabled](#MCREnabled)||<a href="MCRCoupon.md" target="_blank">Main/MCRCoupon</a>|
|[MCRExclusive](#MCRExclusive)||<a href="MCRCoupon.md" target="_blank">Main/MCRCoupon</a>|
|[MCRFromDate](#MCRFromDate)||<a href="MCRCoupon.md" target="_blank">Main/MCRCoupon</a>|
|[MCRIncludeExcludeCatalog](#MCRIncludeExcludeCatalog)||<a href="MCRCoupon.md" target="_blank">Main/MCRCoupon</a>|
|[MCRIncludeExcludeItem](#MCRIncludeExcludeItem)||<a href="MCRCoupon.md" target="_blank">Main/MCRCoupon</a>|
|[MCRManufacturerCoupon](#MCRManufacturerCoupon)||<a href="MCRCoupon.md" target="_blank">Main/MCRCoupon</a>|
|[MCROneTimeUse](#MCROneTimeUse)||<a href="MCRCoupon.md" target="_blank">Main/MCRCoupon</a>|
|[MCRReissue](#MCRReissue)||<a href="MCRCoupon.md" target="_blank">Main/MCRCoupon</a>|
|[MCRToDate](#MCRToDate)||<a href="MCRCoupon.md" target="_blank">Main/MCRCoupon</a>|
|[DataAreaId](#DataAreaId)||<a href="MCRCoupon.md" target="_blank">Main/MCRCoupon</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="MCRCoupon.md" target="_blank">Main/MCRCoupon</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/MCRCoupon (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[MCRCoupon/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#MCRCouponDesc name="MCRCouponDesc">MCRCouponDesc</a>

First included in: Main/MCRCoupon (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRCouponDesc attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MCRCouponExpDate name="MCRCouponExpDate">MCRCouponExpDate</a>

First included in: Main/MCRCoupon (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRCouponExpDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#MCRCouponId name="MCRCouponId">MCRCouponId</a>

First included in: Main/MCRCoupon (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRCouponId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MCRCouponNumber name="MCRCouponNumber">MCRCouponNumber</a>

First included in: Main/MCRCoupon (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRCouponNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MCRCouponOrign name="MCRCouponOrign">MCRCouponOrign</a>

First included in: Main/MCRCoupon (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRCouponOrign attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MCRCouponParentId name="MCRCouponParentId">MCRCouponParentId</a>

First included in: Main/MCRCoupon (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRCouponParentId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MCRCouponRedemptionRate name="MCRCouponRedemptionRate">MCRCouponRedemptionRate</a>

First included in: Main/MCRCoupon (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRCouponRedemptionRate attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#MCRCouponVoided name="MCRCouponVoided">MCRCouponVoided</a>

First included in: Main/MCRCoupon (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRCouponVoided attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MCRCustomerSpecific name="MCRCustomerSpecific">MCRCustomerSpecific</a>

First included in: Main/MCRCoupon (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRCustomerSpecific attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MCREnabled name="MCREnabled">MCREnabled</a>

First included in: Main/MCRCoupon (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCREnabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MCRExclusive name="MCRExclusive">MCRExclusive</a>

First included in: Main/MCRCoupon (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRExclusive attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MCRFromDate name="MCRFromDate">MCRFromDate</a>

First included in: Main/MCRCoupon (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRFromDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#MCRIncludeExcludeCatalog name="MCRIncludeExcludeCatalog">MCRIncludeExcludeCatalog</a>

First included in: Main/MCRCoupon (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRIncludeExcludeCatalog attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MCRIncludeExcludeItem name="MCRIncludeExcludeItem">MCRIncludeExcludeItem</a>

First included in: Main/MCRCoupon (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRIncludeExcludeItem attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MCRManufacturerCoupon name="MCRManufacturerCoupon">MCRManufacturerCoupon</a>

First included in: Main/MCRCoupon (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRManufacturerCoupon attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MCROneTimeUse name="MCROneTimeUse">MCROneTimeUse</a>

First included in: Main/MCRCoupon (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCROneTimeUse attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MCRReissue name="MCRReissue">MCRReissue</a>

First included in: Main/MCRCoupon (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRReissue attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MCRToDate name="MCRToDate">MCRToDate</a>

First included in: Main/MCRCoupon (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRToDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Main/MCRCoupon (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Main/MCRCoupon (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CompanyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
