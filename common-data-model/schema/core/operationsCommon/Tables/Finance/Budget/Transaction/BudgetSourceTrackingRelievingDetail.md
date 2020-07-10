---
title: BudgetSourceTrackingRelievingDetail in Transaction - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/10/2020
ms.author: nebanfic
---

# Budget source tracking relieving details in Transaction(BudgetSourceTrackingRelievingDetail)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Budget/Transaction/BudgetSourceTrackingRelievingDetail.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BudgetSourceTrackingRelievingDetail/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Budget source tracking relieving details</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="BudgetSourceTrackingRelievingDetail.md" target="_blank">Transaction/BudgetSourceTrackingRelievingDetail</a>|
|[AccountingCurrencyAmount](#AccountingCurrencyAmount)||<a href="BudgetSourceTrackingRelievingDetail.md" target="_blank">Transaction/BudgetSourceTrackingRelievingDetail</a>|
|[IsDeletePending](#IsDeletePending)||<a href="BudgetSourceTrackingRelievingDetail.md" target="_blank">Transaction/BudgetSourceTrackingRelievingDetail</a>|
|[IsReturnOfBudgetFunds](#IsReturnOfBudgetFunds)||<a href="BudgetSourceTrackingRelievingDetail.md" target="_blank">Transaction/BudgetSourceTrackingRelievingDetail</a>|
|[IsSummarized](#IsSummarized)||<a href="BudgetSourceTrackingRelievingDetail.md" target="_blank">Transaction/BudgetSourceTrackingRelievingDetail</a>|
|[RelievedBudgetSourceTrackingDetail](#RelievedBudgetSourceTrackingDetail)||<a href="BudgetSourceTrackingRelievingDetail.md" target="_blank">Transaction/BudgetSourceTrackingRelievingDetail</a>|
|[RelievingBudgetSourceLedgerDimension](#RelievingBudgetSourceLedgerDimension)||<a href="BudgetSourceTrackingRelievingDetail.md" target="_blank">Transaction/BudgetSourceTrackingRelievingDetail</a>|
|[RelievingBudgetSourceTracking](#RelievingBudgetSourceTracking)||<a href="BudgetSourceTrackingRelievingDetail.md" target="_blank">Transaction/BudgetSourceTrackingRelievingDetail</a>|
|[Relationship_RelievedBudgetSourceTrackingDetailRelationshipId](#Relationship_RelievedBudgetSourceTrackingDetailRelationshipId)||<a href="BudgetSourceTrackingRelievingDetail.md" target="_blank">Transaction/BudgetSourceTrackingRelievingDetail</a>|
|[Relationship_RelievingBudgetSourceLedgerDimensionRelationshipId](#Relationship_RelievingBudgetSourceLedgerDimensionRelationshipId)||<a href="BudgetSourceTrackingRelievingDetail.md" target="_blank">Transaction/BudgetSourceTrackingRelievingDetail</a>|
|[Relationship_RelievingBudgetSourceTrackingRelationshipId](#Relationship_RelievingBudgetSourceTrackingRelationshipId)||<a href="BudgetSourceTrackingRelievingDetail.md" target="_blank">Transaction/BudgetSourceTrackingRelievingDetail</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/BudgetSourceTrackingRelievingDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BudgetSourceTrackingRelievingDetail/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AccountingCurrencyAmount name="AccountingCurrencyAmount">AccountingCurrencyAmount</a>

First included in: Transaction/BudgetSourceTrackingRelievingDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountingCurrencyAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#IsDeletePending name="IsDeletePending">IsDeletePending</a>

First included in: Transaction/BudgetSourceTrackingRelievingDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsDeletePending attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#IsReturnOfBudgetFunds name="IsReturnOfBudgetFunds">IsReturnOfBudgetFunds</a>

First included in: Transaction/BudgetSourceTrackingRelievingDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsReturnOfBudgetFunds attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#IsSummarized name="IsSummarized">IsSummarized</a>

First included in: Transaction/BudgetSourceTrackingRelievingDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsSummarized attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#RelievedBudgetSourceTrackingDetail name="RelievedBudgetSourceTrackingDetail">RelievedBudgetSourceTrackingDetail</a>

First included in: Transaction/BudgetSourceTrackingRelievingDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Relieved budget source tracking detail</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RelievedBudgetSourceTrackingDetail attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Relieved budget source tracking detail</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RelievingBudgetSourceLedgerDimension name="RelievingBudgetSourceLedgerDimension">RelievingBudgetSourceLedgerDimension</a>

First included in: Transaction/BudgetSourceTrackingRelievingDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RelievingBudgetSourceLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RelievingBudgetSourceTracking name="RelievingBudgetSourceTracking">RelievingBudgetSourceTracking</a>

First included in: Transaction/BudgetSourceTrackingRelievingDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Relieving budget source tracking detail</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RelievingBudgetSourceTracking attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Relieving budget source tracking detail</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_RelievedBudgetSourceTrackingDetailRelationshipId name="Relationship_RelievedBudgetSourceTrackingDetailRelationshipId">Relationship_RelievedBudgetSourceTrackingDetailRelationshipId</a>

First included in: Transaction/BudgetSourceTrackingRelievingDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RelievedBudgetSourceTrackingDetailRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="BudgetSourceTrackingDetail.md" target="_blank">/core/operationsCommon/Tables/Finance/Budget/Transaction/BudgetSourceTrackingDetail.cdm.json/BudgetSourceTrackingDetail</a></td><td><a href="BudgetSourceTrackingDetail.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RelievingBudgetSourceLedgerDimensionRelationshipId name="Relationship_RelievingBudgetSourceLedgerDimensionRelationshipId">Relationship_RelievingBudgetSourceLedgerDimensionRelationshipId</a>

First included in: Transaction/BudgetSourceTrackingRelievingDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RelievingBudgetSourceLedgerDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md" target="_blank">/core/operationsCommon/Tables/Finance/FinancialDimensions/Main/DimensionAttributeValueCombination.cdm.json/DimensionAttributeValueCombination</a></td><td><a href="../../FinancialDimensions/Main/DimensionAttributeValueCombination.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_RelievingBudgetSourceTrackingRelationshipId name="Relationship_RelievingBudgetSourceTrackingRelationshipId">Relationship_RelievingBudgetSourceTrackingRelationshipId</a>

First included in: Transaction/BudgetSourceTrackingRelievingDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_RelievingBudgetSourceTrackingRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="BudgetSourceTracking.md" target="_blank">/core/operationsCommon/Tables/Finance/Budget/Transaction/BudgetSourceTracking.cdm.json/BudgetSourceTracking</a></td><td><a href="BudgetSourceTracking.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
