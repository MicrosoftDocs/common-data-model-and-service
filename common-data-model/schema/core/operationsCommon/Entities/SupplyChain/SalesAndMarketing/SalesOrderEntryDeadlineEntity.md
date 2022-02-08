---
title: SalesOrderEntryDeadlineEntity in SalesAndMarketing - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Sales order entry deadlines in SalesAndMarketing(SalesOrderEntryDeadlineEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/SalesAndMarketing/SalesOrderEntryDeadlineEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales order entry deadlines</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[DeadlineGroupCode](#DeadlineGroupCode)||<a href="SalesOrderEntryDeadlineEntity.md" target="_blank">SalesAndMarketing/SalesOrderEntryDeadlineEntity</a>|
|[SalesOrderEntryDeadlineGroupId](#SalesOrderEntryDeadlineGroupId)||<a href="SalesOrderEntryDeadlineEntity.md" target="_blank">SalesAndMarketing/SalesOrderEntryDeadlineEntity</a>|
|[SiteCode](#SiteCode)||<a href="SalesOrderEntryDeadlineEntity.md" target="_blank">SalesAndMarketing/SalesOrderEntryDeadlineEntity</a>|
|[SiteId](#SiteId)||<a href="SalesOrderEntryDeadlineEntity.md" target="_blank">SalesAndMarketing/SalesOrderEntryDeadlineEntity</a>|
|[LatestOrderEntryTimeMonday](#LatestOrderEntryTimeMonday)||<a href="SalesOrderEntryDeadlineEntity.md" target="_blank">SalesAndMarketing/SalesOrderEntryDeadlineEntity</a>|
|[LatestOrderEntryTimeTuesday](#LatestOrderEntryTimeTuesday)||<a href="SalesOrderEntryDeadlineEntity.md" target="_blank">SalesAndMarketing/SalesOrderEntryDeadlineEntity</a>|
|[LatestOrderEntryTimeWednesday](#LatestOrderEntryTimeWednesday)||<a href="SalesOrderEntryDeadlineEntity.md" target="_blank">SalesAndMarketing/SalesOrderEntryDeadlineEntity</a>|
|[LatestOrderEntryTimeThursday](#LatestOrderEntryTimeThursday)||<a href="SalesOrderEntryDeadlineEntity.md" target="_blank">SalesAndMarketing/SalesOrderEntryDeadlineEntity</a>|
|[LatestOrderEntryTimeFriday](#LatestOrderEntryTimeFriday)||<a href="SalesOrderEntryDeadlineEntity.md" target="_blank">SalesAndMarketing/SalesOrderEntryDeadlineEntity</a>|
|[LatestOrderEntryTimeSaturday](#LatestOrderEntryTimeSaturday)||<a href="SalesOrderEntryDeadlineEntity.md" target="_blank">SalesAndMarketing/SalesOrderEntryDeadlineEntity</a>|
|[LatestOrderEntryTimeSunday](#LatestOrderEntryTimeSunday)||<a href="SalesOrderEntryDeadlineEntity.md" target="_blank">SalesAndMarketing/SalesOrderEntryDeadlineEntity</a>|
|[BackingTable_InventOrderEntryDeadlineTableRelationshipId](#BackingTable_InventOrderEntryDeadlineTableRelationshipId)||<a href="SalesOrderEntryDeadlineEntity.md" target="_blank">SalesAndMarketing/SalesOrderEntryDeadlineEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="SalesOrderEntryDeadlineEntity.md" target="_blank">SalesAndMarketing/SalesOrderEntryDeadlineEntity</a>|

### <a href=#DeadlineGroupCode name="DeadlineGroupCode">DeadlineGroupCode</a>

First included in: SalesAndMarketing/SalesOrderEntryDeadlineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeadlineGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesOrderEntryDeadlineGroupId name="SalesOrderEntryDeadlineGroupId">SalesOrderEntryDeadlineGroupId</a>

First included in: SalesAndMarketing/SalesOrderEntryDeadlineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesOrderEntryDeadlineGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SiteCode name="SiteCode">SiteCode</a>

First included in: SalesAndMarketing/SalesOrderEntryDeadlineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SiteCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SiteId name="SiteId">SiteId</a>

First included in: SalesAndMarketing/SalesOrderEntryDeadlineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LatestOrderEntryTimeMonday name="LatestOrderEntryTimeMonday">LatestOrderEntryTimeMonday</a>

First included in: SalesAndMarketing/SalesOrderEntryDeadlineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LatestOrderEntryTimeMonday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LatestOrderEntryTimeTuesday name="LatestOrderEntryTimeTuesday">LatestOrderEntryTimeTuesday</a>

First included in: SalesAndMarketing/SalesOrderEntryDeadlineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LatestOrderEntryTimeTuesday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LatestOrderEntryTimeWednesday name="LatestOrderEntryTimeWednesday">LatestOrderEntryTimeWednesday</a>

First included in: SalesAndMarketing/SalesOrderEntryDeadlineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LatestOrderEntryTimeWednesday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LatestOrderEntryTimeThursday name="LatestOrderEntryTimeThursday">LatestOrderEntryTimeThursday</a>

First included in: SalesAndMarketing/SalesOrderEntryDeadlineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LatestOrderEntryTimeThursday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LatestOrderEntryTimeFriday name="LatestOrderEntryTimeFriday">LatestOrderEntryTimeFriday</a>

First included in: SalesAndMarketing/SalesOrderEntryDeadlineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LatestOrderEntryTimeFriday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LatestOrderEntryTimeSaturday name="LatestOrderEntryTimeSaturday">LatestOrderEntryTimeSaturday</a>

First included in: SalesAndMarketing/SalesOrderEntryDeadlineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LatestOrderEntryTimeSaturday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LatestOrderEntryTimeSunday name="LatestOrderEntryTimeSunday">LatestOrderEntryTimeSunday</a>

First included in: SalesAndMarketing/SalesOrderEntryDeadlineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LatestOrderEntryTimeSunday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_InventOrderEntryDeadlineTableRelationshipId name="BackingTable_InventOrderEntryDeadlineTableRelationshipId">BackingTable_InventOrderEntryDeadlineTableRelationshipId</a>

First included in: SalesAndMarketing/SalesOrderEntryDeadlineEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_InventOrderEntryDeadlineTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Group/InventOrderEntryDeadlineTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Group/InventOrderEntryDeadlineTable.cdm.json/InventOrderEntryDeadlineTable</a></td><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Group/InventOrderEntryDeadlineTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: SalesAndMarketing/SalesOrderEntryDeadlineEntity (this entity)  

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
