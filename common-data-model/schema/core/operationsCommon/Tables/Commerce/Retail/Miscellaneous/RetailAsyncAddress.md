---
title: RetailAsyncAddress - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# RetailAsyncAddress

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Commerce/Retail/Miscellaneous/RetailAsyncAddress.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailAsyncAddress/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailAsyncAddress.md" target="_blank">Miscellaneous/RetailAsyncAddress</a>|
|[OnlineAddressCreated](#OnlineAddressCreated)||<a href="RetailAsyncAddress.md" target="_blank">Miscellaneous/RetailAsyncAddress</a>|
|[CustAccountAsync](#CustAccountAsync)||<a href="RetailAsyncAddress.md" target="_blank">Miscellaneous/RetailAsyncAddress</a>|
|[CustAccount](#CustAccount)||<a href="RetailAsyncAddress.md" target="_blank">Miscellaneous/RetailAsyncAddress</a>|
|[CustName](#CustName)||<a href="RetailAsyncAddress.md" target="_blank">Miscellaneous/RetailAsyncAddress</a>|
|[Street](#Street)||<a href="RetailAsyncAddress.md" target="_blank">Miscellaneous/RetailAsyncAddress</a>|
|[State](#State)||<a href="RetailAsyncAddress.md" target="_blank">Miscellaneous/RetailAsyncAddress</a>|
|[County](#County)||<a href="RetailAsyncAddress.md" target="_blank">Miscellaneous/RetailAsyncAddress</a>|
|[Phone](#Phone)||<a href="RetailAsyncAddress.md" target="_blank">Miscellaneous/RetailAsyncAddress</a>|
|[Zip](#Zip)||<a href="RetailAsyncAddress.md" target="_blank">Miscellaneous/RetailAsyncAddress</a>|
|[Email](#Email)||<a href="RetailAsyncAddress.md" target="_blank">Miscellaneous/RetailAsyncAddress</a>|
|[Url](#Url)||<a href="RetailAsyncAddress.md" target="_blank">Miscellaneous/RetailAsyncAddress</a>|
|[TaxGroup](#TaxGroup)||<a href="RetailAsyncAddress.md" target="_blank">Miscellaneous/RetailAsyncAddress</a>|
|[City](#City)||<a href="RetailAsyncAddress.md" target="_blank">Miscellaneous/RetailAsyncAddress</a>|
|[Country](#Country)||<a href="RetailAsyncAddress.md" target="_blank">Miscellaneous/RetailAsyncAddress</a>|
|[StreetNumber](#StreetNumber)||<a href="RetailAsyncAddress.md" target="_blank">Miscellaneous/RetailAsyncAddress</a>|
|[DistrictName](#DistrictName)||<a href="RetailAsyncAddress.md" target="_blank">Miscellaneous/RetailAsyncAddress</a>|
|[BuildingCompliment](#BuildingCompliment)||<a href="RetailAsyncAddress.md" target="_blank">Miscellaneous/RetailAsyncAddress</a>|
|[MakePostalAddressPrimary](#MakePostalAddressPrimary)||<a href="RetailAsyncAddress.md" target="_blank">Miscellaneous/RetailAsyncAddress</a>|
|[Role](#Role)||<a href="RetailAsyncAddress.md" target="_blank">Miscellaneous/RetailAsyncAddress</a>|
|[ReplicationCounterFromOrigin](#ReplicationCounterFromOrigin)||<a href="RetailAsyncAddress.md" target="_blank">Miscellaneous/RetailAsyncAddress</a>|
|[AddressId](#AddressId)||<a href="RetailAsyncAddress.md" target="_blank">Miscellaneous/RetailAsyncAddress</a>|
|[LogisticsLocationRoleRecordId](#LogisticsLocationRoleRecordId)||<a href="RetailAsyncAddress.md" target="_blank">Miscellaneous/RetailAsyncAddress</a>|
|[LogisticsPostalAddress](#LogisticsPostalAddress)||<a href="RetailAsyncAddress.md" target="_blank">Miscellaneous/RetailAsyncAddress</a>|
|[DataAreaId](#DataAreaId)||<a href="RetailAsyncAddress.md" target="_blank">Miscellaneous/RetailAsyncAddress</a>|
|[Relationship_LogisticsPostalAddressRelationshipId](#Relationship_LogisticsPostalAddressRelationshipId)||<a href="RetailAsyncAddress.md" target="_blank">Miscellaneous/RetailAsyncAddress</a>|
|[Relationship_RetailAsyncCustomerRelationshipId](#Relationship_RetailAsyncCustomerRelationshipId)||<a href="RetailAsyncAddress.md" target="_blank">Miscellaneous/RetailAsyncAddress</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="RetailAsyncAddress.md" target="_blank">Miscellaneous/RetailAsyncAddress</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/RetailAsyncAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailAsyncAddress/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#OnlineAddressCreated name="OnlineAddressCreated">OnlineAddressCreated</a>

First included in: Miscellaneous/RetailAsyncAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OnlineAddressCreated attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CustAccountAsync name="CustAccountAsync">CustAccountAsync</a>

First included in: Miscellaneous/RetailAsyncAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustAccountAsync attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustAccount name="CustAccount">CustAccount</a>

First included in: Miscellaneous/RetailAsyncAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustName name="CustName">CustName</a>

First included in: Miscellaneous/RetailAsyncAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Street name="Street">Street</a>

First included in: Miscellaneous/RetailAsyncAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Street attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#State name="State">State</a>

First included in: Miscellaneous/RetailAsyncAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the State attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#County name="County">County</a>

First included in: Miscellaneous/RetailAsyncAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the County attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Phone name="Phone">Phone</a>

First included in: Miscellaneous/RetailAsyncAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Phone attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Zip name="Zip">Zip</a>

First included in: Miscellaneous/RetailAsyncAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Zip attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Email name="Email">Email</a>

First included in: Miscellaneous/RetailAsyncAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Email attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Url name="Url">Url</a>

First included in: Miscellaneous/RetailAsyncAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Url attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxGroup name="TaxGroup">TaxGroup</a>

First included in: Miscellaneous/RetailAsyncAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#City name="City">City</a>

First included in: Miscellaneous/RetailAsyncAddress (this entity)  

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

### <a href=#Country name="Country">Country</a>

First included in: Miscellaneous/RetailAsyncAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Country attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StreetNumber name="StreetNumber">StreetNumber</a>

First included in: Miscellaneous/RetailAsyncAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StreetNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DistrictName name="DistrictName">DistrictName</a>

First included in: Miscellaneous/RetailAsyncAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DistrictName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BuildingCompliment name="BuildingCompliment">BuildingCompliment</a>

First included in: Miscellaneous/RetailAsyncAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BuildingCompliment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MakePostalAddressPrimary name="MakePostalAddressPrimary">MakePostalAddressPrimary</a>

First included in: Miscellaneous/RetailAsyncAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MakePostalAddressPrimary attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Role name="Role">Role</a>

First included in: Miscellaneous/RetailAsyncAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Role attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ReplicationCounterFromOrigin name="ReplicationCounterFromOrigin">ReplicationCounterFromOrigin</a>

First included in: Miscellaneous/RetailAsyncAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReplicationCounterFromOrigin attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AddressId name="AddressId">AddressId</a>

First included in: Miscellaneous/RetailAsyncAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AddressId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LogisticsLocationRoleRecordId name="LogisticsLocationRoleRecordId">LogisticsLocationRoleRecordId</a>

First included in: Miscellaneous/RetailAsyncAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogisticsLocationRoleRecordId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#LogisticsPostalAddress name="LogisticsPostalAddress">LogisticsPostalAddress</a>

First included in: Miscellaneous/RetailAsyncAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LogisticsPostalAddress attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Miscellaneous/RetailAsyncAddress (this entity)  

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

### <a href=#Relationship_LogisticsPostalAddressRelationshipId name="Relationship_LogisticsPostalAddressRelationshipId">Relationship_LogisticsPostalAddressRelationshipId</a>

First included in: Miscellaneous/RetailAsyncAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LogisticsPostalAddressRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_RetailAsyncCustomerRelationshipId name="Relationship_RetailAsyncCustomerRelationshipId">Relationship_RetailAsyncCustomerRelationshipId</a>

First included in: Miscellaneous/RetailAsyncAddress (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailAsyncCustomerRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailAsyncCustomer.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Miscellaneous/RetailAsyncCustomer.cdm.json/RetailAsyncCustomer</a></td><td><a href="RetailAsyncCustomer.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Miscellaneous/RetailAsyncAddress (this entity)  

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
