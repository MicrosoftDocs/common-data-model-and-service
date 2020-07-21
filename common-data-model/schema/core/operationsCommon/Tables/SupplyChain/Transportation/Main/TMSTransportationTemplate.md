---
title: TMSTransportationTemplate in Main - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/21/2020
ms.author: nebanfic
---

# Transportation templates in Main(TMSTransportationTemplate)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/Transportation/Main/TMSTransportationTemplate.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TMSTransportationTemplate/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Transportation templates</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="TMSTransportationTemplate.md" target="_blank">Main/TMSTransportationTemplate</a>|
|[ShipCarrierCode](#ShipCarrierCode)||<a href="TMSTransportationTemplate.md" target="_blank">Main/TMSTransportationTemplate</a>|
|[ShipCarrierGroupCode](#ShipCarrierGroupCode)||<a href="TMSTransportationTemplate.md" target="_blank">Main/TMSTransportationTemplate</a>|
|[ShipRoutePlanCode](#ShipRoutePlanCode)||<a href="TMSTransportationTemplate.md" target="_blank">Main/TMSTransportationTemplate</a>|
|[CustCarrierCode](#CustCarrierCode)||<a href="TMSTransportationTemplate.md" target="_blank">Main/TMSTransportationTemplate</a>|
|[CustCarrierServiceCode](#CustCarrierServiceCode)||<a href="TMSTransportationTemplate.md" target="_blank">Main/TMSTransportationTemplate</a>|
|[CustManual](#CustManual)||<a href="TMSTransportationTemplate.md" target="_blank">Main/TMSTransportationTemplate</a>|
|[CustRoutePlanCode](#CustRoutePlanCode)||<a href="TMSTransportationTemplate.md" target="_blank">Main/TMSTransportationTemplate</a>|
|[LoadTemplateId](#LoadTemplateId)||<a href="TMSTransportationTemplate.md" target="_blank">Main/TMSTransportationTemplate</a>|
|[Name](#Name)||<a href="TMSTransportationTemplate.md" target="_blank">Main/TMSTransportationTemplate</a>|
|[ShipCarrierServiceCode](#ShipCarrierServiceCode)||<a href="TMSTransportationTemplate.md" target="_blank">Main/TMSTransportationTemplate</a>|
|[TransportationTemplateId](#TransportationTemplateId)||<a href="TMSTransportationTemplate.md" target="_blank">Main/TMSTransportationTemplate</a>|
|[DataAreaId](#DataAreaId)||<a href="TMSTransportationTemplate.md" target="_blank">Main/TMSTransportationTemplate</a>|
|[Relationship_TMSCarrierCustRelationshipId](#Relationship_TMSCarrierCustRelationshipId)||<a href="TMSTransportationTemplate.md" target="_blank">Main/TMSTransportationTemplate</a>|
|[Relationship_TMSCarrierGroupShipRelationshipId](#Relationship_TMSCarrierGroupShipRelationshipId)||<a href="TMSTransportationTemplate.md" target="_blank">Main/TMSTransportationTemplate</a>|
|[Relationship_TMSCarrierServiceCustRelationshipId](#Relationship_TMSCarrierServiceCustRelationshipId)||<a href="TMSTransportationTemplate.md" target="_blank">Main/TMSTransportationTemplate</a>|
|[Relationship_TMSCarrierServiceShipRelationshipId](#Relationship_TMSCarrierServiceShipRelationshipId)||<a href="TMSTransportationTemplate.md" target="_blank">Main/TMSTransportationTemplate</a>|
|[Relationship_TMSCarrierShipRelationshipId](#Relationship_TMSCarrierShipRelationshipId)||<a href="TMSTransportationTemplate.md" target="_blank">Main/TMSTransportationTemplate</a>|
|[Relationship_TMSRouteConfigCustRelationshipId](#Relationship_TMSRouteConfigCustRelationshipId)||<a href="TMSTransportationTemplate.md" target="_blank">Main/TMSTransportationTemplate</a>|
|[Relationship_TMSRouteConfigShipRelationshipId](#Relationship_TMSRouteConfigShipRelationshipId)||<a href="TMSTransportationTemplate.md" target="_blank">Main/TMSTransportationTemplate</a>|
|[Relationship_WHSLoadTemplateRelationshipId](#Relationship_WHSLoadTemplateRelationshipId)||<a href="TMSTransportationTemplate.md" target="_blank">Main/TMSTransportationTemplate</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="TMSTransportationTemplate.md" target="_blank">Main/TMSTransportationTemplate</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/TMSTransportationTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TMSTransportationTemplate/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ShipCarrierCode name="ShipCarrierCode">ShipCarrierCode</a>

First included in: Main/TMSTransportationTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShipCarrierCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShipCarrierGroupCode name="ShipCarrierGroupCode">ShipCarrierGroupCode</a>

First included in: Main/TMSTransportationTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShipCarrierGroupCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShipRoutePlanCode name="ShipRoutePlanCode">ShipRoutePlanCode</a>

First included in: Main/TMSTransportationTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShipRoutePlanCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustCarrierCode name="CustCarrierCode">CustCarrierCode</a>

First included in: Main/TMSTransportationTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustCarrierCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustCarrierServiceCode name="CustCarrierServiceCode">CustCarrierServiceCode</a>

First included in: Main/TMSTransportationTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustCarrierServiceCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustManual name="CustManual">CustManual</a>

First included in: Main/TMSTransportationTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustManual attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CustRoutePlanCode name="CustRoutePlanCode">CustRoutePlanCode</a>

First included in: Main/TMSTransportationTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustRoutePlanCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LoadTemplateId name="LoadTemplateId">LoadTemplateId</a>

First included in: Main/TMSTransportationTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoadTemplateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: Main/TMSTransportationTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShipCarrierServiceCode name="ShipCarrierServiceCode">ShipCarrierServiceCode</a>

First included in: Main/TMSTransportationTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShipCarrierServiceCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationTemplateId name="TransportationTemplateId">TransportationTemplateId</a>

First included in: Main/TMSTransportationTemplate (this entity)  

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

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Main/TMSTransportationTemplate (this entity)  

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

### <a href=#Relationship_TMSCarrierCustRelationshipId name="Relationship_TMSCarrierCustRelationshipId">Relationship_TMSCarrierCustRelationshipId</a>

First included in: Main/TMSTransportationTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TMSCarrierCustRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TMSCarrier.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Transportation/Main/TMSCarrier.cdm.json/TMSCarrier</a></td><td><a href="TMSCarrier.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TMSCarrierGroupShipRelationshipId name="Relationship_TMSCarrierGroupShipRelationshipId">Relationship_TMSCarrierGroupShipRelationshipId</a>

First included in: Main/TMSTransportationTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TMSCarrierGroupShipRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TMSCarrierGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Transportation/Main/TMSCarrierGroup.cdm.json/TMSCarrierGroup</a></td><td><a href="TMSCarrierGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TMSCarrierServiceCustRelationshipId name="Relationship_TMSCarrierServiceCustRelationshipId">Relationship_TMSCarrierServiceCustRelationshipId</a>

First included in: Main/TMSTransportationTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TMSCarrierServiceCustRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_TMSCarrierServiceShipRelationshipId name="Relationship_TMSCarrierServiceShipRelationshipId">Relationship_TMSCarrierServiceShipRelationshipId</a>

First included in: Main/TMSTransportationTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TMSCarrierServiceShipRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_TMSCarrierShipRelationshipId name="Relationship_TMSCarrierShipRelationshipId">Relationship_TMSCarrierShipRelationshipId</a>

First included in: Main/TMSTransportationTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TMSCarrierShipRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TMSCarrier.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Transportation/Main/TMSCarrier.cdm.json/TMSCarrier</a></td><td><a href="TMSCarrier.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TMSRouteConfigCustRelationshipId name="Relationship_TMSRouteConfigCustRelationshipId">Relationship_TMSRouteConfigCustRelationshipId</a>

First included in: Main/TMSTransportationTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TMSRouteConfigCustRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/TMSRouteConfig.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Transportation/Group/TMSRouteConfig.cdm.json/TMSRouteConfig</a></td><td><a href="../Group/TMSRouteConfig.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TMSRouteConfigShipRelationshipId name="Relationship_TMSRouteConfigShipRelationshipId">Relationship_TMSRouteConfigShipRelationshipId</a>

First included in: Main/TMSTransportationTemplate (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TMSRouteConfigShipRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/TMSRouteConfig.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Transportation/Group/TMSRouteConfig.cdm.json/TMSRouteConfig</a></td><td><a href="../Group/TMSRouteConfig.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WHSLoadTemplateRelationshipId name="Relationship_WHSLoadTemplateRelationshipId">Relationship_WHSLoadTemplateRelationshipId</a>

First included in: Main/TMSTransportationTemplate (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Inventory/Main/WHSLoadTemplate.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/WHSLoadTemplate.cdm.json/WHSLoadTemplate</a></td><td><a href="../../Inventory/Main/WHSLoadTemplate.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Main/TMSTransportationTemplate (this entity)  

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
