---
title: PurchPurchaseOrderReapprovalPolicyRuleEntity in ProcurementAndSourcing - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/15/2020
ms.author: nebanfic
---

# Purchase order re-approval policies in ProcurementAndSourcing(PurchPurchaseOrderReapprovalPolicyRuleEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/PurchPurchaseOrderReapprovalPolicyRuleEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purchase order re-approval policies</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ValidFrom](#ValidFrom)||<a href="PurchPurchaseOrderReapprovalPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderReapprovalPolicyRuleEntity</a>|
|[ValidTo](#ValidTo)||<a href="PurchPurchaseOrderReapprovalPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderReapprovalPolicyRuleEntity</a>|
|[PurchasingPolicyName](#PurchasingPolicyName)||<a href="PurchPurchaseOrderReapprovalPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderReapprovalPolicyRuleEntity</a>|
|[Policy](#Policy)||<a href="PurchPurchaseOrderReapprovalPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderReapprovalPolicyRuleEntity</a>|
|[PolicyRuleType](#PolicyRuleType)||<a href="PurchPurchaseOrderReapprovalPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderReapprovalPolicyRuleEntity</a>|
|[PolicyRuleName](#PolicyRuleName)||<a href="PurchPurchaseOrderReapprovalPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderReapprovalPolicyRuleEntity</a>|
|[ReapprovalTableName](#ReapprovalTableName)||<a href="PurchPurchaseOrderReapprovalPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderReapprovalPolicyRuleEntity</a>|
|[ReapprovalFieldName](#ReapprovalFieldName)||<a href="PurchPurchaseOrderReapprovalPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderReapprovalPolicyRuleEntity</a>|
|[ReapprovalFieldId](#ReapprovalFieldId)||<a href="PurchPurchaseOrderReapprovalPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderReapprovalPolicyRuleEntity</a>|
|[ReapprovalTableId](#ReapprovalTableId)||<a href="PurchPurchaseOrderReapprovalPolicyRuleEntity.md" target="_blank">ProcurementAndSourcing/PurchPurchaseOrderReapprovalPolicyRuleEntity</a>|

### <a href=#ValidFrom name="ValidFrom">ValidFrom</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderReapprovalPolicyRuleEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderReapprovalPolicyRuleEntity (this entity)  

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

### <a href=#PurchasingPolicyName name="PurchasingPolicyName">PurchasingPolicyName</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderReapprovalPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Policy name</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchasingPolicyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Policy name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Policy name="Policy">Policy</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderReapprovalPolicyRuleEntity (this entity)  

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

First included in: ProcurementAndSourcing/PurchPurchaseOrderReapprovalPolicyRuleEntity (this entity)  

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

### <a href=#PolicyRuleName name="PolicyRuleName">PolicyRuleName</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderReapprovalPolicyRuleEntity (this entity)  

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

### <a href=#ReapprovalTableName name="ReapprovalTableName">ReapprovalTableName</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderReapprovalPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReapprovalTableName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReapprovalFieldName name="ReapprovalFieldName">ReapprovalFieldName</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderReapprovalPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReapprovalFieldName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReapprovalFieldId name="ReapprovalFieldId">ReapprovalFieldId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderReapprovalPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReapprovalFieldId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReapprovalTableId name="ReapprovalTableId">ReapprovalTableId</a>

First included in: ProcurementAndSourcing/PurchPurchaseOrderReapprovalPolicyRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReapprovalTableId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
