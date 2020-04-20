---
title: RetailStaffPermissionGroup - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# RetailStaffPermissionGroup

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Commerce/Retail/Group/RetailStaffPermissionGroup.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailStaffPermissionGroup/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailStaffPermissionGroup.md" target="_blank">Group/RetailStaffPermissionGroup</a>|
|[allowChangeNoVoid](#allowChangeNoVoid)||<a href="RetailStaffPermissionGroup.md" target="_blank">Group/RetailStaffPermissionGroup</a>|
|[allowFloatingTenderDeclaration](#allowFloatingTenderDeclaration)||<a href="RetailStaffPermissionGroup.md" target="_blank">Group/RetailStaffPermissionGroup</a>|
|[allowOpenDrawerOnly](#allowOpenDrawerOnly)||<a href="RetailStaffPermissionGroup.md" target="_blank">Group/RetailStaffPermissionGroup</a>|
|[allowPriceOverride](#allowPriceOverride)||<a href="RetailStaffPermissionGroup.md" target="_blank">Group/RetailStaffPermissionGroup</a>|
|[allowTenderDeclaration](#allowTenderDeclaration)||<a href="RetailStaffPermissionGroup.md" target="_blank">Group/RetailStaffPermissionGroup</a>|
|[allowTransactionSuspension](#allowTransactionSuspension)||<a href="RetailStaffPermissionGroup.md" target="_blank">Group/RetailStaffPermissionGroup</a>|
|[allowTransactionVoiding](#allowTransactionVoiding)||<a href="RetailStaffPermissionGroup.md" target="_blank">Group/RetailStaffPermissionGroup</a>|
|[allowXReportPrinting](#allowXReportPrinting)||<a href="RetailStaffPermissionGroup.md" target="_blank">Group/RetailStaffPermissionGroup</a>|
|[AllowZReportPrinting](#AllowZReportPrinting)||<a href="RetailStaffPermissionGroup.md" target="_blank">Group/RetailStaffPermissionGroup</a>|
|[managerPrivileges](#managerPrivileges)||<a href="RetailStaffPermissionGroup.md" target="_blank">Group/RetailStaffPermissionGroup</a>|
|[maximumDiscountPct](#maximumDiscountPct)||<a href="RetailStaffPermissionGroup.md" target="_blank">Group/RetailStaffPermissionGroup</a>|
|[maxLineDiscountAmount](#maxLineDiscountAmount)||<a href="RetailStaffPermissionGroup.md" target="_blank">Group/RetailStaffPermissionGroup</a>|
|[maxTotalDiscountAmount](#maxTotalDiscountAmount)||<a href="RetailStaffPermissionGroup.md" target="_blank">Group/RetailStaffPermissionGroup</a>|
|[maxTotalDiscountPct](#maxTotalDiscountPct)||<a href="RetailStaffPermissionGroup.md" target="_blank">Group/RetailStaffPermissionGroup</a>|
|[name](#name)||<a href="RetailStaffPermissionGroup.md" target="_blank">Group/RetailStaffPermissionGroup</a>|
|[permissionGroupId](#permissionGroupId)||<a href="RetailStaffPermissionGroup.md" target="_blank">Group/RetailStaffPermissionGroup</a>|
|[DataAreaId](#DataAreaId)||<a href="RetailStaffPermissionGroup.md" target="_blank">Group/RetailStaffPermissionGroup</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="RetailStaffPermissionGroup.md" target="_blank">Group/RetailStaffPermissionGroup</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Group/RetailStaffPermissionGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailStaffPermissionGroup/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#allowChangeNoVoid name="allowChangeNoVoid">allowChangeNoVoid</a>

First included in: Group/RetailStaffPermissionGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the allowChangeNoVoid attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#allowFloatingTenderDeclaration name="allowFloatingTenderDeclaration">allowFloatingTenderDeclaration</a>

First included in: Group/RetailStaffPermissionGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the allowFloatingTenderDeclaration attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#allowOpenDrawerOnly name="allowOpenDrawerOnly">allowOpenDrawerOnly</a>

First included in: Group/RetailStaffPermissionGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the allowOpenDrawerOnly attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#allowPriceOverride name="allowPriceOverride">allowPriceOverride</a>

First included in: Group/RetailStaffPermissionGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the allowPriceOverride attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#allowTenderDeclaration name="allowTenderDeclaration">allowTenderDeclaration</a>

First included in: Group/RetailStaffPermissionGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the allowTenderDeclaration attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#allowTransactionSuspension name="allowTransactionSuspension">allowTransactionSuspension</a>

First included in: Group/RetailStaffPermissionGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the allowTransactionSuspension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#allowTransactionVoiding name="allowTransactionVoiding">allowTransactionVoiding</a>

First included in: Group/RetailStaffPermissionGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the allowTransactionVoiding attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#allowXReportPrinting name="allowXReportPrinting">allowXReportPrinting</a>

First included in: Group/RetailStaffPermissionGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the allowXReportPrinting attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AllowZReportPrinting name="AllowZReportPrinting">AllowZReportPrinting</a>

First included in: Group/RetailStaffPermissionGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowZReportPrinting attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#managerPrivileges name="managerPrivileges">managerPrivileges</a>

First included in: Group/RetailStaffPermissionGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the managerPrivileges attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#maximumDiscountPct name="maximumDiscountPct">maximumDiscountPct</a>

First included in: Group/RetailStaffPermissionGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the maximumDiscountPct attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#maxLineDiscountAmount name="maxLineDiscountAmount">maxLineDiscountAmount</a>

First included in: Group/RetailStaffPermissionGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the maxLineDiscountAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#maxTotalDiscountAmount name="maxTotalDiscountAmount">maxTotalDiscountAmount</a>

First included in: Group/RetailStaffPermissionGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the maxTotalDiscountAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#maxTotalDiscountPct name="maxTotalDiscountPct">maxTotalDiscountPct</a>

First included in: Group/RetailStaffPermissionGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the maxTotalDiscountPct attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#name name="name">name</a>

First included in: Group/RetailStaffPermissionGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#permissionGroupId name="permissionGroupId">permissionGroupId</a>

First included in: Group/RetailStaffPermissionGroup (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the permissionGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Group/RetailStaffPermissionGroup (this entity)  

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

First included in: Group/RetailStaffPermissionGroup (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
