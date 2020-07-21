---
title: PayrollBenefitTaxRule_US in Reference - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/21/2020
ms.author: nebanfic
---

# Benefit Tax Rule US in Reference(PayrollBenefitTaxRule_US)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/HumanResources/Payroll/Reference/PayrollBenefitTaxRule_US.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PayrollBenefitTaxRule_US/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Benefit Tax Rule US</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="PayrollBenefitTaxRule_US.md" target="_blank">Reference/PayrollBenefitTaxRule_US</a>|
|[BenefitPlan](#BenefitPlan)||<a href="PayrollBenefitTaxRule_US.md" target="_blank">Reference/PayrollBenefitTaxRule_US</a>|
|[CustomPretaxMethod](#CustomPretaxMethod)||<a href="PayrollBenefitTaxRule_US.md" target="_blank">Reference/PayrollBenefitTaxRule_US</a>|
|[IsExemptFromFederalIncomeTax](#IsExemptFromFederalIncomeTax)||<a href="PayrollBenefitTaxRule_US.md" target="_blank">Reference/PayrollBenefitTaxRule_US</a>|
|[IsExemptFromFICA](#IsExemptFromFICA)||<a href="PayrollBenefitTaxRule_US.md" target="_blank">Reference/PayrollBenefitTaxRule_US</a>|
|[IsExemptFromLocalIncomeTax](#IsExemptFromLocalIncomeTax)||<a href="PayrollBenefitTaxRule_US.md" target="_blank">Reference/PayrollBenefitTaxRule_US</a>|
|[IsExemptFromMedicare](#IsExemptFromMedicare)||<a href="PayrollBenefitTaxRule_US.md" target="_blank">Reference/PayrollBenefitTaxRule_US</a>|
|[IsExemptFromStateDisabilityInsurance](#IsExemptFromStateDisabilityInsurance)||<a href="PayrollBenefitTaxRule_US.md" target="_blank">Reference/PayrollBenefitTaxRule_US</a>|
|[IsExemptFromStateIncomeTax](#IsExemptFromStateIncomeTax)||<a href="PayrollBenefitTaxRule_US.md" target="_blank">Reference/PayrollBenefitTaxRule_US</a>|
|[IsExemptFromStateUnemployment](#IsExemptFromStateUnemployment)||<a href="PayrollBenefitTaxRule_US.md" target="_blank">Reference/PayrollBenefitTaxRule_US</a>|
|[PreTaxBasis](#PreTaxBasis)||<a href="PayrollBenefitTaxRule_US.md" target="_blank">Reference/PayrollBenefitTaxRule_US</a>|
|[TaxGroup](#TaxGroup)||<a href="PayrollBenefitTaxRule_US.md" target="_blank">Reference/PayrollBenefitTaxRule_US</a>|
|[Relationship_PayrollTaxGroupRelationshipId](#Relationship_PayrollTaxGroupRelationshipId)||<a href="PayrollBenefitTaxRule_US.md" target="_blank">Reference/PayrollBenefitTaxRule_US</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Reference/PayrollBenefitTaxRule_US (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[PayrollBenefitTaxRule_US/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BenefitPlan name="BenefitPlan">BenefitPlan</a>

First included in: Reference/PayrollBenefitTaxRule_US (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BenefitPlan attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CustomPretaxMethod name="CustomPretaxMethod">CustomPretaxMethod</a>

First included in: Reference/PayrollBenefitTaxRule_US (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomPretaxMethod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#IsExemptFromFederalIncomeTax name="IsExemptFromFederalIncomeTax">IsExemptFromFederalIncomeTax</a>

First included in: Reference/PayrollBenefitTaxRule_US (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Federal income tax</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsExemptFromFederalIncomeTax attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Federal income tax</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#IsExemptFromFICA name="IsExemptFromFICA">IsExemptFromFICA</a>

First included in: Reference/PayrollBenefitTaxRule_US (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>FICA</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsExemptFromFICA attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>FICA</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#IsExemptFromLocalIncomeTax name="IsExemptFromLocalIncomeTax">IsExemptFromLocalIncomeTax</a>

First included in: Reference/PayrollBenefitTaxRule_US (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Local income tax</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsExemptFromLocalIncomeTax attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Local income tax</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#IsExemptFromMedicare name="IsExemptFromMedicare">IsExemptFromMedicare</a>

First included in: Reference/PayrollBenefitTaxRule_US (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Medicare</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsExemptFromMedicare attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Medicare</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#IsExemptFromStateDisabilityInsurance name="IsExemptFromStateDisabilityInsurance">IsExemptFromStateDisabilityInsurance</a>

First included in: Reference/PayrollBenefitTaxRule_US (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Disability insurance</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsExemptFromStateDisabilityInsurance attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Disability insurance</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#IsExemptFromStateIncomeTax name="IsExemptFromStateIncomeTax">IsExemptFromStateIncomeTax</a>

First included in: Reference/PayrollBenefitTaxRule_US (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>State income tax</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsExemptFromStateIncomeTax attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>State income tax</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#IsExemptFromStateUnemployment name="IsExemptFromStateUnemployment">IsExemptFromStateUnemployment</a>

First included in: Reference/PayrollBenefitTaxRule_US (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Unemployment</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsExemptFromStateUnemployment attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unemployment</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#PreTaxBasis name="PreTaxBasis">PreTaxBasis</a>

First included in: Reference/PayrollBenefitTaxRule_US (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PreTaxBasis attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#TaxGroup name="TaxGroup">TaxGroup</a>

First included in: Reference/PayrollBenefitTaxRule_US (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxGroup attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Relationship_PayrollTaxGroupRelationshipId name="Relationship_PayrollTaxGroupRelationshipId">Relationship_PayrollTaxGroupRelationshipId</a>

First included in: Reference/PayrollBenefitTaxRule_US (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PayrollTaxGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/PayrollTaxGroup.md" target="_blank">/core/operationsCommon/Tables/HumanResources/Payroll/Group/PayrollTaxGroup.cdm.json/PayrollTaxGroup</a></td><td><a href="../Group/PayrollTaxGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
