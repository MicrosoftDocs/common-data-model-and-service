---
title: RetailCDXMetadataSyncTombstone - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# RetailCDXMetadataSyncTombstone

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Commerce/Retail/Miscellaneous/RetailCDXMetadataSyncTombstone.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailCDXMetadataSyncTombstone/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailCDXMetadataSyncTombstone.md" target="_blank">Miscellaneous/RetailCDXMetadataSyncTombstone</a>|
|[JobID](#JobID)||<a href="RetailCDXMetadataSyncTombstone.md" target="_blank">Miscellaneous/RetailCDXMetadataSyncTombstone</a>|
|[RefRecID](#RefRecID)||<a href="RetailCDXMetadataSyncTombstone.md" target="_blank">Miscellaneous/RetailCDXMetadataSyncTombstone</a>|
|[RefTableID](#RefTableID)||<a href="RetailCDXMetadataSyncTombstone.md" target="_blank">Miscellaneous/RetailCDXMetadataSyncTombstone</a>|
|[SubJobID](#SubJobID)||<a href="RetailCDXMetadataSyncTombstone.md" target="_blank">Miscellaneous/RetailCDXMetadataSyncTombstone</a>|
|[Relationship_RetailCDXScheduleDataGroupRelationshipId](#Relationship_RetailCDXScheduleDataGroupRelationshipId)||<a href="RetailCDXMetadataSyncTombstone.md" target="_blank">Miscellaneous/RetailCDXMetadataSyncTombstone</a>|
|[Relationship_RetailConnScheduleJobMappingRelationshipId](#Relationship_RetailConnScheduleJobMappingRelationshipId)||<a href="RetailCDXMetadataSyncTombstone.md" target="_blank">Miscellaneous/RetailCDXMetadataSyncTombstone</a>|
|[Relationship_RetailConnSchedulerJobTableRelationshipId](#Relationship_RetailConnSchedulerJobTableRelationshipId)||<a href="RetailCDXMetadataSyncTombstone.md" target="_blank">Miscellaneous/RetailCDXMetadataSyncTombstone</a>|
|[Relationship_RetailConnSchedulerSubJobTableRelationshipId](#Relationship_RetailConnSchedulerSubJobTableRelationshipId)||<a href="RetailCDXMetadataSyncTombstone.md" target="_blank">Miscellaneous/RetailCDXMetadataSyncTombstone</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/RetailCDXMetadataSyncTombstone (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailCDXMetadataSyncTombstone/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#JobID name="JobID">JobID</a>

First included in: Miscellaneous/RetailCDXMetadataSyncTombstone (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JobID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RefRecID name="RefRecID">RefRecID</a>

First included in: Miscellaneous/RetailCDXMetadataSyncTombstone (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefRecID attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RefTableID name="RefTableID">RefTableID</a>

First included in: Miscellaneous/RetailCDXMetadataSyncTombstone (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RefTableID attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SubJobID name="SubJobID">SubJobID</a>

First included in: Miscellaneous/RetailCDXMetadataSyncTombstone (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubJobID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailCDXScheduleDataGroupRelationshipId name="Relationship_RetailCDXScheduleDataGroupRelationshipId">Relationship_RetailCDXScheduleDataGroupRelationshipId</a>

First included in: Miscellaneous/RetailCDXMetadataSyncTombstone (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailCDXScheduleDataGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/RetailCDXScheduleDataGroup.md" target="_blank">/core/erp/Tables/Commerce/Retail/Main/RetailCDXScheduleDataGroup.cdm.json/RetailCDXScheduleDataGroup</a></td><td><a href="../Main/RetailCDXScheduleDataGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailConnScheduleJobMappingRelationshipId name="Relationship_RetailConnScheduleJobMappingRelationshipId">Relationship_RetailConnScheduleJobMappingRelationshipId</a>

First included in: Miscellaneous/RetailCDXMetadataSyncTombstone (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailConnScheduleJobMappingRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/RetailConnScheduleJobMapping.md" target="_blank">/core/erp/Tables/Commerce/Retail/Transaction/RetailConnScheduleJobMapping.cdm.json/RetailConnScheduleJobMapping</a></td><td><a href="../Transaction/RetailConnScheduleJobMapping.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailConnSchedulerJobTableRelationshipId name="Relationship_RetailConnSchedulerJobTableRelationshipId">Relationship_RetailConnSchedulerJobTableRelationshipId</a>

First included in: Miscellaneous/RetailCDXMetadataSyncTombstone (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailConnSchedulerJobTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/RetailConnSchedulerJobTable.md" target="_blank">/core/erp/Tables/Commerce/Retail/Main/RetailConnSchedulerJobTable.cdm.json/RetailConnSchedulerJobTable</a></td><td><a href="../Main/RetailConnSchedulerJobTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailConnSchedulerSubJobTableRelationshipId name="Relationship_RetailConnSchedulerSubJobTableRelationshipId">Relationship_RetailConnSchedulerSubJobTableRelationshipId</a>

First included in: Miscellaneous/RetailCDXMetadataSyncTombstone (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailConnSchedulerSubJobTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/RetailConnSchedulerSubjobTable.md" target="_blank">/core/erp/Tables/Commerce/Retail/Main/RetailConnSchedulerSubjobTable.cdm.json/RetailConnSchedulerSubjobTable</a></td><td><a href="../Main/RetailConnSchedulerSubjobTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
