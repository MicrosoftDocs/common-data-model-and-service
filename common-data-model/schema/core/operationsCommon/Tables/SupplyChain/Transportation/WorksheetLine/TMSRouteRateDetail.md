---
title: TMSRouteRateDetail in WorksheetLine - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Route rate details in WorksheetLine(TMSRouteRateDetail)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/Transportation/WorksheetLine/TMSRouteRateDetail.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TMSRouteRateDetail/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Route rate details</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="TMSRouteRateDetail.md" target="_blank">WorksheetLine/TMSRouteRateDetail</a>|
|[AccessorialAssignmentLevel](#AccessorialAssignmentLevel)||<a href="TMSRouteRateDetail.md" target="_blank">WorksheetLine/TMSRouteRateDetail</a>|
|[BillingGroupId](#BillingGroupId)||<a href="TMSRouteRateDetail.md" target="_blank">WorksheetLine/TMSRouteRateDetail</a>|
|[CarrierCode](#CarrierCode)||<a href="TMSRouteRateDetail.md" target="_blank">WorksheetLine/TMSRouteRateDetail</a>|
|[CarrierServiceCode](#CarrierServiceCode)||<a href="TMSRouteRateDetail.md" target="_blank">WorksheetLine/TMSRouteRateDetail</a>|
|[CurrencyCode](#CurrencyCode)||<a href="TMSRouteRateDetail.md" target="_blank">WorksheetLine/TMSRouteRateDetail</a>|
|[CustomerRate](#CustomerRate)||<a href="TMSRouteRateDetail.md" target="_blank">WorksheetLine/TMSRouteRateDetail</a>|
|[ExternalCode](#ExternalCode)||<a href="TMSRouteRateDetail.md" target="_blank">WorksheetLine/TMSRouteRateDetail</a>|
|[Generated](#Generated)||<a href="TMSRouteRateDetail.md" target="_blank">WorksheetLine/TMSRouteRateDetail</a>|
|[HubMasterCode](#HubMasterCode)||<a href="TMSRouteRateDetail.md" target="_blank">WorksheetLine/TMSRouteRateDetail</a>|
|[Id](#Id)||<a href="TMSRouteRateDetail.md" target="_blank">WorksheetLine/TMSRouteRateDetail</a>|
|[MarkupCode](#MarkupCode)||<a href="TMSRouteRateDetail.md" target="_blank">WorksheetLine/TMSRouteRateDetail</a>|
|[ModuleType](#ModuleType)||<a href="TMSRouteRateDetail.md" target="_blank">WorksheetLine/TMSRouteRateDetail</a>|
|[RateCur](#RateCur)||<a href="TMSRouteRateDetail.md" target="_blank">WorksheetLine/TMSRouteRateDetail</a>|
|[RateId](#RateId)||<a href="TMSRouteRateDetail.md" target="_blank">WorksheetLine/TMSRouteRateDetail</a>|
|[RateNote](#RateNote)||<a href="TMSRouteRateDetail.md" target="_blank">WorksheetLine/TMSRouteRateDetail</a>|
|[RateType](#RateType)||<a href="TMSRouteRateDetail.md" target="_blank">WorksheetLine/TMSRouteRateDetail</a>|
|[RateUnit](#RateUnit)||<a href="TMSRouteRateDetail.md" target="_blank">WorksheetLine/TMSRouteRateDetail</a>|
|[RateUnitRate](#RateUnitRate)||<a href="TMSRouteRateDetail.md" target="_blank">WorksheetLine/TMSRouteRateDetail</a>|
|[ResponsibleForPayment](#ResponsibleForPayment)||<a href="TMSRouteRateDetail.md" target="_blank">WorksheetLine/TMSRouteRateDetail</a>|
|[RouteAccessorialLevel](#RouteAccessorialLevel)||<a href="TMSRouteRateDetail.md" target="_blank">WorksheetLine/TMSRouteRateDetail</a>|
|[RouteCode](#RouteCode)||<a href="TMSRouteRateDetail.md" target="_blank">WorksheetLine/TMSRouteRateDetail</a>|
|[Sequence](#Sequence)||<a href="TMSRouteRateDetail.md" target="_blank">WorksheetLine/TMSRouteRateDetail</a>|
|[ShipperRate](#ShipperRate)||<a href="TMSRouteRateDetail.md" target="_blank">WorksheetLine/TMSRouteRateDetail</a>|
|[VendorCode](#VendorCode)||<a href="TMSRouteRateDetail.md" target="_blank">WorksheetLine/TMSRouteRateDetail</a>|
|[VendorInvoiceCode](#VendorInvoiceCode)||<a href="TMSRouteRateDetail.md" target="_blank">WorksheetLine/TMSRouteRateDetail</a>|
|[DataAreaId](#DataAreaId)||<a href="TMSRouteRateDetail.md" target="_blank">WorksheetLine/TMSRouteRateDetail</a>|
|[Relationship_CurrencyRelationshipId](#Relationship_CurrencyRelationshipId)||<a href="TMSRouteRateDetail.md" target="_blank">WorksheetLine/TMSRouteRateDetail</a>|
|[Relationship_TMSAccessorialMasterRelationshipId](#Relationship_TMSAccessorialMasterRelationshipId)||<a href="TMSRouteRateDetail.md" target="_blank">WorksheetLine/TMSRouteRateDetail</a>|
|[Relationship_TMSCarrierRelationshipId](#Relationship_TMSCarrierRelationshipId)||<a href="TMSRouteRateDetail.md" target="_blank">WorksheetLine/TMSRouteRateDetail</a>|
|[Relationship_TMSCarrierServiceRelationshipId](#Relationship_TMSCarrierServiceRelationshipId)||<a href="TMSRouteRateDetail.md" target="_blank">WorksheetLine/TMSRouteRateDetail</a>|
|[Relationship_TMSHubMasterRelationshipId](#Relationship_TMSHubMasterRelationshipId)||<a href="TMSRouteRateDetail.md" target="_blank">WorksheetLine/TMSRouteRateDetail</a>|
|[Relationship_TMSRouteRelationshipId](#Relationship_TMSRouteRelationshipId)||<a href="TMSRouteRateDetail.md" target="_blank">WorksheetLine/TMSRouteRateDetail</a>|
|[Relationship_TMSRouteSegmentRelationshipId](#Relationship_TMSRouteSegmentRelationshipId)||<a href="TMSRouteRateDetail.md" target="_blank">WorksheetLine/TMSRouteRateDetail</a>|
|[Relationship_TMSRouteSegmentLoadRelationshipId](#Relationship_TMSRouteSegmentLoadRelationshipId)||<a href="TMSRouteRateDetail.md" target="_blank">WorksheetLine/TMSRouteRateDetail</a>|
|[Relationship_TMSRouteSegmentShipmentRelationshipId](#Relationship_TMSRouteSegmentShipmentRelationshipId)||<a href="TMSRouteRateDetail.md" target="_blank">WorksheetLine/TMSRouteRateDetail</a>|
|[Relationship_VendTableRelationshipId](#Relationship_VendTableRelationshipId)||<a href="TMSRouteRateDetail.md" target="_blank">WorksheetLine/TMSRouteRateDetail</a>|
|[Relationship_VendTableInvoiceRelationshipId](#Relationship_VendTableInvoiceRelationshipId)||<a href="TMSRouteRateDetail.md" target="_blank">WorksheetLine/TMSRouteRateDetail</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="TMSRouteRateDetail.md" target="_blank">WorksheetLine/TMSRouteRateDetail</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetLine/TMSRouteRateDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TMSRouteRateDetail/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AccessorialAssignmentLevel name="AccessorialAssignmentLevel">AccessorialAssignmentLevel</a>

First included in: WorksheetLine/TMSRouteRateDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccessorialAssignmentLevel attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#BillingGroupId name="BillingGroupId">BillingGroupId</a>

First included in: WorksheetLine/TMSRouteRateDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BillingGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CarrierCode name="CarrierCode">CarrierCode</a>

First included in: WorksheetLine/TMSRouteRateDetail (this entity)  

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

### <a href=#CarrierServiceCode name="CarrierServiceCode">CarrierServiceCode</a>

First included in: WorksheetLine/TMSRouteRateDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CarrierServiceCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: WorksheetLine/TMSRouteRateDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerRate name="CustomerRate">CustomerRate</a>

First included in: WorksheetLine/TMSRouteRateDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerRate attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ExternalCode name="ExternalCode">ExternalCode</a>

First included in: WorksheetLine/TMSRouteRateDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExternalCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Generated name="Generated">Generated</a>

First included in: WorksheetLine/TMSRouteRateDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Generated attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#HubMasterCode name="HubMasterCode">HubMasterCode</a>

First included in: WorksheetLine/TMSRouteRateDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HubMasterCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Id name="Id">Id</a>

First included in: WorksheetLine/TMSRouteRateDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Id attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MarkupCode name="MarkupCode">MarkupCode</a>

First included in: WorksheetLine/TMSRouteRateDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MarkupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ModuleType name="ModuleType">ModuleType</a>

First included in: WorksheetLine/TMSRouteRateDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ModuleType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RateCur name="RateCur">RateCur</a>

First included in: WorksheetLine/TMSRouteRateDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RateCur attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#RateId name="RateId">RateId</a>

First included in: WorksheetLine/TMSRouteRateDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rate ID</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Rate ID</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RateNote name="RateNote">RateNote</a>

First included in: WorksheetLine/TMSRouteRateDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RateNote attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RateType name="RateType">RateType</a>

First included in: WorksheetLine/TMSRouteRateDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RateType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RateUnit name="RateUnit">RateUnit</a>

First included in: WorksheetLine/TMSRouteRateDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RateUnit attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#RateUnitRate name="RateUnitRate">RateUnitRate</a>

First included in: WorksheetLine/TMSRouteRateDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RateUnitRate attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ResponsibleForPayment name="ResponsibleForPayment">ResponsibleForPayment</a>

First included in: WorksheetLine/TMSRouteRateDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResponsibleForPayment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RouteAccessorialLevel name="RouteAccessorialLevel">RouteAccessorialLevel</a>

First included in: WorksheetLine/TMSRouteRateDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RouteAccessorialLevel attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RouteCode name="RouteCode">RouteCode</a>

First included in: WorksheetLine/TMSRouteRateDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RouteCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Sequence name="Sequence">Sequence</a>

First included in: WorksheetLine/TMSRouteRateDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Sequence attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ShipperRate name="ShipperRate">ShipperRate</a>

First included in: WorksheetLine/TMSRouteRateDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShipperRate attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#VendorCode name="VendorCode">VendorCode</a>

First included in: WorksheetLine/TMSRouteRateDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorInvoiceCode name="VendorInvoiceCode">VendorInvoiceCode</a>

First included in: WorksheetLine/TMSRouteRateDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorInvoiceCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetLine/TMSRouteRateDetail (this entity)  

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

### <a href=#Relationship_CurrencyRelationshipId name="Relationship_CurrencyRelationshipId">Relationship_CurrencyRelationshipId</a>

First included in: WorksheetLine/TMSRouteRateDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CurrencyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Currency/Group/Currency.md" target="_blank">/core/operationsCommon/Tables/Common/Currency/Group/Currency.cdm.json/Currency</a></td><td><a href="../../../Common/Currency/Group/Currency.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TMSAccessorialMasterRelationshipId name="Relationship_TMSAccessorialMasterRelationshipId">Relationship_TMSAccessorialMasterRelationshipId</a>

First included in: WorksheetLine/TMSRouteRateDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TMSAccessorialMasterRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/TMSAccessorialMaster.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Transportation/Main/TMSAccessorialMaster.cdm.json/TMSAccessorialMaster</a></td><td><a href="../Main/TMSAccessorialMaster.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TMSCarrierRelationshipId name="Relationship_TMSCarrierRelationshipId">Relationship_TMSCarrierRelationshipId</a>

First included in: WorksheetLine/TMSRouteRateDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TMSCarrierRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/TMSCarrier.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Transportation/Main/TMSCarrier.cdm.json/TMSCarrier</a></td><td><a href="../Main/TMSCarrier.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TMSCarrierServiceRelationshipId name="Relationship_TMSCarrierServiceRelationshipId">Relationship_TMSCarrierServiceRelationshipId</a>

First included in: WorksheetLine/TMSRouteRateDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TMSCarrierServiceRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/TMSCarrierService.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Transportation/Group/TMSCarrierService.cdm.json/TMSCarrierService</a></td><td><a href="../Group/TMSCarrierService.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TMSHubMasterRelationshipId name="Relationship_TMSHubMasterRelationshipId">Relationship_TMSHubMasterRelationshipId</a>

First included in: WorksheetLine/TMSRouteRateDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TMSHubMasterRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/TMSHubMaster.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Transportation/Group/TMSHubMaster.cdm.json/TMSHubMaster</a></td><td><a href="../Group/TMSHubMaster.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TMSRouteRelationshipId name="Relationship_TMSRouteRelationshipId">Relationship_TMSRouteRelationshipId</a>

First included in: WorksheetLine/TMSRouteRateDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TMSRouteRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/TMSRoute.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Transportation/Main/TMSRoute.cdm.json/TMSRoute</a></td><td><a href="../Main/TMSRoute.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TMSRouteSegmentRelationshipId name="Relationship_TMSRouteSegmentRelationshipId">Relationship_TMSRouteSegmentRelationshipId</a>

First included in: WorksheetLine/TMSRouteRateDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TMSRouteSegmentRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TMSRouteSegment.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Transportation/WorksheetLine/TMSRouteSegment.cdm.json/TMSRouteSegment</a></td><td><a href="TMSRouteSegment.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TMSRouteSegmentLoadRelationshipId name="Relationship_TMSRouteSegmentLoadRelationshipId">Relationship_TMSRouteSegmentLoadRelationshipId</a>

First included in: WorksheetLine/TMSRouteRateDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TMSRouteSegmentLoadRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/TMSRouteSegmentLoad.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Transportation/Transaction/TMSRouteSegmentLoad.cdm.json/TMSRouteSegmentLoad</a></td><td><a href="../Transaction/TMSRouteSegmentLoad.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TMSRouteSegmentShipmentRelationshipId name="Relationship_TMSRouteSegmentShipmentRelationshipId">Relationship_TMSRouteSegmentShipmentRelationshipId</a>

First included in: WorksheetLine/TMSRouteRateDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TMSRouteSegmentShipmentRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/TMSRouteSegmentShipment.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Transportation/Transaction/TMSRouteSegmentShipment.cdm.json/TMSRouteSegmentShipment</a></td><td><a href="../Transaction/TMSRouteSegmentShipment.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendTableRelationshipId name="Relationship_VendTableRelationshipId">Relationship_VendTableRelationshipId</a>

First included in: WorksheetLine/TMSRouteRateDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Vendor/Main/VendTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Vendor/Main/VendTable.cdm.json/VendTable</a></td><td><a href="../../Vendor/Main/VendTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendTableInvoiceRelationshipId name="Relationship_VendTableInvoiceRelationshipId">Relationship_VendTableInvoiceRelationshipId</a>

First included in: WorksheetLine/TMSRouteRateDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendTableInvoiceRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Vendor/Main/VendTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Vendor/Main/VendTable.cdm.json/VendTable</a></td><td><a href="../../Vendor/Main/VendTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetLine/TMSRouteRateDetail (this entity)  

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
