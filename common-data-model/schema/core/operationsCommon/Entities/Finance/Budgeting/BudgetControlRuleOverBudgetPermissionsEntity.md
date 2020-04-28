---
title: BudgetControlRuleOverBudgetPermissionsEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Budget control rule over budget permissions

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/Budgeting/BudgetControlRuleOverBudgetPermissionsEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Budget control rule over budget permissions</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[LegalEntityId](#LegalEntityId)||<a href="BudgetControlRuleOverBudgetPermissionsEntity.md" target="_blank">Budgeting/BudgetControlRuleOverBudgetPermissionsEntity</a>|
|[Status](#Status)||<a href="BudgetControlRuleOverBudgetPermissionsEntity.md" target="_blank">Budgeting/BudgetControlRuleOverBudgetPermissionsEntity</a>|
|[InUseBy](#InUseBy)||<a href="BudgetControlRuleOverBudgetPermissionsEntity.md" target="_blank">Budgeting/BudgetControlRuleOverBudgetPermissionsEntity</a>|
|[RuleName](#RuleName)||<a href="BudgetControlRuleOverBudgetPermissionsEntity.md" target="_blank">Budgeting/BudgetControlRuleOverBudgetPermissionsEntity</a>|
|[UserGroupId](#UserGroupId)||<a href="BudgetControlRuleOverBudgetPermissionsEntity.md" target="_blank">Budgeting/BudgetControlRuleOverBudgetPermissionsEntity</a>|
|[UserGroupName](#UserGroupName)||<a href="BudgetControlRuleOverBudgetPermissionsEntity.md" target="_blank">Budgeting/BudgetControlRuleOverBudgetPermissionsEntity</a>|
|[OverrideOverbudgetOption](#OverrideOverbudgetOption)||<a href="BudgetControlRuleOverBudgetPermissionsEntity.md" target="_blank">Budgeting/BudgetControlRuleOverBudgetPermissionsEntity</a>|
|[OverbudgetBudgetGroupCheckOption](#OverbudgetBudgetGroupCheckOption)||<a href="BudgetControlRuleOverBudgetPermissionsEntity.md" target="_blank">Budgeting/BudgetControlRuleOverBudgetPermissionsEntity</a>|
|[Relationship_BudgetControlRuleEntityRelationshipId](#Relationship_BudgetControlRuleEntityRelationshipId)||<a href="BudgetControlRuleOverBudgetPermissionsEntity.md" target="_blank">Budgeting/BudgetControlRuleOverBudgetPermissionsEntity</a>|
|[Relationship_SystemUserGroupEntityRelationshipId](#Relationship_SystemUserGroupEntityRelationshipId)||<a href="BudgetControlRuleOverBudgetPermissionsEntity.md" target="_blank">Budgeting/BudgetControlRuleOverBudgetPermissionsEntity</a>|
|[BackingTable_BudgetControlRuleUserGroupOptionRelationshipId](#BackingTable_BudgetControlRuleUserGroupOptionRelationshipId)||<a href="BudgetControlRuleOverBudgetPermissionsEntity.md" target="_blank">Budgeting/BudgetControlRuleOverBudgetPermissionsEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="BudgetControlRuleOverBudgetPermissionsEntity.md" target="_blank">Budgeting/BudgetControlRuleOverBudgetPermissionsEntity</a>|

### <a href=#LegalEntityId name="LegalEntityId">LegalEntityId</a>

First included in: Budgeting/BudgetControlRuleOverBudgetPermissionsEntity (this entity)  

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

### <a href=#Status name="Status">Status</a>

First included in: Budgeting/BudgetControlRuleOverBudgetPermissionsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Status attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InUseBy name="InUseBy">InUseBy</a>

First included in: Budgeting/BudgetControlRuleOverBudgetPermissionsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InUseBy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RuleName name="RuleName">RuleName</a>

First included in: Budgeting/BudgetControlRuleOverBudgetPermissionsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RuleName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UserGroupId name="UserGroupId">UserGroupId</a>

First included in: Budgeting/BudgetControlRuleOverBudgetPermissionsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UserGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UserGroupName name="UserGroupName">UserGroupName</a>

First included in: Budgeting/BudgetControlRuleOverBudgetPermissionsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UserGroupName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OverrideOverbudgetOption name="OverrideOverbudgetOption">OverrideOverbudgetOption</a>

First included in: Budgeting/BudgetControlRuleOverBudgetPermissionsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OverrideOverbudgetOption attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OverbudgetBudgetGroupCheckOption name="OverbudgetBudgetGroupCheckOption">OverbudgetBudgetGroupCheckOption</a>

First included in: Budgeting/BudgetControlRuleOverBudgetPermissionsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OverbudgetBudgetGroupCheckOption attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BudgetControlRuleEntityRelationshipId name="Relationship_BudgetControlRuleEntityRelationshipId">Relationship_BudgetControlRuleEntityRelationshipId</a>

First included in: Budgeting/BudgetControlRuleOverBudgetPermissionsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BudgetControlRuleEntityRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SystemUserGroupEntityRelationshipId name="Relationship_SystemUserGroupEntityRelationshipId">Relationship_SystemUserGroupEntityRelationshipId</a>

First included in: Budgeting/BudgetControlRuleOverBudgetPermissionsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SystemUserGroupEntityRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_BudgetControlRuleUserGroupOptionRelationshipId name="BackingTable_BudgetControlRuleUserGroupOptionRelationshipId">BackingTable_BudgetControlRuleUserGroupOptionRelationshipId</a>

First included in: Budgeting/BudgetControlRuleOverBudgetPermissionsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_BudgetControlRuleUserGroupOptionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Budget/Group/BudgetControlRuleUserGroupOption.md" target="_blank">/core/operationsCommon/Tables/Finance/Budget/Group/BudgetControlRuleUserGroupOption.cdm.json/BudgetControlRuleUserGroupOption</a></td><td><a href="../../../Tables/Finance/Budget/Group/BudgetControlRuleUserGroupOption.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: Budgeting/BudgetControlRuleOverBudgetPermissionsEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PrimaryCompanyContextRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
