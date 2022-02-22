---
title: PurchPurchaseRequisitionBusinessJustificationEntity in ProcurementAndSourcing - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Purchase requisition business justifications in ProcurementAndSourcing(PurchPurchaseRequisitionBusinessJustificationEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/PurchPurchaseRequisitionBusinessJustificationEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchase requisition business justifications</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[PurchaseRequisitionBusinessJustificationCode](#PurchaseRequisitionBusinessJustificationCode)||<a href="PurchPurchaseRequisitionBusinessJustificationEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRequisitionBusinessJustificationEntity</a>|
|[JustificationDescription](#JustificationDescription)||<a href="PurchPurchaseRequisitionBusinessJustificationEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRequisitionBusinessJustificationEntity</a>|
|[BackingTable_PurchReqBusinessJustificationCodesRelationshipId](#BackingTable_PurchReqBusinessJustificationCodesRelationshipId)||<a href="PurchPurchaseRequisitionBusinessJustificationEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRequisitionBusinessJustificationEntity</a>|

### <a href=#PurchaseRequisitionBusinessJustificationCode name="PurchaseRequisitionBusinessJustificationCode">PurchaseRequisitionBusinessJustificationCode</a>

First included in: ProcurementAndSourcing/PurchPurchaseRequisitionBusinessJustificationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseRequisitionBusinessJustificationCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JustificationDescription name="JustificationDescription">JustificationDescription</a>

First included in: ProcurementAndSourcing/PurchPurchaseRequisitionBusinessJustificationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JustificationDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_PurchReqBusinessJustificationCodesRelationshipId name="BackingTable_PurchReqBusinessJustificationCodesRelationshipId">BackingTable_PurchReqBusinessJustificationCodesRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseRequisitionBusinessJustificationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PurchReqBusinessJustificationCodesRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Reference/PurchReqBusinessJustificationCodes.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Reference/PurchReqBusinessJustificationCodes.cdm.json/PurchReqBusinessJustificationCodes</a></td><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Reference/PurchReqBusinessJustificationCodes.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
