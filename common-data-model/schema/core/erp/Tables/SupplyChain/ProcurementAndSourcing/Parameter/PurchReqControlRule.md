---
title: PurchReqControlRule - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# PurchReqControlRule

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/SupplyChain/ProcurementAndSourcing/Parameter/PurchReqControlRule.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PurchReqControlRule/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="PurchReqControlRule.md" target="_blank">Parameter/PurchReqControlRule</a>|
|[InstanceRelationType](#InstanceRelationType)||<a href="PurchReqControlRule.md" target="_blank">Parameter/PurchReqControlRule</a>|
|[IsInherited](#IsInherited)||<a href="PurchReqControlRule.md" target="_blank">Parameter/PurchReqControlRule</a>|
|[Policy](#Policy)||<a href="PurchReqControlRule.md" target="_blank">Parameter/PurchReqControlRule</a>|
|[PolicyRuleType](#PolicyRuleType)||<a href="PurchReqControlRule.md" target="_blank">Parameter/PurchReqControlRule</a>|
|[ValidFrom](#ValidFrom)||<a href="PurchReqControlRule.md" target="_blank">Parameter/PurchReqControlRule</a>|
|[ValidTo](#ValidTo)||<a href="PurchReqControlRule.md" target="_blank">Parameter/PurchReqControlRule</a>|
|[Relationship_PolicyRelationshipId](#Relationship_PolicyRelationshipId)||<a href="PurchReqControlRule.md" target="_blank">Parameter/PurchReqControlRule</a>|
|[Relationship_PolicyRulesRelationshipId](#Relationship_PolicyRulesRelationshipId)||<a href="PurchReqControlRule.md" target="_blank">Parameter/PurchReqControlRule</a>|
|[AlternateAddress](#AlternateAddress)||<a href="PurchReqControlRule.md" target="_blank">Parameter/PurchReqControlRule</a>|
|[IsFixedMaximumOrderQuantity](#IsFixedMaximumOrderQuantity)||<a href="PurchReqControlRule.md" target="_blank">Parameter/PurchReqControlRule</a>|
|[IsFixedMinimumOrderQuantity](#IsFixedMinimumOrderQuantity)||<a href="PurchReqControlRule.md" target="_blank">Parameter/PurchReqControlRule</a>|
|[IsFixedMultipleOrderQuantity](#IsFixedMultipleOrderQuantity)||<a href="PurchReqControlRule.md" target="_blank">Parameter/PurchReqControlRule</a>|
|[IsReqDateTransDate](#IsReqDateTransDate)||<a href="PurchReqControlRule.md" target="_blank">Parameter/PurchReqControlRule</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Parameter/PurchReqControlRule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PurchReqControlRule/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#InstanceRelationType name="InstanceRelationType">InstanceRelationType</a>

First included in: Parameter/PurchReqControlRule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InstanceRelationType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#IsInherited name="IsInherited">IsInherited</a>

First included in: Parameter/PurchReqControlRule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsInherited attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Policy name="Policy">Policy</a>

First included in: Parameter/PurchReqControlRule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Policy attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PolicyRuleType name="PolicyRuleType">PolicyRuleType</a>

First included in: Parameter/PurchReqControlRule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PolicyRuleType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ValidFrom name="ValidFrom">ValidFrom</a>

First included in: Parameter/PurchReqControlRule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidFrom attribute are listed below.</summary>

</details>

### <a href=#ValidTo name="ValidTo">ValidTo</a>

First included in: Parameter/PurchReqControlRule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidTo attribute are listed below.</summary>

</details>

### <a href=#Relationship_PolicyRelationshipId name="Relationship_PolicyRelationshipId">Relationship_PolicyRelationshipId</a>

First included in: Parameter/PurchReqControlRule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PolicyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/Workflow/Main/SysPolicy.md" target="_blank">/core/erp/Tables/System/Workflow/Main/SysPolicy.cdm.json/SysPolicy</a></td><td><a href="../../../System/Workflow/Main/SysPolicy.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PolicyRulesRelationshipId name="Relationship_PolicyRulesRelationshipId">Relationship_PolicyRulesRelationshipId</a>

First included in: Parameter/PurchReqControlRule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PolicyRulesRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/Workflow/Reference/SysPolicyRuleType.md" target="_blank">/core/erp/Tables/System/Workflow/Reference/SysPolicyRuleType.cdm.json/SysPolicyRuleType</a></td><td><a href="../../../System/Workflow/Reference/SysPolicyRuleType.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AlternateAddress name="AlternateAddress">AlternateAddress</a>

First included in: Parameter/PurchReqControlRule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AlternateAddress attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsFixedMaximumOrderQuantity name="IsFixedMaximumOrderQuantity">IsFixedMaximumOrderQuantity</a>

First included in: Parameter/PurchReqControlRule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsFixedMaximumOrderQuantity attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsFixedMinimumOrderQuantity name="IsFixedMinimumOrderQuantity">IsFixedMinimumOrderQuantity</a>

First included in: Parameter/PurchReqControlRule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsFixedMinimumOrderQuantity attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsFixedMultipleOrderQuantity name="IsFixedMultipleOrderQuantity">IsFixedMultipleOrderQuantity</a>

First included in: Parameter/PurchReqControlRule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsFixedMultipleOrderQuantity attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsReqDateTransDate name="IsReqDateTransDate">IsReqDateTransDate</a>

First included in: Parameter/PurchReqControlRule (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsReqDateTransDate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>
