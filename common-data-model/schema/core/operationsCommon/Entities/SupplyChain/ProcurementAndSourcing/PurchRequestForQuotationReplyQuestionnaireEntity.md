---
title: PurchRequestForQuotationReplyQuestionnaireEntity in ProcurementAndSourcing - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/13/2020
ms.author: nebanfic
---

# Request for quotation reply questionnaires in ProcurementAndSourcing(PurchRequestForQuotationReplyQuestionnaireEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/PurchRequestForQuotationReplyQuestionnaireEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Request for quotation reply questionnaires</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[KMVirtualNetworkAnswerTableId](#KMVirtualNetworkAnswerTableId)||<a href="PurchRequestForQuotationReplyQuestionnaireEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyQuestionnaireEntity</a>|
|[QuestionnaireId](#QuestionnaireId)||<a href="PurchRequestForQuotationReplyQuestionnaireEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyQuestionnaireEntity</a>|
|[RFQNumber](#RFQNumber)||<a href="PurchRequestForQuotationReplyQuestionnaireEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyQuestionnaireEntity</a>|
|[VendorAccountNumber](#VendorAccountNumber)||<a href="PurchRequestForQuotationReplyQuestionnaireEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyQuestionnaireEntity</a>|
|[QuestionnaireQuestionId](#QuestionnaireQuestionId)||<a href="PurchRequestForQuotationReplyQuestionnaireEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyQuestionnaireEntity</a>|
|[AnswerText](#AnswerText)||<a href="PurchRequestForQuotationReplyQuestionnaireEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyQuestionnaireEntity</a>|
|[QuestionSequenceNumber](#QuestionSequenceNumber)||<a href="PurchRequestForQuotationReplyQuestionnaireEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyQuestionnaireEntity</a>|
|[QuestionInstruction](#QuestionInstruction)||<a href="PurchRequestForQuotationReplyQuestionnaireEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyQuestionnaireEntity</a>|
|[QuestionText](#QuestionText)||<a href="PurchRequestForQuotationReplyQuestionnaireEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyQuestionnaireEntity</a>|
|[QuestionInputType](#QuestionInputType)||<a href="PurchRequestForQuotationReplyQuestionnaireEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyQuestionnaireEntity</a>|
|[AnswerComment](#AnswerComment)||<a href="PurchRequestForQuotationReplyQuestionnaireEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyQuestionnaireEntity</a>|
|[QuestionnaireStatus](#QuestionnaireStatus)||<a href="PurchRequestForQuotationReplyQuestionnaireEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyQuestionnaireEntity</a>|
|[ResponseRecId](#ResponseRecId)||<a href="PurchRequestForQuotationReplyQuestionnaireEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyQuestionnaireEntity</a>|
|[BackingTable_PurchRFQTableKMCollectionRelationshipId](#BackingTable_PurchRFQTableKMCollectionRelationshipId)||<a href="PurchRequestForQuotationReplyQuestionnaireEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyQuestionnaireEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="PurchRequestForQuotationReplyQuestionnaireEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyQuestionnaireEntity</a>|

### <a href=#KMVirtualNetworkAnswerTableId name="KMVirtualNetworkAnswerTableId">KMVirtualNetworkAnswerTableId</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyQuestionnaireEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the KMVirtualNetworkAnswerTableId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuestionnaireId name="QuestionnaireId">QuestionnaireId</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyQuestionnaireEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Questionnaire Id</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuestionnaireId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Questionnaire Id</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RFQNumber name="RFQNumber">RFQNumber</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyQuestionnaireEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorAccountNumber name="VendorAccountNumber">VendorAccountNumber</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyQuestionnaireEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuestionnaireQuestionId name="QuestionnaireQuestionId">QuestionnaireQuestionId</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyQuestionnaireEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Question ID</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuestionnaireQuestionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Question ID</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AnswerText name="AnswerText">AnswerText</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyQuestionnaireEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Answer text</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AnswerText attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Answer text</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuestionSequenceNumber name="QuestionSequenceNumber">QuestionSequenceNumber</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyQuestionnaireEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Question sequence number</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuestionSequenceNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Question sequence number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuestionInstruction name="QuestionInstruction">QuestionInstruction</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyQuestionnaireEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Question instruction</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuestionInstruction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Question instruction</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuestionText name="QuestionText">QuestionText</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyQuestionnaireEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Question text</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuestionText attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Question text</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuestionInputType name="QuestionInputType">QuestionInputType</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyQuestionnaireEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Question input type</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuestionInputType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Question input type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AnswerComment name="AnswerComment">AnswerComment</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyQuestionnaireEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Answer comment</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AnswerComment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Answer comment</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#QuestionnaireStatus name="QuestionnaireStatus">QuestionnaireStatus</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyQuestionnaireEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the QuestionnaireStatus attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ResponseRecId name="ResponseRecId">ResponseRecId</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyQuestionnaireEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ResponseRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_PurchRFQTableKMCollectionRelationshipId name="BackingTable_PurchRFQTableKMCollectionRelationshipId">BackingTable_PurchRFQTableKMCollectionRelationshipId</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyQuestionnaireEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PurchRFQTableKMCollectionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Miscellaneous/PurchRFQTableKMCollection.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Miscellaneous/PurchRFQTableKMCollection.cdm.json/PurchRFQTableKMCollection</a></td><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Miscellaneous/PurchRFQTableKMCollection.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyQuestionnaireEntity (this entity)  

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
