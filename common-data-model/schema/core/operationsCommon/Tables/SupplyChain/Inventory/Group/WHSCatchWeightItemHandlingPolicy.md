---
title: WHSCatchWeightItemHandlingPolicy in Group - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/13/2020
ms.author: nebanfic
---

# Catch weight item handling policy in Group(WHSCatchWeightItemHandlingPolicy)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/Inventory/Group/WHSCatchWeightItemHandlingPolicy.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[WHSCatchWeightItemHandlingPolicy/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Catch weight item handling policy</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="WHSCatchWeightItemHandlingPolicy.md" target="_blank">Group/WHSCatchWeightItemHandlingPolicy</a>|
|[PolicyName](#PolicyName)||<a href="WHSCatchWeightItemHandlingPolicy.md" target="_blank">Group/WHSCatchWeightItemHandlingPolicy</a>|
|[PolicyDescription](#PolicyDescription)||<a href="WHSCatchWeightItemHandlingPolicy.md" target="_blank">Group/WHSCatchWeightItemHandlingPolicy</a>|
|[InboundCatchWeightTagCapturingMethod](#InboundCatchWeightTagCapturingMethod)||<a href="WHSCatchWeightItemHandlingPolicy.md" target="_blank">Group/WHSCatchWeightItemHandlingPolicy</a>|
|[InboundWeightCapturingMethod](#InboundWeightCapturingMethod)||<a href="WHSCatchWeightItemHandlingPolicy.md" target="_blank">Group/WHSCatchWeightItemHandlingPolicy</a>|
|[CatchWeightTagTracking](#CatchWeightTagTracking)||<a href="WHSCatchWeightItemHandlingPolicy.md" target="_blank">Group/WHSCatchWeightItemHandlingPolicy</a>|
|[OutboundWeightCapturingMethod](#OutboundWeightCapturingMethod)||<a href="WHSCatchWeightItemHandlingPolicy.md" target="_blank">Group/WHSCatchWeightItemHandlingPolicy</a>|
|[ProductionPickingWeightCapturingMethod](#ProductionPickingWeightCapturingMethod)||<a href="WHSCatchWeightItemHandlingPolicy.md" target="_blank">Group/WHSCatchWeightItemHandlingPolicy</a>|
|[SalesOrderWeightCapturingProcess](#SalesOrderWeightCapturingProcess)||<a href="WHSCatchWeightItemHandlingPolicy.md" target="_blank">Group/WHSCatchWeightItemHandlingPolicy</a>|
|[TransferIssueWeightCapturingProcess](#TransferIssueWeightCapturingProcess)||<a href="WHSCatchWeightItemHandlingPolicy.md" target="_blank">Group/WHSCatchWeightItemHandlingPolicy</a>|
|[CountingWeightCapturingMethod](#CountingWeightCapturingMethod)||<a href="WHSCatchWeightItemHandlingPolicy.md" target="_blank">Group/WHSCatchWeightItemHandlingPolicy</a>|
|[OutboundWeightVarianceMethod](#OutboundWeightVarianceMethod)||<a href="WHSCatchWeightItemHandlingPolicy.md" target="_blank">Group/WHSCatchWeightItemHandlingPolicy</a>|
|[MovementWeightCapturingMethod](#MovementWeightCapturingMethod)||<a href="WHSCatchWeightItemHandlingPolicy.md" target="_blank">Group/WHSCatchWeightItemHandlingPolicy</a>|
|[CatchWeightTagDimensionTrackingMethod](#CatchWeightTagDimensionTrackingMethod)||<a href="WHSCatchWeightItemHandlingPolicy.md" target="_blank">Group/WHSCatchWeightItemHandlingPolicy</a>|
|[CycleCountWeightCapturingMethod](#CycleCountWeightCapturingMethod)||<a href="WHSCatchWeightItemHandlingPolicy.md" target="_blank">Group/WHSCatchWeightItemHandlingPolicy</a>|
|[WarehouseTransferWeightCapturingMethod](#WarehouseTransferWeightCapturingMethod)||<a href="WHSCatchWeightItemHandlingPolicy.md" target="_blank">Group/WHSCatchWeightItemHandlingPolicy</a>|
|[OutboundCatchWeightTagCapturingMethod](#OutboundCatchWeightTagCapturingMethod)||<a href="WHSCatchWeightItemHandlingPolicy.md" target="_blank">Group/WHSCatchWeightItemHandlingPolicy</a>|
|[DataAreaId](#DataAreaId)||<a href="WHSCatchWeightItemHandlingPolicy.md" target="_blank">Group/WHSCatchWeightItemHandlingPolicy</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="WHSCatchWeightItemHandlingPolicy.md" target="_blank">Group/WHSCatchWeightItemHandlingPolicy</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Group/WHSCatchWeightItemHandlingPolicy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[WHSCatchWeightItemHandlingPolicy/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PolicyName name="PolicyName">PolicyName</a>

First included in: Group/WHSCatchWeightItemHandlingPolicy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PolicyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PolicyDescription name="PolicyDescription">PolicyDescription</a>

First included in: Group/WHSCatchWeightItemHandlingPolicy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PolicyDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InboundCatchWeightTagCapturingMethod name="InboundCatchWeightTagCapturingMethod">InboundCatchWeightTagCapturingMethod</a>

First included in: Group/WHSCatchWeightItemHandlingPolicy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InboundCatchWeightTagCapturingMethod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#InboundWeightCapturingMethod name="InboundWeightCapturingMethod">InboundWeightCapturingMethod</a>

First included in: Group/WHSCatchWeightItemHandlingPolicy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InboundWeightCapturingMethod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CatchWeightTagTracking name="CatchWeightTagTracking">CatchWeightTagTracking</a>

First included in: Group/WHSCatchWeightItemHandlingPolicy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CatchWeightTagTracking attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#OutboundWeightCapturingMethod name="OutboundWeightCapturingMethod">OutboundWeightCapturingMethod</a>

First included in: Group/WHSCatchWeightItemHandlingPolicy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OutboundWeightCapturingMethod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ProductionPickingWeightCapturingMethod name="ProductionPickingWeightCapturingMethod">ProductionPickingWeightCapturingMethod</a>

First included in: Group/WHSCatchWeightItemHandlingPolicy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductionPickingWeightCapturingMethod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#SalesOrderWeightCapturingProcess name="SalesOrderWeightCapturingProcess">SalesOrderWeightCapturingProcess</a>

First included in: Group/WHSCatchWeightItemHandlingPolicy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesOrderWeightCapturingProcess attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TransferIssueWeightCapturingProcess name="TransferIssueWeightCapturingProcess">TransferIssueWeightCapturingProcess</a>

First included in: Group/WHSCatchWeightItemHandlingPolicy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransferIssueWeightCapturingProcess attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CountingWeightCapturingMethod name="CountingWeightCapturingMethod">CountingWeightCapturingMethod</a>

First included in: Group/WHSCatchWeightItemHandlingPolicy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CountingWeightCapturingMethod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#OutboundWeightVarianceMethod name="OutboundWeightVarianceMethod">OutboundWeightVarianceMethod</a>

First included in: Group/WHSCatchWeightItemHandlingPolicy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OutboundWeightVarianceMethod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#MovementWeightCapturingMethod name="MovementWeightCapturingMethod">MovementWeightCapturingMethod</a>

First included in: Group/WHSCatchWeightItemHandlingPolicy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MovementWeightCapturingMethod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CatchWeightTagDimensionTrackingMethod name="CatchWeightTagDimensionTrackingMethod">CatchWeightTagDimensionTrackingMethod</a>

First included in: Group/WHSCatchWeightItemHandlingPolicy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CatchWeightTagDimensionTrackingMethod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CycleCountWeightCapturingMethod name="CycleCountWeightCapturingMethod">CycleCountWeightCapturingMethod</a>

First included in: Group/WHSCatchWeightItemHandlingPolicy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CycleCountWeightCapturingMethod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#WarehouseTransferWeightCapturingMethod name="WarehouseTransferWeightCapturingMethod">WarehouseTransferWeightCapturingMethod</a>

First included in: Group/WHSCatchWeightItemHandlingPolicy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WarehouseTransferWeightCapturingMethod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#OutboundCatchWeightTagCapturingMethod name="OutboundCatchWeightTagCapturingMethod">OutboundCatchWeightTagCapturingMethod</a>

First included in: Group/WHSCatchWeightItemHandlingPolicy (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OutboundCatchWeightTagCapturingMethod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Group/WHSCatchWeightItemHandlingPolicy (this entity)  

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

First included in: Group/WHSCatchWeightItemHandlingPolicy (this entity)  

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
