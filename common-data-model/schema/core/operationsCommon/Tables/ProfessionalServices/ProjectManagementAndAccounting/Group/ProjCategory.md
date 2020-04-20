---
title: ProjCategory - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# ProjCategory

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Group/ProjCategory.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ProjCategory/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="ProjCategory.md" target="_blank">Group/ProjCategory</a>|
|[Active](#Active)||<a href="ProjCategory.md" target="_blank">Group/ProjCategory</a>|
|[CategoryGroupId](#CategoryGroupId)||<a href="ProjCategory.md" target="_blank">Group/ProjCategory</a>|
|[CategoryId](#CategoryId)||<a href="ProjCategory.md" target="_blank">Group/ProjCategory</a>|
|[CategoryType](#CategoryType)||<a href="ProjCategory.md" target="_blank">Group/ProjCategory</a>|
|[Name](#Name)||<a href="ProjCategory.md" target="_blank">Group/ProjCategory</a>|
|[ProjCategoryEmplOption](#ProjCategoryEmplOption)||<a href="ProjCategory.md" target="_blank">Group/ProjCategory</a>|
|[PSACustPaymentRetention](#PSACustPaymentRetention)||<a href="ProjCategory.md" target="_blank">Group/ProjCategory</a>|
|[PSAIndirectComponent](#PSAIndirectComponent)||<a href="ProjCategory.md" target="_blank">Group/ProjCategory</a>|
|[SetupEstimate](#SetupEstimate)||<a href="ProjCategory.md" target="_blank">Group/ProjCategory</a>|
|[SetupSubscription](#SetupSubscription)||<a href="ProjCategory.md" target="_blank">Group/ProjCategory</a>|
|[TaxItemGroupId](#TaxItemGroupId)||<a href="ProjCategory.md" target="_blank">Group/ProjCategory</a>|
|[TaxServiceCodeId_BR](#TaxServiceCodeId_BR)||<a href="ProjCategory.md" target="_blank">Group/ProjCategory</a>|
|[TaxWithholdItemGroupHeading_TH](#TaxWithholdItemGroupHeading_TH)||<a href="ProjCategory.md" target="_blank">Group/ProjCategory</a>|
|[TsAbsence](#TsAbsence)||<a href="ProjCategory.md" target="_blank">Group/ProjCategory</a>|
|[Exempt_IN](#Exempt_IN)||<a href="ProjCategory.md" target="_blank">Group/ProjCategory</a>|
|[ServiceAccountingCodeTable_IN](#ServiceAccountingCodeTable_IN)||<a href="ProjCategory.md" target="_blank">Group/ProjCategory</a>|
|[TaxRateType](#TaxRateType)||<a href="ProjCategory.md" target="_blank">Group/ProjCategory</a>|
|[DataAreaId](#DataAreaId)||<a href="ProjCategory.md" target="_blank">Group/ProjCategory</a>|
|[Relationship_CategoryTableRelationshipId](#Relationship_CategoryTableRelationshipId)||<a href="ProjCategory.md" target="_blank">Group/ProjCategory</a>|
|[Relationship_ProjCategoryGroupRelationshipId](#Relationship_ProjCategoryGroupRelationshipId)||<a href="ProjCategory.md" target="_blank">Group/ProjCategory</a>|
|[Relationship_TaxItemGroupHeadingRelationshipId](#Relationship_TaxItemGroupHeadingRelationshipId)||<a href="ProjCategory.md" target="_blank">Group/ProjCategory</a>|
|[Relationship_TaxWithholdItemGroupHeading_THRelationshipId](#Relationship_TaxWithholdItemGroupHeading_THRelationshipId)||<a href="ProjCategory.md" target="_blank">Group/ProjCategory</a>|
|[Relationship_ServiceAccountingCodeTable_INRelationshipId](#Relationship_ServiceAccountingCodeTable_INRelationshipId)||<a href="ProjCategory.md" target="_blank">Group/ProjCategory</a>|
|[Relationship_TaxRateTypeRelationshipId](#Relationship_TaxRateTypeRelationshipId)||<a href="ProjCategory.md" target="_blank">Group/ProjCategory</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="ProjCategory.md" target="_blank">Group/ProjCategory</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Group/ProjCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ProjCategory/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Active name="Active">Active</a>

First included in: Group/ProjCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Active attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CategoryGroupId name="CategoryGroupId">CategoryGroupId</a>

First included in: Group/ProjCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CategoryGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CategoryId name="CategoryId">CategoryId</a>

First included in: Group/ProjCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CategoryId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CategoryType name="CategoryType">CategoryType</a>

First included in: Group/ProjCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CategoryType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: Group/ProjCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjCategoryEmplOption name="ProjCategoryEmplOption">ProjCategoryEmplOption</a>

First included in: Group/ProjCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjCategoryEmplOption attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PSACustPaymentRetention name="PSACustPaymentRetention">PSACustPaymentRetention</a>

First included in: Group/ProjCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PSACustPaymentRetention attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#PSAIndirectComponent name="PSAIndirectComponent">PSAIndirectComponent</a>

First included in: Group/ProjCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PSAIndirectComponent attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SetupEstimate name="SetupEstimate">SetupEstimate</a>

First included in: Group/ProjCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SetupEstimate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SetupSubscription name="SetupSubscription">SetupSubscription</a>

First included in: Group/ProjCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SetupSubscription attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#TaxItemGroupId name="TaxItemGroupId">TaxItemGroupId</a>

First included in: Group/ProjCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxItemGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxServiceCodeId_BR name="TaxServiceCodeId_BR">TaxServiceCodeId_BR</a>

First included in: Group/ProjCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxServiceCodeId_BR attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxWithholdItemGroupHeading_TH name="TaxWithholdItemGroupHeading_TH">TaxWithholdItemGroupHeading_TH</a>

First included in: Group/ProjCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdItemGroupHeading_TH attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TsAbsence name="TsAbsence">TsAbsence</a>

First included in: Group/ProjCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TsAbsence attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Exempt_IN name="Exempt_IN">Exempt_IN</a>

First included in: Group/ProjCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Exempt_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ServiceAccountingCodeTable_IN name="ServiceAccountingCodeTable_IN">ServiceAccountingCodeTable_IN</a>

First included in: Group/ProjCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceAccountingCodeTable_IN attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxRateType name="TaxRateType">TaxRateType</a>

First included in: Group/ProjCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxRateType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Group/ProjCategory (this entity)  

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

### <a href=#Relationship_CategoryTableRelationshipId name="Relationship_CategoryTableRelationshipId">Relationship_CategoryTableRelationshipId</a>

First included in: Group/ProjCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CategoryTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Project/Group/CategoryTable.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/Project/Group/CategoryTable.cdm.json/CategoryTable</a></td><td><a href="../../Project/Group/CategoryTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ProjCategoryGroupRelationshipId name="Relationship_ProjCategoryGroupRelationshipId">Relationship_ProjCategoryGroupRelationshipId</a>

First included in: Group/ProjCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ProjCategoryGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="ProjCategoryGroup.md" target="_blank">/core/operationsCommon/Tables/ProfessionalServices/ProjectManagementAndAccounting/Group/ProjCategoryGroup.cdm.json/ProjCategoryGroup</a></td><td><a href="ProjCategoryGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxItemGroupHeadingRelationshipId name="Relationship_TaxItemGroupHeadingRelationshipId">Relationship_TaxItemGroupHeadingRelationshipId</a>

First included in: Group/ProjCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxItemGroupHeadingRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Tax/Group/TaxItemGroupHeading.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxItemGroupHeading.cdm.json/TaxItemGroupHeading</a></td><td><a href="../../../Finance/Tax/Group/TaxItemGroupHeading.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxWithholdItemGroupHeading_THRelationshipId name="Relationship_TaxWithholdItemGroupHeading_THRelationshipId">Relationship_TaxWithholdItemGroupHeading_THRelationshipId</a>

First included in: Group/ProjCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxWithholdItemGroupHeading_THRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Tax/Group/TaxWithholdItemGroupHeading_TH.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxWithholdItemGroupHeading_TH.cdm.json/TaxWithholdItemGroupHeading_TH</a></td><td><a href="../../../Finance/Tax/Group/TaxWithholdItemGroupHeading_TH.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ServiceAccountingCodeTable_INRelationshipId name="Relationship_ServiceAccountingCodeTable_INRelationshipId">Relationship_ServiceAccountingCodeTable_INRelationshipId</a>

First included in: Group/ProjCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ServiceAccountingCodeTable_INRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/APARShared/Main/ServiceAccountingCodeTable_IN.md" target="_blank">/core/operationsCommon/Tables/Finance/APARShared/Main/ServiceAccountingCodeTable_IN.cdm.json/ServiceAccountingCodeTable_IN</a></td><td><a href="../../../Finance/APARShared/Main/ServiceAccountingCodeTable_IN.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxRateTypeRelationshipId name="Relationship_TaxRateTypeRelationshipId">Relationship_TaxRateTypeRelationshipId</a>

First included in: Group/ProjCategory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxRateTypeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Tax/Main/TaxRateType.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Main/TaxRateType.cdm.json/TaxRateType</a></td><td><a href="../../../Finance/Tax/Main/TaxRateType.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Group/ProjCategory (this entity)  

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
