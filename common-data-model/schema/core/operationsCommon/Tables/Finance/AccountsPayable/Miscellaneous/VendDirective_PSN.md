---
title: VendDirective_PSN - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/21/2020
ms.author: nebanfic
---

# VendDirective_PSN

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/AccountsPayable/Miscellaneous/VendDirective_PSN.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[VendDirective_PSN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="VendDirective_PSN.md" target="_blank">Miscellaneous/VendDirective_PSN</a>|
|[AccountantApprovalDate](#AccountantApprovalDate)||<a href="VendDirective_PSN.md" target="_blank">Miscellaneous/VendDirective_PSN</a>|
|[AccountantApprovalStatus](#AccountantApprovalStatus)||<a href="VendDirective_PSN.md" target="_blank">Miscellaneous/VendDirective_PSN</a>|
|[AccountantUserId](#AccountantUserId)||<a href="VendDirective_PSN.md" target="_blank">Miscellaneous/VendDirective_PSN</a>|
|[DirectorApprovalDate](#DirectorApprovalDate)||<a href="VendDirective_PSN.md" target="_blank">Miscellaneous/VendDirective_PSN</a>|
|[DirectorApprovalStatus](#DirectorApprovalStatus)||<a href="VendDirective_PSN.md" target="_blank">Miscellaneous/VendDirective_PSN</a>|
|[DirectorUserId](#DirectorUserId)||<a href="VendDirective_PSN.md" target="_blank">Miscellaneous/VendDirective_PSN</a>|
|[InstanceRelationType](#InstanceRelationType)||<a href="VendDirective_PSN.md" target="_blank">Miscellaneous/VendDirective_PSN</a>|
|[IssueDate](#IssueDate)||<a href="VendDirective_PSN.md" target="_blank">Miscellaneous/VendDirective_PSN</a>|
|[Memo](#Memo)||<a href="VendDirective_PSN.md" target="_blank">Miscellaneous/VendDirective_PSN</a>|
|[DataAreaId](#DataAreaId)||<a href="VendDirective_PSN.md" target="_blank">Miscellaneous/VendDirective_PSN</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="VendDirective_PSN.md" target="_blank">Miscellaneous/VendDirective_PSN</a>|
|[DeductAmount](#DeductAmount)||<a href="VendDirective_PSN.md" target="_blank">Miscellaneous/VendDirective_PSN</a>|
|[DeductCode](#DeductCode)||<a href="VendDirective_PSN.md" target="_blank">Miscellaneous/VendDirective_PSN</a>|
|[RequisitionOrder](#RequisitionOrder)||<a href="VendDirective_PSN.md" target="_blank">Miscellaneous/VendDirective_PSN</a>|
|[VendDirectiveId](#VendDirectiveId)||<a href="VendDirective_PSN.md" target="_blank">Miscellaneous/VendDirective_PSN</a>|
|[VendRoutingSlip_PSN](#VendRoutingSlip_PSN)||<a href="VendDirective_PSN.md" target="_blank">Miscellaneous/VendDirective_PSN</a>|
|[WithholdAmount](#WithholdAmount)||<a href="VendDirective_PSN.md" target="_blank">Miscellaneous/VendDirective_PSN</a>|
|[WithholdCode](#WithholdCode)||<a href="VendDirective_PSN.md" target="_blank">Miscellaneous/VendDirective_PSN</a>|
|[Relationship_VendRoutingSlip_PSNRelationshipId](#Relationship_VendRoutingSlip_PSNRelationshipId)||<a href="VendDirective_PSN.md" target="_blank">Miscellaneous/VendDirective_PSN</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/VendDirective_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[VendDirective_PSN/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AccountantApprovalDate name="AccountantApprovalDate">AccountantApprovalDate</a>

First included in: Miscellaneous/VendDirective_PSN (this entity)  

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

First included in: Miscellaneous/VendDirective_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountantApprovalStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AccountantUserId name="AccountantUserId">AccountantUserId</a>

First included in: Miscellaneous/VendDirective_PSN (this entity)  

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

First included in: Miscellaneous/VendDirective_PSN (this entity)  

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

First included in: Miscellaneous/VendDirective_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DirectorApprovalStatus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DirectorUserId name="DirectorUserId">DirectorUserId</a>

First included in: Miscellaneous/VendDirective_PSN (this entity)  

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

First included in: Miscellaneous/VendDirective_PSN (this entity)  

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

First included in: Miscellaneous/VendDirective_PSN (this entity)  

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

First included in: Miscellaneous/VendDirective_PSN (this entity)  

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

First included in: Miscellaneous/VendDirective_PSN (this entity)  

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

First included in: Miscellaneous/VendDirective_PSN (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DeductAmount name="DeductAmount">DeductAmount</a>

First included in: Miscellaneous/VendDirective_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeductAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DeductCode name="DeductCode">DeductCode</a>

First included in: Miscellaneous/VendDirective_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeductCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequisitionOrder name="RequisitionOrder">RequisitionOrder</a>

First included in: Miscellaneous/VendDirective_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequisitionOrder attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#VendDirectiveId name="VendDirectiveId">VendDirectiveId</a>

First included in: Miscellaneous/VendDirective_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendDirectiveId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendRoutingSlip_PSN name="VendRoutingSlip_PSN">VendRoutingSlip_PSN</a>

First included in: Miscellaneous/VendDirective_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendRoutingSlip_PSN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#WithholdAmount name="WithholdAmount">WithholdAmount</a>

First included in: Miscellaneous/VendDirective_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WithholdAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#WithholdCode name="WithholdCode">WithholdCode</a>

First included in: Miscellaneous/VendDirective_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WithholdCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendRoutingSlip_PSNRelationshipId name="Relationship_VendRoutingSlip_PSNRelationshipId">Relationship_VendRoutingSlip_PSNRelationshipId</a>

First included in: Miscellaneous/VendDirective_PSN (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendRoutingSlip_PSNRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="VendRoutingSlip_PSN.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsPayable/Miscellaneous/VendRoutingSlip_PSN.cdm.json/VendRoutingSlip_PSN</a></td><td><a href="VendRoutingSlip_PSN.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
