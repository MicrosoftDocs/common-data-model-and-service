---
title: RetailConnSchedulerSubjobTable - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/17/2020
ms.author: nebanfic
---

# RetailConnSchedulerSubjobTable

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/erp/Tables/Commerce/Retail/Main/RetailConnSchedulerSubjobTable.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailConnSchedulerSubjobTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailConnSchedulerSubjobTable.md" target="_blank">Main/RetailConnSchedulerSubjobTable</a>|
|[actionCounterInterval](#actionCounterInterval)||<a href="RetailConnSchedulerSubjobTable.md" target="_blank">Main/RetailConnSchedulerSubjobTable</a>|
|[AXTableName](#AXTableName)||<a href="RetailConnSchedulerSubjobTable.md" target="_blank">Main/RetailConnSchedulerSubjobTable</a>|
|[ChannelTableName](#ChannelTableName)||<a href="RetailConnSchedulerSubjobTable.md" target="_blank">Main/RetailConnSchedulerSubjobTable</a>|
|[dataReplicationByPull](#dataReplicationByPull)||<a href="RetailConnSchedulerSubjobTable.md" target="_blank">Main/RetailConnSchedulerSubjobTable</a>|
|[DeleteTargetTable](#DeleteTargetTable)||<a href="RetailConnSchedulerSubjobTable.md" target="_blank">Main/RetailConnSchedulerSubjobTable</a>|
|[enabled](#enabled)||<a href="RetailConnSchedulerSubjobTable.md" target="_blank">Main/RetailConnSchedulerSubjobTable</a>|
|[ForReferenceOnly](#ForReferenceOnly)||<a href="RetailConnSchedulerSubjobTable.md" target="_blank">Main/RetailConnSchedulerSubjobTable</a>|
|[InsertTargetTable](#InsertTargetTable)||<a href="RetailConnSchedulerSubjobTable.md" target="_blank">Main/RetailConnSchedulerSubjobTable</a>|
|[name](#name)||<a href="RetailConnSchedulerSubjobTable.md" target="_blank">Main/RetailConnSchedulerSubjobTable</a>|
|[noDistributionFilter](#noDistributionFilter)||<a href="RetailConnSchedulerSubjobTable.md" target="_blank">Main/RetailConnSchedulerSubjobTable</a>|
|[replicateDataAreaId](#replicateDataAreaId)||<a href="RetailConnSchedulerSubjobTable.md" target="_blank">Main/RetailConnSchedulerSubjobTable</a>|
|[replicationCounterFieldName](#replicationCounterFieldName)||<a href="RetailConnSchedulerSubjobTable.md" target="_blank">Main/RetailConnSchedulerSubjobTable</a>|
|[replicationCounterInterval](#replicationCounterInterval)||<a href="RetailConnSchedulerSubjobTable.md" target="_blank">Main/RetailConnSchedulerSubjobTable</a>|
|[replicationMethod](#replicationMethod)||<a href="RetailConnSchedulerSubjobTable.md" target="_blank">Main/RetailConnSchedulerSubjobTable</a>|
|[RetailConnChannelSchema](#RetailConnChannelSchema)||<a href="RetailConnSchedulerSubjobTable.md" target="_blank">Main/RetailConnSchedulerSubjobTable</a>|
|[subJobId](#subJobId)||<a href="RetailConnSchedulerSubjobTable.md" target="_blank">Main/RetailConnSchedulerSubjobTable</a>|
|[TempDBTableName](#TempDBTableName)||<a href="RetailConnSchedulerSubjobTable.md" target="_blank">Main/RetailConnSchedulerSubjobTable</a>|
|[toDataAreaIdFieldName](#toDataAreaIdFieldName)||<a href="RetailConnSchedulerSubjobTable.md" target="_blank">Main/RetailConnSchedulerSubjobTable</a>|
|[updateCounterOnEmptyInterval](#updateCounterOnEmptyInterval)||<a href="RetailConnSchedulerSubjobTable.md" target="_blank">Main/RetailConnSchedulerSubjobTable</a>|
|[updateReplicationCounter](#updateReplicationCounter)||<a href="RetailConnSchedulerSubjobTable.md" target="_blank">Main/RetailConnSchedulerSubjobTable</a>|
|[FilterDuplicatePackageGenerationRecords](#FilterDuplicatePackageGenerationRecords)||<a href="RetailConnSchedulerSubjobTable.md" target="_blank">Main/RetailConnSchedulerSubjobTable</a>|
|[AllowSkipDataSync](#AllowSkipDataSync)||<a href="RetailConnSchedulerSubjobTable.md" target="_blank">Main/RetailConnSchedulerSubjobTable</a>|
|[Relationship_DataAreadIdFieldNameRelationshipId](#Relationship_DataAreadIdFieldNameRelationshipId)||<a href="RetailConnSchedulerSubjobTable.md" target="_blank">Main/RetailConnSchedulerSubjobTable</a>|
|[Relationship_ReplicationCounterFieldNameRelationshipId](#Relationship_ReplicationCounterFieldNameRelationshipId)||<a href="RetailConnSchedulerSubjobTable.md" target="_blank">Main/RetailConnSchedulerSubjobTable</a>|
|[Relationship_RetailConnChannelSchemaRelationshipId](#Relationship_RetailConnChannelSchemaRelationshipId)||<a href="RetailConnSchedulerSubjobTable.md" target="_blank">Main/RetailConnSchedulerSubjobTable</a>|
|[Relationship_RetailConnLocationDesignTableRelationshipId](#Relationship_RetailConnLocationDesignTableRelationshipId)||<a href="RetailConnSchedulerSubjobTable.md" target="_blank">Main/RetailConnSchedulerSubjobTable</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/RetailConnSchedulerSubjobTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailConnSchedulerSubjobTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#actionCounterInterval name="actionCounterInterval">actionCounterInterval</a>

First included in: Main/RetailConnSchedulerSubjobTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the actionCounterInterval attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AXTableName name="AXTableName">AXTableName</a>

First included in: Main/RetailConnSchedulerSubjobTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AXTableName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ChannelTableName name="ChannelTableName">ChannelTableName</a>

First included in: Main/RetailConnSchedulerSubjobTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ChannelTableName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#dataReplicationByPull name="dataReplicationByPull">dataReplicationByPull</a>

First included in: Main/RetailConnSchedulerSubjobTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the dataReplicationByPull attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#DeleteTargetTable name="DeleteTargetTable">DeleteTargetTable</a>

First included in: Main/RetailConnSchedulerSubjobTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DeleteTargetTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#enabled name="enabled">enabled</a>

First included in: Main/RetailConnSchedulerSubjobTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the enabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#ForReferenceOnly name="ForReferenceOnly">ForReferenceOnly</a>

First included in: Main/RetailConnSchedulerSubjobTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ForReferenceOnly attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#InsertTargetTable name="InsertTargetTable">InsertTargetTable</a>

First included in: Main/RetailConnSchedulerSubjobTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InsertTargetTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#name name="name">name</a>

First included in: Main/RetailConnSchedulerSubjobTable (this entity)  

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

### <a href=#noDistributionFilter name="noDistributionFilter">noDistributionFilter</a>

First included in: Main/RetailConnSchedulerSubjobTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the noDistributionFilter attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#replicateDataAreaId name="replicateDataAreaId">replicateDataAreaId</a>

First included in: Main/RetailConnSchedulerSubjobTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the replicateDataAreaId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#replicationCounterFieldName name="replicationCounterFieldName">replicationCounterFieldName</a>

First included in: Main/RetailConnSchedulerSubjobTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the replicationCounterFieldName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#replicationCounterInterval name="replicationCounterInterval">replicationCounterInterval</a>

First included in: Main/RetailConnSchedulerSubjobTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the replicationCounterInterval attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#replicationMethod name="replicationMethod">replicationMethod</a>

First included in: Main/RetailConnSchedulerSubjobTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the replicationMethod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RetailConnChannelSchema name="RetailConnChannelSchema">RetailConnChannelSchema</a>

First included in: Main/RetailConnSchedulerSubjobTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailConnChannelSchema attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#subJobId name="subJobId">subJobId</a>

First included in: Main/RetailConnSchedulerSubjobTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the subJobId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TempDBTableName name="TempDBTableName">TempDBTableName</a>

First included in: Main/RetailConnSchedulerSubjobTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TempDBTableName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#toDataAreaIdFieldName name="toDataAreaIdFieldName">toDataAreaIdFieldName</a>

First included in: Main/RetailConnSchedulerSubjobTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the toDataAreaIdFieldName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#updateCounterOnEmptyInterval name="updateCounterOnEmptyInterval">updateCounterOnEmptyInterval</a>

First included in: Main/RetailConnSchedulerSubjobTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the updateCounterOnEmptyInterval attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#updateReplicationCounter name="updateReplicationCounter">updateReplicationCounter</a>

First included in: Main/RetailConnSchedulerSubjobTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the updateReplicationCounter attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.dataFormat.integer**  
</details>

### <a href=#FilterDuplicatePackageGenerationRecords name="FilterDuplicatePackageGenerationRecords">FilterDuplicatePackageGenerationRecords</a>

First included in: Main/RetailConnSchedulerSubjobTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FilterDuplicatePackageGenerationRecords attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#AllowSkipDataSync name="AllowSkipDataSync">AllowSkipDataSync</a>

First included in: Main/RetailConnSchedulerSubjobTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowSkipDataSync attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Relationship_DataAreadIdFieldNameRelationshipId name="Relationship_DataAreadIdFieldNameRelationshipId">Relationship_DataAreadIdFieldNameRelationshipId</a>

First included in: Main/RetailConnSchedulerSubjobTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DataAreadIdFieldNameRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailConnLocationDesignTableField.md" target="_blank">/core/erp/Tables/Commerce/Retail/Main/RetailConnLocationDesignTableField.cdm.json/RetailConnLocationDesignTableField</a></td><td><a href="RetailConnLocationDesignTableField.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ReplicationCounterFieldNameRelationshipId name="Relationship_ReplicationCounterFieldNameRelationshipId">Relationship_ReplicationCounterFieldNameRelationshipId</a>

First included in: Main/RetailConnSchedulerSubjobTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReplicationCounterFieldNameRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailConnLocationDesignTableField.md" target="_blank">/core/erp/Tables/Commerce/Retail/Main/RetailConnLocationDesignTableField.cdm.json/RetailConnLocationDesignTableField</a></td><td><a href="RetailConnLocationDesignTableField.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailConnChannelSchemaRelationshipId name="Relationship_RetailConnChannelSchemaRelationshipId">Relationship_RetailConnChannelSchemaRelationshipId</a>

First included in: Main/RetailConnSchedulerSubjobTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailConnChannelSchemaRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailConnChannelSchema.md" target="_blank">/core/erp/Tables/Commerce/Retail/Main/RetailConnChannelSchema.cdm.json/RetailConnChannelSchema</a></td><td><a href="RetailConnChannelSchema.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RetailConnLocationDesignTableRelationshipId name="Relationship_RetailConnLocationDesignTableRelationshipId">Relationship_RetailConnLocationDesignTableRelationshipId</a>

First included in: Main/RetailConnSchedulerSubjobTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailConnLocationDesignTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailConnLocationDesignTable.md" target="_blank">/core/erp/Tables/Commerce/Retail/Main/RetailConnLocationDesignTable.cdm.json/RetailConnLocationDesignTable</a></td><td><a href="RetailConnLocationDesignTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
