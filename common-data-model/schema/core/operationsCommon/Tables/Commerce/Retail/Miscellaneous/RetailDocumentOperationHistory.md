---
title: RetailDocumentOperationHistory - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# RetailDocumentOperationHistory

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Commerce/Retail/Miscellaneous/RetailDocumentOperationHistory.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailDocumentOperationHistory/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="RetailDocumentOperationHistory.md" target="_blank">Miscellaneous/RetailDocumentOperationHistory</a>|
|[RetailDocumentOperationRecId](#RetailDocumentOperationRecId)||<a href="RetailDocumentOperationHistory.md" target="_blank">Miscellaneous/RetailDocumentOperationHistory</a>|
|[RetailDocumentOperationId](#RetailDocumentOperationId)||<a href="RetailDocumentOperationHistory.md" target="_blank">Miscellaneous/RetailDocumentOperationHistory</a>|
|[RequestId](#RequestId)||<a href="RetailDocumentOperationHistory.md" target="_blank">Miscellaneous/RetailDocumentOperationHistory</a>|
|[OperationName](#OperationName)||<a href="RetailDocumentOperationHistory.md" target="_blank">Miscellaneous/RetailDocumentOperationHistory</a>|
|[ProcessorClassNumber](#ProcessorClassNumber)||<a href="RetailDocumentOperationHistory.md" target="_blank">Miscellaneous/RetailDocumentOperationHistory</a>|
|[Status](#Status)||<a href="RetailDocumentOperationHistory.md" target="_blank">Miscellaneous/RetailDocumentOperationHistory</a>|
|[RequestContainer](#RequestContainer)||<a href="RetailDocumentOperationHistory.md" target="_blank">Miscellaneous/RetailDocumentOperationHistory</a>|
|[ResultContainer](#ResultContainer)||<a href="RetailDocumentOperationHistory.md" target="_blank">Miscellaneous/RetailDocumentOperationHistory</a>|
|[ProcessingErrorCode](#ProcessingErrorCode)||<a href="RetailDocumentOperationHistory.md" target="_blank">Miscellaneous/RetailDocumentOperationHistory</a>|
|[BatchId](#BatchId)||<a href="RetailDocumentOperationHistory.md" target="_blank">Miscellaneous/RetailDocumentOperationHistory</a>|
|[Company](#Company)||<a href="RetailDocumentOperationHistory.md" target="_blank">Miscellaneous/RetailDocumentOperationHistory</a>|
|[RetryCount](#RetryCount)||<a href="RetailDocumentOperationHistory.md" target="_blank">Miscellaneous/RetailDocumentOperationHistory</a>|
|[CommittedDateTime](#CommittedDateTime)||<a href="RetailDocumentOperationHistory.md" target="_blank">Miscellaneous/RetailDocumentOperationHistory</a>|
|[StartDateTime](#StartDateTime)||<a href="RetailDocumentOperationHistory.md" target="_blank">Miscellaneous/RetailDocumentOperationHistory</a>|
|[EndDateTime](#EndDateTime)||<a href="RetailDocumentOperationHistory.md" target="_blank">Miscellaneous/RetailDocumentOperationHistory</a>|
|[Relationship_RetailDocumentOperationRelationRelationshipId](#Relationship_RetailDocumentOperationRelationRelationshipId)||<a href="RetailDocumentOperationHistory.md" target="_blank">Miscellaneous/RetailDocumentOperationHistory</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/RetailDocumentOperationHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[RetailDocumentOperationHistory/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RetailDocumentOperationRecId name="RetailDocumentOperationRecId">RetailDocumentOperationRecId</a>

First included in: Miscellaneous/RetailDocumentOperationHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailDocumentOperationRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RetailDocumentOperationId name="RetailDocumentOperationId">RetailDocumentOperationId</a>

First included in: Miscellaneous/RetailDocumentOperationHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailDocumentOperationId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RequestId name="RequestId">RequestId</a>

First included in: Miscellaneous/RetailDocumentOperationHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OperationName name="OperationName">OperationName</a>

First included in: Miscellaneous/RetailDocumentOperationHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OperationName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProcessorClassNumber name="ProcessorClassNumber">ProcessorClassNumber</a>

First included in: Miscellaneous/RetailDocumentOperationHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcessorClassNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#Status name="Status">Status</a>

First included in: Miscellaneous/RetailDocumentOperationHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Status attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#RequestContainer name="RequestContainer">RequestContainer</a>

First included in: Miscellaneous/RetailDocumentOperationHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RequestContainer attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#ResultContainer name="ResultContainer">ResultContainer</a>

First included in: Miscellaneous/RetailDocumentOperationHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>binary</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResultContainer attribute are listed below.</summary>

**is.dataFormat.byte**  
**is.dataFormat.array**  
**is.dataFormat.byte**  
**is.dataFormat.array**  
</details>

### <a href=#ProcessingErrorCode name="ProcessingErrorCode">ProcessingErrorCode</a>

First included in: Miscellaneous/RetailDocumentOperationHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcessingErrorCode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#BatchId name="BatchId">BatchId</a>

First included in: Miscellaneous/RetailDocumentOperationHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BatchId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Company name="Company">Company</a>

First included in: Miscellaneous/RetailDocumentOperationHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Company attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetryCount name="RetryCount">RetryCount</a>

First included in: Miscellaneous/RetailDocumentOperationHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetryCount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#CommittedDateTime name="CommittedDateTime">CommittedDateTime</a>

First included in: Miscellaneous/RetailDocumentOperationHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CommittedDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#StartDateTime name="StartDateTime">StartDateTime</a>

First included in: Miscellaneous/RetailDocumentOperationHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StartDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#EndDateTime name="EndDateTime">EndDateTime</a>

First included in: Miscellaneous/RetailDocumentOperationHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#Relationship_RetailDocumentOperationRelationRelationshipId name="Relationship_RetailDocumentOperationRelationRelationshipId">Relationship_RetailDocumentOperationRelationRelationshipId</a>

First included in: Miscellaneous/RetailDocumentOperationHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RetailDocumentOperationRelationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="RetailDocumentOperation.md" target="_blank">/core/operationsCommon/Tables/Commerce/Retail/Miscellaneous/RetailDocumentOperation.cdm.json/RetailDocumentOperation</a></td><td><a href="RetailDocumentOperation.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
