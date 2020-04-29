---
title: WorkCalendarTimeTemplateEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/29/2020
ms.author: nebanfic
---

# Working time templates

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductionControl/WorkCalendarTimeTemplateEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Working time templates</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[TemplateId](#TemplateId)||<a href="WorkCalendarTimeTemplateEntity.md" target="_blank">ProductionControl/WorkCalendarTimeTemplateEntity</a>|
|[TemplateName](#TemplateName)||<a href="WorkCalendarTimeTemplateEntity.md" target="_blank">ProductionControl/WorkCalendarTimeTemplateEntity</a>|
|[IsPickingUpClosedMonday](#IsPickingUpClosedMonday)||<a href="WorkCalendarTimeTemplateEntity.md" target="_blank">ProductionControl/WorkCalendarTimeTemplateEntity</a>|
|[IsPickingUpClosedTuesday](#IsPickingUpClosedTuesday)||<a href="WorkCalendarTimeTemplateEntity.md" target="_blank">ProductionControl/WorkCalendarTimeTemplateEntity</a>|
|[IsPickingUpClosedWednesday](#IsPickingUpClosedWednesday)||<a href="WorkCalendarTimeTemplateEntity.md" target="_blank">ProductionControl/WorkCalendarTimeTemplateEntity</a>|
|[IsPickingUpClosedThursday](#IsPickingUpClosedThursday)||<a href="WorkCalendarTimeTemplateEntity.md" target="_blank">ProductionControl/WorkCalendarTimeTemplateEntity</a>|
|[IsPickingUpClosedFriday](#IsPickingUpClosedFriday)||<a href="WorkCalendarTimeTemplateEntity.md" target="_blank">ProductionControl/WorkCalendarTimeTemplateEntity</a>|
|[IsPickingUpClosedSaturday](#IsPickingUpClosedSaturday)||<a href="WorkCalendarTimeTemplateEntity.md" target="_blank">ProductionControl/WorkCalendarTimeTemplateEntity</a>|
|[IsPickingUpClosedSunday](#IsPickingUpClosedSunday)||<a href="WorkCalendarTimeTemplateEntity.md" target="_blank">ProductionControl/WorkCalendarTimeTemplateEntity</a>|
|[BackingTable_WorkTimeTableRelationshipId](#BackingTable_WorkTimeTableRelationshipId)||<a href="WorkCalendarTimeTemplateEntity.md" target="_blank">ProductionControl/WorkCalendarTimeTemplateEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="WorkCalendarTimeTemplateEntity.md" target="_blank">ProductionControl/WorkCalendarTimeTemplateEntity</a>|

### <a href=#TemplateId name="TemplateId">TemplateId</a>

First included in: ProductionControl/WorkCalendarTimeTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TemplateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TemplateName name="TemplateName">TemplateName</a>

First included in: ProductionControl/WorkCalendarTimeTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TemplateName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPickingUpClosedMonday name="IsPickingUpClosedMonday">IsPickingUpClosedMonday</a>

First included in: ProductionControl/WorkCalendarTimeTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPickingUpClosedMonday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPickingUpClosedTuesday name="IsPickingUpClosedTuesday">IsPickingUpClosedTuesday</a>

First included in: ProductionControl/WorkCalendarTimeTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPickingUpClosedTuesday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPickingUpClosedWednesday name="IsPickingUpClosedWednesday">IsPickingUpClosedWednesday</a>

First included in: ProductionControl/WorkCalendarTimeTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPickingUpClosedWednesday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPickingUpClosedThursday name="IsPickingUpClosedThursday">IsPickingUpClosedThursday</a>

First included in: ProductionControl/WorkCalendarTimeTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPickingUpClosedThursday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPickingUpClosedFriday name="IsPickingUpClosedFriday">IsPickingUpClosedFriday</a>

First included in: ProductionControl/WorkCalendarTimeTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPickingUpClosedFriday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPickingUpClosedSaturday name="IsPickingUpClosedSaturday">IsPickingUpClosedSaturday</a>

First included in: ProductionControl/WorkCalendarTimeTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPickingUpClosedSaturday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPickingUpClosedSunday name="IsPickingUpClosedSunday">IsPickingUpClosedSunday</a>

First included in: ProductionControl/WorkCalendarTimeTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPickingUpClosedSunday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_WorkTimeTableRelationshipId name="BackingTable_WorkTimeTableRelationshipId">BackingTable_WorkTimeTableRelationshipId</a>

First included in: ProductionControl/WorkCalendarTimeTemplateEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_WorkTimeTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/MasterPlanning/Group/WorkTimeTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/MasterPlanning/Group/WorkTimeTable.cdm.json/WorkTimeTable</a></td><td><a href="../../../Tables/SupplyChain/MasterPlanning/Group/WorkTimeTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProductionControl/WorkCalendarTimeTemplateEntity (this entity)  

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
