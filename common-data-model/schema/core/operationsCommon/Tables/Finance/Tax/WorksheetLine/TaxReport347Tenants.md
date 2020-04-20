---
title: TaxReport347Tenants - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# TaxReport347Tenants

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Tax/WorksheetLine/TaxReport347Tenants.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxReport347Tenants/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="TaxReport347Tenants.md" target="_blank">WorksheetLine/TaxReport347Tenants</a>|
|[Amount](#Amount)||<a href="TaxReport347Tenants.md" target="_blank">WorksheetLine/TaxReport347Tenants</a>|
|[City](#City)||<a href="TaxReport347Tenants.md" target="_blank">WorksheetLine/TaxReport347Tenants</a>|
|[CountryRegionId](#CountryRegionId)||<a href="TaxReport347Tenants.md" target="_blank">WorksheetLine/TaxReport347Tenants</a>|
|[CountyId](#CountyId)||<a href="TaxReport347Tenants.md" target="_blank">WorksheetLine/TaxReport347Tenants</a>|
|[Door](#Door)||<a href="TaxReport347Tenants.md" target="_blank">WorksheetLine/TaxReport347Tenants</a>|
|[Entrance](#Entrance)||<a href="TaxReport347Tenants.md" target="_blank">WorksheetLine/TaxReport347Tenants</a>|
|[Floor](#Floor)||<a href="TaxReport347Tenants.md" target="_blank">WorksheetLine/TaxReport347Tenants</a>|
|[Name](#Name)||<a href="TaxReport347Tenants.md" target="_blank">WorksheetLine/TaxReport347Tenants</a>|
|[PropertyReference](#PropertyReference)||<a href="TaxReport347Tenants.md" target="_blank">WorksheetLine/TaxReport347Tenants</a>|
|[SituationCode](#SituationCode)||<a href="TaxReport347Tenants.md" target="_blank">WorksheetLine/TaxReport347Tenants</a>|
|[StreetName](#StreetName)||<a href="TaxReport347Tenants.md" target="_blank">WorksheetLine/TaxReport347Tenants</a>|
|[StreetNum](#StreetNum)||<a href="TaxReport347Tenants.md" target="_blank">WorksheetLine/TaxReport347Tenants</a>|
|[TaxRep347AddressAbbrev](#TaxRep347AddressAbbrev)||<a href="TaxReport347Tenants.md" target="_blank">WorksheetLine/TaxReport347Tenants</a>|
|[TaxReport347Table](#TaxReport347Table)||<a href="TaxReport347Tenants.md" target="_blank">WorksheetLine/TaxReport347Tenants</a>|
|[VATNum](#VATNum)||<a href="TaxReport347Tenants.md" target="_blank">WorksheetLine/TaxReport347Tenants</a>|
|[ZipCode](#ZipCode)||<a href="TaxReport347Tenants.md" target="_blank">WorksheetLine/TaxReport347Tenants</a>|
|[DataAreaId](#DataAreaId)||<a href="TaxReport347Tenants.md" target="_blank">WorksheetLine/TaxReport347Tenants</a>|
|[Relationship_AddressCountyRelationshipId](#Relationship_AddressCountyRelationshipId)||<a href="TaxReport347Tenants.md" target="_blank">WorksheetLine/TaxReport347Tenants</a>|
|[Relationship_LogisticsAddressCountryRegionRelationshipId](#Relationship_LogisticsAddressCountryRegionRelationshipId)||<a href="TaxReport347Tenants.md" target="_blank">WorksheetLine/TaxReport347Tenants</a>|
|[Relationship_LogisticsAddressZipCodeRelationshipId](#Relationship_LogisticsAddressZipCodeRelationshipId)||<a href="TaxReport347Tenants.md" target="_blank">WorksheetLine/TaxReport347Tenants</a>|
|[Relationship_TaxRep347AddressAbbrevRelationshipId](#Relationship_TaxRep347AddressAbbrevRelationshipId)||<a href="TaxReport347Tenants.md" target="_blank">WorksheetLine/TaxReport347Tenants</a>|
|[Relationship_TaxReport347TableRelationshipId](#Relationship_TaxReport347TableRelationshipId)||<a href="TaxReport347Tenants.md" target="_blank">WorksheetLine/TaxReport347Tenants</a>|
|[Relationship_TaxReport347TransRelationshipId](#Relationship_TaxReport347TransRelationshipId)||<a href="TaxReport347Tenants.md" target="_blank">WorksheetLine/TaxReport347Tenants</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="TaxReport347Tenants.md" target="_blank">WorksheetLine/TaxReport347Tenants</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetLine/TaxReport347Tenants (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxReport347Tenants/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Amount name="Amount">Amount</a>

First included in: WorksheetLine/TaxReport347Tenants (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Amount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#City name="City">City</a>

First included in: WorksheetLine/TaxReport347Tenants (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the City attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CountryRegionId name="CountryRegionId">CountryRegionId</a>

First included in: WorksheetLine/TaxReport347Tenants (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CountryRegionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CountyId name="CountyId">CountyId</a>

First included in: WorksheetLine/TaxReport347Tenants (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CountyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Door name="Door">Door</a>

First included in: WorksheetLine/TaxReport347Tenants (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Door attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Entrance name="Entrance">Entrance</a>

First included in: WorksheetLine/TaxReport347Tenants (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Entrance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Floor name="Floor">Floor</a>

First included in: WorksheetLine/TaxReport347Tenants (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Floor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: WorksheetLine/TaxReport347Tenants (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PropertyReference name="PropertyReference">PropertyReference</a>

First included in: WorksheetLine/TaxReport347Tenants (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PropertyReference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SituationCode name="SituationCode">SituationCode</a>

First included in: WorksheetLine/TaxReport347Tenants (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SituationCode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#StreetName name="StreetName">StreetName</a>

First included in: WorksheetLine/TaxReport347Tenants (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StreetName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StreetNum name="StreetNum">StreetNum</a>

First included in: WorksheetLine/TaxReport347Tenants (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StreetNum attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxRep347AddressAbbrev name="TaxRep347AddressAbbrev">TaxRep347AddressAbbrev</a>

First included in: WorksheetLine/TaxReport347Tenants (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxRep347AddressAbbrev attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxReport347Table name="TaxReport347Table">TaxReport347Table</a>

First included in: WorksheetLine/TaxReport347Tenants (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxReport347Table attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#VATNum name="VATNum">VATNum</a>

First included in: WorksheetLine/TaxReport347Tenants (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VATNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ZipCode name="ZipCode">ZipCode</a>

First included in: WorksheetLine/TaxReport347Tenants (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ZipCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetLine/TaxReport347Tenants (this entity)  

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

### <a href=#Relationship_AddressCountyRelationshipId name="Relationship_AddressCountyRelationshipId">Relationship_AddressCountyRelationshipId</a>

First included in: WorksheetLine/TaxReport347Tenants (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AddressCountyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Group/LogisticsAddressCounty.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Group/LogisticsAddressCounty.cdm.json/LogisticsAddressCounty</a></td><td><a href="../../../Common/GAB/Group/LogisticsAddressCounty.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LogisticsAddressCountryRegionRelationshipId name="Relationship_LogisticsAddressCountryRegionRelationshipId">Relationship_LogisticsAddressCountryRegionRelationshipId</a>

First included in: WorksheetLine/TaxReport347Tenants (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LogisticsAddressCountryRegionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Group/LogisticsAddressCountryRegion.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Group/LogisticsAddressCountryRegion.cdm.json/LogisticsAddressCountryRegion</a></td><td><a href="../../../Common/GAB/Group/LogisticsAddressCountryRegion.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LogisticsAddressZipCodeRelationshipId name="Relationship_LogisticsAddressZipCodeRelationshipId">Relationship_LogisticsAddressZipCodeRelationshipId</a>

First included in: WorksheetLine/TaxReport347Tenants (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LogisticsAddressZipCodeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Group/LogisticsAddressZipCode.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Group/LogisticsAddressZipCode.cdm.json/LogisticsAddressZipCode</a></td><td><a href="../../../Common/GAB/Group/LogisticsAddressZipCode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxRep347AddressAbbrevRelationshipId name="Relationship_TaxRep347AddressAbbrevRelationshipId">Relationship_TaxRep347AddressAbbrevRelationshipId</a>

First included in: WorksheetLine/TaxReport347Tenants (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxRep347AddressAbbrevRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/TaxRep347AddressAbbrev.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxRep347AddressAbbrev.cdm.json/TaxRep347AddressAbbrev</a></td><td><a href="../Group/TaxRep347AddressAbbrev.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxReport347TableRelationshipId name="Relationship_TaxReport347TableRelationshipId">Relationship_TaxReport347TableRelationshipId</a>

First included in: WorksheetLine/TaxReport347Tenants (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxReport347TableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/TaxReport347Table.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/WorksheetHeader/TaxReport347Table.cdm.json/TaxReport347Table</a></td><td><a href="../WorksheetHeader/TaxReport347Table.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxReport347TransRelationshipId name="Relationship_TaxReport347TransRelationshipId">Relationship_TaxReport347TransRelationshipId</a>

First included in: WorksheetLine/TaxReport347Tenants (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxReport347TransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TaxReport347Trans.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/WorksheetLine/TaxReport347Trans.cdm.json/TaxReport347Trans</a></td><td><a href="TaxReport347Trans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetLine/TaxReport347Tenants (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
