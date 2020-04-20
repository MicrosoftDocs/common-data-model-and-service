---
title: LedgerItemCodeZakat_SA - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# LedgerItemCodeZakat_SA

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Ledger/Main/LedgerItemCodeZakat_SA.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[LedgerItemCodeZakat_SA/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="LedgerItemCodeZakat_SA.md" target="_blank">Main/LedgerItemCodeZakat_SA</a>|
|[Description](#Description)||<a href="LedgerItemCodeZakat_SA.md" target="_blank">Main/LedgerItemCodeZakat_SA</a>|
|[IsAsset](#IsAsset)||<a href="LedgerItemCodeZakat_SA.md" target="_blank">Main/LedgerItemCodeZakat_SA</a>|
|[IsBalance](#IsBalance)||<a href="LedgerItemCodeZakat_SA.md" target="_blank">Main/LedgerItemCodeZakat_SA</a>|
|[IsCost](#IsCost)||<a href="LedgerItemCodeZakat_SA.md" target="_blank">Main/LedgerItemCodeZakat_SA</a>|
|[IsLiability](#IsLiability)||<a href="LedgerItemCodeZakat_SA.md" target="_blank">Main/LedgerItemCodeZakat_SA</a>|
|[IsProfitLoss](#IsProfitLoss)||<a href="LedgerItemCodeZakat_SA.md" target="_blank">Main/LedgerItemCodeZakat_SA</a>|
|[IsRevenue](#IsRevenue)||<a href="LedgerItemCodeZakat_SA.md" target="_blank">Main/LedgerItemCodeZakat_SA</a>|
|[ItemCode](#ItemCode)||<a href="LedgerItemCodeZakat_SA.md" target="_blank">Main/LedgerItemCodeZakat_SA</a>|
|[ItemType](#ItemType)||<a href="LedgerItemCodeZakat_SA.md" target="_blank">Main/LedgerItemCodeZakat_SA</a>|
|[DataAreaId](#DataAreaId)||<a href="LedgerItemCodeZakat_SA.md" target="_blank">Main/LedgerItemCodeZakat_SA</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="LedgerItemCodeZakat_SA.md" target="_blank">Main/LedgerItemCodeZakat_SA</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/LedgerItemCodeZakat_SA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[LedgerItemCodeZakat_SA/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: Main/LedgerItemCodeZakat_SA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsAsset name="IsAsset">IsAsset</a>

First included in: Main/LedgerItemCodeZakat_SA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsAsset attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsBalance name="IsBalance">IsBalance</a>

First included in: Main/LedgerItemCodeZakat_SA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsBalance attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsCost name="IsCost">IsCost</a>

First included in: Main/LedgerItemCodeZakat_SA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCost attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsLiability name="IsLiability">IsLiability</a>

First included in: Main/LedgerItemCodeZakat_SA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsLiability attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsProfitLoss name="IsProfitLoss">IsProfitLoss</a>

First included in: Main/LedgerItemCodeZakat_SA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProfitLoss attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsRevenue name="IsRevenue">IsRevenue</a>

First included in: Main/LedgerItemCodeZakat_SA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsRevenue attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ItemCode name="ItemCode">ItemCode</a>

First included in: Main/LedgerItemCodeZakat_SA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemType name="ItemType">ItemType</a>

First included in: Main/LedgerItemCodeZakat_SA (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Main/LedgerItemCodeZakat_SA (this entity)  

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

First included in: Main/LedgerItemCodeZakat_SA (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
