---
title: TrvEnhancedCarRentalData - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# TrvEnhancedCarRentalData

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Expense/WorksheetLine/TrvEnhancedCarRentalData.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TrvEnhancedCarRentalData/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="TrvEnhancedCarRentalData.md" target="_blank">WorksheetLine/TrvEnhancedCarRentalData</a>|
|[InstanceRelationType](#InstanceRelationType)||<a href="TrvEnhancedCarRentalData.md" target="_blank">WorksheetLine/TrvEnhancedCarRentalData</a>|
|[PBSRecid](#PBSRecid)||<a href="TrvEnhancedCarRentalData.md" target="_blank">WorksheetLine/TrvEnhancedCarRentalData</a>|
|[TransactionRecord](#TransactionRecord)||<a href="TrvEnhancedCarRentalData.md" target="_blank">WorksheetLine/TrvEnhancedCarRentalData</a>|
|[Relationship_TrvPBSMaindataRelationshipId](#Relationship_TrvPBSMaindataRelationshipId)||<a href="TrvEnhancedCarRentalData.md" target="_blank">WorksheetLine/TrvEnhancedCarRentalData</a>|
|[Relationship_TrvExpTransRelationshipId](#Relationship_TrvExpTransRelationshipId)||<a href="TrvEnhancedCarRentalData.md" target="_blank">WorksheetLine/TrvEnhancedCarRentalData</a>|
|[CarRentalCheckOutDate](#CarRentalCheckOutDate)||<a href="TrvEnhancedCarRentalData.md" target="_blank">WorksheetLine/TrvEnhancedCarRentalData</a>|
|[CheckOutLocation](#CheckOutLocation)||<a href="TrvEnhancedCarRentalData.md" target="_blank">WorksheetLine/TrvEnhancedCarRentalData</a>|
|[DailyRentalRate](#DailyRentalRate)||<a href="TrvEnhancedCarRentalData.md" target="_blank">WorksheetLine/TrvEnhancedCarRentalData</a>|
|[DaysRented](#DaysRented)||<a href="TrvEnhancedCarRentalData.md" target="_blank">WorksheetLine/TrvEnhancedCarRentalData</a>|
|[MonthlyRentalRate](#MonthlyRentalRate)||<a href="TrvEnhancedCarRentalData.md" target="_blank">WorksheetLine/TrvEnhancedCarRentalData</a>|
|[RegularMileageCharges](#RegularMileageCharges)||<a href="TrvEnhancedCarRentalData.md" target="_blank">WorksheetLine/TrvEnhancedCarRentalData</a>|
|[RenterName](#RenterName)||<a href="TrvEnhancedCarRentalData.md" target="_blank">WorksheetLine/TrvEnhancedCarRentalData</a>|
|[ReservationNumber](#ReservationNumber)||<a href="TrvEnhancedCarRentalData.md" target="_blank">WorksheetLine/TrvEnhancedCarRentalData</a>|
|[ReturnDate](#ReturnDate)||<a href="TrvEnhancedCarRentalData.md" target="_blank">WorksheetLine/TrvEnhancedCarRentalData</a>|
|[ReturnLocation](#ReturnLocation)||<a href="TrvEnhancedCarRentalData.md" target="_blank">WorksheetLine/TrvEnhancedCarRentalData</a>|
|[TotalMiles](#TotalMiles)||<a href="TrvEnhancedCarRentalData.md" target="_blank">WorksheetLine/TrvEnhancedCarRentalData</a>|
|[VehicleClass](#VehicleClass)||<a href="TrvEnhancedCarRentalData.md" target="_blank">WorksheetLine/TrvEnhancedCarRentalData</a>|
|[WeeklyRentalRate](#WeeklyRentalRate)||<a href="TrvEnhancedCarRentalData.md" target="_blank">WorksheetLine/TrvEnhancedCarRentalData</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetLine/TrvEnhancedCarRentalData (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TrvEnhancedCarRentalData/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#InstanceRelationType name="InstanceRelationType">InstanceRelationType</a>

First included in: WorksheetLine/TrvEnhancedCarRentalData (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InstanceRelationType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PBSRecid name="PBSRecid">PBSRecid</a>

First included in: WorksheetLine/TrvEnhancedCarRentalData (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PBSRecid attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TransactionRecord name="TransactionRecord">TransactionRecord</a>

First included in: WorksheetLine/TrvEnhancedCarRentalData (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionRecord attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_TrvPBSMaindataRelationshipId name="Relationship_TrvPBSMaindataRelationshipId">Relationship_TrvPBSMaindataRelationshipId</a>

First included in: WorksheetLine/TrvEnhancedCarRentalData (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TrvPBSMaindataRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TrvPBSMaindata.md" target="_blank">/core/operationsCommon/Tables/Finance/Expense/WorksheetLine/TrvPBSMaindata.cdm.json/TrvPBSMaindata</a></td><td><a href="TrvPBSMaindata.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TrvExpTransRelationshipId name="Relationship_TrvExpTransRelationshipId">Relationship_TrvExpTransRelationshipId</a>

First included in: WorksheetLine/TrvEnhancedCarRentalData (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TrvExpTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/TrvExpTrans.md" target="_blank">/core/operationsCommon/Tables/Finance/Expense/Transaction/TrvExpTrans.cdm.json/TrvExpTrans</a></td><td><a href="../Transaction/TrvExpTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CarRentalCheckOutDate name="CarRentalCheckOutDate">CarRentalCheckOutDate</a>

First included in: WorksheetLine/TrvEnhancedCarRentalData (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CarRentalCheckOutDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#CheckOutLocation name="CheckOutLocation">CheckOutLocation</a>

First included in: WorksheetLine/TrvEnhancedCarRentalData (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CheckOutLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DailyRentalRate name="DailyRentalRate">DailyRentalRate</a>

First included in: WorksheetLine/TrvEnhancedCarRentalData (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DailyRentalRate attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DaysRented name="DaysRented">DaysRented</a>

First included in: WorksheetLine/TrvEnhancedCarRentalData (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DaysRented attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#MonthlyRentalRate name="MonthlyRentalRate">MonthlyRentalRate</a>

First included in: WorksheetLine/TrvEnhancedCarRentalData (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MonthlyRentalRate attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#RegularMileageCharges name="RegularMileageCharges">RegularMileageCharges</a>

First included in: WorksheetLine/TrvEnhancedCarRentalData (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RegularMileageCharges attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#RenterName name="RenterName">RenterName</a>

First included in: WorksheetLine/TrvEnhancedCarRentalData (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RenterName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReservationNumber name="ReservationNumber">ReservationNumber</a>

First included in: WorksheetLine/TrvEnhancedCarRentalData (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReservationNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnDate name="ReturnDate">ReturnDate</a>

First included in: WorksheetLine/TrvEnhancedCarRentalData (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#ReturnLocation name="ReturnLocation">ReturnLocation</a>

First included in: WorksheetLine/TrvEnhancedCarRentalData (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnLocation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalMiles name="TotalMiles">TotalMiles</a>

First included in: WorksheetLine/TrvEnhancedCarRentalData (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalMiles attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#VehicleClass name="VehicleClass">VehicleClass</a>

First included in: WorksheetLine/TrvEnhancedCarRentalData (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VehicleClass attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#WeeklyRentalRate name="WeeklyRentalRate">WeeklyRentalRate</a>

First included in: WorksheetLine/TrvEnhancedCarRentalData (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WeeklyRentalRate attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>
