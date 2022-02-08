---
title: WHSCatchWeightItemHandlingPolicyV2Entity in WMS - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Catch weight item handling policy V2 in WMS(WHSCatchWeightItemHandlingPolicyV2Entity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/WMS/WHSCatchWeightItemHandlingPolicyV2Entity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Catch weight item handling policy V2</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[PolicyName](#PolicyName)||<a href="WHSCatchWeightItemHandlingPolicyV2Entity.md" target="_blank">WMS/WHSCatchWeightItemHandlingPolicyV2Entity</a>|
|[PolicyDescription](#PolicyDescription)||<a href="WHSCatchWeightItemHandlingPolicyV2Entity.md" target="_blank">WMS/WHSCatchWeightItemHandlingPolicyV2Entity</a>|
|[InboundCatchWeightTagCapturingMethod](#InboundCatchWeightTagCapturingMethod)||<a href="WHSCatchWeightItemHandlingPolicyV2Entity.md" target="_blank">WMS/WHSCatchWeightItemHandlingPolicyV2Entity</a>|
|[InboundWeightCapturingMethod](#InboundWeightCapturingMethod)||<a href="WHSCatchWeightItemHandlingPolicyV2Entity.md" target="_blank">WMS/WHSCatchWeightItemHandlingPolicyV2Entity</a>|
|[CatchWeightTagTracking](#CatchWeightTagTracking)||<a href="WHSCatchWeightItemHandlingPolicyV2Entity.md" target="_blank">WMS/WHSCatchWeightItemHandlingPolicyV2Entity</a>|
|[OutboundCatchWeightTagCapturingMethod](#OutboundCatchWeightTagCapturingMethod)||<a href="WHSCatchWeightItemHandlingPolicyV2Entity.md" target="_blank">WMS/WHSCatchWeightItemHandlingPolicyV2Entity</a>|
|[OutboundWeightCapturingMethod](#OutboundWeightCapturingMethod)||<a href="WHSCatchWeightItemHandlingPolicyV2Entity.md" target="_blank">WMS/WHSCatchWeightItemHandlingPolicyV2Entity</a>|
|[ProductionPickingWeightCapturingMethod](#ProductionPickingWeightCapturingMethod)||<a href="WHSCatchWeightItemHandlingPolicyV2Entity.md" target="_blank">WMS/WHSCatchWeightItemHandlingPolicyV2Entity</a>|
|[SalesOrderWeightCapturingProcess](#SalesOrderWeightCapturingProcess)||<a href="WHSCatchWeightItemHandlingPolicyV2Entity.md" target="_blank">WMS/WHSCatchWeightItemHandlingPolicyV2Entity</a>|
|[TransferIssueWeightCapturingProcess](#TransferIssueWeightCapturingProcess)||<a href="WHSCatchWeightItemHandlingPolicyV2Entity.md" target="_blank">WMS/WHSCatchWeightItemHandlingPolicyV2Entity</a>|
|[CorrectionWeightCapturingProcess](#CorrectionWeightCapturingProcess)||<a href="WHSCatchWeightItemHandlingPolicyV2Entity.md" target="_blank">WMS/WHSCatchWeightItemHandlingPolicyV2Entity</a>|
|[OutboundWeightVarianceMethod](#OutboundWeightVarianceMethod)||<a href="WHSCatchWeightItemHandlingPolicyV2Entity.md" target="_blank">WMS/WHSCatchWeightItemHandlingPolicyV2Entity</a>|
|[MovementWeightCapturingMethod](#MovementWeightCapturingMethod)||<a href="WHSCatchWeightItemHandlingPolicyV2Entity.md" target="_blank">WMS/WHSCatchWeightItemHandlingPolicyV2Entity</a>|
|[CountingWeightCapturingMethod](#CountingWeightCapturingMethod)||<a href="WHSCatchWeightItemHandlingPolicyV2Entity.md" target="_blank">WMS/WHSCatchWeightItemHandlingPolicyV2Entity</a>|
|[WarehouseTransferWeightCapturingMethod](#WarehouseTransferWeightCapturingMethod)||<a href="WHSCatchWeightItemHandlingPolicyV2Entity.md" target="_blank">WMS/WHSCatchWeightItemHandlingPolicyV2Entity</a>|
|[CatchWeightTagDimensionTrackingMethod](#CatchWeightTagDimensionTrackingMethod)||<a href="WHSCatchWeightItemHandlingPolicyV2Entity.md" target="_blank">WMS/WHSCatchWeightItemHandlingPolicyV2Entity</a>|
|[BackingTable_WHSCatchWeightItemHandlingPolicyRelationshipId](#BackingTable_WHSCatchWeightItemHandlingPolicyRelationshipId)||<a href="WHSCatchWeightItemHandlingPolicyV2Entity.md" target="_blank">WMS/WHSCatchWeightItemHandlingPolicyV2Entity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="WHSCatchWeightItemHandlingPolicyV2Entity.md" target="_blank">WMS/WHSCatchWeightItemHandlingPolicyV2Entity</a>|

### <a href=#PolicyName name="PolicyName">PolicyName</a>

First included in: WMS/WHSCatchWeightItemHandlingPolicyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PolicyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PolicyDescription name="PolicyDescription">PolicyDescription</a>

First included in: WMS/WHSCatchWeightItemHandlingPolicyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PolicyDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InboundCatchWeightTagCapturingMethod name="InboundCatchWeightTagCapturingMethod">InboundCatchWeightTagCapturingMethod</a>

First included in: WMS/WHSCatchWeightItemHandlingPolicyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InboundCatchWeightTagCapturingMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InboundWeightCapturingMethod name="InboundWeightCapturingMethod">InboundWeightCapturingMethod</a>

First included in: WMS/WHSCatchWeightItemHandlingPolicyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InboundWeightCapturingMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CatchWeightTagTracking name="CatchWeightTagTracking">CatchWeightTagTracking</a>

First included in: WMS/WHSCatchWeightItemHandlingPolicyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CatchWeightTagTracking attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OutboundCatchWeightTagCapturingMethod name="OutboundCatchWeightTagCapturingMethod">OutboundCatchWeightTagCapturingMethod</a>

First included in: WMS/WHSCatchWeightItemHandlingPolicyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OutboundCatchWeightTagCapturingMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OutboundWeightCapturingMethod name="OutboundWeightCapturingMethod">OutboundWeightCapturingMethod</a>

First included in: WMS/WHSCatchWeightItemHandlingPolicyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OutboundWeightCapturingMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductionPickingWeightCapturingMethod name="ProductionPickingWeightCapturingMethod">ProductionPickingWeightCapturingMethod</a>

First included in: WMS/WHSCatchWeightItemHandlingPolicyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductionPickingWeightCapturingMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesOrderWeightCapturingProcess name="SalesOrderWeightCapturingProcess">SalesOrderWeightCapturingProcess</a>

First included in: WMS/WHSCatchWeightItemHandlingPolicyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesOrderWeightCapturingProcess attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransferIssueWeightCapturingProcess name="TransferIssueWeightCapturingProcess">TransferIssueWeightCapturingProcess</a>

First included in: WMS/WHSCatchWeightItemHandlingPolicyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferIssueWeightCapturingProcess attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CorrectionWeightCapturingProcess name="CorrectionWeightCapturingProcess">CorrectionWeightCapturingProcess</a>

First included in: WMS/WHSCatchWeightItemHandlingPolicyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CorrectionWeightCapturingProcess attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OutboundWeightVarianceMethod name="OutboundWeightVarianceMethod">OutboundWeightVarianceMethod</a>

First included in: WMS/WHSCatchWeightItemHandlingPolicyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OutboundWeightVarianceMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MovementWeightCapturingMethod name="MovementWeightCapturingMethod">MovementWeightCapturingMethod</a>

First included in: WMS/WHSCatchWeightItemHandlingPolicyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MovementWeightCapturingMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CountingWeightCapturingMethod name="CountingWeightCapturingMethod">CountingWeightCapturingMethod</a>

First included in: WMS/WHSCatchWeightItemHandlingPolicyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CountingWeightCapturingMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WarehouseTransferWeightCapturingMethod name="WarehouseTransferWeightCapturingMethod">WarehouseTransferWeightCapturingMethod</a>

First included in: WMS/WHSCatchWeightItemHandlingPolicyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseTransferWeightCapturingMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CatchWeightTagDimensionTrackingMethod name="CatchWeightTagDimensionTrackingMethod">CatchWeightTagDimensionTrackingMethod</a>

First included in: WMS/WHSCatchWeightItemHandlingPolicyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CatchWeightTagDimensionTrackingMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_WHSCatchWeightItemHandlingPolicyRelationshipId name="BackingTable_WHSCatchWeightItemHandlingPolicyRelationshipId">BackingTable_WHSCatchWeightItemHandlingPolicyRelationshipId</a>

First included in: WMS/WHSCatchWeightItemHandlingPolicyV2Entity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_WHSCatchWeightItemHandlingPolicyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Group/WHSCatchWeightItemHandlingPolicy.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/WHSCatchWeightItemHandlingPolicy.cdm.json/WHSCatchWeightItemHandlingPolicy</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Group/WHSCatchWeightItemHandlingPolicy.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: WMS/WHSCatchWeightItemHandlingPolicyV2Entity (this entity)  

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
