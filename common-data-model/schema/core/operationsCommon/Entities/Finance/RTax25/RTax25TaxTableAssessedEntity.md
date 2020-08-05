---
title: RTax25TaxTableAssessedEntity in RTax25 - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/5/2020
ms.author: weiluo
---

# Sales tax relations (Assets) in RTax25(RTax25TaxTableAssessedEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/RTax25/RTax25TaxTableAssessedEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales tax relations (Assets)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[MainAccount](#MainAccount)||<a href="RTax25TaxTableAssessedEntity.md" target="_blank">RTax25/RTax25TaxTableAssessedEntity</a>|
|[TypeOfTax](#TypeOfTax)||<a href="RTax25TaxTableAssessedEntity.md" target="_blank">RTax25/RTax25TaxTableAssessedEntity</a>|
|[Code](#Code)||<a href="RTax25TaxTableAssessedEntity.md" target="_blank">RTax25/RTax25TaxTableAssessedEntity</a>|
|[Module](#Module)||<a href="RTax25TaxTableAssessedEntity.md" target="_blank">RTax25/RTax25TaxTableAssessedEntity</a>|
|[MainAccountDisplayValue](#MainAccountDisplayValue)||<a href="RTax25TaxTableAssessedEntity.md" target="_blank">RTax25/RTax25TaxTableAssessedEntity</a>|
|[BudgetRevenueCode](#BudgetRevenueCode)||<a href="RTax25TaxTableAssessedEntity.md" target="_blank">RTax25/RTax25TaxTableAssessedEntity</a>|
|[AllowanceByReductionOfRate](#AllowanceByReductionOfRate)||<a href="RTax25TaxTableAssessedEntity.md" target="_blank">RTax25/RTax25TaxTableAssessedEntity</a>|
|[AllowanceByReductionOfRateValue](#AllowanceByReductionOfRateValue)||<a href="RTax25TaxTableAssessedEntity.md" target="_blank">RTax25/RTax25TaxTableAssessedEntity</a>|
|[AllowanceByReductionOfTax](#AllowanceByReductionOfTax)||<a href="RTax25TaxTableAssessedEntity.md" target="_blank">RTax25/RTax25TaxTableAssessedEntity</a>|
|[AllowanceByReductionOfTaxValue](#AllowanceByReductionOfTaxValue)||<a href="RTax25TaxTableAssessedEntity.md" target="_blank">RTax25/RTax25TaxTableAssessedEntity</a>|
|[AllowanceDecreaseBase387](#AllowanceDecreaseBase387)||<a href="RTax25TaxTableAssessedEntity.md" target="_blank">RTax25/RTax25TaxTableAssessedEntity</a>|
|[AllowanceDecreaseBase387Value](#AllowanceDecreaseBase387Value)||<a href="RTax25TaxTableAssessedEntity.md" target="_blank">RTax25/RTax25TaxTableAssessedEntity</a>|
|[AllowanceDecreaseBase391](#AllowanceDecreaseBase391)||<a href="RTax25TaxTableAssessedEntity.md" target="_blank">RTax25/RTax25TaxTableAssessedEntity</a>|
|[AllowanceDecreaseBase391Value](#AllowanceDecreaseBase391Value)||<a href="RTax25TaxTableAssessedEntity.md" target="_blank">RTax25/RTax25TaxTableAssessedEntity</a>|
|[Relationship_MainAccountCombinationRelationshipId](#Relationship_MainAccountCombinationRelationshipId)||<a href="RTax25TaxTableAssessedEntity.md" target="_blank">RTax25/RTax25TaxTableAssessedEntity</a>|
|[BackingTable_RTax25TaxTableRelationshipId](#BackingTable_RTax25TaxTableRelationshipId)||<a href="RTax25TaxTableAssessedEntity.md" target="_blank">RTax25/RTax25TaxTableAssessedEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="RTax25TaxTableAssessedEntity.md" target="_blank">RTax25/RTax25TaxTableAssessedEntity</a>|

### <a href=#MainAccount name="MainAccount">MainAccount</a>

First included in: RTax25/RTax25TaxTableAssessedEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TypeOfTax name="TypeOfTax">TypeOfTax</a>

First included in: RTax25/RTax25TaxTableAssessedEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TypeOfTax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Code name="Code">Code</a>

First included in: RTax25/RTax25TaxTableAssessedEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Code attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Module name="Module">Module</a>

First included in: RTax25/RTax25TaxTableAssessedEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Module attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MainAccountDisplayValue name="MainAccountDisplayValue">MainAccountDisplayValue</a>

First included in: RTax25/RTax25TaxTableAssessedEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MainAccountDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BudgetRevenueCode name="BudgetRevenueCode">BudgetRevenueCode</a>

First included in: RTax25/RTax25TaxTableAssessedEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetRevenueCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowanceByReductionOfRate name="AllowanceByReductionOfRate">AllowanceByReductionOfRate</a>

First included in: RTax25/RTax25TaxTableAssessedEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowanceByReductionOfRate attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowanceByReductionOfRateValue name="AllowanceByReductionOfRateValue">AllowanceByReductionOfRateValue</a>

First included in: RTax25/RTax25TaxTableAssessedEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowanceByReductionOfRateValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowanceByReductionOfTax name="AllowanceByReductionOfTax">AllowanceByReductionOfTax</a>

First included in: RTax25/RTax25TaxTableAssessedEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowanceByReductionOfTax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowanceByReductionOfTaxValue name="AllowanceByReductionOfTaxValue">AllowanceByReductionOfTaxValue</a>

First included in: RTax25/RTax25TaxTableAssessedEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowanceByReductionOfTaxValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowanceDecreaseBase387 name="AllowanceDecreaseBase387">AllowanceDecreaseBase387</a>

First included in: RTax25/RTax25TaxTableAssessedEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowanceDecreaseBase387 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowanceDecreaseBase387Value name="AllowanceDecreaseBase387Value">AllowanceDecreaseBase387Value</a>

First included in: RTax25/RTax25TaxTableAssessedEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowanceDecreaseBase387Value attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowanceDecreaseBase391 name="AllowanceDecreaseBase391">AllowanceDecreaseBase391</a>

First included in: RTax25/RTax25TaxTableAssessedEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowanceDecreaseBase391 attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AllowanceDecreaseBase391Value name="AllowanceDecreaseBase391Value">AllowanceDecreaseBase391Value</a>

First included in: RTax25/RTax25TaxTableAssessedEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AllowanceDecreaseBase391Value attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_MainAccountCombinationRelationshipId name="Relationship_MainAccountCombinationRelationshipId">Relationship_MainAccountCombinationRelationshipId</a>

First included in: RTax25/RTax25TaxTableAssessedEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MainAccountCombinationRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_RTax25TaxTableRelationshipId name="BackingTable_RTax25TaxTableRelationshipId">BackingTable_RTax25TaxTableRelationshipId</a>

First included in: RTax25/RTax25TaxTableAssessedEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_RTax25TaxTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/RTax25/Group/RTax25TaxTable.md" target="_blank">/core/operationsCommon/Tables/Finance/RTax25/Group/RTax25TaxTable.cdm.json/RTax25TaxTable</a></td><td><a href="../../../Tables/Finance/RTax25/Group/RTax25TaxTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: RTax25/RTax25TaxTableAssessedEntity (this entity)  

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
