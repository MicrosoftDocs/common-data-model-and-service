---
title: PurchPurchaseRequisitionExpenditureReviewerLegalEntityConfigurationEntity in ProcurementAndSourcing - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Purchase requisition expenditure reviewer legal entity configuration in ProcurementAndSourcing(PurchPurchaseRequisitionExpenditureReviewerLegalEntityConfigurationEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/PurchPurchaseRequisitionExpenditureReviewerLegalEntityConfigurationEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchase requisition expenditure reviewer legal entity configuration</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[IsProjectControllerExpenditureReviewer](#IsProjectControllerExpenditureReviewer)||<a href="PurchPurchaseRequisitionExpenditureReviewerLegalEntityConfigurationEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRequisitionExpenditureReviewerLegalEntityConfigurationEntity</a>|
|[IsProjectManagerExpenditureReviewer](#IsProjectManagerExpenditureReviewer)||<a href="PurchPurchaseRequisitionExpenditureReviewerLegalEntityConfigurationEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRequisitionExpenditureReviewerLegalEntityConfigurationEntity</a>|
|[IsProjectSalesManagerExpenditureReviewer](#IsProjectSalesManagerExpenditureReviewer)||<a href="PurchPurchaseRequisitionExpenditureReviewerLegalEntityConfigurationEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRequisitionExpenditureReviewerLegalEntityConfigurationEntity</a>|
|[LegalEntityId](#LegalEntityId)||<a href="PurchPurchaseRequisitionExpenditureReviewerLegalEntityConfigurationEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRequisitionExpenditureReviewerLegalEntityConfigurationEntity</a>|
|[PurchaseRequisitionExpenditureReviewerConfigurationName](#PurchaseRequisitionExpenditureReviewerConfigurationName)||<a href="PurchPurchaseRequisitionExpenditureReviewerLegalEntityConfigurationEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRequisitionExpenditureReviewerLegalEntityConfigurationEntity</a>|
|[BackingTable_WorkflowParticipantExpenTokenLineRelationshipId](#BackingTable_WorkflowParticipantExpenTokenLineRelationshipId)||<a href="PurchPurchaseRequisitionExpenditureReviewerLegalEntityConfigurationEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRequisitionExpenditureReviewerLegalEntityConfigurationEntity</a>|

### <a href=#IsProjectControllerExpenditureReviewer name="IsProjectControllerExpenditureReviewer">IsProjectControllerExpenditureReviewer</a>

First included in: ProcurementAndSourcing/PurchPurchaseRequisitionExpenditureReviewerLegalEntityConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProjectControllerExpenditureReviewer attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProjectManagerExpenditureReviewer name="IsProjectManagerExpenditureReviewer">IsProjectManagerExpenditureReviewer</a>

First included in: ProcurementAndSourcing/PurchPurchaseRequisitionExpenditureReviewerLegalEntityConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProjectManagerExpenditureReviewer attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProjectSalesManagerExpenditureReviewer name="IsProjectSalesManagerExpenditureReviewer">IsProjectSalesManagerExpenditureReviewer</a>

First included in: ProcurementAndSourcing/PurchPurchaseRequisitionExpenditureReviewerLegalEntityConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProjectSalesManagerExpenditureReviewer attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LegalEntityId name="LegalEntityId">LegalEntityId</a>

First included in: ProcurementAndSourcing/PurchPurchaseRequisitionExpenditureReviewerLegalEntityConfigurationEntity (this entity)  

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

### <a href=#PurchaseRequisitionExpenditureReviewerConfigurationName name="PurchaseRequisitionExpenditureReviewerConfigurationName">PurchaseRequisitionExpenditureReviewerConfigurationName</a>

First included in: ProcurementAndSourcing/PurchPurchaseRequisitionExpenditureReviewerLegalEntityConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchaseRequisitionExpenditureReviewerConfigurationName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_WorkflowParticipantExpenTokenLineRelationshipId name="BackingTable_WorkflowParticipantExpenTokenLineRelationshipId">BackingTable_WorkflowParticipantExpenTokenLineRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseRequisitionExpenditureReviewerLegalEntityConfigurationEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_WorkflowParticipantExpenTokenLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Reference/WorkflowParticipantExpenTokenLine.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Reference/WorkflowParticipantExpenTokenLine.cdm.json/WorkflowParticipantExpenTokenLine</a></td><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Reference/WorkflowParticipantExpenTokenLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
