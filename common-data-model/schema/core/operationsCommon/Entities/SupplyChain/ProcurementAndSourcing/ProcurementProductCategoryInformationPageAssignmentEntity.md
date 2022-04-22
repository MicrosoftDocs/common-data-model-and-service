---
title: ProcurementProductCategoryInformationPageAssignmentEntity in ProcurementAndSourcing - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Procurement product category information page assignments in ProcurementAndSourcing(ProcurementProductCategoryInformationPageAssignmentEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProcurementAndSourcing/ProcurementProductCategoryInformationPageAssignmentEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Procurement product category information page assignments</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ProductCategoryHierarchyName](#ProductCategoryHierarchyName)||<a href="ProcurementProductCategoryInformationPageAssignmentEntity.md" target="_blank">ProcurementAndSourcing/ProcurementProductCategoryInformationPageAssignmentEntity</a>|
|[ProductCategoryName](#ProductCategoryName)||<a href="ProcurementProductCategoryInformationPageAssignmentEntity.md" target="_blank">ProcurementAndSourcing/ProcurementProductCategoryInformationPageAssignmentEntity</a>|
|[ProductCategoryInformationPageLegalEntityId](#ProductCategoryInformationPageLegalEntityId)||<a href="ProcurementProductCategoryInformationPageAssignmentEntity.md" target="_blank">ProcurementAndSourcing/ProcurementProductCategoryInformationPageAssignmentEntity</a>|
|[ProductCategoryInformationPageName](#ProductCategoryInformationPageName)||<a href="ProcurementProductCategoryInformationPageAssignmentEntity.md" target="_blank">ProcurementAndSourcing/ProcurementProductCategoryInformationPageAssignmentEntity</a>|
|[BackingTable_ProcCategoryCharterPagePolicyRelationshipId](#BackingTable_ProcCategoryCharterPagePolicyRelationshipId)||<a href="ProcurementProductCategoryInformationPageAssignmentEntity.md" target="_blank">ProcurementAndSourcing/ProcurementProductCategoryInformationPageAssignmentEntity</a>|

### <a href=#ProductCategoryHierarchyName name="ProductCategoryHierarchyName">ProductCategoryHierarchyName</a>

First included in: ProcurementAndSourcing/ProcurementProductCategoryInformationPageAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Product category hierarchy name</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductCategoryHierarchyName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Product category hierarchy name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductCategoryName name="ProductCategoryName">ProductCategoryName</a>

First included in: ProcurementAndSourcing/ProcurementProductCategoryInformationPageAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Product category name</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductCategoryName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Product category name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductCategoryInformationPageLegalEntityId name="ProductCategoryInformationPageLegalEntityId">ProductCategoryInformationPageLegalEntityId</a>

First included in: ProcurementAndSourcing/ProcurementProductCategoryInformationPageAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductCategoryInformationPageLegalEntityId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProductCategoryInformationPageName name="ProductCategoryInformationPageName">ProductCategoryInformationPageName</a>

First included in: ProcurementAndSourcing/ProcurementProductCategoryInformationPageAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Information page name</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductCategoryInformationPageName attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Information page name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_ProcCategoryCharterPagePolicyRelationshipId name="BackingTable_ProcCategoryCharterPagePolicyRelationshipId">BackingTable_ProcCategoryCharterPagePolicyRelationshipId</a>

First included in: ProcurementAndSourcing/ProcurementProductCategoryInformationPageAssignmentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_ProcCategoryCharterPagePolicyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Main/ProcCategoryCharterPagePolicy.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Main/ProcCategoryCharterPagePolicy.cdm.json/ProcCategoryCharterPagePolicy</a></td><td><a href="../../../Tables/SupplyChain/ProcurementAndSourcing/Main/ProcCategoryCharterPagePolicy.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
