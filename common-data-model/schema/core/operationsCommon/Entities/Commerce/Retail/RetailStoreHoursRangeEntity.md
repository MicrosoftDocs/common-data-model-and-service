---
title: RetailStoreHoursRangeEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# RetailStoreHoursRangeEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Commerce/Retail/RetailStoreHoursRangeEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[Description](#Description)||<a href="RetailStoreHoursRangeEntity.md" target="_blank">Retail/RetailStoreHoursRangeEntity</a>|
|[StartDate](#StartDate)||<a href="RetailStoreHoursRangeEntity.md" target="_blank">Retail/RetailStoreHoursRangeEntity</a>|
|[EndDate](#EndDate)||<a href="RetailStoreHoursRangeEntity.md" target="_blank">Retail/RetailStoreHoursRangeEntity</a>|
|[StoreHoursTemplateId](#StoreHoursTemplateId)||<a href="RetailStoreHoursRangeEntity.md" target="_blank">Retail/RetailStoreHoursRangeEntity</a>|
|[LineNum](#LineNum)||<a href="RetailStoreHoursRangeEntity.md" target="_blank">Retail/RetailStoreHoursRangeEntity</a>|
|[MondayOpenTime](#MondayOpenTime)||<a href="RetailStoreHoursRangeEntity.md" target="_blank">Retail/RetailStoreHoursRangeEntity</a>|
|[MondayCloseTime](#MondayCloseTime)||<a href="RetailStoreHoursRangeEntity.md" target="_blank">Retail/RetailStoreHoursRangeEntity</a>|
|[TuesdayOpenTime](#TuesdayOpenTime)||<a href="RetailStoreHoursRangeEntity.md" target="_blank">Retail/RetailStoreHoursRangeEntity</a>|
|[TuesdayCloseTime](#TuesdayCloseTime)||<a href="RetailStoreHoursRangeEntity.md" target="_blank">Retail/RetailStoreHoursRangeEntity</a>|
|[WednesdayOpenTime](#WednesdayOpenTime)||<a href="RetailStoreHoursRangeEntity.md" target="_blank">Retail/RetailStoreHoursRangeEntity</a>|
|[WednesdayCloseTime](#WednesdayCloseTime)||<a href="RetailStoreHoursRangeEntity.md" target="_blank">Retail/RetailStoreHoursRangeEntity</a>|
|[ThursdayOpenTime](#ThursdayOpenTime)||<a href="RetailStoreHoursRangeEntity.md" target="_blank">Retail/RetailStoreHoursRangeEntity</a>|
|[ThursdayCloseTime](#ThursdayCloseTime)||<a href="RetailStoreHoursRangeEntity.md" target="_blank">Retail/RetailStoreHoursRangeEntity</a>|
|[FridayOpenTime](#FridayOpenTime)||<a href="RetailStoreHoursRangeEntity.md" target="_blank">Retail/RetailStoreHoursRangeEntity</a>|
|[FridayCloseTime](#FridayCloseTime)||<a href="RetailStoreHoursRangeEntity.md" target="_blank">Retail/RetailStoreHoursRangeEntity</a>|
|[SaturdayOpenTime](#SaturdayOpenTime)||<a href="RetailStoreHoursRangeEntity.md" target="_blank">Retail/RetailStoreHoursRangeEntity</a>|
|[SaturdayCloseTime](#SaturdayCloseTime)||<a href="RetailStoreHoursRangeEntity.md" target="_blank">Retail/RetailStoreHoursRangeEntity</a>|
|[SundayOpenTime](#SundayOpenTime)||<a href="RetailStoreHoursRangeEntity.md" target="_blank">Retail/RetailStoreHoursRangeEntity</a>|
|[SundayCloseTime](#SundayCloseTime)||<a href="RetailStoreHoursRangeEntity.md" target="_blank">Retail/RetailStoreHoursRangeEntity</a>|
|[ClosedOnMonday](#ClosedOnMonday)||<a href="RetailStoreHoursRangeEntity.md" target="_blank">Retail/RetailStoreHoursRangeEntity</a>|
|[ClosedOnTuesday](#ClosedOnTuesday)||<a href="RetailStoreHoursRangeEntity.md" target="_blank">Retail/RetailStoreHoursRangeEntity</a>|
|[ClosedOnWednesday](#ClosedOnWednesday)||<a href="RetailStoreHoursRangeEntity.md" target="_blank">Retail/RetailStoreHoursRangeEntity</a>|
|[ClosedOnThursday](#ClosedOnThursday)||<a href="RetailStoreHoursRangeEntity.md" target="_blank">Retail/RetailStoreHoursRangeEntity</a>|
|[ClosedOnFriday](#ClosedOnFriday)||<a href="RetailStoreHoursRangeEntity.md" target="_blank">Retail/RetailStoreHoursRangeEntity</a>|
|[ClosedOnSaturday](#ClosedOnSaturday)||<a href="RetailStoreHoursRangeEntity.md" target="_blank">Retail/RetailStoreHoursRangeEntity</a>|
|[ClosedOnSunday](#ClosedOnSunday)||<a href="RetailStoreHoursRangeEntity.md" target="_blank">Retail/RetailStoreHoursRangeEntity</a>|
|[BackingTable_RetailStoreHoursRangeRelationshipId](#BackingTable_RetailStoreHoursRangeRelationshipId)||<a href="RetailStoreHoursRangeEntity.md" target="_blank">Retail/RetailStoreHoursRangeEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="RetailStoreHoursRangeEntity.md" target="_blank">Retail/RetailStoreHoursRangeEntity</a>|

### <a href=#Description name="Description">Description</a>

First included in: Retail/RetailStoreHoursRangeEntity (this entity)  

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

### <a href=#StartDate name="StartDate">StartDate</a>

First included in: Retail/RetailStoreHoursRangeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EndDate name="EndDate">EndDate</a>

First included in: Retail/RetailStoreHoursRangeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StoreHoursTemplateId name="StoreHoursTemplateId">StoreHoursTemplateId</a>

First included in: Retail/RetailStoreHoursRangeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StoreHoursTemplateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNum name="LineNum">LineNum</a>

First included in: Retail/RetailStoreHoursRangeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MondayOpenTime name="MondayOpenTime">MondayOpenTime</a>

First included in: Retail/RetailStoreHoursRangeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MondayOpenTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MondayCloseTime name="MondayCloseTime">MondayCloseTime</a>

First included in: Retail/RetailStoreHoursRangeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MondayCloseTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TuesdayOpenTime name="TuesdayOpenTime">TuesdayOpenTime</a>

First included in: Retail/RetailStoreHoursRangeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TuesdayOpenTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TuesdayCloseTime name="TuesdayCloseTime">TuesdayCloseTime</a>

First included in: Retail/RetailStoreHoursRangeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TuesdayCloseTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WednesdayOpenTime name="WednesdayOpenTime">WednesdayOpenTime</a>

First included in: Retail/RetailStoreHoursRangeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WednesdayOpenTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WednesdayCloseTime name="WednesdayCloseTime">WednesdayCloseTime</a>

First included in: Retail/RetailStoreHoursRangeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WednesdayCloseTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThursdayOpenTime name="ThursdayOpenTime">ThursdayOpenTime</a>

First included in: Retail/RetailStoreHoursRangeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThursdayOpenTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThursdayCloseTime name="ThursdayCloseTime">ThursdayCloseTime</a>

First included in: Retail/RetailStoreHoursRangeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThursdayCloseTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FridayOpenTime name="FridayOpenTime">FridayOpenTime</a>

First included in: Retail/RetailStoreHoursRangeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FridayOpenTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FridayCloseTime name="FridayCloseTime">FridayCloseTime</a>

First included in: Retail/RetailStoreHoursRangeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FridayCloseTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SaturdayOpenTime name="SaturdayOpenTime">SaturdayOpenTime</a>

First included in: Retail/RetailStoreHoursRangeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SaturdayOpenTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SaturdayCloseTime name="SaturdayCloseTime">SaturdayCloseTime</a>

First included in: Retail/RetailStoreHoursRangeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SaturdayCloseTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SundayOpenTime name="SundayOpenTime">SundayOpenTime</a>

First included in: Retail/RetailStoreHoursRangeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SundayOpenTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SundayCloseTime name="SundayCloseTime">SundayCloseTime</a>

First included in: Retail/RetailStoreHoursRangeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SundayCloseTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ClosedOnMonday name="ClosedOnMonday">ClosedOnMonday</a>

First included in: Retail/RetailStoreHoursRangeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClosedOnMonday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ClosedOnTuesday name="ClosedOnTuesday">ClosedOnTuesday</a>

First included in: Retail/RetailStoreHoursRangeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClosedOnTuesday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ClosedOnWednesday name="ClosedOnWednesday">ClosedOnWednesday</a>

First included in: Retail/RetailStoreHoursRangeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClosedOnWednesday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ClosedOnThursday name="ClosedOnThursday">ClosedOnThursday</a>

First included in: Retail/RetailStoreHoursRangeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClosedOnThursday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ClosedOnFriday name="ClosedOnFriday">ClosedOnFriday</a>

First included in: Retail/RetailStoreHoursRangeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClosedOnFriday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ClosedOnSaturday name="ClosedOnSaturday">ClosedOnSaturday</a>

First included in: Retail/RetailStoreHoursRangeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClosedOnSaturday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ClosedOnSunday name="ClosedOnSunday">ClosedOnSunday</a>

First included in: Retail/RetailStoreHoursRangeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ClosedOnSunday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_RetailStoreHoursRangeRelationshipId name="BackingTable_RetailStoreHoursRangeRelationshipId">BackingTable_RetailStoreHoursRangeRelationshipId</a>

First included in: Retail/RetailStoreHoursRangeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RetailStoreHoursRangeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Commerce/Retail/Miscellaneous/RetailStoreHoursRange.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Miscellaneous/RetailStoreHoursRange.cdm.json/RetailStoreHoursRange</a></td><td><a href="../../../Tables/Commerce/Retail/Miscellaneous/RetailStoreHoursRange.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: Retail/RetailStoreHoursRangeEntity (this entity)  

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
