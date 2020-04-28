---
title: IntercompanyTradingPartnershipEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Intercompany trading partnership

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/SalesAndMarketing/IntercompanyTradingPartnershipEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Intercompany trading partnership</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[CustomerLegalEntityId](#CustomerLegalEntityId)||<a href="IntercompanyTradingPartnershipEntity.md" target="_blank">SalesAndMarketing/IntercompanyTradingPartnershipEntity</a>|
|[CustomerAccountNumber](#CustomerAccountNumber)||<a href="IntercompanyTradingPartnershipEntity.md" target="_blank">SalesAndMarketing/IntercompanyTradingPartnershipEntity</a>|
|[VendorLegalEntityId](#VendorLegalEntityId)||<a href="IntercompanyTradingPartnershipEntity.md" target="_blank">SalesAndMarketing/IntercompanyTradingPartnershipEntity</a>|
|[VendorAccountNumber](#VendorAccountNumber)||<a href="IntercompanyTradingPartnershipEntity.md" target="_blank">SalesAndMarketing/IntercompanyTradingPartnershipEntity</a>|
|[IsTradingPartnershipActive](#IsTradingPartnershipActive)||<a href="IntercompanyTradingPartnershipEntity.md" target="_blank">SalesAndMarketing/IntercompanyTradingPartnershipEntity</a>|
|[CustomerTradingPartner_CustomerDataAreaId](#CustomerTradingPartner_CustomerDataAreaId)||<a href="IntercompanyTradingPartnershipEntity.md" target="_blank">SalesAndMarketing/IntercompanyTradingPartnershipEntity</a>|
|[CustomerTradingPartner_TradingPartnerType](#CustomerTradingPartner_TradingPartnerType)||<a href="IntercompanyTradingPartnershipEntity.md" target="_blank">SalesAndMarketing/IntercompanyTradingPartnershipEntity</a>|
|[VendorTradingPartner_VendorDataAreaId](#VendorTradingPartner_VendorDataAreaId)||<a href="IntercompanyTradingPartnershipEntity.md" target="_blank">SalesAndMarketing/IntercompanyTradingPartnershipEntity</a>|
|[VendorTradingPartner_TradingPartnerType](#VendorTradingPartner_TradingPartnerType)||<a href="IntercompanyTradingPartnershipEntity.md" target="_blank">SalesAndMarketing/IntercompanyTradingPartnershipEntity</a>|
|[BackingTable_InterCompanyTradingPartnerRelationshipId](#BackingTable_InterCompanyTradingPartnerRelationshipId)||<a href="IntercompanyTradingPartnershipEntity.md" target="_blank">SalesAndMarketing/IntercompanyTradingPartnershipEntity</a>|

### <a href=#CustomerLegalEntityId name="CustomerLegalEntityId">CustomerLegalEntityId</a>

First included in: SalesAndMarketing/IntercompanyTradingPartnershipEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerLegalEntityId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerAccountNumber name="CustomerAccountNumber">CustomerAccountNumber</a>

First included in: SalesAndMarketing/IntercompanyTradingPartnershipEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorLegalEntityId name="VendorLegalEntityId">VendorLegalEntityId</a>

First included in: SalesAndMarketing/IntercompanyTradingPartnershipEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorLegalEntityId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorAccountNumber name="VendorAccountNumber">VendorAccountNumber</a>

First included in: SalesAndMarketing/IntercompanyTradingPartnershipEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsTradingPartnershipActive name="IsTradingPartnershipActive">IsTradingPartnershipActive</a>

First included in: SalesAndMarketing/IntercompanyTradingPartnershipEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsTradingPartnershipActive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerTradingPartner_CustomerDataAreaId name="CustomerTradingPartner_CustomerDataAreaId">CustomerTradingPartner_CustomerDataAreaId</a>

First included in: SalesAndMarketing/IntercompanyTradingPartnershipEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerTradingPartner_CustomerDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerTradingPartner_TradingPartnerType name="CustomerTradingPartner_TradingPartnerType">CustomerTradingPartner_TradingPartnerType</a>

First included in: SalesAndMarketing/IntercompanyTradingPartnershipEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerTradingPartner_TradingPartnerType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorTradingPartner_VendorDataAreaId name="VendorTradingPartner_VendorDataAreaId">VendorTradingPartner_VendorDataAreaId</a>

First included in: SalesAndMarketing/IntercompanyTradingPartnershipEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorTradingPartner_VendorDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorTradingPartner_TradingPartnerType name="VendorTradingPartner_TradingPartnerType">VendorTradingPartner_TradingPartnerType</a>

First included in: SalesAndMarketing/IntercompanyTradingPartnershipEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorTradingPartner_TradingPartnerType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_InterCompanyTradingPartnerRelationshipId name="BackingTable_InterCompanyTradingPartnerRelationshipId">BackingTable_InterCompanyTradingPartnerRelationshipId</a>

First included in: SalesAndMarketing/IntercompanyTradingPartnershipEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_InterCompanyTradingPartnerRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Group/InterCompanyTradingPartner.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Group/InterCompanyTradingPartner.cdm.json/InterCompanyTradingPartner</a></td><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Group/InterCompanyTradingPartner.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
