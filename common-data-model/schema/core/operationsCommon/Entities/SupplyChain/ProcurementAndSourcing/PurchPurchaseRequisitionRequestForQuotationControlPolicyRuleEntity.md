---
title: PurchPurchaseRequisitionRequestForQuotationControlPolicyRuleEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# Purchase requisition request for quotation control policies

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/PurchPurchaseRequisitionRequestForQuotationControlPolicyRuleEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchase requisition request for quotation control policies</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[Policy](#Policy)||<a href="PurchPurchaseRequisitionRequestForQuotationControlPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRequisitionRequestForQuotationControlPolicyRuleEntity</a>|
|[PolicyRuleType](#PolicyRuleType)||<a href="PurchPurchaseRequisitionRequestForQuotationControlPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRequisitionRequestForQuotationControlPolicyRuleEntity</a>|
|[ValidFrom](#ValidFrom)||<a href="PurchPurchaseRequisitionRequestForQuotationControlPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRequisitionRequestForQuotationControlPolicyRuleEntity</a>|
|[ValidTo](#ValidTo)||<a href="PurchPurchaseRequisitionRequestForQuotationControlPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRequisitionRequestForQuotationControlPolicyRuleEntity</a>|
|[FormalRFQInstruction](#FormalRFQInstruction)||<a href="PurchPurchaseRequisitionRequestForQuotationControlPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRequisitionRequestForQuotationControlPolicyRuleEntity</a>|
|[FormalRFQRequirementRule](#FormalRFQRequirementRule)||<a href="PurchPurchaseRequisitionRequestForQuotationControlPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRequisitionRequestForQuotationControlPolicyRuleEntity</a>|
|[FormalRFQThresholdAmount](#FormalRFQThresholdAmount)||<a href="PurchPurchaseRequisitionRequestForQuotationControlPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRequisitionRequestForQuotationControlPolicyRuleEntity</a>|
|[FormalRFQThresholdAmountCurrencyCode](#FormalRFQThresholdAmountCurrencyCode)||<a href="PurchPurchaseRequisitionRequestForQuotationControlPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRequisitionRequestForQuotationControlPolicyRuleEntity</a>|
|[PurchasingPolicyName](#PurchasingPolicyName)||<a href="PurchPurchaseRequisitionRequestForQuotationControlPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRequisitionRequestForQuotationControlPolicyRuleEntity</a>|
|[PolicyRuleName](#PolicyRuleName)||<a href="PurchPurchaseRequisitionRequestForQuotationControlPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRequisitionRequestForQuotationControlPolicyRuleEntity</a>|
|[InformalRFQInstruction](#InformalRFQInstruction)||<a href="PurchPurchaseRequisitionRequestForQuotationControlPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRequisitionRequestForQuotationControlPolicyRuleEntity</a>|
|[InformalRFQRequirementRule](#InformalRFQRequirementRule)||<a href="PurchPurchaseRequisitionRequestForQuotationControlPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRequisitionRequestForQuotationControlPolicyRuleEntity</a>|
|[InformalRFQThresholdAmount](#InformalRFQThresholdAmount)||<a href="PurchPurchaseRequisitionRequestForQuotationControlPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRequisitionRequestForQuotationControlPolicyRuleEntity</a>|
|[InformalRFQThresholdAmountCurrencyCode](#InformalRFQThresholdAmountCurrencyCode)||<a href="PurchPurchaseRequisitionRequestForQuotationControlPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRequisitionRequestForQuotationControlPolicyRuleEntity</a>|
|[BackingTable_PurchReqControlRFQRuleRelationshipId](#BackingTable_PurchReqControlRFQRuleRelationshipId)||<a href="PurchPurchaseRequisitionRequestForQuotationControlPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseRequisitionRequestForQuotationControlPolicyRuleEntity</a>|

### <a href=#Policy name="Policy">Policy</a>

First included in: ProcurementAndSourcing/PurchPurchaseRequisitionRequestForQuotationControlPolicyRuleEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseRequisitionRequestForQuotationControlPolicyRuleEntity (this entity)  

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

### <a href=#ValidFrom name="ValidFrom">ValidFrom</a>

First included in: ProcurementAndSourcing/PurchPurchaseRequisitionRequestForQuotationControlPolicyRuleEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseRequisitionRequestForQuotationControlPolicyRuleEntity (this entity)  

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

### <a href=#FormalRFQInstruction name="FormalRFQInstruction">FormalRFQInstruction</a>

First included in: ProcurementAndSourcing/PurchPurchaseRequisitionRequestForQuotationControlPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormalRFQInstruction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FormalRFQRequirementRule name="FormalRFQRequirementRule">FormalRFQRequirementRule</a>

First included in: ProcurementAndSourcing/PurchPurchaseRequisitionRequestForQuotationControlPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormalRFQRequirementRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FormalRFQThresholdAmount name="FormalRFQThresholdAmount">FormalRFQThresholdAmount</a>

First included in: ProcurementAndSourcing/PurchPurchaseRequisitionRequestForQuotationControlPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormalRFQThresholdAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FormalRFQThresholdAmountCurrencyCode name="FormalRFQThresholdAmountCurrencyCode">FormalRFQThresholdAmountCurrencyCode</a>

First included in: ProcurementAndSourcing/PurchPurchaseRequisitionRequestForQuotationControlPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FormalRFQThresholdAmountCurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchasingPolicyName name="PurchasingPolicyName">PurchasingPolicyName</a>

First included in: ProcurementAndSourcing/PurchPurchaseRequisitionRequestForQuotationControlPolicyRuleEntity (this entity)  

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

### <a href=#PolicyRuleName name="PolicyRuleName">PolicyRuleName</a>

First included in: ProcurementAndSourcing/PurchPurchaseRequisitionRequestForQuotationControlPolicyRuleEntity (this entity)  

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

### <a href=#InformalRFQInstruction name="InformalRFQInstruction">InformalRFQInstruction</a>

First included in: ProcurementAndSourcing/PurchPurchaseRequisitionRequestForQuotationControlPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InformalRFQInstruction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InformalRFQRequirementRule name="InformalRFQRequirementRule">InformalRFQRequirementRule</a>

First included in: ProcurementAndSourcing/PurchPurchaseRequisitionRequestForQuotationControlPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InformalRFQRequirementRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InformalRFQThresholdAmount name="InformalRFQThresholdAmount">InformalRFQThresholdAmount</a>

First included in: ProcurementAndSourcing/PurchPurchaseRequisitionRequestForQuotationControlPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InformalRFQThresholdAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InformalRFQThresholdAmountCurrencyCode name="InformalRFQThresholdAmountCurrencyCode">InformalRFQThresholdAmountCurrencyCode</a>

First included in: ProcurementAndSourcing/PurchPurchaseRequisitionRequestForQuotationControlPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InformalRFQThresholdAmountCurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_PurchReqControlRFQRuleRelationshipId name="BackingTable_PurchReqControlRFQRuleRelationshipId">BackingTable_PurchReqControlRFQRuleRelationshipId</a>

First included in: ProcurementAndSourcing/PurchPurchaseRequisitionRequestForQuotationControlPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PurchReqControlRFQRuleRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Parameter/PurchReqControlRFQRule.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Parameter/PurchReqControlRFQRule.cdm.json/PurchReqControlRFQRule</a></td><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Parameter/PurchReqControlRFQRule.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
