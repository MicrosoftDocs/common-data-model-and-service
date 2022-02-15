---
title: TaxWithholdLedgerAccountGroupEntity in Tax - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Withholding tax ledger posting groups in Tax(TaxWithholdLedgerAccountGroupEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/Tax/TaxWithholdLedgerAccountGroupEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Withholding tax ledger posting groups</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ExpenseLedgerDimension](#ExpenseLedgerDimension)||<a href="TaxWithholdLedgerAccountGroupEntity.md" target="_blank">Tax/TaxWithholdLedgerAccountGroupEntity</a>|
|[Name](#Name)||<a href="TaxWithholdLedgerAccountGroupEntity.md" target="_blank">Tax/TaxWithholdLedgerAccountGroupEntity</a>|
|[TaxWithhodlSettlementLedgerDimension](#TaxWithhodlSettlementLedgerDimension)||<a href="TaxWithholdLedgerAccountGroupEntity.md" target="_blank">Tax/TaxWithholdLedgerAccountGroupEntity</a>|
|[TaxWithholdAccountGroup](#TaxWithholdAccountGroup)||<a href="TaxWithholdLedgerAccountGroupEntity.md" target="_blank">Tax/TaxWithholdLedgerAccountGroupEntity</a>|
|[TaxWithholdLedgerDimension](#TaxWithholdLedgerDimension)||<a href="TaxWithholdLedgerAccountGroupEntity.md" target="_blank">Tax/TaxWithholdLedgerAccountGroupEntity</a>|
|[TaxWithholdOffsetLedgerDimension](#TaxWithholdOffsetLedgerDimension)||<a href="TaxWithholdLedgerAccountGroupEntity.md" target="_blank">Tax/TaxWithholdLedgerAccountGroupEntity</a>|
|[ExpenseLedgerDimensionDisplayValue](#ExpenseLedgerDimensionDisplayValue)||<a href="TaxWithholdLedgerAccountGroupEntity.md" target="_blank">Tax/TaxWithholdLedgerAccountGroupEntity</a>|
|[TaxWithhodlSettlementLedgerDimensionDisplayValue](#TaxWithhodlSettlementLedgerDimensionDisplayValue)||<a href="TaxWithholdLedgerAccountGroupEntity.md" target="_blank">Tax/TaxWithholdLedgerAccountGroupEntity</a>|
|[TaxWithholdLedgerDimensionDisplayValue](#TaxWithholdLedgerDimensionDisplayValue)||<a href="TaxWithholdLedgerAccountGroupEntity.md" target="_blank">Tax/TaxWithholdLedgerAccountGroupEntity</a>|
|[TaxWithholdOffsetLedgerDimensionDisplayValue](#TaxWithholdOffsetLedgerDimensionDisplayValue)||<a href="TaxWithholdLedgerAccountGroupEntity.md" target="_blank">Tax/TaxWithholdLedgerAccountGroupEntity</a>|
|[Relationship_ExpenseLedgerDimensionCombinationRelationshipId](#Relationship_ExpenseLedgerDimensionCombinationRelationshipId)||<a href="TaxWithholdLedgerAccountGroupEntity.md" target="_blank">Tax/TaxWithholdLedgerAccountGroupEntity</a>|
|[Relationship_TaxWithhodlSettlementLedgerDimensionCombinationRelationshipId](#Relationship_TaxWithhodlSettlementLedgerDimensionCombinationRelationshipId)||<a href="TaxWithholdLedgerAccountGroupEntity.md" target="_blank">Tax/TaxWithholdLedgerAccountGroupEntity</a>|
|[Relationship_TaxWithholdLedgerDimensionCombinationRelationshipId](#Relationship_TaxWithholdLedgerDimensionCombinationRelationshipId)||<a href="TaxWithholdLedgerAccountGroupEntity.md" target="_blank">Tax/TaxWithholdLedgerAccountGroupEntity</a>|
|[Relationship_TaxWithholdOffsetLedgerDimensionCombinationRelationshipId](#Relationship_TaxWithholdOffsetLedgerDimensionCombinationRelationshipId)||<a href="TaxWithholdLedgerAccountGroupEntity.md" target="_blank">Tax/TaxWithholdLedgerAccountGroupEntity</a>|
|[BackingTable_TaxWithholdLedgerAccountGroup_THRelationshipId](#BackingTable_TaxWithholdLedgerAccountGroup_THRelationshipId)||<a href="TaxWithholdLedgerAccountGroupEntity.md" target="_blank">Tax/TaxWithholdLedgerAccountGroupEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="TaxWithholdLedgerAccountGroupEntity.md" target="_blank">Tax/TaxWithholdLedgerAccountGroupEntity</a>|

### <a href=#ExpenseLedgerDimension name="ExpenseLedgerDimension">ExpenseLedgerDimension</a>

First included in: Tax/TaxWithholdLedgerAccountGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Expense account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpenseLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Expense account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Name name="Name">Name</a>

First included in: Tax/TaxWithholdLedgerAccountGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Name attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxWithhodlSettlementLedgerDimension name="TaxWithhodlSettlementLedgerDimension">TaxWithhodlSettlementLedgerDimension</a>

First included in: Tax/TaxWithholdLedgerAccountGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Settlement account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithhodlSettlementLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Settlement account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxWithholdAccountGroup name="TaxWithholdAccountGroup">TaxWithholdAccountGroup</a>

First included in: Tax/TaxWithholdLedgerAccountGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ledger posting group</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdAccountGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Ledger posting group</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxWithholdLedgerDimension name="TaxWithholdLedgerDimension">TaxWithholdLedgerDimension</a>

First included in: Tax/TaxWithholdLedgerAccountGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Withholding tax</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Withholding tax</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxWithholdOffsetLedgerDimension name="TaxWithholdOffsetLedgerDimension">TaxWithholdOffsetLedgerDimension</a>

First included in: Tax/TaxWithholdLedgerAccountGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Withholding tax offset</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdOffsetLedgerDimension attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Withholding tax offset</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExpenseLedgerDimensionDisplayValue name="ExpenseLedgerDimensionDisplayValue">ExpenseLedgerDimensionDisplayValue</a>

First included in: Tax/TaxWithholdLedgerAccountGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Expense account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExpenseLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Expense account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxWithhodlSettlementLedgerDimensionDisplayValue name="TaxWithhodlSettlementLedgerDimensionDisplayValue">TaxWithhodlSettlementLedgerDimensionDisplayValue</a>

First included in: Tax/TaxWithholdLedgerAccountGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Settlement account</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithhodlSettlementLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Settlement account</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxWithholdLedgerDimensionDisplayValue name="TaxWithholdLedgerDimensionDisplayValue">TaxWithholdLedgerDimensionDisplayValue</a>

First included in: Tax/TaxWithholdLedgerAccountGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Withholding tax</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Withholding tax</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxWithholdOffsetLedgerDimensionDisplayValue name="TaxWithholdOffsetLedgerDimensionDisplayValue">TaxWithholdOffsetLedgerDimensionDisplayValue</a>

First included in: Tax/TaxWithholdLedgerAccountGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Withholding tax offset</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxWithholdOffsetLedgerDimensionDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Withholding tax offset</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ExpenseLedgerDimensionCombinationRelationshipId name="Relationship_ExpenseLedgerDimensionCombinationRelationshipId">Relationship_ExpenseLedgerDimensionCombinationRelationshipId</a>

First included in: Tax/TaxWithholdLedgerAccountGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ExpenseLedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxWithhodlSettlementLedgerDimensionCombinationRelationshipId name="Relationship_TaxWithhodlSettlementLedgerDimensionCombinationRelationshipId">Relationship_TaxWithhodlSettlementLedgerDimensionCombinationRelationshipId</a>

First included in: Tax/TaxWithholdLedgerAccountGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxWithhodlSettlementLedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxWithholdLedgerDimensionCombinationRelationshipId name="Relationship_TaxWithholdLedgerDimensionCombinationRelationshipId">Relationship_TaxWithholdLedgerDimensionCombinationRelationshipId</a>

First included in: Tax/TaxWithholdLedgerAccountGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxWithholdLedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxWithholdOffsetLedgerDimensionCombinationRelationshipId name="Relationship_TaxWithholdOffsetLedgerDimensionCombinationRelationshipId">Relationship_TaxWithholdOffsetLedgerDimensionCombinationRelationshipId</a>

First included in: Tax/TaxWithholdLedgerAccountGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxWithholdOffsetLedgerDimensionCombinationRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td>empty table</td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_TaxWithholdLedgerAccountGroup_THRelationshipId name="BackingTable_TaxWithholdLedgerAccountGroup_THRelationshipId">BackingTable_TaxWithholdLedgerAccountGroup_THRelationshipId</a>

First included in: Tax/TaxWithholdLedgerAccountGroupEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_TaxWithholdLedgerAccountGroup_THRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Tax/Group/TaxWithholdLedgerAccountGroup_TH.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Group/TaxWithholdLedgerAccountGroup_TH.cdm.json/TaxWithholdLedgerAccountGroup_TH</a></td><td><a href="../../../Tables/Finance/Tax/Group/TaxWithholdLedgerAccountGroup_TH.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: Tax/TaxWithholdLedgerAccountGroupEntity (this entity)  

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
