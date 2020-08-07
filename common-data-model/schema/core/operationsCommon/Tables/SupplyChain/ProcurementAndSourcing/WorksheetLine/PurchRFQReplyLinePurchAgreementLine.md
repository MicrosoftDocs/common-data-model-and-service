---
title: PurchRFQReplyLinePurchAgreementLine in WorksheetLine - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Purch RFQ Reply Line and Agreement Line relation table in WorksheetLine(PurchRFQReplyLinePurchAgreementLine)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/WorksheetLine/PurchRFQReplyLinePurchAgreementLine.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PurchRFQReplyLinePurchAgreementLine/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Purch RFQ Reply Line and Agreement Line relation table</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="PurchRFQReplyLinePurchAgreementLine.md" target="_blank">WorksheetLine/PurchRFQReplyLinePurchAgreementLine</a>|
|[PurchAgreementLine](#PurchAgreementLine)||<a href="PurchRFQReplyLinePurchAgreementLine.md" target="_blank">WorksheetLine/PurchRFQReplyLinePurchAgreementLine</a>|
|[PurchRFQLineDataAreaId](#PurchRFQLineDataAreaId)||<a href="PurchRFQReplyLinePurchAgreementLine.md" target="_blank">WorksheetLine/PurchRFQReplyLinePurchAgreementLine</a>|
|[PurchRFQReplyLineLineNum](#PurchRFQReplyLineLineNum)||<a href="PurchRFQReplyLinePurchAgreementLine.md" target="_blank">WorksheetLine/PurchRFQReplyLinePurchAgreementLine</a>|
|[PurchRFQReplyLineRFQId](#PurchRFQReplyLineRFQId)||<a href="PurchRFQReplyLinePurchAgreementLine.md" target="_blank">WorksheetLine/PurchRFQReplyLinePurchAgreementLine</a>|
|[Relationship_PurchAgreementLineRelationshipId](#Relationship_PurchAgreementLineRelationshipId)||<a href="PurchRFQReplyLinePurchAgreementLine.md" target="_blank">WorksheetLine/PurchRFQReplyLinePurchAgreementLine</a>|
|[Relationship_PurchRFQReplyLineRelationshipId](#Relationship_PurchRFQReplyLineRelationshipId)||<a href="PurchRFQReplyLinePurchAgreementLine.md" target="_blank">WorksheetLine/PurchRFQReplyLinePurchAgreementLine</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetLine/PurchRFQReplyLinePurchAgreementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PurchRFQReplyLinePurchAgreementLine/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PurchAgreementLine name="PurchAgreementLine">PurchAgreementLine</a>

First included in: WorksheetLine/PurchRFQReplyLinePurchAgreementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchAgreementLine attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#PurchRFQLineDataAreaId name="PurchRFQLineDataAreaId">PurchRFQLineDataAreaId</a>

First included in: WorksheetLine/PurchRFQReplyLinePurchAgreementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchRFQLineDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PurchRFQReplyLineLineNum name="PurchRFQReplyLineLineNum">PurchRFQReplyLineLineNum</a>

First included in: WorksheetLine/PurchRFQReplyLinePurchAgreementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchRFQReplyLineLineNum attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#PurchRFQReplyLineRFQId name="PurchRFQReplyLineRFQId">PurchRFQReplyLineRFQId</a>

First included in: WorksheetLine/PurchRFQReplyLinePurchAgreementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PurchRFQReplyLineRFQId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PurchAgreementLineRelationshipId name="Relationship_PurchAgreementLineRelationshipId">Relationship_PurchAgreementLineRelationshipId</a>

First included in: WorksheetLine/PurchRFQReplyLinePurchAgreementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchAgreementLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="AgreementLine.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/WorksheetLine/AgreementLine.cdm.json/AgreementLine</a></td><td><a href="AgreementLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PurchRFQReplyLineRelationshipId name="Relationship_PurchRFQReplyLineRelationshipId">Relationship_PurchRFQReplyLineRelationshipId</a>

First included in: WorksheetLine/PurchRFQReplyLinePurchAgreementLine (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PurchRFQReplyLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="PurchRFQReplyLine.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/WorksheetLine/PurchRFQReplyLine.cdm.json/PurchRFQReplyLine</a></td><td><a href="PurchRFQReplyLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
