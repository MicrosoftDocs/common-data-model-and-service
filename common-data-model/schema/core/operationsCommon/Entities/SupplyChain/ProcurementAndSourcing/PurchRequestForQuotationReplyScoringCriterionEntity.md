---
title: PurchRequestForQuotationReplyScoringCriterionEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Request for quotation reply scoring criteria

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/PurchRequestForQuotationReplyScoringCriterionEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Request for quotation reply scoring criteria</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RFQNumber](#RFQNumber)||<a href="PurchRequestForQuotationReplyScoringCriterionEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyScoringCriterionEntity</a>|
|[CriterionScore](#CriterionScore)||<a href="PurchRequestForQuotationReplyScoringCriterionEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyScoringCriterionEntity</a>|
|[CriterionName](#CriterionName)||<a href="PurchRequestForQuotationReplyScoringCriterionEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyScoringCriterionEntity</a>|
|[VendorRFQReplyStatusCode](#VendorRFQReplyStatusCode)||<a href="PurchRequestForQuotationReplyScoringCriterionEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyScoringCriterionEntity</a>|
|[VendorScoringStatusComment](#VendorScoringStatusComment)||<a href="PurchRequestForQuotationReplyScoringCriterionEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyScoringCriterionEntity</a>|
|[CriterionId](#CriterionId)||<a href="PurchRequestForQuotationReplyScoringCriterionEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyScoringCriterionEntity</a>|
|[VendorAccountNumber](#VendorAccountNumber)||<a href="PurchRequestForQuotationReplyScoringCriterionEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyScoringCriterionEntity</a>|
|[BackingTable_PurchRFQScoringRelationshipId](#BackingTable_PurchRFQScoringRelationshipId)||<a href="PurchRequestForQuotationReplyScoringCriterionEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyScoringCriterionEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="PurchRequestForQuotationReplyScoringCriterionEntity.md" target="_blank">ProcurementAndSourcing/PurchRequestForQuotationReplyScoringCriterionEntity</a>|

### <a href=#RFQNumber name="RFQNumber">RFQNumber</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyScoringCriterionEntity (this entity)  

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

### <a href=#CriterionScore name="CriterionScore">CriterionScore</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyScoringCriterionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CriterionScore attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CriterionName name="CriterionName">CriterionName</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyScoringCriterionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Criterion name</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CriterionName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Criterion name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorRFQReplyStatusCode name="VendorRFQReplyStatusCode">VendorRFQReplyStatusCode</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyScoringCriterionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Vendor reply status code</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorRFQReplyStatusCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Vendor reply status code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorScoringStatusComment name="VendorScoringStatusComment">VendorScoringStatusComment</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyScoringCriterionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Vendor scoring status comment</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorScoringStatusComment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Vendor scoring status comment</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CriterionId name="CriterionId">CriterionId</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyScoringCriterionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CriterionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#VendorAccountNumber name="VendorAccountNumber">VendorAccountNumber</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyScoringCriterionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendorAccountNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_PurchRFQScoringRelationshipId name="BackingTable_PurchRFQScoringRelationshipId">BackingTable_PurchRFQScoringRelationshipId</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyScoringCriterionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PurchRFQScoringRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/WorksheetLine/PurchRFQScoring.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/WorksheetLine/PurchRFQScoring.cdm.json/PurchRFQScoring</a></td><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/WorksheetLine/PurchRFQScoring.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProcurementAndSourcing/PurchRequestForQuotationReplyScoringCriterionEntity (this entity)  

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
