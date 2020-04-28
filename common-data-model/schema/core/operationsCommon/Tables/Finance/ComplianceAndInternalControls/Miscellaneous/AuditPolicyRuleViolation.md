---
title: AuditPolicyRuleViolation - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Audit policy rule violation

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/ComplianceAndInternalControls/Miscellaneous/AuditPolicyRuleViolation.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[AuditPolicyRuleViolation/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Audit policy rule violation</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="AuditPolicyRuleViolation.md" target="_blank">Miscellaneous/AuditPolicyRuleViolation</a>|
|[BatchJob](#BatchJob)||<a href="AuditPolicyRuleViolation.md" target="_blank">Miscellaneous/AuditPolicyRuleViolation</a>|
|[CaseDetailBase](#CaseDetailBase)||<a href="AuditPolicyRuleViolation.md" target="_blank">Miscellaneous/AuditPolicyRuleViolation</a>|
|[InstanceID](#InstanceID)||<a href="AuditPolicyRuleViolation.md" target="_blank">Miscellaneous/AuditPolicyRuleViolation</a>|
|[PolicyExecutionTimestamp](#PolicyExecutionTimestamp)||<a href="AuditPolicyRuleViolation.md" target="_blank">Miscellaneous/AuditPolicyRuleViolation</a>|
|[PolicySourceDocumentRuleViolation](#PolicySourceDocumentRuleViolation)||<a href="AuditPolicyRuleViolation.md" target="_blank">Miscellaneous/AuditPolicyRuleViolation</a>|
|[Relationship_BatchJobFKRelationshipId](#Relationship_BatchJobFKRelationshipId)||<a href="AuditPolicyRuleViolation.md" target="_blank">Miscellaneous/AuditPolicyRuleViolation</a>|
|[Relationship_SourceDocumentRuleViolationFKRelationshipId](#Relationship_SourceDocumentRuleViolationFKRelationshipId)||<a href="AuditPolicyRuleViolation.md" target="_blank">Miscellaneous/AuditPolicyRuleViolation</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/AuditPolicyRuleViolation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[AuditPolicyRuleViolation/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BatchJob name="BatchJob">BatchJob</a>

First included in: Miscellaneous/AuditPolicyRuleViolation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BatchJob attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CaseDetailBase name="CaseDetailBase">CaseDetailBase</a>

First included in: Miscellaneous/AuditPolicyRuleViolation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CaseDetailBase attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#InstanceID name="InstanceID">InstanceID</a>

First included in: Miscellaneous/AuditPolicyRuleViolation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Instance ID</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InstanceID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Instance ID</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PolicyExecutionTimestamp name="PolicyExecutionTimestamp">PolicyExecutionTimestamp</a>

First included in: Miscellaneous/AuditPolicyRuleViolation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PolicyExecutionTimestamp attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#PolicySourceDocumentRuleViolation name="PolicySourceDocumentRuleViolation">PolicySourceDocumentRuleViolation</a>

First included in: Miscellaneous/AuditPolicyRuleViolation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PolicySourceDocumentRuleViolation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_BatchJobFKRelationshipId name="Relationship_BatchJobFKRelationshipId">Relationship_BatchJobFKRelationshipId</a>

First included in: Miscellaneous/AuditPolicyRuleViolation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BatchJobFKRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Transaction/BatchJob.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Transaction/BatchJob.cdm.json/BatchJob</a></td><td><a href="../../../System/SystemAdministration/Transaction/BatchJob.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SourceDocumentRuleViolationFKRelationshipId name="Relationship_SourceDocumentRuleViolationFKRelationshipId">Relationship_SourceDocumentRuleViolationFKRelationshipId</a>

First included in: Miscellaneous/AuditPolicyRuleViolation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SourceDocumentRuleViolationFKRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/Workflow/Main/SysPolicySourceDocumentRuleViolation.md" target="_blank">/core/operationsCommon/Tables/System/Workflow/Main/SysPolicySourceDocumentRuleViolation.cdm.json/SysPolicySourceDocumentRuleViolation</a></td><td><a href="../../../System/Workflow/Main/SysPolicySourceDocumentRuleViolation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
