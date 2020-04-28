---
title: PurchPurchaseRequisitionWorkerLegalEntityAuthorizationEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Purchase requisition worker legal entity authorizations

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/PurchPurchaseRequisitionWorkerLegalEntityAuthorizationEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchase requisition worker legal entity authorizations</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[Requisitioner](#Requisitioner)||<a href="PurchPurchaseRequisitionWorkerLegalEntityAuthorizationEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRequisitionWorkerLegalEntityAuthorizationEntity</a>|
|[LegalEntity](#LegalEntity)||<a href="PurchPurchaseRequisitionWorkerLegalEntityAuthorizationEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRequisitionWorkerLegalEntityAuthorizationEntity</a>|
|[RequisitionerPersonnelNumber](#RequisitionerPersonnelNumber)||<a href="PurchPurchaseRequisitionWorkerLegalEntityAuthorizationEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRequisitionWorkerLegalEntityAuthorizationEntity</a>|
|[LegalEntityId](#LegalEntityId)||<a href="PurchPurchaseRequisitionWorkerLegalEntityAuthorizationEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRequisitionWorkerLegalEntityAuthorizationEntity</a>|
|[ValidFrom](#ValidFrom)||<a href="PurchPurchaseRequisitionWorkerLegalEntityAuthorizationEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRequisitionWorkerLegalEntityAuthorizationEntity</a>|
|[ValidTo](#ValidTo)||<a href="PurchPurchaseRequisitionWorkerLegalEntityAuthorizationEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRequisitionWorkerLegalEntityAuthorizationEntity</a>|
|[BackingTable_PurchReqAuthorizationLegalEntityRelationshipId](#BackingTable_PurchReqAuthorizationLegalEntityRelationshipId)||<a href="PurchPurchaseRequisitionWorkerLegalEntityAuthorizationEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRequisitionWorkerLegalEntityAuthorizationEntity</a>|

### <a href=#Requisitioner name="Requisitioner">Requisitioner</a>

First included in: ProcurementAndSourcing/PurchPurchaseRequisitionWorkerLegalEntityAuthorizationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Requisitioner attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LegalEntity name="LegalEntity">LegalEntity</a>

First included in: ProcurementAndSourcing/PurchPurchaseRequisitionWorkerLegalEntityAuthorizationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LegalEntity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequisitionerPersonnelNumber name="RequisitionerPersonnelNumber">RequisitionerPersonnelNumber</a>

First included in: ProcurementAndSourcing/PurchPurchaseRequisitionWorkerLegalEntityAuthorizationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequisitionerPersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LegalEntityId name="LegalEntityId">LegalEntityId</a>

First included in: ProcurementAndSourcing/PurchPurchaseRequisitionWorkerLegalEntityAuthorizationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LegalEntityId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidFrom name="ValidFrom">ValidFrom</a>

First included in: ProcurementAndSourcing/PurchPurchaseRequisitionWorkerLegalEntityAuthorizationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidTo name="ValidTo">ValidTo</a>

First included in: ProcurementAndSourcing/PurchPurchaseRequisitionWorkerLegalEntityAuthorizationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_PurchReqAuthorizationLegalEntityRelationshipId name="BackingTable_PurchReqAuthorizationLegalEntityRelationshipId">BackingTable_PurchReqAuthorizationLegalEntityRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseRequisitionWorkerLegalEntityAuthorizationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PurchReqAuthorizationLegalEntityRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Main/PurchReqAuthorizationLegalEntity.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Main/PurchReqAuthorizationLegalEntity.cdm.json/PurchReqAuthorizationLegalEntity</a></td><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Main/PurchReqAuthorizationLegalEntity.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
