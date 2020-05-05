---
title: TrvEnhancedTripLegDetail - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 5/5/2020
ms.author: nebanfic
---

# Enhanced trip leg detail

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Expense/WorksheetLine/TrvEnhancedTripLegDetail.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TrvEnhancedTripLegDetail/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Enhanced trip leg detail</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="TrvEnhancedTripLegDetail.md" target="_blank">WorksheetLine/TrvEnhancedTripLegDetail</a>|
|[ArrivalDate](#ArrivalDate)||<a href="TrvEnhancedTripLegDetail.md" target="_blank">WorksheetLine/TrvEnhancedTripLegDetail</a>|
|[CarrierCode](#CarrierCode)||<a href="TrvEnhancedTripLegDetail.md" target="_blank">WorksheetLine/TrvEnhancedTripLegDetail</a>|
|[CityOfOrigin](#CityOfOrigin)||<a href="TrvEnhancedTripLegDetail.md" target="_blank">WorksheetLine/TrvEnhancedTripLegDetail</a>|
|[DepartureTax](#DepartureTax)||<a href="TrvEnhancedTripLegDetail.md" target="_blank">WorksheetLine/TrvEnhancedTripLegDetail</a>|
|[DestinationCity](#DestinationCity)||<a href="TrvEnhancedTripLegDetail.md" target="_blank">WorksheetLine/TrvEnhancedTripLegDetail</a>|
|[FareAmount](#FareAmount)||<a href="TrvEnhancedTripLegDetail.md" target="_blank">WorksheetLine/TrvEnhancedTripLegDetail</a>|
|[FeeAmount](#FeeAmount)||<a href="TrvEnhancedTripLegDetail.md" target="_blank">WorksheetLine/TrvEnhancedTripLegDetail</a>|
|[FlightNumber](#FlightNumber)||<a href="TrvEnhancedTripLegDetail.md" target="_blank">WorksheetLine/TrvEnhancedTripLegDetail</a>|
|[ItineraryRecId](#ItineraryRecId)||<a href="TrvEnhancedTripLegDetail.md" target="_blank">WorksheetLine/TrvEnhancedTripLegDetail</a>|
|[ServiceClass](#ServiceClass)||<a href="TrvEnhancedTripLegDetail.md" target="_blank">WorksheetLine/TrvEnhancedTripLegDetail</a>|
|[StopOverCity](#StopOverCity)||<a href="TrvEnhancedTripLegDetail.md" target="_blank">WorksheetLine/TrvEnhancedTripLegDetail</a>|
|[TaxAmount](#TaxAmount)||<a href="TrvEnhancedTripLegDetail.md" target="_blank">WorksheetLine/TrvEnhancedTripLegDetail</a>|
|[TravelDate](#TravelDate)||<a href="TrvEnhancedTripLegDetail.md" target="_blank">WorksheetLine/TrvEnhancedTripLegDetail</a>|
|[TripLegNumber](#TripLegNumber)||<a href="TrvEnhancedTripLegDetail.md" target="_blank">WorksheetLine/TrvEnhancedTripLegDetail</a>|
|[Relationship_ItineraryRelationshipId](#Relationship_ItineraryRelationshipId)||<a href="TrvEnhancedTripLegDetail.md" target="_blank">WorksheetLine/TrvEnhancedTripLegDetail</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetLine/TrvEnhancedTripLegDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TrvEnhancedTripLegDetail/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ArrivalDate name="ArrivalDate">ArrivalDate</a>

First included in: WorksheetLine/TrvEnhancedTripLegDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ArrivalDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#CarrierCode name="CarrierCode">CarrierCode</a>

First included in: WorksheetLine/TrvEnhancedTripLegDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CarrierCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CityOfOrigin name="CityOfOrigin">CityOfOrigin</a>

First included in: WorksheetLine/TrvEnhancedTripLegDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CityOfOrigin attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DepartureTax name="DepartureTax">DepartureTax</a>

First included in: WorksheetLine/TrvEnhancedTripLegDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DepartureTax attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DestinationCity name="DestinationCity">DestinationCity</a>

First included in: WorksheetLine/TrvEnhancedTripLegDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationCity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FareAmount name="FareAmount">FareAmount</a>

First included in: WorksheetLine/TrvEnhancedTripLegDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FareAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#FeeAmount name="FeeAmount">FeeAmount</a>

First included in: WorksheetLine/TrvEnhancedTripLegDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FeeAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#FlightNumber name="FlightNumber">FlightNumber</a>

First included in: WorksheetLine/TrvEnhancedTripLegDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FlightNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItineraryRecId name="ItineraryRecId">ItineraryRecId</a>

First included in: WorksheetLine/TrvEnhancedTripLegDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItineraryRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ServiceClass name="ServiceClass">ServiceClass</a>

First included in: WorksheetLine/TrvEnhancedTripLegDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceClass attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#StopOverCity name="StopOverCity">StopOverCity</a>

First included in: WorksheetLine/TrvEnhancedTripLegDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StopOverCity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxAmount name="TaxAmount">TaxAmount</a>

First included in: WorksheetLine/TrvEnhancedTripLegDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TravelDate name="TravelDate">TravelDate</a>

First included in: WorksheetLine/TrvEnhancedTripLegDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TravelDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#TripLegNumber name="TripLegNumber">TripLegNumber</a>

First included in: WorksheetLine/TrvEnhancedTripLegDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TripLegNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Relationship_ItineraryRelationshipId name="Relationship_ItineraryRelationshipId">Relationship_ItineraryRelationshipId</a>

First included in: WorksheetLine/TrvEnhancedTripLegDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ItineraryRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TrvEnhancedItineraryData.md" target="_blank">/core/operationsCommon/Tables/Finance/Expense/WorksheetLine/TrvEnhancedItineraryData.cdm.json/TrvEnhancedItineraryData</a></td><td><a href="TrvEnhancedItineraryData.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
