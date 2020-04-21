---
title: MCRPickingWorkbenchSession - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# MCRPickingWorkbenchSession

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/Inventory/Transaction/MCRPickingWorkbenchSession.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[MCRPickingWorkbenchSession/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="MCRPickingWorkbenchSession.md" target="_blank">Transaction/MCRPickingWorkbenchSession</a>|
|[createdFromBatch](#createdFromBatch)||<a href="MCRPickingWorkbenchSession.md" target="_blank">Transaction/MCRPickingWorkbenchSession</a>|
|[CustGroupId](#CustGroupId)||<a href="MCRPickingWorkbenchSession.md" target="_blank">Transaction/MCRPickingWorkbenchSession</a>|
|[Description](#Description)||<a href="MCRPickingWorkbenchSession.md" target="_blank">Transaction/MCRPickingWorkbenchSession</a>|
|[DlvDate](#DlvDate)||<a href="MCRPickingWorkbenchSession.md" target="_blank">Transaction/MCRPickingWorkbenchSession</a>|
|[DlvMode](#DlvMode)||<a href="MCRPickingWorkbenchSession.md" target="_blank">Transaction/MCRPickingWorkbenchSession</a>|
|[InitProfileId](#InitProfileId)||<a href="MCRPickingWorkbenchSession.md" target="_blank">Transaction/MCRPickingWorkbenchSession</a>|
|[InventSiteId](#InventSiteId)||<a href="MCRPickingWorkbenchSession.md" target="_blank">Transaction/MCRPickingWorkbenchSession</a>|
|[ItemIdQuery](#ItemIdQuery)||<a href="MCRPickingWorkbenchSession.md" target="_blank">Transaction/MCRPickingWorkbenchSession</a>|
|[MaxLinesPerOrder](#MaxLinesPerOrder)||<a href="MCRPickingWorkbenchSession.md" target="_blank">Transaction/MCRPickingWorkbenchSession</a>|
|[MaxOrders](#MaxOrders)||<a href="MCRPickingWorkbenchSession.md" target="_blank">Transaction/MCRPickingWorkbenchSession</a>|
|[MCRExpedite](#MCRExpedite)||<a href="MCRPickingWorkbenchSession.md" target="_blank">Transaction/MCRPickingWorkbenchSession</a>|
|[MCRPickingQuery](#MCRPickingQuery)||<a href="MCRPickingWorkbenchSession.md" target="_blank">Transaction/MCRPickingWorkbenchSession</a>|
|[onlySingleLineOrders](#onlySingleLineOrders)||<a href="MCRPickingWorkbenchSession.md" target="_blank">Transaction/MCRPickingWorkbenchSession</a>|
|[Prompt](#Prompt)||<a href="MCRPickingWorkbenchSession.md" target="_blank">Transaction/MCRPickingWorkbenchSession</a>|
|[PromptForContinuityItem](#PromptForContinuityItem)||<a href="MCRPickingWorkbenchSession.md" target="_blank">Transaction/MCRPickingWorkbenchSession</a>|
|[PromptForItems](#PromptForItems)||<a href="MCRPickingWorkbenchSession.md" target="_blank">Transaction/MCRPickingWorkbenchSession</a>|
|[PromptForSalesIds](#PromptForSalesIds)||<a href="MCRPickingWorkbenchSession.md" target="_blank">Transaction/MCRPickingWorkbenchSession</a>|
|[SessionId](#SessionId)||<a href="MCRPickingWorkbenchSession.md" target="_blank">Transaction/MCRPickingWorkbenchSession</a>|
|[SessionStatus](#SessionStatus)||<a href="MCRPickingWorkbenchSession.md" target="_blank">Transaction/MCRPickingWorkbenchSession</a>|
|[SOAllocHighPriority](#SOAllocHighPriority)||<a href="MCRPickingWorkbenchSession.md" target="_blank">Transaction/MCRPickingWorkbenchSession</a>|
|[SOAllocLowPriority](#SOAllocLowPriority)||<a href="MCRPickingWorkbenchSession.md" target="_blank">Transaction/MCRPickingWorkbenchSession</a>|
|[TenderTypeId](#TenderTypeId)||<a href="MCRPickingWorkbenchSession.md" target="_blank">Transaction/MCRPickingWorkbenchSession</a>|
|[Warehouse](#Warehouse)||<a href="MCRPickingWorkbenchSession.md" target="_blank">Transaction/MCRPickingWorkbenchSession</a>|
|[DataAreaId](#DataAreaId)||<a href="MCRPickingWorkbenchSession.md" target="_blank">Transaction/MCRPickingWorkbenchSession</a>|
|[Relationship_CustGroupRelationshipId](#Relationship_CustGroupRelationshipId)||<a href="MCRPickingWorkbenchSession.md" target="_blank">Transaction/MCRPickingWorkbenchSession</a>|
|[Relationship_DlvModeRelationshipId](#Relationship_DlvModeRelationshipId)||<a href="MCRPickingWorkbenchSession.md" target="_blank">Transaction/MCRPickingWorkbenchSession</a>|
|[Relationship_InventLocationRelationshipId](#Relationship_InventLocationRelationshipId)||<a href="MCRPickingWorkbenchSession.md" target="_blank">Transaction/MCRPickingWorkbenchSession</a>|
|[Relationship_InventSiteRelationshipId](#Relationship_InventSiteRelationshipId)||<a href="MCRPickingWorkbenchSession.md" target="_blank">Transaction/MCRPickingWorkbenchSession</a>|
|[Relationship_MCRPickingWorkbenchProfileRelationshipId](#Relationship_MCRPickingWorkbenchProfileRelationshipId)||<a href="MCRPickingWorkbenchSession.md" target="_blank">Transaction/MCRPickingWorkbenchSession</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="MCRPickingWorkbenchSession.md" target="_blank">Transaction/MCRPickingWorkbenchSession</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/MCRPickingWorkbenchSession (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[MCRPickingWorkbenchSession/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#createdFromBatch name="createdFromBatch">createdFromBatch</a>

First included in: Transaction/MCRPickingWorkbenchSession (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the createdFromBatch attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CustGroupId name="CustGroupId">CustGroupId</a>

First included in: Transaction/MCRPickingWorkbenchSession (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: Transaction/MCRPickingWorkbenchSession (this entity)  

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

### <a href=#DlvDate name="DlvDate">DlvDate</a>

First included in: Transaction/MCRPickingWorkbenchSession (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DlvDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#DlvMode name="DlvMode">DlvMode</a>

First included in: Transaction/MCRPickingWorkbenchSession (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DlvMode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InitProfileId name="InitProfileId">InitProfileId</a>

First included in: Transaction/MCRPickingWorkbenchSession (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InitProfileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InventSiteId name="InventSiteId">InventSiteId</a>

First included in: Transaction/MCRPickingWorkbenchSession (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventSiteId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemIdQuery name="ItemIdQuery">ItemIdQuery</a>

First included in: Transaction/MCRPickingWorkbenchSession (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemIdQuery attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaxLinesPerOrder name="MaxLinesPerOrder">MaxLinesPerOrder</a>

First included in: Transaction/MCRPickingWorkbenchSession (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxLinesPerOrder attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MaxOrders name="MaxOrders">MaxOrders</a>

First included in: Transaction/MCRPickingWorkbenchSession (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxOrders attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#MCRExpedite name="MCRExpedite">MCRExpedite</a>

First included in: Transaction/MCRPickingWorkbenchSession (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRExpedite attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MCRPickingQuery name="MCRPickingQuery">MCRPickingQuery</a>

First included in: Transaction/MCRPickingWorkbenchSession (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MCRPickingQuery attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#onlySingleLineOrders name="onlySingleLineOrders">onlySingleLineOrders</a>

First included in: Transaction/MCRPickingWorkbenchSession (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the onlySingleLineOrders attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Prompt name="Prompt">Prompt</a>

First included in: Transaction/MCRPickingWorkbenchSession (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Prompt attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PromptForContinuityItem name="PromptForContinuityItem">PromptForContinuityItem</a>

First included in: Transaction/MCRPickingWorkbenchSession (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PromptForContinuityItem attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PromptForItems name="PromptForItems">PromptForItems</a>

First included in: Transaction/MCRPickingWorkbenchSession (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PromptForItems attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PromptForSalesIds name="PromptForSalesIds">PromptForSalesIds</a>

First included in: Transaction/MCRPickingWorkbenchSession (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PromptForSalesIds attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SessionId name="SessionId">SessionId</a>

First included in: Transaction/MCRPickingWorkbenchSession (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SessionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SessionStatus name="SessionStatus">SessionStatus</a>

First included in: Transaction/MCRPickingWorkbenchSession (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SessionStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SOAllocHighPriority name="SOAllocHighPriority">SOAllocHighPriority</a>

First included in: Transaction/MCRPickingWorkbenchSession (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SOAllocHighPriority attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SOAllocLowPriority name="SOAllocLowPriority">SOAllocLowPriority</a>

First included in: Transaction/MCRPickingWorkbenchSession (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SOAllocLowPriority attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TenderTypeId name="TenderTypeId">TenderTypeId</a>

First included in: Transaction/MCRPickingWorkbenchSession (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TenderTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Warehouse name="Warehouse">Warehouse</a>

First included in: Transaction/MCRPickingWorkbenchSession (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Warehouse attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/MCRPickingWorkbenchSession (this entity)  

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

### <a href=#Relationship_CustGroupRelationshipId name="Relationship_CustGroupRelationshipId">Relationship_CustGroupRelationshipId</a>

First included in: Transaction/MCRPickingWorkbenchSession (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/AccountsReceivable/Group/CustGroup.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Group/CustGroup.cdm.json/CustGroup</a></td><td><a href="../../../Finance/AccountsReceivable/Group/CustGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DlvModeRelationshipId name="Relationship_DlvModeRelationshipId">Relationship_DlvModeRelationshipId</a>

First included in: Transaction/MCRPickingWorkbenchSession (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DlvModeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../SalesAndMarketing/Group/DlvMode.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Group/DlvMode.cdm.json/DlvMode</a></td><td><a href="../../SalesAndMarketing/Group/DlvMode.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventLocationRelationshipId name="Relationship_InventLocationRelationshipId">Relationship_InventLocationRelationshipId</a>

First included in: Transaction/MCRPickingWorkbenchSession (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventLocationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/InventLocation.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/InventLocation.cdm.json/InventLocation</a></td><td><a href="../Group/InventLocation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventSiteRelationshipId name="Relationship_InventSiteRelationshipId">Relationship_InventSiteRelationshipId</a>

First included in: Transaction/MCRPickingWorkbenchSession (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventSiteRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/InventSite.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/InventSite.cdm.json/InventSite</a></td><td><a href="../Group/InventSite.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_MCRPickingWorkbenchProfileRelationshipId name="Relationship_MCRPickingWorkbenchProfileRelationshipId">Relationship_MCRPickingWorkbenchProfileRelationshipId</a>

First included in: Transaction/MCRPickingWorkbenchSession (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MCRPickingWorkbenchProfileRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/MCRPickingWorkbenchProfile.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Main/MCRPickingWorkbenchProfile.cdm.json/MCRPickingWorkbenchProfile</a></td><td><a href="../Main/MCRPickingWorkbenchProfile.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Transaction/MCRPickingWorkbenchSession (this entity)  

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
