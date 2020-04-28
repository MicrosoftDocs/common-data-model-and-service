---
title: PayrollBenefitTaxRuleUSEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/28/2020
ms.author: nebanfic
---

# Benefit Tax Rule US

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/HumanResources/Payroll/PayrollBenefitTaxRuleUSEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Benefit Tax Rule US</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[BenefitPlan](#BenefitPlan)||<a href="PayrollBenefitTaxRuleUSEntity.md" target="_blank">Payroll/PayrollBenefitTaxRuleUSEntity</a>|
|[CustomPretaxMethod](#CustomPretaxMethod)||<a href="PayrollBenefitTaxRuleUSEntity.md" target="_blank">Payroll/PayrollBenefitTaxRuleUSEntity</a>|
|[IsExemptFromFederalIncomeTax](#IsExemptFromFederalIncomeTax)||<a href="PayrollBenefitTaxRuleUSEntity.md" target="_blank">Payroll/PayrollBenefitTaxRuleUSEntity</a>|
|[IsExemptFromFICA](#IsExemptFromFICA)||<a href="PayrollBenefitTaxRuleUSEntity.md" target="_blank">Payroll/PayrollBenefitTaxRuleUSEntity</a>|
|[IsExemptFromLocalIncomeTax](#IsExemptFromLocalIncomeTax)||<a href="PayrollBenefitTaxRuleUSEntity.md" target="_blank">Payroll/PayrollBenefitTaxRuleUSEntity</a>|
|[IsExemptFromMedicare](#IsExemptFromMedicare)||<a href="PayrollBenefitTaxRuleUSEntity.md" target="_blank">Payroll/PayrollBenefitTaxRuleUSEntity</a>|
|[IsExemptFromStateDisabilityInsurance](#IsExemptFromStateDisabilityInsurance)||<a href="PayrollBenefitTaxRuleUSEntity.md" target="_blank">Payroll/PayrollBenefitTaxRuleUSEntity</a>|
|[IsExemptFromStateIncomeTax](#IsExemptFromStateIncomeTax)||<a href="PayrollBenefitTaxRuleUSEntity.md" target="_blank">Payroll/PayrollBenefitTaxRuleUSEntity</a>|
|[IsExemptFromStateUnemployment](#IsExemptFromStateUnemployment)||<a href="PayrollBenefitTaxRuleUSEntity.md" target="_blank">Payroll/PayrollBenefitTaxRuleUSEntity</a>|
|[PreTaxBasis](#PreTaxBasis)||<a href="PayrollBenefitTaxRuleUSEntity.md" target="_blank">Payroll/PayrollBenefitTaxRuleUSEntity</a>|
|[TaxGroup](#TaxGroup)||<a href="PayrollBenefitTaxRuleUSEntity.md" target="_blank">Payroll/PayrollBenefitTaxRuleUSEntity</a>|
|[BenefitPlanID](#BenefitPlanID)||<a href="PayrollBenefitTaxRuleUSEntity.md" target="_blank">Payroll/PayrollBenefitTaxRuleUSEntity</a>|
|[TaxGroupId](#TaxGroupId)||<a href="PayrollBenefitTaxRuleUSEntity.md" target="_blank">Payroll/PayrollBenefitTaxRuleUSEntity</a>|
|[Relationship_PayrollTaxGroupEntityRelationshipId](#Relationship_PayrollTaxGroupEntityRelationshipId)||<a href="PayrollBenefitTaxRuleUSEntity.md" target="_blank">Payroll/PayrollBenefitTaxRuleUSEntity</a>|
|[BackingTable_PayrollBenefitTaxRule_USRelationshipId](#BackingTable_PayrollBenefitTaxRule_USRelationshipId)||<a href="PayrollBenefitTaxRuleUSEntity.md" target="_blank">Payroll/PayrollBenefitTaxRuleUSEntity</a>|

### <a href=#BenefitPlan name="BenefitPlan">BenefitPlan</a>

First included in: Payroll/PayrollBenefitTaxRuleUSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BenefitPlan attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomPretaxMethod name="CustomPretaxMethod">CustomPretaxMethod</a>

First included in: Payroll/PayrollBenefitTaxRuleUSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomPretaxMethod attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsExemptFromFederalIncomeTax name="IsExemptFromFederalIncomeTax">IsExemptFromFederalIncomeTax</a>

First included in: Payroll/PayrollBenefitTaxRuleUSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsExemptFromFederalIncomeTax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsExemptFromFICA name="IsExemptFromFICA">IsExemptFromFICA</a>

First included in: Payroll/PayrollBenefitTaxRuleUSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsExemptFromFICA attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsExemptFromLocalIncomeTax name="IsExemptFromLocalIncomeTax">IsExemptFromLocalIncomeTax</a>

First included in: Payroll/PayrollBenefitTaxRuleUSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsExemptFromLocalIncomeTax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsExemptFromMedicare name="IsExemptFromMedicare">IsExemptFromMedicare</a>

First included in: Payroll/PayrollBenefitTaxRuleUSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsExemptFromMedicare attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsExemptFromStateDisabilityInsurance name="IsExemptFromStateDisabilityInsurance">IsExemptFromStateDisabilityInsurance</a>

First included in: Payroll/PayrollBenefitTaxRuleUSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsExemptFromStateDisabilityInsurance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsExemptFromStateIncomeTax name="IsExemptFromStateIncomeTax">IsExemptFromStateIncomeTax</a>

First included in: Payroll/PayrollBenefitTaxRuleUSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsExemptFromStateIncomeTax attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsExemptFromStateUnemployment name="IsExemptFromStateUnemployment">IsExemptFromStateUnemployment</a>

First included in: Payroll/PayrollBenefitTaxRuleUSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsExemptFromStateUnemployment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PreTaxBasis name="PreTaxBasis">PreTaxBasis</a>

First included in: Payroll/PayrollBenefitTaxRuleUSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PreTaxBasis attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxGroup name="TaxGroup">TaxGroup</a>

First included in: Payroll/PayrollBenefitTaxRuleUSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BenefitPlanID name="BenefitPlanID">BenefitPlanID</a>

First included in: Payroll/PayrollBenefitTaxRuleUSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BenefitPlanID attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxGroupId name="TaxGroupId">TaxGroupId</a>

First included in: Payroll/PayrollBenefitTaxRuleUSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PayrollTaxGroupEntityRelationshipId name="Relationship_PayrollTaxGroupEntityRelationshipId">Relationship_PayrollTaxGroupEntityRelationshipId</a>

First included in: Payroll/PayrollBenefitTaxRuleUSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PayrollTaxGroupEntityRelationshipId attribute are listed below.</summary>

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

### <a href=#BackingTable_PayrollBenefitTaxRule_USRelationshipId name="BackingTable_PayrollBenefitTaxRule_USRelationshipId">BackingTable_PayrollBenefitTaxRule_USRelationshipId</a>

First included in: Payroll/PayrollBenefitTaxRuleUSEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_PayrollBenefitTaxRule_USRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/HumanResources/Payroll/Reference/PayrollBenefitTaxRule_US.md" target="_blank">/core/operationsCommon/Tables/HumanResources/Payroll/Reference/PayrollBenefitTaxRule_US.cdm.json/PayrollBenefitTaxRule_US</a></td><td><a href="../../../Tables/HumanResources/Payroll/Reference/PayrollBenefitTaxRule_US.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
