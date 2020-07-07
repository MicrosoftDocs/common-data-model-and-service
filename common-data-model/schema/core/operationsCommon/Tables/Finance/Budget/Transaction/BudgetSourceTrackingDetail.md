---
title: BudgetSourceTrackingDetail in Transaction - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/7/2020
ms.author: nebanfic
---

# Budget source tracking detail in Transaction

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Budget/Transaction/BudgetSourceTrackingDetail.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BudgetSourceTrackingDetail/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Budget source tracking detail</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="BudgetSourceTrackingDetail.md" target="_blank">Transaction/BudgetSourceTrackingDetail</a>|
|[AccountingCurrencyAmount](#AccountingCurrencyAmount)||<a href="BudgetSourceTrackingDetail.md" target="_blank">Transaction/BudgetSourceTrackingDetail</a>|
|[BudgetControlLedgerDimension](#BudgetControlLedgerDimension)||<a href="BudgetSourceTrackingDetail.md" target="_blank">Transaction/BudgetSourceTrackingDetail</a>|
|[BudgetControlRule](#BudgetControlRule)||<a href="BudgetSourceTrackingDetail.md" target="_blank">Transaction/BudgetSourceTrackingDetail</a>|
|[BudgetGroupMember](#BudgetGroupMember)||<a href="BudgetSourceTrackingDetail.md" target="_blank">Transaction/BudgetSourceTrackingDetail</a>|
|[BudgetSourceLedgerDimension](#BudgetSourceLedgerDimension)||<a href="BudgetSourceTrackingDetail.md" target="_blank">Transaction/BudgetSourceTrackingDetail</a>|
|[BudgetSourceTracking](#BudgetSourceTracking)||<a href="BudgetSourceTrackingDetail.md" target="_blank">Transaction/BudgetSourceTrackingDetail</a>|
|[IsCarryForward](#IsCarryForward)||<a href="BudgetSourceTrackingDetail.md" target="_blank">Transaction/BudgetSourceTrackingDetail</a>|
|[IsDeletePending](#IsDeletePending)||<a href="BudgetSourceTrackingDetail.md" target="_blank">Transaction/BudgetSourceTrackingDetail</a>|
|[IsReturnOfBudgetFunds](#IsReturnOfBudgetFunds)||<a href="BudgetSourceTrackingDetail.md" target="_blank">Transaction/BudgetSourceTrackingDetail</a>|
|[IsSummarized](#IsSummarized)||<a href="BudgetSourceTrackingDetail.md" target="_blank">Transaction/BudgetSourceTrackingDetail</a>|
|[PrimaryLedger](#PrimaryLedger)||<a href="BudgetSourceTrackingDetail.md" target="_blank">Transaction/BudgetSourceTrackingDetail</a>|
|[Relationship_BudgetControlLedgerDimensionRelationshipId](#Relationship_BudgetControlLedgerDimensionRelationshipId)||<a href="BudgetSourceTrackingDetail.md" target="_blank">Transaction/BudgetSourceTrackingDetail</a>|
|[Relationship_BudgetControlRuleRelationshipId](#Relationship_BudgetControlRuleRelationshipId)||<a href="BudgetSourceTrackingDetail.md" target="_blank">Transaction/BudgetSourceTrackingDetail</a>|
|[Relationship_BudgetGroupMemberRelationshipId](#Relationship_BudgetGroupMemberRelationshipId)||<a href="BudgetSourceTrackingDetail.md" target="_blank">Transaction/BudgetSourceTrackingDetail</a>|
|[Relationship_BudgetSourceLedgerDimensionRelationshipId](#Relationship_BudgetSourceLedgerDimensionRelationshipId)||<a href="BudgetSourceTrackingDetail.md" target="_blank">Transaction/BudgetSourceTrackingDetail</a>|
|[Relationship_BudgetSourceTrackingRelationshipId](#Relationship_BudgetSourceTrackingRelationshipId)||<a href="BudgetSourceTrackingDetail.md" target="_blank">Transaction/BudgetSourceTrackingDetail</a>|
|[Relationship_PrimaryLedgerRelationshipId](#Relationship_PrimaryLedgerRelationshipId)||<a href="BudgetSourceTrackingDetail.md" target="_blank">Transaction/BudgetSourceTrackingDetail</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/BudgetSourceTrackingDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BudgetSourceTrackingDetail/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AccountingCurrencyAmount name="AccountingCurrencyAmount">AccountingCurrencyAmount</a>

First included in: Transaction/BudgetSourceTrackingDetail (this entity)  

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

### <a href=#BudgetControlLedgerDimension name="BudgetControlLedgerDimension">BudgetControlLedgerDimension</a>

First included in: Transaction/BudgetSourceTrackingDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Budget control dimension</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetControlLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Budget control dimension</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BudgetControlRule name="BudgetControlRule">BudgetControlRule</a>

First included in: Transaction/BudgetSourceTrackingDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetControlRule attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BudgetGroupMember name="BudgetGroupMember">BudgetGroupMember</a>

First included in: Transaction/BudgetSourceTrackingDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetGroupMember attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BudgetSourceLedgerDimension name="BudgetSourceLedgerDimension">BudgetSourceLedgerDimension</a>

First included in: Transaction/BudgetSourceTrackingDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Budget source ledger account</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetSourceLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Budget source ledger account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BudgetSourceTracking name="BudgetSourceTracking">BudgetSourceTracking</a>

First included in: Transaction/BudgetSourceTrackingDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Budget source tracking</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetSourceTracking attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Budget source tracking</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#IsCarryForward name="IsCarryForward">IsCarryForward</a>

First included in: Transaction/BudgetSourceTrackingDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCarryForward attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#IsDeletePending name="IsDeletePending">IsDeletePending</a>

First included in: Transaction/BudgetSourceTrackingDetail (this entity)  

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

First included in: Transaction/BudgetSourceTrackingDetail (this entity)  

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

First included in: Transaction/BudgetSourceTrackingDetail (this entity)  

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

### <a href=#PrimaryLedger name="PrimaryLedger">PrimaryLedger</a>

First included in: Transaction/BudgetSourceTrackingDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryLedger attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_BudgetControlLedgerDimensionRelationshipId name="Relationship_BudgetControlLedgerDimensionRelationshipId">Relationship_BudgetControlLedgerDimensionRelationshipId</a>

First included in: Transaction/BudgetSourceTrackingDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BudgetControlLedgerDimensionRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_BudgetControlRuleRelationshipId name="Relationship_BudgetControlRuleRelationshipId">Relationship_BudgetControlRuleRelationshipId</a>

First included in: Transaction/BudgetSourceTrackingDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BudgetControlRuleRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/BudgetControlRule.md" target="_blank">/core/operationsCommon/Tables/Finance/Budget/Group/BudgetControlRule.cdm.json/BudgetControlRule</a></td><td><a href="../Group/BudgetControlRule.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BudgetGroupMemberRelationshipId name="Relationship_BudgetGroupMemberRelationshipId">Relationship_BudgetGroupMemberRelationshipId</a>

First included in: Transaction/BudgetSourceTrackingDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BudgetGroupMemberRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/BudgetGroupMember.md" target="_blank">/core/operationsCommon/Tables/Finance/Budget/Group/BudgetGroupMember.cdm.json/BudgetGroupMember</a></td><td><a href="../Group/BudgetGroupMember.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BudgetSourceLedgerDimensionRelationshipId name="Relationship_BudgetSourceLedgerDimensionRelationshipId">Relationship_BudgetSourceLedgerDimensionRelationshipId</a>

First included in: Transaction/BudgetSourceTrackingDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BudgetSourceLedgerDimensionRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_BudgetSourceTrackingRelationshipId name="Relationship_BudgetSourceTrackingRelationshipId">Relationship_BudgetSourceTrackingRelationshipId</a>

First included in: Transaction/BudgetSourceTrackingDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BudgetSourceTrackingRelationshipId attribute are listed below.</summary>

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

### <a href=#Relationship_PrimaryLedgerRelationshipId name="Relationship_PrimaryLedgerRelationshipId">Relationship_PrimaryLedgerRelationshipId</a>

First included in: Transaction/BudgetSourceTrackingDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PrimaryLedgerRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Ledger/Main/Ledger.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/Ledger.cdm.json/Ledger</a></td><td><a href="../../Ledger/Main/Ledger.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
