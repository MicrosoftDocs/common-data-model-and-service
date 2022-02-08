---
title: TMSTransportationRouteScheduleEntity in Transportation - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Transportation route schedules in Transportation(TMSTransportationRouteScheduleEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/Transportation/TMSTransportationRouteScheduleEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Transportation route schedules</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[IsRouteRecurrenceActive](#IsRouteRecurrenceActive)||<a href="TMSTransportationRouteScheduleEntity.md" target="_blank">Transportation/TMSTransportationRouteScheduleEntity</a>|
|[EffectiveStartDateTime](#EffectiveStartDateTime)||<a href="TMSTransportationRouteScheduleEntity.md" target="_blank">Transportation/TMSTransportationRouteScheduleEntity</a>|
|[WillRouteGenerationScheduleOnFriday](#WillRouteGenerationScheduleOnFriday)||<a href="TMSTransportationRouteScheduleEntity.md" target="_blank">Transportation/TMSTransportationRouteScheduleEntity</a>|
|[WillRouteGenerationScheduleOnMonday](#WillRouteGenerationScheduleOnMonday)||<a href="TMSTransportationRouteScheduleEntity.md" target="_blank">Transportation/TMSTransportationRouteScheduleEntity</a>|
|[ScheduleName](#ScheduleName)||<a href="TMSTransportationRouteScheduleEntity.md" target="_blank">Transportation/TMSTransportationRouteScheduleEntity</a>|
|[WillRouteGenerationScheduleOnSaturday](#WillRouteGenerationScheduleOnSaturday)||<a href="TMSTransportationRouteScheduleEntity.md" target="_blank">Transportation/TMSTransportationRouteScheduleEntity</a>|
|[WillRouteGenerationScheduleOnSunday](#WillRouteGenerationScheduleOnSunday)||<a href="TMSTransportationRouteScheduleEntity.md" target="_blank">Transportation/TMSTransportationRouteScheduleEntity</a>|
|[WillRouteGenerationScheduleOnThursday](#WillRouteGenerationScheduleOnThursday)||<a href="TMSTransportationRouteScheduleEntity.md" target="_blank">Transportation/TMSTransportationRouteScheduleEntity</a>|
|[WillRouteGenerationScheduleOnTuesday](#WillRouteGenerationScheduleOnTuesday)||<a href="TMSTransportationRouteScheduleEntity.md" target="_blank">Transportation/TMSTransportationRouteScheduleEntity</a>|
|[WillRouteGenerationScheduleOnWednesday](#WillRouteGenerationScheduleOnWednesday)||<a href="TMSTransportationRouteScheduleEntity.md" target="_blank">Transportation/TMSTransportationRouteScheduleEntity</a>|
|[WeeklyIntervalDays](#WeeklyIntervalDays)||<a href="TMSTransportationRouteScheduleEntity.md" target="_blank">Transportation/TMSTransportationRouteScheduleEntity</a>|
|[EffectiveEndDateTime](#EffectiveEndDateTime)||<a href="TMSTransportationRouteScheduleEntity.md" target="_blank">Transportation/TMSTransportationRouteScheduleEntity</a>|
|[LoadTemplateId](#LoadTemplateId)||<a href="TMSTransportationRouteScheduleEntity.md" target="_blank">Transportation/TMSTransportationRouteScheduleEntity</a>|
|[TransportationRoutePlanId](#TransportationRoutePlanId)||<a href="TMSTransportationRouteScheduleEntity.md" target="_blank">Transportation/TMSTransportationRouteScheduleEntity</a>|
|[ReferenceTableId](#ReferenceTableId)||<a href="TMSTransportationRouteScheduleEntity.md" target="_blank">Transportation/TMSTransportationRouteScheduleEntity</a>|
|[Relationship_TransportationRoutePlanRelationshipId](#Relationship_TransportationRoutePlanRelationshipId)||<a href="TMSTransportationRouteScheduleEntity.md" target="_blank">Transportation/TMSTransportationRouteScheduleEntity</a>|
|[Relationship_LoadTemplateRelationshipId](#Relationship_LoadTemplateRelationshipId)||<a href="TMSTransportationRouteScheduleEntity.md" target="_blank">Transportation/TMSTransportationRouteScheduleEntity</a>|
|[BackingTable_TMSRouteScheduleRelationshipId](#BackingTable_TMSRouteScheduleRelationshipId)||<a href="TMSTransportationRouteScheduleEntity.md" target="_blank">Transportation/TMSTransportationRouteScheduleEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="TMSTransportationRouteScheduleEntity.md" target="_blank">Transportation/TMSTransportationRouteScheduleEntity</a>|

### <a href=#IsRouteRecurrenceActive name="IsRouteRecurrenceActive">IsRouteRecurrenceActive</a>

First included in: Transportation/TMSTransportationRouteScheduleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsRouteRecurrenceActive attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EffectiveStartDateTime name="EffectiveStartDateTime">EffectiveStartDateTime</a>

First included in: Transportation/TMSTransportationRouteScheduleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EffectiveStartDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillRouteGenerationScheduleOnFriday name="WillRouteGenerationScheduleOnFriday">WillRouteGenerationScheduleOnFriday</a>

First included in: Transportation/TMSTransportationRouteScheduleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillRouteGenerationScheduleOnFriday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillRouteGenerationScheduleOnMonday name="WillRouteGenerationScheduleOnMonday">WillRouteGenerationScheduleOnMonday</a>

First included in: Transportation/TMSTransportationRouteScheduleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillRouteGenerationScheduleOnMonday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ScheduleName name="ScheduleName">ScheduleName</a>

First included in: Transportation/TMSTransportationRouteScheduleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ScheduleName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillRouteGenerationScheduleOnSaturday name="WillRouteGenerationScheduleOnSaturday">WillRouteGenerationScheduleOnSaturday</a>

First included in: Transportation/TMSTransportationRouteScheduleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillRouteGenerationScheduleOnSaturday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillRouteGenerationScheduleOnSunday name="WillRouteGenerationScheduleOnSunday">WillRouteGenerationScheduleOnSunday</a>

First included in: Transportation/TMSTransportationRouteScheduleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillRouteGenerationScheduleOnSunday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillRouteGenerationScheduleOnThursday name="WillRouteGenerationScheduleOnThursday">WillRouteGenerationScheduleOnThursday</a>

First included in: Transportation/TMSTransportationRouteScheduleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillRouteGenerationScheduleOnThursday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillRouteGenerationScheduleOnTuesday name="WillRouteGenerationScheduleOnTuesday">WillRouteGenerationScheduleOnTuesday</a>

First included in: Transportation/TMSTransportationRouteScheduleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillRouteGenerationScheduleOnTuesday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WillRouteGenerationScheduleOnWednesday name="WillRouteGenerationScheduleOnWednesday">WillRouteGenerationScheduleOnWednesday</a>

First included in: Transportation/TMSTransportationRouteScheduleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WillRouteGenerationScheduleOnWednesday attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WeeklyIntervalDays name="WeeklyIntervalDays">WeeklyIntervalDays</a>

First included in: Transportation/TMSTransportationRouteScheduleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WeeklyIntervalDays attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EffectiveEndDateTime name="EffectiveEndDateTime">EffectiveEndDateTime</a>

First included in: Transportation/TMSTransportationRouteScheduleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EffectiveEndDateTime attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LoadTemplateId name="LoadTemplateId">LoadTemplateId</a>

First included in: Transportation/TMSTransportationRouteScheduleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LoadTemplateId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransportationRoutePlanId name="TransportationRoutePlanId">TransportationRoutePlanId</a>

First included in: Transportation/TMSTransportationRouteScheduleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransportationRoutePlanId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReferenceTableId name="ReferenceTableId">ReferenceTableId</a>

First included in: Transportation/TMSTransportationRouteScheduleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReferenceTableId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TransportationRoutePlanRelationshipId name="Relationship_TransportationRoutePlanRelationshipId">Relationship_TransportationRoutePlanRelationshipId</a>

First included in: Transportation/TMSTransportationRouteScheduleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TransportationRoutePlanRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_LoadTemplateRelationshipId name="Relationship_LoadTemplateRelationshipId">Relationship_LoadTemplateRelationshipId</a>

First included in: Transportation/TMSTransportationRouteScheduleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LoadTemplateRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_TMSRouteScheduleRelationshipId name="BackingTable_TMSRouteScheduleRelationshipId">BackingTable_TMSRouteScheduleRelationshipId</a>

First included in: Transportation/TMSTransportationRouteScheduleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_TMSRouteScheduleRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/Transportation/Group/TMSRouteSchedule.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Transportation/Group/TMSRouteSchedule.cdm.json/TMSRouteSchedule</a></td><td><a href="../../../Tables/SupplyChain/Transportation/Group/TMSRouteSchedule.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: Transportation/TMSTransportationRouteScheduleEntity (this entity)  

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
