---
title: PurchReqQuestionnaireAnswerTableHistory in TransactionHeader - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Plan a questionnaire in TransactionHeader(PurchReqQuestionnaireAnswerTableHistory)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/TransactionHeader/PurchReqQuestionnaireAnswerTableHistory.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PurchReqQuestionnaireAnswerTableHistory/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Plan a questionnaire</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="PurchReqQuestionnaireAnswerTableHistory.md" target="_blank">TransactionHeader/PurchReqQuestionnaireAnswerTableHistory</a>|
|[correctAnswers](#correctAnswers)||<a href="PurchReqQuestionnaireAnswerTableHistory.md" target="_blank">TransactionHeader/PurchReqQuestionnaireAnswerTableHistory</a>|
|[DiscussionId](#DiscussionId)||<a href="PurchReqQuestionnaireAnswerTableHistory.md" target="_blank">TransactionHeader/PurchReqQuestionnaireAnswerTableHistory</a>|
|[EndDateTime](#EndDateTime)||<a href="PurchReqQuestionnaireAnswerTableHistory.md" target="_blank">TransactionHeader/PurchReqQuestionnaireAnswerTableHistory</a>|
|[evaluation](#evaluation)||<a href="PurchReqQuestionnaireAnswerTableHistory.md" target="_blank">TransactionHeader/PurchReqQuestionnaireAnswerTableHistory</a>|
|[EvaluationOf](#EvaluationOf)||<a href="PurchReqQuestionnaireAnswerTableHistory.md" target="_blank">TransactionHeader/PurchReqQuestionnaireAnswerTableHistory</a>|
|[ExecutedBy](#ExecutedBy)||<a href="PurchReqQuestionnaireAnswerTableHistory.md" target="_blank">TransactionHeader/PurchReqQuestionnaireAnswerTableHistory</a>|
|[kmCollectionId](#kmCollectionId)||<a href="PurchReqQuestionnaireAnswerTableHistory.md" target="_blank">TransactionHeader/PurchReqQuestionnaireAnswerTableHistory</a>|
|[kmKnowledgeCollectorPlanningTableId](#kmKnowledgeCollectorPlanningTableId)||<a href="PurchReqQuestionnaireAnswerTableHistory.md" target="_blank">TransactionHeader/PurchReqQuestionnaireAnswerTableHistory</a>|
|[KMVirtualNetworkAnswerTable](#KMVirtualNetworkAnswerTable)||<a href="PurchReqQuestionnaireAnswerTableHistory.md" target="_blank">TransactionHeader/PurchReqQuestionnaireAnswerTableHistory</a>|
|[kmVirtualNetworkAnswerTableId](#kmVirtualNetworkAnswerTableId)||<a href="PurchReqQuestionnaireAnswerTableHistory.md" target="_blank">TransactionHeader/PurchReqQuestionnaireAnswerTableHistory</a>|
|[percent](#percent)||<a href="PurchReqQuestionnaireAnswerTableHistory.md" target="_blank">TransactionHeader/PurchReqQuestionnaireAnswerTableHistory</a>|
|[point](#point)||<a href="PurchReqQuestionnaireAnswerTableHistory.md" target="_blank">TransactionHeader/PurchReqQuestionnaireAnswerTableHistory</a>|
|[role](#role)||<a href="PurchReqQuestionnaireAnswerTableHistory.md" target="_blank">TransactionHeader/PurchReqQuestionnaireAnswerTableHistory</a>|
|[startDateTime](#startDateTime)||<a href="PurchReqQuestionnaireAnswerTableHistory.md" target="_blank">TransactionHeader/PurchReqQuestionnaireAnswerTableHistory</a>|
|[status](#status)||<a href="PurchReqQuestionnaireAnswerTableHistory.md" target="_blank">TransactionHeader/PurchReqQuestionnaireAnswerTableHistory</a>|
|[ValidFrom](#ValidFrom)||<a href="PurchReqQuestionnaireAnswerTableHistory.md" target="_blank">TransactionHeader/PurchReqQuestionnaireAnswerTableHistory</a>|
|[ValidTo](#ValidTo)||<a href="PurchReqQuestionnaireAnswerTableHistory.md" target="_blank">TransactionHeader/PurchReqQuestionnaireAnswerTableHistory</a>|
|[DataAreaId](#DataAreaId)||<a href="PurchReqQuestionnaireAnswerTableHistory.md" target="_blank">TransactionHeader/PurchReqQuestionnaireAnswerTableHistory</a>|
|[Relationship_EvaluationOf_FKRelationshipId](#Relationship_EvaluationOf_FKRelationshipId)||<a href="PurchReqQuestionnaireAnswerTableHistory.md" target="_blank">TransactionHeader/PurchReqQuestionnaireAnswerTableHistory</a>|
|[Relationship_ExecutedBy_FKRelationshipId](#Relationship_ExecutedBy_FKRelationshipId)||<a href="PurchReqQuestionnaireAnswerTableHistory.md" target="_blank">TransactionHeader/PurchReqQuestionnaireAnswerTableHistory</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="PurchReqQuestionnaireAnswerTableHistory.md" target="_blank">TransactionHeader/PurchReqQuestionnaireAnswerTableHistory</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: TransactionHeader/PurchReqQuestionnaireAnswerTableHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PurchReqQuestionnaireAnswerTableHistory/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#correctAnswers name="correctAnswers">correctAnswers</a>

First included in: TransactionHeader/PurchReqQuestionnaireAnswerTableHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the correctAnswers attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DiscussionId name="DiscussionId">DiscussionId</a>

First included in: TransactionHeader/PurchReqQuestionnaireAnswerTableHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DiscussionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EndDateTime name="EndDateTime">EndDateTime</a>

First included in: TransactionHeader/PurchReqQuestionnaireAnswerTableHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#evaluation name="evaluation">evaluation</a>

First included in: TransactionHeader/PurchReqQuestionnaireAnswerTableHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the evaluation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#EvaluationOf name="EvaluationOf">EvaluationOf</a>

First included in: TransactionHeader/PurchReqQuestionnaireAnswerTableHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EvaluationOf attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ExecutedBy name="ExecutedBy">ExecutedBy</a>

First included in: TransactionHeader/PurchReqQuestionnaireAnswerTableHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExecutedBy attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#kmCollectionId name="kmCollectionId">kmCollectionId</a>

First included in: TransactionHeader/PurchReqQuestionnaireAnswerTableHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the kmCollectionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#kmKnowledgeCollectorPlanningTableId name="kmKnowledgeCollectorPlanningTableId">kmKnowledgeCollectorPlanningTableId</a>

First included in: TransactionHeader/PurchReqQuestionnaireAnswerTableHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the kmKnowledgeCollectorPlanningTableId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#KMVirtualNetworkAnswerTable name="KMVirtualNetworkAnswerTable">KMVirtualNetworkAnswerTable</a>

First included in: TransactionHeader/PurchReqQuestionnaireAnswerTableHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the KMVirtualNetworkAnswerTable attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#kmVirtualNetworkAnswerTableId name="kmVirtualNetworkAnswerTableId">kmVirtualNetworkAnswerTableId</a>

First included in: TransactionHeader/PurchReqQuestionnaireAnswerTableHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the kmVirtualNetworkAnswerTableId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#percent name="percent">percent</a>

First included in: TransactionHeader/PurchReqQuestionnaireAnswerTableHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the percent attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#point name="point">point</a>

First included in: TransactionHeader/PurchReqQuestionnaireAnswerTableHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the point attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#role name="role">role</a>

First included in: TransactionHeader/PurchReqQuestionnaireAnswerTableHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the role attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#startDateTime name="startDateTime">startDateTime</a>

First included in: TransactionHeader/PurchReqQuestionnaireAnswerTableHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the startDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#status name="status">status</a>

First included in: TransactionHeader/PurchReqQuestionnaireAnswerTableHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the status attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ValidFrom name="ValidFrom">ValidFrom</a>

First included in: TransactionHeader/PurchReqQuestionnaireAnswerTableHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidFrom attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#ValidTo name="ValidTo">ValidTo</a>

First included in: TransactionHeader/PurchReqQuestionnaireAnswerTableHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidTo attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: TransactionHeader/PurchReqQuestionnaireAnswerTableHistory (this entity)  

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

### <a href=#Relationship_EvaluationOf_FKRelationshipId name="Relationship_EvaluationOf_FKRelationshipId">Relationship_EvaluationOf_FKRelationshipId</a>

First included in: TransactionHeader/PurchReqQuestionnaireAnswerTableHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EvaluationOf_FKRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Main/DirPerson.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Main/DirPerson.cdm.json/DirPerson</a></td><td><a href="../../../Common/GAB/Main/DirPerson.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ExecutedBy_FKRelationshipId name="Relationship_ExecutedBy_FKRelationshipId">Relationship_ExecutedBy_FKRelationshipId</a>

First included in: TransactionHeader/PurchReqQuestionnaireAnswerTableHistory (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ExecutedBy_FKRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/GAB/Main/DirPerson.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Main/DirPerson.cdm.json/DirPerson</a></td><td><a href="../../../Common/GAB/Main/DirPerson.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: TransactionHeader/PurchReqQuestionnaireAnswerTableHistory (this entity)  

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
