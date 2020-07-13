---
title: BusinessEventsExceptionLog in Miscellaneous - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/13/2020
ms.author: nebanfic
---

# Exception log in Miscellaneous(BusinessEventsExceptionLog)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/System/SystemAdministration/Miscellaneous/BusinessEventsExceptionLog.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BusinessEventsExceptionLog/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Exception log</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="BusinessEventsExceptionLog.md" target="_blank">Miscellaneous/BusinessEventsExceptionLog</a>|
|[BusinessEventId](#BusinessEventId)||<a href="BusinessEventsExceptionLog.md" target="_blank">Miscellaneous/BusinessEventsExceptionLog</a>|
|[ProducerConsumerType](#ProducerConsumerType)||<a href="BusinessEventsExceptionLog.md" target="_blank">Miscellaneous/BusinessEventsExceptionLog</a>|
|[EventId](#EventId)||<a href="BusinessEventsExceptionLog.md" target="_blank">Miscellaneous/BusinessEventsExceptionLog</a>|
|[EventTime](#EventTime)||<a href="BusinessEventsExceptionLog.md" target="_blank">Miscellaneous/BusinessEventsExceptionLog</a>|
|[SessionId](#SessionId)||<a href="BusinessEventsExceptionLog.md" target="_blank">Miscellaneous/BusinessEventsExceptionLog</a>|
|[SerializedContract](#SerializedContract)||<a href="BusinessEventsExceptionLog.md" target="_blank">Miscellaneous/BusinessEventsExceptionLog</a>|
|[ExceptionMessage](#ExceptionMessage)||<a href="BusinessEventsExceptionLog.md" target="_blank">Miscellaneous/BusinessEventsExceptionLog</a>|
|[ExceptionSource](#ExceptionSource)||<a href="BusinessEventsExceptionLog.md" target="_blank">Miscellaneous/BusinessEventsExceptionLog</a>|
|[StackTrace](#StackTrace)||<a href="BusinessEventsExceptionLog.md" target="_blank">Miscellaneous/BusinessEventsExceptionLog</a>|
|[ExceptionTypeName](#ExceptionTypeName)||<a href="BusinessEventsExceptionLog.md" target="_blank">Miscellaneous/BusinessEventsExceptionLog</a>|
|[LegalEntity](#LegalEntity)||<a href="BusinessEventsExceptionLog.md" target="_blank">Miscellaneous/BusinessEventsExceptionLog</a>|
|[LastProcessTime](#LastProcessTime)||<a href="BusinessEventsExceptionLog.md" target="_blank">Miscellaneous/BusinessEventsExceptionLog</a>|
|[TargetEndpoint](#TargetEndpoint)||<a href="BusinessEventsExceptionLog.md" target="_blank">Miscellaneous/BusinessEventsExceptionLog</a>|
|[SerializedFilterProperties](#SerializedFilterProperties)||<a href="BusinessEventsExceptionLog.md" target="_blank">Miscellaneous/BusinessEventsExceptionLog</a>|
|[Relationship_BusinessEventsConfigurationRelationshipId](#Relationship_BusinessEventsConfigurationRelationshipId)||<a href="BusinessEventsExceptionLog.md" target="_blank">Miscellaneous/BusinessEventsExceptionLog</a>|
|[Relationship_DataFeedsDefinitionRelationshipId](#Relationship_DataFeedsDefinitionRelationshipId)||<a href="BusinessEventsExceptionLog.md" target="_blank">Miscellaneous/BusinessEventsExceptionLog</a>|
|[Relationship_BusinessEventsEndpointRelationshipId](#Relationship_BusinessEventsEndpointRelationshipId)||<a href="BusinessEventsExceptionLog.md" target="_blank">Miscellaneous/BusinessEventsExceptionLog</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/BusinessEventsExceptionLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BusinessEventsExceptionLog/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BusinessEventId name="BusinessEventId">BusinessEventId</a>

First included in: Miscellaneous/BusinessEventsExceptionLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BusinessEventId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProducerConsumerType name="ProducerConsumerType">ProducerConsumerType</a>

First included in: Miscellaneous/BusinessEventsExceptionLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProducerConsumerType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#EventId name="EventId">EventId</a>

First included in: Miscellaneous/BusinessEventsExceptionLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EventId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EventTime name="EventTime">EventTime</a>

First included in: Miscellaneous/BusinessEventsExceptionLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EventTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#SessionId name="SessionId">SessionId</a>

First included in: Miscellaneous/BusinessEventsExceptionLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SessionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SerializedContract name="SerializedContract">SerializedContract</a>

First included in: Miscellaneous/BusinessEventsExceptionLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SerializedContract attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExceptionMessage name="ExceptionMessage">ExceptionMessage</a>

First included in: Miscellaneous/BusinessEventsExceptionLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExceptionMessage attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExceptionSource name="ExceptionSource">ExceptionSource</a>

First included in: Miscellaneous/BusinessEventsExceptionLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExceptionSource attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#StackTrace name="StackTrace">StackTrace</a>

First included in: Miscellaneous/BusinessEventsExceptionLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StackTrace attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExceptionTypeName name="ExceptionTypeName">ExceptionTypeName</a>

First included in: Miscellaneous/BusinessEventsExceptionLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExceptionTypeName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LegalEntity name="LegalEntity">LegalEntity</a>

First included in: Miscellaneous/BusinessEventsExceptionLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LegalEntity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LastProcessTime name="LastProcessTime">LastProcessTime</a>

First included in: Miscellaneous/BusinessEventsExceptionLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LastProcessTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#TargetEndpoint name="TargetEndpoint">TargetEndpoint</a>

First included in: Miscellaneous/BusinessEventsExceptionLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TargetEndpoint attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SerializedFilterProperties name="SerializedFilterProperties">SerializedFilterProperties</a>

First included in: Miscellaneous/BusinessEventsExceptionLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SerializedFilterProperties attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BusinessEventsConfigurationRelationshipId name="Relationship_BusinessEventsConfigurationRelationshipId">Relationship_BusinessEventsConfigurationRelationshipId</a>

First included in: Miscellaneous/BusinessEventsExceptionLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BusinessEventsConfigurationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="BusinessEventsConfiguration.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Miscellaneous/BusinessEventsConfiguration.cdm.json/BusinessEventsConfiguration</a></td><td><a href="BusinessEventsConfiguration.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DataFeedsDefinitionRelationshipId name="Relationship_DataFeedsDefinitionRelationshipId">Relationship_DataFeedsDefinitionRelationshipId</a>

First included in: Miscellaneous/BusinessEventsExceptionLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DataFeedsDefinitionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="DataFeedsDefinition.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Miscellaneous/DataFeedsDefinition.cdm.json/DataFeedsDefinition</a></td><td><a href="DataFeedsDefinition.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BusinessEventsEndpointRelationshipId name="Relationship_BusinessEventsEndpointRelationshipId">Relationship_BusinessEventsEndpointRelationshipId</a>

First included in: Miscellaneous/BusinessEventsExceptionLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BusinessEventsEndpointRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="BusinessEventsEndpoint.md" target="_blank">/core/operationsCommon/Tables/System/SystemAdministration/Miscellaneous/BusinessEventsEndpoint.cdm.json/BusinessEventsEndpoint</a></td><td><a href="BusinessEventsEndpoint.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
