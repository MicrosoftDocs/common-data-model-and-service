---
title: ProcProcurementCategoryPolicyRuleEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# ProcProcurementCategoryPolicyRuleEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/ProcProcurementCategoryPolicyRuleEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[ValidFrom](#ValidFrom)||<a href="ProcProcurementCategoryPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/ProcProcurementCategoryPolicyRuleEntity</a>|
|[ValidTo](#ValidTo)||<a href="ProcProcurementCategoryPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/ProcProcurementCategoryPolicyRuleEntity</a>|
|[ProcurementCategoryName](#ProcurementCategoryName)||<a href="ProcProcurementCategoryPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/ProcProcurementCategoryPolicyRuleEntity</a>|
|[IsReturnedQuantityVerifiedBeforeRecordingReturn](#IsReturnedQuantityVerifiedBeforeRecordingReturn)||<a href="ProcProcurementCategoryPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/ProcProcurementCategoryPolicyRuleEntity</a>|
|[WillPurchaseRequisitionShowQuestionnaires](#WillPurchaseRequisitionShowQuestionnaires)||<a href="ProcProcurementCategoryPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/ProcProcurementCategoryPolicyRuleEntity</a>|
|[IsQuantityVerifiedBeforeRecordingPurchase](#IsQuantityVerifiedBeforeRecordingPurchase)||<a href="ProcProcurementCategoryPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/ProcProcurementCategoryPolicyRuleEntity</a>|
|[CategoryMatchingPolicy](#CategoryMatchingPolicy)||<a href="ProcProcurementCategoryPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/ProcProcurementCategoryPolicyRuleEntity</a>|
|[WillProductReceiptAccruePurchaseExpense](#WillProductReceiptAccruePurchaseExpense)||<a href="ProcProcurementCategoryPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/ProcProcurementCategoryPolicyRuleEntity</a>|
|[VendorSelectionRule](#VendorSelectionRule)||<a href="ProcProcurementCategoryPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/ProcProcurementCategoryPolicyRuleEntity</a>|
|[ProcurementCategory](#ProcurementCategory)||<a href="ProcProcurementCategoryPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/ProcProcurementCategoryPolicyRuleEntity</a>|
|[ProcurementCategoryPolicyRule](#ProcurementCategoryPolicyRule)||<a href="ProcProcurementCategoryPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/ProcProcurementCategoryPolicyRuleEntity</a>|
|[Policy](#Policy)||<a href="ProcProcurementCategoryPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/ProcProcurementCategoryPolicyRuleEntity</a>|
|[PolicyRuleType](#PolicyRuleType)||<a href="ProcProcurementCategoryPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/ProcProcurementCategoryPolicyRuleEntity</a>|
|[InstanceRelationType](#InstanceRelationType)||<a href="ProcProcurementCategoryPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/ProcProcurementCategoryPolicyRuleEntity</a>|
|[PolicyRuleName](#PolicyRuleName)||<a href="ProcProcurementCategoryPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/ProcProcurementCategoryPolicyRuleEntity</a>|
|[PurchasingPolicyName](#PurchasingPolicyName)||<a href="ProcProcurementCategoryPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/ProcProcurementCategoryPolicyRuleEntity</a>|
|[BackingTable_ProcCategoryPolicyParameterRelationshipId](#BackingTable_ProcCategoryPolicyParameterRelationshipId)||<a href="ProcProcurementCategoryPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/ProcProcurementCategoryPolicyRuleEntity</a>|

### <a href=#ValidFrom name="ValidFrom">ValidFrom</a>

First included in: ProcurementAndSourcing/ProcProcurementCategoryPolicyRuleEntity (this entity)  

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

First included in: ProcurementAndSourcing/ProcProcurementCategoryPolicyRuleEntity (this entity)  

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

### <a href=#ProcurementCategoryName name="ProcurementCategoryName">ProcurementCategoryName</a>

First included in: ProcurementAndSourcing/ProcProcurementCategoryPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcurementCategoryName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsReturnedQuantityVerifiedBeforeRecordingReturn name="IsReturnedQuantityVerifiedBeforeRecordingReturn">IsReturnedQuantityVerifiedBeforeRecordingReturn</a>

First included in: ProcurementAndSourcing/ProcProcurementCategoryPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsReturnedQuantityVerifiedBeforeRecordingReturn attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillPurchaseRequisitionShowQuestionnaires name="WillPurchaseRequisitionShowQuestionnaires">WillPurchaseRequisitionShowQuestionnaires</a>

First included in: ProcurementAndSourcing/ProcProcurementCategoryPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillPurchaseRequisitionShowQuestionnaires attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsQuantityVerifiedBeforeRecordingPurchase name="IsQuantityVerifiedBeforeRecordingPurchase">IsQuantityVerifiedBeforeRecordingPurchase</a>

First included in: ProcurementAndSourcing/ProcProcurementCategoryPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsQuantityVerifiedBeforeRecordingPurchase attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CategoryMatchingPolicy name="CategoryMatchingPolicy">CategoryMatchingPolicy</a>

First included in: ProcurementAndSourcing/ProcProcurementCategoryPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CategoryMatchingPolicy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillProductReceiptAccruePurchaseExpense name="WillProductReceiptAccruePurchaseExpense">WillProductReceiptAccruePurchaseExpense</a>

First included in: ProcurementAndSourcing/ProcProcurementCategoryPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillProductReceiptAccruePurchaseExpense attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorSelectionRule name="VendorSelectionRule">VendorSelectionRule</a>

First included in: ProcurementAndSourcing/ProcProcurementCategoryPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorSelectionRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProcurementCategory name="ProcurementCategory">ProcurementCategory</a>

First included in: ProcurementAndSourcing/ProcProcurementCategoryPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcurementCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProcurementCategoryPolicyRule name="ProcurementCategoryPolicyRule">ProcurementCategoryPolicyRule</a>

First included in: ProcurementAndSourcing/ProcProcurementCategoryPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcurementCategoryPolicyRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Policy name="Policy">Policy</a>

First included in: ProcurementAndSourcing/ProcProcurementCategoryPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Policy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PolicyRuleType name="PolicyRuleType">PolicyRuleType</a>

First included in: ProcurementAndSourcing/ProcProcurementCategoryPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PolicyRuleType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InstanceRelationType name="InstanceRelationType">InstanceRelationType</a>

First included in: ProcurementAndSourcing/ProcProcurementCategoryPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InstanceRelationType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PolicyRuleName name="PolicyRuleName">PolicyRuleName</a>

First included in: ProcurementAndSourcing/ProcProcurementCategoryPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PolicyRuleName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchasingPolicyName name="PurchasingPolicyName">PurchasingPolicyName</a>

First included in: ProcurementAndSourcing/ProcProcurementCategoryPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchasingPolicyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_ProcCategoryPolicyParameterRelationshipId name="BackingTable_ProcCategoryPolicyParameterRelationshipId">BackingTable_ProcCategoryPolicyParameterRelationshipId</a>

First included in: ProcurementAndSourcing/ProcProcurementCategoryPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_ProcCategoryPolicyParameterRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Main/ProcCategoryPolicyParameter.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Main/ProcCategoryPolicyParameter.cdm.json/ProcCategoryPolicyParameter</a></td><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Main/ProcCategoryPolicyParameter.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
