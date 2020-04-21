---
title: PurchReqSourcingPriceToleranceRule - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# PurchReqSourcingPriceToleranceRule

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Main/PurchReqSourcingPriceToleranceRule.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PurchReqSourcingPriceToleranceRule/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="PurchReqSourcingPriceToleranceRule.md" target="_blank">Main/PurchReqSourcingPriceToleranceRule</a>|
|[AmountLimit](#AmountLimit)||<a href="PurchReqSourcingPriceToleranceRule.md" target="_blank">Main/PurchReqSourcingPriceToleranceRule</a>|
|[AmountLimitCurrencyCode](#AmountLimitCurrencyCode)||<a href="PurchReqSourcingPriceToleranceRule.md" target="_blank">Main/PurchReqSourcingPriceToleranceRule</a>|
|[EnableAmountLimit](#EnableAmountLimit)||<a href="PurchReqSourcingPriceToleranceRule.md" target="_blank">Main/PurchReqSourcingPriceToleranceRule</a>|
|[EnablePercentageLimit](#EnablePercentageLimit)||<a href="PurchReqSourcingPriceToleranceRule.md" target="_blank">Main/PurchReqSourcingPriceToleranceRule</a>|
|[EnablePriceTolerance](#EnablePriceTolerance)||<a href="PurchReqSourcingPriceToleranceRule.md" target="_blank">Main/PurchReqSourcingPriceToleranceRule</a>|
|[PercentageLimit](#PercentageLimit)||<a href="PurchReqSourcingPriceToleranceRule.md" target="_blank">Main/PurchReqSourcingPriceToleranceRule</a>|
|[PolicyRule](#PolicyRule)||<a href="PurchReqSourcingPriceToleranceRule.md" target="_blank">Main/PurchReqSourcingPriceToleranceRule</a>|
|[Relationship_CurrencyRelationshipId](#Relationship_CurrencyRelationshipId)||<a href="PurchReqSourcingPriceToleranceRule.md" target="_blank">Main/PurchReqSourcingPriceToleranceRule</a>|
|[Relationship_PurchReqSourcingPolicyRuleRelationshipId](#Relationship_PurchReqSourcingPolicyRuleRelationshipId)||<a href="PurchReqSourcingPriceToleranceRule.md" target="_blank">Main/PurchReqSourcingPriceToleranceRule</a>|
|[Relationship_SysPolicyRuleRelationshipId](#Relationship_SysPolicyRuleRelationshipId)||<a href="PurchReqSourcingPriceToleranceRule.md" target="_blank">Main/PurchReqSourcingPriceToleranceRule</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/PurchReqSourcingPriceToleranceRule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PurchReqSourcingPriceToleranceRule/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AmountLimit name="AmountLimit">AmountLimit</a>

First included in: Main/PurchReqSourcingPriceToleranceRule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountLimit attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#AmountLimitCurrencyCode name="AmountLimitCurrencyCode">AmountLimitCurrencyCode</a>

First included in: Main/PurchReqSourcingPriceToleranceRule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AmountLimitCurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnableAmountLimit name="EnableAmountLimit">EnableAmountLimit</a>

First included in: Main/PurchReqSourcingPriceToleranceRule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnableAmountLimit attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EnablePercentageLimit name="EnablePercentageLimit">EnablePercentageLimit</a>

First included in: Main/PurchReqSourcingPriceToleranceRule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnablePercentageLimit attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EnablePriceTolerance name="EnablePriceTolerance">EnablePriceTolerance</a>

First included in: Main/PurchReqSourcingPriceToleranceRule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnablePriceTolerance attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PercentageLimit name="PercentageLimit">PercentageLimit</a>

First included in: Main/PurchReqSourcingPriceToleranceRule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PercentageLimit attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PolicyRule name="PolicyRule">PolicyRule</a>

First included in: Main/PurchReqSourcingPriceToleranceRule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PolicyRule attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_CurrencyRelationshipId name="Relationship_CurrencyRelationshipId">Relationship_CurrencyRelationshipId</a>

First included in: Main/PurchReqSourcingPriceToleranceRule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CurrencyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Currency/Group/Currency.md" target="_blank">/core/operationsCommon/Tables/Common/Currency/Group/Currency.cdm.json/Currency</a></td><td><a href="../../../Common/Currency/Group/Currency.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PurchReqSourcingPolicyRuleRelationshipId name="Relationship_PurchReqSourcingPolicyRuleRelationshipId">Relationship_PurchReqSourcingPolicyRuleRelationshipId</a>

First included in: Main/PurchReqSourcingPriceToleranceRule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchReqSourcingPolicyRuleRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Parameter/PurchReqSourcingPolicyRule.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Parameter/PurchReqSourcingPolicyRule.cdm.json/PurchReqSourcingPolicyRule</a></td><td><a href="../Parameter/PurchReqSourcingPolicyRule.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SysPolicyRuleRelationshipId name="Relationship_SysPolicyRuleRelationshipId">Relationship_SysPolicyRuleRelationshipId</a>

First included in: Main/PurchReqSourcingPriceToleranceRule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SysPolicyRuleRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/Workflow/Main/SysPolicyRule.md" target="_blank">/core/operationsCommon/Tables/System/Workflow/Main/SysPolicyRule.cdm.json/SysPolicyRule</a></td><td><a href="../../../System/Workflow/Main/SysPolicyRule.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
