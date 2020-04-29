---
title: WHSLoadTable - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# Loads

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/Inventory/WorksheetHeader/WHSLoadTable.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[WHSLoadTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Loads</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[CarrierCode](#CarrierCode)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[OriginHubCode](#OriginHubCode)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[AccountNum](#AccountNum)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[ActualGrossWeight](#ActualGrossWeight)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[ActualNetWeight](#ActualNetWeight)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[ActualTareWeight](#ActualTareWeight)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[BillOfLadingId](#BillOfLadingId)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[BookingNum](#BookingNum)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[BrokerCode](#BrokerCode)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[CarNumber](#CarNumber)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[CarrierGroupCode](#CarrierGroupCode)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[CarrierServiceCode](#CarrierServiceCode)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[CustVendRef](#CustVendRef)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[CutOffUTCDateTime](#CutOffUTCDateTime)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[DestinationHubCode](#DestinationHubCode)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[DestinationName](#DestinationName)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[DestinationPostalAddress](#DestinationPostalAddress)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[ETA](#ETA)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[ETD](#ETD)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[FinalDestination](#FinalDestination)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[HouseBill](#HouseBill)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[InspectionSeal](#InspectionSeal)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[Invalid](#Invalid)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[InventLocationId](#InventLocationId)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[InventSiteId](#InventSiteId)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[LastUpdateUTCDateTime](#LastUpdateUTCDateTime)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[LateShipReasonCode](#LateShipReasonCode)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[LoadArrivalUTCDateTime](#LoadArrivalUTCDateTime)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[LoadDepth](#LoadDepth)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[LoadDirection](#LoadDirection)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[Loader](#Loader)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[LoadFloorStack](#LoadFloorStack)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[LoadHeight](#LoadHeight)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[LoadId](#LoadId)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[LoadNetWeight](#LoadNetWeight)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[LoadPaysFreight](#LoadPaysFreight)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[LoadReferenceNum](#LoadReferenceNum)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[LoadSchedShipUTCDateTime](#LoadSchedShipUTCDateTime)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[LoadShipConfirmUTCDateTime](#LoadShipConfirmUTCDateTime)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[LoadStatus](#LoadStatus)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[LoadTemplateId](#LoadTemplateId)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[LoadTipVolume](#LoadTipVolume)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[LoadTipWeight](#LoadTipWeight)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[LoadUserDef1](#LoadUserDef1)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[LoadUserDef2](#LoadUserDef2)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[LoadUserDef3](#LoadUserDef3)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[LoadWeight](#LoadWeight)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[LoadWidth](#LoadWidth)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[MaxFreightPieces](#MaxFreightPieces)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[ModeCode](#ModeCode)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[OrderNum](#OrderNum)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[OriginName](#OriginName)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[OriginPostalAddress](#OriginPostalAddress)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[ProNum](#ProNum)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[RequiredSailUTCDateTime](#RequiredSailUTCDateTime)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[RouteCode](#RouteCode)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[SailUTCDateTime](#SailUTCDateTime)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[SealNum](#SealNum)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[SystemTareWeight](#SystemTareWeight)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[TractorNumber](#TractorNumber)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[TrailerNumber](#TrailerNumber)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[TransportationTemplateId](#TransportationTemplateId)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[VesselName](#VesselName)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[VoyageNum](#VoyageNum)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[CarState_BR](#CarState_BR)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[PackingSlipType](#PackingSlipType)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[ActualVolume](#ActualVolume)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[LoadingStrategy](#LoadingStrategy)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[AllowLoadSplitShipConfirm](#AllowLoadSplitShipConfirm)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[LoadBuildTemplateName](#LoadBuildTemplateName)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[CredManInCreditControl](#CredManInCreditControl)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[DataAreaId](#DataAreaId)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[Relationship_InventLocationRelationshipId](#Relationship_InventLocationRelationshipId)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[Relationship_InventSiteRelationshipId](#Relationship_InventSiteRelationshipId)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[Relationship_LogisitcsPostalAddressOriginRelationshipId](#Relationship_LogisitcsPostalAddressOriginRelationshipId)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[Relationship_LogisticsPostalAddressDestinationRelationshipId](#Relationship_LogisticsPostalAddressDestinationRelationshipId)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[Relationship_TMSBrokerRelationshipId](#Relationship_TMSBrokerRelationshipId)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[Relationship_TMSCarrierRelationshipId](#Relationship_TMSCarrierRelationshipId)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[Relationship_TMSCarrierGroupRelationshipId](#Relationship_TMSCarrierGroupRelationshipId)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[Relationship_TMSCarrierServiceRelationshipId](#Relationship_TMSCarrierServiceRelationshipId)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[Relationship_TMSHubMasterDestRelationshipId](#Relationship_TMSHubMasterDestRelationshipId)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[Relationship_TMSHubMasterOriginRelationshipId](#Relationship_TMSHubMasterOriginRelationshipId)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[Relationship_TMSLateShipReasonRelationshipId](#Relationship_TMSLateShipReasonRelationshipId)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[Relationship_TMSModeRelationshipId](#Relationship_TMSModeRelationshipId)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[Relationship_TMSRouteRelationshipId](#Relationship_TMSRouteRelationshipId)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[Relationship_TMSTransportationTemplateRelationshipId](#Relationship_TMSTransportationTemplateRelationshipId)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[Relationship_WHSLoadTemplateRelationshipId](#Relationship_WHSLoadTemplateRelationshipId)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[Relationship_WHSLoadBuildTemplateRelationshipId](#Relationship_WHSLoadBuildTemplateRelationshipId)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="WHSLoadTable.md" target="_blank">WorksheetHeader/WHSLoadTable</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[WHSLoadTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CarrierCode name="CarrierCode">CarrierCode</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

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

### <a href=#OriginHubCode name="OriginHubCode">OriginHubCode</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginHubCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AccountNum name="AccountNum">AccountNum</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActualGrossWeight name="ActualGrossWeight">ActualGrossWeight</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActualGrossWeight attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ActualNetWeight name="ActualNetWeight">ActualNetWeight</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActualNetWeight attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ActualTareWeight name="ActualTareWeight">ActualTareWeight</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActualTareWeight attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#BillOfLadingId name="BillOfLadingId">BillOfLadingId</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Master bill of lading</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BillOfLadingId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Master bill of lading</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BookingNum name="BookingNum">BookingNum</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

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

### <a href=#BrokerCode name="BrokerCode">BrokerCode</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BrokerCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CarNumber name="CarNumber">CarNumber</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CarNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CarrierGroupCode name="CarrierGroupCode">CarrierGroupCode</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CarrierGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CarrierServiceCode name="CarrierServiceCode">CarrierServiceCode</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

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

### <a href=#CustVendRef name="CustVendRef">CustVendRef</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustVendRef attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CutOffUTCDateTime name="CutOffUTCDateTime">CutOffUTCDateTime</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CutOffUTCDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#DestinationHubCode name="DestinationHubCode">DestinationHubCode</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationHubCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DestinationName name="DestinationName">DestinationName</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Destination</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Destination</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DestinationPostalAddress name="DestinationPostalAddress">DestinationPostalAddress</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

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

### <a href=#ETA name="ETA">ETA</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ETA attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#ETD name="ETD">ETD</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ETD attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#FinalDestination name="FinalDestination">FinalDestination</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FinalDestination attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#HouseBill name="HouseBill">HouseBill</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HouseBill attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InspectionSeal name="InspectionSeal">InspectionSeal</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InspectionSeal attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Invalid name="Invalid">Invalid</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Invalid attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#InventLocationId name="InventLocationId">InventLocationId</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

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

First included in: WorksheetHeader/WHSLoadTable (this entity)  

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

### <a href=#LastUpdateUTCDateTime name="LastUpdateUTCDateTime">LastUpdateUTCDateTime</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LastUpdateUTCDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#LateShipReasonCode name="LateShipReasonCode">LateShipReasonCode</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LateShipReasonCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LoadArrivalUTCDateTime name="LoadArrivalUTCDateTime">LoadArrivalUTCDateTime</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoadArrivalUTCDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#LoadDepth name="LoadDepth">LoadDepth</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoadDepth attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#LoadDirection name="LoadDirection">LoadDirection</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoadDirection attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#Loader name="Loader">Loader</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Loader attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LoadFloorStack name="LoadFloorStack">LoadFloorStack</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoadFloorStack attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LoadHeight name="LoadHeight">LoadHeight</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoadHeight attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#LoadId name="LoadId">LoadId</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

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

### <a href=#LoadNetWeight name="LoadNetWeight">LoadNetWeight</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoadNetWeight attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#LoadPaysFreight name="LoadPaysFreight">LoadPaysFreight</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoadPaysFreight attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LoadReferenceNum name="LoadReferenceNum">LoadReferenceNum</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoadReferenceNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LoadSchedShipUTCDateTime name="LoadSchedShipUTCDateTime">LoadSchedShipUTCDateTime</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoadSchedShipUTCDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#LoadShipConfirmUTCDateTime name="LoadShipConfirmUTCDateTime">LoadShipConfirmUTCDateTime</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoadShipConfirmUTCDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#LoadStatus name="LoadStatus">LoadStatus</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoadStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#LoadTemplateId name="LoadTemplateId">LoadTemplateId</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoadTemplateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LoadTipVolume name="LoadTipVolume">LoadTipVolume</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoadTipVolume attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#LoadTipWeight name="LoadTipWeight">LoadTipWeight</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Max. allowed load weight</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoadTipWeight attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Max. allowed load weight</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#LoadUserDef1 name="LoadUserDef1">LoadUserDef1</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoadUserDef1 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LoadUserDef2 name="LoadUserDef2">LoadUserDef2</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoadUserDef2 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LoadUserDef3 name="LoadUserDef3">LoadUserDef3</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoadUserDef3 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LoadWeight name="LoadWeight">LoadWeight</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoadWeight attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#LoadWidth name="LoadWidth">LoadWidth</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoadWidth attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#MaxFreightPieces name="MaxFreightPieces">MaxFreightPieces</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxFreightPieces attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ModeCode name="ModeCode">ModeCode</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

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

### <a href=#OrderNum name="OrderNum">OrderNum</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OriginName name="OriginName">OriginName</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Origin</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Origin</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OriginPostalAddress name="OriginPostalAddress">OriginPostalAddress</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

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

First included in: WorksheetHeader/WHSLoadTable (this entity)  

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

### <a href=#RequiredSailUTCDateTime name="RequiredSailUTCDateTime">RequiredSailUTCDateTime</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequiredSailUTCDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#RouteCode name="RouteCode">RouteCode</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

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

### <a href=#SailUTCDateTime name="SailUTCDateTime">SailUTCDateTime</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SailUTCDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#SealNum name="SealNum">SealNum</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SealNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SystemTareWeight name="SystemTareWeight">SystemTareWeight</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SystemTareWeight attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#TractorNumber name="TractorNumber">TractorNumber</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

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

First included in: WorksheetHeader/WHSLoadTable (this entity)  

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

### <a href=#TransportationTemplateId name="TransportationTemplateId">TransportationTemplateId</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationTemplateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VesselName name="VesselName">VesselName</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

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

First included in: WorksheetHeader/WHSLoadTable (this entity)  

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

### <a href=#CarState_BR name="CarState_BR">CarState_BR</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CarState_BR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PackingSlipType name="PackingSlipType">PackingSlipType</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PackingSlipType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ActualVolume name="ActualVolume">ActualVolume</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActualVolume attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#LoadingStrategy name="LoadingStrategy">LoadingStrategy</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoadingStrategy attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AllowLoadSplitShipConfirm name="AllowLoadSplitShipConfirm">AllowLoadSplitShipConfirm</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowLoadSplitShipConfirm attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#LoadBuildTemplateName name="LoadBuildTemplateName">LoadBuildTemplateName</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoadBuildTemplateName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CredManInCreditControl name="CredManInCreditControl">CredManInCreditControl</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CredManInCreditControl attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

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

### <a href=#Relationship_InventLocationRelationshipId name="Relationship_InventLocationRelationshipId">Relationship_InventLocationRelationshipId</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/InventLocation.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/InventLocation.cdm.json/InventLocation</a></td><td><a href="../Group/InventLocation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventSiteRelationshipId name="Relationship_InventSiteRelationshipId">Relationship_InventSiteRelationshipId</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/InventSite.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/InventSite.cdm.json/InventSite</a></td><td><a href="../Group/InventSite.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LogisitcsPostalAddressOriginRelationshipId name="Relationship_LogisitcsPostalAddressOriginRelationshipId">Relationship_LogisitcsPostalAddressOriginRelationshipId</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LogisitcsPostalAddressOriginRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_LogisticsPostalAddressDestinationRelationshipId name="Relationship_LogisticsPostalAddressDestinationRelationshipId">Relationship_LogisticsPostalAddressDestinationRelationshipId</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

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

### <a href=#Relationship_TMSBrokerRelationshipId name="Relationship_TMSBrokerRelationshipId">Relationship_TMSBrokerRelationshipId</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TMSBrokerRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Transportation/Main/TMSCarrier.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Transportation/Main/TMSCarrier.cdm.json/TMSCarrier</a></td><td><a href="../../Transportation/Main/TMSCarrier.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TMSCarrierRelationshipId name="Relationship_TMSCarrierRelationshipId">Relationship_TMSCarrierRelationshipId</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Transportation/Main/TMSCarrier.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Transportation/Main/TMSCarrier.cdm.json/TMSCarrier</a></td><td><a href="../../Transportation/Main/TMSCarrier.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TMSCarrierGroupRelationshipId name="Relationship_TMSCarrierGroupRelationshipId">Relationship_TMSCarrierGroupRelationshipId</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TMSCarrierGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Transportation/Main/TMSCarrierGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Transportation/Main/TMSCarrierGroup.cdm.json/TMSCarrierGroup</a></td><td><a href="../../Transportation/Main/TMSCarrierGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TMSCarrierServiceRelationshipId name="Relationship_TMSCarrierServiceRelationshipId">Relationship_TMSCarrierServiceRelationshipId</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Transportation/Group/TMSCarrierService.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Transportation/Group/TMSCarrierService.cdm.json/TMSCarrierService</a></td><td><a href="../../Transportation/Group/TMSCarrierService.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TMSHubMasterDestRelationshipId name="Relationship_TMSHubMasterDestRelationshipId">Relationship_TMSHubMasterDestRelationshipId</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TMSHubMasterDestRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Transportation/Group/TMSHubMaster.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Transportation/Group/TMSHubMaster.cdm.json/TMSHubMaster</a></td><td><a href="../../Transportation/Group/TMSHubMaster.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TMSHubMasterOriginRelationshipId name="Relationship_TMSHubMasterOriginRelationshipId">Relationship_TMSHubMasterOriginRelationshipId</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TMSHubMasterOriginRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Transportation/Group/TMSHubMaster.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Transportation/Group/TMSHubMaster.cdm.json/TMSHubMaster</a></td><td><a href="../../Transportation/Group/TMSHubMaster.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TMSLateShipReasonRelationshipId name="Relationship_TMSLateShipReasonRelationshipId">Relationship_TMSLateShipReasonRelationshipId</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TMSLateShipReasonRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Transportation/Group/TMSLateShipReason.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Transportation/Group/TMSLateShipReason.cdm.json/TMSLateShipReason</a></td><td><a href="../../Transportation/Group/TMSLateShipReason.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TMSModeRelationshipId name="Relationship_TMSModeRelationshipId">Relationship_TMSModeRelationshipId</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Transportation/Group/TMSMode.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Transportation/Group/TMSMode.cdm.json/TMSMode</a></td><td><a href="../../Transportation/Group/TMSMode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TMSRouteRelationshipId name="Relationship_TMSRouteRelationshipId">Relationship_TMSRouteRelationshipId</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Transportation/Main/TMSRoute.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Transportation/Main/TMSRoute.cdm.json/TMSRoute</a></td><td><a href="../../Transportation/Main/TMSRoute.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TMSTransportationTemplateRelationshipId name="Relationship_TMSTransportationTemplateRelationshipId">Relationship_TMSTransportationTemplateRelationshipId</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TMSTransportationTemplateRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Transportation/Main/TMSTransportationTemplate.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Transportation/Main/TMSTransportationTemplate.cdm.json/TMSTransportationTemplate</a></td><td><a href="../../Transportation/Main/TMSTransportationTemplate.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WHSLoadTemplateRelationshipId name="Relationship_WHSLoadTemplateRelationshipId">Relationship_WHSLoadTemplateRelationshipId</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WHSLoadTemplateRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/WHSLoadTemplate.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/WHSLoadTemplate.cdm.json/WHSLoadTemplate</a></td><td><a href="../Main/WHSLoadTemplate.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WHSLoadBuildTemplateRelationshipId name="Relationship_WHSLoadBuildTemplateRelationshipId">Relationship_WHSLoadBuildTemplateRelationshipId</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WHSLoadBuildTemplateRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/WHSLoadBuildTemplate.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/WHSLoadBuildTemplate.cdm.json/WHSLoadBuildTemplate</a></td><td><a href="../Main/WHSLoadBuildTemplate.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetHeader/WHSLoadTable (this entity)  

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
