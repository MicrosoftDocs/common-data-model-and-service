---
title: BudgetCheckResultErrorWarningDetail in Transaction - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/13/2020
ms.author: nebanfic
---

# Budget check result error warning detail in Transaction(BudgetCheckResultErrorWarningDetail)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Budget/Transaction/BudgetCheckResultErrorWarningDetail.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BudgetCheckResultErrorWarningDetail/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Budget check result error warning detail</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="BudgetCheckResultErrorWarningDetail.md" target="_blank">Transaction/BudgetCheckResultErrorWarningDetail</a>|
|[AccountingCurrencyAmountOverAvailable](#AccountingCurrencyAmountOverAvailable)||<a href="BudgetCheckResultErrorWarningDetail.md" target="_blank">Transaction/BudgetCheckResultErrorWarningDetail</a>|
|[AccountingCurrencyAmountOverThreshold](#AccountingCurrencyAmountOverThreshold)||<a href="BudgetCheckResultErrorWarningDetail.md" target="_blank">Transaction/BudgetCheckResultErrorWarningDetail</a>|
|[BudgetControlLedgerDimension](#BudgetControlLedgerDimension)||<a href="BudgetCheckResultErrorWarningDetail.md" target="_blank">Transaction/BudgetCheckResultErrorWarningDetail</a>|
|[BudgetGroupMember](#BudgetGroupMember)||<a href="BudgetCheckResultErrorWarningDetail.md" target="_blank">Transaction/BudgetCheckResultErrorWarningDetail</a>|
|[BudgetSource](#BudgetSource)||<a href="BudgetCheckResultErrorWarningDetail.md" target="_blank">Transaction/BudgetCheckResultErrorWarningDetail</a>|
|[BudgetSourceLedgerDimension](#BudgetSourceLedgerDimension)||<a href="BudgetCheckResultErrorWarningDetail.md" target="_blank">Transaction/BudgetCheckResultErrorWarningDetail</a>|
|[CheckResult](#CheckResult)||<a href="BudgetCheckResultErrorWarningDetail.md" target="_blank">Transaction/BudgetCheckResultErrorWarningDetail</a>|
|[CheckResultErrorWarning](#CheckResultErrorWarning)||<a href="BudgetCheckResultErrorWarningDetail.md" target="_blank">Transaction/BudgetCheckResultErrorWarningDetail</a>|
|[CheckResultErrorWarningType](#CheckResultErrorWarningType)||<a href="BudgetCheckResultErrorWarningDetail.md" target="_blank">Transaction/BudgetCheckResultErrorWarningDetail</a>|
|[PrimaryLedger](#PrimaryLedger)||<a href="BudgetCheckResultErrorWarningDetail.md" target="_blank">Transaction/BudgetCheckResultErrorWarningDetail</a>|
|[SequenceNumber](#SequenceNumber)||<a href="BudgetCheckResultErrorWarningDetail.md" target="_blank">Transaction/BudgetCheckResultErrorWarningDetail</a>|
|[Relationship_BudgetControlLedgerDimensionRelationshipId](#Relationship_BudgetControlLedgerDimensionRelationshipId)||<a href="BudgetCheckResultErrorWarningDetail.md" target="_blank">Transaction/BudgetCheckResultErrorWarningDetail</a>|
|[Relationship_BudgetGroupMemberRelationshipId](#Relationship_BudgetGroupMemberRelationshipId)||<a href="BudgetCheckResultErrorWarningDetail.md" target="_blank">Transaction/BudgetCheckResultErrorWarningDetail</a>|
|[Relationship_BudgetSourceRelationshipId](#Relationship_BudgetSourceRelationshipId)||<a href="BudgetCheckResultErrorWarningDetail.md" target="_blank">Transaction/BudgetCheckResultErrorWarningDetail</a>|
|[Relationship_BudgetSourceLedgerDimensionRelationshipId](#Relationship_BudgetSourceLedgerDimensionRelationshipId)||<a href="BudgetCheckResultErrorWarningDetail.md" target="_blank">Transaction/BudgetCheckResultErrorWarningDetail</a>|
|[Relationship_PrimaryLedgerRelationshipId](#Relationship_PrimaryLedgerRelationshipId)||<a href="BudgetCheckResultErrorWarningDetail.md" target="_blank">Transaction/BudgetCheckResultErrorWarningDetail</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/BudgetCheckResultErrorWarningDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[BudgetCheckResultErrorWarningDetail/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AccountingCurrencyAmountOverAvailable name="AccountingCurrencyAmountOverAvailable">AccountingCurrencyAmountOverAvailable</a>

First included in: Transaction/BudgetCheckResultErrorWarningDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountingCurrencyAmountOverAvailable attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#AccountingCurrencyAmountOverThreshold name="AccountingCurrencyAmountOverThreshold">AccountingCurrencyAmountOverThreshold</a>

First included in: Transaction/BudgetCheckResultErrorWarningDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AccountingCurrencyAmountOverThreshold attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#BudgetControlLedgerDimension name="BudgetControlLedgerDimension">BudgetControlLedgerDimension</a>

First included in: Transaction/BudgetCheckResultErrorWarningDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Budget control dimension value</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetControlLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Budget control dimension value</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BudgetGroupMember name="BudgetGroupMember">BudgetGroupMember</a>

First included in: Transaction/BudgetCheckResultErrorWarningDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Budget group</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetGroupMember attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Budget group</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BudgetSource name="BudgetSource">BudgetSource</a>

First included in: Transaction/BudgetCheckResultErrorWarningDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Budget source</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetSource attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Budget source</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BudgetSourceLedgerDimension name="BudgetSourceLedgerDimension">BudgetSourceLedgerDimension</a>

First included in: Transaction/BudgetCheckResultErrorWarningDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ledger account</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetSourceLedgerDimension attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Ledger account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CheckResult name="CheckResult">CheckResult</a>

First included in: Transaction/BudgetCheckResultErrorWarningDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CheckResult attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CheckResultErrorWarning name="CheckResultErrorWarning">CheckResultErrorWarning</a>

First included in: Transaction/BudgetCheckResultErrorWarningDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CheckResultErrorWarning attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CheckResultErrorWarningType name="CheckResultErrorWarningType">CheckResultErrorWarningType</a>

First included in: Transaction/BudgetCheckResultErrorWarningDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CheckResultErrorWarningType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PrimaryLedger name="PrimaryLedger">PrimaryLedger</a>

First included in: Transaction/BudgetCheckResultErrorWarningDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PrimaryLedger attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SequenceNumber name="SequenceNumber">SequenceNumber</a>

First included in: Transaction/BudgetCheckResultErrorWarningDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sequence number</td></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SequenceNumber attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sequence number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_BudgetControlLedgerDimensionRelationshipId name="Relationship_BudgetControlLedgerDimensionRelationshipId">Relationship_BudgetControlLedgerDimensionRelationshipId</a>

First included in: Transaction/BudgetCheckResultErrorWarningDetail (this entity)  

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

### <a href=#Relationship_BudgetGroupMemberRelationshipId name="Relationship_BudgetGroupMemberRelationshipId">Relationship_BudgetGroupMemberRelationshipId</a>

First included in: Transaction/BudgetCheckResultErrorWarningDetail (this entity)  

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

### <a href=#Relationship_BudgetSourceRelationshipId name="Relationship_BudgetSourceRelationshipId">Relationship_BudgetSourceRelationshipId</a>

First included in: Transaction/BudgetCheckResultErrorWarningDetail (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BudgetSourceRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="BudgetSource.md" target="_blank">/core/operationsCommon/Tables/Finance/Budget/Transaction/BudgetSource.cdm.json/BudgetSource</a></td><td><a href="BudgetSource.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BudgetSourceLedgerDimensionRelationshipId name="Relationship_BudgetSourceLedgerDimensionRelationshipId">Relationship_BudgetSourceLedgerDimensionRelationshipId</a>

First included in: Transaction/BudgetCheckResultErrorWarningDetail (this entity)  

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

### <a href=#Relationship_PrimaryLedgerRelationshipId name="Relationship_PrimaryLedgerRelationshipId">Relationship_PrimaryLedgerRelationshipId</a>

First included in: Transaction/BudgetCheckResultErrorWarningDetail (this entity)  

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
