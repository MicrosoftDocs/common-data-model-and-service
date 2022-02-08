---
title: WHSShipConsolidationTemplateV2Entity in WMS - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Shipment consolidation templates V2 in WMS(WHSShipConsolidationTemplateV2Entity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/WMS/WHSShipConsolidationTemplateV2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shipment consolidation templates V2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[OrderingCustomerAccountNumber](#OrderingCustomerAccountNumber)||<a href="WHSShipConsolidationTemplateV2Entity.md" target="_blank">WMS/WHSShipConsolidationTemplateV2Entity</a>|
|[TemplateDescription](#TemplateDescription)||<a href="WHSShipConsolidationTemplateV2Entity.md" target="_blank">WMS/WHSShipConsolidationTemplateV2Entity</a>|
|[DestinationCountryRegionId](#DestinationCountryRegionId)||<a href="WHSShipConsolidationTemplateV2Entity.md" target="_blank">WMS/WHSShipConsolidationTemplateV2Entity</a>|
|[DestinationFromZipCode](#DestinationFromZipCode)||<a href="WHSShipConsolidationTemplateV2Entity.md" target="_blank">WMS/WHSShipConsolidationTemplateV2Entity</a>|
|[DestinationToZipCode](#DestinationToZipCode)||<a href="WHSShipConsolidationTemplateV2Entity.md" target="_blank">WMS/WHSShipConsolidationTemplateV2Entity</a>|
|[DestinationWarehouseId](#DestinationWarehouseId)||<a href="WHSShipConsolidationTemplateV2Entity.md" target="_blank">WMS/WHSShipConsolidationTemplateV2Entity</a>|
|[DestinationOperationalSiteId](#DestinationOperationalSiteId)||<a href="WHSShipConsolidationTemplateV2Entity.md" target="_blank">WMS/WHSShipConsolidationTemplateV2Entity</a>|
|[FirstProductFilterCode](#FirstProductFilterCode)||<a href="WHSShipConsolidationTemplateV2Entity.md" target="_blank">WMS/WHSShipConsolidationTemplateV2Entity</a>|
|[SecondProductFilterCode](#SecondProductFilterCode)||<a href="WHSShipConsolidationTemplateV2Entity.md" target="_blank">WMS/WHSShipConsolidationTemplateV2Entity</a>|
|[ThirdProductFilterCode](#ThirdProductFilterCode)||<a href="WHSShipConsolidationTemplateV2Entity.md" target="_blank">WMS/WHSShipConsolidationTemplateV2Entity</a>|
|[FourthProductFilterCode](#FourthProductFilterCode)||<a href="WHSShipConsolidationTemplateV2Entity.md" target="_blank">WMS/WHSShipConsolidationTemplateV2Entity</a>|
|[ShipConsolidationTemplateName](#ShipConsolidationTemplateName)||<a href="WHSShipConsolidationTemplateV2Entity.md" target="_blank">WMS/WHSShipConsolidationTemplateV2Entity</a>|
|[OriginCountryRegionId](#OriginCountryRegionId)||<a href="WHSShipConsolidationTemplateV2Entity.md" target="_blank">WMS/WHSShipConsolidationTemplateV2Entity</a>|
|[OriginFromZipCode](#OriginFromZipCode)||<a href="WHSShipConsolidationTemplateV2Entity.md" target="_blank">WMS/WHSShipConsolidationTemplateV2Entity</a>|
|[OriginWarehouseId](#OriginWarehouseId)||<a href="WHSShipConsolidationTemplateV2Entity.md" target="_blank">WMS/WHSShipConsolidationTemplateV2Entity</a>|
|[OriginOperationalSiteId](#OriginOperationalSiteId)||<a href="WHSShipConsolidationTemplateV2Entity.md" target="_blank">WMS/WHSShipConsolidationTemplateV2Entity</a>|
|[OriginToZipCode](#OriginToZipCode)||<a href="WHSShipConsolidationTemplateV2Entity.md" target="_blank">WMS/WHSShipConsolidationTemplateV2Entity</a>|
|[FilterQuery](#FilterQuery)||<a href="WHSShipConsolidationTemplateV2Entity.md" target="_blank">WMS/WHSShipConsolidationTemplateV2Entity</a>|
|[ShipmentConsolidationPolicyType](#ShipmentConsolidationPolicyType)||<a href="WHSShipConsolidationTemplateV2Entity.md" target="_blank">WMS/WHSShipConsolidationTemplateV2Entity</a>|
|[WillConsolidationSplitShipmentByLoadCapacity](#WillConsolidationSplitShipmentByLoadCapacity)||<a href="WHSShipConsolidationTemplateV2Entity.md" target="_blank">WMS/WHSShipConsolidationTemplateV2Entity</a>|
|[WillConsolidationUpdateScheduledShipDateTime](#WillConsolidationUpdateScheduledShipDateTime)||<a href="WHSShipConsolidationTemplateV2Entity.md" target="_blank">WMS/WHSShipConsolidationTemplateV2Entity</a>|
|[BackingTable_WHSShipConsolidationTemplateRelationshipId](#BackingTable_WHSShipConsolidationTemplateRelationshipId)||<a href="WHSShipConsolidationTemplateV2Entity.md" target="_blank">WMS/WHSShipConsolidationTemplateV2Entity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="WHSShipConsolidationTemplateV2Entity.md" target="_blank">WMS/WHSShipConsolidationTemplateV2Entity</a>|

### <a href=#OrderingCustomerAccountNumber name="OrderingCustomerAccountNumber">OrderingCustomerAccountNumber</a>

First included in: WMS/WHSShipConsolidationTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderingCustomerAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TemplateDescription name="TemplateDescription">TemplateDescription</a>

First included in: WMS/WHSShipConsolidationTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TemplateDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DestinationCountryRegionId name="DestinationCountryRegionId">DestinationCountryRegionId</a>

First included in: WMS/WHSShipConsolidationTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationCountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DestinationFromZipCode name="DestinationFromZipCode">DestinationFromZipCode</a>

First included in: WMS/WHSShipConsolidationTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationFromZipCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DestinationToZipCode name="DestinationToZipCode">DestinationToZipCode</a>

First included in: WMS/WHSShipConsolidationTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationToZipCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DestinationWarehouseId name="DestinationWarehouseId">DestinationWarehouseId</a>

First included in: WMS/WHSShipConsolidationTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DestinationOperationalSiteId name="DestinationOperationalSiteId">DestinationOperationalSiteId</a>

First included in: WMS/WHSShipConsolidationTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DestinationOperationalSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FirstProductFilterCode name="FirstProductFilterCode">FirstProductFilterCode</a>

First included in: WMS/WHSShipConsolidationTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FirstProductFilterCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SecondProductFilterCode name="SecondProductFilterCode">SecondProductFilterCode</a>

First included in: WMS/WHSShipConsolidationTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SecondProductFilterCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ThirdProductFilterCode name="ThirdProductFilterCode">ThirdProductFilterCode</a>

First included in: WMS/WHSShipConsolidationTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ThirdProductFilterCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FourthProductFilterCode name="FourthProductFilterCode">FourthProductFilterCode</a>

First included in: WMS/WHSShipConsolidationTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FourthProductFilterCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShipConsolidationTemplateName name="ShipConsolidationTemplateName">ShipConsolidationTemplateName</a>

First included in: WMS/WHSShipConsolidationTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShipConsolidationTemplateName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OriginCountryRegionId name="OriginCountryRegionId">OriginCountryRegionId</a>

First included in: WMS/WHSShipConsolidationTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginCountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OriginFromZipCode name="OriginFromZipCode">OriginFromZipCode</a>

First included in: WMS/WHSShipConsolidationTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginFromZipCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OriginWarehouseId name="OriginWarehouseId">OriginWarehouseId</a>

First included in: WMS/WHSShipConsolidationTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginWarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OriginOperationalSiteId name="OriginOperationalSiteId">OriginOperationalSiteId</a>

First included in: WMS/WHSShipConsolidationTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginOperationalSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OriginToZipCode name="OriginToZipCode">OriginToZipCode</a>

First included in: WMS/WHSShipConsolidationTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OriginToZipCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FilterQuery name="FilterQuery">FilterQuery</a>

First included in: WMS/WHSShipConsolidationTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FilterQuery attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShipmentConsolidationPolicyType name="ShipmentConsolidationPolicyType">ShipmentConsolidationPolicyType</a>

First included in: WMS/WHSShipConsolidationTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShipmentConsolidationPolicyType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillConsolidationSplitShipmentByLoadCapacity name="WillConsolidationSplitShipmentByLoadCapacity">WillConsolidationSplitShipmentByLoadCapacity</a>

First included in: WMS/WHSShipConsolidationTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillConsolidationSplitShipmentByLoadCapacity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillConsolidationUpdateScheduledShipDateTime name="WillConsolidationUpdateScheduledShipDateTime">WillConsolidationUpdateScheduledShipDateTime</a>

First included in: WMS/WHSShipConsolidationTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillConsolidationUpdateScheduledShipDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_WHSShipConsolidationTemplateRelationshipId name="BackingTable_WHSShipConsolidationTemplateRelationshipId">BackingTable_WHSShipConsolidationTemplateRelationshipId</a>

First included in: WMS/WHSShipConsolidationTemplateV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_WHSShipConsolidationTemplateRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Main/WHSShipConsolidationTemplate.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/WHSShipConsolidationTemplate.cdm.json/WHSShipConsolidationTemplate</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Main/WHSShipConsolidationTemplate.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: WMS/WHSShipConsolidationTemplateV2Entity (this entity)  

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
