---
title: JmgTimeCalcParmeters in Parameter - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 7/7/2020
ms.author: nebanfic
---

# Calculation parameters in Parameter

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/ProductionControl/Parameter/JmgTimeCalcParmeters.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[JmgTimeCalcParmeters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Calculation parameters</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="JmgTimeCalcParmeters.md" target="_blank">Parameter/JmgTimeCalcParmeters</a>|
|[CalcAbsIllegalTime](#CalcAbsIllegalTime)||<a href="JmgTimeCalcParmeters.md" target="_blank">Parameter/JmgTimeCalcParmeters</a>|
|[CalcAbsLegalTime](#CalcAbsLegalTime)||<a href="JmgTimeCalcParmeters.md" target="_blank">Parameter/JmgTimeCalcParmeters</a>|
|[CalcFlexAddTime](#CalcFlexAddTime)||<a href="JmgTimeCalcParmeters.md" target="_blank">Parameter/JmgTimeCalcParmeters</a>|
|[CalcFlexSubTime](#CalcFlexSubTime)||<a href="JmgTimeCalcParmeters.md" target="_blank">Parameter/JmgTimeCalcParmeters</a>|
|[CalcPayOverTime](#CalcPayOverTime)||<a href="JmgTimeCalcParmeters.md" target="_blank">Parameter/JmgTimeCalcParmeters</a>|
|[CalcPayTime](#CalcPayTime)||<a href="JmgTimeCalcParmeters.md" target="_blank">Parameter/JmgTimeCalcParmeters</a>|
|[CalcWorkTime](#CalcWorkTime)||<a href="JmgTimeCalcParmeters.md" target="_blank">Parameter/JmgTimeCalcParmeters</a>|
|[PayOnAbsence](#PayOnAbsence)||<a href="JmgTimeCalcParmeters.md" target="_blank">Parameter/JmgTimeCalcParmeters</a>|
|[PayOnBonus](#PayOnBonus)||<a href="JmgTimeCalcParmeters.md" target="_blank">Parameter/JmgTimeCalcParmeters</a>|
|[PayOnBreak](#PayOnBreak)||<a href="JmgTimeCalcParmeters.md" target="_blank">Parameter/JmgTimeCalcParmeters</a>|
|[PayOnFlexAddTime](#PayOnFlexAddTime)||<a href="JmgTimeCalcParmeters.md" target="_blank">Parameter/JmgTimeCalcParmeters</a>|
|[PayOnFlexSubTime](#PayOnFlexSubTime)||<a href="JmgTimeCalcParmeters.md" target="_blank">Parameter/JmgTimeCalcParmeters</a>|
|[PayOnOverTime](#PayOnOverTime)||<a href="JmgTimeCalcParmeters.md" target="_blank">Parameter/JmgTimeCalcParmeters</a>|
|[PayOnPayTime](#PayOnPayTime)||<a href="JmgTimeCalcParmeters.md" target="_blank">Parameter/JmgTimeCalcParmeters</a>|
|[ProfileSpecType](#ProfileSpecType)||<a href="JmgTimeCalcParmeters.md" target="_blank">Parameter/JmgTimeCalcParmeters</a>|
|[StampTypeSpec](#StampTypeSpec)||<a href="JmgTimeCalcParmeters.md" target="_blank">Parameter/JmgTimeCalcParmeters</a>|
|[DataAreaId](#DataAreaId)||<a href="JmgTimeCalcParmeters.md" target="_blank">Parameter/JmgTimeCalcParmeters</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="JmgTimeCalcParmeters.md" target="_blank">Parameter/JmgTimeCalcParmeters</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Parameter/JmgTimeCalcParmeters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[JmgTimeCalcParmeters/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CalcAbsIllegalTime name="CalcAbsIllegalTime">CalcAbsIllegalTime</a>

First included in: Parameter/JmgTimeCalcParmeters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalcAbsIllegalTime attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CalcAbsLegalTime name="CalcAbsLegalTime">CalcAbsLegalTime</a>

First included in: Parameter/JmgTimeCalcParmeters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalcAbsLegalTime attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CalcFlexAddTime name="CalcFlexAddTime">CalcFlexAddTime</a>

First included in: Parameter/JmgTimeCalcParmeters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalcFlexAddTime attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CalcFlexSubTime name="CalcFlexSubTime">CalcFlexSubTime</a>

First included in: Parameter/JmgTimeCalcParmeters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalcFlexSubTime attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CalcPayOverTime name="CalcPayOverTime">CalcPayOverTime</a>

First included in: Parameter/JmgTimeCalcParmeters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalcPayOverTime attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CalcPayTime name="CalcPayTime">CalcPayTime</a>

First included in: Parameter/JmgTimeCalcParmeters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalcPayTime attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CalcWorkTime name="CalcWorkTime">CalcWorkTime</a>

First included in: Parameter/JmgTimeCalcParmeters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CalcWorkTime attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PayOnAbsence name="PayOnAbsence">PayOnAbsence</a>

First included in: Parameter/JmgTimeCalcParmeters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayOnAbsence attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PayOnBonus name="PayOnBonus">PayOnBonus</a>

First included in: Parameter/JmgTimeCalcParmeters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayOnBonus attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PayOnBreak name="PayOnBreak">PayOnBreak</a>

First included in: Parameter/JmgTimeCalcParmeters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayOnBreak attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PayOnFlexAddTime name="PayOnFlexAddTime">PayOnFlexAddTime</a>

First included in: Parameter/JmgTimeCalcParmeters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayOnFlexAddTime attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PayOnFlexSubTime name="PayOnFlexSubTime">PayOnFlexSubTime</a>

First included in: Parameter/JmgTimeCalcParmeters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayOnFlexSubTime attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PayOnOverTime name="PayOnOverTime">PayOnOverTime</a>

First included in: Parameter/JmgTimeCalcParmeters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayOnOverTime attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PayOnPayTime name="PayOnPayTime">PayOnPayTime</a>

First included in: Parameter/JmgTimeCalcParmeters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PayOnPayTime attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ProfileSpecType name="ProfileSpecType">ProfileSpecType</a>

First included in: Parameter/JmgTimeCalcParmeters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProfileSpecType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#StampTypeSpec name="StampTypeSpec">StampTypeSpec</a>

First included in: Parameter/JmgTimeCalcParmeters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StampTypeSpec attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Parameter/JmgTimeCalcParmeters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Parameter/JmgTimeCalcParmeters (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CompanyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
