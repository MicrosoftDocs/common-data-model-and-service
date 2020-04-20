---
title: BudgetAllowTransferRuleMemberCriteria - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# BudgetAllowTransferRuleMemberCriteria

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Budget/Group/BudgetAllowTransferRuleMemberCriteria.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BudgetAllowTransferRuleMemberCriteria/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="BudgetAllowTransferRuleMemberCriteria.md" target="_blank">Group/BudgetAllowTransferRuleMemberCriteria</a>|
|[BudgetAllowTransferRuleMember](#BudgetAllowTransferRuleMember)||<a href="BudgetAllowTransferRuleMemberCriteria.md" target="_blank">Group/BudgetAllowTransferRuleMemberCriteria</a>|
|[BudgetPrimaryLedgerDimensionAttribute](#BudgetPrimaryLedgerDimensionAttribute)||<a href="BudgetAllowTransferRuleMemberCriteria.md" target="_blank">Group/BudgetAllowTransferRuleMemberCriteria</a>|
|[IsFromOpen](#IsFromOpen)||<a href="BudgetAllowTransferRuleMemberCriteria.md" target="_blank">Group/BudgetAllowTransferRuleMemberCriteria</a>|
|[IsToOpen](#IsToOpen)||<a href="BudgetAllowTransferRuleMemberCriteria.md" target="_blank">Group/BudgetAllowTransferRuleMemberCriteria</a>|
|[RangeFrom](#RangeFrom)||<a href="BudgetAllowTransferRuleMemberCriteria.md" target="_blank">Group/BudgetAllowTransferRuleMemberCriteria</a>|
|[RangeTo](#RangeTo)||<a href="BudgetAllowTransferRuleMemberCriteria.md" target="_blank">Group/BudgetAllowTransferRuleMemberCriteria</a>|
|[WildcardString](#WildcardString)||<a href="BudgetAllowTransferRuleMemberCriteria.md" target="_blank">Group/BudgetAllowTransferRuleMemberCriteria</a>|
|[Relationship_BudgetAllowTransferRuleMemberRelationshipId](#Relationship_BudgetAllowTransferRuleMemberRelationshipId)||<a href="BudgetAllowTransferRuleMemberCriteria.md" target="_blank">Group/BudgetAllowTransferRuleMemberCriteria</a>|
|[Relationship_BudgetPrimaryLedgerDimensionAttributeRelationshipId](#Relationship_BudgetPrimaryLedgerDimensionAttributeRelationshipId)||<a href="BudgetAllowTransferRuleMemberCriteria.md" target="_blank">Group/BudgetAllowTransferRuleMemberCriteria</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Group/BudgetAllowTransferRuleMemberCriteria (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BudgetAllowTransferRuleMemberCriteria/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BudgetAllowTransferRuleMember name="BudgetAllowTransferRuleMember">BudgetAllowTransferRuleMember</a>

First included in: Group/BudgetAllowTransferRuleMemberCriteria (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetAllowTransferRuleMember attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BudgetPrimaryLedgerDimensionAttribute name="BudgetPrimaryLedgerDimensionAttribute">BudgetPrimaryLedgerDimensionAttribute</a>

First included in: Group/BudgetAllowTransferRuleMemberCriteria (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetPrimaryLedgerDimensionAttribute attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#IsFromOpen name="IsFromOpen">IsFromOpen</a>

First included in: Group/BudgetAllowTransferRuleMemberCriteria (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsFromOpen attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsToOpen name="IsToOpen">IsToOpen</a>

First included in: Group/BudgetAllowTransferRuleMemberCriteria (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsToOpen attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RangeFrom name="RangeFrom">RangeFrom</a>

First included in: Group/BudgetAllowTransferRuleMemberCriteria (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RangeFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RangeTo name="RangeTo">RangeTo</a>

First included in: Group/BudgetAllowTransferRuleMemberCriteria (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RangeTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WildcardString name="WildcardString">WildcardString</a>

First included in: Group/BudgetAllowTransferRuleMemberCriteria (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WildcardString attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BudgetAllowTransferRuleMemberRelationshipId name="Relationship_BudgetAllowTransferRuleMemberRelationshipId">Relationship_BudgetAllowTransferRuleMemberRelationshipId</a>

First included in: Group/BudgetAllowTransferRuleMemberCriteria (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BudgetAllowTransferRuleMemberRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="BudgetAllowTransferRuleMember.md" target="_blank">/core/operationsCommon/Tables/Finance/Budget/Group/BudgetAllowTransferRuleMember.cdm.json/BudgetAllowTransferRuleMember</a></td><td><a href="BudgetAllowTransferRuleMember.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BudgetPrimaryLedgerDimensionAttributeRelationshipId name="Relationship_BudgetPrimaryLedgerDimensionAttributeRelationshipId">Relationship_BudgetPrimaryLedgerDimensionAttributeRelationshipId</a>

First included in: Group/BudgetAllowTransferRuleMemberCriteria (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BudgetPrimaryLedgerDimensionAttributeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="BudgetPrimaryLedgerDimensionAttribute.md" target="_blank">/core/operationsCommon/Tables/Finance/Budget/Group/BudgetPrimaryLedgerDimensionAttribute.cdm.json/BudgetPrimaryLedgerDimensionAttribute</a></td><td><a href="BudgetPrimaryLedgerDimensionAttribute.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
