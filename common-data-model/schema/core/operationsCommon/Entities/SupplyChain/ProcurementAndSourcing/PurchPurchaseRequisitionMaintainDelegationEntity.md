---
title: PurchPurchaseRequisitionMaintainDelegationEntity in ProcurementAndSourcing - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/7/2020
ms.author: nebanfic
---

# Purchase requisition maintenance delegations in ProcurementAndSourcing

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/PurchPurchaseRequisitionMaintainDelegationEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchase requisition maintenance delegations</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[Originator](#Originator)||<a href="PurchPurchaseRequisitionMaintainDelegationEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRequisitionMaintainDelegationEntity</a>|
|[Requisitioner](#Requisitioner)||<a href="PurchPurchaseRequisitionMaintainDelegationEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRequisitionMaintainDelegationEntity</a>|
|[PreparerPersonnelNumber](#PreparerPersonnelNumber)||<a href="PurchPurchaseRequisitionMaintainDelegationEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRequisitionMaintainDelegationEntity</a>|
|[RequisitionerPersonnelNumber](#RequisitionerPersonnelNumber)||<a href="PurchPurchaseRequisitionMaintainDelegationEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRequisitionMaintainDelegationEntity</a>|
|[AuthorizationLevel](#AuthorizationLevel)||<a href="PurchPurchaseRequisitionMaintainDelegationEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRequisitionMaintainDelegationEntity</a>|
|[ValidFrom](#ValidFrom)||<a href="PurchPurchaseRequisitionMaintainDelegationEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRequisitionMaintainDelegationEntity</a>|
|[ValidTo](#ValidTo)||<a href="PurchPurchaseRequisitionMaintainDelegationEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRequisitionMaintainDelegationEntity</a>|
|[HasAdministratorGrantedPermission](#HasAdministratorGrantedPermission)||<a href="PurchPurchaseRequisitionMaintainDelegationEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRequisitionMaintainDelegationEntity</a>|
|[BackingTable_PurchReqAuthorizationOriginationRelationshipId](#BackingTable_PurchReqAuthorizationOriginationRelationshipId)||<a href="PurchPurchaseRequisitionMaintainDelegationEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRequisitionMaintainDelegationEntity</a>|

### <a href=#Originator name="Originator">Originator</a>

First included in: ProcurementAndSourcing/PurchPurchaseRequisitionMaintainDelegationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Originator attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Requisitioner name="Requisitioner">Requisitioner</a>

First included in: ProcurementAndSourcing/PurchPurchaseRequisitionMaintainDelegationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Requisitioner attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PreparerPersonnelNumber name="PreparerPersonnelNumber">PreparerPersonnelNumber</a>

First included in: ProcurementAndSourcing/PurchPurchaseRequisitionMaintainDelegationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PreparerPersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequisitionerPersonnelNumber name="RequisitionerPersonnelNumber">RequisitionerPersonnelNumber</a>

First included in: ProcurementAndSourcing/PurchPurchaseRequisitionMaintainDelegationEntity (this entity)  

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

### <a href=#AuthorizationLevel name="AuthorizationLevel">AuthorizationLevel</a>

First included in: ProcurementAndSourcing/PurchPurchaseRequisitionMaintainDelegationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AuthorizationLevel attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidFrom name="ValidFrom">ValidFrom</a>

First included in: ProcurementAndSourcing/PurchPurchaseRequisitionMaintainDelegationEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseRequisitionMaintainDelegationEntity (this entity)  

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

### <a href=#HasAdministratorGrantedPermission name="HasAdministratorGrantedPermission">HasAdministratorGrantedPermission</a>

First included in: ProcurementAndSourcing/PurchPurchaseRequisitionMaintainDelegationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HasAdministratorGrantedPermission attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_PurchReqAuthorizationOriginationRelationshipId name="BackingTable_PurchReqAuthorizationOriginationRelationshipId">BackingTable_PurchReqAuthorizationOriginationRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseRequisitionMaintainDelegationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PurchReqAuthorizationOriginationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Main/PurchReqAuthorizationOrigination.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Main/PurchReqAuthorizationOrigination.cdm.json/PurchReqAuthorizationOrigination</a></td><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Main/PurchReqAuthorizationOrigination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
