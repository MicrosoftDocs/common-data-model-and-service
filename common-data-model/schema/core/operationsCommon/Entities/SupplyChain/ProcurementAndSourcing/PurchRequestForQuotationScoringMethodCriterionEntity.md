---
title: PurchRequestForQuotationScoringMethodCriterionEntity in ProcurementAndSourcing - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Request for quotation scoring method criteria in ProcurementAndSourcing(PurchRequestForQuotationScoringMethodCriterionEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/PurchRequestForQuotationScoringMethodCriterionEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Request for quotation scoring method criteria</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RFQScoringMethodRecId](#RFQScoringMethodRecId)||<a href="PurchRequestForQuotationScoringMethodCriterionEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationScoringMethodCriterionEntity</a>|
|[RFQScoringMethodName](#RFQScoringMethodName)||<a href="PurchRequestForQuotationScoringMethodCriterionEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationScoringMethodCriterionEntity</a>|
|[CriterionName](#CriterionName)||<a href="PurchRequestForQuotationScoringMethodCriterionEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationScoringMethodCriterionEntity</a>|
|[CriterionDescription](#CriterionDescription)||<a href="PurchRequestForQuotationScoringMethodCriterionEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationScoringMethodCriterionEntity</a>|
|[MinimumPoints](#MinimumPoints)||<a href="PurchRequestForQuotationScoringMethodCriterionEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationScoringMethodCriterionEntity</a>|
|[MaximumPoints](#MaximumPoints)||<a href="PurchRequestForQuotationScoringMethodCriterionEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationScoringMethodCriterionEntity</a>|
|[BackingTable_PurchRFQScoringMethodCriteriaRelationshipId](#BackingTable_PurchRFQScoringMethodCriteriaRelationshipId)||<a href="PurchRequestForQuotationScoringMethodCriterionEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationScoringMethodCriterionEntity</a>|

### <a href=#RFQScoringMethodRecId name="RFQScoringMethodRecId">RFQScoringMethodRecId</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationScoringMethodCriterionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQScoringMethodRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RFQScoringMethodName name="RFQScoringMethodName">RFQScoringMethodName</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationScoringMethodCriterionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RFQScoringMethodName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CriterionName name="CriterionName">CriterionName</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationScoringMethodCriterionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CriterionName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CriterionDescription name="CriterionDescription">CriterionDescription</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationScoringMethodCriterionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CriterionDescription attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MinimumPoints name="MinimumPoints">MinimumPoints</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationScoringMethodCriterionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MinimumPoints attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MaximumPoints name="MaximumPoints">MaximumPoints</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationScoringMethodCriterionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaximumPoints attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_PurchRFQScoringMethodCriteriaRelationshipId name="BackingTable_PurchRFQScoringMethodCriteriaRelationshipId">BackingTable_PurchRFQScoringMethodCriteriaRelationshipId</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationScoringMethodCriterionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PurchRFQScoringMethodCriteriaRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Main/PurchRFQScoringMethodCriteria.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Main/PurchRFQScoringMethodCriteria.cdm.json/PurchRFQScoringMethodCriteria</a></td><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Main/PurchRFQScoringMethodCriteria.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
