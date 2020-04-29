---
title: TMSFreightBillDetail - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# Freight bill details

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/Transportation/WorksheetLine/TMSFreightBillDetail.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TMSFreightBillDetail/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Freight bill details</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[BillingGroupId](#BillingGroupId)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[BillOfLadingId](#BillOfLadingId)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[BookingNum](#BookingNum)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[CarrierCode](#CarrierCode)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[CarrierServiceCode](#CarrierServiceCode)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[CurrencyCode](#CurrencyCode)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[DeliveryUTCDateTime](#DeliveryUTCDateTime)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[DestinationPostalAddress](#DestinationPostalAddress)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[Dimension1](#Dimension1)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[Dimension10](#Dimension10)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[Dimension2](#Dimension2)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[Dimension3](#Dimension3)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[Dimension4](#Dimension4)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[Dimension5](#Dimension5)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[Dimension6](#Dimension6)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[Dimension7](#Dimension7)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[Dimension8](#Dimension8)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[Dimension9](#Dimension9)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[Direction](#Direction)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[EquipmentCode](#EquipmentCode)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[ExternalCode](#ExternalCode)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[FBRate](#FBRate)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[FreightBillId](#FreightBillId)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[FreightBillMatchStatus](#FreightBillMatchStatus)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[FreightBillTypeId](#FreightBillTypeId)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[HubMasterCode](#HubMasterCode)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[InventLocationId](#InventLocationId)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[InventSiteId](#InventSiteId)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[LineType](#LineType)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[LoadId](#LoadId)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[ModeCode](#ModeCode)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[OriginPostalAddress](#OriginPostalAddress)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[ProNum](#ProNum)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[Qty](#Qty)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[RateCur](#RateCur)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[RateId](#RateId)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[RateNote](#RateNote)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[RateUnit](#RateUnit)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[RateUnitRate](#RateUnitRate)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[RelatedAccountNum](#RelatedAccountNum)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[RelatedOrderNum](#RelatedOrderNum)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[RouteCode](#RouteCode)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[Sequence](#Sequence)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[ShipmentId](#ShipmentId)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[ShipUTCDateTime](#ShipUTCDateTime)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[STCCCode](#STCCCode)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[TractorNumber](#TractorNumber)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[TrailerNumber](#TrailerNumber)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[Value](#Value)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[VendorCode](#VendorCode)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[VendorInvoiceCode](#VendorInvoiceCode)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[VesselName](#VesselName)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[VoyageNum](#VoyageNum)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[Weight](#Weight)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[DataAreaId](#DataAreaId)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[Relationship_CurrencyRelationshipId](#Relationship_CurrencyRelationshipId)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[Relationship_InventLocationRelationshipId](#Relationship_InventLocationRelationshipId)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[Relationship_InventSiteRelationshipId](#Relationship_InventSiteRelationshipId)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[Relationship_LogisticsPostalAddressDestinationRelationshipId](#Relationship_LogisticsPostalAddressDestinationRelationshipId)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[Relationship_LogisticsPostalAddressOriginRelationshipId](#Relationship_LogisticsPostalAddressOriginRelationshipId)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[Relationship_TMSAccessorialMasterRelationshipId](#Relationship_TMSAccessorialMasterRelationshipId)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[Relationship_TMSBillingGroupRelationshipId](#Relationship_TMSBillingGroupRelationshipId)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[Relationship_TMSCarrierRelationshipId](#Relationship_TMSCarrierRelationshipId)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[Relationship_TMSEquipmentRelationshipId](#Relationship_TMSEquipmentRelationshipId)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[Relationship_TMSFreightBillTypeRelationshipId](#Relationship_TMSFreightBillTypeRelationshipId)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[Relationship_TMSHubMasterRelationshipId](#Relationship_TMSHubMasterRelationshipId)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[Relationship_TMSModeRelationshipId](#Relationship_TMSModeRelationshipId)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[Relationship_TMSRouteRelationshipId](#Relationship_TMSRouteRelationshipId)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[Relationship_VendTableRelationshipId](#Relationship_VendTableRelationshipId)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[Relationship_VendTableInvoiceRelationshipId](#Relationship_VendTableInvoiceRelationshipId)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[Relationship_WHSLoadTableRelationshipId](#Relationship_WHSLoadTableRelationshipId)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[Relationship_WHSShipmentTableRelationshipId](#Relationship_WHSShipmentTableRelationshipId)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="TMSFreightBillDetail.md" target="_blank">WorksheetLine/TMSFreightBillDetail</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TMSFreightBillDetail/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BillingGroupId name="BillingGroupId">BillingGroupId</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BillingGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BillOfLadingId name="BillOfLadingId">BillOfLadingId</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BillOfLadingId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BookingNum name="BookingNum">BookingNum</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BookingNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CarrierCode name="CarrierCode">CarrierCode</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CarrierCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CarrierServiceCode name="CarrierServiceCode">CarrierServiceCode</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CarrierServiceCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

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

### <a href=#DeliveryUTCDateTime name="DeliveryUTCDateTime">DeliveryUTCDateTime</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryUTCDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#DestinationPostalAddress name="DestinationPostalAddress">DestinationPostalAddress</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationPostalAddress attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Dimension1 name="Dimension1">Dimension1</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Dimension1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Dimension10 name="Dimension10">Dimension10</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Dimension10 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Dimension2 name="Dimension2">Dimension2</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Dimension2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Dimension3 name="Dimension3">Dimension3</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Dimension3 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Dimension4 name="Dimension4">Dimension4</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Dimension4 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Dimension5 name="Dimension5">Dimension5</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Dimension5 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Dimension6 name="Dimension6">Dimension6</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Dimension6 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Dimension7 name="Dimension7">Dimension7</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Dimension7 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Dimension8 name="Dimension8">Dimension8</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Dimension8 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Dimension9 name="Dimension9">Dimension9</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Dimension9 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Direction name="Direction">Direction</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Direction attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EquipmentCode name="EquipmentCode">EquipmentCode</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EquipmentCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExternalCode name="ExternalCode">ExternalCode</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExternalCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FBRate name="FBRate">FBRate</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FBRate attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#FreightBillId name="FreightBillId">FreightBillId</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FreightBillId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FreightBillMatchStatus name="FreightBillMatchStatus">FreightBillMatchStatus</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FreightBillMatchStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#FreightBillTypeId name="FreightBillTypeId">FreightBillTypeId</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FreightBillTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HubMasterCode name="HubMasterCode">HubMasterCode</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HubMasterCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventLocationId name="InventLocationId">InventLocationId</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventLocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventSiteId name="InventSiteId">InventSiteId</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineType name="LineType">LineType</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LoadId name="LoadId">LoadId</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoadId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ModeCode name="ModeCode">ModeCode</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ModeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OriginPostalAddress name="OriginPostalAddress">OriginPostalAddress</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginPostalAddress attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ProNum name="ProNum">ProNum</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Qty name="Qty">Qty</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Qty attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#RateCur name="RateCur">RateCur</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

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

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rate ID</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Rate ID</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RateNote name="RateNote">RateNote</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RateNote attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RateUnit name="RateUnit">RateUnit</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RateUnit attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#RateUnitRate name="RateUnitRate">RateUnitRate</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RateUnitRate attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#RelatedAccountNum name="RelatedAccountNum">RelatedAccountNum</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Account number</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RelatedAccountNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Account number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RelatedOrderNum name="RelatedOrderNum">RelatedOrderNum</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RelatedOrderNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RouteCode name="RouteCode">RouteCode</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RouteCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Sequence name="Sequence">Sequence</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Sequence attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ShipmentId name="ShipmentId">ShipmentId</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShipmentId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShipUTCDateTime name="ShipUTCDateTime">ShipUTCDateTime</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShipUTCDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#STCCCode name="STCCCode">STCCCode</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the STCCCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TractorNumber name="TractorNumber">TractorNumber</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TractorNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TrailerNumber name="TrailerNumber">TrailerNumber</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TrailerNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Value name="Value">Value</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Value attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorCode name="VendorCode">VendorCode</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorInvoiceCode name="VendorInvoiceCode">VendorInvoiceCode</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorInvoiceCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VesselName name="VesselName">VesselName</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VesselName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VoyageNum name="VoyageNum">VoyageNum</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VoyageNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Weight name="Weight">Weight</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Weight attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

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

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

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

### <a href=#Relationship_InventLocationRelationshipId name="Relationship_InventLocationRelationshipId">Relationship_InventLocationRelationshipId</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventLocationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Inventory/Group/InventLocation.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/InventLocation.cdm.json/InventLocation</a></td><td><a href="../../Inventory/Group/InventLocation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventSiteRelationshipId name="Relationship_InventSiteRelationshipId">Relationship_InventSiteRelationshipId</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventSiteRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Inventory/Group/InventSite.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/InventSite.cdm.json/InventSite</a></td><td><a href="../../Inventory/Group/InventSite.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LogisticsPostalAddressDestinationRelationshipId name="Relationship_LogisticsPostalAddressDestinationRelationshipId">Relationship_LogisticsPostalAddressDestinationRelationshipId</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LogisticsPostalAddressDestinationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Main/LogisticsPostalAddress.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Main/LogisticsPostalAddress.cdm.json/LogisticsPostalAddress</a></td><td><a href="../../../Common/GAB/Main/LogisticsPostalAddress.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LogisticsPostalAddressOriginRelationshipId name="Relationship_LogisticsPostalAddressOriginRelationshipId">Relationship_LogisticsPostalAddressOriginRelationshipId</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LogisticsPostalAddressOriginRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Main/LogisticsPostalAddress.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Main/LogisticsPostalAddress.cdm.json/LogisticsPostalAddress</a></td><td><a href="../../../Common/GAB/Main/LogisticsPostalAddress.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TMSAccessorialMasterRelationshipId name="Relationship_TMSAccessorialMasterRelationshipId">Relationship_TMSAccessorialMasterRelationshipId</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

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

### <a href=#Relationship_TMSBillingGroupRelationshipId name="Relationship_TMSBillingGroupRelationshipId">Relationship_TMSBillingGroupRelationshipId</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TMSBillingGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/TMSBillingGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Transportation/Group/TMSBillingGroup.cdm.json/TMSBillingGroup</a></td><td><a href="../Group/TMSBillingGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TMSCarrierRelationshipId name="Relationship_TMSCarrierRelationshipId">Relationship_TMSCarrierRelationshipId</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

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

### <a href=#Relationship_TMSEquipmentRelationshipId name="Relationship_TMSEquipmentRelationshipId">Relationship_TMSEquipmentRelationshipId</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TMSEquipmentRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/TMSEquipment.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Transportation/Group/TMSEquipment.cdm.json/TMSEquipment</a></td><td><a href="../Group/TMSEquipment.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TMSFreightBillTypeRelationshipId name="Relationship_TMSFreightBillTypeRelationshipId">Relationship_TMSFreightBillTypeRelationshipId</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TMSFreightBillTypeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/TMSFreightBillType.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Transportation/Main/TMSFreightBillType.cdm.json/TMSFreightBillType</a></td><td><a href="../Main/TMSFreightBillType.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TMSHubMasterRelationshipId name="Relationship_TMSHubMasterRelationshipId">Relationship_TMSHubMasterRelationshipId</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

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

### <a href=#Relationship_TMSModeRelationshipId name="Relationship_TMSModeRelationshipId">Relationship_TMSModeRelationshipId</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TMSModeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/TMSMode.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Transportation/Group/TMSMode.cdm.json/TMSMode</a></td><td><a href="../Group/TMSMode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TMSRouteRelationshipId name="Relationship_TMSRouteRelationshipId">Relationship_TMSRouteRelationshipId</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

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

### <a href=#Relationship_VendTableRelationshipId name="Relationship_VendTableRelationshipId">Relationship_VendTableRelationshipId</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

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

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

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

### <a href=#Relationship_WHSLoadTableRelationshipId name="Relationship_WHSLoadTableRelationshipId">Relationship_WHSLoadTableRelationshipId</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WHSLoadTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Inventory/WorksheetHeader/WHSLoadTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/WorksheetHeader/WHSLoadTable.cdm.json/WHSLoadTable</a></td><td><a href="../../Inventory/WorksheetHeader/WHSLoadTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WHSShipmentTableRelationshipId name="Relationship_WHSShipmentTableRelationshipId">Relationship_WHSShipmentTableRelationshipId</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WHSShipmentTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Inventory/WorksheetHeader/WHSShipmentTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/WorksheetHeader/WHSShipmentTable.cdm.json/WHSShipmentTable</a></td><td><a href="../../Inventory/WorksheetHeader/WHSShipmentTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetLine/TMSFreightBillDetail (this entity)  

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
