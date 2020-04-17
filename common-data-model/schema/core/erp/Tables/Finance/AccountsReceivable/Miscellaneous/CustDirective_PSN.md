---
title: CustDirective_PSN - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# CustDirective_PSN

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Finance/AccountsReceivable/Miscellaneous/CustDirective_PSN.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[CustDirective_PSN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="CustDirective_PSN.md" target="_blank">Miscellaneous/CustDirective_PSN</a>|
|[AccountantApprovalDate](#AccountantApprovalDate)||<a href="CustDirective_PSN.md" target="_blank">Miscellaneous/CustDirective_PSN</a>|
|[AccountantApprovalStatus](#AccountantApprovalStatus)||<a href="CustDirective_PSN.md" target="_blank">Miscellaneous/CustDirective_PSN</a>|
|[AccountantUserId](#AccountantUserId)||<a href="CustDirective_PSN.md" target="_blank">Miscellaneous/CustDirective_PSN</a>|
|[DirectorApprovalDate](#DirectorApprovalDate)||<a href="CustDirective_PSN.md" target="_blank">Miscellaneous/CustDirective_PSN</a>|
|[DirectorApprovalStatus](#DirectorApprovalStatus)||<a href="CustDirective_PSN.md" target="_blank">Miscellaneous/CustDirective_PSN</a>|
|[DirectorUserId](#DirectorUserId)||<a href="CustDirective_PSN.md" target="_blank">Miscellaneous/CustDirective_PSN</a>|
|[InstanceRelationType](#InstanceRelationType)||<a href="CustDirective_PSN.md" target="_blank">Miscellaneous/CustDirective_PSN</a>|
|[IssueDate](#IssueDate)||<a href="CustDirective_PSN.md" target="_blank">Miscellaneous/CustDirective_PSN</a>|
|[Memo](#Memo)||<a href="CustDirective_PSN.md" target="_blank">Miscellaneous/CustDirective_PSN</a>|
|[DataAreaId](#DataAreaId)||<a href="CustDirective_PSN.md" target="_blank">Miscellaneous/CustDirective_PSN</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="CustDirective_PSN.md" target="_blank">Miscellaneous/CustDirective_PSN</a>|
|[CustDirectiveBudgetaryAccount](#CustDirectiveBudgetaryAccount)||<a href="CustDirective_PSN.md" target="_blank">Miscellaneous/CustDirective_PSN</a>|
|[CustDirectiveId](#CustDirectiveId)||<a href="CustDirective_PSN.md" target="_blank">Miscellaneous/CustDirective_PSN</a>|
|[CustRoutingSlip_PSN](#CustRoutingSlip_PSN)||<a href="CustDirective_PSN.md" target="_blank">Miscellaneous/CustDirective_PSN</a>|
|[Relationship_CustRoutingSlip_PSNRelationshipId](#Relationship_CustRoutingSlip_PSNRelationshipId)||<a href="CustDirective_PSN.md" target="_blank">Miscellaneous/CustDirective_PSN</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/CustDirective_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[CustDirective_PSN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AccountantApprovalDate name="AccountantApprovalDate">AccountantApprovalDate</a>

First included in: Miscellaneous/CustDirective_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountantApprovalDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#AccountantApprovalStatus name="AccountantApprovalStatus">AccountantApprovalStatus</a>

First included in: Miscellaneous/CustDirective_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountantApprovalStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AccountantUserId name="AccountantUserId">AccountantUserId</a>

First included in: Miscellaneous/CustDirective_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountantUserId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DirectorApprovalDate name="DirectorApprovalDate">DirectorApprovalDate</a>

First included in: Miscellaneous/CustDirective_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DirectorApprovalDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#DirectorApprovalStatus name="DirectorApprovalStatus">DirectorApprovalStatus</a>

First included in: Miscellaneous/CustDirective_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DirectorApprovalStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DirectorUserId name="DirectorUserId">DirectorUserId</a>

First included in: Miscellaneous/CustDirective_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DirectorUserId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InstanceRelationType name="InstanceRelationType">InstanceRelationType</a>

First included in: Miscellaneous/CustDirective_PSN (this entity)  

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

### <a href=#IssueDate name="IssueDate">IssueDate</a>

First included in: Miscellaneous/CustDirective_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IssueDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#Memo name="Memo">Memo</a>

First included in: Miscellaneous/CustDirective_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Memo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Miscellaneous/CustDirective_PSN (this entity)  

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

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Miscellaneous/CustDirective_PSN (this entity)  

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

### <a href=#CustDirectiveBudgetaryAccount name="CustDirectiveBudgetaryAccount">CustDirectiveBudgetaryAccount</a>

First included in: Miscellaneous/CustDirective_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustDirectiveBudgetaryAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustDirectiveId name="CustDirectiveId">CustDirectiveId</a>

First included in: Miscellaneous/CustDirective_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustDirectiveId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustRoutingSlip_PSN name="CustRoutingSlip_PSN">CustRoutingSlip_PSN</a>

First included in: Miscellaneous/CustDirective_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustRoutingSlip_PSN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_CustRoutingSlip_PSNRelationshipId name="Relationship_CustRoutingSlip_PSNRelationshipId">Relationship_CustRoutingSlip_PSNRelationshipId</a>

First included in: Miscellaneous/CustDirective_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustRoutingSlip_PSNRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="CustRoutingSlip_PSN.md" target="_blank">/core/erp/Tables/Finance/AccountsReceivable/Miscellaneous/CustRoutingSlip_PSN.cdm.json/CustRoutingSlip_PSN</a></td><td><a href="CustRoutingSlip_PSN.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
