---
title: PayrollBenefitPlanDefaultDimensionEntity in Payroll - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: reference
ms.date: 8/7/2020
ms.author: weiluo
---

# Benefit plan default dimension in Payroll(PayrollBenefitPlanDefaultDimensionEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/HumanResources/Payroll/PayrollBenefitPlanDefaultDimensionEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Benefit plan default dimension</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[Plan](#Plan)||<a href="PayrollBenefitPlanDefaultDimensionEntity.md" target="_blank">Payroll/PayrollBenefitPlanDefaultDimensionEntity</a>|
|[Company](#Company)||<a href="PayrollBenefitPlanDefaultDimensionEntity.md" target="_blank">Payroll/PayrollBenefitPlanDefaultDimensionEntity</a>|
|[Category](#Category)||<a href="PayrollBenefitPlanDefaultDimensionEntity.md" target="_blank">Payroll/PayrollBenefitPlanDefaultDimensionEntity</a>|
|[DefaultFinancialDimensions](#DefaultFinancialDimensions)||<a href="PayrollBenefitPlanDefaultDimensionEntity.md" target="_blank">Payroll/PayrollBenefitPlanDefaultDimensionEntity</a>|
|[LegalEntity](#LegalEntity)||<a href="PayrollBenefitPlanDefaultDimensionEntity.md" target="_blank">Payroll/PayrollBenefitPlanDefaultDimensionEntity</a>|
|[Vendor](#Vendor)||<a href="PayrollBenefitPlanDefaultDimensionEntity.md" target="_blank">Payroll/PayrollBenefitPlanDefaultDimensionEntity</a>|
|[CompanyId](#CompanyId)||<a href="PayrollBenefitPlanDefaultDimensionEntity.md" target="_blank">Payroll/PayrollBenefitPlanDefaultDimensionEntity</a>|
|[LegalEntityId](#LegalEntityId)||<a href="PayrollBenefitPlanDefaultDimensionEntity.md" target="_blank">Payroll/PayrollBenefitPlanDefaultDimensionEntity</a>|
|[BenefitPlanId](#BenefitPlanId)||<a href="PayrollBenefitPlanDefaultDimensionEntity.md" target="_blank">Payroll/PayrollBenefitPlanDefaultDimensionEntity</a>|
|[DefaultFinancialDimensionsDisplayValue](#DefaultFinancialDimensionsDisplayValue)||<a href="PayrollBenefitPlanDefaultDimensionEntity.md" target="_blank">Payroll/PayrollBenefitPlanDefaultDimensionEntity</a>|
|[Relationship_DefaultFinancialDimensionsDimensionSetRelationshipId](#Relationship_DefaultFinancialDimensionsDimensionSetRelationshipId)||<a href="PayrollBenefitPlanDefaultDimensionEntity.md" target="_blank">Payroll/PayrollBenefitPlanDefaultDimensionEntity</a>|
|[BackingTable_PayrollBenefitPlanDefaultDimensionRelationshipId](#BackingTable_PayrollBenefitPlanDefaultDimensionRelationshipId)||<a href="PayrollBenefitPlanDefaultDimensionEntity.md" target="_blank">Payroll/PayrollBenefitPlanDefaultDimensionEntity</a>|

### <a href=#Plan name="Plan">Plan</a>

First included in: Payroll/PayrollBenefitPlanDefaultDimensionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Plan attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Company name="Company">Company</a>

First included in: Payroll/PayrollBenefitPlanDefaultDimensionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Company attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Category name="Category">Category</a>

First included in: Payroll/PayrollBenefitPlanDefaultDimensionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Category attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultFinancialDimensions name="DefaultFinancialDimensions">DefaultFinancialDimensions</a>

First included in: Payroll/PayrollBenefitPlanDefaultDimensionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultFinancialDimensions attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LegalEntity name="LegalEntity">LegalEntity</a>

First included in: Payroll/PayrollBenefitPlanDefaultDimensionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LegalEntity attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Vendor name="Vendor">Vendor</a>

First included in: Payroll/PayrollBenefitPlanDefaultDimensionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Vendor attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CompanyId name="CompanyId">CompanyId</a>

First included in: Payroll/PayrollBenefitPlanDefaultDimensionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CompanyId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LegalEntityId name="LegalEntityId">LegalEntityId</a>

First included in: Payroll/PayrollBenefitPlanDefaultDimensionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LegalEntityId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BenefitPlanId name="BenefitPlanId">BenefitPlanId</a>

First included in: Payroll/PayrollBenefitPlanDefaultDimensionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BenefitPlanId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DefaultFinancialDimensionsDisplayValue name="DefaultFinancialDimensionsDisplayValue">DefaultFinancialDimensionsDisplayValue</a>

First included in: Payroll/PayrollBenefitPlanDefaultDimensionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default financial dimensions</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DefaultFinancialDimensionsDisplayValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Default financial dimensions</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultFinancialDimensionsDimensionSetRelationshipId name="Relationship_DefaultFinancialDimensionsDimensionSetRelationshipId">Relationship_DefaultFinancialDimensionsDimensionSetRelationshipId</a>

First included in: Payroll/PayrollBenefitPlanDefaultDimensionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultFinancialDimensionsDimensionSetRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_PayrollBenefitPlanDefaultDimensionRelationshipId name="BackingTable_PayrollBenefitPlanDefaultDimensionRelationshipId">BackingTable_PayrollBenefitPlanDefaultDimensionRelationshipId</a>

First included in: Payroll/PayrollBenefitPlanDefaultDimensionEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PayrollBenefitPlanDefaultDimensionRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/HumanResources/Payroll/Reference/PayrollBenefitPlanDefaultDimension.md" target="_blank">/core/operationsCommon/Tables/HumanResources/Payroll/Reference/PayrollBenefitPlanDefaultDimension.cdm.json/PayrollBenefitPlanDefaultDimension</a></td><td><a href="../../../Tables/HumanResources/Payroll/Reference/PayrollBenefitPlanDefaultDimension.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
