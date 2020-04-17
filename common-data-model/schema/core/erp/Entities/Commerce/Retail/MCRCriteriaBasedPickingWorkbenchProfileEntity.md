---
title: MCRCriteriaBasedPickingWorkbenchProfileEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# MCRCriteriaBasedPickingWorkbenchProfileEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Entities/Commerce/Retail/MCRCriteriaBasedPickingWorkbenchProfileEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[SalesOrderCustomerGroupIdCriterion](#SalesOrderCustomerGroupIdCriterion)||<a href="MCRCriteriaBasedPickingWorkbenchProfileEntity.md" target="_blank">Retail/MCRCriteriaBasedPickingWorkbenchProfileEntity</a>|
|[SalesOrderLineDeliveryModeCodeCriterion](#SalesOrderLineDeliveryModeCodeCriterion)||<a href="MCRCriteriaBasedPickingWorkbenchProfileEntity.md" target="_blank">Retail/MCRCriteriaBasedPickingWorkbenchProfileEntity</a>|
|[SalesOrderLineShippingSiteIdCriterion](#SalesOrderLineShippingSiteIdCriterion)||<a href="MCRCriteriaBasedPickingWorkbenchProfileEntity.md" target="_blank">Retail/MCRCriteriaBasedPickingWorkbenchProfileEntity</a>|
|[SalesOrderLineItemNumberQueryCriteria](#SalesOrderLineItemNumberQueryCriteria)||<a href="MCRCriteriaBasedPickingWorkbenchProfileEntity.md" target="_blank">Retail/MCRCriteriaBasedPickingWorkbenchProfileEntity</a>|
|[SalesOrderLineShipDateOffsetDaysCriterion](#SalesOrderLineShipDateOffsetDaysCriterion)||<a href="MCRCriteriaBasedPickingWorkbenchProfileEntity.md" target="_blank">Retail/MCRCriteriaBasedPickingWorkbenchProfileEntity</a>|
|[MaximumSalesOrderLinesPerSessionCriterion](#MaximumSalesOrderLinesPerSessionCriterion)||<a href="MCRCriteriaBasedPickingWorkbenchProfileEntity.md" target="_blank">Retail/MCRCriteriaBasedPickingWorkbenchProfileEntity</a>|
|[MaximumSalesOrdersPerSessionCriterion](#MaximumSalesOrdersPerSessionCriterion)||<a href="MCRCriteriaBasedPickingWorkbenchProfileEntity.md" target="_blank">Retail/MCRCriteriaBasedPickingWorkbenchProfileEntity</a>|
|[SalesOrderLineExpediteCodeCriterion](#SalesOrderLineExpediteCodeCriterion)||<a href="MCRCriteriaBasedPickingWorkbenchProfileEntity.md" target="_blank">Retail/MCRCriteriaBasedPickingWorkbenchProfileEntity</a>|
|[AreOnlySingleLineSalesOrdersSelectedCriterion](#AreOnlySingleLineSalesOrdersSelectedCriterion)||<a href="MCRCriteriaBasedPickingWorkbenchProfileEntity.md" target="_blank">Retail/MCRCriteriaBasedPickingWorkbenchProfileEntity</a>|
|[ProfileDescription](#ProfileDescription)||<a href="MCRCriteriaBasedPickingWorkbenchProfileEntity.md" target="_blank">Retail/MCRCriteriaBasedPickingWorkbenchProfileEntity</a>|
|[ProfileNumber](#ProfileNumber)||<a href="MCRCriteriaBasedPickingWorkbenchProfileEntity.md" target="_blank">Retail/MCRCriteriaBasedPickingWorkbenchProfileEntity</a>|
|[UpperSalesOrderFulfillmentPriorityLimitCriterion](#UpperSalesOrderFulfillmentPriorityLimitCriterion)||<a href="MCRCriteriaBasedPickingWorkbenchProfileEntity.md" target="_blank">Retail/MCRCriteriaBasedPickingWorkbenchProfileEntity</a>|
|[LowerSalesOrderFulfillmentPriorityLimitCriterion](#LowerSalesOrderFulfillmentPriorityLimitCriterion)||<a href="MCRCriteriaBasedPickingWorkbenchProfileEntity.md" target="_blank">Retail/MCRCriteriaBasedPickingWorkbenchProfileEntity</a>|
|[SalesOrderPaymentMethodNumberCriterion](#SalesOrderPaymentMethodNumberCriterion)||<a href="MCRCriteriaBasedPickingWorkbenchProfileEntity.md" target="_blank">Retail/MCRCriteriaBasedPickingWorkbenchProfileEntity</a>|
|[SalesOrderLineShippingWarehouseIdCriterion](#SalesOrderLineShippingWarehouseIdCriterion)||<a href="MCRCriteriaBasedPickingWorkbenchProfileEntity.md" target="_blank">Retail/MCRCriteriaBasedPickingWorkbenchProfileEntity</a>|
|[BackingTable_MCRPickingWorkbenchProfileRelationshipId](#BackingTable_MCRPickingWorkbenchProfileRelationshipId)||<a href="MCRCriteriaBasedPickingWorkbenchProfileEntity.md" target="_blank">Retail/MCRCriteriaBasedPickingWorkbenchProfileEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="MCRCriteriaBasedPickingWorkbenchProfileEntity.md" target="_blank">Retail/MCRCriteriaBasedPickingWorkbenchProfileEntity</a>|

### <a href=#SalesOrderCustomerGroupIdCriterion name="SalesOrderCustomerGroupIdCriterion">SalesOrderCustomerGroupIdCriterion</a>

First included in: Retail/MCRCriteriaBasedPickingWorkbenchProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesOrderCustomerGroupIdCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesOrderLineDeliveryModeCodeCriterion name="SalesOrderLineDeliveryModeCodeCriterion">SalesOrderLineDeliveryModeCodeCriterion</a>

First included in: Retail/MCRCriteriaBasedPickingWorkbenchProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesOrderLineDeliveryModeCodeCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesOrderLineShippingSiteIdCriterion name="SalesOrderLineShippingSiteIdCriterion">SalesOrderLineShippingSiteIdCriterion</a>

First included in: Retail/MCRCriteriaBasedPickingWorkbenchProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesOrderLineShippingSiteIdCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesOrderLineItemNumberQueryCriteria name="SalesOrderLineItemNumberQueryCriteria">SalesOrderLineItemNumberQueryCriteria</a>

First included in: Retail/MCRCriteriaBasedPickingWorkbenchProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesOrderLineItemNumberQueryCriteria attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesOrderLineShipDateOffsetDaysCriterion name="SalesOrderLineShipDateOffsetDaysCriterion">SalesOrderLineShipDateOffsetDaysCriterion</a>

First included in: Retail/MCRCriteriaBasedPickingWorkbenchProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesOrderLineShipDateOffsetDaysCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumSalesOrderLinesPerSessionCriterion name="MaximumSalesOrderLinesPerSessionCriterion">MaximumSalesOrderLinesPerSessionCriterion</a>

First included in: Retail/MCRCriteriaBasedPickingWorkbenchProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumSalesOrderLinesPerSessionCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumSalesOrdersPerSessionCriterion name="MaximumSalesOrdersPerSessionCriterion">MaximumSalesOrdersPerSessionCriterion</a>

First included in: Retail/MCRCriteriaBasedPickingWorkbenchProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumSalesOrdersPerSessionCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesOrderLineExpediteCodeCriterion name="SalesOrderLineExpediteCodeCriterion">SalesOrderLineExpediteCodeCriterion</a>

First included in: Retail/MCRCriteriaBasedPickingWorkbenchProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesOrderLineExpediteCodeCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreOnlySingleLineSalesOrdersSelectedCriterion name="AreOnlySingleLineSalesOrdersSelectedCriterion">AreOnlySingleLineSalesOrdersSelectedCriterion</a>

First included in: Retail/MCRCriteriaBasedPickingWorkbenchProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreOnlySingleLineSalesOrdersSelectedCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProfileDescription name="ProfileDescription">ProfileDescription</a>

First included in: Retail/MCRCriteriaBasedPickingWorkbenchProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProfileDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProfileNumber name="ProfileNumber">ProfileNumber</a>

First included in: Retail/MCRCriteriaBasedPickingWorkbenchProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProfileNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UpperSalesOrderFulfillmentPriorityLimitCriterion name="UpperSalesOrderFulfillmentPriorityLimitCriterion">UpperSalesOrderFulfillmentPriorityLimitCriterion</a>

First included in: Retail/MCRCriteriaBasedPickingWorkbenchProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UpperSalesOrderFulfillmentPriorityLimitCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LowerSalesOrderFulfillmentPriorityLimitCriterion name="LowerSalesOrderFulfillmentPriorityLimitCriterion">LowerSalesOrderFulfillmentPriorityLimitCriterion</a>

First included in: Retail/MCRCriteriaBasedPickingWorkbenchProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LowerSalesOrderFulfillmentPriorityLimitCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesOrderPaymentMethodNumberCriterion name="SalesOrderPaymentMethodNumberCriterion">SalesOrderPaymentMethodNumberCriterion</a>

First included in: Retail/MCRCriteriaBasedPickingWorkbenchProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesOrderPaymentMethodNumberCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesOrderLineShippingWarehouseIdCriterion name="SalesOrderLineShippingWarehouseIdCriterion">SalesOrderLineShippingWarehouseIdCriterion</a>

First included in: Retail/MCRCriteriaBasedPickingWorkbenchProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesOrderLineShippingWarehouseIdCriterion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_MCRPickingWorkbenchProfileRelationshipId name="BackingTable_MCRPickingWorkbenchProfileRelationshipId">BackingTable_MCRPickingWorkbenchProfileRelationshipId</a>

First included in: Retail/MCRCriteriaBasedPickingWorkbenchProfileEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_MCRPickingWorkbenchProfileRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Inventory/Main/MCRPickingWorkbenchProfile.md" target="_blank">/core/erp/Tables/SupplyChain/Inventory/Main/MCRPickingWorkbenchProfile.cdm.json/MCRPickingWorkbenchProfile</a></td><td><a href="../../../Tables/SupplyChain/Inventory/Main/MCRPickingWorkbenchProfile.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: Retail/MCRCriteriaBasedPickingWorkbenchProfileEntity (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/erp/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
