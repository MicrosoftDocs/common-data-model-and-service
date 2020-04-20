---
title: JmgTimeAndAttendancePayCalculationPolicyEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/20/2020
ms.author: nebanfic
---

# JmgTimeAndAttendancePayCalculationPolicyEntity

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/ProductionControl/JmgTimeAndAttendancePayCalculationPolicyEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[ProfileSpecificationTypeCode](#ProfileSpecificationTypeCode)||<a href="JmgTimeAndAttendancePayCalculationPolicyEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendancePayCalculationPolicyEntity</a>|
|[RegistrationSpecificationType](#RegistrationSpecificationType)||<a href="JmgTimeAndAttendancePayCalculationPolicyEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendancePayCalculationPolicyEntity</a>|
|[IsIllegalAbsenceIncludedInCalculation](#IsIllegalAbsenceIncludedInCalculation)||<a href="JmgTimeAndAttendancePayCalculationPolicyEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendancePayCalculationPolicyEntity</a>|
|[IsLegalAbsenceIncludedInCalculation](#IsLegalAbsenceIncludedInCalculation)||<a href="JmgTimeAndAttendancePayCalculationPolicyEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendancePayCalculationPolicyEntity</a>|
|[IsFlexPlusIncludedInCalculation](#IsFlexPlusIncludedInCalculation)||<a href="JmgTimeAndAttendancePayCalculationPolicyEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendancePayCalculationPolicyEntity</a>|
|[IsFlexMinusIncludedInCalculation](#IsFlexMinusIncludedInCalculation)||<a href="JmgTimeAndAttendancePayCalculationPolicyEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendancePayCalculationPolicyEntity</a>|
|[IsOverTimeIncludedInCalculation](#IsOverTimeIncludedInCalculation)||<a href="JmgTimeAndAttendancePayCalculationPolicyEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendancePayCalculationPolicyEntity</a>|
|[IsPayTimeIncludedInCalculation](#IsPayTimeIncludedInCalculation)||<a href="JmgTimeAndAttendancePayCalculationPolicyEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendancePayCalculationPolicyEntity</a>|
|[IsStandardTimeIncludedInCalculation](#IsStandardTimeIncludedInCalculation)||<a href="JmgTimeAndAttendancePayCalculationPolicyEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendancePayCalculationPolicyEntity</a>|
|[IsAbsenceIncludedInPay](#IsAbsenceIncludedInPay)||<a href="JmgTimeAndAttendancePayCalculationPolicyEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendancePayCalculationPolicyEntity</a>|
|[IsPremiumIncludedInPay](#IsPremiumIncludedInPay)||<a href="JmgTimeAndAttendancePayCalculationPolicyEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendancePayCalculationPolicyEntity</a>|
|[IsBreakIncludedInPay](#IsBreakIncludedInPay)||<a href="JmgTimeAndAttendancePayCalculationPolicyEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendancePayCalculationPolicyEntity</a>|
|[IsFlexPlusIncludedInPay](#IsFlexPlusIncludedInPay)||<a href="JmgTimeAndAttendancePayCalculationPolicyEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendancePayCalculationPolicyEntity</a>|
|[IsFlexMinusIncludedInPay](#IsFlexMinusIncludedInPay)||<a href="JmgTimeAndAttendancePayCalculationPolicyEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendancePayCalculationPolicyEntity</a>|
|[IsOverTimeIncludedInPay](#IsOverTimeIncludedInPay)||<a href="JmgTimeAndAttendancePayCalculationPolicyEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendancePayCalculationPolicyEntity</a>|
|[IsPayTimeIncludedInPay](#IsPayTimeIncludedInPay)||<a href="JmgTimeAndAttendancePayCalculationPolicyEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendancePayCalculationPolicyEntity</a>|
|[BackingTable_JmgTimeCalcParmetersRelationshipId](#BackingTable_JmgTimeCalcParmetersRelationshipId)||<a href="JmgTimeAndAttendancePayCalculationPolicyEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendancePayCalculationPolicyEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="JmgTimeAndAttendancePayCalculationPolicyEntity.md" target="_blank">ProductionControl/JmgTimeAndAttendancePayCalculationPolicyEntity</a>|

### <a href=#ProfileSpecificationTypeCode name="ProfileSpecificationTypeCode">ProfileSpecificationTypeCode</a>

First included in: ProductionControl/JmgTimeAndAttendancePayCalculationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProfileSpecificationTypeCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RegistrationSpecificationType name="RegistrationSpecificationType">RegistrationSpecificationType</a>

First included in: ProductionControl/JmgTimeAndAttendancePayCalculationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RegistrationSpecificationType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsIllegalAbsenceIncludedInCalculation name="IsIllegalAbsenceIncludedInCalculation">IsIllegalAbsenceIncludedInCalculation</a>

First included in: ProductionControl/JmgTimeAndAttendancePayCalculationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsIllegalAbsenceIncludedInCalculation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsLegalAbsenceIncludedInCalculation name="IsLegalAbsenceIncludedInCalculation">IsLegalAbsenceIncludedInCalculation</a>

First included in: ProductionControl/JmgTimeAndAttendancePayCalculationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsLegalAbsenceIncludedInCalculation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsFlexPlusIncludedInCalculation name="IsFlexPlusIncludedInCalculation">IsFlexPlusIncludedInCalculation</a>

First included in: ProductionControl/JmgTimeAndAttendancePayCalculationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsFlexPlusIncludedInCalculation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsFlexMinusIncludedInCalculation name="IsFlexMinusIncludedInCalculation">IsFlexMinusIncludedInCalculation</a>

First included in: ProductionControl/JmgTimeAndAttendancePayCalculationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsFlexMinusIncludedInCalculation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsOverTimeIncludedInCalculation name="IsOverTimeIncludedInCalculation">IsOverTimeIncludedInCalculation</a>

First included in: ProductionControl/JmgTimeAndAttendancePayCalculationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsOverTimeIncludedInCalculation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPayTimeIncludedInCalculation name="IsPayTimeIncludedInCalculation">IsPayTimeIncludedInCalculation</a>

First included in: ProductionControl/JmgTimeAndAttendancePayCalculationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPayTimeIncludedInCalculation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsStandardTimeIncludedInCalculation name="IsStandardTimeIncludedInCalculation">IsStandardTimeIncludedInCalculation</a>

First included in: ProductionControl/JmgTimeAndAttendancePayCalculationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsStandardTimeIncludedInCalculation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsAbsenceIncludedInPay name="IsAbsenceIncludedInPay">IsAbsenceIncludedInPay</a>

First included in: ProductionControl/JmgTimeAndAttendancePayCalculationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsAbsenceIncludedInPay attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPremiumIncludedInPay name="IsPremiumIncludedInPay">IsPremiumIncludedInPay</a>

First included in: ProductionControl/JmgTimeAndAttendancePayCalculationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPremiumIncludedInPay attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsBreakIncludedInPay name="IsBreakIncludedInPay">IsBreakIncludedInPay</a>

First included in: ProductionControl/JmgTimeAndAttendancePayCalculationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsBreakIncludedInPay attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsFlexPlusIncludedInPay name="IsFlexPlusIncludedInPay">IsFlexPlusIncludedInPay</a>

First included in: ProductionControl/JmgTimeAndAttendancePayCalculationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsFlexPlusIncludedInPay attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsFlexMinusIncludedInPay name="IsFlexMinusIncludedInPay">IsFlexMinusIncludedInPay</a>

First included in: ProductionControl/JmgTimeAndAttendancePayCalculationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsFlexMinusIncludedInPay attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsOverTimeIncludedInPay name="IsOverTimeIncludedInPay">IsOverTimeIncludedInPay</a>

First included in: ProductionControl/JmgTimeAndAttendancePayCalculationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsOverTimeIncludedInPay attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPayTimeIncludedInPay name="IsPayTimeIncludedInPay">IsPayTimeIncludedInPay</a>

First included in: ProductionControl/JmgTimeAndAttendancePayCalculationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPayTimeIncludedInPay attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_JmgTimeCalcParmetersRelationshipId name="BackingTable_JmgTimeCalcParmetersRelationshipId">BackingTable_JmgTimeCalcParmetersRelationshipId</a>

First included in: ProductionControl/JmgTimeAndAttendancePayCalculationPolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_JmgTimeCalcParmetersRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/ProductionControl/Parameter/JmgTimeCalcParmeters.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductionControl/Parameter/JmgTimeCalcParmeters.cdm.json/JmgTimeCalcParmeters</a></td><td><a href="../../../Tables/SupplyChain/ProductionControl/Parameter/JmgTimeCalcParmeters.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: ProductionControl/JmgTimeAndAttendancePayCalculationPolicyEntity (this entity)  

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
