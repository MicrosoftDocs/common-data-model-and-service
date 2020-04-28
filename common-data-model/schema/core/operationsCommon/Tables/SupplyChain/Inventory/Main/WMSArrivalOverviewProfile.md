---
title: WMSArrivalOverviewProfile - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Arrival overview profiles

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/Inventory/Main/WMSArrivalOverviewProfile.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[WMSArrivalOverviewProfile/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Arrival overview profiles</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="WMSArrivalOverviewProfile.md" target="_blank">Main/WMSArrivalOverviewProfile</a>|
|[Name](#Name)||<a href="WMSArrivalOverviewProfile.md" target="_blank">Main/WMSArrivalOverviewProfile</a>|
|[ProgressSelection](#ProgressSelection)||<a href="WMSArrivalOverviewProfile.md" target="_blank">Main/WMSArrivalOverviewProfile</a>|
|[DaysBack](#DaysBack)||<a href="WMSArrivalOverviewProfile.md" target="_blank">Main/WMSArrivalOverviewProfile</a>|
|[DaysForward](#DaysForward)||<a href="WMSArrivalOverviewProfile.md" target="_blank">Main/WMSArrivalOverviewProfile</a>|
|[WarehouseRange](#WarehouseRange)||<a href="WMSArrivalOverviewProfile.md" target="_blank">Main/WMSArrivalOverviewProfile</a>|
|[VendorReference](#VendorReference)||<a href="WMSArrivalOverviewProfile.md" target="_blank">Main/WMSArrivalOverviewProfile</a>|
|[Account](#Account)||<a href="WMSArrivalOverviewProfile.md" target="_blank">Main/WMSArrivalOverviewProfile</a>|
|[ItemId](#ItemId)||<a href="WMSArrivalOverviewProfile.md" target="_blank">Main/WMSArrivalOverviewProfile</a>|
|[DeliveryModeId](#DeliveryModeId)||<a href="WMSArrivalOverviewProfile.md" target="_blank">Main/WMSArrivalOverviewProfile</a>|
|[ReturnItemNum](#ReturnItemNum)||<a href="WMSArrivalOverviewProfile.md" target="_blank">Main/WMSArrivalOverviewProfile</a>|
|[ReferenceRange](#ReferenceRange)||<a href="WMSArrivalOverviewProfile.md" target="_blank">Main/WMSArrivalOverviewProfile</a>|
|[SiteId](#SiteId)||<a href="WMSArrivalOverviewProfile.md" target="_blank">Main/WMSArrivalOverviewProfile</a>|
|[JournalNameId](#JournalNameId)||<a href="WMSArrivalOverviewProfile.md" target="_blank">Main/WMSArrivalOverviewProfile</a>|
|[WarehouseId](#WarehouseId)||<a href="WMSArrivalOverviewProfile.md" target="_blank">Main/WMSArrivalOverviewProfile</a>|
|[LocationId](#LocationId)||<a href="WMSArrivalOverviewProfile.md" target="_blank">Main/WMSArrivalOverviewProfile</a>|
|[IncludePurchase](#IncludePurchase)||<a href="WMSArrivalOverviewProfile.md" target="_blank">Main/WMSArrivalOverviewProfile</a>|
|[IncludeProduction](#IncludeProduction)||<a href="WMSArrivalOverviewProfile.md" target="_blank">Main/WMSArrivalOverviewProfile</a>|
|[IncludeTransfer](#IncludeTransfer)||<a href="WMSArrivalOverviewProfile.md" target="_blank">Main/WMSArrivalOverviewProfile</a>|
|[IncludeQuarantine](#IncludeQuarantine)||<a href="WMSArrivalOverviewProfile.md" target="_blank">Main/WMSArrivalOverviewProfile</a>|
|[IncludeOther](#IncludeOther)||<a href="WMSArrivalOverviewProfile.md" target="_blank">Main/WMSArrivalOverviewProfile</a>|
|[IncludeReturn](#IncludeReturn)||<a href="WMSArrivalOverviewProfile.md" target="_blank">Main/WMSArrivalOverviewProfile</a>|
|[UpdateOnStartup](#UpdateOnStartup)||<a href="WMSArrivalOverviewProfile.md" target="_blank">Main/WMSArrivalOverviewProfile</a>|
|[UpdateOnRangeChange](#UpdateOnRangeChange)||<a href="WMSArrivalOverviewProfile.md" target="_blank">Main/WMSArrivalOverviewProfile</a>|
|[IncludeConsignmentReplenishmentOrder](#IncludeConsignmentReplenishmentOrder)||<a href="WMSArrivalOverviewProfile.md" target="_blank">Main/WMSArrivalOverviewProfile</a>|
|[DataAreaId](#DataAreaId)||<a href="WMSArrivalOverviewProfile.md" target="_blank">Main/WMSArrivalOverviewProfile</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="WMSArrivalOverviewProfile.md" target="_blank">Main/WMSArrivalOverviewProfile</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/WMSArrivalOverviewProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[WMSArrivalOverviewProfile/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: Main/WMSArrivalOverviewProfile (this entity)  

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

### <a href=#ProgressSelection name="ProgressSelection">ProgressSelection</a>

First included in: Main/WMSArrivalOverviewProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProgressSelection attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DaysBack name="DaysBack">DaysBack</a>

First included in: Main/WMSArrivalOverviewProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Days back</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DaysBack attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Days back</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DaysForward name="DaysForward">DaysForward</a>

First included in: Main/WMSArrivalOverviewProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Days forward</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DaysForward attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Days forward</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseRange name="WarehouseRange">WarehouseRange</a>

First included in: Main/WMSArrivalOverviewProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseRange attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorReference name="VendorReference">VendorReference</a>

First included in: Main/WMSArrivalOverviewProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorReference attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Account name="Account">Account</a>

First included in: Main/WMSArrivalOverviewProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Account attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemId name="ItemId">ItemId</a>

First included in: Main/WMSArrivalOverviewProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeliveryModeId name="DeliveryModeId">DeliveryModeId</a>

First included in: Main/WMSArrivalOverviewProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeliveryModeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReturnItemNum name="ReturnItemNum">ReturnItemNum</a>

First included in: Main/WMSArrivalOverviewProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnItemNum attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReferenceRange name="ReferenceRange">ReferenceRange</a>

First included in: Main/WMSArrivalOverviewProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReferenceRange attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SiteId name="SiteId">SiteId</a>

First included in: Main/WMSArrivalOverviewProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Restrict to site</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Restrict to site</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JournalNameId name="JournalNameId">JournalNameId</a>

First included in: Main/WMSArrivalOverviewProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalNameId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseId name="WarehouseId">WarehouseId</a>

First included in: Main/WMSArrivalOverviewProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LocationId name="LocationId">LocationId</a>

First included in: Main/WMSArrivalOverviewProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LocationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IncludePurchase name="IncludePurchase">IncludePurchase</a>

First included in: Main/WMSArrivalOverviewProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IncludePurchase attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IncludeProduction name="IncludeProduction">IncludeProduction</a>

First included in: Main/WMSArrivalOverviewProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IncludeProduction attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IncludeTransfer name="IncludeTransfer">IncludeTransfer</a>

First included in: Main/WMSArrivalOverviewProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IncludeTransfer attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IncludeQuarantine name="IncludeQuarantine">IncludeQuarantine</a>

First included in: Main/WMSArrivalOverviewProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IncludeQuarantine attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IncludeOther name="IncludeOther">IncludeOther</a>

First included in: Main/WMSArrivalOverviewProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IncludeOther attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IncludeReturn name="IncludeReturn">IncludeReturn</a>

First included in: Main/WMSArrivalOverviewProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IncludeReturn attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#UpdateOnStartup name="UpdateOnStartup">UpdateOnStartup</a>

First included in: Main/WMSArrivalOverviewProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UpdateOnStartup attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#UpdateOnRangeChange name="UpdateOnRangeChange">UpdateOnRangeChange</a>

First included in: Main/WMSArrivalOverviewProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UpdateOnRangeChange attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IncludeConsignmentReplenishmentOrder name="IncludeConsignmentReplenishmentOrder">IncludeConsignmentReplenishmentOrder</a>

First included in: Main/WMSArrivalOverviewProfile (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IncludeConsignmentReplenishmentOrder attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Main/WMSArrivalOverviewProfile (this entity)  

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

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Main/WMSArrivalOverviewProfile (this entity)  

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
