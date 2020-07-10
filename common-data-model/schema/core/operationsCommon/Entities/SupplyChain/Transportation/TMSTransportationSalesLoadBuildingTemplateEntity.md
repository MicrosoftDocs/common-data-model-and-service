---
title: TMSTransportationSalesLoadBuildingTemplateEntity in Transportation - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/10/2020
ms.author: nebanfic
---

# Transportation sales load building templates in Transportation(TMSTransportationSalesLoadBuildingTemplateEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/Transportation/TMSTransportationSalesLoadBuildingTemplateEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Transportation sales load building templates</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[OrderingCustomerAccountNumber](#OrderingCustomerAccountNumber)||<a href="TMSTransportationSalesLoadBuildingTemplateEntity.md" target="_blank">Transportation/TMSTransportationSalesLoadBuildingTemplateEntity</a>|
|[TemplateDescription](#TemplateDescription)||<a href="TMSTransportationSalesLoadBuildingTemplateEntity.md" target="_blank">Transportation/TMSTransportationSalesLoadBuildingTemplateEntity</a>|
|[DestinationCountryRegionId](#DestinationCountryRegionId)||<a href="TMSTransportationSalesLoadBuildingTemplateEntity.md" target="_blank">Transportation/TMSTransportationSalesLoadBuildingTemplateEntity</a>|
|[DestinationFromZipCode](#DestinationFromZipCode)||<a href="TMSTransportationSalesLoadBuildingTemplateEntity.md" target="_blank">Transportation/TMSTransportationSalesLoadBuildingTemplateEntity</a>|
|[DestinationToZipCode](#DestinationToZipCode)||<a href="TMSTransportationSalesLoadBuildingTemplateEntity.md" target="_blank">Transportation/TMSTransportationSalesLoadBuildingTemplateEntity</a>|
|[FirstProductFilterCode](#FirstProductFilterCode)||<a href="TMSTransportationSalesLoadBuildingTemplateEntity.md" target="_blank">Transportation/TMSTransportationSalesLoadBuildingTemplateEntity</a>|
|[SecondProductFilterCode](#SecondProductFilterCode)||<a href="TMSTransportationSalesLoadBuildingTemplateEntity.md" target="_blank">Transportation/TMSTransportationSalesLoadBuildingTemplateEntity</a>|
|[ThirdProductFilterCode](#ThirdProductFilterCode)||<a href="TMSTransportationSalesLoadBuildingTemplateEntity.md" target="_blank">Transportation/TMSTransportationSalesLoadBuildingTemplateEntity</a>|
|[FourthProductFilterCode](#FourthProductFilterCode)||<a href="TMSTransportationSalesLoadBuildingTemplateEntity.md" target="_blank">Transportation/TMSTransportationSalesLoadBuildingTemplateEntity</a>|
|[TransportationLoadBuildStrategy](#TransportationLoadBuildStrategy)||<a href="TMSTransportationSalesLoadBuildingTemplateEntity.md" target="_blank">Transportation/TMSTransportationSalesLoadBuildingTemplateEntity</a>|
|[TemplateName](#TemplateName)||<a href="TMSTransportationSalesLoadBuildingTemplateEntity.md" target="_blank">Transportation/TMSTransportationSalesLoadBuildingTemplateEntity</a>|
|[OriginCountryRegionId](#OriginCountryRegionId)||<a href="TMSTransportationSalesLoadBuildingTemplateEntity.md" target="_blank">Transportation/TMSTransportationSalesLoadBuildingTemplateEntity</a>|
|[OriginFromZipCode](#OriginFromZipCode)||<a href="TMSTransportationSalesLoadBuildingTemplateEntity.md" target="_blank">Transportation/TMSTransportationSalesLoadBuildingTemplateEntity</a>|
|[OriginWarehouseId](#OriginWarehouseId)||<a href="TMSTransportationSalesLoadBuildingTemplateEntity.md" target="_blank">Transportation/TMSTransportationSalesLoadBuildingTemplateEntity</a>|
|[OriginOperationalSiteId](#OriginOperationalSiteId)||<a href="TMSTransportationSalesLoadBuildingTemplateEntity.md" target="_blank">Transportation/TMSTransportationSalesLoadBuildingTemplateEntity</a>|
|[OriginToZipCode](#OriginToZipCode)||<a href="TMSTransportationSalesLoadBuildingTemplateEntity.md" target="_blank">Transportation/TMSTransportationSalesLoadBuildingTemplateEntity</a>|
|[SalesOrderFilterQuery](#SalesOrderFilterQuery)||<a href="TMSTransportationSalesLoadBuildingTemplateEntity.md" target="_blank">Transportation/TMSTransportationSalesLoadBuildingTemplateEntity</a>|
|[TransportationLoadBuildingStrategyName](#TransportationLoadBuildingStrategyName)||<a href="TMSTransportationSalesLoadBuildingTemplateEntity.md" target="_blank">Transportation/TMSTransportationSalesLoadBuildingTemplateEntity</a>|
|[Relationship_FirstProductFilterCodeRelationshipId](#Relationship_FirstProductFilterCodeRelationshipId)||<a href="TMSTransportationSalesLoadBuildingTemplateEntity.md" target="_blank">Transportation/TMSTransportationSalesLoadBuildingTemplateEntity</a>|
|[Relationship_SecondProductFilterCodeRelationshipId](#Relationship_SecondProductFilterCodeRelationshipId)||<a href="TMSTransportationSalesLoadBuildingTemplateEntity.md" target="_blank">Transportation/TMSTransportationSalesLoadBuildingTemplateEntity</a>|
|[Relationship_ThirdProductFilterCodeRelationshipId](#Relationship_ThirdProductFilterCodeRelationshipId)||<a href="TMSTransportationSalesLoadBuildingTemplateEntity.md" target="_blank">Transportation/TMSTransportationSalesLoadBuildingTemplateEntity</a>|
|[Relationship_FourthProductFilterCodeRelationshipId](#Relationship_FourthProductFilterCodeRelationshipId)||<a href="TMSTransportationSalesLoadBuildingTemplateEntity.md" target="_blank">Transportation/TMSTransportationSalesLoadBuildingTemplateEntity</a>|
|[Relationship_DestinationCountryRegionRelationshipId](#Relationship_DestinationCountryRegionRelationshipId)||<a href="TMSTransportationSalesLoadBuildingTemplateEntity.md" target="_blank">Transportation/TMSTransportationSalesLoadBuildingTemplateEntity</a>|
|[Relationship_OriginCountryRegionRelationshipId](#Relationship_OriginCountryRegionRelationshipId)||<a href="TMSTransportationSalesLoadBuildingTemplateEntity.md" target="_blank">Transportation/TMSTransportationSalesLoadBuildingTemplateEntity</a>|
|[Relationship_OriginOperationalSiteRelationshipId](#Relationship_OriginOperationalSiteRelationshipId)||<a href="TMSTransportationSalesLoadBuildingTemplateEntity.md" target="_blank">Transportation/TMSTransportationSalesLoadBuildingTemplateEntity</a>|
|[Relationship_OriginWarehouseRelationshipId](#Relationship_OriginWarehouseRelationshipId)||<a href="TMSTransportationSalesLoadBuildingTemplateEntity.md" target="_blank">Transportation/TMSTransportationSalesLoadBuildingTemplateEntity</a>|
|[Relationship_TransportationLoadBuildingStrategyRelationshipId](#Relationship_TransportationLoadBuildingStrategyRelationshipId)||<a href="TMSTransportationSalesLoadBuildingTemplateEntity.md" target="_blank">Transportation/TMSTransportationSalesLoadBuildingTemplateEntity</a>|
|[Relationship_OrderingCustomerRelationshipId](#Relationship_OrderingCustomerRelationshipId)||<a href="TMSTransportationSalesLoadBuildingTemplateEntity.md" target="_blank">Transportation/TMSTransportationSalesLoadBuildingTemplateEntity</a>|
|[BackingTable_TMSLoadBuildTemplateRelationshipId](#BackingTable_TMSLoadBuildTemplateRelationshipId)||<a href="TMSTransportationSalesLoadBuildingTemplateEntity.md" target="_blank">Transportation/TMSTransportationSalesLoadBuildingTemplateEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="TMSTransportationSalesLoadBuildingTemplateEntity.md" target="_blank">Transportation/TMSTransportationSalesLoadBuildingTemplateEntity</a>|

### <a href=#OrderingCustomerAccountNumber name="OrderingCustomerAccountNumber">OrderingCustomerAccountNumber</a>

First included in: Transportation/TMSTransportationSalesLoadBuildingTemplateEntity (this entity)  

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

First included in: Transportation/TMSTransportationSalesLoadBuildingTemplateEntity (this entity)  

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

First included in: Transportation/TMSTransportationSalesLoadBuildingTemplateEntity (this entity)  

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

First included in: Transportation/TMSTransportationSalesLoadBuildingTemplateEntity (this entity)  

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

First included in: Transportation/TMSTransportationSalesLoadBuildingTemplateEntity (this entity)  

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

### <a href=#FirstProductFilterCode name="FirstProductFilterCode">FirstProductFilterCode</a>

First included in: Transportation/TMSTransportationSalesLoadBuildingTemplateEntity (this entity)  

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

First included in: Transportation/TMSTransportationSalesLoadBuildingTemplateEntity (this entity)  

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

First included in: Transportation/TMSTransportationSalesLoadBuildingTemplateEntity (this entity)  

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

First included in: Transportation/TMSTransportationSalesLoadBuildingTemplateEntity (this entity)  

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

### <a href=#TransportationLoadBuildStrategy name="TransportationLoadBuildStrategy">TransportationLoadBuildStrategy</a>

First included in: Transportation/TMSTransportationSalesLoadBuildingTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationLoadBuildStrategy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TemplateName name="TemplateName">TemplateName</a>

First included in: Transportation/TMSTransportationSalesLoadBuildingTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TemplateName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OriginCountryRegionId name="OriginCountryRegionId">OriginCountryRegionId</a>

First included in: Transportation/TMSTransportationSalesLoadBuildingTemplateEntity (this entity)  

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

First included in: Transportation/TMSTransportationSalesLoadBuildingTemplateEntity (this entity)  

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

First included in: Transportation/TMSTransportationSalesLoadBuildingTemplateEntity (this entity)  

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

First included in: Transportation/TMSTransportationSalesLoadBuildingTemplateEntity (this entity)  

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

First included in: Transportation/TMSTransportationSalesLoadBuildingTemplateEntity (this entity)  

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

### <a href=#SalesOrderFilterQuery name="SalesOrderFilterQuery">SalesOrderFilterQuery</a>

First included in: Transportation/TMSTransportationSalesLoadBuildingTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesOrderFilterQuery attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationLoadBuildingStrategyName name="TransportationLoadBuildingStrategyName">TransportationLoadBuildingStrategyName</a>

First included in: Transportation/TMSTransportationSalesLoadBuildingTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationLoadBuildingStrategyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FirstProductFilterCodeRelationshipId name="Relationship_FirstProductFilterCodeRelationshipId">Relationship_FirstProductFilterCodeRelationshipId</a>

First included in: Transportation/TMSTransportationSalesLoadBuildingTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FirstProductFilterCodeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SecondProductFilterCodeRelationshipId name="Relationship_SecondProductFilterCodeRelationshipId">Relationship_SecondProductFilterCodeRelationshipId</a>

First included in: Transportation/TMSTransportationSalesLoadBuildingTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SecondProductFilterCodeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ThirdProductFilterCodeRelationshipId name="Relationship_ThirdProductFilterCodeRelationshipId">Relationship_ThirdProductFilterCodeRelationshipId</a>

First included in: Transportation/TMSTransportationSalesLoadBuildingTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ThirdProductFilterCodeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FourthProductFilterCodeRelationshipId name="Relationship_FourthProductFilterCodeRelationshipId">Relationship_FourthProductFilterCodeRelationshipId</a>

First included in: Transportation/TMSTransportationSalesLoadBuildingTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FourthProductFilterCodeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DestinationCountryRegionRelationshipId name="Relationship_DestinationCountryRegionRelationshipId">Relationship_DestinationCountryRegionRelationshipId</a>

First included in: Transportation/TMSTransportationSalesLoadBuildingTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DestinationCountryRegionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_OriginCountryRegionRelationshipId name="Relationship_OriginCountryRegionRelationshipId">Relationship_OriginCountryRegionRelationshipId</a>

First included in: Transportation/TMSTransportationSalesLoadBuildingTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OriginCountryRegionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_OriginOperationalSiteRelationshipId name="Relationship_OriginOperationalSiteRelationshipId">Relationship_OriginOperationalSiteRelationshipId</a>

First included in: Transportation/TMSTransportationSalesLoadBuildingTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OriginOperationalSiteRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_OriginWarehouseRelationshipId name="Relationship_OriginWarehouseRelationshipId">Relationship_OriginWarehouseRelationshipId</a>

First included in: Transportation/TMSTransportationSalesLoadBuildingTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OriginWarehouseRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TransportationLoadBuildingStrategyRelationshipId name="Relationship_TransportationLoadBuildingStrategyRelationshipId">Relationship_TransportationLoadBuildingStrategyRelationshipId</a>

First included in: Transportation/TMSTransportationSalesLoadBuildingTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TransportationLoadBuildingStrategyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_OrderingCustomerRelationshipId name="Relationship_OrderingCustomerRelationshipId">Relationship_OrderingCustomerRelationshipId</a>

First included in: Transportation/TMSTransportationSalesLoadBuildingTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OrderingCustomerRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_TMSLoadBuildTemplateRelationshipId name="BackingTable_TMSLoadBuildTemplateRelationshipId">BackingTable_TMSLoadBuildTemplateRelationshipId</a>

First included in: Transportation/TMSTransportationSalesLoadBuildingTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_TMSLoadBuildTemplateRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Transportation/Main/TMSLoadBuildTemplate.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Transportation/Main/TMSLoadBuildTemplate.cdm.json/TMSLoadBuildTemplate</a></td><td><a href="../../../Tables/SupplyChain/Transportation/Main/TMSLoadBuildTemplate.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: Transportation/TMSTransportationSalesLoadBuildingTemplateEntity (this entity)  

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
