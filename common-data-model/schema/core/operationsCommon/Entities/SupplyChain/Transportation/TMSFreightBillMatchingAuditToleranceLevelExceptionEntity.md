---
title: TMSFreightBillMatchingAuditToleranceLevelExceptionEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Freight bill matching audit tolerance level exceptions

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/Transportation/TMSFreightBillMatchingAuditToleranceLevelExceptionEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Freight bill matching audit tolerance level exceptions</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[FreightBillMatchingAuditToleranceLevelId](#FreightBillMatchingAuditToleranceLevelId)||<a href="TMSFreightBillMatchingAuditToleranceLevelExceptionEntity.md" target="_blank">Transportation/TMSFreightBillMatchingAuditToleranceLevelExceptionEntity</a>|
|[MaximumAuditToleranceUnitType](#MaximumAuditToleranceUnitType)||<a href="TMSFreightBillMatchingAuditToleranceLevelExceptionEntity.md" target="_blank">Transportation/TMSFreightBillMatchingAuditToleranceLevelExceptionEntity</a>|
|[MinimumAuditToleranceUnitType](#MinimumAuditToleranceUnitType)||<a href="TMSFreightBillMatchingAuditToleranceLevelExceptionEntity.md" target="_blank">Transportation/TMSFreightBillMatchingAuditToleranceLevelExceptionEntity</a>|
|[TransportationBillingGroupId](#TransportationBillingGroupId)||<a href="TMSFreightBillMatchingAuditToleranceLevelExceptionEntity.md" target="_blank">Transportation/TMSFreightBillMatchingAuditToleranceLevelExceptionEntity</a>|
|[ShippingCarrierAccessorialChargeId](#ShippingCarrierAccessorialChargeId)||<a href="TMSFreightBillMatchingAuditToleranceLevelExceptionEntity.md" target="_blank">Transportation/TMSFreightBillMatchingAuditToleranceLevelExceptionEntity</a>|
|[TransportationHubAccessorialChargeId](#TransportationHubAccessorialChargeId)||<a href="TMSFreightBillMatchingAuditToleranceLevelExceptionEntity.md" target="_blank">Transportation/TMSFreightBillMatchingAuditToleranceLevelExceptionEntity</a>|
|[MaximumAuditToleranceAmount](#MaximumAuditToleranceAmount)||<a href="TMSFreightBillMatchingAuditToleranceLevelExceptionEntity.md" target="_blank">Transportation/TMSFreightBillMatchingAuditToleranceLevelExceptionEntity</a>|
|[MaximumAuditTolerancePercentage](#MaximumAuditTolerancePercentage)||<a href="TMSFreightBillMatchingAuditToleranceLevelExceptionEntity.md" target="_blank">Transportation/TMSFreightBillMatchingAuditToleranceLevelExceptionEntity</a>|
|[MinimumAuditToleranceAmount](#MinimumAuditToleranceAmount)||<a href="TMSFreightBillMatchingAuditToleranceLevelExceptionEntity.md" target="_blank">Transportation/TMSFreightBillMatchingAuditToleranceLevelExceptionEntity</a>|
|[MinimumAuditTolerancePercentage](#MinimumAuditTolerancePercentage)||<a href="TMSFreightBillMatchingAuditToleranceLevelExceptionEntity.md" target="_blank">Transportation/TMSFreightBillMatchingAuditToleranceLevelExceptionEntity</a>|
|[BackingTable_TMSAuditExceptionRelationshipId](#BackingTable_TMSAuditExceptionRelationshipId)||<a href="TMSFreightBillMatchingAuditToleranceLevelExceptionEntity.md" target="_blank">Transportation/TMSFreightBillMatchingAuditToleranceLevelExceptionEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="TMSFreightBillMatchingAuditToleranceLevelExceptionEntity.md" target="_blank">Transportation/TMSFreightBillMatchingAuditToleranceLevelExceptionEntity</a>|

### <a href=#FreightBillMatchingAuditToleranceLevelId name="FreightBillMatchingAuditToleranceLevelId">FreightBillMatchingAuditToleranceLevelId</a>

First included in: Transportation/TMSFreightBillMatchingAuditToleranceLevelExceptionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FreightBillMatchingAuditToleranceLevelId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumAuditToleranceUnitType name="MaximumAuditToleranceUnitType">MaximumAuditToleranceUnitType</a>

First included in: Transportation/TMSFreightBillMatchingAuditToleranceLevelExceptionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumAuditToleranceUnitType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinimumAuditToleranceUnitType name="MinimumAuditToleranceUnitType">MinimumAuditToleranceUnitType</a>

First included in: Transportation/TMSFreightBillMatchingAuditToleranceLevelExceptionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumAuditToleranceUnitType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationBillingGroupId name="TransportationBillingGroupId">TransportationBillingGroupId</a>

First included in: Transportation/TMSFreightBillMatchingAuditToleranceLevelExceptionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationBillingGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ShippingCarrierAccessorialChargeId name="ShippingCarrierAccessorialChargeId">ShippingCarrierAccessorialChargeId</a>

First included in: Transportation/TMSFreightBillMatchingAuditToleranceLevelExceptionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ShippingCarrierAccessorialChargeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationHubAccessorialChargeId name="TransportationHubAccessorialChargeId">TransportationHubAccessorialChargeId</a>

First included in: Transportation/TMSFreightBillMatchingAuditToleranceLevelExceptionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationHubAccessorialChargeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumAuditToleranceAmount name="MaximumAuditToleranceAmount">MaximumAuditToleranceAmount</a>

First included in: Transportation/TMSFreightBillMatchingAuditToleranceLevelExceptionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumAuditToleranceAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumAuditTolerancePercentage name="MaximumAuditTolerancePercentage">MaximumAuditTolerancePercentage</a>

First included in: Transportation/TMSFreightBillMatchingAuditToleranceLevelExceptionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumAuditTolerancePercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinimumAuditToleranceAmount name="MinimumAuditToleranceAmount">MinimumAuditToleranceAmount</a>

First included in: Transportation/TMSFreightBillMatchingAuditToleranceLevelExceptionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumAuditToleranceAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinimumAuditTolerancePercentage name="MinimumAuditTolerancePercentage">MinimumAuditTolerancePercentage</a>

First included in: Transportation/TMSFreightBillMatchingAuditToleranceLevelExceptionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumAuditTolerancePercentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_TMSAuditExceptionRelationshipId name="BackingTable_TMSAuditExceptionRelationshipId">BackingTable_TMSAuditExceptionRelationshipId</a>

First included in: Transportation/TMSFreightBillMatchingAuditToleranceLevelExceptionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_TMSAuditExceptionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Transportation/Group/TMSAuditException.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Transportation/Group/TMSAuditException.cdm.json/TMSAuditException</a></td><td><a href="../../../Tables/SupplyChain/Transportation/Group/TMSAuditException.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: Transportation/TMSFreightBillMatchingAuditToleranceLevelExceptionEntity (this entity)  

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
