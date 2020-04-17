---
title: EmployeeTable_RU - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# EmployeeTable_RU

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Finance/Expense/Main/EmployeeTable_RU.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[EmployeeTable_RU/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="EmployeeTable_RU.md" target="_blank">Main/EmployeeTable_RU</a>|
|[AdvHolder](#AdvHolder)||<a href="EmployeeTable_RU.md" target="_blank">Main/EmployeeTable_RU</a>|
|[EmployeeId](#EmployeeId)||<a href="EmployeeTable_RU.md" target="_blank">Main/EmployeeTable_RU</a>|
|[HcmEmployment](#HcmEmployment)||<a href="EmployeeTable_RU.md" target="_blank">Main/EmployeeTable_RU</a>|
|[IdentityCard](#IdentityCard)||<a href="EmployeeTable_RU.md" target="_blank">Main/EmployeeTable_RU</a>|
|[IdentityCardIssueBy](#IdentityCardIssueBy)||<a href="EmployeeTable_RU.md" target="_blank">Main/EmployeeTable_RU</a>|
|[IdentityCardIssueDate](#IdentityCardIssueDate)||<a href="EmployeeTable_RU.md" target="_blank">Main/EmployeeTable_RU</a>|
|[IdentityCardNumber](#IdentityCardNumber)||<a href="EmployeeTable_RU.md" target="_blank">Main/EmployeeTable_RU</a>|
|[IdentityCardSeries](#IdentityCardSeries)||<a href="EmployeeTable_RU.md" target="_blank">Main/EmployeeTable_RU</a>|
|[LvPaymTransCodes](#LvPaymTransCodes)||<a href="EmployeeTable_RU.md" target="_blank">Main/EmployeeTable_RU</a>|
|[RPayCheck](#RPayCheck)||<a href="EmployeeTable_RU.md" target="_blank">Main/EmployeeTable_RU</a>|
|[WorkerGroup](#WorkerGroup)||<a href="EmployeeTable_RU.md" target="_blank">Main/EmployeeTable_RU</a>|
|[WorkTypeId](#WorkTypeId)||<a href="EmployeeTable_RU.md" target="_blank">Main/EmployeeTable_RU</a>|
|[DataAreaId](#DataAreaId)||<a href="EmployeeTable_RU.md" target="_blank">Main/EmployeeTable_RU</a>|
|[Relationship_HcmWorkerGroup_FKRelationshipId](#Relationship_HcmWorkerGroup_FKRelationshipId)||<a href="EmployeeTable_RU.md" target="_blank">Main/EmployeeTable_RU</a>|
|[Relationship_IdentityCardTable_FKRelationshipId](#Relationship_IdentityCardTable_FKRelationshipId)||<a href="EmployeeTable_RU.md" target="_blank">Main/EmployeeTable_RU</a>|
|[Relationship_LvPaymTransCodesRelationshipId](#Relationship_LvPaymTransCodesRelationshipId)||<a href="EmployeeTable_RU.md" target="_blank">Main/EmployeeTable_RU</a>|
|[Relationship_WorkTypeTableRelationshipId](#Relationship_WorkTypeTableRelationshipId)||<a href="EmployeeTable_RU.md" target="_blank">Main/EmployeeTable_RU</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="EmployeeTable_RU.md" target="_blank">Main/EmployeeTable_RU</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/EmployeeTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[EmployeeTable_RU/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AdvHolder name="AdvHolder">AdvHolder</a>

First included in: Main/EmployeeTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AdvHolder attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#EmployeeId name="EmployeeId">EmployeeId</a>

First included in: Main/EmployeeTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EmployeeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HcmEmployment name="HcmEmployment">HcmEmployment</a>

First included in: Main/EmployeeTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HcmEmployment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#IdentityCard name="IdentityCard">IdentityCard</a>

First included in: Main/EmployeeTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IdentityCard attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#IdentityCardIssueBy name="IdentityCardIssueBy">IdentityCardIssueBy</a>

First included in: Main/EmployeeTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IdentityCardIssueBy attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IdentityCardIssueDate name="IdentityCardIssueDate">IdentityCardIssueDate</a>

First included in: Main/EmployeeTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IdentityCardIssueDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#IdentityCardNumber name="IdentityCardNumber">IdentityCardNumber</a>

First included in: Main/EmployeeTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IdentityCardNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IdentityCardSeries name="IdentityCardSeries">IdentityCardSeries</a>

First included in: Main/EmployeeTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IdentityCardSeries attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LvPaymTransCodes name="LvPaymTransCodes">LvPaymTransCodes</a>

First included in: Main/EmployeeTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LvPaymTransCodes attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RPayCheck name="RPayCheck">RPayCheck</a>

First included in: Main/EmployeeTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RPayCheck attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#WorkerGroup name="WorkerGroup">WorkerGroup</a>

First included in: Main/EmployeeTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerGroup attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#WorkTypeId name="WorkTypeId">WorkTypeId</a>

First included in: Main/EmployeeTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Main/EmployeeTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_HcmWorkerGroup_FKRelationshipId name="Relationship_HcmWorkerGroup_FKRelationshipId">Relationship_HcmWorkerGroup_FKRelationshipId</a>

First included in: Main/EmployeeTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_HcmWorkerGroup_FKRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../HumanResources/HumanResource/Group/HcmWorkerGroup_RU.md" target="_blank">/core/erp/Tables/HumanResources/HumanResource/Group/HcmWorkerGroup_RU.cdm.json/HcmWorkerGroup_RU</a></td><td><a href="../../../HumanResources/HumanResource/Group/HcmWorkerGroup_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_IdentityCardTable_FKRelationshipId name="Relationship_IdentityCardTable_FKRelationshipId">Relationship_IdentityCardTable_FKRelationshipId</a>

First included in: Main/EmployeeTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_IdentityCardTable_FKRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Main/IdentityCardTable_RU.md" target="_blank">/core/erp/Tables/Common/GAB/Main/IdentityCardTable_RU.cdm.json/IdentityCardTable_RU</a></td><td><a href="../../../Common/GAB/Main/IdentityCardTable_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LvPaymTransCodesRelationshipId name="Relationship_LvPaymTransCodesRelationshipId">Relationship_LvPaymTransCodesRelationshipId</a>

First included in: Main/EmployeeTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LvPaymTransCodesRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Bank/Miscellaneous/LvPaymTransCodes.md" target="_blank">/core/erp/Tables/Finance/Bank/Miscellaneous/LvPaymTransCodes.cdm.json/LvPaymTransCodes</a></td><td><a href="../../Bank/Miscellaneous/LvPaymTransCodes.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_WorkTypeTableRelationshipId name="Relationship_WorkTypeTableRelationshipId">Relationship_WorkTypeTableRelationshipId</a>

First included in: Main/EmployeeTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_WorkTypeTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../APARShared/Main/WorkTypeTable_W.md" target="_blank">/core/erp/Tables/Finance/APARShared/Main/WorkTypeTable_W.cdm.json/WorkTypeTable_W</a></td><td><a href="../../APARShared/Main/WorkTypeTable_W.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Main/EmployeeTable_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CompanyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Ledger/Main/CompanyInfo.md" target="_blank">/core/erp/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
