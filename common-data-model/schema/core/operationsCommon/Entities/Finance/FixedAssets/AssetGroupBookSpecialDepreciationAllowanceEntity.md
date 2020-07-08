---
title: AssetGroupBookSpecialDepreciationAllowanceEntity in FixedAssets - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/8/2020
ms.author: nebanfic
---

# Fixed asset group/book special depreciation allowance in FixedAssets(AssetGroupBookSpecialDepreciationAllowanceEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/FixedAssets/AssetGroupBookSpecialDepreciationAllowanceEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Fixed asset group/book special depreciation allowance</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[GroupId](#GroupId)||<a href="AssetGroupBookSpecialDepreciationAllowanceEntity.md" target="_blank">FixedAssets/AssetGroupBookSpecialDepreciationAllowanceEntity</a>|
|[BookId](#BookId)||<a href="AssetGroupBookSpecialDepreciationAllowanceEntity.md" target="_blank">FixedAssets/AssetGroupBookSpecialDepreciationAllowanceEntity</a>|
|[SpecialDepreciationAllowanceId](#SpecialDepreciationAllowanceId)||<a href="AssetGroupBookSpecialDepreciationAllowanceEntity.md" target="_blank">FixedAssets/AssetGroupBookSpecialDepreciationAllowanceEntity</a>|
|[Description](#Description)||<a href="AssetGroupBookSpecialDepreciationAllowanceEntity.md" target="_blank">FixedAssets/AssetGroupBookSpecialDepreciationAllowanceEntity</a>|
|[Priority](#Priority)||<a href="AssetGroupBookSpecialDepreciationAllowanceEntity.md" target="_blank">FixedAssets/AssetGroupBookSpecialDepreciationAllowanceEntity</a>|
|[Amount](#Amount)||<a href="AssetGroupBookSpecialDepreciationAllowanceEntity.md" target="_blank">FixedAssets/AssetGroupBookSpecialDepreciationAllowanceEntity</a>|
|[Percentage](#Percentage)||<a href="AssetGroupBookSpecialDepreciationAllowanceEntity.md" target="_blank">FixedAssets/AssetGroupBookSpecialDepreciationAllowanceEntity</a>|
|[Relationship_AssetBookTableRelationshipId](#Relationship_AssetBookTableRelationshipId)||<a href="AssetGroupBookSpecialDepreciationAllowanceEntity.md" target="_blank">FixedAssets/AssetGroupBookSpecialDepreciationAllowanceEntity</a>|
|[Relationship_AssetGroupRelationshipId](#Relationship_AssetGroupRelationshipId)||<a href="AssetGroupBookSpecialDepreciationAllowanceEntity.md" target="_blank">FixedAssets/AssetGroupBookSpecialDepreciationAllowanceEntity</a>|
|[Relationship_AssetSpecialDepreciationAllowanceEntityRelationshipId](#Relationship_AssetSpecialDepreciationAllowanceEntityRelationshipId)||<a href="AssetGroupBookSpecialDepreciationAllowanceEntity.md" target="_blank">FixedAssets/AssetGroupBookSpecialDepreciationAllowanceEntity</a>|
|[BackingTable_AssetGroupSetupBonusRelationshipId](#BackingTable_AssetGroupSetupBonusRelationshipId)||<a href="AssetGroupBookSpecialDepreciationAllowanceEntity.md" target="_blank">FixedAssets/AssetGroupBookSpecialDepreciationAllowanceEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="AssetGroupBookSpecialDepreciationAllowanceEntity.md" target="_blank">FixedAssets/AssetGroupBookSpecialDepreciationAllowanceEntity</a>|

### <a href=#GroupId name="GroupId">GroupId</a>

First included in: FixedAssets/AssetGroupBookSpecialDepreciationAllowanceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BookId name="BookId">BookId</a>

First included in: FixedAssets/AssetGroupBookSpecialDepreciationAllowanceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BookId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SpecialDepreciationAllowanceId name="SpecialDepreciationAllowanceId">SpecialDepreciationAllowanceId</a>

First included in: FixedAssets/AssetGroupBookSpecialDepreciationAllowanceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SpecialDepreciationAllowanceId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: FixedAssets/AssetGroupBookSpecialDepreciationAllowanceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Description attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Priority name="Priority">Priority</a>

First included in: FixedAssets/AssetGroupBookSpecialDepreciationAllowanceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Priority attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Amount name="Amount">Amount</a>

First included in: FixedAssets/AssetGroupBookSpecialDepreciationAllowanceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Amount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Percentage name="Percentage">Percentage</a>

First included in: FixedAssets/AssetGroupBookSpecialDepreciationAllowanceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Percentage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_AssetBookTableRelationshipId name="Relationship_AssetBookTableRelationshipId">Relationship_AssetBookTableRelationshipId</a>

First included in: FixedAssets/AssetGroupBookSpecialDepreciationAllowanceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetBookTableRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_AssetGroupRelationshipId name="Relationship_AssetGroupRelationshipId">Relationship_AssetGroupRelationshipId</a>

First included in: FixedAssets/AssetGroupBookSpecialDepreciationAllowanceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetGroupRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_AssetSpecialDepreciationAllowanceEntityRelationshipId name="Relationship_AssetSpecialDepreciationAllowanceEntityRelationshipId">Relationship_AssetSpecialDepreciationAllowanceEntityRelationshipId</a>

First included in: FixedAssets/AssetGroupBookSpecialDepreciationAllowanceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AssetSpecialDepreciationAllowanceEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_AssetGroupSetupBonusRelationshipId name="BackingTable_AssetGroupSetupBonusRelationshipId">BackingTable_AssetGroupSetupBonusRelationshipId</a>

First included in: FixedAssets/AssetGroupBookSpecialDepreciationAllowanceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_AssetGroupSetupBonusRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/FixedAssets/Miscellaneous/AssetGroupSetupBonus.md" target="_blank">/core/operationsCommon/Tables/Finance/FixedAssets/Miscellaneous/AssetGroupSetupBonus.cdm.json/AssetGroupSetupBonus</a></td><td><a href="../../../Tables/Finance/FixedAssets/Miscellaneous/AssetGroupSetupBonus.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: FixedAssets/AssetGroupBookSpecialDepreciationAllowanceEntity (this entity)  

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
