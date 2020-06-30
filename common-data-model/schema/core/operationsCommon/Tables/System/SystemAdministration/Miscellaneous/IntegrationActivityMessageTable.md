---
title: IntegrationActivityMessageTable - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 6/30/2020
ms.author: nebanfic
---

# IntegrationActivityMessageTable

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/System/SystemAdministration/Miscellaneous/IntegrationActivityMessageTable.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[IntegrationActivityMessageTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="IntegrationActivityMessageTable.md" target="_blank">Miscellaneous/IntegrationActivityMessageTable</a>|
|[MessageId](#MessageId)||<a href="IntegrationActivityMessageTable.md" target="_blank">Miscellaneous/IntegrationActivityMessageTable</a>|
|[ActivityCorrelationId](#ActivityCorrelationId)||<a href="IntegrationActivityMessageTable.md" target="_blank">Miscellaneous/IntegrationActivityMessageTable</a>|
|[ActivityRuntimeExecutionCorrelationId](#ActivityRuntimeExecutionCorrelationId)||<a href="IntegrationActivityMessageTable.md" target="_blank">Miscellaneous/IntegrationActivityMessageTable</a>|
|[EntityName](#EntityName)||<a href="IntegrationActivityMessageTable.md" target="_blank">Miscellaneous/IntegrationActivityMessageTable</a>|
|[ExternalCorrelationId](#ExternalCorrelationId)||<a href="IntegrationActivityMessageTable.md" target="_blank">Miscellaneous/IntegrationActivityMessageTable</a>|
|[EnqueueDateTime](#EnqueueDateTime)||<a href="IntegrationActivityMessageTable.md" target="_blank">Miscellaneous/IntegrationActivityMessageTable</a>|
|[EnqueueUser](#EnqueueUser)||<a href="IntegrationActivityMessageTable.md" target="_blank">Miscellaneous/IntegrationActivityMessageTable</a>|
|[ProcessingCompletedDateTime](#ProcessingCompletedDateTime)||<a href="IntegrationActivityMessageTable.md" target="_blank">Miscellaneous/IntegrationActivityMessageTable</a>|
|[LastDequeueDateTime](#LastDequeueDateTime)||<a href="IntegrationActivityMessageTable.md" target="_blank">Miscellaneous/IntegrationActivityMessageTable</a>|
|[LastDownloadDateTime](#LastDownloadDateTime)||<a href="IntegrationActivityMessageTable.md" target="_blank">Miscellaneous/IntegrationActivityMessageTable</a>|
|[AckDateTime](#AckDateTime)||<a href="IntegrationActivityMessageTable.md" target="_blank">Miscellaneous/IntegrationActivityMessageTable</a>|
|[AckUser](#AckUser)||<a href="IntegrationActivityMessageTable.md" target="_blank">Miscellaneous/IntegrationActivityMessageTable</a>|
|[Status](#Status)||<a href="IntegrationActivityMessageTable.md" target="_blank">Miscellaneous/IntegrationActivityMessageTable</a>|
|[ProcessingStartedDateTime](#ProcessingStartedDateTime)||<a href="IntegrationActivityMessageTable.md" target="_blank">Miscellaneous/IntegrationActivityMessageTable</a>|
|[RetryEnabled](#RetryEnabled)||<a href="IntegrationActivityMessageTable.md" target="_blank">Miscellaneous/IntegrationActivityMessageTable</a>|
|[RetryCount](#RetryCount)||<a href="IntegrationActivityMessageTable.md" target="_blank">Miscellaneous/IntegrationActivityMessageTable</a>|
|[ContextDataAreaId](#ContextDataAreaId)||<a href="IntegrationActivityMessageTable.md" target="_blank">Miscellaneous/IntegrationActivityMessageTable</a>|
|[IsContextDataAreaIdSet](#IsContextDataAreaIdSet)||<a href="IntegrationActivityMessageTable.md" target="_blank">Miscellaneous/IntegrationActivityMessageTable</a>|
|[SubmittedDataFile](#SubmittedDataFile)||<a href="IntegrationActivityMessageTable.md" target="_blank">Miscellaneous/IntegrationActivityMessageTable</a>|
|[BatchHistory](#BatchHistory)||<a href="IntegrationActivityMessageTable.md" target="_blank">Miscellaneous/IntegrationActivityMessageTable</a>|
|[BatchStatus](#BatchStatus)||<a href="IntegrationActivityMessageTable.md" target="_blank">Miscellaneous/IntegrationActivityMessageTable</a>|
|[TotalRecordsExported](#TotalRecordsExported)||<a href="IntegrationActivityMessageTable.md" target="_blank">Miscellaneous/IntegrationActivityMessageTable</a>|
|[FileUploaded](#FileUploaded)||<a href="IntegrationActivityMessageTable.md" target="_blank">Miscellaneous/IntegrationActivityMessageTable</a>|
|[Relationship_IntegrationActivityTableRelationshipId](#Relationship_IntegrationActivityTableRelationshipId)||<a href="IntegrationActivityMessageTable.md" target="_blank">Miscellaneous/IntegrationActivityMessageTable</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/IntegrationActivityMessageTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[IntegrationActivityMessageTable/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#MessageId name="MessageId">MessageId</a>

First included in: Miscellaneous/IntegrationActivityMessageTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MessageId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActivityCorrelationId name="ActivityCorrelationId">ActivityCorrelationId</a>

First included in: Miscellaneous/IntegrationActivityMessageTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActivityCorrelationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ActivityRuntimeExecutionCorrelationId name="ActivityRuntimeExecutionCorrelationId">ActivityRuntimeExecutionCorrelationId</a>

First included in: Miscellaneous/IntegrationActivityMessageTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActivityRuntimeExecutionCorrelationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EntityName name="EntityName">EntityName</a>

First included in: Miscellaneous/IntegrationActivityMessageTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EntityName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExternalCorrelationId name="ExternalCorrelationId">ExternalCorrelationId</a>

First included in: Miscellaneous/IntegrationActivityMessageTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExternalCorrelationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EnqueueDateTime name="EnqueueDateTime">EnqueueDateTime</a>

First included in: Miscellaneous/IntegrationActivityMessageTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnqueueDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#EnqueueUser name="EnqueueUser">EnqueueUser</a>

First included in: Miscellaneous/IntegrationActivityMessageTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EnqueueUser attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProcessingCompletedDateTime name="ProcessingCompletedDateTime">ProcessingCompletedDateTime</a>

First included in: Miscellaneous/IntegrationActivityMessageTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcessingCompletedDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#LastDequeueDateTime name="LastDequeueDateTime">LastDequeueDateTime</a>

First included in: Miscellaneous/IntegrationActivityMessageTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LastDequeueDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#LastDownloadDateTime name="LastDownloadDateTime">LastDownloadDateTime</a>

First included in: Miscellaneous/IntegrationActivityMessageTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LastDownloadDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#AckDateTime name="AckDateTime">AckDateTime</a>

First included in: Miscellaneous/IntegrationActivityMessageTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AckDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#AckUser name="AckUser">AckUser</a>

First included in: Miscellaneous/IntegrationActivityMessageTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AckUser attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Status name="Status">Status</a>

First included in: Miscellaneous/IntegrationActivityMessageTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Status attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ProcessingStartedDateTime name="ProcessingStartedDateTime">ProcessingStartedDateTime</a>

First included in: Miscellaneous/IntegrationActivityMessageTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcessingStartedDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#RetryEnabled name="RetryEnabled">RetryEnabled</a>

First included in: Miscellaneous/IntegrationActivityMessageTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetryEnabled attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RetryCount name="RetryCount">RetryCount</a>

First included in: Miscellaneous/IntegrationActivityMessageTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetryCount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ContextDataAreaId name="ContextDataAreaId">ContextDataAreaId</a>

First included in: Miscellaneous/IntegrationActivityMessageTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContextDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsContextDataAreaIdSet name="IsContextDataAreaIdSet">IsContextDataAreaIdSet</a>

First included in: Miscellaneous/IntegrationActivityMessageTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is company specified in the request message</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsContextDataAreaIdSet attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Is company specified in the request message</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#SubmittedDataFile name="SubmittedDataFile">SubmittedDataFile</a>

First included in: Miscellaneous/IntegrationActivityMessageTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SubmittedDataFile attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BatchHistory name="BatchHistory">BatchHistory</a>

First included in: Miscellaneous/IntegrationActivityMessageTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BatchHistory attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BatchStatus name="BatchStatus">BatchStatus</a>

First included in: Miscellaneous/IntegrationActivityMessageTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Batch status</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BatchStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Batch status</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TotalRecordsExported name="TotalRecordsExported">TotalRecordsExported</a>

First included in: Miscellaneous/IntegrationActivityMessageTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total records exported</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TotalRecordsExported attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Total records exported</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#FileUploaded name="FileUploaded">FileUploaded</a>

First included in: Miscellaneous/IntegrationActivityMessageTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>File uploaded successfully</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FileUploaded attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>File uploaded successfully</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#Relationship_IntegrationActivityTableRelationshipId name="Relationship_IntegrationActivityTableRelationshipId">Relationship_IntegrationActivityTableRelationshipId</a>

First included in: Miscellaneous/IntegrationActivityMessageTable (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_IntegrationActivityTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="IntegrationActivityTable.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Miscellaneous/IntegrationActivityTable.cdm.json/IntegrationActivityTable</a></td><td><a href="IntegrationActivityTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
