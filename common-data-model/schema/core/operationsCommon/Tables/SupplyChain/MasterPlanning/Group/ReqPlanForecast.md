---
title: ReqPlanForecast in Group - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Forecast plan setup in Group(ReqPlanForecast)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/MasterPlanning/Group/ReqPlanForecast.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ReqPlanForecast/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Forecast plan setup</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="ReqPlanForecast.md" target="_blank">Group/ReqPlanForecast</a>|
|[IssueMargin](#IssueMargin)||<a href="ReqPlanForecast.md" target="_blank">Group/ReqPlanForecast</a>|
|[Name](#Name)||<a href="ReqPlanForecast.md" target="_blank">Group/ReqPlanForecast</a>|
|[OrderingMargin](#OrderingMargin)||<a href="ReqPlanForecast.md" target="_blank">Group/ReqPlanForecast</a>|
|[PlannedOrderSequenceRecId](#PlannedOrderSequenceRecId)||<a href="ReqPlanForecast.md" target="_blank">Group/ReqPlanForecast</a>|
|[ReceiptMargin](#ReceiptMargin)||<a href="ReqPlanForecast.md" target="_blank">Group/ReqPlanForecast</a>|
|[ReqPlanIdForecast](#ReqPlanIdForecast)||<a href="ReqPlanForecast.md" target="_blank">Group/ReqPlanForecast</a>|
|[ReqPlanSequenceRecId](#ReqPlanSequenceRecId)||<a href="ReqPlanForecast.md" target="_blank">Group/ReqPlanForecast</a>|
|[SkipCovCalc](#SkipCovCalc)||<a href="ReqPlanForecast.md" target="_blank">Group/ReqPlanForecast</a>|
|[TimeFenceCapacity](#TimeFenceCapacity)||<a href="ReqPlanForecast.md" target="_blank">Group/ReqPlanForecast</a>|
|[TimeFenceCov](#TimeFenceCov)||<a href="ReqPlanForecast.md" target="_blank">Group/ReqPlanForecast</a>|
|[TimeFenceExplosion](#TimeFenceExplosion)||<a href="ReqPlanForecast.md" target="_blank">Group/ReqPlanForecast</a>|
|[DataAreaId](#DataAreaId)||<a href="ReqPlanForecast.md" target="_blank">Group/ReqPlanForecast</a>|
|[Relationship_PlannedOrderNumberSequenceRelationshipId](#Relationship_PlannedOrderNumberSequenceRelationshipId)||<a href="ReqPlanForecast.md" target="_blank">Group/ReqPlanForecast</a>|
|[Relationship_ReqLogRelationshipId](#Relationship_ReqLogRelationshipId)||<a href="ReqPlanForecast.md" target="_blank">Group/ReqPlanForecast</a>|
|[Relationship_ReqPlanRelationshipId](#Relationship_ReqPlanRelationshipId)||<a href="ReqPlanForecast.md" target="_blank">Group/ReqPlanForecast</a>|
|[Relationship_ReqPlanNumberSequenceRelationshipId](#Relationship_ReqPlanNumberSequenceRelationshipId)||<a href="ReqPlanForecast.md" target="_blank">Group/ReqPlanForecast</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="ReqPlanForecast.md" target="_blank">Group/ReqPlanForecast</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Group/ReqPlanForecast (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[ReqPlanForecast/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#IssueMargin name="IssueMargin">IssueMargin</a>

First included in: Group/ReqPlanForecast (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IssueMargin attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: Group/ReqPlanForecast (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OrderingMargin name="OrderingMargin">OrderingMargin</a>

First included in: Group/ReqPlanForecast (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OrderingMargin attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PlannedOrderSequenceRecId name="PlannedOrderSequenceRecId">PlannedOrderSequenceRecId</a>

First included in: Group/ReqPlanForecast (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PlannedOrderSequenceRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ReceiptMargin name="ReceiptMargin">ReceiptMargin</a>

First included in: Group/ReqPlanForecast (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReceiptMargin attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ReqPlanIdForecast name="ReqPlanIdForecast">ReqPlanIdForecast</a>

First included in: Group/ReqPlanForecast (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReqPlanIdForecast attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReqPlanSequenceRecId name="ReqPlanSequenceRecId">ReqPlanSequenceRecId</a>

First included in: Group/ReqPlanForecast (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReqPlanSequenceRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SkipCovCalc name="SkipCovCalc">SkipCovCalc</a>

First included in: Group/ReqPlanForecast (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SkipCovCalc attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TimeFenceCapacity name="TimeFenceCapacity">TimeFenceCapacity</a>

First included in: Group/ReqPlanForecast (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeFenceCapacity attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TimeFenceCov name="TimeFenceCov">TimeFenceCov</a>

First included in: Group/ReqPlanForecast (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeFenceCov attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TimeFenceExplosion name="TimeFenceExplosion">TimeFenceExplosion</a>

First included in: Group/ReqPlanForecast (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TimeFenceExplosion attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Group/ReqPlanForecast (this entity)  

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

### <a href=#Relationship_PlannedOrderNumberSequenceRelationshipId name="Relationship_PlannedOrderNumberSequenceRelationshipId">Relationship_PlannedOrderNumberSequenceRelationshipId</a>

First included in: Group/ReqPlanForecast (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PlannedOrderNumberSequenceRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Framework/NumberSequenceTable.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Framework/NumberSequenceTable.cdm.json/NumberSequenceTable</a></td><td><a href="../../../System/SystemAdministration/Framework/NumberSequenceTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ReqLogRelationshipId name="Relationship_ReqLogRelationshipId">Relationship_ReqLogRelationshipId</a>

First included in: Group/ReqPlanForecast (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReqLogRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/ReqLog.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/MasterPlanning/Transaction/ReqLog.cdm.json/ReqLog</a></td><td><a href="../Transaction/ReqLog.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ReqPlanRelationshipId name="Relationship_ReqPlanRelationshipId">Relationship_ReqPlanRelationshipId</a>

First included in: Group/ReqPlanForecast (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReqPlanRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="ReqPlan.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/MasterPlanning/Group/ReqPlan.cdm.json/ReqPlan</a></td><td><a href="ReqPlan.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ReqPlanNumberSequenceRelationshipId name="Relationship_ReqPlanNumberSequenceRelationshipId">Relationship_ReqPlanNumberSequenceRelationshipId</a>

First included in: Group/ReqPlanForecast (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReqPlanNumberSequenceRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../System/SystemAdministration/Framework/NumberSequenceTable.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Framework/NumberSequenceTable.cdm.json/NumberSequenceTable</a></td><td><a href="../../../System/SystemAdministration/Framework/NumberSequenceTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Group/ReqPlanForecast (this entity)  

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
