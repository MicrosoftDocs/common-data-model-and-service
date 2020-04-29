---
title: PurchPurchaseOrderExpenditureReviewPolicyEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# Purchase order expenditure review policies

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/PurchPurchaseOrderExpenditureReviewPolicyEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchase order expenditure review policies</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[IsProjectControllerExpenditureReviewer](#IsProjectControllerExpenditureReviewer)||<a href="PurchPurchaseOrderExpenditureReviewPolicyEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderExpenditureReviewPolicyEntity</a>|
|[IsProjectManagerExpenditureReviewer](#IsProjectManagerExpenditureReviewer)||<a href="PurchPurchaseOrderExpenditureReviewPolicyEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderExpenditureReviewPolicyEntity</a>|
|[IsProjectSalesManagerExpenditureReviewer](#IsProjectSalesManagerExpenditureReviewer)||<a href="PurchPurchaseOrderExpenditureReviewPolicyEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderExpenditureReviewPolicyEntity</a>|
|[AreOrganizationFinancialDimensionOwnerExpenditureReviewer](#AreOrganizationFinancialDimensionOwnerExpenditureReviewer)||<a href="PurchPurchaseOrderExpenditureReviewPolicyEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderExpenditureReviewPolicyEntity</a>|
|[AreProjectFinancialDimensionOwnerExpenditureReviewer](#AreProjectFinancialDimensionOwnerExpenditureReviewer)||<a href="PurchPurchaseOrderExpenditureReviewPolicyEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderExpenditureReviewPolicyEntity</a>|
|[Token](#Token)||<a href="PurchPurchaseOrderExpenditureReviewPolicyEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderExpenditureReviewPolicyEntity</a>|
|[LegalEntityId](#LegalEntityId)||<a href="PurchPurchaseOrderExpenditureReviewPolicyEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderExpenditureReviewPolicyEntity</a>|
|[PolicyName](#PolicyName)||<a href="PurchPurchaseOrderExpenditureReviewPolicyEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderExpenditureReviewPolicyEntity</a>|
|[AreOrganizationFinancialDimensionOwnerExpenditureReviewerDisplayValue](#AreOrganizationFinancialDimensionOwnerExpenditureReviewerDisplayValue)||<a href="PurchPurchaseOrderExpenditureReviewPolicyEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderExpenditureReviewPolicyEntity</a>|
|[AreProjectFinancialDimensionOwnerExpenditureReviewerDisplayValue](#AreProjectFinancialDimensionOwnerExpenditureReviewerDisplayValue)||<a href="PurchPurchaseOrderExpenditureReviewPolicyEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderExpenditureReviewPolicyEntity</a>|
|[BackingTable_WorkflowParticipantExpenTokenLineRelationshipId](#BackingTable_WorkflowParticipantExpenTokenLineRelationshipId)||<a href="PurchPurchaseOrderExpenditureReviewPolicyEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderExpenditureReviewPolicyEntity</a>|

### <a href=#IsProjectControllerExpenditureReviewer name="IsProjectControllerExpenditureReviewer">IsProjectControllerExpenditureReviewer</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderExpenditureReviewPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProjectControllerExpenditureReviewer attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProjectManagerExpenditureReviewer name="IsProjectManagerExpenditureReviewer">IsProjectManagerExpenditureReviewer</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderExpenditureReviewPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProjectManagerExpenditureReviewer attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsProjectSalesManagerExpenditureReviewer name="IsProjectSalesManagerExpenditureReviewer">IsProjectSalesManagerExpenditureReviewer</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderExpenditureReviewPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsProjectSalesManagerExpenditureReviewer attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreOrganizationFinancialDimensionOwnerExpenditureReviewer name="AreOrganizationFinancialDimensionOwnerExpenditureReviewer">AreOrganizationFinancialDimensionOwnerExpenditureReviewer</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderExpenditureReviewPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreOrganizationFinancialDimensionOwnerExpenditureReviewer attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreProjectFinancialDimensionOwnerExpenditureReviewer name="AreProjectFinancialDimensionOwnerExpenditureReviewer">AreProjectFinancialDimensionOwnerExpenditureReviewer</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderExpenditureReviewPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreProjectFinancialDimensionOwnerExpenditureReviewer attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Token name="Token">Token</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderExpenditureReviewPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Token attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LegalEntityId name="LegalEntityId">LegalEntityId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderExpenditureReviewPolicyEntity (this entity)  

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

### <a href=#PolicyName name="PolicyName">PolicyName</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderExpenditureReviewPolicyEntity (this entity)  

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

### <a href=#AreOrganizationFinancialDimensionOwnerExpenditureReviewerDisplayValue name="AreOrganizationFinancialDimensionOwnerExpenditureReviewerDisplayValue">AreOrganizationFinancialDimensionOwnerExpenditureReviewerDisplayValue</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderExpenditureReviewPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreOrganizationFinancialDimensionOwnerExpenditureReviewerDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AreProjectFinancialDimensionOwnerExpenditureReviewerDisplayValue name="AreProjectFinancialDimensionOwnerExpenditureReviewerDisplayValue">AreProjectFinancialDimensionOwnerExpenditureReviewerDisplayValue</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderExpenditureReviewPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AreProjectFinancialDimensionOwnerExpenditureReviewerDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_WorkflowParticipantExpenTokenLineRelationshipId name="BackingTable_WorkflowParticipantExpenTokenLineRelationshipId">BackingTable_WorkflowParticipantExpenTokenLineRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderExpenditureReviewPolicyEntity (this entity)  

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
