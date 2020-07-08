---
title: RequisitionReplenishControlSubmsnParam in Parameter - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/8/2020
ms.author: nebanfic
---

# Requisition replenishment submission parameters in Parameter(RequisitionReplenishControlSubmsnParam)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Parameter/RequisitionReplenishControlSubmsnParam.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RequisitionReplenishControlSubmsnParam/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Requisition replenishment submission parameters</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RequisitionReplenishControlSubmsnParam.md" target="_blank">Parameter/RequisitionReplenishControlSubmsnParam</a>|
|[FieldId](#FieldId)||<a href="RequisitionReplenishControlSubmsnParam.md" target="_blank">Parameter/RequisitionReplenishControlSubmsnParam</a>|
|[PurchReqControlSubmissionRequirement](#PurchReqControlSubmissionRequirement)||<a href="RequisitionReplenishControlSubmsnParam.md" target="_blank">Parameter/RequisitionReplenishControlSubmsnParam</a>|
|[RequisitionReplenishControlRule](#RequisitionReplenishControlRule)||<a href="RequisitionReplenishControlSubmsnParam.md" target="_blank">Parameter/RequisitionReplenishControlSubmsnParam</a>|
|[Relationship_RequisitionReplenishControlRuleRelationshipId](#Relationship_RequisitionReplenishControlRuleRelationshipId)||<a href="RequisitionReplenishControlSubmsnParam.md" target="_blank">Parameter/RequisitionReplenishControlSubmsnParam</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Parameter/RequisitionReplenishControlSubmsnParam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RequisitionReplenishControlSubmsnParam/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FieldId name="FieldId">FieldId</a>

First included in: Parameter/RequisitionReplenishControlSubmsnParam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FieldId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PurchReqControlSubmissionRequirement name="PurchReqControlSubmissionRequirement">PurchReqControlSubmissionRequirement</a>

First included in: Parameter/RequisitionReplenishControlSubmsnParam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Workflow requirement</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchReqControlSubmissionRequirement attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Workflow requirement</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#RequisitionReplenishControlRule name="RequisitionReplenishControlRule">RequisitionReplenishControlRule</a>

First included in: Parameter/RequisitionReplenishControlSubmsnParam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequisitionReplenishControlRule attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_RequisitionReplenishControlRuleRelationshipId name="Relationship_RequisitionReplenishControlRuleRelationshipId">Relationship_RequisitionReplenishControlRuleRelationshipId</a>

First included in: Parameter/RequisitionReplenishControlSubmsnParam (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RequisitionReplenishControlRuleRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RequisitionReplenishControlRule.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Parameter/RequisitionReplenishControlRule.cdm.json/RequisitionReplenishControlRule</a></td><td><a href="RequisitionReplenishControlRule.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
