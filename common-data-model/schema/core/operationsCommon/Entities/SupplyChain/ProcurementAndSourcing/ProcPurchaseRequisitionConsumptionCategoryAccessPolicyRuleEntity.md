---
title: ProcPurchaseRequisitionConsumptionCategoryAccessPolicyRuleEntity in ProcurementAndSourcing - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/10/2020
ms.author: nebanfic
---

# Purchase requisition consumption category access policies in ProcurementAndSourcing(ProcPurchaseRequisitionConsumptionCategoryAccessPolicyRuleEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/ProcPurchaseRequisitionConsumptionCategoryAccessPolicyRuleEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchase requisition consumption category access policies</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ValidFrom](#ValidFrom)||<a href="ProcPurchaseRequisitionConsumptionCategoryAccessPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/ProcPurchaseRequisitionConsumptionCategoryAccessPolicyRuleEntity</a>|
|[ValidTo](#ValidTo)||<a href="ProcPurchaseRequisitionConsumptionCategoryAccessPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/ProcPurchaseRequisitionConsumptionCategoryAccessPolicyRuleEntity</a>|
|[IsParentRuleIncluded](#IsParentRuleIncluded)||<a href="ProcPurchaseRequisitionConsumptionCategoryAccessPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/ProcPurchaseRequisitionConsumptionCategoryAccessPolicyRuleEntity</a>|
|[ProcurementCategoryName](#ProcurementCategoryName)||<a href="ProcPurchaseRequisitionConsumptionCategoryAccessPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/ProcPurchaseRequisitionConsumptionCategoryAccessPolicyRuleEntity</a>|
|[ProcurementCategory](#ProcurementCategory)||<a href="ProcPurchaseRequisitionConsumptionCategoryAccessPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/ProcPurchaseRequisitionConsumptionCategoryAccessPolicyRuleEntity</a>|
|[ProcurementCategoryAccessPolicyRule](#ProcurementCategoryAccessPolicyRule)||<a href="ProcPurchaseRequisitionConsumptionCategoryAccessPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/ProcPurchaseRequisitionConsumptionCategoryAccessPolicyRuleEntity</a>|
|[Policy](#Policy)||<a href="ProcPurchaseRequisitionConsumptionCategoryAccessPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/ProcPurchaseRequisitionConsumptionCategoryAccessPolicyRuleEntity</a>|
|[PolicyRuleType](#PolicyRuleType)||<a href="ProcPurchaseRequisitionConsumptionCategoryAccessPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/ProcPurchaseRequisitionConsumptionCategoryAccessPolicyRuleEntity</a>|
|[InstanceRelationType](#InstanceRelationType)||<a href="ProcPurchaseRequisitionConsumptionCategoryAccessPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/ProcPurchaseRequisitionConsumptionCategoryAccessPolicyRuleEntity</a>|
|[PolicyRuleName](#PolicyRuleName)||<a href="ProcPurchaseRequisitionConsumptionCategoryAccessPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/ProcPurchaseRequisitionConsumptionCategoryAccessPolicyRuleEntity</a>|
|[PurchasingPolicyName](#PurchasingPolicyName)||<a href="ProcPurchaseRequisitionConsumptionCategoryAccessPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/ProcPurchaseRequisitionConsumptionCategoryAccessPolicyRuleEntity</a>|
|[BackingTable_ProcCategoryAccessPolicyParameterRelationshipId](#BackingTable_ProcCategoryAccessPolicyParameterRelationshipId)||<a href="ProcPurchaseRequisitionConsumptionCategoryAccessPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/ProcPurchaseRequisitionConsumptionCategoryAccessPolicyRuleEntity</a>|

### <a href=#ValidFrom name="ValidFrom">ValidFrom</a>

First included in: ProcurementAndSourcing/ProcPurchaseRequisitionConsumptionCategoryAccessPolicyRuleEntity (this entity)  

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

First included in: ProcurementAndSourcing/ProcPurchaseRequisitionConsumptionCategoryAccessPolicyRuleEntity (this entity)  

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

### <a href=#IsParentRuleIncluded name="IsParentRuleIncluded">IsParentRuleIncluded</a>

First included in: ProcurementAndSourcing/ProcPurchaseRequisitionConsumptionCategoryAccessPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsParentRuleIncluded attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProcurementCategoryName name="ProcurementCategoryName">ProcurementCategoryName</a>

First included in: ProcurementAndSourcing/ProcPurchaseRequisitionConsumptionCategoryAccessPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Procurement category name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcurementCategoryName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Procurement category name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProcurementCategory name="ProcurementCategory">ProcurementCategory</a>

First included in: ProcurementAndSourcing/ProcPurchaseRequisitionConsumptionCategoryAccessPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcurementCategory attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProcurementCategoryAccessPolicyRule name="ProcurementCategoryAccessPolicyRule">ProcurementCategoryAccessPolicyRule</a>

First included in: ProcurementAndSourcing/ProcPurchaseRequisitionConsumptionCategoryAccessPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcurementCategoryAccessPolicyRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Policy name="Policy">Policy</a>

First included in: ProcurementAndSourcing/ProcPurchaseRequisitionConsumptionCategoryAccessPolicyRuleEntity (this entity)  

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

First included in: ProcurementAndSourcing/ProcPurchaseRequisitionConsumptionCategoryAccessPolicyRuleEntity (this entity)  

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

### <a href=#InstanceRelationType name="InstanceRelationType">InstanceRelationType</a>

First included in: ProcurementAndSourcing/ProcPurchaseRequisitionConsumptionCategoryAccessPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InstanceRelationType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PolicyRuleName name="PolicyRuleName">PolicyRuleName</a>

First included in: ProcurementAndSourcing/ProcPurchaseRequisitionConsumptionCategoryAccessPolicyRuleEntity (this entity)  

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

### <a href=#PurchasingPolicyName name="PurchasingPolicyName">PurchasingPolicyName</a>

First included in: ProcurementAndSourcing/ProcPurchaseRequisitionConsumptionCategoryAccessPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Policy name</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchasingPolicyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Policy name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_ProcCategoryAccessPolicyParameterRelationshipId name="BackingTable_ProcCategoryAccessPolicyParameterRelationshipId">BackingTable_ProcCategoryAccessPolicyParameterRelationshipId</a>

First included in: ProcurementAndSourcing/ProcPurchaseRequisitionConsumptionCategoryAccessPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_ProcCategoryAccessPolicyParameterRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Main/ProcCategoryAccessPolicyParameter.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Main/ProcCategoryAccessPolicyParameter.cdm.json/ProcCategoryAccessPolicyParameter</a></td><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Main/ProcCategoryAccessPolicyParameter.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
