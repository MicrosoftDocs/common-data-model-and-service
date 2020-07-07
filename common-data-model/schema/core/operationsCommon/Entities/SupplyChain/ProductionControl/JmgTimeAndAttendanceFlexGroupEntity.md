---
title: JmgTimeAndAttendanceFlexGroupEntity in ProductionControl - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/7/2020
ms.author: nebanfic
---

# Time and attendance flex groups in ProductionControl

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductionControl/JmgTimeAndAttendanceFlexGroupEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Time and attendance flex groups</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[FlexGroupId](#FlexGroupId)||<a href="JmgTimeAndAttendanceFlexGroupEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceFlexGroupEntity</a>|
|[Description](#Description)||<a href="JmgTimeAndAttendanceFlexGroupEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceFlexGroupEntity</a>|
|[IsFlexMaximumBalanceAdjusted](#IsFlexMaximumBalanceAdjusted)||<a href="JmgTimeAndAttendanceFlexGroupEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceFlexGroupEntity</a>|
|[IsFlexMinimumBalanceAdjusted](#IsFlexMinimumBalanceAdjusted)||<a href="JmgTimeAndAttendanceFlexGroupEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceFlexGroupEntity</a>|
|[FlexMaximumPayTypeCode](#FlexMaximumPayTypeCode)||<a href="JmgTimeAndAttendanceFlexGroupEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceFlexGroupEntity</a>|
|[FlexMinumumPayTypeCode](#FlexMinumumPayTypeCode)||<a href="JmgTimeAndAttendanceFlexGroupEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceFlexGroupEntity</a>|
|[PayTypeCodeForMaximumFlexBalance](#PayTypeCodeForMaximumFlexBalance)||<a href="JmgTimeAndAttendanceFlexGroupEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceFlexGroupEntity</a>|
|[PayTypeCodeForMinimumFlexBalance](#PayTypeCodeForMinimumFlexBalance)||<a href="JmgTimeAndAttendanceFlexGroupEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceFlexGroupEntity</a>|
|[PayFactorForAdjustedMaximumBalance](#PayFactorForAdjustedMaximumBalance)||<a href="JmgTimeAndAttendanceFlexGroupEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceFlexGroupEntity</a>|
|[PayFactorForAdjustedMinimumBalance](#PayFactorForAdjustedMinimumBalance)||<a href="JmgTimeAndAttendanceFlexGroupEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceFlexGroupEntity</a>|
|[MaximumFlexBalanceInTimePresentationUnits](#MaximumFlexBalanceInTimePresentationUnits)||<a href="JmgTimeAndAttendanceFlexGroupEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceFlexGroupEntity</a>|
|[MinimunFlexBalanceInTimePresentationUnits](#MinimunFlexBalanceInTimePresentationUnits)||<a href="JmgTimeAndAttendanceFlexGroupEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceFlexGroupEntity</a>|
|[IsFlexBalanceCalculatedFromPayTypeCode](#IsFlexBalanceCalculatedFromPayTypeCode)||<a href="JmgTimeAndAttendanceFlexGroupEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceFlexGroupEntity</a>|
|[BackingTable_JmgFlexGroupRelationshipId](#BackingTable_JmgFlexGroupRelationshipId)||<a href="JmgTimeAndAttendanceFlexGroupEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceFlexGroupEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="JmgTimeAndAttendanceFlexGroupEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendanceFlexGroupEntity</a>|

### <a href=#FlexGroupId name="FlexGroupId">FlexGroupId</a>

First included in: ProductionControl/JmgTimeAndAttendanceFlexGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FlexGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Description name="Description">Description</a>

First included in: ProductionControl/JmgTimeAndAttendanceFlexGroupEntity (this entity)  

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

### <a href=#IsFlexMaximumBalanceAdjusted name="IsFlexMaximumBalanceAdjusted">IsFlexMaximumBalanceAdjusted</a>

First included in: ProductionControl/JmgTimeAndAttendanceFlexGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsFlexMaximumBalanceAdjusted attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsFlexMinimumBalanceAdjusted name="IsFlexMinimumBalanceAdjusted">IsFlexMinimumBalanceAdjusted</a>

First included in: ProductionControl/JmgTimeAndAttendanceFlexGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsFlexMinimumBalanceAdjusted attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FlexMaximumPayTypeCode name="FlexMaximumPayTypeCode">FlexMaximumPayTypeCode</a>

First included in: ProductionControl/JmgTimeAndAttendanceFlexGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FlexMaximumPayTypeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#FlexMinumumPayTypeCode name="FlexMinumumPayTypeCode">FlexMinumumPayTypeCode</a>

First included in: ProductionControl/JmgTimeAndAttendanceFlexGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FlexMinumumPayTypeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayTypeCodeForMaximumFlexBalance name="PayTypeCodeForMaximumFlexBalance">PayTypeCodeForMaximumFlexBalance</a>

First included in: ProductionControl/JmgTimeAndAttendanceFlexGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayTypeCodeForMaximumFlexBalance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayTypeCodeForMinimumFlexBalance name="PayTypeCodeForMinimumFlexBalance">PayTypeCodeForMinimumFlexBalance</a>

First included in: ProductionControl/JmgTimeAndAttendanceFlexGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayTypeCodeForMinimumFlexBalance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayFactorForAdjustedMaximumBalance name="PayFactorForAdjustedMaximumBalance">PayFactorForAdjustedMaximumBalance</a>

First included in: ProductionControl/JmgTimeAndAttendanceFlexGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayFactorForAdjustedMaximumBalance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PayFactorForAdjustedMinimumBalance name="PayFactorForAdjustedMinimumBalance">PayFactorForAdjustedMinimumBalance</a>

First included in: ProductionControl/JmgTimeAndAttendanceFlexGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayFactorForAdjustedMinimumBalance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumFlexBalanceInTimePresentationUnits name="MaximumFlexBalanceInTimePresentationUnits">MaximumFlexBalanceInTimePresentationUnits</a>

First included in: ProductionControl/JmgTimeAndAttendanceFlexGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumFlexBalanceInTimePresentationUnits attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinimunFlexBalanceInTimePresentationUnits name="MinimunFlexBalanceInTimePresentationUnits">MinimunFlexBalanceInTimePresentationUnits</a>

First included in: ProductionControl/JmgTimeAndAttendanceFlexGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimunFlexBalanceInTimePresentationUnits attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsFlexBalanceCalculatedFromPayTypeCode name="IsFlexBalanceCalculatedFromPayTypeCode">IsFlexBalanceCalculatedFromPayTypeCode</a>

First included in: ProductionControl/JmgTimeAndAttendanceFlexGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsFlexBalanceCalculatedFromPayTypeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_JmgFlexGroupRelationshipId name="BackingTable_JmgFlexGroupRelationshipId">BackingTable_JmgFlexGroupRelationshipId</a>

First included in: ProductionControl/JmgTimeAndAttendanceFlexGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_JmgFlexGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProductionControl/Group/JmgFlexGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/Group/JmgFlexGroup.cdm.json/JmgFlexGroup</a></td><td><a href="../../../Tables/SupplyChain/ProductionControl/Group/JmgFlexGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProductionControl/JmgTimeAndAttendanceFlexGroupEntity (this entity)  

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
