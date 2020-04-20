---
title: JmgTimeAndAttendanceTimeRegistrationWorkerEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# JmgTimeAndAttendanceTimeRegistrationWorkerEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductionControl/JmgTimeAndAttendanceTimeRegistrationWorkerEntity.cdm.json" target="_blank">GitHub</a>.  

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
|[ApproverPersonnelNumber](#ApproverPersonnelNumber)||<a href="JmgTimeAndAttendanceTimeRegistrationWorkerEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceTimeRegistrationWorkerEntity</a>|
|[CanBundleNewJobs](#CanBundleNewJobs)||<a href="JmgTimeAndAttendanceTimeRegistrationWorkerEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceTimeRegistrationWorkerEntity</a>|
|[CanUseElectronicTimecard](#CanUseElectronicTimecard)||<a href="JmgTimeAndAttendanceTimeRegistrationWorkerEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceTimeRegistrationWorkerEntity</a>|
|[DefaultTimeAndAttedanceCalculationGroupId](#DefaultTimeAndAttedanceCalculationGroupId)||<a href="JmgTimeAndAttendanceTimeRegistrationWorkerEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceTimeRegistrationWorkerEntity</a>|
|[IsActive](#IsActive)||<a href="JmgTimeAndAttendanceTimeRegistrationWorkerEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceTimeRegistrationWorkerEntity</a>|
|[IsFlexTimeAllowed](#IsFlexTimeAllowed)||<a href="JmgTimeAndAttendanceTimeRegistrationWorkerEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceTimeRegistrationWorkerEntity</a>|
|[HasSupervisorOptions](#HasSupervisorOptions)||<a href="JmgTimeAndAttendanceTimeRegistrationWorkerEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceTimeRegistrationWorkerEntity</a>|
|[JobCardTerminalConfigurationId](#JobCardTerminalConfigurationId)||<a href="JmgTimeAndAttendanceTimeRegistrationWorkerEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceTimeRegistrationWorkerEntity</a>|
|[OpeningFlexBalanceSeconds](#OpeningFlexBalanceSeconds)||<a href="JmgTimeAndAttendanceTimeRegistrationWorkerEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceTimeRegistrationWorkerEntity</a>|
|[PayAgreementCode](#PayAgreementCode)||<a href="JmgTimeAndAttendanceTimeRegistrationWorkerEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceTimeRegistrationWorkerEntity</a>|
|[ProjectCategoryId](#ProjectCategoryId)||<a href="JmgTimeAndAttendanceTimeRegistrationWorkerEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceTimeRegistrationWorkerEntity</a>|
|[ProjectPeriodId](#ProjectPeriodId)||<a href="JmgTimeAndAttendanceTimeRegistrationWorkerEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceTimeRegistrationWorkerEntity</a>|
|[StandardTimeProfileId](#StandardTimeProfileId)||<a href="JmgTimeAndAttendanceTimeRegistrationWorkerEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceTimeRegistrationWorkerEntity</a>|
|[SeniorityDate](#SeniorityDate)||<a href="JmgTimeAndAttendanceTimeRegistrationWorkerEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceTimeRegistrationWorkerEntity</a>|
|[TimeAndAttendanceApprovalGroupId](#TimeAndAttendanceApprovalGroupId)||<a href="JmgTimeAndAttendanceTimeRegistrationWorkerEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceTimeRegistrationWorkerEntity</a>|
|[TimeAndAttendanceCalculationGroupId](#TimeAndAttendanceCalculationGroupId)||<a href="JmgTimeAndAttendanceTimeRegistrationWorkerEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceTimeRegistrationWorkerEntity</a>|
|[TimeAndAttendanceFlexGroupId](#TimeAndAttendanceFlexGroupId)||<a href="JmgTimeAndAttendanceTimeRegistrationWorkerEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceTimeRegistrationWorkerEntity</a>|
|[TimeAndAttendanceProfileGroupId](#TimeAndAttendanceProfileGroupId)||<a href="JmgTimeAndAttendanceTimeRegistrationWorkerEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceTimeRegistrationWorkerEntity</a>|
|[WorkerActivationDate](#WorkerActivationDate)||<a href="JmgTimeAndAttendanceTimeRegistrationWorkerEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceTimeRegistrationWorkerEntity</a>|
|[WorkerBadgeId](#WorkerBadgeId)||<a href="JmgTimeAndAttendanceTimeRegistrationWorkerEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceTimeRegistrationWorkerEntity</a>|
|[WorkerBadgeVersion](#WorkerBadgeVersion)||<a href="JmgTimeAndAttendanceTimeRegistrationWorkerEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceTimeRegistrationWorkerEntity</a>|
|[Relationship_HCMWorkerRelationshipId](#Relationship_HCMWorkerRelationshipId)||<a href="JmgTimeAndAttendanceTimeRegistrationWorkerEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceTimeRegistrationWorkerEntity</a>|
|[BackingTable_JmgEmployeeRelationshipId](#BackingTable_JmgEmployeeRelationshipId)||<a href="JmgTimeAndAttendanceTimeRegistrationWorkerEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceTimeRegistrationWorkerEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="JmgTimeAndAttendanceTimeRegistrationWorkerEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceTimeRegistrationWorkerEntity</a>|

### <a href=#ApproverPersonnelNumber name="ApproverPersonnelNumber">ApproverPersonnelNumber</a>

First included in: ProductionControl/JmgTimeAndAttendanceTimeRegistrationWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ApproverPersonnelNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CanBundleNewJobs name="CanBundleNewJobs">CanBundleNewJobs</a>

First included in: ProductionControl/JmgTimeAndAttendanceTimeRegistrationWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CanBundleNewJobs attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CanUseElectronicTimecard name="CanUseElectronicTimecard">CanUseElectronicTimecard</a>

First included in: ProductionControl/JmgTimeAndAttendanceTimeRegistrationWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CanUseElectronicTimecard attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultTimeAndAttedanceCalculationGroupId name="DefaultTimeAndAttedanceCalculationGroupId">DefaultTimeAndAttedanceCalculationGroupId</a>

First included in: ProductionControl/JmgTimeAndAttendanceTimeRegistrationWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultTimeAndAttedanceCalculationGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsActive name="IsActive">IsActive</a>

First included in: ProductionControl/JmgTimeAndAttendanceTimeRegistrationWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsActive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsFlexTimeAllowed name="IsFlexTimeAllowed">IsFlexTimeAllowed</a>

First included in: ProductionControl/JmgTimeAndAttendanceTimeRegistrationWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsFlexTimeAllowed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HasSupervisorOptions name="HasSupervisorOptions">HasSupervisorOptions</a>

First included in: ProductionControl/JmgTimeAndAttendanceTimeRegistrationWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HasSupervisorOptions attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JobCardTerminalConfigurationId name="JobCardTerminalConfigurationId">JobCardTerminalConfigurationId</a>

First included in: ProductionControl/JmgTimeAndAttendanceTimeRegistrationWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JobCardTerminalConfigurationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OpeningFlexBalanceSeconds name="OpeningFlexBalanceSeconds">OpeningFlexBalanceSeconds</a>

First included in: ProductionControl/JmgTimeAndAttendanceTimeRegistrationWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OpeningFlexBalanceSeconds attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayAgreementCode name="PayAgreementCode">PayAgreementCode</a>

First included in: ProductionControl/JmgTimeAndAttendanceTimeRegistrationWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayAgreementCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectCategoryId name="ProjectCategoryId">ProjectCategoryId</a>

First included in: ProductionControl/JmgTimeAndAttendanceTimeRegistrationWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectCategoryId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectPeriodId name="ProjectPeriodId">ProjectPeriodId</a>

First included in: ProductionControl/JmgTimeAndAttendanceTimeRegistrationWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectPeriodId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StandardTimeProfileId name="StandardTimeProfileId">StandardTimeProfileId</a>

First included in: ProductionControl/JmgTimeAndAttendanceTimeRegistrationWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StandardTimeProfileId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SeniorityDate name="SeniorityDate">SeniorityDate</a>

First included in: ProductionControl/JmgTimeAndAttendanceTimeRegistrationWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SeniorityDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeAndAttendanceApprovalGroupId name="TimeAndAttendanceApprovalGroupId">TimeAndAttendanceApprovalGroupId</a>

First included in: ProductionControl/JmgTimeAndAttendanceTimeRegistrationWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeAndAttendanceApprovalGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeAndAttendanceCalculationGroupId name="TimeAndAttendanceCalculationGroupId">TimeAndAttendanceCalculationGroupId</a>

First included in: ProductionControl/JmgTimeAndAttendanceTimeRegistrationWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeAndAttendanceCalculationGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeAndAttendanceFlexGroupId name="TimeAndAttendanceFlexGroupId">TimeAndAttendanceFlexGroupId</a>

First included in: ProductionControl/JmgTimeAndAttendanceTimeRegistrationWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeAndAttendanceFlexGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TimeAndAttendanceProfileGroupId name="TimeAndAttendanceProfileGroupId">TimeAndAttendanceProfileGroupId</a>

First included in: ProductionControl/JmgTimeAndAttendanceTimeRegistrationWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeAndAttendanceProfileGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkerActivationDate name="WorkerActivationDate">WorkerActivationDate</a>

First included in: ProductionControl/JmgTimeAndAttendanceTimeRegistrationWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerActivationDate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkerBadgeId name="WorkerBadgeId">WorkerBadgeId</a>

First included in: ProductionControl/JmgTimeAndAttendanceTimeRegistrationWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerBadgeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkerBadgeVersion name="WorkerBadgeVersion">WorkerBadgeVersion</a>

First included in: ProductionControl/JmgTimeAndAttendanceTimeRegistrationWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerBadgeVersion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_HCMWorkerRelationshipId name="Relationship_HCMWorkerRelationshipId">Relationship_HCMWorkerRelationshipId</a>

First included in: ProductionControl/JmgTimeAndAttendanceTimeRegistrationWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_HCMWorkerRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_JmgEmployeeRelationshipId name="BackingTable_JmgEmployeeRelationshipId">BackingTable_JmgEmployeeRelationshipId</a>

First included in: ProductionControl/JmgTimeAndAttendanceTimeRegistrationWorkerEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_JmgEmployeeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProductionControl/Main/JmgEmployee.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/Main/JmgEmployee.cdm.json/JmgEmployee</a></td><td><a href="../../../Tables/SupplyChain/ProductionControl/Main/JmgEmployee.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProductionControl/JmgTimeAndAttendanceTimeRegistrationWorkerEntity (this entity)  

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
