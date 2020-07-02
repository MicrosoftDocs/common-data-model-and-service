---
title: PurchRFQVendPostedQuestionAnswer - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 6/30/2020
ms.author: nebanfic
---

# Answers posted to vendor questions

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Worksheet/PurchRFQVendPostedQuestionAnswer.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PurchRFQVendPostedQuestionAnswer/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Answers posted to vendor questions</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="PurchRFQVendPostedQuestionAnswer.md" target="_blank">Worksheet/PurchRFQVendPostedQuestionAnswer</a>|
|[QuestionNumber](#QuestionNumber)||<a href="PurchRFQVendPostedQuestionAnswer.md" target="_blank">Worksheet/PurchRFQVendPostedQuestionAnswer</a>|
|[RFQId](#RFQId)||<a href="PurchRFQVendPostedQuestionAnswer.md" target="_blank">Worksheet/PurchRFQVendPostedQuestionAnswer</a>|
|[VendQuestion](#VendQuestion)||<a href="PurchRFQVendPostedQuestionAnswer.md" target="_blank">Worksheet/PurchRFQVendPostedQuestionAnswer</a>|
|[CustomerAnswer](#CustomerAnswer)||<a href="PurchRFQVendPostedQuestionAnswer.md" target="_blank">Worksheet/PurchRFQVendPostedQuestionAnswer</a>|
|[QuestionSubmittedOn](#QuestionSubmittedOn)||<a href="PurchRFQVendPostedQuestionAnswer.md" target="_blank">Worksheet/PurchRFQVendPostedQuestionAnswer</a>|
|[AnswerPublishedOn](#AnswerPublishedOn)||<a href="PurchRFQVendPostedQuestionAnswer.md" target="_blank">Worksheet/PurchRFQVendPostedQuestionAnswer</a>|
|[RFQCaseId](#RFQCaseId)||<a href="PurchRFQVendPostedQuestionAnswer.md" target="_blank">Worksheet/PurchRFQVendPostedQuestionAnswer</a>|
|[IsAnswerPublishedToVendor](#IsAnswerPublishedToVendor)||<a href="PurchRFQVendPostedQuestionAnswer.md" target="_blank">Worksheet/PurchRFQVendPostedQuestionAnswer</a>|
|[IsDirectResponse](#IsDirectResponse)||<a href="PurchRFQVendPostedQuestionAnswer.md" target="_blank">Worksheet/PurchRFQVendPostedQuestionAnswer</a>|
|[PurchRFQVendPostedGroupQuestionAnswerRecId](#PurchRFQVendPostedGroupQuestionAnswerRecId)||<a href="PurchRFQVendPostedQuestionAnswer.md" target="_blank">Worksheet/PurchRFQVendPostedQuestionAnswer</a>|
|[DataAreaId](#DataAreaId)||<a href="PurchRFQVendPostedQuestionAnswer.md" target="_blank">Worksheet/PurchRFQVendPostedQuestionAnswer</a>|
|[Relationship_PurchRFQReplyTableRelationshipId](#Relationship_PurchRFQReplyTableRelationshipId)||<a href="PurchRFQVendPostedQuestionAnswer.md" target="_blank">Worksheet/PurchRFQVendPostedQuestionAnswer</a>|
|[Relationship_PurchRFQCaseTableRelationshipId](#Relationship_PurchRFQCaseTableRelationshipId)||<a href="PurchRFQVendPostedQuestionAnswer.md" target="_blank">Worksheet/PurchRFQVendPostedQuestionAnswer</a>|
|[Relationship_PurchRFQVendPostedGroupQuestionAnswerRelationshipId](#Relationship_PurchRFQVendPostedGroupQuestionAnswerRelationshipId)||<a href="PurchRFQVendPostedQuestionAnswer.md" target="_blank">Worksheet/PurchRFQVendPostedQuestionAnswer</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="PurchRFQVendPostedQuestionAnswer.md" target="_blank">Worksheet/PurchRFQVendPostedQuestionAnswer</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Worksheet/PurchRFQVendPostedQuestionAnswer (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PurchRFQVendPostedQuestionAnswer/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#QuestionNumber name="QuestionNumber">QuestionNumber</a>

First included in: Worksheet/PurchRFQVendPostedQuestionAnswer (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuestionNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RFQId name="RFQId">RFQId</a>

First included in: Worksheet/PurchRFQVendPostedQuestionAnswer (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendQuestion name="VendQuestion">VendQuestion</a>

First included in: Worksheet/PurchRFQVendPostedQuestionAnswer (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendQuestion attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerAnswer name="CustomerAnswer">CustomerAnswer</a>

First included in: Worksheet/PurchRFQVendPostedQuestionAnswer (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerAnswer attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuestionSubmittedOn name="QuestionSubmittedOn">QuestionSubmittedOn</a>

First included in: Worksheet/PurchRFQVendPostedQuestionAnswer (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuestionSubmittedOn attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#AnswerPublishedOn name="AnswerPublishedOn">AnswerPublishedOn</a>

First included in: Worksheet/PurchRFQVendPostedQuestionAnswer (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AnswerPublishedOn attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#RFQCaseId name="RFQCaseId">RFQCaseId</a>

First included in: Worksheet/PurchRFQVendPostedQuestionAnswer (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQCaseId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsAnswerPublishedToVendor name="IsAnswerPublishedToVendor">IsAnswerPublishedToVendor</a>

First included in: Worksheet/PurchRFQVendPostedQuestionAnswer (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsAnswerPublishedToVendor attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#IsDirectResponse name="IsDirectResponse">IsDirectResponse</a>

First included in: Worksheet/PurchRFQVendPostedQuestionAnswer (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDirectResponse attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PurchRFQVendPostedGroupQuestionAnswerRecId name="PurchRFQVendPostedGroupQuestionAnswerRecId">PurchRFQVendPostedGroupQuestionAnswerRecId</a>

First included in: Worksheet/PurchRFQVendPostedQuestionAnswer (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchRFQVendPostedGroupQuestionAnswerRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Worksheet/PurchRFQVendPostedQuestionAnswer (this entity)  

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

### <a href=#Relationship_PurchRFQReplyTableRelationshipId name="Relationship_PurchRFQReplyTableRelationshipId">Relationship_PurchRFQReplyTableRelationshipId</a>

First included in: Worksheet/PurchRFQVendPostedQuestionAnswer (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchRFQReplyTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/PurchRFQReplyTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/WorksheetHeader/PurchRFQReplyTable.cdm.json/PurchRFQReplyTable</a></td><td><a href="../WorksheetHeader/PurchRFQReplyTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PurchRFQCaseTableRelationshipId name="Relationship_PurchRFQCaseTableRelationshipId">Relationship_PurchRFQCaseTableRelationshipId</a>

First included in: Worksheet/PurchRFQVendPostedQuestionAnswer (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchRFQCaseTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/PurchRFQCaseTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/WorksheetHeader/PurchRFQCaseTable.cdm.json/PurchRFQCaseTable</a></td><td><a href="../WorksheetHeader/PurchRFQCaseTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PurchRFQVendPostedGroupQuestionAnswerRelationshipId name="Relationship_PurchRFQVendPostedGroupQuestionAnswerRelationshipId">Relationship_PurchRFQVendPostedGroupQuestionAnswerRelationshipId</a>

First included in: Worksheet/PurchRFQVendPostedQuestionAnswer (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchRFQVendPostedGroupQuestionAnswerRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="PurchRFQVendPostedGroupQuestionAnswer.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Worksheet/PurchRFQVendPostedGroupQuestionAnswer.cdm.json/PurchRFQVendPostedGroupQuestionAnswer</a></td><td><a href="PurchRFQVendPostedGroupQuestionAnswer.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Worksheet/PurchRFQVendPostedQuestionAnswer (this entity)  

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
