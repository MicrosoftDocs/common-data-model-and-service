---
title: CFMPaymentRequestTypeEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# CFMPaymentRequestTypeEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Entities/Finance/RCashFlowManagement/CFMPaymentRequestTypeEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[Description](#Description)||<a href="CFMPaymentRequestTypeEntity.md" target="_blank">RCashFlowManagement/CFMPaymentRequestTypeEntity</a>|
|[Direction](#Direction)||<a href="CFMPaymentRequestTypeEntity.md" target="_blank">RCashFlowManagement/CFMPaymentRequestTypeEntity</a>|
|[PaymentPriority](#PaymentPriority)||<a href="CFMPaymentRequestTypeEntity.md" target="_blank">RCashFlowManagement/CFMPaymentRequestTypeEntity</a>|
|[PaymentRequestType](#PaymentRequestType)||<a href="CFMPaymentRequestTypeEntity.md" target="_blank">RCashFlowManagement/CFMPaymentRequestTypeEntity</a>|
|[PriorityCode](#PriorityCode)||<a href="CFMPaymentRequestTypeEntity.md" target="_blank">RCashFlowManagement/CFMPaymentRequestTypeEntity</a>|
|[Workflow](#Workflow)||<a href="CFMPaymentRequestTypeEntity.md" target="_blank">RCashFlowManagement/CFMPaymentRequestTypeEntity</a>|
|[BackingTable_CFMPaymentRequestTypeRelationshipId](#BackingTable_CFMPaymentRequestTypeRelationshipId)||<a href="CFMPaymentRequestTypeEntity.md" target="_blank">RCashFlowManagement/CFMPaymentRequestTypeEntity</a>|

### <a href=#Description name="Description">Description</a>

First included in: RCashFlowManagement/CFMPaymentRequestTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Direction name="Direction">Direction</a>

First included in: RCashFlowManagement/CFMPaymentRequestTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Direction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentPriority name="PaymentPriority">PaymentPriority</a>

First included in: RCashFlowManagement/CFMPaymentRequestTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentPriority attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentRequestType name="PaymentRequestType">PaymentRequestType</a>

First included in: RCashFlowManagement/CFMPaymentRequestTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentRequestType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PriorityCode name="PriorityCode">PriorityCode</a>

First included in: RCashFlowManagement/CFMPaymentRequestTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PriorityCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Workflow name="Workflow">Workflow</a>

First included in: RCashFlowManagement/CFMPaymentRequestTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Workflow attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_CFMPaymentRequestTypeRelationshipId name="BackingTable_CFMPaymentRequestTypeRelationshipId">BackingTable_CFMPaymentRequestTypeRelationshipId</a>

First included in: RCashFlowManagement/CFMPaymentRequestTypeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_CFMPaymentRequestTypeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/RCashFlowManagement/Group/CFMPaymentRequestType.md" target="_blank">/core/erp/Tables/Finance/RCashFlowManagement/Group/CFMPaymentRequestType.cdm.json/CFMPaymentRequestType</a></td><td><a href="../../../Tables/Finance/RCashFlowManagement/Group/CFMPaymentRequestType.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
