---
title: TMSTransportationRoutePlanSegmentEntity in Transportation - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Transportation route plan segments in Transportation(TMSTransportationRoutePlanSegmentEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/Transportation/TMSTransportationRoutePlanSegmentEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Transportation route plan segments</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[OriginTransportationHubId](#OriginTransportationHubId)||<a href="TMSTransportationRoutePlanSegmentEntity.md" target="_blank">Transportation/TMSTransportationRoutePlanSegmentEntity</a>|
|[ShippingCarrierId](#ShippingCarrierId)||<a href="TMSTransportationRoutePlanSegmentEntity.md" target="_blank">Transportation/TMSTransportationRoutePlanSegmentEntity</a>|
|[ShippingCarrierServiceGroupId](#ShippingCarrierServiceGroupId)||<a href="TMSTransportationRoutePlanSegmentEntity.md" target="_blank">Transportation/TMSTransportationRoutePlanSegmentEntity</a>|
|[ShippingCarrierServiceId](#ShippingCarrierServiceId)||<a href="TMSTransportationRoutePlanSegmentEntity.md" target="_blank">Transportation/TMSTransportationRoutePlanSegmentEntity</a>|
|[DeliveryTermsCode](#DeliveryTermsCode)||<a href="TMSTransportationRoutePlanSegmentEntity.md" target="_blank">Transportation/TMSTransportationRoutePlanSegmentEntity</a>|
|[InvoiceAccountType](#InvoiceAccountType)||<a href="TMSTransportationRoutePlanSegmentEntity.md" target="_blank">Transportation/TMSTransportationRoutePlanSegmentEntity</a>|
|[TransportationModeCode](#TransportationModeCode)||<a href="TMSTransportationRoutePlanSegmentEntity.md" target="_blank">Transportation/TMSTransportationRoutePlanSegmentEntity</a>|
|[SegmentName](#SegmentName)||<a href="TMSTransportationRoutePlanSegmentEntity.md" target="_blank">Transportation/TMSTransportationRoutePlanSegmentEntity</a>|
|[PayingPartyRole](#PayingPartyRole)||<a href="TMSTransportationRoutePlanSegmentEntity.md" target="_blank">Transportation/TMSTransportationRoutePlanSegmentEntity</a>|
|[TransportationRoutePlanId](#TransportationRoutePlanId)||<a href="TMSTransportationRoutePlanSegmentEntity.md" target="_blank">Transportation/TMSTransportationRoutePlanSegmentEntity</a>|
|[DestinationTransportationHubId](#DestinationTransportationHubId)||<a href="TMSTransportationRoutePlanSegmentEntity.md" target="_blank">Transportation/TMSTransportationRoutePlanSegmentEntity</a>|
|[SequenceNumber](#SequenceNumber)||<a href="TMSTransportationRoutePlanSegmentEntity.md" target="_blank">Transportation/TMSTransportationRoutePlanSegmentEntity</a>|
|[OrderVendorAccountNumber](#OrderVendorAccountNumber)||<a href="TMSTransportationRoutePlanSegmentEntity.md" target="_blank">Transportation/TMSTransportationRoutePlanSegmentEntity</a>|
|[InvoiceVendorAccountNumber](#InvoiceVendorAccountNumber)||<a href="TMSTransportationRoutePlanSegmentEntity.md" target="_blank">Transportation/TMSTransportationRoutePlanSegmentEntity</a>|
|[BackingTable_TMSRouteSegmentConfigRelationshipId](#BackingTable_TMSRouteSegmentConfigRelationshipId)||<a href="TMSTransportationRoutePlanSegmentEntity.md" target="_blank">Transportation/TMSTransportationRoutePlanSegmentEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="TMSTransportationRoutePlanSegmentEntity.md" target="_blank">Transportation/TMSTransportationRoutePlanSegmentEntity</a>|

### <a href=#OriginTransportationHubId name="OriginTransportationHubId">OriginTransportationHubId</a>

First included in: Transportation/TMSTransportationRoutePlanSegmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginTransportationHubId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingCarrierId name="ShippingCarrierId">ShippingCarrierId</a>

First included in: Transportation/TMSTransportationRoutePlanSegmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingCarrierId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingCarrierServiceGroupId name="ShippingCarrierServiceGroupId">ShippingCarrierServiceGroupId</a>

First included in: Transportation/TMSTransportationRoutePlanSegmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingCarrierServiceGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingCarrierServiceId name="ShippingCarrierServiceId">ShippingCarrierServiceId</a>

First included in: Transportation/TMSTransportationRoutePlanSegmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingCarrierServiceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryTermsCode name="DeliveryTermsCode">DeliveryTermsCode</a>

First included in: Transportation/TMSTransportationRoutePlanSegmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryTermsCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceAccountType name="InvoiceAccountType">InvoiceAccountType</a>

First included in: Transportation/TMSTransportationRoutePlanSegmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceAccountType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationModeCode name="TransportationModeCode">TransportationModeCode</a>

First included in: Transportation/TMSTransportationRoutePlanSegmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationModeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SegmentName name="SegmentName">SegmentName</a>

First included in: Transportation/TMSTransportationRoutePlanSegmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SegmentName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayingPartyRole name="PayingPartyRole">PayingPartyRole</a>

First included in: Transportation/TMSTransportationRoutePlanSegmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayingPartyRole attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationRoutePlanId name="TransportationRoutePlanId">TransportationRoutePlanId</a>

First included in: Transportation/TMSTransportationRoutePlanSegmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationRoutePlanId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DestinationTransportationHubId name="DestinationTransportationHubId">DestinationTransportationHubId</a>

First included in: Transportation/TMSTransportationRoutePlanSegmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationTransportationHubId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SequenceNumber name="SequenceNumber">SequenceNumber</a>

First included in: Transportation/TMSTransportationRoutePlanSegmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SequenceNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrderVendorAccountNumber name="OrderVendorAccountNumber">OrderVendorAccountNumber</a>

First included in: Transportation/TMSTransportationRoutePlanSegmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderVendorAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InvoiceVendorAccountNumber name="InvoiceVendorAccountNumber">InvoiceVendorAccountNumber</a>

First included in: Transportation/TMSTransportationRoutePlanSegmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InvoiceVendorAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_TMSRouteSegmentConfigRelationshipId name="BackingTable_TMSRouteSegmentConfigRelationshipId">BackingTable_TMSRouteSegmentConfigRelationshipId</a>

First included in: Transportation/TMSTransportationRoutePlanSegmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_TMSRouteSegmentConfigRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Transportation/Group/TMSRouteSegmentConfig.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Transportation/Group/TMSRouteSegmentConfig.cdm.json/TMSRouteSegmentConfig</a></td><td><a href="../../../Tables/SupplyChain/Transportation/Group/TMSRouteSegmentConfig.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: Transportation/TMSTransportationRoutePlanSegmentEntity (this entity)  

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
