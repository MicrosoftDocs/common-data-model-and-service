---
title: PurchPurchaseRequisitionReplenishmentControlPolicyRuleEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 6/30/2020
ms.author: nebanfic
---

# Purchase requisition replenishment control policies

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/PurchPurchaseRequisitionReplenishmentControlPolicyRuleEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchase requisition replenishment control policies</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[Policy](#Policy)||<a href="PurchPurchaseRequisitionReplenishmentControlPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRequisitionReplenishmentControlPolicyRuleEntity</a>|
|[PolicyRuleType](#PolicyRuleType)||<a href="PurchPurchaseRequisitionReplenishmentControlPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRequisitionReplenishmentControlPolicyRuleEntity</a>|
|[ValidFrom](#ValidFrom)||<a href="PurchPurchaseRequisitionReplenishmentControlPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRequisitionReplenishmentControlPolicyRuleEntity</a>|
|[ValidTo](#ValidTo)||<a href="PurchPurchaseRequisitionReplenishmentControlPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRequisitionReplenishmentControlPolicyRuleEntity</a>|
|[IsRequestedDateDefaultAccountingDate](#IsRequestedDateDefaultAccountingDate)||<a href="PurchPurchaseRequisitionReplenishmentControlPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRequisitionReplenishmentControlPolicyRuleEntity</a>|
|[PurchasingPolicyName](#PurchasingPolicyName)||<a href="PurchPurchaseRequisitionReplenishmentControlPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRequisitionReplenishmentControlPolicyRuleEntity</a>|
|[PolicyRuleName](#PolicyRuleName)||<a href="PurchPurchaseRequisitionReplenishmentControlPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRequisitionReplenishmentControlPolicyRuleEntity</a>|
|[FieldId](#FieldId)||<a href="PurchPurchaseRequisitionReplenishmentControlPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRequisitionReplenishmentControlPolicyRuleEntity</a>|
|[WorkflowFieldExpressionId](#WorkflowFieldExpressionId)||<a href="PurchPurchaseRequisitionReplenishmentControlPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRequisitionReplenishmentControlPolicyRuleEntity</a>|
|[WorkflowFieldRequirementRule](#WorkflowFieldRequirementRule)||<a href="PurchPurchaseRequisitionReplenishmentControlPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRequisitionReplenishmentControlPolicyRuleEntity</a>|
|[RequisitionReplenishControlRule](#RequisitionReplenishControlRule)||<a href="PurchPurchaseRequisitionReplenishmentControlPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRequisitionReplenishmentControlPolicyRuleEntity</a>|
|[RequisitionReplenishControlSubmsnParam](#RequisitionReplenishControlSubmsnParam)||<a href="PurchPurchaseRequisitionReplenishmentControlPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRequisitionReplenishmentControlPolicyRuleEntity</a>|
|[WorkflowFieldName](#WorkflowFieldName)||<a href="PurchPurchaseRequisitionReplenishmentControlPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRequisitionReplenishmentControlPolicyRuleEntity</a>|
|[BackingTable_RequisitionReplenishControlSubmsnParamRelationshipId](#BackingTable_RequisitionReplenishControlSubmsnParamRelationshipId)||<a href="PurchPurchaseRequisitionReplenishmentControlPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRequisitionReplenishmentControlPolicyRuleEntity</a>|

### <a href=#Policy name="Policy">Policy</a>

First included in: ProcurementAndSourcing/PurchPurchaseRequisitionReplenishmentControlPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Policy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PolicyRuleType name="PolicyRuleType">PolicyRuleType</a>

First included in: ProcurementAndSourcing/PurchPurchaseRequisitionReplenishmentControlPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PolicyRuleType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidFrom name="ValidFrom">ValidFrom</a>

First included in: ProcurementAndSourcing/PurchPurchaseRequisitionReplenishmentControlPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidTo name="ValidTo">ValidTo</a>

First included in: ProcurementAndSourcing/PurchPurchaseRequisitionReplenishmentControlPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsRequestedDateDefaultAccountingDate name="IsRequestedDateDefaultAccountingDate">IsRequestedDateDefaultAccountingDate</a>

First included in: ProcurementAndSourcing/PurchPurchaseRequisitionReplenishmentControlPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsRequestedDateDefaultAccountingDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchasingPolicyName name="PurchasingPolicyName">PurchasingPolicyName</a>

First included in: ProcurementAndSourcing/PurchPurchaseRequisitionReplenishmentControlPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchasingPolicyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PolicyRuleName name="PolicyRuleName">PolicyRuleName</a>

First included in: ProcurementAndSourcing/PurchPurchaseRequisitionReplenishmentControlPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PolicyRuleName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FieldId name="FieldId">FieldId</a>

First included in: ProcurementAndSourcing/PurchPurchaseRequisitionReplenishmentControlPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FieldId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkflowFieldExpressionId name="WorkflowFieldExpressionId">WorkflowFieldExpressionId</a>

First included in: ProcurementAndSourcing/PurchPurchaseRequisitionReplenishmentControlPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkflowFieldExpressionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkflowFieldRequirementRule name="WorkflowFieldRequirementRule">WorkflowFieldRequirementRule</a>

First included in: ProcurementAndSourcing/PurchPurchaseRequisitionReplenishmentControlPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkflowFieldRequirementRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequisitionReplenishControlRule name="RequisitionReplenishControlRule">RequisitionReplenishControlRule</a>

First included in: ProcurementAndSourcing/PurchPurchaseRequisitionReplenishmentControlPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequisitionReplenishControlRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequisitionReplenishControlSubmsnParam name="RequisitionReplenishControlSubmsnParam">RequisitionReplenishControlSubmsnParam</a>

First included in: ProcurementAndSourcing/PurchPurchaseRequisitionReplenishmentControlPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequisitionReplenishControlSubmsnParam attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkflowFieldName name="WorkflowFieldName">WorkflowFieldName</a>

First included in: ProcurementAndSourcing/PurchPurchaseRequisitionReplenishmentControlPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkflowFieldName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_RequisitionReplenishControlSubmsnParamRelationshipId name="BackingTable_RequisitionReplenishControlSubmsnParamRelationshipId">BackingTable_RequisitionReplenishControlSubmsnParamRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseRequisitionReplenishmentControlPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RequisitionReplenishControlSubmsnParamRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Parameter/RequisitionReplenishControlSubmsnParam.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Parameter/RequisitionReplenishControlSubmsnParam.cdm.json/RequisitionReplenishControlSubmsnParam</a></td><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Parameter/RequisitionReplenishControlSubmsnParam.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
